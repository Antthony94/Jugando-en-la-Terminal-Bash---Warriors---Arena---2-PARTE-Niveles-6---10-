<!doctype html>
<html lang="es">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Jugando en la Terminal – Bash Battle Arena · Niveles 6–10</title>
<style>
  :root{
    --bg: #0b1220;
    --panel: #0f172a;
    --card: #111827;
    --text: #e5e7eb;
    --muted:#9ca3af;
    --primary:#6366f1;     /* indigo */
    --secondary:#22d3ee;   /* cyan 300 */
    --accent:#f59e0b;      /* amber 500 */
    --ok:#22c55e;          /* green 500 */
    --danger:#ef4444;      /* red 500 */
    --shadow: 0 10px 30px rgba(0,0,0,.35);
    --radius: 16px;
  }
  @media (prefers-color-scheme: light){
    :root{
      --bg:#f5f7fb; --panel:#ffffff; --card:#ffffff; --text:#0f172a; --muted:#6b7280;
      --shadow: 0 10px 30px rgba(0,0,0,.08);
    }
  }
  *{box-sizing:border-box}
  body{
    margin:0; background:linear-gradient(180deg,var(--bg),#0a0f1a);
    font-family: ui-sans-serif, -apple-system, Segoe UI, Roboto, "Helvetica Neue", Arial, "Noto Sans", "Liberation Sans", sans-serif;
    color:var(--text); line-height:1.6;
  }
  .hero{
    background: radial-gradient(1200px 400px at 10% -10%, rgba(99,102,241,.35), transparent),
                radial-gradient(1200px 400px at 90% -10%, rgba(34,211,238,.35), transparent),
                linear-gradient(180deg, #0b1220, #0d1324 60%);
    padding: 48px 24px 32px;
    border-bottom: 1px solid rgba(255,255,255,.06);
  }
  .wrap{max-width:1000px;margin:0 auto;padding:0 20px}
  h1{
    margin:0 0 6px; font-size: clamp(26px, 3.2vw, 40px); letter-spacing:.2px;
    font-weight:800; background:linear-gradient(90deg,var(--secondary),var(--primary));
    -webkit-background-clip:text; background-clip:text; color:transparent;
  }
  .subtitle{color:var(--muted); margin:0 0 18px; font-size:clamp(14px,1.6vw,16px)}
  .meta{
    display:flex; flex-wrap:wrap; gap:10px;
  }
  .badge{
    display:inline-flex; align-items:center; gap:8px;
    background:rgba(99,102,241,.12); color:#c7d2fe; padding:8px 12px; border-radius:999px;
    border:1px solid rgba(99,102,241,.25);
  }
  .badge b{font-weight:700;color:#fff}
  .board{
    margin:24px auto; display:grid; gap:18px;
    grid-template-columns: 1fr;
  }
  @media(min-width:860px){ .board{ grid-template-columns: 1fr 1fr; } }
  .card{
    background:var(--card); border:1px solid rgba(255,255,255,.06);
    border-radius: var(--radius); box-shadow:var(--shadow); padding:18px 18px 16px;
  }
  .card h2{
    margin:0 0 8px; font-size:18px; font-weight:800;
    display:flex; align-items:center; gap:8px;
  }
  .pill{
    font-size:12px; font-weight:700; letter-spacing:.3px;
    padding:3px 8px; border-radius:999px; color:#0b1220; background:var(--secondary);
  }
  .list{margin:10px 0 0; padding:0; list-style:none; display:grid; gap:10px}
  .item{background:rgba(255,255,255,.03); border:1px dashed rgba(255,255,255,.08); padding:12px; border-radius:12px}
  .k{font-weight:800; color:#cbd5e1; text-transform:uppercase; letter-spacing:.5px; font-size:12px}
  .v{display:block; margin-top:4px}
  .footer{
    max-width:1000px; margin:30px auto 60px; padding:0 20px; color:var(--muted); font-size:14px
  }
  .callout{
    margin-top:14px; padding:10px 12px; border-radius:12px; background:rgba(245,158,11,.08);
    border:1px solid rgba(245,158,11,.25); color:#fde68a
  }
  code{font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;}
</style>
</head>
<body>
  <header class="hero">
    <div class="wrap">
      <h1>Jugando en la Terminal — Bash Battle Arena (Niveles 6–10)</h1>
      <p class="subtitle">Práctica 1.1 · Ciberseguridad · Warriors — Arena (Parte 2)</p>
      <div class="meta">
        <span class="badge">👤 <b>Alumno:</b> Anthony Damián Córdova Cacay</span>
        <span class="badge">📅 <b>Fecha:</b> 05/10/2025</span>
        <span class="badge">🏁 <b>Niveles:</b> 6–10</span>
        <span class="badge">⏱️ <b>Tiempo:</b> ~3 horas</span>
      </div>
      <div class="callout"><b>Nota:</b> Este informe recoge las dificultades reales encontradas y sus soluciones aplicadas durante la práctica.</div>
    </div>
  </header>

  <main class="wrap">
    <section style="margin:28px 0">
      <h2 style="margin:0 0 10px;font-size:22px">Dificultades encontradas y cómo las solucioné</h2>
      <p style="color:var(--muted);margin:0 0 16px">Resumen por nivel con <em>Síntoma → Causa → Solución</em>.</p>

      <div class="board">
        <!-- Nivel 06 -->
        <article class="card">
          <h2>🧮 Nivel 06 — <code>count_lines.sh</code> <span class="pill">OK</span></h2>
          <ul class="list">
            <li class="item">
              <span class="k">Síntoma</span><span class="v"> <code>wc -l</code> mostraba también el nombre del archivo (<code>3 test.txt</code>).</span>
              <span class="k">Causa</span><span class="v"> Usé <code>wc -l archivo</code> en lugar de redirección.</span>
              <span class="k">Solución</span><span class="v"> <code>wc -l &lt; "$1"</code> para imprimir solo el número.</span>
            </li>
            <li class="item">
              <span class="k">Síntoma</span><span class="v"> El mensaje “No archivo provided” no pasaba el check.</span>
              <span class="k">Causa</span><span class="v"> El reto exige el texto exacto.</span>
              <span class="k">Solución</span><span class="v"> Imprimir exactamente <code>No archivo provided</code> y <code>exit 1</code>.</span>
            </li>
            <li class="item">
              <span class="k">Síntoma</span><span class="v"> “Permission denied” al ejecutar.</span>
              <span class="k">Causa</span><span class="v"> Faltaba permiso de ejecución.</span>
              <span class="k">Solución</span><span class="v"> <code>chmod +x count_lines.sh</code>.</span>
            </li>
          </ul>
        </article>

        <!-- Nivel 07 -->
        <article class="card">
          <h2>📦 Nivel 07 — <code>sort_txt_by_size.sh</code> <span class="pill">OK</span></h2>
          <ul class="list">
            <li class="item">
              <span class="k">Síntoma</span><span class="v"> El archivo de salida aparecía en el ranking.</span>
              <span class="k">Causa</span><span class="v"> No excluí <code>sort_output.txt</code>.</span>
              <span class="k">Solución</span><span class="v"> <code>[[ "$f" == "$out" ]] &amp;&amp; continue</code>.</span>
            </li>
            <li class="item">
              <span class="k">Síntoma</span><span class="v"> Orden incorrecto (200 va antes que 30).</span>
              <span class="k">Causa</span><span class="v"> Orden lexicográfico.</span>
              <span class="k">Solución</span><span class="v"> <code>sort -k3,3n</code> para orden numérico por la 3ª columna.</span>
            </li>
            <li class="item">
              <span class="k">Síntoma</span><span class="v"> El bucle iteraba literalmente <code>*.txt</code>.</span>
              <span class="k">Causa</span><span class="v"> No había <code>.txt</code> y el glob no se expandía.</span>
              <span class="k">Solución</span><span class="v"> <code>shopt -s nullglob</code> antes del <code>for</code>.</span>
            </li>
          </ul>
        </article>

        <!-- Nivel 08 -->
        <article class="card">
          <h2>🔎 Nivel 08 — <code>search_logs.sh</code> <span class="pill">OK</span></h2>
          <ul class="list">
            <li class="item">
              <span class="k">Síntoma</span><span class="v"> Imprimía líneas coincidentes en lugar de solo nombres.</span>
              <span class="k">Causa</span><span class="v"> Usé <code>grep</code> sin bandera adecuada.</span>
              <span class="k">Solución</span><span class="v"> <code>grep -F -l -- "$query" *.log</code> (búsqueda literal, solo nombres).</span>
            </li>
            <li class="item">
              <span class="k">Síntoma</span><span class="v"> Resultados duplicados/desordenados.</span>
              <span class="k">Causa</span><span class="v"> Impresión directa dentro del bucle.</span>
              <span class="k">Solución</span><span class="v"> Acumular coincidencias y ordenar para salida consistente.</span>
            </li>
            <li class="item">
              <span class="k">Síntoma</span><span class="v"> Error si no existían <code>.log</code>.</span>
              <span class="k">Causa</span><span class="v"> El glob <code>*.log</code> no coincidía con nada.</span>
              <span class="k">Solución</span><span class="v"> <code>shopt -s nullglob</code> o comprobar <code>[[ -f "$f" ]]</code>.</span>
            </li>
          </ul>
        </article>

        <!-- Puedes añadir más tarjetas para niveles 09 y 10 cuando quieras -->
      </div>
    </section>
  </main>

  <footer class="footer">
    <p>© 2025 · Informe de práctica – Bash Battle Arena · Elaborado por Anthony Damián Córdova Cacay.</p>
  </footer>
</body>
</html>
