<!doctype html>

<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>JINWOO-CRASHER</title>
  <style>
    /* Reset & base */
    *{box-sizing:border-box;margin:0;padding:0}
    html,body{height:100%}
    body{
      font-family: 'Segoe UI', Roboto, Arial, sans-serif;
      background:#0b0b0b;
      color:#e6e6e6;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      display:flex;
      flex-direction:column;
      min-height:100vh;
      align-items:center;
      gap:18px;
      padding:24px;
    }/* gif header */
.hero-gif{width:100%;max-width:1000px;border-radius:8px;overflow:hidden}
.hero-gif img{display:block;width:100%;height:auto}

h1.title{
  font-size:26px;
  letter-spacing:2px;
  text-align:center;
  font-weight:700;
  margin-top:8px;
}

.subtitle{
  text-align:center;
  font-size:16px;
  opacity:0.9;
  margin-bottom:8px;
}

.repo{max-width:900px;width:100%;display:flex;flex-direction:column;align-items:center;gap:12px}
.repo img.thumb{border-radius:6px;max-width:420px;width:90%;height:auto;display:block}

.typing-wrap{margin-top:6px}

/* Glowing line pinned to the bottom of the page */
.glow-line{
  position:fixed; /* pinned to viewport bottom */
  left:0;
  bottom:0; /* show in the down */
  width:100%;
  height:8px; /* thickness of the glow line */
  pointer-events:none; /* doesn't block clicks */
  z-index:9999;
  background:linear-gradient(90deg, rgba(255,0,171,0.0) 0%, rgba(255,0,171,0.9) 20%, rgba(0,255,255,0.9) 50%, rgba(255,255,0,0.9) 80%, rgba(255,0,171,0.0) 100%);
  background-size:300% 100%;
  box-shadow:0 0 20px rgba(255,0,171,0.45), 0 0 40px rgba(0,255,255,0.25);
  animation:slideGlow 6s linear infinite;
  filter:drop-shadow(0 0 14px rgba(255,0,171,0.45));
}

/* optional soft upper glow (a thin blurred band a little above bottom) */
.glow-line::before{
  content:"";
  position:absolute;
  left:0;right:0;top:-6px;height:6px;
  background:linear-gradient(90deg, rgba(255,0,171,0.0) 0%, rgba(255,0,171,0.6) 25%, rgba(0,255,255,0.6) 50%, rgba(255,255,0,0.6) 75%, rgba(255,0,171,0.0) 100%);
  filter:blur(6px);
  opacity:0.9;
}

@keyframes slideGlow{
  0%{background-position:0% 50%}
  50%{background-position:100% 50%}
  100%{background-position:0% 50%}
}

/* small responsive niceties */
@media (max-width:640px){
  h1.title{font-size:20px}
  .subtitle{font-size:14px}
}

  </style>
</head>
<body>  <div class="hero-gif">
    <img src="https://i.imgur.com/dBaSKWF.gif" alt="Jinwoo gif">
  </div>  <h1 class="title">JINWOO-CRASHER💀</h1>
  <div class="subtitle">𝐒𝐢𝐦𝐩𝐥𝐞 𝐁𝐞𝐬𝐭 𝐖𝐡𝐚𝐭𝐬𝐚𝐩𝐩 𝐁𝐨𝐭 𝐂𝐫𝐞𝐚𝐭𝐞𝐝 𝐁𝐲 DAMINĪ🖤🥀</div>  <div class="repo" align="center">
    <a href="#">
      <img class="thumb" src="https://files.catbox.moe/t4o3iq.png" alt="thumb">
    </a><p class="typing-wrap">
  <img src="http://readme-typing-svg.herokuapp.com?color=ff00ab&center=true&vCenter=true&multiline=false&lines=JINWOO+CRASHER+WHATSAPP+BOT" alt="typing">
</p>

  </div>  <!-- glowing line fixed to the bottom of the viewport -->  <div class="glow-line" aria-hidden="true"></div></body>
</html>
