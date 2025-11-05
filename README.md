# Jugando-en-la-Terminal-Bash---Warriors---Arena---2-PARTE-Niveles-6---10-

![Estado](https://img.shields.io/badge/estado-completado-22c55e)
![Niveles](https://img.shields.io/badge/niveles-6--10-6366f1)
![Tiempo](https://img.shields.io/badge/tiempo_aprox-~3_horas-0ea5e9)
![Fecha](https://img.shields.io/badge/fecha-05%2F10%2F2025-f59e0b)

Esta es la parte 2 de la practica de Ciberseguridad - Jugando en la Terminal  
**Práctica 1.1 - Bash Battle Arena**  
**Alumno:** Anthony Damián Córdova Cacay  
**Fecha:** 05/11/2025  
**Niveles completados:** 6-10  
**Tiempo aproximado:** 2 horas

---

## Dificultades encontradas y cómo las solucioné:

### Nivel 06 – `count_lines.sh`

- **Síntoma:** `wc -l` mostraba también el nombre del archivo (`3 test.txt`).  
  **Causa:** usé `wc -l test.txt` en lugar de redirección.  
  **Solución:** `wc -l < "$1"` para imprimir solo el número.

- **Síntoma:** “No archivo provided” no pasaba el check.  
  **Causa:** mensaje exacto exigido por el reto (cualquier variación falla).  
  **Solución:** imprimir exactamente `No archivo provided` y salir con `exit 1`.

- **Síntoma:** “Permission denied” al ejecutar.  
  **Causa:** faltaba permiso de ejecución.  
  **Solución:** `chmod +x count_lines.sh`.

---

### Nivel 07 – `sort_txt_by_size.sh`

- **Síntoma:** el archivo de salida aparecía en el ranking.  
  **Causa:** no excluí `sort_output.txt`.  
  **Solución:** `[[ "$f" == "$out" ]] && continue`.

- **Síntoma:** orden incorrecto (200 va antes que 30).  
  **Causa:** orden lexicográfico en vez de numérico.  
  **Solución:** `sort -k3,3n` (ordenar por la 3ª columna, numérico).

- **Síntoma:** el bucle iteraba literalmente `*.txt`.  
  **Causa:** no había `.txt` y el glob no se expandía.  
  **Solución:** `shopt -s nullglob` antes del `for f in *.txt; do ....`

---

### Nivel 08 – `search_logs.sh`

- **Síntoma:** imprimía líneas coincidentes, no solo nombres.  
  **Causa:** usé `grep` sin bandera adecuada.  
  **Solución:** `grep -F -l -- "$query" *.log` (literal, solo nombres).

- **Síntoma:** resultados duplicados o desordenados.  
  **Causa:** impresión directa en el bucle.  
  **Solución:** acumular y luego `sort` para salida consistente.

- **Síntoma:** error si no existían `.log`.  
  **Causa:** el glob `*.log` no coincidía con nada.  
  **Solución:** `shopt -s nullglob` o comprobar `[[ -f "$f" ]]`.

---

*Hasta aqui los problemas encontrados en la practica.*
