#   
  
<!DOCTYPE html>  
  
<html lang="en">  
<head>  
<meta charset="UTF-8">  
<meta name="viewport" content="width=device-width, initial-scale=1.0">  
<title>What You Mean to Me — For Lakshita</title>  
<link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,300;0,9..144,700;0,9..144,900;1,9..144,400;1,9..144,700&family=Plus+Jakarta+Sans:wght@300;400;500;600;700&family=Caveat:wght@400;600;700&display=swap" rel="stylesheet">  
<style>  
:root {  
  --ink: #1A0D2E;  
  --gold: #FF9F43;  
  --rose: #FF6B9D;  
  --amber: #FFD93D;  
  --sage: #6BCB77;  
  --dusk: #A855F7;  
  --sky: #4FC3F7;  
  --cream: #FFF0F8;  
  --warm: #FFF0FB;  
  --card: #FFFFFF;  
  --text: #1A0D2E;  
  --muted: #6B5B8A;  
}  
*{margin:0;padding:0;box-sizing:border-box}  
html{scroll-behavior:smooth}  
body{background:linear-gradient(160deg,#FFF0F8 0%,#F0F8FF 40%,#F8FFF0 70%,#FFF8F0 100%);background-attachment:fixed;font-family:'Plus Jakarta Sans',sans-serif;color:var(--text);overflow-x:hidden}  
  
/* HERO */  
.hero{min-height:100vh;background:#1A0D2E;display:flex;align-items:center;justify-content:center;position:relative;overflow:hidden;padding:60px 24px;text-align:center}  
.hero-glow-1{position:absolute;width:600px;height:600px;border-radius:50%;background:radial-gradient(circle,rgba(255,159,67,.25) 0%,transparent 70%);top:-100px;left:-150px}  
.hero-glow-2{position:absolute;width:500px;height:500px;border-radius:50%;background:radial-gradient(circle,rgba(255,107,157,.2) 0%,transparent 70%);bottom:-100px;right:-100px}  
.hero-inner{position:relative;z-index:2;max-width:700px}  
.hero-chip{display:inline-block;border:1px solid rgba(212,146,42,.4);color:var(–amber);font-size:10px;letter-spacing:.4em;text-transform:uppercase;padding:7px 18px;border-radius:100px;margin-bottom:28px;opacity:0;animation:up .8s .3s ease forwards}  
.hero-eyeline{font-family:‘Plus Jakarta Sans’,sans-serif;font-weight:300;font-size:clamp(14px,2.5vw,18px);color:rgba(255,255,255,.5);margin-bottom:16px;opacity:0;animation:up .8s .5s ease forwards}  
.hero-title{font-family:‘Fraunces’,serif;font-size:clamp(48px,10vw,100px);font-weight:900;color:white;line-height:.95;opacity:0;animation:up 1s .7s cubic-bezier(.34,1.56,.64,1) forwards}  
.hero-title em{display:block;font-style:italic;font-weight:300;color:var(–amber);font-size:.65em;margin-top:8px}  
.hero-sub{font-family:‘Fraunces’,serif;font-style:italic;font-size:clamp(15px,2vw,19px);color:rgba(255,255,255,.4);margin-top:22px;line-height:1.7;opacity:0;animation:up .8s 1s ease forwards}  
.hero-scroll{position:absolute;bottom:28px;left:50%;transform:translateX(-50%);display:flex;flex-direction:column;align-items:center;gap:6px;opacity:0;animation:up .8s 1.5s ease forwards}  
.scroll-bar{width:1px;height:44px;background:linear-gradient(180deg,transparent,rgba(212,146,42,.6));animation:pulse 2s ease-in-out infinite}  
@keyframes pulse{0%,100%{opacity:.4}50%{opacity:1}}  
.scroll-txt{font-size:8px;letter-spacing:.3em;text-transform:uppercase;color:rgba(212,146,42,.4)}  
@keyframes up{from{opacity:0;transform:translateY(24px)}to{opacity:1;transform:translateY(0)}}  
  
/* SHARED */  
.page{padding:80px 24px;max-width:1060px;margin:0 auto}  
.vis{opacity:0;transform:translateY(32px);transition:opacity .8s ease,transform .8s ease}  
.vis.on{opacity:1;transform:translateY(0)}  
.d1{transition-delay:.1s}.d2{transition-delay:.2s}.d3{transition-delay:.3s}.d4{transition-delay:.4s}  
  
.chip{display:inline-flex;align-items:center;gap:6px;font-size:9px;letter-spacing:.35em;text-transform:uppercase;font-weight:700;padding:6px 16px;border-radius:100px;margin-bottom:16px}  
.chip-rose{background:rgba(255,107,157,.15);color:var(–rose);border:1px solid rgba(255,107,157,.4)}  
.chip-gold{background:rgba(255,159,67,.15);color:var(–gold);border:1px solid rgba(255,159,67,.4)}  
.chip-sage{background:rgba(107,203,119,.15);color:var(–sage);border:1px solid rgba(107,203,119,.4)}  
.chip-dusk{background:rgba(168,85,247,.15);color:var(–dusk);border:1px solid rgba(168,85,247,.4)}  
  
.big-h{font-family:‘Fraunces’,serif;font-size:clamp(34px,6vw,60px);font-weight:800;line-height:1.05;margin-bottom:8px}  
.big-h em{font-style:italic;color:var(–rose)}  
.sub{font-size:14px;color:var(–muted);font-weight:300;line-height:1.7;margin-bottom:44px;max-width:560px}  
  
.divider{height:1px;background:linear-gradient(90deg,transparent,rgba(255,159,67,.4),transparent);margin:0}  
  
/* ── SECTION 1: THE PROOF ── */  
.proof-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:16px;margin-bottom:50px}  
.proof-card{background:var(–card);border-radius:22px;padding:28px 22px;border:1px solid rgba(0,0,0,.06);position:relative;overflow:hidden;transition:transform .3s,box-shadow .3s}  
.proof-card:hover{transform:translateY(-5px);box-shadow:0 16px 40px rgba(0,0,0,.08)}  
.proof-card::after{content:’’;position:absolute;bottom:0;left:0;right:0;height:3px;border-radius:0 0 22px 22px}  
.pc-rose::after{background:linear-gradient(90deg,#FF6B9D,#FF9F43)}  
.pc-gold::after{background:linear-gradient(90deg,#FFD93D,#FF9F43)}  
.pc-sage::after{background:linear-gradient(90deg,#6BCB77,#4FC3F7)}  
.pc-dusk::after{background:linear-gradient(90deg,#A855F7,#FF6B9D)}  
.pc-sky::after{background:linear-gradient(90deg,#4FC3F7,#6BCB77)}  
.pc-amber::after{background:linear-gradient(90deg,#FFD93D,#FF9F43)}  
.proof-icon{font-size:30px;margin-bottom:14px;display:block}  
.proof-stat{font-family:‘Fraunces’,serif;font-size:44px;font-weight:900;line-height:1;margin-bottom:6px;color:var(–ink)}  
.proof-label{font-size:12px;font-weight:600;color:var(–text);margin-bottom:4px}  
.proof-sub{font-size:11px;color:var(–muted);line-height:1.5}  
.proof-pill{display:inline-block;font-size:10px;font-weight:700;padding:3px 10px;border-radius:100px;margin-top:8px}  
.pp-rose{background:rgba(255,107,157,.12);color:var(–rose)}  
.pp-gold{background:rgba(255,217,61,.15);color:var(–gold)}  
  
/* ── SECTION 2: RESPONSE TIME ── */  
.vs-wrap{display:grid;grid-template-columns:1fr auto 1fr;gap:20px;align-items:center;margin-bottom:50px}  
@media(max-width:600px){.vs-wrap{grid-template-columns:1fr;}.vs-mid{display:none}}  
.vs-card{background:var(–card);border-radius:24px;padding:32px;border:1px solid rgba(0,0,0,.07);text-align:center;transition:transform .3s}  
.vs-card:hover{transform:scale(1.02)}  
.vs-name{font-size:11px;letter-spacing:.15em;text-transform:uppercase;font-weight:600;margin-bottom:12px}  
.vs-num{font-family:‘Fraunces’,serif;font-size:64px;font-weight:900;line-height:1}  
.vs-unit{font-size:14px;font-weight:300;color:var(–muted)}  
.vs-bar-wrap{margin-top:16px;height:6px;background:rgba(0,0,0,.05);border-radius:100px;overflow:hidden}  
.vs-bar{height:100%;border-radius:100px;animation:grow 1.5s ease-out forwards}  
@keyframes grow{from{width:0!important}}  
.vs-mid{font-family:‘Fraunces’,serif;font-size:36px;font-weight:900;color:var(–muted);opacity:.3;text-align:center}  
  
/* ── SECTION 3: THE WORDS ── */  
.word-evidence{display:grid;grid-template-columns:1fr 1fr;gap:20px;margin-bottom:50px}  
@media(max-width:600px){.word-evidence{grid-template-columns:1fr}}  
.we-card{background:var(–card);border-radius:22px;padding:28px;border:1px solid rgba(0,0,0,.06)}  
.we-title{font-family:‘Fraunces’,serif;font-size:18px;font-weight:700;margin-bottom:16px}  
.we-row{display:flex;align-items:center;gap:12px;margin-bottom:10px}  
.we-word{font-family:‘Fraunces’,serif;font-style:italic;font-size:15px;color:var(–ink);width:90px;flex-shrink:0}  
.we-track{flex:1;height:8px;background:rgba(0,0,0,.04);border-radius:100px;overflow:hidden}  
.we-fill{height:100%;border-radius:100px;animation:grow 1.5s ease-out forwards}  
.we-count{font-size:12px;font-weight:700;width:40px;text-align:right;flex-shrink:0}  
  
/* ── SECTION 4: INITIATIVES ── */  
.init-wrap{background:#1A0D2E;border-radius:28px;padding:clamp(30px,5vw,52px);margin-bottom:50px;position:relative;overflow:hidden}  
.init-wrap::before{content:’’;position:absolute;inset:0;background:radial-gradient(ellipse at 30% 50%,rgba(255,159,67,.15),transparent 60%)}  
.init-title{font-family:‘Fraunces’,serif;font-size:clamp(22px,4vw,38px);font-weight:800;color:white;margin-bottom:8px;position:relative}  
.init-sub{font-size:13px;color:rgba(255,255,255,.4);margin-bottom:32px;position:relative;font-style:italic}  
.init-bars{display:grid;grid-template-columns:1fr 1fr;gap:20px;position:relative}  
@media(max-width:550px){.init-bars{grid-template-columns:1fr}}  
.init-person{text-align:center}  
.init-name{font-size:11px;letter-spacing:.15em;text-transform:uppercase;font-weight:600;margin-bottom:12px}  
.init-circle-wrap{position:relative;width:140px;height:140px;margin:0 auto 12px}  
.init-circle-bg{position:absolute;inset:0;border-radius:50%}  
.init-circle-val{position:absolute;inset:0;display:flex;flex-direction:column;align-items:center;justify-content:center}  
.init-big{font-family:‘Fraunces’,serif;font-size:36px;font-weight:900;color:white;line-height:1}  
.init-small{font-size:10px;color:rgba(255,255,255,.5);text-transform:uppercase;letter-spacing:.1em}  
.init-desc{font-size:12px;color:rgba(255,255,255,.45);line-height:1.5;max-width:200px;margin:0 auto}  
.insight-box{grid-column:span 2;background:rgba(255,255,255,.04);border:1px solid rgba(255,255,255,.08);border-radius:16px;padding:20px 24px;font-size:13px;color:rgba(255,255,255,.5);font-style:italic;line-height:1.6;position:relative}  
@media(max-width:550px){.insight-box{grid-column:span 1}}  
  
/* ── SECTION 5: CHECKING IN ── */  
.checkin-section{background:linear-gradient(135deg,#FFF0FB,#F0FAFF);border-radius:28px;padding:clamp(28px,4vw,48px);margin-bottom:50px}  
.checkin-big{font-family:‘Fraunces’,serif;font-size:clamp(60px,12vw,120px);font-weight:900;color:var(–rose);line-height:1;margin-bottom:4px}  
.checkin-label{font-size:14px;font-weight:600;color:var(–text);margin-bottom:16px}  
.checkin-desc{font-size:14px;color:var(–muted);max-width:500px;line-height:1.7}  
  
/* ── SECTION 6: QUOTES ── */  
.quote-stack{display:flex;flex-direction:column;gap:20px;margin-bottom:50px}  
.quote-card{background:var(–card);border-radius:22px;padding:clamp(22px,3vw,36px);border:1px solid rgba(0,0,0,.06);position:relative;overflow:hidden;transition:transform .3s}  
.quote-card:hover{transform:translateY(-3px)}  
.qc-tag{display:inline-flex;align-items:center;gap:6px;font-size:9px;letter-spacing:.3em;text-transform:uppercase;font-weight:700;padding:4px 12px;border-radius:100px;margin-bottom:14px}  
.qc-text{font-family:‘Fraunces’,serif;font-style:italic;font-size:clamp(15px,2vw,19px);line-height:1.75;color:var(–ink);margin-bottom:12px}  
.qc-text em{color:var(–rose);font-style:normal;font-weight:700}  
.qc-meta{font-size:10px;letter-spacing:.15em;text-transform:uppercase;color:var(–muted)}  
.qc-deco{position:absolute;top:-10px;right:16px;font-family:‘Fraunces’,serif;font-size:120px;opacity:.04;line-height:1;color:var(–rose)}  
  
/* ── SECTION 7: TIMELINE OF CARE ── */  
.care-timeline{position:relative;padding-left:28px;margin-bottom:50px}  
.ct-line{position:absolute;left:6px;top:0;bottom:0;width:2px;background:linear-gradient(180deg,var(–rose),var(–gold),var(–sage),var(–dusk))}  
.ct-item{position:relative;margin-bottom:30px;opacity:0;transform:translateX(-16px);transition:opacity .6s,transform .6s}  
.ct-item.on{opacity:1;transform:translateX(0)}  
.ct-dot{position:absolute;left:-24px;top:4px;width:12px;height:12px;border-radius:50%;border:2px solid white}  
.ct-date{font-size:9px;letter-spacing:.15em;text-transform:uppercase;color:var(–rose);font-weight:600;margin-bottom:3px}  
.ct-head{font-family:‘Fraunces’,serif;font-size:17px;font-weight:700;margin-bottom:4px;line-height:1.3}  
.ct-body{font-size:12px;color:var(–muted);line-height:1.6}  
.ct-quote{font-family:‘Fraunces’,serif;font-style:italic;font-size:13px;color:var(–text);background:linear-gradient(135deg,#FFF0F8,#F8F0FF);border-left:3px solid var(–gold);padding:10px 14px;border-radius:0 10px 10px 0;margin-top:8px;line-height:1.6}  
  
/* ── CLOSING ── */  
.closing{background:#1A0D2E;padding:100px 24px;text-align:center;position:relative;overflow:hidden}  
.closing-halo{position:absolute;width:700px;height:700px;border-radius:50%;background:radial-gradient(circle,rgba(255,107,157,.2) 0%,transparent 70%);top:50%;left:50%;transform:translate(-50%,-50%);animation:breathe 5s ease-in-out infinite}  
@keyframes breathe{0%,100%{transform:translate(-50%,-50%) scale(1)}50%{transform:translate(-50%,-50%) scale(1.08)}}  
.closing-title{font-family:‘Fraunces’,serif;font-size:clamp(14px,2.5vw,20px);font-style:italic;color:rgba(255,255,255,.35);position:relative;margin-bottom:16px}  
.closing-big{font-family:‘Fraunces’,serif;font-size:clamp(44px,10vw,110px);font-weight:900;color:white;line-height:.95;position:relative;margin-bottom:16px}  
.closing-big em{font-style:italic;color:var(–amber)}  
.closing-caveat{font-family:‘Caveat’,cursive;font-size:clamp(26px,5vw,50px);color:var(–rose);position:relative;margin-bottom:24px}  
.closing-para{font-size:14px;color:rgba(255,255,255,.35);max-width:500px;margin:0 auto;line-height:1.8;position:relative;font-weight:300}  
.closing-sig{margin-top:48px;font-size:9px;letter-spacing:.4em;text-transform:uppercase;color:rgba(212,146,42,.3);position:relative}  
</style>  
  
</head>  
<body>  
  
<!-- ══ HERO ══ -->  
  
<section class="hero">  
  <div class="hero-glow-1"></div>  
  <div class="hero-glow-2"></div>  
  <div class="hero-inner">  
    <div class="hero-chip">📊 Evidence from 3 years of chats</div>  
    <p class="hero-eyeline">The data doesn't lie.</p>  
    <h1 class="hero-title">What you mean to me<em>— in proof</em></h1>  
    <p class="hero-sub">Words are easy. But 83,540 messages leave a trail. Here is everything the chat data reveals about how much Lakshita matters.</p>  
  </div>  
  <div class="hero-scroll">  
    <div class="scroll-bar"></div>  
    <span class="scroll-txt">scroll</span>  
  </div>  
</section>  
  
<!-- ══ THE PROOF ══ -->  
  
<section>  
<div class="page">  
  <div class="vis">  
    <div class="chip chip-rose">💛 The Hard Evidence</div>  
    <h2 class="big-h">Six things the data <em>proves</em></h2>  
    <p class="sub">These aren't feelings. These are facts, extracted from 83,540 messages.</p>  
  </div>  
  <div class="proof-grid">  
    <div class="proof-card pc-rose vis d1">  
      <span class="proof-icon">⚡</span>  
      <div class="proof-stat" data-count="90">0</div>  
      <div class="proof-label">% of the time Yash replies within 15 minutes</div>  
      <div class="proof-sub">Out of 16,612 times Lakshita messaged him, he responded in under 15 minutes — 14,958 times.</div>  
      <div class="proof-pill pp-rose">16,612 exchanges tracked</div>  
    </div>  
    <div class="proof-card pc-gold vis d1">  
      <span class="proof-icon">🌙</span>  
      <div class="proof-stat" data-count="13677">0</div>  
      <div class="proof-label">Late-night messages he sent her</div>  
      <div class="proof-sub">Between 10 PM and 2 AM. He didn't just talk to her during the day — he stayed up for her.</div>  
      <div class="proof-pill pp-gold">That's 1 in 3 messages</div>  
    </div>  
    <div class="proof-card pc-sage vis d2">  
      <span class="proof-icon">🫂</span>  
      <div class="proof-stat" data-count="524">0</div>  
      <div class="proof-label">Times he checked in on her</div>  
      <div class="proof-sub">"You okay?" "Theek ho?" "What happened?" — 524 times he noticed, and asked.</div>  
      <div class="proof-pill" style="background:rgba(107,203,119,.12);color:var(--sage)">Once every 2.6 days</div>  
    </div>  
    <div class="proof-card pc-dusk vis d2">  
      <span class="proof-icon">✍️</span>  
      <div class="proof-stat">45%</div>  
      <div class="proof-label">Longer messages than hers, on average</div>  
      <div class="proof-sub">His avg: 42 chars. Hers: 29. He elaborated. He explained. He made sure she understood.</div>  
      <div class="proof-pill" style="background:rgba(168,85,247,.12);color:var(--dusk)">41,611 messages total</div>  
    </div>  
    <div class="proof-card pc-sky vis d3">  
      <span class="proof-icon">🔥</span>  
      <div class="proof-stat" data-count="3186">0</div>  
      <div class="proof-label">Times he sent 5+ messages in a row</div>  
      <div class="proof-sub">When he had something to say to her, he said all of it. No holding back.</div>  
      <div class="proof-pill" style="background:rgba(79,195,247,.12);color:var(--sky)">Bursts of care</div>  
    </div>  
    <div class="proof-card pc-amber vis d3">  
      <span class="proof-icon">📅</span>  
      <div class="proof-stat" data-count="635">0</div>  
      <div class="proof-label">Days he started the conversation first</div>  
      <div class="proof-sub">635 mornings (or afternoons, or nights) when he woke up and thought of her first.</div>  
      <div class="proof-pill" style="background:rgba(255,217,61,.12);color:var(--amber)">Almost every other day</div>  
    </div>  
  </div>  
</div>  
</section>  
  
<div class="divider"></div>  
  
<!-- ══ RESPONSE TIME ══ -->  
  
<section>  
<div class="page">  
  <div class="vis">  
    <div class="chip chip-gold">⏱ Response Speed</div>  
    <h2 class="big-h">He replies to her <em>faster</em></h2>  
    <p class="sub">Average response times within the same conversation — the gap tells the story.</p>  
  </div>  
  <div class="vs-wrap vis">  
    <div class="vs-card">  
      <div class="vs-name" style="color:var(--gold)">Yash responds to Lakshita</div>  
      <div class="vs-num" style="color:var(--gold)">4.5<span class="vs-unit"> min</span></div>  
      <div style="font-size:12px;color:var(--muted);margin-top:8px">On average, across 16,612 exchanges</div>  
      <div class="vs-bar-wrap"><div class="vs-bar" style="width:71%;background:var(--gold)"></div></div>  
    </div>  
    <div class="vs-mid">VS</div>  
    <div class="vs-card">  
      <div class="vs-name" style="color:var(--rose)">Lakshita responds to Yash</div>  
      <div class="vs-num" style="color:var(--rose)">6.3<span class="vs-unit"> min</span></div>  
      <div style="font-size:12px;color:var(--muted);margin-top:8px">On average, across her replies</div>  
      <div class="vs-bar-wrap"><div class="vs-bar" style="width:100%;background:var(--rose)"></div></div>  
    </div>  
  </div>  
  <div class="vis" style="background:var(--warm);border-radius:20px;padding:22px 26px;border:1px solid rgba(255,159,67,.2)">  
    <p style="font-family:'Fraunces',serif;font-style:italic;font-size:16px;line-height:1.7;color:var(--text)">He's 1.8× faster at responding to her than she is to him. When Lakshita texts, Yash is there — almost immediately, almost every time.</p>  
  </div>  
</div>  
</section>  
  
<div class="divider"></div>  
  
<!-- ══ WORDS OF CARE ══ -->  
  
<section style="background:linear-gradient(135deg,#FFF0FB,#F0F8FF);padding:80px 0">  
<div class="page">  
  <div class="vis">  
    <div class="chip chip-rose">💬 His Vocabulary of Care</div>  
    <h2 class="big-h">The words he used <em>for her</em></h2>  
    <p class="sub">These are words Yash used specifically in messages to or about Lakshita — counted from 41,611 messages.</p>  
  </div>  
  <div class="word-evidence vis">  
    <div class="we-card">  
      <div class="we-title">How he described her</div>  
      <div class="we-row"><div class="we-word">best</div><div class="we-track"><div class="we-fill" style="width:100%;background:var(--rose)"></div></div><div class="we-count" style="color:var(--rose)">275×</div></div>  
      <div class="we-row"><div class="we-word">amazing</div><div class="we-track"><div class="we-fill" style="width:23%;background:var(--gold)"></div></div><div class="we-count" style="color:var(--gold)">63×</div></div>  
      <div class="we-row"><div class="we-word">beautiful</div><div class="we-track"><div class="we-fill" style="width:13%;background:var(--dusk)"></div></div><div class="we-count" style="color:var(--dusk)">35×</div></div>  
      <div class="we-row"><div class="we-word">special</div><div class="we-track"><div class="we-fill" style="width:28%;background:var(--sage)"></div></div><div class="we-count" style="color:var(--sage)">77×</div></div>  
      <div class="we-row"><div class="we-word">wonderful</div><div class="we-track"><div class="we-fill" style="width:3%;background:var(--sky)"></div></div><div class="we-count" style="color:var(--sky)">7×</div></div>  
    </div>  
    <div class="we-card">  
      <div class="we-title">How he showed up</div>  
      <div class="we-row"><div class="we-word">important</div><div class="we-track"><div class="we-fill" style="width:100%;background:var(--rose)"></div></div><div class="we-count" style="color:var(--rose)">126×</div></div>  
      <div class="we-row"><div class="we-word">proud</div><div class="we-track"><div class="we-fill" style="width:55%;background:var(--gold)"></div></div><div class="we-count" style="color:var(--gold)">69×</div></div>  
      <div class="we-row"><div class="we-word">lucky</div><div class="we-track"><div class="we-fill" style="width:22%;background:var(--dusk)"></div></div><div class="we-count" style="color:var(--dusk)">28×</div></div>  
      <div class="we-row"><div class="we-word">grateful</div><div class="we-track"><div class="we-fill" style="width:10%;background:var(--sage)"></div></div><div class="we-count" style="color:var(--sage)">12×</div></div>  
      <div class="we-row"><div class="we-word">trust</div><div class="we-track"><div class="we-fill" style="width:27%;background:var(--sky)"></div></div><div class="we-count" style="color:var(--sky)">34×</div></div>  
    </div>  
  </div>  
</div>  
</section>  
  
<div class="divider"></div>  
  
<!-- ══ WHO INITIATES ══ -->  
  
<section>  
<div class="page">  
  <div class="vis">  
    <div class="chip chip-sage">📲 Who Starts the Conversation</div>  
    <h2 class="big-h">635 days he woke up <em>thinking of her</em></h2>  
    <p class="sub">Out of 1,358 days chatting, Yash initiated 635 times. Lakshita initiated 723 times. They both showed up — almost equally.</p>  
  </div>  
  <div class="init-wrap vis">  
    <div class="init-title">Who texted first, by day</div>  
    <div class="init-sub">Across 1,358 total days of conversation</div>  
    <div class="init-bars">  
      <div class="init-person">  
        <div class="init-name" style="color:var(--gold)">Yash</div>  
        <div class="init-circle-wrap">  
          <svg viewBox="0 0 120 120" style="position:absolute;inset:0;width:100%;height:100%;transform:rotate(-90deg)">  
            <circle cx="60" cy="60" r="50" fill="none" stroke="rgba(255,255,255,.08)" stroke-width="10"/>  
            <circle cx="60" cy="60" r="50" fill="none" stroke="var(--gold)" stroke-width="10" stroke-dasharray="314" stroke-dashoffset="157" stroke-linecap="round"/>  
          </svg>  
          <div class="init-circle-val"><div class="init-big" style="color:var(--gold)">635</div><div class="init-small">days</div></div>  
        </div>  
        <div class="init-desc">47% of all days — he reached out first</div>  
      </div>  
      <div class="init-person">  
        <div class="init-name" style="color:var(--rose)">Lakshita</div>  
        <div class="init-circle-wrap">  
          <svg viewBox="0 0 120 120" style="position:absolute;inset:0;width:100%;height:100%;transform:rotate(-90deg)">  
            <circle cx="60" cy="60" r="50" fill="none" stroke="rgba(255,255,255,.08)" stroke-width="10"/>  
            <circle cx="60" cy="60" r="50" fill="none" stroke="var(--rose)" stroke-width="10" stroke-dasharray="314" stroke-dashoffset="123" stroke-linecap="round"/>  
          </svg>  
          <div class="init-circle-val"><div class="init-big" style="color:var(--rose)">723</div><div class="init-small">days</div></div>  
        </div>  
        <div class="init-desc">53% of all days — she reached out first</div>  
      </div>  
      <div class="insight-box">  
        💡 &nbsp;Almost perfectly equal. Neither of them was ever "the one who cares more." They both showed up. Every single day, one of them started the conversation. For 1,358 days.  
      </div>  
    </div>  
  </div>  
</div>  
</section>  
  
<div class="divider"></div>  
  
<!-- ══ CHECKING IN ══ -->  
  
<section style="background:linear-gradient(135deg,#FFF0FB,#F0F8FF);padding:80px 0">  
<div class="page">  
  <div class="vis">  
    <div class="chip chip-dusk">🫂 Being There</div>  
    <h2 class="big-h">524 times he asked <em>"you okay?"</em></h2>  
    <p class="sub">He didn't just talk to her — he watched out for her. "Theek ho?" "What happened?" "You okay?" Once every 2.6 days.</p>  
  </div>  
  <div class="checkin-section vis">  
    <div style="display:grid;grid-template-columns:auto 1fr;gap:30px;align-items:center">  
      <div>  
        <div class="checkin-big">524</div>  
        <div class="checkin-label">check-ins across 3 years</div>  
      </div>  
      <div>  
        <p class="checkin-desc">That's not someone who just replies to messages. That's someone who pays attention. Who notices when you go quiet. Who asks before you have to say anything.</p>  
        <div style="margin-top:20px;display:flex;flex-wrap:wrap;gap:10px">  
          <div style="background:rgba(255,107,157,.12);border:1px solid rgba(217,79,106,.15);color:var(--rose);padding:8px 16px;border-radius:100px;font-size:12px;font-weight:600">Once every 2.6 days 📅</div>  
          <div style="background:rgba(255,217,61,.15);border:1px solid rgba(255,159,67,.2);color:var(--gold);padding:8px 16px;border-radius:100px;font-size:12px;font-weight:600">565 times he said sorry 🙏</div>  
          <div style="background:rgba(107,203,119,.12);border:1px solid rgba(90,158,122,.15);color:var(--sage);padding:8px 16px;border-radius:100px;font-size:12px;font-weight:600">14 times: "I love you" 💛</div>  
        </div>  
      </div>  
    </div>  
  </div>  
</div>  
</section>  
  
<div class="divider"></div>  
  
<!-- ══ REAL QUOTES ══ -->  
  
<section>  
<div class="page">  
  <div class="vis">  
    <div class="chip chip-rose">✍️ His Actual Words</div>  
    <h2 class="big-h">What he wrote <em>to her</em></h2>  
    <p class="sub">Not paraphrased. Not summarised. The real things Yash actually typed, from the chat.</p>  
  </div>  
  <div class="quote-stack">  
  
```  
<div class="quote-card vis d1">  
  <div class="qc-deco">"</div>  
  <div class="qc-tag" style="background:rgba(255,217,61,.15);color:var(--gold);border:1px solid rgba(212,146,42,.2)">💛 May 9, 2023 — Her Birthday</div>  
  <p class="qc-text">"Thank you so much for being such a supportive friend, listening patiently to my crazy thoughts and advising me about everything. <em>In hindsight, I feel that had I not met you, my college life wouldn't have been half as fun.</em> Thank you so much for everything, I really love you and no matter how much you say otherwise, <em>you matter.</em>"</p>  
  <div class="qc-meta">Yash → Lakshita · Birthday message</div>  
</div>  
  
<div class="quote-card vis d2">  
  <div class="qc-deco">"</div>  
  <div class="qc-tag" style="background:rgba(107,203,119,.12);color:var(--sage);border:1px solid rgba(107,203,119,.35)">🌿 May 29, 2023</div>  
  <p class="qc-text">"<em>I'll really miss you Lakshita</em>, in case I haven't said it enough, <em>tumhe idea bhi nahi hai ki kitni chhoti chhoti harkate hai tumhaari jinke wajah se itna effortlessly I get a smile on my face.</em>"</p>  
  <div class="qc-meta">Yash → Lakshita · When she was leaving</div>  
</div>  
  
<div class="quote-card vis d3">  
  <div class="qc-deco">"</div>  
  <div class="qc-tag" style="background:rgba(255,107,157,.12);color:var(--rose);border:1px solid rgba(255,107,157,.35)">💬 March 22, 2023</div>  
  <p class="qc-text">"<em>This might come as a surprise to you since I don't say it out loud, but I really care about you.</em>"</p>  
  <div class="qc-meta">Yash → Lakshita · Said out of nowhere, just because</div>  
</div>  
  
<div class="quote-card vis d3">  
  <div class="qc-deco">"</div>  
  <div class="qc-tag" style="background:rgba(168,85,247,.12);color:var(--dusk);border:1px solid rgba(168,85,247,.35)">🫀 October 16, 2023 — The Vulnerable Message</div>  
  <p class="qc-text">"<em>Jab meri kisi dost se baat nahi hoti 2-3-4 din ke liye, mujhe affect nahi hota.</em> But jab tumse baat nahi ho paati hai, <em>I start to feel weird.</em> The feeling that goes on in my head when we talk — <em>that of pure happiness.</em>"</p>  
  <div class="qc-meta">Yash → Lakshita · The most honest thing he ever sent her</div>  
</div>  
```  
  
  </div>  
</div>  
</section>  
  
<div class="divider"></div>  
  
<!-- ══ CARE TIMELINE ══ -->  
  
<section style="background:linear-gradient(135deg,#FFF0FB,#F0F8FF);padding:80px 0">  
<div class="page">  
  <div class="vis">  
    <div class="chip chip-gold">📖 Moments of Care</div>  
    <h2 class="big-h">Every time he <em>showed up</em></h2>  
    <p class="sub">A timeline of the moments that prove this friendship meant everything.</p>  
  </div>  
  <div class="care-timeline" id="ct">  
    <div class="ct-line"></div>  
  
```  
<div class="ct-item"><div class="ct-dot" style="background:var(--gold)"></div>  
  <div class="ct-date">March 22, 2023</div>  
  <div class="ct-head">He said it, quietly 💛</div>  
  <div class="ct-body">Unprompted, mid-conversation, he told her he cared about her. Just because.</div>  
  <div class="ct-quote">"This might come as a surprise since I don't say it out loud, but I really care about you."</div>  
</div>  
  
<div class="ct-item"><div class="ct-dot" style="background:var(--rose)"></div>  
  <div class="ct-date">May 9, 2023 — Her Birthday</div>  
  <div class="ct-head">The birthday message that said everything 🎂</div>  
  <div class="ct-body">Not just "happy birthday" — a full, heartfelt letter about what she meant to him.</div>  
  <div class="ct-quote">"Had I not met you, my college life wouldn't have been half as fun. You matter."</div>  
</div>  
  
<div class="ct-item"><div class="ct-dot" style="background:var(--sage)"></div>  
  <div class="ct-date">May 29, 2023</div>  
  <div class="ct-head">He noticed the little things 🌸</div>  
  <div class="ct-body">When she was leaving, he didn't just say bye. He told her exactly what he'd miss — the small things.</div>  
  <div class="ct-quote">"Tumhe idea bhi nahi hai ki kitni chhoti chhoti harkate tumhaari — jinke wajah se I get a smile on my face."</div>  
</div>  
  
<div class="ct-item"><div class="ct-dot" style="background:var(--dusk)"></div>  
  <div class="ct-date">October 16, 2023</div>  
  <div class="ct-head">He was vulnerable with her 🫀</div>  
  <div class="ct-body">He sent the hardest kind of message — honest, scared, and real. He told her she was different from everyone else.</div>  
  <div class="ct-quote">"When we don't talk, I start to feel weird. The feeling when we do talk — that of pure happiness."</div>  
</div>  
  
<div class="ct-item"><div class="ct-dot" style="background:var(--amber)"></div>  
  <div class="ct-date">Every single day · 2022–2026</div>  
  <div class="ct-head">90% response rate. Always. 🔔</div>  
  <div class="ct-body">Every time she messaged, he was there within 15 minutes. 14,958 out of 16,612 times. That's not coincidence. That's priority.</div>  
</div>  
```  
  
  </div>  
</div>  
</section>  
  
<!-- ══ WHAT HE LOVES ABOUT HER ══ -->  
  
<section style="background:linear-gradient(135deg,#FFF0FB,#F0F8FF);padding:80px 0">  
<div style="padding:0 24px;max-width:1060px;margin:0 auto">  
  <div class="vis">  
    <div class="chip chip-rose">✨ The Real List</div>  
    <h2 class="big-h">Things he <em>loves</em> about her</h2>  
    <p class="sub">Not made up. Every single one pulled from actual messages he sent her.</p>  
  </div>  
  <div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:16px;margin-bottom:50px">  
    <div class="proof-card pc-rose vis d1"><span class="proof-icon">😂</span><div style="font-family:Fraunces,serif;font-size:18px;font-weight:700;margin-bottom:8px">Her "cynical laughter"</div><p style="font-size:13px;color:#6B5B8A;line-height:1.6">He literally named it. He noticed it, remembered it, and loved it enough to give it its own title.</p><div style="font-family:Fraunces,serif;font-style:italic;font-size:12px;color:#BC7A90;margin-top:10px;border-left:3px solid #FF9F43;padding-left:10px">"Lot of expletives, followed by that cynical laughter of yours" — May 2023</div></div>  
    <div class="proof-card pc-gold vis d1"><span class="proof-icon">🧀</span><div style="font-family:Fraunces,serif;font-size:18px;font-weight:700;margin-bottom:8px">Cheesy Lakshita</div><p style="font-size:13px;color:#6B5B8A;line-height:1.6">He made it law. When she goes full cheesy mode, he is 100% here for it — no debates.</p><div style="font-family:Fraunces,serif;font-style:italic;font-size:12px;color:#BC7A90;margin-top:10px;border-left:3px solid #FF9F43;padding-left:10px">"Cheesy Lakshita is the best version and no one can tell me otherwise" — Apr 2023</div></div>  
    <div class="proof-card pc-sage vis d2"><span class="proof-icon">💪</span><div style="font-family:Fraunces,serif;font-size:18px;font-weight:700;margin-bottom:8px">Her problem-solving brain</div><p style="font-size:13px;color:#6B5B8A;line-height:1.6">Confused between two heels? Buy jeans instead. He found this so brilliant he brought it up multiple times.</p><div style="font-family:Fraunces,serif;font-style:italic;font-size:12px;color:#BC7A90;margin-top:10px;border-left:3px solid #6BCB77;padding-left:10px">"I love your problem solving attitude — 2 heels mei confusion, toh jeans khareed li 🤣" — Aug 2023</div></div>  
    <div class="proof-card pc-dusk vis d2"><span class="proof-icon">😁</span><div style="font-family:Fraunces,serif;font-size:18px;font-weight:700;margin-bottom:8px">When she started saying "bro"</div><p style="font-size:13px;color:#6B5B8A;line-height:1.6">She picked up "bro" and "dude." He couldn't stop laughing every time he imagined her saying it.</p><div style="font-family:Fraunces,serif;font-style:italic;font-size:12px;color:#BC7A90;margin-top:10px;border-left:3px solid #A855F7;padding-left:10px">"The moment I imagine you saying it, I start laughing 😂😂" — Apr 2023</div></div>  
    <div class="proof-card pc-sky vis d3"><span class="proof-icon">😁</span><div style="font-family:Fraunces,serif;font-size:18px;font-weight:700;margin-bottom:8px">Her smile</div><p style="font-size:13px;color:#6B5B8A;line-height:1.6">He said it takes his heart rate to 200 bpm. He also said her small habits give him a smile "effortlessly" every single time.</p><div style="font-family:Fraunces,serif;font-style:italic;font-size:12px;color:#BC7A90;margin-top:10px;border-left:3px solid #4FC3F7;padding-left:10px">"Kya smile hai bhai, heart rate ekdum 200 bpm touch kar jaata hai" — Mar 2024</div></div>  
    <div class="proof-card pc-amber vis d3"><span class="proof-icon">⚡</span><div style="font-family:Fraunces,serif;font-size:18px;font-weight:700;margin-bottom:8px">She can switch in one second</div><p style="font-size:13px;color:#6B5B8A;line-height:1.6">From serious to completely unhinged in zero seconds, without either of you noticing. He called it a rare, rare quality.</p><div style="font-family:Fraunces,serif;font-style:italic;font-size:12px;color:#BC7A90;margin-top:10px;border-left:3px solid #FFD93D;padding-left:10px">"Sensical se non-sensical mei ek second mei switch — without knowing you've switched" — Jun 2025</div></div>  
  </div>  
</div>  
</section>  
  
<!-- ══ FUNNY INCIDENTS ══ -->  
  
<section style="background:linear-gradient(135deg,#F0F8FF,#FFF0F8);padding:80px 0">  
<div style="padding:0 24px;max-width:1060px;margin:0 auto">  
  <div class="vis">  
    <div class="chip chip-sage">😂 The Funny Files</div>  
    <h2 class="big-h">7 incidents that <em>made him laugh</em></h2>  
    <p class="sub">Real moments, real chaos — pulled straight from the chat, 2022 to 2025.</p>  
  </div>  
  <div style="display:flex;flex-direction:column;gap:20px">  
  
```  
<div class="vis proof-card" style="background:white;border-radius:22px;padding:28px;border:1px solid rgba(0,0,0,.06);position:relative;overflow:hidden">  
  <div style="position:absolute;top:0;left:0;bottom:0;width:4px;background:linear-gradient(180deg,#FF9F43,#FF6B9D)"></div>  
  <div style="font-size:9px;letter-spacing:.3em;text-transform:uppercase;color:#FF9F43;font-weight:700;margin-bottom:10px">🍸 May 2022 · The Drunk Call She Didn't Remember</div>  
  <p style="font-family:Fraunces,serif;font-size:17px;line-height:1.7;color:#1A0D2E;margin-bottom:8px">Lakshita called Yash one night clearly not herself — then woke up sending sorry messages to everyone. Yash told her he had the full recording saved and would play it back every time she claimed alcohol doesn't affect her.</p>  
  <div style="font-size:12px;color:#6B5B8A;font-style:italic">"Mere paas puri call recording hai 😂😂. Ab kabhi ye bola na ki mujhe nasha nahi hota, toh yeh recording sunaunga tumhe" — Yash</div>  
</div>  
  
<div class="vis proof-card d1" style="background:white;border-radius:22px;padding:28px;border:1px solid rgba(0,0,0,.06);position:relative;overflow:hidden">  
  <div style="position:absolute;top:0;left:0;bottom:0;width:4px;background:linear-gradient(180deg,#A855F7,#4FC3F7)"></div>  
  <div style="font-size:9px;letter-spacing:.3em;text-transform:uppercase;color:#A855F7;font-weight:700;margin-bottom:10px">✉️ Dec 2022 · The Cringe Letter She Kept</div>  
  <p style="font-family:Fraunces,serif;font-size:17px;line-height:1.7;color:#1A0D2E;margin-bottom:8px">She shared old school letters with him — including a very dramatic love letter she had written herself and secretly kept a copy of. Yash read it, called it "very SOTY waali vibe," and asked why she had kept her own letter. The whole backstory unravelled from there.</p>  
  <div style="font-size:12px;color:#6B5B8A;font-style:italic">"Typical teenage girlfriend waali vibes aa rahi hai 😂 — aur ye letter tumhaare paas kyu hai??" — Yash</div>  
</div>  
  
<div class="vis proof-card d1" style="background:white;border-radius:22px;padding:28px;border:1px solid rgba(0,0,0,.06);position:relative;overflow:hidden">  
  <div style="position:absolute;top:0;left:0;bottom:0;width:4px;background:linear-gradient(180deg,#FFD93D,#6BCB77)"></div>  
  <div style="font-size:9px;letter-spacing:.3em;text-transform:uppercase;color:#6BCB77;font-weight:700;margin-bottom:10px">🤡 Apr 2023 · She Pranked Him on April Fool's Day</div>  
  <p style="font-family:Fraunces,serif;font-size:17px;line-height:1.7;color:#1A0D2E;margin-bottom:8px">Yash spent all of April Fool's Day trying to prank her. She got him first — and at the end revealed it with "You've been my most successful prank ever. Congratulations!" His ego did not recover. He insisted he wasn't affected. She said "loser" and moved on.</p>  
  <div style="font-size:12px;color:#6B5B8A;font-style:italic">"What you have done today has actually hurt my ego. How can somebody prank ME??" — Yash</div>  
</div>  
  
<div class="vis proof-card d2" style="background:white;border-radius:22px;padding:28px;border:1px solid rgba(0,0,0,.06);position:relative;overflow:hidden">  
  <div style="position:absolute;top:0;left:0;bottom:0;width:4px;background:linear-gradient(180deg,#4FC3F7,#A855F7)"></div>  
  <div style="font-size:9px;letter-spacing:.3em;text-transform:uppercase;color:#4FC3F7;font-weight:700;margin-bottom:10px">📺 Mid 2023 · He Made Her the Permanent "Bigg Boss"</div>  
  <p style="font-family:Fraunces,serif;font-size:17px;line-height:1.7;color:#1A0D2E;margin-bottom:8px">At some point Yash decided Lakshita ran their friendship like a Bigg Boss host — giving tasks, creating drama, making contestants (him) suffer. He called her "Bigg Boss" so many times across 2023 it became a running nickname. He even said "Bigg Boss ke ghar mein jab Bigg Boss hi pagal ho jaaye…"</p>  
  <div style="font-size:12px;color:#6B5B8A;font-style:italic">"Roz subah sochti ho kya ki aaj Bigg Boss mein kya naya task du contestants ko?" — Yash, Apr 2023</div>  
</div>  
  
<div class="vis proof-card d2" style="background:white;border-radius:22px;padding:28px;border:1px solid rgba(0,0,0,.06);position:relative;overflow:hidden">  
  <div style="position:absolute;top:0;left:0;bottom:0;width:4px;background:linear-gradient(180deg,#FF6B9D,#FFD93D)"></div>  
  <div style="font-size:9px;letter-spacing:.3em;text-transform:uppercase;color:#FF6B9D;font-weight:700;margin-bottom:10px">👟 Aug 2023 · The Heels → Jeans Problem Solve</div>  
  <p style="font-family:Fraunces,serif;font-size:17px;line-height:1.7;color:#1A0D2E;margin-bottom:8px">She was stuck choosing between two pairs of heels for an outfit. Her solution? Just buy jeans instead. Yash found this so chaotically brilliant he brought it up multiple times. "I love your problem solving attitude," he said — completely seriously.</p>  
  <div style="font-size:12px;color:#6B5B8A;font-style:italic">"2 heels mein confusion tha, toh jeans khareed li 🤣" — Yash, Aug 2023</div>  
</div>  
  
<div class="vis proof-card d3" style="background:white;border-radius:22px;padding:28px;border:1px solid rgba(0,0,0,.06);position:relative;overflow:hidden">  
  <div style="position:absolute;top:0;left:0;bottom:0;width:4px;background:linear-gradient(180deg,#6BCB77,#4FC3F7)"></div>  
  <div style="font-size:9px;letter-spacing:.3em;text-transform:uppercase;color:#6BCB77;font-weight:700;margin-bottom:10px">📱 Jan 2024 · The Fake Emoji App That He Downloaded</div>  
  <p style="font-family:Fraunces,serif;font-size:17px;line-height:1.7;color:#1A0D2E;margin-bottom:8px">She once told him there was "an app to combine emojis." He believed her completely and actually downloaded it. He found this buried in the old chat months later and could not stop laughing — at himself for falling for it, and at her for pulling it off so casually.</p>  
  <div style="font-size:12px;color:#6B5B8A;font-style:italic">"Tum kitna bewakoof banati thi — aur mai gadho ki tarah download bhi karke baitha tha 😂" — Yash, Jan 2024</div>  
</div>  
  
<div class="vis proof-card d3" style="background:white;border-radius:22px;padding:28px;border:1px solid rgba(0,0,0,.06);position:relative;overflow:hidden">  
  <div style="position:absolute;top:0;left:0;bottom:0;width:4px;background:linear-gradient(180deg,#FFD93D,#FF9F43)"></div>  
  <div style="font-size:9px;letter-spacing:.3em;text-transform:uppercase;color:#FF9F43;font-weight:700;margin-bottom:10px">🏃 Nov 2025 · His Sister Described Her Best Friend — It Was Lakshita</div>  
  <p style="font-family:Fraunces,serif;font-size:17px;line-height:1.7;color:#1A0D2E;margin-bottom:8px">His sister Esha was gushing about a close friend she admires. Then she said: "Jab aap Manali se aaye the, aapne bola tha — aapki ek dost hai jo bilkul meri jaisi hai. Uska naam Lakshita hai." Yash started laughing because he had zero memory of saying it — but confirmed it was 100% true.</p>  
  <div style="font-size:12px;color:#6B5B8A;font-style:italic">"I started laughing — bhai I don't even remember saying it, but it's true for sure" — Yash, Nov 2025</div>  
</div>  
```  
  
  </div>  
</div>  
</section>  
  
<!-- ══ HIS WORD LIST ══ -->  
  
<section style="background:linear-gradient(135deg,#F0F8FF,#FFF0F8);padding:80px 0">  
<div style="padding:0 24px;max-width:1060px;margin:0 auto">  
  <div class="vis">  
    <div class="chip chip-gold">📝 Women's Day 2026</div>  
    <h2 class="big-h">Every word he used <em>to describe her</em></h2>  
    <p class="sub">He sat down and wrote this out. Unsolicited. Unprompted. Every word is real.</p>  
  </div>  
  <div class="vis" style="background:linear-gradient(135deg,#1A0D2E,#0D2040);border-radius:28px;padding:clamp(32px,5vw,60px);position:relative;overflow:hidden">  
    <div style="position:absolute;top:-20px;right:20px;font-family:Fraunces,serif;font-size:200px;color:rgba(255,255,255,.03);line-height:1">"</div>  
    <div style="font-size:10px;letter-spacing:.4em;text-transform:uppercase;color:rgba(255,159,67,.6);margin-bottom:20px;position:relative">March 8, 2026 — Women's Day · Yash to Lakshita</div>  
    <div style="display:flex;flex-wrap:wrap;gap:10px;margin-bottom:28px;position:relative">  
      <span style="background:rgba(255,107,157,.2);border:1px solid rgba(255,107,157,.4);color:#FF6B9D;padding:8px 16px;border-radius:100px;font-size:13px;font-weight:600">Beautiful</span>  
      <span style="background:rgba(255,159,67,.2);border:1px solid rgba(255,159,67,.4);color:#FF9F43;padding:8px 16px;border-radius:100px;font-size:13px;font-weight:600">Inspiring</span>  
      <span style="background:rgba(107,203,119,.2);border:1px solid rgba(107,203,119,.4);color:#6BCB77;padding:8px 16px;border-radius:100px;font-size:13px;font-weight:600">Pretty</span>  
      <span style="background:rgba(168,85,247,.2);border:1px solid rgba(168,85,247,.4);color:#A855F7;padding:8px 16px;border-radius:100px;font-size:13px;font-weight:600">Smart</span>  
      <span style="background:rgba(79,195,247,.2);border:1px solid rgba(79,195,247,.4);color:#4FC3F7;padding:8px 16px;border-radius:100px;font-size:13px;font-weight:600">Intelligent</span>  
      <span style="background:rgba(255,211,61,.2);border:1px solid rgba(255,211,61,.4);color:#FFD93D;padding:8px 16px;border-radius:100px;font-size:13px;font-weight:600">Dedicated</span>  
      <span style="background:rgba(255,107,157,.2);border:1px solid rgba(255,107,157,.4);color:#FF6B9D;padding:8px 16px;border-radius:100px;font-size:13px;font-weight:600">Hardworking</span>  
      <span style="background:rgba(255,159,67,.2);border:1px solid rgba(255,159,67,.4);color:#FF9F43;padding:8px 16px;border-radius:100px;font-size:13px;font-weight:600">Entertaining</span>  
      <span style="background:rgba(107,203,119,.2);border:1px solid rgba(107,203,119,.4);color:#6BCB77;padding:8px 16px;border-radius:100px;font-size:13px;font-weight:600">Loving</span>  
      <span style="background:rgba(168,85,247,.2);border:1px solid rgba(168,85,247,.4);color:#A855F7;padding:8px 16px;border-radius:100px;font-size:13px;font-weight:600">Ambitious</span>  
      <span style="background:rgba(79,195,247,.2);border:1px solid rgba(79,195,247,.4);color:#4FC3F7;padding:8px 16px;border-radius:100px;font-size:13px;font-weight:600">Caring</span>  
      <span style="background:rgba(255,211,61,.2);border:1px solid rgba(255,211,61,.4);color:#FFD93D;padding:8px 16px;border-radius:100px;font-size:13px;font-weight:600">Stubborn 😂</span>  
    </div>  
    <p style="font-family:Fraunces,serif;font-style:italic;font-size:clamp(16px,2vw,20px);color:rgba(255,255,255,.7);line-height:1.8;position:relative">"Don't know about other people but I am definitely celebrating your presence in my life."</p>  
    <div style="font-size:10px;letter-spacing:.2em;text-transform:uppercase;color:rgba(255,255,255,.25);margin-top:14px;position:relative">— Yash to Lakshita · Mar 8, 2026</div>  
  </div>  
</div>  
</section>  
  
<!-- ══ CLOSING ══ -->  
  
<section class="closing">  
  <div class="closing-halo"></div>  
  <p class="closing-title" style="position:relative">The data, translated:</p>  
  <h2 class="closing-big" style="position:relative">She is not<br><em>just a friend</em></h2>  
  <div class="closing-caveat">She is home. 🏡</div>  
  <p class="closing-para">83,540 messages. 90% response rate. 524 check-ins. 13,677 late nights. 635 days of texting first. One honest, vulnerable message about how she makes him feel weird when she's gone.<br><br>The numbers say what he sometimes can't.</p>  
  <p class="closing-sig">Extracted from 3 years of WhatsApp · Made with 💛 by Yash · 2026</p>  
</section>  
  
<script>  
// COUNT UP  
const obs = new IntersectionObserver(entries => {  
  entries.forEach(e => {  
    if(e.isIntersecting) {  
      const target = parseInt(e.target.dataset.count);  
      let cur = 0; const step = target / 60;  
      const t = setInterval(() => {  
        cur = Math.min(cur + step, target);  
        e.target.textContent = Math.floor(cur).toLocaleString();  
        if(cur >= target) clearInterval(t);  
      }, 25);  
      obs.unobserve(e.target);  
    }  
  });  
}, {threshold:.5});  
document.querySelectorAll('[data-count]').forEach(el => obs.observe(el));  
  
// REVEAL  
const ro = new IntersectionObserver(entries => {  
  entries.forEach(e => { if(e.isIntersecting) e.target.classList.add('on'); });  
}, {threshold:.1});  
document.querySelectorAll('.vis, .ct-item').forEach(el => ro.observe(el));  
</script>  
  
</body>  
</html>  
