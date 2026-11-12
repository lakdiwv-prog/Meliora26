
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Meliora '26</title>
<style>
*{box-sizing:border-box}
body{
 margin:0;min-height:100vh;display:grid;place-items:center;
 padding:20px;font-family:Inter,Arial,sans-serif;color:#f6f7ff;
 background:radial-gradient(ellipse at top left,#382078 0%,transparent 45%),
 linear-gradient(145deg,#080817,#050611 65%,#11102b);
}
.shell{
 width:min(100%,540px);min-height:720px;padding:50px 25px 30px;
 border:1px solid #8054ff70;border-radius:30px;
 background:linear-gradient(145deg,#19193ae8,#08091df5);
 box-shadow:0 25px 70px #0009;
 display:flex;flex-direction:column;align-items:center;
}
.mark{
 font-size:40px;font-weight:900;letter-spacing:-10px;
 padding-right:10px;color:#ffbd32;
}
.line{height:2px;width:90px;background:linear-gradient(90deg,transparent,#ffbd32)}
.brand{display:flex;align-items:center;gap:20px}
h1{font-size:clamp(48px,10vw,70px);letter-spacing:-3px;margin:30px 0 8px}
h1 span{color:#ffbd32}
.subtitle{color:#abb0c9;letter-spacing:3px;font-size:12px}
nav{width:100%;display:grid;gap:18px;margin:auto 0}
.nav-card{
 display:flex;align-items:center;gap:17px;padding:22px;
 min-height:95px;text-decoration:none;color:white;
 border:1px solid #8054ff75;border-radius:20px;
 background:linear-gradient(110deg,#30245c,#101329);
 transition:.2s;
}
.nav-card:hover{transform:translateY(-4px);border-color:#ffbd32}
.icon{
 width:50px;height:50px;border-radius:15px;
 display:grid;place-items:center;font-size:25px;
 color:#ffcd67;background:#ffffff12;
}
.nav-title{font-size:20px;font-weight:750}
.nav-desc{font-size:12px;color:#aeb5cf;margin-top:5px}
.arrow{margin-left:auto;font-size:25px;color:#aaa}
footer{margin-top:35px;text-align:center;color:#999eb8}
footer .mark{margin:10px}
@media(max-width:420px){.shell{min-height:calc(100vh - 30px);padding:40px 18px 25px}}
</style>
</head>
<body>
<main class="shell">

 <div class="brand">
  <div class="line"></div>
  <div class="mark">MΛ</div>
  <div class="line"></div>
 </div>

 <h1>Meliora <span>'26</span></h1>
 <p class="subtitle">GATHER • CONNECT • CELEBRATE</p>

 <nav>
  <a href="attendance.html" class="nav-card">
   <div class="icon">✓</div>
   <div>
    <div class="nav-title">Attendance</div>
    <div class="nav-desc">Member check-in and attendance</div>
   </div>
   <div class="arrow">›</div>
  </a>

  <a href="games.html" class="nav-card">
   <div class="icon">🎮</div>
   <div>
    <div class="nav-title">Mini Games</div>
    <div class="nav-desc">Games and activities</div>
   </div>
   <div class="arrow">›</div>
  </a>
 </nav>

 <footer>
  <div class="brand">
   <div class="line"></div>
   <div class="mark">MΛ</div>
   <div class="line"></div>
  </div>
  MELIORA '26
 </footer>

</main>
</body>
</html>
