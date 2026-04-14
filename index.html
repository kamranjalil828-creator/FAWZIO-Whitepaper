<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Fawzio — Where Achievement Has No Price Tag</title>
<style>
*{margin:0;padding:0;box-sizing:border-box;}
html{scroll-behavior:smooth;overflow-x:hidden;}
body{
  font-family:'Segoe UI',system-ui,sans-serif;
  background:#FAFBFF;color:#0A0E2A;
  overflow-x:hidden;
}

/* CURSOR */
.cursor{position:fixed;width:12px;height:12px;border-radius:50%;pointer-events:none;z-index:9999;mix-blend-mode:multiply;transition:transform 0.1s;}
.cursor-trail{position:fixed;width:40px;height:40px;border-radius:50%;border:1.5px solid rgba(233,69,96,0.4);pointer-events:none;z-index:9998;transition:all 0.12s ease;}

/* NOISE TEXTURE OVERLAY */
body::before{
  content:'';position:fixed;inset:0;z-index:0;pointer-events:none;
  background-image:url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.03'/%3E%3C/svg%3E");
  opacity:0.4;
}

/* GRADIENT BLOBS - light mode */
.blobs{position:fixed;inset:0;z-index:0;pointer-events:none;overflow:hidden;}
.blob{position:absolute;border-radius:50%;animation:blobFloat linear infinite;}
.blob1{width:800px;height:800px;background:radial-gradient(circle,rgba(233,69,96,0.12),transparent 65%);top:-300px;left:-200px;animation-duration:25s;}
.blob2{width:600px;height:600px;background:radial-gradient(circle,rgba(79,140,255,0.1),transparent 65%);top:20%;right:-200px;animation-duration:30s;animation-delay:-10s;}
.blob3{width:700px;height:700px;background:radial-gradient(circle,rgba(255,196,0,0.1),transparent 65%);bottom:-250px;left:20%;animation-duration:22s;animation-delay:-6s;}
.blob4{width:500px;height:500px;background:radial-gradient(circle,rgba(0,200,150,0.08),transparent 65%);top:50%;right:10%;animation-duration:18s;animation-delay:-3s;}
@keyframes blobFloat{
  0%{transform:translate(0,0) scale(1);}
  33%{transform:translate(40px,-50px) scale(1.06);}
  66%{transform:translate(-40px,40px) scale(0.94);}
  100%{transform:translate(0,0) scale(1);}
}

