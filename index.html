<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>🎮 Cumple Minecraft - Gael</title>

<!-- PREVIEW -->
<meta property="og:title" content="🎮 Cumple de Gael">
<meta property="og:description" content="⛏️ Desbloqueá tu invitación gamer">
<meta property="og:image" content="https://angel-097-ux.github.io/CUMPLE-GAEL/preview.jpg">
<meta property="og:url" content="https://angel-097-ux.github.io/CUMPLE-GAEL/">

<style>
body{
margin:0;
overflow:hidden;
font-family:monospace;
color:white;
}

/* VIDEO */
video{
position:fixed;
width:100%;
height:100%;
object-fit:cover;
filter:brightness(0.5);
z-index:-2;
}

/* START */
#start{
position:fixed;
width:100%;
height:100%;
background:black;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
z-index:10;
}
#start h1{
color:#00ff00;
animation:blink 1s infinite;
}
@keyframes blink{50%{opacity:0;}}

/* FLOAT CARDS */
.card{
position:absolute;
left:50%;
transform:translateX(-50%);
background:rgba(0,0,0,0.7);
padding:15px;
border:2px solid #00ff00;
border-radius:10px;
box-shadow:0 0 20px #00ff00;
animation:float 3s infinite ease-in-out;
text-align:center;
}
@keyframes float{
0%,100%{transform:translate(-50%,0);}
50%{transform:translate(-50%,-10px);}
}

/* POSICIONES (NO TAPAN STEVE) */
#info{top:65%;}
#botones{top:80%;}

/* BOTONES */
button{
padding:12px;
margin:5px;
border:none;
background:#006600;
color:white;
border-radius:5px;
}

/* CONTADOR */
#contador{
margin-top:10px;
color:#00ffcc;
}

/* PROGRESO */
#barra{width:100%;height:10px;background:#222;margin-top:10px;}
#progreso{height:100%;width:0;background:#00ff00;}

/* BLOQUES */
.block{
width:70px;
height:70px;
background:#8B4513;
position:absolute;
}

/* CREEPER */
#creeper{
position:absolute;
bottom:0;
left:-100px;
width:80px;
transition:2s;
}

/* EXPLOSION */
#explosion{
position:absolute;
font-size:70px;
display:none;
}

/* FINAL */
#win{
display:none;
position:fixed;
top:50%;
left:50%;
transform:translate(-50%,-50%);
background:black;
padding:20px;
border:3px solid gold;
text-align:center;
box-shadow:0 0 30px gold;
}

/* PARTICULAS */
.pixel{
position:absolute;
width:6px;
height:6px;
background:#00ff00;
animation:up 6s linear infinite;
}
@keyframes up{
from{transform:translateY(100vh);}
to{transform:translateY(-10vh);}
}
</style>
</head>

<body>

<!-- START -->
<div id="start">
<h1>🎮 PRESS START 🎮</h1>
<button onclick="start()">INICIAR</button>
</div>

<!-- VIDEO -->
<video autoplay muted loop>
<source src="video-steve.mp4">
</video>

<!-- INFO -->
<div id="info" class="card">
<p>🧒 GAEL CUMPLE 7</p>
<p>📍 PIKARDIAS</p>
<p>📌 ARISTÓBULO 5424</p>
<p>📅 9 MAYO</p>
<p>⏰ 14:00 - 16:30</p>
<div id="contador"></div>
<div id="barra"><div id="progreso"></div></div>
</div>

<!-- BOTONES -->
<div id="botones" class="card">
<button onclick="playMusic()">🎵 Música</button>
<button onclick="startGame()">⛏️ Jugar</button>
</div>

<audio id="music" loop>
<source src="minecraft.mp3">
</audio>

<!-- CREEPER -->
<img id="creeper" src="https://i.imgur.com/7yUVEpL.png">

<div id="explosion">💥</div>

<!-- FINAL -->
<div id="win">
<h2>🏆 INVITACIÓN DESBLOQUEADA</h2>
<p>🎂 Cumple de Gael</p>
<p>📅 9 de Mayo</p>
<p>📍 Pikardias</p>
<button onclick="sendWhatsApp()">💬 Confirmar</button>
</div>

<script>

// TELEFONO
const telefono="549XXXXXXXXXX";

// START
function start(){
document.getElementById("start").style.display="none";
}

// MUSICA
function playMusic(){
document.getElementById("music").play();
}

// CONTADOR
const fecha=new Date("May 9, 2026 14:00:00").getTime();
setInterval(()=>{
let now=new Date().getTime();
let diff=fecha-now;
let d=Math.floor(diff/(1000*60*60*24));
let h=Math.floor((diff%(1000*60*60*24))/(1000*60*60));
let m=Math.floor((diff%(1000*60*60))/(1000*60));
let s=Math.floor((diff%(1000*60))/1000);
document.getElementById("contador").innerHTML=`⏳ ${d}D ${h}H ${m}M ${s}S`;
},1000);

// JUEGO
let total=6,count=0;

function startGame(){
count=0;
updateBar();

for(let i=0;i<total;i++){
let b=document.createElement("div");
b.className="block";
b.style.left=Math.random()*80+"vw";
b.style.top=Math.random()*70+"vh";
b.onclick=function(){
b.remove();
count++;
updateBar();
if(count>=total){finalGame();}
};
document.body.appendChild(b);
}
}

function updateBar(){
document.getElementById("progreso").style.width=(count/total*100)+"%";
}

// FINAL CON CREEPER
function finalGame(){

let c=document.getElementById("creeper");
let e=document.getElementById("explosion");

c.style.left="50%";
c.style.transform="translateX(-50%)";

setTimeout(()=>{

let rect=c.getBoundingClientRect();

e.style.left=rect.left+"px";
e.style.top=rect.top+"px";
e.style.display="block";

document.body.style.animation="shake 0.3s";

setTimeout(()=>{
c.style.display="none";
e.style.display="none";
document.getElementById("win").style.display="block";
},800);

},2000);
}

// WHATSAPP
function sendWhatsApp(){
let msg=encodeURIComponent("🎮 Confirmo asistencia al cumple de Gael");
window.open(`https://wa.me/${telefono}?text=${msg}`);
}

// PARTICULAS
for(let i=0;i<40;i++){
let p=document.createElement("div");
p.className="pixel";
p.style.left=Math.random()*100+"vw";
document.body.appendChild(p);
}

</script>

</body>
</html>