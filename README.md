# cafe-sargarmi
<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>کافه سرگرمی</title>

<link href="https://fonts.googleapis.com/css2?family=Vazirmatn:wght@300;400;700;900&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Vazirmatn',sans-serif;
}

body{
background:#050505;
overflow:hidden;
height:100vh;
color:white;
}

.container{
width:100%;
height:100vh;
display:flex;
align-items:center;
justify-content:center;
position:relative;
overflow:hidden;
}

.bg{
position:absolute;
width:100%;
height:100%;
background:
radial-gradient(circle at top right,#ff004c33,transparent 30%),
radial-gradient(circle at bottom left,#00eeff22,transparent 30%),
linear-gradient(to bottom,#050505,#111);
z-index:-2;
}

.blur{
position:absolute;
width:500px;
height:500px;
background:#ff004c;
filter:blur(180px);
opacity:.25;
border-radius:50%;
top:-100px;
right:-100px;
animation:move 8s infinite alternate;
}

.blur2{
position:absolute;
width:400px;
height:400px;
background:#00d9ff;
filter:blur(160px);
opacity:.2;
border-radius:50%;
bottom:-120px;
left:-100px;
animation:move2 10s infinite alternate;
}

@keyframes move{
100%{
transform:translate(-120px,80px);
}
}

@keyframes move2{
100%{
transform:translate(120px,-80px);
}
}

.card{
width:90%;
max-width:1100px;
height:650px;
background:rgba(255,255,255,.05);
backdrop-filter:blur(15px);
border:1px solid rgba(255,255,255,.1);
border-radius:35px;
display:flex;
overflow:hidden;
box-shadow:0 0 50px rgba(0,0,0,.6);
}

.left{
flex:1;
display:flex;
align-items:center;
justify-content:center;
padding:30px;
}

.left img{
width:100%;
max-width:450px;
animation:float 4s ease-in-out infinite;
filter:drop-shadow(0 0 30px #ff004c88);
}

@keyframes float{
50%{
transform:translateY(-15px);
}
}

.right{
flex:1;
padding:60px;
display:flex;
flex-direction:column;
justify-content:center;
}

.badge{
display:inline-block;
padding:10px 20px;
background:#ff004c22;
border:1px solid #ff004c66;
border-radius:50px;
color:#ff5e8d;
margin-bottom:25px;
font-size:14px;
width:max-content;
}

h1{
font-size:70px;
font-weight:900;
line-height:1.1;
margin-bottom:20px;
background:linear-gradient(45deg,#fff,#ffbf00);
-webkit-background-clip:text;
-webkit-text-fill-color:transparent;
}

p{
color:#d1d1d1;
line-height:2;
font-size:18px;
margin-bottom:30px;
}

.features{
display:grid;
grid-template-columns:repeat(2,1fr);
gap:15px;
margin-bottom:35px;
}

.feature{
background:rgba(255,255,255,.05);
border:1px solid rgba(255,255,255,.08);
padding:15px;
border-radius:18px;
font-size:15px;
transition:.3s;
}

.feature:hover{
transform:translateY(-5px);
background:#ffffff10;
}

.buttons{
display:flex;
gap:15px;
flex-wrap:wrap;
}

.btn{
padding:16px 35px;
border:none;
border-radius:18px;
font-size:17px;
font-weight:700;
cursor:pointer;
transition:.3s;
text-decoration:none;
display:flex;
align-items:center;
justify-content:center;
}

.primary{
background:linear-gradient(45deg,#ff004c,#ff7b00);
color:white;
box-shadow:0 0 25px #ff004c66;
}

.primary:hover{
transform:scale(1.05);
}

.secondary{
background:rgba(255,255,255,.08);
border:1px solid rgba(255,255,255,.08);
color:white;
}

.secondary:hover{
background:white;
color:black;
}

.socials{
margin-top:35px;
display:flex;
gap:15px;
}

.social{
width:55px;
height:55px;
background:rgba(255,255,255,.06);
border-radius:18px;
display:flex;
align-items:center;
justify-content:center;
font-size:24px;
transition:.3s;
cursor:pointer;
}

.social:hover{
transform:translateY(-5px);
background:#ff004c;
}

@media(max-width:950px){

body{
overflow:auto;
}

.card{
flex-direction:column;
height:auto;
margin:30px 0;
}

.right{
padding:35px;
}

h1{
font-size:50px;
}

.features{
grid-template-columns:1fr;
}

}

</style>
</head>

<body>

<div class="container">

<div class="bg"></div>
<div class="blur"></div>
<div class="blur2"></div>

<div class="card">

<div class="left">
<img src="logo.png">
</div>

<div class="right">

<div class="badge">
🔥 کانال رسمی کافه سرگرمی
</div>

<h1>
کافه سرگرمی
</h1>

<p>
به دنیای سرگرمی خوش اومدی 😎✨  
اینجا میتونی بهترین ویدیوها، ماشین بازی، مود ماینکرافت، میم، آهنگ فانکی، جوک و کلی محتوای خفن پیدا کنی 🚀
</p>

<div class="features">

<div class="feature">🚗 ماشین بازی و کلیپ خفن</div>

<div class="feature">🎮 مود بازی و ماینکرافت</div>

<div class="feature">😂 میم و جوک های داغ</div>

<div class="feature">🎵 آهنگ فانکی و ترند</div>

<div class="feature">📱 ترفند و برنامه های جذاب</div>

<div class="feature">🔥 محتوای روز و خاص</div>

</div>

<div class="buttons">

<a href="#" class="btn primary">
عضویت در کانال
</a>

<a href="#" class="btn secondary">
مشاهده ویدیوها
</a>

</div>

<div class="socials">

<div class="social">🎮</div>
<div class="social">🚗</div>
<div class="social">🔥</div>
<div class="social">🎵</div>

</div>

</div>

</div>

</div>

</body>
</html>