/* NAV */
nav{
  position:fixed;top:0;left:0;right:0;z-index:100;
  display:flex;justify-content:space-between;align-items:center;
  padding:1.2rem 3rem;
  background:rgba(250,251,255,0.85);
  backdrop-filter:blur(0px);
  border-bottom:1px solid rgba(10,14,42,0.06);
  transition:all 0.4s;
}
nav.scrolled{background:rgba(250,251,255,0.97);border-bottom-color:rgba(10,14,42,0.1);}
.logo{
  font-size:1.7rem;font-weight:900;letter-spacing:-1px;
  color:#0A0E2A;position:relative;
}
.logo span{color:#E94560;}
.nav-links a{
  margin-left:2rem;color:#6B7A99;text-decoration:none;
  font-size:0.88rem;font-weight:500;transition:color 0.3s;
}
.nav-links a:hover{color:#0A0E2A;}
.nav-cta{
  margin-left:2rem;padding:0.6rem 1.4rem;
  background:#0A0E2A;color:#fff;border-radius:100px;
  font-size:0.85rem;font-weight:700;text-decoration:none;
  transition:transform 0.2s,background 0.2s;
}
.nav-cta:hover{background:#E94560;transform:translateY(-1px);}

/* HERO */
#hero{
  position:relative;z-index:1;
  min-height:100vh;
  display:flex;flex-direction:column;
  align-items:center;justify-content:center;
  text-align:center;padding:8rem 2rem 5rem;
}

.hero-eyebrow{
  display:inline-flex;align-items:center;gap:0.6rem;
  background:#fff;border:1px solid rgba(10,14,42,0.08);
  border-radius:100px;padding:0.5rem 1.2rem;
  font-size:0.78rem;font-weight:600;color:#6B7A99;
  margin-bottom:2.5rem;
  box-shadow:0 2px 12px rgba(10,14,42,0.06);
  animation:eyebrowIn 1s cubic-bezier(0.34,1.56,0.64,1) both;
}
.ey-dot{width:7px;height:7px;border-radius:50%;background:#00C896;animation:eyeDot 2s infinite;}
@keyframes eyeDot{0%,100%{opacity:1;transform:scale(1);}50%{opacity:0.4;transform:scale(1.5);}}

.hero-title{
  font-size:clamp(4rem,11vw,8rem);font-weight:900;
  line-height:0.9;letter-spacing:-5px;
  margin-bottom:2rem;
}
.ht-line{display:block;overflow:hidden;}
.ht-inner{
  display:block;
  animation:lineSlide 1s cubic-bezier(0.77,0,0.175,1) both;
}
.ht-inner.l1{animation-delay:0.1s;color:#0A0E2A;}
.ht-inner.l2{
  animation-delay:0.2s;
  background:linear-gradient(135deg,#E94560 0%,#F5A623 40%,#4F8CFF 80%,#00C896 100%);
  background-size:200%;
  -webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;
  animation:lineSlide 1s 0.2s cubic-bezier(0.77,0,0.175,1) both, gradMove 4s 1.2s linear infinite;
}
.ht-inner.l3{animation-delay:0.3s;color:#0A0E2A;}
@keyframes lineSlide{from{transform:translateY(110%);}to{transform:translateY(0);}}
@keyframes gradMove{0%{background-position:0%;}100%{background-position:200%;}}

.hero-sub{
  font-size:clamp(1rem,2vw,1.2rem);color:#6B7A99;
  max-width:540px;line-height:1.85;margin-bottom:3.5rem;
  animation:fadeUp 1s 0.5s both;
}
.hero-sub strong{color:#0A0E2A;font-weight:700;}

.hero-btns{
  display:flex;gap:1rem;flex-wrap:wrap;justify-content:center;
  margin-bottom:5rem;animation:fadeUp 1s 0.6s both;
}
.btn-dark{
  padding:1rem 2.5rem;background:#0A0E2A;color:#fff;
  border-radius:100px;font-size:1rem;font-weight:700;
  text-decoration:none;transition:all 0.3s;
  box-shadow:0 4px 20px rgba(10,14,42,0.2);
}
.btn-dark:hover{background:#E94560;transform:translateY(-3px);box-shadow:0 12px 35px rgba(233,69,96,0.35);}
.btn-light{
  padding:1rem 2.5rem;background:#fff;color:#0A0E2A;
  border-radius:100px;font-size:1rem;font-weight:700;
  border:1.5px solid rgba(10,14,42,0.12);
  text-decoration:none;transition:all 0.3s;
}
.btn-light:hover{border-color:#0A0E2A;transform:translateY(-3px);box-shadow:0 8px 25px rgba(10,14,42,0.1);}

/* FLOATING CARDS */
.hero-cards{
  display:flex;gap:1.5rem;flex-wrap:wrap;justify-content:center;
  animation:fadeUp 1s 0.7s both;
}
.hcard{
  background:#fff;border:1px solid rgba(10,14,42,0.08);
  border-radius:20px;padding:1.5rem 2rem;text-align:center;
  box-shadow:0 4px 20px rgba(10,14,42,0.06);
  animation:cardBreathe 5s ease-in-out infinite;
  transition:transform 0.4s cubic-bezier(0.34,1.56,0.64,1),box-shadow 0.4s;
}
.hcard:nth-child(2){animation-delay:-1.7s;}
.hcard:nth-child(3){animation-delay:-3.3s;}
.hcard:hover{transform:translateY(-12px) scale(1.04)!important;box-shadow:0 20px 50px rgba(10,14,42,0.12);}
@keyframes cardBreathe{0%,100%{transform:translateY(0);}50%{transform:translateY(-8px);}}
.hcard-num{font-size:2.4rem;font-weight:900;line-height:1;}
.hcard:nth-child(1) .hcard-num{color:#E94560;}
.hcard:nth-child(2) .hcard-num{color:#4F8CFF;}
.hcard:nth-child(3) .hcard-num{color:#F5A623;}
.hcard-lbl{font-size:0.74rem;color:#6B7A99;margin-top:0.4rem;font-weight:600;text-transform:uppercase;letter-spacing:1px;}

/* MARQUEE */
.marquee-wrap{position:relative;z-index:1;overflow:hidden;padding:1.2rem 0;background:#fff;border-top:1px solid rgba(10,14,42,0.06);border-bottom:1px solid rgba(10,14,42,0.06);}
.marquee-track{display:flex;gap:3rem;animation:mq 24s linear infinite;white-space:nowrap;}
.mq-item{font-size:0.8rem;font-weight:700;letter-spacing:2px;text-transform:uppercase;color:#C5CAD9;display:flex;align-items:center;gap:0.8rem;flex-shrink:0;}
.mq-dot{width:5px;height:5px;border-radius:50%;display:inline-block;}
@keyframes mq{from{transform:translateX(0);}to{transform:translateX(-50%);}}

/* SECTIONS */
.sec{position:relative;z-index:1;padding:8rem 2rem;}
.sec-in{max-width:1100px;margin:0 auto;}
.sec-alt{background:#fff;}

.eyebrow{font-size:0.72rem;font-weight:800;letter-spacing:3px;text-transform:uppercase;margin-bottom:1rem;display:block;}
.e-red{color:#E94560;}
.e-blue{color:#4F8CFF;}
.e-gold{color:#F5A623;}
.e-green{color:#00C896;}

.sec-title{font-size:clamp(2.2rem,5vw,3.8rem);font-weight:900;line-height:1.05;letter-spacing:-2px;margin-bottom:1.2rem;color:#0A0E2A;}
.sec-sub{font-size:1rem;color:#6B7A99;line-height:1.8;max-width:560px;}

/* CARDS GRID */
.cards3{display:grid;grid-template-columns:repeat(auto-fit,minmax(290px,1fr));gap:1.5rem;margin-top:3.5rem;}
.card{
  background:#fff;border:1px solid rgba(10,14,42,0.07);
  border-radius:24px;padding:2.2rem;
  transition:all 0.5s cubic-bezier(0.34,1.56,0.64,1);
  box-shadow:0 2px 12px rgba(10,14,42,0.04);
  cursor:default;
}
.card:hover{transform:translateY(-10px);box-shadow:0 25px 60px rgba(10,14,42,0.1);}
.card-icon{width:52px;height:52px;border-radius:16px;display:flex;align-items:center;justify-content:center;font-size:1.6rem;margin-bottom:1.5rem;}
.ci1{background:linear-gradient(135deg,rgba(233,69,96,0.12),rgba(245,166,35,0.12));}
.ci2{background:linear-gradient(135deg,rgba(79,140,255,0.12),rgba(0,200,150,0.12));}
.ci3{background:linear-gradient(135deg,rgba(245,166,35,0.12),rgba(233,69,96,0.12));}
.card h3{font-size:1.1rem;font-weight:700;margin-bottom:0.6rem;color:#0A0E2A;}
.card p{font-size:0.87rem;color:#6B7A99;line-height:1.75;}

/* STEPS ROW */
.steps4{display:grid;grid-template-columns:repeat(auto-fit,minmax(230px,1fr));gap:1.5rem;margin-top:3.5rem;}
.step{
  background:#FAFBFF;border:1px solid rgba(10,14,42,0.07);
  border-radius:24px;padding:2rem;text-align:center;
  transition:all 0.5s cubic-bezier(0.34,1.56,0.64,1);
}
.step:hover{transform:translateY(-10px) scale(1.03);background:#fff;box-shadow:0 25px 55px rgba(10,14,42,0.09);}
.step-n{
  width:60px;height:60px;border-radius:50%;
  display:flex;align-items:center;justify-content:center;
  font-size:1.4rem;font-weight:900;margin:0 auto 1.5rem;color:#fff;
}
.sn1{background:linear-gradient(135deg,#E94560,#F5A623);}
.sn2{background:linear-gradient(135deg,#4F8CFF,#00C896);}
.sn3{background:linear-gradient(135deg,#00C896,#4F8CFF);}
.sn4{background:linear-gradient(135deg,#F5A623,#E94560);}
.step h3{font-size:1rem;font-weight:700;margin-bottom:0.6rem;color:#0A0E2A;}
.step p{font-size:0.84rem;color:#6B7A99;line-height:1.75;}

/* PRODUCTS GRID */
.prods{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:1rem;margin-top:3.5rem;}
.prod{
  background:#fff;border:1px solid rgba(10,14,42,0.07);
  border-radius:20px;padding:1.8rem 1.5rem;
  transition:all 0.4s cubic-bezier(0.34,1.56,0.64,1);
  box-shadow:0 2px 12px rgba(10,14,42,0.04);
}
.prod:hover{transform:translateY(-8px) scale(1.03);box-shadow:0 20px 50px rgba(10,14,42,0.1);}
.prod-icon{font-size:2rem;margin-bottom:1rem;display:block;}
.prod-name{font-size:1rem;font-weight:800;color:#0A0E2A;margin-bottom:0.3rem;}
.prod-desc{font-size:0.8rem;color:#6B7A99;line-height:1.6;}
.prod-tag{display:inline-block;font-size:0.65rem;font-weight:700;letter-spacing:1px;text-transform:uppercase;padding:0.2rem 0.6rem;border-radius:100px;margin-top:0.8rem;}
.pt-soon{background:rgba(233,69,96,0.1);color:#E94560;}
.pt-flagship{background:rgba(0,200,150,0.1);color:#00C896;}

/* QUOTE BANNER */
.qbanner{
  position:relative;z-index:1;padding:4rem 2rem;
  background:linear-gradient(135deg,#0A0E2A 0%,#1A1A4A 100%);
  overflow:hidden;
}
.qbanner::before{
  content:'';position:absolute;inset:0;
  background:linear-gradient(135deg,rgba(233,69,96,0.15),rgba(79,140,255,0.1),rgba(245,166,35,0.12));
}
.qbanner-in{position:relative;z-index:1;max-width:800px;margin:0 auto;text-align:center;}
.qbanner-text{
  font-size:clamp(1.3rem,3vw,2.2rem);font-weight:900;
  color:#fff;line-height:1.4;letter-spacing:-1px;
  margin-bottom:1rem;
}
.qbanner-text span{
  background:linear-gradient(90deg,#E94560,#F5A623,#4F8CFF,#00C896,#E94560);
  background-size:300%;
  -webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;
  animation:gradMove 5s linear infinite;
}
.qbanner-attr{font-size:0.85rem;color:rgba(255,255,255,0.5);font-style:italic;}

/* FOUNDER */
.founder-wrap{max-width:720px;margin:0 auto;text-align:center;}
.founder-av{
  width:100px;height:100px;border-radius:50%;margin:0 auto 2rem;
  background:linear-gradient(135deg,#E94560,#F5A623,#4F8CFF,#00C896);
  display:flex;align-items:center;justify-content:center;
  font-size:1.9rem;font-weight:900;color:#fff;
  animation:avPulse 3s ease-in-out infinite;
}
@keyframes avPulse{0%,100%{box-shadow:0 0 0 0 rgba(233,69,96,0.3);}50%{box-shadow:0 0 0 18px rgba(233,69,96,0);}}
.fnote{font-size:1.05rem;color:#6B7A99;line-height:1.9;font-style:italic;margin-bottom:2rem;}
.fsig{font-size:1.2rem;font-weight:900;color:#0A0E2A;}
.fmeta{font-size:0.82rem;color:#C5CAD9;margin-top:0.3rem;}

/* JOIN */
.join-wrap{max-width:620px;margin:0 auto;text-align:center;}
.erow{display:flex;gap:0.75rem;max-width:500px;margin:0 auto 1rem;flex-wrap:wrap;justify-content:center;}
.ein{
  flex:1;min-width:220px;padding:1rem 1.5rem;
  background:#fff;border:1.5px solid rgba(10,14,42,0.12);
  border-radius:100px;color:#0A0E2A;font-size:0.95rem;
  outline:none;transition:border-color 0.3s;
  box-shadow:0 2px 8px rgba(10,14,42,0.05);
}
.ein:focus{border-color:#E94560;}
.ein::placeholder{color:#C5CAD9;}
.jnote{font-size:0.76rem;color:#C5CAD9;}
.smsg{display:none;color:#00C896;font-weight:700;font-size:1rem;margin-top:1rem;}

/* FOOTER */
footer{position:relative;z-index:1;padding:3rem;border-top:1px solid rgba(10,14,42,0.08);background:#fff;}
.fin{max-width:1100px;margin:0 auto;display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:1.5rem;}
.flogo{font-size:1.4rem;font-weight:900;color:#0A0E2A;}
.flogo span{color:#E94560;}
.flinks a{color:#C5CAD9;text-decoration:none;font-size:0.84rem;margin-left:1.5rem;transition:color 0.3s;}
.flinks a:hover{color:#0A0E2A;}
.fcopy{font-size:0.76rem;color:#C5CAD9;}

/* REVEAL */
.rv{opacity:0;transform:translateY(50px);transition:opacity 0.9s cubic-bezier(0.34,1.2,0.64,1),transform 0.9s cubic-bezier(0.34,1.56,0.64,1);}
.rv.on{opacity:1;transform:none;}
.rv2{opacity:0;transform:translateY(50px);transition:opacity 0.9s 0.15s cubic-bezier(0.34,1.2,0.64,1),transform 0.9s 0.15s cubic-bezier(0.34,1.56,0.64,1);}
.rv2.on{opacity:1;transform:none;}
.rv3{opacity:0;transform:translateY(50px);transition:opacity 0.9s 0.3s cubic-bezier(0.34,1.2,0.64,1),transform 0.9s 0.3s cubic-bezier(0.34,1.56,0.64,1);}
.rv3.on{opacity:1;transform:none;}

@keyframes fadeUp{from{opacity:0;transform:translateY(30px);}to{opacity:1;transform:translateY(0);}}
@keyframes eyebrowIn{from{opacity:0;transform:translateY(-20px);}to{opacity:1;transform:translateY(0);}}
@keyframes shake{0%,100%{transform:translateX(0);}25%{transform:translateX(-8px);}75%{transform:translateX(8px);}}

@media(max-width:768px){
  nav{padding:1rem 1.5rem;}
  .nav-links{display:none;}
  .hero-title{letter-spacing:-3px;}
  footer .fin{flex-direction:column;text-align:center;}
  .flinks{margin-top:0.5rem;}
}
</style>
</head>
<body>

<div class="cursor" id="cur"></div>
<div class="cursor-trail" id="trail"></div>

<div class="blobs">
  <div class="blob blob1"></div>
  <div class="blob blob2"></div>
  <div class="blob blob3"></div>
  <div class="blob blob4"></div>
</div>

<!-- NAV -->
<nav id="nav">
  <div class="logo">Fawz<span>io</span></div>
  <div class="nav-links">
    <a href="#problem">Problem</a>
    <a href="#how">How it works</a>
    <a href="#products">Products</a>
    <a href="#founder">Founder</a>
  </div>
  <a href="#join" class="nav-cta">Join Early</a>
</nav>

<!-- HERO -->
<section id="hero">
  <div class="hero-eyebrow">
    <span class="ey-dot"></span>
    Brand Whitepaper v1.0 — Published Now
  </div>

  <h1 class="hero-title">
    <span class="ht-line"><span class="ht-inner l1">Achievement</span></span>
    <span class="ht-line"><span class="ht-inner l2">Without</span></span>
    <span class="ht-line"><span class="ht-inner l3">Price Tags.</span></span>
  </h1>

  <p class="hero-sub">
    Fawzio is a brand built for the billions who were never given the tools to succeed.
    <strong>Not one product — a house of products</strong> — all free, all powerful, all theirs.
  </p>

  <div class="hero-btns">
    <a href="https://github.com/kamranjalil828-creator/Prospera-Whitepaper" target="_blank" class="btn-dark">Read the Whitepaper</a>
    <a href="#products" class="btn-light">See What We Build</a>
  </div>

  <div class="hero-cards">
    <div class="hcard"><div class="hcard-num">4.7B</div><div class="hcard-lbl">Priced Out of AI</div></div>
    <div class="hcard"><div class="hcard-num">$0</div><div class="hcard-lbl">Cost to Join</div></div>
    <div class="hcard"><div class="hcard-num">∞</div><div class="hcard-lbl">Products Coming</div></div>
  </div>
</section>

<!-- MARQUEE -->
<div class="marquee-wrap">
  <div class="marquee-track">
    <span class="mq-item"><span class="mq-dot" style="background:#E94560"></span>Free for Everyone</span>
    <span class="mq-item"><span class="mq-dot" style="background:#4F8CFF"></span>Achievement for All</span>
    <span class="mq-item"><span class="mq-dot" style="background:#F5A623"></span>No Price Tags</span>
    <span class="mq-item"><span class="mq-dot" style="background:#00C896"></span>Built in Pakistan</span>
    <span class="mq-item"><span class="mq-dot" style="background:#E94560"></span>Fawz — Victory in Urdu</span>
    <span class="mq-item"><span class="mq-dot" style="background:#4F8CFF"></span>Not a Product — A Brand</span>
    <span class="mq-item"><span class="mq-dot" style="background:#F5A623"></span>Open Source Soul</span>
    <span class="mq-item"><span class="mq-dot" style="background:#00C896"></span>Founded by Kamran Jalil</span>
    <span class="mq-item"><span class="mq-dot" style="background:#E94560"></span>Free for Everyone</span>
    <span class="mq-item"><span class="mq-dot" style="background:#4F8CFF"></span>Achievement for All</span>
    <span class="mq-item"><span class="mq-dot" style="background:#F5A623"></span>No Price Tags</span>
    <span class="mq-item"><span class="mq-dot" style="background:#00C896"></span>Built in Pakistan</span>
    <span class="mq-item"><span class="mq-dot" style="background:#E94560"></span>Fawz — Victory in Urdu</span>
    <span class="mq-item"><span class="mq-dot" style="background:#4F8CFF"></span>Not a Product — A Brand</span>
    <span class="mq-item"><span class="mq-dot" style="background:#F5A623"></span>Open Source Soul</span>
    <span class="mq-item"><span class="mq-dot" style="background:#00C896"></span>Founded by Kamran Jalil</span>
  </div>
</div>

<!-- PROBLEM -->
<section class="sec" id="problem">
  <div class="sec-in">
    <span class="eyebrow e-red rv">The Problem</span>
    <h2 class="sec-title rv">The world's best tools<br>were never meant for you.</h2>
    <p class="sec-sub rv">Not because you lack talent. Because someone decided achievement should cost money first.</p>
    <div class="cards3">
      <div class="card rv"><div class="card-icon ci1">🎓</div><h3>The Student</h3><p>Paid everything for education. Cannot afford ChatGPT, design tools, or coding platforms on top. Left behind before they start.</p></div>
      <div class="card rv2"><div class="card-icon ci2">🌍</div><h3>The Gap</h3><p>A student in Silicon Valley has every AI tool available. A student in Lahore has nothing. Same intelligence. Different access. That is wrong.</p></div>
      <div class="card rv3"><div class="card-icon ci3">💸</div><h3>The Wall</h3><p>Every solution requires money — subscriptions, hardware, servers. The people who need these tools most are always the ones who can afford them least.</p></div>
    </div>
  </div>
</section>

<!-- HOW IT WORKS -->
<section class="sec sec-alt" id="how">
  <div class="sec-in">
    <span class="eyebrow e-blue rv">How It Works</span>
    <h2 class="sec-title rv">Free does not mean<br>weak. It means smarter.</h2>
    <p class="sec-sub rv">Every Fawzio product uses the same principle — your existing resources become your payment.</p>
    <div class="steps4">
      <div class="step rv"><div class="step-n sn1">1</div><h3>You Already Have What It Takes</h3><p>Internet you pay for. A device you own. Time you have. Fawzio turns what you already have into access.</p></div>
      <div class="step rv2"><div class="step-n sn2">2</div><h3>Everyone Contributes a Little</h3><p>Your idle internet bandwidth quietly joins a shared network. You never feel it. Someone else gets an answer.</p></div>
      <div class="step rv3"><div class="step-n sn3">3</div><h3>The Network Thinks Together</h3><p>No single server. No single owner. Thousands of people collectively become one powerful brain.</p></div>
      <div class="step rv"><div class="step-n sn4">4</div><h3>You Get Everything. Free.</h3><p>AI. Tools. Platforms. All free. All powerful. All growing stronger as more people join.</p></div>
    </div>
  </div>
</section>

<!-- QUOTE BANNER -->
<div class="qbanner">
  <div class="qbanner-in">
    <p class="qbanner-text rv"><span>"This is not charity. This is justice."</span></p>
    <p class="qbanner-attr rv">— Kamran Jalil, Founder of Fawzio, Age 17, Pakistan</p>
  </div>
</div>

<!-- PRODUCTS -->
<section class="sec" id="products">
  <div class="sec-in">
    <span class="eyebrow e-gold rv">What We Build</span>
    <h2 class="sec-title rv">One brand.<br>Infinite products.</h2>
    <p class="sec-sub rv">Every product Fawzio builds shares one rule — genuinely free for anyone who cannot afford to pay.</p>
    <div class="prods">
      <div class="prod rv">
        <span class="prod-icon">🤖</span>
        <div class="prod-name">Fawzio AI</div>
        <div class="prod-desc">Peer-to-peer AI intelligence. No subscription. Powered by the network itself.</div>
        <span class="prod-tag pt-flagship">Flagship</span>
      </div>
      <div class="prod rv2">
        <span class="prod-icon">🛠️</span>
        <div class="prod-name">Fawzio Tools</div>
        <div class="prod-desc">Free web-based productivity and creation tools for everyone.</div>
        <span class="prod-tag pt-soon">Coming Soon</span>
      </div>
      <div class="prod rv3">
        <span class="prod-icon">☁️</span>
        <div class="prod-name">Fawzio Cloud</div>
        <div class="prod-desc">Free storage and compute access for builders without resources.</div>
        <span class="prod-tag pt-soon">Coming Soon</span>
      </div>
      <div class="prod rv">
        <span class="prod-icon">🎨</span>
        <div class="prod-name">Fawzio Studio</div>
        <div class="prod-desc">Free design and creative platform. For artists everywhere.</div>
        <span class="prod-tag pt-soon">Coming Soon</span>
      </div>
      <div class="prod rv2">
        <span class="prod-icon">📚</span>
        <div class="prod-name">Fawzio Learn</div>
        <div class="prod-desc">Free intelligent tutoring system. For every student on earth.</div>
        <span class="prod-tag pt-soon">Coming Soon</span>
      </div>
    </div>
  </div>
</section>

<!-- FOUNDER -->
<section class="sec sec-alt" id="founder">
  <div class="founder-wrap">
    <div class="founder-av rv">KJ</div>
    <span class="eyebrow e-red rv" style="display:block;margin-bottom:1.5rem;">The Founder</span>
    <p class="fnote rv">"I built Fawzio because of millions and billions of people like me. People who have no money to buy things by themselves. Whether they are poor. Whether they are savers. Whether they are students without jobs. They cannot buy ChatGPT. They cannot buy design tools. They cannot afford the platforms that could change their lives. I was that person. I am still that person. And I refused to accept that this is how it should be. So I built Fawzio. Not one product. A brand. A house of products all built on the same promise — that achievement belongs to everyone."</p>
    <div class="fsig rv">— Kamran Jalil</div>
    <div class="fmeta rv">Founder, Fawzio &nbsp;·&nbsp; Age 17 &nbsp;·&nbsp; Pakistan &nbsp;·&nbsp; 2026</div>
  </div>
</section>

<!-- JOIN -->
<section class="sec" id="join">
  <div class="join-wrap">
    <span class="eyebrow e-green rv" style="display:block;text-align:center;">Join Early</span>
    <h2 class="sec-title rv" style="text-align:center;">Be part of<br><span style="background:linear-gradient(135deg,#E94560,#F5A623,#4F8CFF);-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;">the beginning.</span></h2>
    <p class="sec-sub rv" style="margin:0 auto 2.5rem;text-align:center;">No money. No hardware. Just your email. We will reach you when Fawzio is ready for you.</p>
    <div class="erow rv">
      <input type="email" class="ein" id="ein" placeholder="your@email.com"/>
      <button class="btn-dark" onclick="handleJoin()" style="border:none;cursor:pointer;">Join Waitlist</button>
    </div>
    <p class="jnote rv" style="text-align:center;">No spam. No fees. Ever.</p>
    <div class="smsg" id="smsg" style="text-align:center;">You are in. Welcome to Fawzio. InshAllah we change the world together.</div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="fin">
    <div class="flogo">Fawz<span>io</span></div>
    <div class="flinks">
      <a href="https://github.com/kamranjalil828-creator/Prospera-Whitepaper" target="_blank">GitHub</a>
      <a href="https://www.linkedin.com/feed/update/urn:li:activity:7449777591512764416/" target="_blank">LinkedIn</a>
      <a href="#join">Join</a>
    </div>
    <div class="fcopy">© 2026 Fawzio · Founded by Kamran Jalil · Pakistan · Achievement for everyone.</div>
  </div>
</footer>

<script>
// CUSTOM CURSOR
const cur=document.getElementById('cur'),trail=document.getElementById('trail');
let mx=0,my=0,tx=0,ty=0;
const colors=['#E94560','#4F8CFF','#F5A623','#00C896'];
let ci=0;
document.addEventListener('mousemove',e=>{
  mx=e.clientX;my=e.clientY;
  cur.style.left=mx-6+'px';cur.style.top=my-6+'px';
  cur.style.background=colors[ci%colors.length];
  ci++;
});
setInterval(()=>{
  tx+=(mx-tx)*0.15;ty+=(my-ty)*0.15;
  trail.style.left=tx-20+'px';trail.style.top=ty-20+'px';
  trail.style.borderColor=colors[(ci+2)%colors.length];
},16);

// NAV SCROLL
window.addEventListener('scroll',()=>{
  document.getElementById('nav').classList.toggle('scrolled',window.scrollY>50);
});

// MOUSE PARALLAX BLOBS
document.addEventListener('mousemove',e=>{
  const x=(e.clientX/window.innerWidth-0.5)*25;
  const y=(e.clientY/window.innerHeight-0.5)*25;
  document.querySelectorAll('.blob').forEach((b,i)=>{
    const f=(i+1)*0.3;
    b.style.transform=`translate(${x*f}px,${y*f}px)`;
  });
});

// SCROLL REVEAL
const obs=new IntersectionObserver(entries=>{
  entries.forEach(e=>{if(e.isIntersecting)e.target.classList.add('on');});
},{threshold:0.1});
document.querySelectorAll('.rv,.rv2,.rv3').forEach(el=>obs.observe(el));

// 3D CARD TILT
document.querySelectorAll('.card,.step,.prod,.hcard').forEach(c=>{
  c.addEventListener('mousemove',e=>{
    const r=c.getBoundingClientRect();
    const x=(e.clientX-r.left)/r.width-0.5;
    const y=(e.clientY-r.top)/r.height-0.5;
    c.style.transform=`translateY(-10px) rotateX(${-y*12}deg) rotateY(${x*12}deg) scale(1.03)`;
    c.style.transition='transform 0.08s';
  });
  c.addEventListener('mouseleave',()=>{
    c.style.transform='';
    c.style.transition='transform 0.6s cubic-bezier(0.34,1.56,0.64,1)';
  });
});

// MAGNETIC BUTTONS
document.querySelectorAll('.btn-dark,.btn-light,.nav-cta').forEach(btn=>{
  btn.addEventListener('mousemove',e=>{
    const r=btn.getBoundingClientRect();
    const x=e.clientX-r.left-r.width/2;
    const y=e.clientY-r.top-r.height/2;
    btn.style.transform=`translateY(-3px) translate(${x*0.1}px,${y*0.1}px)`;
  });
  btn.addEventListener('mouseleave',()=>{btn.style.transform='';});
});

// HERO TITLE LETTER BURST ON HOVER
document.querySelectorAll('.ht-inner').forEach(el=>{
  el.addEventListener('mouseenter',()=>{
    el.style.letterSpacing='-2px';
    el.style.transition='letter-spacing 0.4s cubic-bezier(0.34,1.56,0.64,1)';
  });
  el.addEventListener('mouseleave',()=>{
    el.style.letterSpacing='-5px';
  });
});

// JOIN
function handleJoin(){
  const ei=document.getElementById('ein');
  if(!ei.value||!ei.value.includes('@')){
    ei.style.borderColor='#E94560';
    ei.style.animation='shake 0.4s ease';
    setTimeout(()=>{ei.style.animation='';},400);
    return;
  }
  document.querySelector('.erow').style.display='none';
  document.getElementById('smsg').style.display='block';
}

// COUNTER ANIMATION
function animateCounter(el,target,suffix=''){
  let start=0;
  const dur=2000,step=16;
  const inc=target/(dur/step);
  const timer=setInterval(()=>{
    start+=inc;
    if(start>=target){start=target;clearInterval(timer);}
    el.textContent=Math.floor(start).toLocaleString()+suffix;
  },step);
}
const counterObs=new IntersectionObserver(entries=>{
  entries.forEach(e=>{
    if(e.isIntersecting){
      const el=e.target;
      const val=el.getAttribute('data-val');
      if(val)animateCounter(el,parseInt(val),el.getAttribute('data-suffix')||'');
      counterObs.unobserve(el);
    }
  });
},{threshold:0.5});
document.querySelectorAll('[data-val]').forEach(el=>counterObs.observe(el));
</script>
</body>
</html>
