<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Perfil – Ana Regina</title>
  <style>
    :root{
      --bg:#0f1724; 
      --card:#0b1220; 
      --muted:#9aa5b1; 
      --accent:#7dd3fc;
      --glass: rgba(255,255,255,0.03);
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    body{
      margin:0; 
      background:linear-gradient(180deg,#071028 0%, #0b1220 60%);
      color:#e6eef6; 
      padding:28px;
    }
    .wrap{
      max-width:1100px;
      margin:0 auto;
      display:grid;
      grid-template-columns:1fr;
      gap:20px;
    }
    .card{
      background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border:1px solid rgba(255,255,255,0.04); 
      padding:20px; 
      border-radius:14px; 
      box-shadow:0 6px 20px rgba(2,6,23,0.6);
    }
    h1,h2,h3{
      margin-top:0;
    }
    .chip{
      background:var(--glass);
      padding:6px 10px;
      border-radius:999px;
      border:1px solid rgba(255,255,255,0.04);
      margin-right:8px;
      font-size:0.9rem;
      color:var(--muted);
    }
    img.banner{
      width:100%;
      border-radius:10px;
      margin-bottom:20px;
      border:1px solid rgba(255,255,255,0.1);
    }
    a{
      color:var(--accent);
      text-decoration:none;
      font-weight:600;
    }
  </style>
</head>

<body>
  <main class="wrap">

    <!-- Hola -->
    <div class="card">
      <h1>Hola Mundito :3 ✨</h1>
      <img class="banner" src="https://raw.githubusercontent.com/TU_USUARIO_GITHUB/TU_USUARIO_GITHUB/main/BannerUno.png" alt="Banner">
    </div>

    <!-- Sobre mí -->
    <section class="card">
      <h2>🌸 Sobre mí</h2>

      <h3>💬 Lenguajes que uso</h3>
      <div>
        <span class="chip">Dart</span>
        <span class="chip">Flutter</span>
        <span class="chip">Java</span>
        <span class="chip">PHP</span>
        <span class="chip">React</span>
      </div>

      <h3 style="margin-top:20px;">🎓 Especialidad</h3>
      <p><strong>Ciencia de Datos</strong></p>

      <h3 style="margin-top:20px;">🏅 Certificaciones</h3>
      <p>Puedes ver todas mis certificaciones aquí:</p>
      <p>
        <a href="https://www.linkedin.com/in/ana-regina-jaramillo-pineda-251ba233a/" target="_blank">
          Mi perfil de LinkedIn
        </a>
      </p>

      <h3 style="margin-top:20px;">💬 Mi Discord</h3>
      <p>
        <a href="https://discordapp.com/users/kodokunigamixx" target="_blank">
          kodokunigamixx
        </a>
      </p>
    </section>

    <!-- Música -->
    <section class="card">
      <h2>🎵 Música que estoy escuchando ahora</h2>
      <p>Mi música en tiempo real desde YouTube Music → Last.fm:</p>

      <img 
        src="https://lastfm-recently-played.vercel.app/api?user=AnaReginaXX&width=450" 
        alt="Now Playing"
      >
    </section>

    <!-- Steam -->
    <section class="card">
      <h2>🎮 Lo que estoy jugando en Steam</h2>

      <p>Estado actual de Steam:</p>

      <img 
        src="https://steam-stat.vercel.app/api/status/76561199202911474" 
        alt="Steam Status"
      >

      <p style="margin-top:20px;">Mi perfil:</p>
      <a href="https://steamcommunity.com/profiles/76561199202911474/" target="_blank">
        <img 
          src="https://steam-stat.vercel.app/api/profile/76561199202911474" 
          alt="Steam Profile"
        >
      </a>
    </section>

  </main>
</body>
</html>
