<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <title>Viewport Debug</title>

  <meta name="viewport" content="width=device-width, initial-scale=1" />

  <style>
    body {
      font-family: system-ui, -apple-system, BlinkMacSystemFont, sans-serif;
      background: #0f172a;
      color: #e5e7eb;
      margin: 0;
      padding: 16px;
    }

    h1 {
      font-size: 1.4rem;
      margin-bottom: 16px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 16px;
    }

    .card {
      background: #020617;
      border-radius: 12px;
      padding: 16px;
      box-shadow: 0 0 0 1px #1e293b inset;
    }

    .card h2 {
      font-size: 1rem;
      margin-bottom: 8px;
      color: #38bdf8;
    }

    .row {
      display: flex;
      justify-content: space-between;
      padding: 4px 0;
      font-size: 0.9rem;
    }

    .label {
      color: #94a3b8;
    }

    .value {
      font-weight: 600;
    }

    footer {
      margin-top: 24px;
      font-size: 0.8rem;
      color: #94a3b8;
    }
  </style>
</head>
<body>

  <h1>📐 Viewport Debug (tempo real)</h1>

  <div class="grid">

    <div class="card">
      <h2>Visual Viewport (viewport real)</h2>
      <div class="row">
        <span class="label">width</span>
        <span class="value" id="vv-width">—</span>
      </div>
      <div class="row">
        <span class="label">height</span>
        <span class="value" id="vv-height">—</span>
      </div>
      <div class="row">
        <span class="label">scale (zoom)</span>
        <span class="value" id="vv-scale">—</span>
      </div>
    </div>

    <div class="card">
      <h2>Layout Viewport (viewport mínima)</h2>
      <div class="row">
        <span class="label">innerWidth</span>
        <span class="value" id="lw-width">—</span>
      </div>
      <div class="row">
        <span class="label">innerHeight</span>
        <span class="value" id="lw-height">—</span>
      </div>
    </div>

    <div class="card">
      <h2>Document Element</h2>
      <div class="row">
        <span class="label">clientWidth</span>
        <span class="value" id="de-width">—</span>
      </div>
      <div class="row">
        <span class="label">clientHeight</span>
        <span class="value" id="de-height">—</span>
      </div>
    </div>

    <div class="card">
      <h2>Device / Input</h2>
      <div class="row">
        <span class="label">pointer</span>
        <span class="value" id="pointer">—</span>
      </div>
      <div class="row">
        <span class="label">hover</span>
        <span class="value" id="hover">—</span>
      </div>
      <div class="row">
        <span class="label">devicePixelRatio</span>
        <span class="value" id="dpr">—</span>
      </div>
    </div>

  </div>

  <footer>
    Dica: ative <strong>“Site para computador”</strong>, aplique zoom ou gire a tela para ver as diferenças.
  </footer>

  <script>
    function update() {
      const vv = window.visualViewport;

      if (vv) {
        document.getElementById("vv-width").textContent = vv.width.toFixed(2) + " px";
        document.getElementById("vv-height").textContent = vv.height.toFixed(2) + " px";
        document.getElementById("vv-scale").textContent = vv.scale.toFixed(2);
      } else {
        document.getElementById("vv-width").textContent = "não suportado";
        document.getElementById("vv-height").textContent = "não suportado";
        document.getElementById("vv-scale").textContent = "—";
      }

      document.getElementById("lw-width").textContent = window.innerWidth + " px";
      document.getElementById("lw-height").textContent = window.innerHeight + " px";

      document.getElementById("de-width").textContent =
        document.documentElement.clientWidth + " px";
      document.getElementById("de-height").textContent =
        document.documentElement.clientHeight + " px";

      document.getElementById("dpr").textContent = window.devicePixelRatio;

      document.getElementById("pointer").textContent =
        matchMedia("(pointer: coarse)").matches ? "coarse (touch)" : "fine (mouse)";

      document.getElementById("hover").textContent =
        matchMedia("(hover: hover)").matches ? "hover disponível" : "sem hover";
    }

    update();

    window.addEventListener("resize", update);
    window.visualViewport?.addEventListener("resize", update);
    window.visualViewport?.addEventListener("scroll", update);
  </script>

</body>
</html>
