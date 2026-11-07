<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#1a0b12">
<title>Happy Diwali | A Little Festival of Lights</title>
<link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="preload" as="style" href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@500;600;700&family=Manrope:wght@300;400;500;600&display=swap" onload="this.onload=null;this.rel='stylesheet'"><noscript><link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@500;600;700&family=Manrope:wght@300;400;500;600&display=swap"></noscript>
<style>
:root{--night:#1a0b12;--plum:#3b0f26;--gold:#ffc857;--orange:#ff8a1f;--cream:#fff4e0;--rose:#ff4f8b}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{margin:0;background:var(--night);color:var(--cream);font-family:Manrope,system-ui,sans-serif;overflow-x:hidden;-webkit-tap-highlight-color:transparent}
body.locked{overflow:hidden;height:100svh}
button{font:inherit;cursor:pointer;touch-action:manipulation}
button:focus-visible,a:focus-visible{outline:3px solid var(--gold);outline-offset:4px}
h1,h2,h3{font-family:"Dancing Script",cursive;font-weight:600;margin:0}
.gold{background:linear-gradient(180deg,#fff0b3,#ffc857 45%,#ff8a1f);-webkit-background-clip:text;background-clip:text;color:transparent;-webkit-text-fill-color:transparent}
.to{font-family:"Dancing Script",cursive;color:var(--gold);white-space:nowrap}
#fx{position:fixed;inset:0;width:100%;height:100%;pointer-events:none;z-index:20}
section{padding:90px 20px;text-align:center;position:relative}
.inner{width:min(100%,980px);margin:auto}
.kicker{font-size:.68rem;letter-spacing:.26em;text-transform:uppercase;color:var(--orange);margin:0 0 14px}
h2{font-size:clamp(2.8rem,8vw,5rem);line-height:1.05;margin:0 0 16px}
.lead{max-width:620px;margin:0 auto 30px;line-height:1.9;color:#e8cfb0;font-size:.95rem}
.btn{border:0;border-radius:999px;padding:13px 24px;background:linear-gradient(135deg,#ffc857,#ff8a1f);color:#3b0f26;font-weight:600;box-shadow:0 10px 28px #ff8a1f40;transition:transform .25s}
.btn:hover{transform:translateY(-3px)}
.btn.ghost{background:transparent;color:var(--gold);border:1px solid #ffc85788;box-shadow:none}
.hidden{display:none!important}
#gate{position:fixed;inset:0;z-index:100;display:grid;place-items:center;text-align:center;padding:28px;background:radial-gradient(ellipse at 50% 35%,#5a1a33 0,#2a0e1c 55%,#12060c 100%);transition:opacity 1.1s,transform 1.3s,visibility 1.3s}
#gate.leave{opacity:0;transform:scale(1.2);visibility:hidden;pointer-events:none}
#gate .stars{position:absolute;inset:0;overflow:hidden}
.star{position:absolute;width:3px;height:3px;border-radius:50%;background:#ffe6a8;animation:tw 3s ease-in-out infinite}
@keyframes tw{0%,100%{opacity:.15;transform:scale(.7)}50%{opacity:1;transform:scale(1.4)}}
.g-in{position:relative;max-width:520px}
.g-small{font:600 clamp(1.5rem,5.5vw,2.2rem)/1.3 "Dancing Script",cursive;color:#ffe6a8;min-height:1.4em;margin:12px 0 4px}
.g-big{font:700 clamp(3.6rem,17vw,7.5rem)/1 "Dancing Script",cursive;min-height:1.1em;margin:0 0 18px}
.g-line{font-size:.98rem;line-height:1.9;color:#f0d9bb;min-height:3.8em;margin:0 0 24px}
#gBtn{opacity:0;transform:translateY(10px);transition:.8s;pointer-events:none}
#gBtn.show{opacity:1;transform:none;pointer-events:auto}
.caret::after{content:"|";margin-left:2px;animation:blink 1s steps(1) infinite;-webkit-text-fill-color:#ffc857}
@keyframes blink{50%{opacity:0}}
.diya svg{width:100%;height:auto;display:block;overflow:visible}
.diya .flame{opacity:0;transform-origin:50% 90%;transform:scale(.2);transition:opacity .5s,transform .6s}
.diya .glow{opacity:0;transition:opacity .8s}
.diya.lit .flame{opacity:1;transform:scale(1);animation:flick 1.3s ease-in-out infinite .6s}
.diya.lit .glow{opacity:1}
@keyframes flick{0%,100%{transform:scale(1) rotate(-1deg)}50%{transform:scale(1.07,.95) rotate(2deg)}}
.gate-diya{width:120px;margin:0 auto}
.hero{min-height:100svh;display:grid;place-items:center;padding:70px 20px;text-align:center;background:radial-gradient(ellipse at 50% 15%,#6a2040 0,#3b0f26 42%,#1a0b12 100%);position:relative;overflow:hidden;isolation:isolate}
.hero:before{content:"";position:absolute;width:min(95vw,720px);aspect-ratio:1;border-radius:50%;z-index:-1;background:repeating-conic-gradient(from 0deg,#ffc8571f 0 6deg,transparent 6deg 18deg);-webkit-mask:radial-gradient(circle,transparent 18%,#000 19%,#000 62%,transparent 63%);mask:radial-gradient(circle,transparent 18%,#000 19%,#000 62%,transparent 63%);animation:spin 80s linear infinite}
.hero.off:before{animation-play-state:paused}
@keyframes spin{to{transform:rotate(360deg)}}
.lights{position:absolute;top:0;left:0;right:0;display:flex;justify-content:space-around;pointer-events:none}
.lights i{width:10px;height:10px;border-radius:50%;margin-top:14px;background:var(--gold);box-shadow:0 0 14px 3px #ffc857aa;animation:bulb 2.4s ease-in-out infinite}
.lights i:nth-child(2n){background:#ff8a1f;box-shadow:0 0 14px 3px #ff8a1faa;animation-delay:.6s}
.lights i:nth-child(3n){background:#ff4f8b;box-shadow:0 0 14px 3px #ff4f8baa;animation-delay:1.2s}
@keyframes bulb{0%,100%{opacity:1}50%{opacity:.35}}
.hero h1{font-size:clamp(4.2rem,16vw,9rem);line-height:.95}
.hero .name{font:700 clamp(2.6rem,10vw,5rem)/1.1 "Dancing Script",cursive;color:var(--gold);margin:6px 0 18px;text-shadow:0 0 24px #ff8a1f77}
.hero .sub{max-width:540px;margin:0 auto 28px;line-height:1.9;color:#f0d9bb;font-size:.96rem}
#wish{background:linear-gradient(180deg,#1a0b12,#2c1020)}
.env-wrap{width:min(90vw,440px);margin:34px auto 22px;perspective:1000px}
.envelope{height:260px;position:relative;background:#e8a24a;border-radius:4px 4px 12px 12px;box-shadow:0 25px 60px #00000066;cursor:pointer;isolation:isolate}
.envelope:before{content:"";position:absolute;inset:0;background:linear-gradient(145deg,#ffd98a,#f0a847);clip-path:polygon(0 0,50% 58%,100% 0);z-index:3;transform-origin:top;transition:transform 1s ease}
.envelope:after{content:"";position:absolute;inset:0;background:linear-gradient(35deg,#d88a2e,#f8c26a);clip-path:polygon(0 100%,0 0,50% 56%,100% 0,100% 100%);z-index:2}
.seal{position:absolute;z-index:4;left:50%;top:53%;transform:translate(-50%,-50%);width:50px;height:50px;border-radius:50%;background:#a3281f;color:#ffe6a8;display:grid;place-items:center;font-size:1.4rem;box-shadow:0 3px 10px #0006;transition:.4s}
.paper{position:absolute;z-index:1;left:7%;right:7%;bottom:5%;height:86%;background:#fff6e3;padding:24px 20px;text-align:center;display:flex;flex-direction:column;justify-content:center;color:#5a1a33;transition:transform 1s ease;overflow:hidden}
.paper strong{font:600 2.1rem "Dancing Script",cursive;color:#b4411f}
.paper strong .to{color:#b4411f}
.paper span{font-size:.74rem;line-height:1.6;margin-top:8px}
.envelope.open:before{transform:rotateX(180deg);z-index:0}
.envelope.open .seal{opacity:0;transform:translate(-50%,-50%) scale(.2)}
.envelope.open .paper{transform:translateY(-68px);height:100%;z-index:5;transition-delay:.35s}
.hint{font-size:.78rem;color:#c9a97f}
.letter{max-width:700px;margin:28px auto 0;padding:clamp(24px,5vw,46px);background:#fff6e3;color:#5a2a2a;border-radius:6px;box-shadow:0 18px 50px #0007;text-align:left;line-height:1.95;font-size:.96rem;border-top:6px solid var(--orange)}
.letter p{margin:0 0 1.15em}
.letter .sal,.letter .sig{font:600 2.1rem "Dancing Script",cursive;color:#b4411f;margin-bottom:.4em}
.letter .to{color:#b4411f}
#diyas{background:linear-gradient(180deg,#2c1020,#1a0b12)}
.diya-row{display:flex;flex-wrap:wrap;justify-content:center;gap:10px 8px;max-width:900px;margin:34px auto 12px}
.diya-row .diya{background:none;border:0;padding:0;width:min(23vw,104px);color:#e8cfb0;font-size:.74rem}
.diya-row .diya span{display:block;margin-top:4px}
.count{font-size:.8rem;color:#c9a97f;margin:6px 0 18px}
.wish-panel{max-width:600px;min-height:92px;margin:0 auto 26px;padding:20px 22px;border:1px solid #ffc85755;border-radius:20px;background:#ffffff0a;font:500 1.55rem/1.5 "Dancing Script",cursive;color:#ffe6a8}
#sweets{background:radial-gradient(ellipse at 50% 0,#4a1730 0,#1a0b12 70%)}
.sw-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:16px;max-width:960px;margin:34px auto}
.sw{background:#ffffff0a;border:1px solid #ffc85744;border-radius:22px;padding:28px 20px;min-height:200px;color:inherit;transition:transform .25s,background .25s}
.sw:hover{transform:translateY(-5px)}
.sw .em{font-size:3rem;display:block;margin-bottom:8px}
.sw h3{font-size:1.9rem;color:var(--gold);margin-bottom:8px}
.sw p{margin:0;font-size:.88rem;line-height:1.8;color:#e8cfb0}
.sw .back{display:none}
.sw.flip{background:#ffc85722}
.sw.flip .front{display:none}
.sw.flip .back{display:block}
#sky{min-height:90svh;display:grid;place-items:center;background:linear-gradient(180deg,#1a0b12,#0b0610 60%,#1a0b12);cursor:crosshair}
#blessing{min-height:100svh;display:grid;place-items:center;background:radial-gradient(ellipse at center,#6a2040 0,#33101f 55%,#12060c 100%)}
#blessing h2{font-size:clamp(3.2rem,12vw,7rem)}
.bless{max-width:640px;margin:22px auto;padding:30px 26px;border:1px solid #ffc85755;border-radius:22px;background:#ffffff0a;line-height:2;text-align:left}
.bless p{margin:0 0 1.1em}
.row{display:flex;flex-wrap:wrap;gap:12px;justify-content:center;margin-top:10px}
#toast{position:fixed;left:50%;bottom:26px;transform:translate(-50%,30px);background:#ffc857;color:#3b0f26;padding:10px 20px;border-radius:99px;font-size:.85rem;font-weight:600;opacity:0;transition:.4s;z-index:60;pointer-events:none;max-width:90vw;text-align:center}
#toast.on{opacity:1;transform:translate(-50%,0)}
footer{text-align:center;background:#0b0610;color:#b69a78;padding:24px;font-size:.74rem;letter-spacing:.04em}
.reveal{opacity:0;transform:translateY(24px);transition:opacity .85s ease,transform .85s ease}
.reveal.in{opacity:1;transform:none}
#places{position:fixed;right:12px;top:50%;transform:translateY(-50%);z-index:40;display:none;flex-direction:column;gap:12px}
body.entered #places{display:flex}
#places a{position:relative;width:11px;height:11px;border-radius:50%;border:1px solid var(--gold);background:#ffc85744;display:block;transition:.3s}
#places a.on{background:var(--gold);box-shadow:0 0 12px var(--gold);transform:scale(1.3)}
#places a span{position:absolute;right:20px;top:50%;transform:translateY(-50%);white-space:nowrap;font-size:.7rem;background:#1a0b12ee;color:var(--gold);padding:4px 10px;border-radius:99px;opacity:0;pointer-events:none;transition:.25s}
#places a:hover span{opacity:1}
@media(max-width:700px){section{padding:72px 16px}#places{right:6px;gap:9px}#places a{width:8px;height:8px}#places a span{display:none}.hero:before{animation:none}.reveal{transition-duration:.55s}}
@media(prefers-reduced-motion:reduce){*,*::before,*::after{animation-duration:.01ms!important;animation-iteration-count:1!important;transition-duration:.01ms!important;scroll-behavior:auto!important}}
</style>
</head>
<body class="locked">
<canvas id="fx" aria-hidden="true"></canvas>

<div id="gate" role="dialog" aria-label="Welcome">
  <div class="stars" id="stars" aria-hidden="true"></div>
  <div class="g-in">
    <div class="diya gate-diya" id="gateDiya" aria-hidden="true"></div>
    <p class="g-small" id="gSmall"></p>
    <h1 class="g-big gold caret" id="gBig"></h1>
    <p class="g-line" id="gLine"></p>
    <button class="btn" id="gBtn" onclick="lightGate()">Light the diya 🪔</button>
  </div>
</div>
<nav id="places" aria-label="Places on this page"></nav>

<header class="hero">
  <div class="lights" id="lights" aria-hidden="true"></div>
  <div>
    <p class="kicker">Shubh Deepavali</p>
    <h1 class="gold">Happy Diwali</h1>
    <div class="name"><span class="to" data-to>Monisha</span> 🪔</div>
    <p class="sub">May this festival of lights fill your world with warmth, sweetness, and a glow that lasts all year. I made you a little place to celebrate it.</p>
    <button class="btn" onclick="goTo('wish')">Open your Diwali wish ✉</button>
  </div>
</header>

<main>
<section id="wish">
  <div class="inner">
    <p class="kicker">The Wish</p>
    <h2 class="gold">A letter of light</h2>
    <p class="lead">Tap the envelope to open it. Read it slowly, like a quiet evening with a diya.</p>
    <div class="env-wrap"><div class="envelope" id="env" role="button" tabindex="0" aria-label="Open the letter" onclick="openEnv()" onkeydown="if(event.key==='Enter'||event.key===' '){event.preventDefault();openEnv()}">
      <div class="paper"><strong>For <span class="to" data-to>Monisha</span></strong><span>A few words for your Diwali, whenever you need them. 🪔</span></div>
      <div class="seal">🪔</div>
    </div></div>
    <p class="hint" id="hint">Tap the envelope to open your wish</p>
    <article class="letter hidden" id="letter">
      <div class="sal">My dear <span class="to" data-to>Monisha</span>,</div>
      <p>Diwali is the festival of lights, and honestly, you are the light I'm most grateful for. 🪔</p>
      <p>This year I wanted to wish you something more than a quick forwarded message, so I made you a little world of diyas, sweets, and fireworks.</p>
      <p>May every diya you light carry away a worry. May your home glow with happiness, your heart with peace, and your dreams with success.</p>
      <p>May this Diwali bring you good health, sweet moments, laughter that fills every room, and the kind of luck that follows you all year long.</p>
      <p>Thank you for the warmth you bring, and for every day you make better just by being you.</p>
      <div class="sig">Happy Diwali, my Angel ✨</div>
    </article>
    <button class="btn" style="margin-top:28px" onclick="goTo('diyas')">Light the diyas ↓</button>
  </div>
</section>

<section id="diyas">
  <div class="inner">
    <p class="kicker">The Diyas</p>
    <h2 class="gold">Light seven wishes</h2>
    <p class="lead">Each diya holds a wish for you. Tap one to light it, and watch the room glow brighter.</p>
    <div class="diya-row" id="diyaRow"></div>
    <p class="count" id="count">0 of 7 lit</p>
    <div class="wish-panel" id="wishPanel" aria-live="polite">Tap a diya to light it 🪔</div>
    <button class="btn" onclick="goTo('sweets')">On to the sweets 🍬</button>
  </div>
</section>

<section id="sweets">
  <div class="inner">
    <p class="kicker">Sweet Wishes</p>
    <h2 class="gold">The best part of Diwali</h2>
    <p class="lead">Tap a card to unwrap it.</p>
    <div class="sw-grid">
      <button class="sw" onclick="this.classList.toggle('flip')"><span class="front"><span class="em">🍬</span><h3>Ladoos</h3><small>Tap to unwrap</small></span><span class="back"><h3>Sweet life</h3><p>May your life be as sweet as the first bite, and may you never run out of seconds.</p></span></button>
      <button class="sw" onclick="this.classList.toggle('flip')"><span class="front"><span class="em">🎨</span><h3>Rangoli</h3><small>Tap to unwrap</small></span><span class="back"><h3>Colourful days</h3><p>May your days be as colourful as the patterns at your doorstep, and every path lead to joy.</p></span></button>
      <button class="sw" onclick="this.classList.toggle('flip')"><span class="front"><span class="em">🎆</span><h3>Crackers</h3><small>Tap to unwrap</small></span><span class="back"><h3>Bright sparks</h3><p>May every worry go up in sparks, and every happy moment shine just as bright.</p></span></button>
      <button class="sw" onclick="this.classList.toggle('flip')"><span class="front"><span class="em">👗</span><h3>New clothes</h3><small>Tap to unwrap</small></span><span class="back"><h3>Dazzling you</h3><p>May you look stunning this Diwali, though honestly, you always do. 😉</p></span></button>
    </div>
    <button class="btn" onclick="goTo('sky')">Look at the sky 🎆</button>
  </div>
</section>

<section id="sky">
  <div class="inner">
    <p class="kicker">The Sky</p>
    <h2 class="gold">Tap the sky</h2>
    <p class="lead">Every tap here launches a firework. Make a wish on each one.</p>
    <div class="row"><button class="btn" onclick="show()">Launch fireworks 🎆</button><button class="btn ghost" onclick="goTo('blessing')">Final blessing ↓</button></div>
  </div>
</section>

<section id="blessing">
  <div class="inner">
    <p class="kicker">Blessings</p>
    <span style="font-size:3.4rem;display:block">🪔</span>
    <h2 class="gold">Shubh Deepavali</h2>
    <div class="bless">
      <p><span class="to" data-to>Monisha</span>, may the light of Diwali chase away every shadow, and may every corner of your life glow with joy.</p>
      <p>May you be healthy, loved, and proud of how far you've come. May this year bring you the things you've been quietly hoping for.</p>
      <p>And wherever you are tonight, know that someone is thinking of you, smiling, and wishing you the happiest Diwali ever. 🧡</p>
      <p style="font:600 2rem 'Dancing Script',cursive;color:#ffc857;margin:0;text-align:center">Happy Diwali! ✨</p>
    </div>
    <div class="row"><button class="btn" onclick="shareWish()">Share this wish 🪔</button><button class="btn ghost" onclick="show()">Light it up again ✨</button></div>
  </div>
</section>
</main>

<footer>Made with love for the festival of lights · Happy Diwali 🪔</footer>
<div id="toast" role="status"></div>

<script>
/* Who is this wish for? Change "Monisha" below, or share the link as  index.html?to=Name */
const TO=(new URLSearchParams(location.search).get("to")||"Monisha").slice(0,24);
document.querySelectorAll("[data-to]").forEach(e=>e.textContent=TO);
document.title="Happy Diwali, "+TO+" | A Little Festival of Lights";

const DIYA=`<svg viewBox="0 0 100 90" aria-hidden="true"><defs>
<radialGradient id="g%"><stop offset="0" stop-color="#ffd36b" stop-opacity=".85"/><stop offset="1" stop-color="#ff8a1f" stop-opacity="0"/></radialGradient>
<linearGradient id="b%" x1="0" x2="0" y1="0" y2="1"><stop offset="0" stop-color="#ff9a3c"/><stop offset="1" stop-color="#b4411f"/></linearGradient>
<linearGradient id="f%" x1="0" x2="0" y1="0" y2="1"><stop offset="0" stop-color="#fff6c2"/><stop offset=".5" stop-color="#ffc857"/><stop offset="1" stop-color="#ff6a1f"/></linearGradient></defs>
<circle class="glow" cx="50" cy="38" r="46" fill="url(#g%)"/>
<path class="flame" d="M50 6 C60 20 63 31 50 44 C37 31 40 20 50 6Z" fill="url(#f%)"/>
<path d="M8 50 Q50 88 92 50 Q50 60 8 50Z" fill="url(#b%)"/>
<ellipse cx="50" cy="50" rx="42" ry="7" fill="#ffb347"/><ellipse cx="50" cy="51" rx="34" ry="4.5" fill="#7a2c14"/>
<rect x="48.5" y="42" width="3" height="9" rx="1.5" fill="#3a1a10"/></svg>`;
let uid=0;const mkDiya=()=>DIYA.replace(/%/g,++uid);
document.getElementById("gateDiya").innerHTML=mkDiya();
const WISHES=[["Health","May you stay strong, healthy, and full of energy, every single day of the year."],["Happiness","May small things make you smile, and big things make you glow."],["Success","May every dream you're chasing come a little closer this year."],["Love","May you always be surrounded by people who treat you with care and respect."],["Peace","May your mind be calm, your heart light, and your nights restful."],["Prosperity","May your home be full of blessings, and your days full of good fortune."],["Laughter","May laughter be loud, frequent, and the reason for your best memories."]];
let lit=0;
const row=document.getElementById("diyaRow");
WISHES.forEach(w=>{
  const b=document.createElement("button");b.type="button";b.className="diya";b.setAttribute("aria-label","Light the diya of "+w[0]);
  b.innerHTML=mkDiya()+"<span>"+w[0]+"</span>";
  b.onclick=()=>{
    document.getElementById("wishPanel").textContent=w[1];
    if(!b.classList.contains("lit")){
      b.classList.add("lit");lit++;document.getElementById("count").textContent=lit+" of 7 lit";
      const r=b.getBoundingClientRect();boom(r.left+r.width/2,r.top+r.height*.3,"#ffc857");
      if(lit===7)setTimeout(()=>{show();toast("All seven diyas are lit. Happy Diwali! ✨")},500);
    }
  };
  row.appendChild(b);
});

(function(){
  const L=document.getElementById("lights");for(let i=0;i<14;i++)L.appendChild(document.createElement("i"));
  const st=document.getElementById("stars");for(let i=0;i<55;i++){const d=document.createElement("i");d.className="star";d.style.left=Math.random()*100+"%";d.style.top=Math.random()*100+"%";d.style.animationDelay=Math.random()*3+"s";st.appendChild(d)}
})();

(function(){
  const calm=matchMedia("(prefers-reduced-motion: reduce)").matches;
  const w=ms=>new Promise(r=>setTimeout(r,calm?0:ms));
  const small=document.getElementById("gSmall"),big=document.getElementById("gBig"),line=document.getElementById("gLine"),btn=document.getElementById("gBtn");
  async function type(el,t,sp){el.textContent="";for(const c of t){el.textContent+=c;await w(sp)}}
  (async()=>{
    await w(600);await type(small,"Happy Diwali to you,",55);await w(300);await type(big,TO,100);
    big.classList.remove("caret");
    for(const l of ["Someone lit a little world, just for you.","Light the diya to step inside."]){await type(line,l,34);await w(900)}
    btn.classList.add("show");btn.focus({preventScroll:true});
  })();
})();
function lightGate(){
  document.getElementById("gateDiya").classList.add("lit");
  document.getElementById("gBtn").classList.remove("show");
  setTimeout(()=>{
    document.getElementById("gate").classList.add("leave");
    document.body.classList.remove("locked");document.body.classList.add("entered");
    window.scrollTo(0,0);startFx();show();
    setTimeout(()=>{const g=document.getElementById("gate");g&&g.remove()},1600);
  },1100);
}

(function(){
  const els=document.querySelectorAll(".inner > *, .hero > div:last-child");
  const io="IntersectionObserver" in window?new IntersectionObserver(es=>es.forEach(e=>{if(e.isIntersecting){e.target.classList.add("in");io.unobserve(e.target)}}),{threshold:.12}):null;
  els.forEach(el=>{el.classList.add("reveal");io?io.observe(el):el.classList.add("in")});
  const N={wish:"The Wish",diyas:"The Diyas",sweets:"Sweet Wishes",sky:"The Sky",blessing:"Blessings"},nav=document.getElementById("places");
  Object.keys(N).forEach(id=>{const a=document.createElement("a");a.href="#"+id;a.setAttribute("aria-label",N[id]);a.innerHTML="<span>"+N[id]+"</span>";a.dataset.id=id;a.onclick=e=>{e.preventDefault();goTo(id)};nav.appendChild(a)});
  if(io){
    const so=new IntersectionObserver(es=>es.forEach(e=>{if(e.isIntersecting)nav.querySelectorAll("a").forEach(a=>a.classList.toggle("on",a.dataset.id===e.target.id))}),{threshold:.4});
    Object.keys(N).forEach(id=>so.observe(document.getElementById(id)));
    const h=document.querySelector(".hero");new IntersectionObserver(es=>es.forEach(e=>h.classList.toggle("off",!e.isIntersecting))).observe(h);
  }
})();
function goTo(id){const t=document.getElementById(id);if(t)t.scrollIntoView({behavior:"smooth",block:"start"})}
function openEnv(){
  document.getElementById("env").classList.add("open");document.getElementById("hint").textContent="A little wish, just for you 🪔";
  setTimeout(()=>{const l=document.getElementById("letter");l.classList.remove("hidden");l.scrollIntoView({behavior:"smooth",block:"center"})},650);
}
function toast(m){const t=document.getElementById("toast");t.textContent=m;t.classList.add("on");clearTimeout(toast.t);toast.t=setTimeout(()=>t.classList.remove("on"),2600)}
async function shareWish(){
  const d={title:"Happy Diwali!",text:"A little Diwali wish, made just for you 🪔",url:location.href};
  try{if(navigator.share){await navigator.share(d);return}await navigator.clipboard.writeText(location.href);toast("Link copied. Send it to someone you love! 🪔")}catch(e){}
}

/* ---------- light shower + fireworks (one canvas = smooth on phones) ---------- */
const calm=matchMedia("(prefers-reduced-motion: reduce)").matches;
const fx=document.getElementById("fx"),ctx=fx.getContext("2d");
const small=innerWidth<700||/Mobi|Android/i.test(navigator.userAgent);
const DPR=Math.min(window.devicePixelRatio||1,small?1.5:2);
let VW=0,VH=0;
function resizeFx(){VW=innerWidth;VH=innerHeight;fx.width=Math.round(VW*DPR);fx.height=Math.round(VH*DPR)}
resizeFx();addEventListener("resize",resizeFx);
const LIM={names:small?10:18,glyphs:small?26:44,total:small?100:160,sparks:small?420:800};
const BASE={...LIM};
const NAMES=["Happy Diwali","Shubh Deepavali",TO,"Happy Diwali "+TO];
const NCOL=["#ffc857","#ff9f3a","#ffe08a"],GL=["✨","🪔","🏮","🧡","💛","⭐","✦"],GCOL=["#ffc857","#ffe08a","#ff9f3a","#ffffff"];
const FC=["#ffc857","#ff8a1f","#ff4f8b","#ffffff","#7bdff2","#b8f27b","#c58bff"];
const cache={};
function mk(w,h,draw){const c=document.createElement("canvas");c.width=Math.ceil(w*DPR);c.height=Math.ceil(h*DPR);const x=c.getContext("2d");x.scale(DPR,DPR);draw(x);return{c,w,h}}
function nameSprite(t,size,col){
  const k="n"+t+size+col;if(cache[k])return cache[k];
  const f=`600 ${size}px "Dancing Script",cursive`,m=document.createElement("canvas").getContext("2d");m.font=f;
  const tw=Math.ceil(m.measureText(t).width),pad=16,w=tw+pad*2,h=size*1.5+pad*2;
  return cache[k]=mk(w,h,x=>{x.font=f;x.textAlign="center";x.textBaseline="middle";x.fillStyle=col;x.shadowColor=col;x.shadowBlur=12;x.fillText(t,w/2,h/2);x.shadowBlur=0;x.fillText(t,w/2,h/2)});
}
function glyphSprite(g,size,col){
  const k="g"+g+size+col;if(cache[k])return cache[k];const w=size*1.6;
  return cache[k]=mk(w,w,x=>{x.font=`${size}px serif`;x.textAlign="center";x.textBaseline="middle";x.fillStyle=col;x.fillText(g,w/2,w/2)});
}
const pick=a=>a[Math.floor(Math.random()*a.length)];
const P=[],S=[],R=[];let nN=0,nG=0;
function add(p){if(P.length>=LIM.total)return;P.push(p);p.kind==="n"?nN++:nG++}
function makeName(){
  if(calm||nN>=LIM.names)return;
  add({kind:"n",s:nameSprite(pick(NAMES),pick(small?[22,30,40]:[24,34,46,58]),pick(NCOL)),x:Math.random()*VW,y:VH+50+Math.random()*80,vy:36+Math.random()*44,amp:12+Math.random()*30,fr:.5+Math.random()*.8,ph:Math.random()*6.28,rot:(Math.random()-.5)*.2,vr:(Math.random()-.5)*.1,am:.35+Math.random()*.3,age:0});
}
function makeGlow(burst){
  if(calm||(!burst&&nG>=LIM.glyphs))return;
  const size=Math.round((burst?16+Math.random()*24:12+Math.random()*20)/4)*4;
  add({kind:"g",s:glyphSprite(pick(GL),size,pick(GCOL)),x:Math.random()*VW,y:VH+30+(burst?Math.random()*240:0),vy:(burst?100:55)+Math.random()*(burst?140:90),amp:6+Math.random()*20,fr:.8+Math.random()*1.4,ph:Math.random()*6.28,rot:0,vr:(Math.random()-.5),am:.5+Math.random()*.4,age:0});
}
function boom(x,y,c){
  if(calm||!running)return;
  const n=Math.round((small?30:56)*Math.max(.5,qual)),col=c||pick(FC);
  for(let i=0;i<n&&S.length<LIM.sparks;i++){const a=Math.PI*2*i/n+Math.random()*.2,sp=60+Math.random()*(small?150:200);
    S.push({x,y,px:x,py:y,vx:Math.cos(a)*sp,vy:Math.sin(a)*sp,age:0,life:.9+Math.random()*.9,c:Math.random()<.2?"#ffffff":col})}
}
function rocket(x){R.push({x:x==null?VW*(.12+Math.random()*.76):x,y:VH+10,vy:-(VH*.9+Math.random()*VH*.25),ty:VH*(.16+Math.random()*.34),c:pick(FC),px:0,py:0})}
function show(){if(calm||!running)return;for(let i=0;i<(small?4:6);i++)setTimeout(()=>rocket(),i*320)}
let raf=0,last=0,tN=0,tG=0,running=false,qual=1,acc=0,fc=0,win=0;
function frame(t){
  raf=requestAnimationFrame(frame);
  const dt=Math.min((t-last)/1000||.016,.05);last=t;
  acc+=dt;if(++fc>=90){if(++win>2){const av=acc/fc;if(av>.028&&qual>.4)qual=Math.max(.4,qual*.8);else if(av<.02&&qual<1)qual=Math.min(1,qual/.85);LIM.names=Math.max(3,Math.round(BASE.names*qual));LIM.glyphs=Math.max(8,Math.round(BASE.glyphs*qual));LIM.total=Math.max(30,Math.round(BASE.total*qual));LIM.sparks=Math.max(150,Math.round(BASE.sparks*qual))}acc=0;fc=0}
  tN-=dt;if(tN<=0){makeName();tN=(small?.7:.45)/qual}
  tG-=dt;if(tG<=0){makeGlow(false);tG=(small?.2:.12)/qual}
  ctx.setTransform(1,0,0,1,0,0);ctx.clearRect(0,0,fx.width,fx.height);
  for(let i=P.length-1;i>=0;i--){
    const p=P[i];p.age+=dt;p.y-=p.vy*dt;p.rot+=p.vr*dt;
    if(p.y<-70){p.kind==="n"?nN--:nG--;P.splice(i,1);continue}
    const a=p.am*Math.min(1,p.age/.7)*Math.min(1,(p.y+60)/220),x=p.x+Math.sin(p.age*p.fr+p.ph)*p.amp,c=Math.cos(p.rot)*DPR,sn=Math.sin(p.rot)*DPR;
    ctx.globalAlpha=a;ctx.setTransform(c,sn,-sn,c,x*DPR,p.y*DPR);ctx.drawImage(p.s.c,-p.s.w/2,-p.s.h/2,p.s.w,p.s.h);
  }
  ctx.setTransform(DPR,0,0,DPR,0,0);ctx.lineCap="round";ctx.lineWidth=2;
  for(let i=R.length-1;i>=0;i--){
    const r=R[i];r.px=r.x;r.py=r.y;r.y+=r.vy*dt;
    ctx.globalAlpha=.9;ctx.strokeStyle="#ffe6a8";ctx.beginPath();ctx.moveTo(r.px,r.py);ctx.lineTo(r.x,r.y+10);ctx.stroke();
    if(r.y<=r.ty){boom(r.x,r.y,r.c);R.splice(i,1)}
  }
  for(let i=S.length-1;i>=0;i--){
    const s=S[i];s.age+=dt;if(s.age>s.life){S.splice(i,1);continue}
    s.px=s.x;s.py=s.y;s.vy+=130*dt;s.vx*=.985;s.x+=s.vx*dt;s.y+=s.vy*dt;
    ctx.globalAlpha=1-s.age/s.life;ctx.strokeStyle=s.c;ctx.beginPath();ctx.moveTo(s.px,s.py);ctx.lineTo(s.x,s.y);ctx.stroke();
  }
  ctx.globalAlpha=1;
}
function startFx(){
  if(calm||running)return;running=true;
  const go=()=>{last=performance.now();raf=requestAnimationFrame(frame)};
  Promise.race([document.fonts?document.fonts.load('600 30px "Dancing Script"'):0,new Promise(r=>setTimeout(r,1500))]).then(go,go);
  for(let i=0;i<5;i++)setTimeout(makeName,i*250);
  for(let i=0;i<(small?25:40);i++)setTimeout(()=>makeGlow(true),i*40);
}
document.addEventListener("visibilitychange",()=>{if(!running)return;if(document.hidden)cancelAnimationFrame(raf);else{last=performance.now();raf=requestAnimationFrame(frame)}});
document.addEventListener("pointerdown",e=>{
  if(!running||e.target.closest("button,a"))return;
  if(e.target.closest("#sky")){rocket(e.clientX);return}
  boom(e.clientX,e.clientY,"#ffc857");
},{passive:true});
</script>
</body>
</html>
