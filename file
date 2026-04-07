<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width,initial-scale=1.0"/>
<title>Prashant Kishor Sharma — PhD Researcher · Mechanical Engineering · NCKU Taiwan</title>
<meta name="description" content="PhD Researcher in AI-Integrated Microfluidics, MEMS, Biomedical Engineering & Semiconductor Systems at NCKU Taiwan."/>
<link rel="preconnect" href="https://fonts.googleapis.com"/>
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin/>
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;500;600;700;800&family=Instrument+Serif:ital@0;1&family=JetBrains+Mono:wght@300;400;500&family=DM+Sans:ital,opsz,wght@0,9..40,300;0,9..40,400;0,9..40,500;1,9..40,300&display=swap" rel="stylesheet"/>
<style>
/* ═══════════════════════════════════════════
   DESIGN TOKENS
═══════════════════════════════════════════ */
:root {
  --bg:       #07090f;
  --bg2:      #0a0d16;
  --bg3:      #0d1120;
  --card:     #111827;
  --card2:    #151e30;
  --border:   rgba(255,255,255,0.06);
  --primary:  #00e5b0;
  --primary2: #00c49a;
  --blue:     #3b82f6;
  --blue2:    #60a5fa;
  --amber:    #f59e0b;
  --amber2:   #fbbf24;
  --rose:     #f43f5e;
  --muted:    #4b5a72;
  --muted2:   #7a90b0;
  --text:     #e2eaf6;
  --text2:    #a8bcda;
  --white:    #ffffff;
}

/* ═══════════════════════════════════════════
   RESET & BASE
═══════════════════════════════════════════ */
*,*::before,*::after { box-sizing:border-box; margin:0; padding:0; }
html { scroll-behavior:smooth; }
body {
  font-family:'DM Sans',sans-serif;
  background:var(--bg); color:var(--text);
  overflow-x:hidden; line-height:1.7;
}
/* grain texture */
body::before {
  content:''; position:fixed; inset:0; pointer-events:none; z-index:9999; opacity:0.35;
  background-image:url("data:image/svg+xml,%3Csvg viewBox='0 0 512 512' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.75' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.04'/%3E%3C/svg%3E");
}
#bg-canvas { position:fixed; inset:0; pointer-events:none; z-index:0; }

/* ═══════════════════════════════════════════
   NAV
═══════════════════════════════════════════ */
nav {
  position:fixed; top:0; left:0; right:0; z-index:500;
  padding:1.1rem 3rem;
  display:flex; align-items:center; justify-content:space-between;
  background:rgba(7,9,15,0.5);
  backdrop-filter:blur(20px) saturate(180%);
  border-bottom:1px solid var(--border);
  transition:background 0.4s;
}
nav.scrolled { background:rgba(7,9,15,0.92); }
.nav-logo {
  font-family:'Syne',sans-serif; font-size:0.8rem; font-weight:700;
  letter-spacing:0.15em; text-transform:uppercase;
  color:var(--primary); text-decoration:none;
  display:flex; align-items:center; gap:0.6rem;
}
.nav-logo-dot {
  width:8px; height:8px; border-radius:50%;
  background:var(--primary); box-shadow:0 0 10px var(--primary);
  animation:pulse-dot 2.5s infinite;
}
@keyframes pulse-dot {
  0%,100% { transform:scale(1); opacity:1; }
  50% { transform:scale(0.6); opacity:0.5; }
}
.nav-links { display:flex; gap:2rem; list-style:none; }
.nav-links a {
  font-family:'JetBrains Mono',monospace;
  font-size:0.68rem; letter-spacing:0.1em; text-transform:uppercase;
  color:var(--muted2); text-decoration:none; transition:color 0.2s;
  position:relative;
}
.nav-links a::after {
  content:''; position:absolute; bottom:-4px; left:0; right:0;
  height:1px; background:var(--primary);
  transform:scaleX(0); transform-origin:left; transition:transform 0.2s;
}
.nav-links a:hover { color:var(--primary); }
.nav-links a:hover::after { transform:scaleX(1); }
.nav-cta {
  font-family:'Syne',sans-serif; font-size:0.72rem; font-weight:600;
  letter-spacing:0.08em; text-transform:uppercase;
  color:var(--bg); background:var(--primary);
  padding:0.5rem 1.2rem; border-radius:3px; text-decoration:none;
  transition:background 0.2s, transform 0.15s;
}
.nav-cta:hover { background:var(--primary2); transform:translateY(-1px); }

/* ═══════════════════════════════════════════
   LAYOUT UTILITIES
═══════════════════════════════════════════ */
section { position:relative; z-index:1; }
.container { max-width:1140px; margin:0 auto; padding:0 2.5rem; }
.chip {
  font-family:'JetBrains Mono',monospace;
  font-size:0.65rem; letter-spacing:0.18em; text-transform:uppercase;
  color:var(--primary); display:inline-flex; align-items:center; gap:0.6rem;
  margin-bottom:1rem;
}
.chip::before { content:''; width:20px; height:1px; background:var(--primary); }
h2.stitle {
  font-family:'Syne',sans-serif;
  font-size:clamp(2.2rem,4vw,3.2rem);
  font-weight:700; color:var(--white); line-height:1.1; margin-bottom:0.5rem;
}
h2.stitle em {
  font-family:'Instrument Serif',serif;
  font-style:italic; color:var(--primary); font-weight:400;
}
.rule {
  width:48px; height:2px;
  background:linear-gradient(90deg,var(--primary),transparent);
  margin:1.4rem 0 3.5rem;
}
.btn-p {
  font-family:'Syne',sans-serif; font-size:0.8rem; font-weight:700;
  letter-spacing:0.06em; text-transform:uppercase;
  padding:0.85rem 2rem; background:var(--primary);
  color:var(--bg); border-radius:3px; text-decoration:none;
  transition:background 0.2s, transform 0.15s; display:inline-block;
}
.btn-p:hover { background:var(--primary2); transform:translateY(-2px); }
.btn-g {
  font-family:'Syne',sans-serif; font-size:0.8rem; font-weight:600;
  letter-spacing:0.06em; text-transform:uppercase;
  padding:0.85rem 2rem; background:transparent;
  color:var(--text2); border:1px solid rgba(255,255,255,0.12);
  border-radius:3px; text-decoration:none;
  transition:border-color 0.2s, color 0.2s, transform 0.15s;
}
.btn-g:hover { border-color:var(--primary); color:var(--primary); transform:translateY(-2px); }

/* ═══════════════════════════════════════════
   HERO
═══════════════════════════════════════════ */
#hero {
  min-height:100vh;
  display:grid; grid-template-columns:1fr 1fr;
  align-items:center; gap:4rem;
  max-width:1140px; margin:0 auto;
  padding:7rem 2.5rem 5rem;
}
.hero-eyebrow {
  font-family:'JetBrains Mono',monospace;
  font-size:0.7rem; letter-spacing:0.2em; text-transform:uppercase;
  color:var(--primary); display:inline-flex; align-items:center; gap:0.8rem;
  border:1px solid rgba(0,229,176,0.2);
  padding:0.45rem 1rem; border-radius:100px; margin-bottom:2rem;
}
.hero-eyebrow-dot { width:6px; height:6px; border-radius:50%; background:var(--primary); animation:pulse-dot 2s infinite; }
h1.hero-h1 {
  font-family:'Syne',sans-serif;
  font-size:clamp(3rem,5.5vw,5rem);
  font-weight:800; line-height:1.0;
  color:var(--white); margin-bottom:0.5rem; letter-spacing:-0.02em;
}
h1.hero-h1 span {
  font-family:'Instrument Serif',serif;
  font-weight:400; font-style:italic; color:var(--primary); letter-spacing:0;
}
.hero-desc {
  font-size:1rem; color:var(--text2); line-height:1.8;
  max-width:500px; margin:1.8rem 0 2.4rem;
}
.hero-desc strong { color:var(--text); }
.hero-tags { display:flex; flex-wrap:wrap; gap:0.5rem; margin-bottom:2.4rem; }
.htag {
  font-family:'JetBrains Mono',monospace;
  font-size:0.65rem; letter-spacing:0.08em;
  padding:0.3rem 0.75rem; border-radius:3px;
  background:rgba(59,130,246,0.08);
  border:1px solid rgba(59,130,246,0.18); color:var(--blue2);
}
.hero-btns { display:flex; gap:1rem; flex-wrap:wrap; }

/* Hero Visual */
.hero-visual { display:flex; align-items:center; justify-content:center; position:relative; }
.hero-vis-wrap { position:relative; width:100%; aspect-ratio:1/1; max-width:440px; }
.hero-vis-svg { width:100%; height:100%; }
.metrics-float {
  position:absolute;
  display:grid; grid-template-columns:1fr 1fr;
  gap:1px; background:rgba(0,229,176,0.06);
  border:1px solid rgba(0,229,176,0.12);
  border-radius:12px; overflow:hidden;
  top:50%; left:50%; transform:translate(-50%,-50%); width:230px;
}
.metric-cell { background:var(--bg2); padding:1.2rem 1rem; text-align:center; }
.metric-n {
  font-family:'Syne',sans-serif; font-size:2rem; font-weight:800;
  color:var(--primary); display:block; line-height:1; margin-bottom:0.3rem;
}
.metric-l {
  font-family:'JetBrains Mono',monospace; font-size:0.58rem;
  letter-spacing:0.12em; text-transform:uppercase; color:var(--muted);
}

/* ═══════════════════════════════════════════
   DUAL TRACK
═══════════════════════════════════════════ */
#dualtrack { background:var(--bg2); padding:6rem 0; border-top:1px solid var(--border); }
.dt-grid { display:grid; grid-template-columns:1fr 1fr; gap:1.5rem; }
.dt-card {
  border-radius:12px; padding:2.5rem; position:relative; overflow:hidden;
}
.dt-card.academic { background:var(--card); border:1px solid rgba(59,130,246,0.15); }
.dt-card.industry  { background:var(--card); border:1px solid rgba(0,229,176,0.15); }
.dt-card::before { content:''; position:absolute; top:0; left:0; right:0; height:3px; }
.dt-card.academic::before { background:linear-gradient(90deg,var(--blue),transparent); }
.dt-card.industry::before  { background:linear-gradient(90deg,var(--primary),transparent); }
.dt-badge {
  font-family:'JetBrains Mono',monospace; font-size:0.62rem;
  letter-spacing:0.15em; text-transform:uppercase;
  padding:0.25rem 0.7rem; border-radius:100px;
  margin-bottom:1.2rem; display:inline-block;
}
.dt-card.academic .dt-badge { color:var(--blue2); background:rgba(59,130,246,0.08); border:1px solid rgba(59,130,246,0.2); }
.dt-card.industry  .dt-badge { color:var(--primary); background:rgba(0,229,176,0.06); border:1px solid rgba(0,229,176,0.2); }
.dt-card h3 { font-family:'Syne',sans-serif; font-weight:700; font-size:1.4rem; color:var(--white); margin-bottom:1rem; line-height:1.2; }
.dt-list { list-style:none; }
.dt-list li {
  font-size:0.88rem; color:var(--text2);
  padding:0.55rem 0 0.55rem 1.2rem;
  border-bottom:1px solid var(--border);
  position:relative; line-height:1.5;
}
.dt-list li::before { content:'▸'; position:absolute; left:0; font-size:0.65rem; top:0.7rem; }
.dt-card.academic .dt-list li::before { color:var(--blue); }
.dt-card.industry  .dt-list li::before { color:var(--primary); }
.dt-list li:last-child { border-bottom:none; }

/* ═══════════════════════════════════════════
   ABOUT
═══════════════════════════════════════════ */
#about { background:var(--bg); padding:7rem 0; }
.about-grid { display:grid; grid-template-columns:3fr 2fr; gap:6rem; align-items:start; }
.about-p { font-size:1rem; color:var(--text2); line-height:1.9; margin-bottom:1.3rem; }
.about-p.lead { font-family:'Instrument Serif',serif; font-size:1.25rem; color:var(--text); line-height:1.7; font-style:italic; }
.patent-block {
  margin-top:2rem;
  background:linear-gradient(135deg,rgba(0,229,176,0.05),rgba(245,158,11,0.04));
  border:1px solid rgba(0,229,176,0.12); border-radius:10px; padding:1.4rem;
  display:flex; gap:1rem; align-items:flex-start;
}
.patent-ico { font-size:1.5rem; flex-shrink:0; }
.patent-lbl { font-family:'JetBrains Mono',monospace; font-size:0.62rem; text-transform:uppercase; letter-spacing:0.1em; color:var(--muted2); margin-bottom:0.3rem; }
.patent-t { font-size:0.88rem; color:var(--text); line-height:1.5; margin-bottom:0.3rem; }
.patent-n { font-family:'JetBrains Mono',monospace; font-size:0.72rem; color:var(--amber); }
.info-stack { display:flex; flex-direction:column; gap:0.6rem; }
.info-row {
  display:flex; gap:0.8rem; align-items:flex-start;
  background:var(--card); border-radius:8px; padding:0.9rem 1rem;
  border-left:2px solid var(--primary);
}
.info-ico { font-size:1rem; flex-shrink:0; margin-top:1px; }
.info-lbl { font-family:'JetBrains Mono',monospace; font-size:0.6rem; text-transform:uppercase; letter-spacing:0.1em; color:var(--muted); margin-bottom:2px; }
.info-v { font-size:0.88rem; color:var(--text2); }
.info-v a { color:var(--primary); text-decoration:none; }

/* ═══════════════════════════════════════════
   EDUCATION
═══════════════════════════════════════════ */
#education { background:var(--bg2); padding:7rem 0; border-top:1px solid var(--border); }
.edu-wrap { display:grid; grid-template-columns:repeat(3,1fr); gap:1.5rem; }
.edu-card {
  background:var(--card); border:1px solid var(--border); border-radius:12px; padding:2rem;
  position:relative; overflow:hidden; transition:transform 0.25s, border-color 0.25s;
}
.edu-card:hover { transform:translateY(-4px); border-color:rgba(0,229,176,0.2); }
.edu-card::after {
  content:''; position:absolute; bottom:0; left:0; right:0; height:2px;
  background:linear-gradient(90deg,var(--primary),transparent);
}
.edu-badge {
  font-family:'JetBrains Mono',monospace; font-size:0.6rem; letter-spacing:0.12em; text-transform:uppercase;
  color:var(--primary); background:rgba(0,229,176,0.07); border:1px solid rgba(0,229,176,0.18);
  padding:0.2rem 0.6rem; border-radius:100px; display:inline-block; margin-bottom:1rem;
}
.edu-deg { font-family:'Syne',sans-serif; font-weight:700; font-size:1rem; color:var(--white); margin-bottom:0.4rem; line-height:1.3; }
.edu-uni { font-size:0.85rem; color:var(--muted2); margin-bottom:0.2rem; }
.edu-loc { font-size:0.75rem; color:var(--muted); }

/* ═══════════════════════════════════════════
   IMPACT METRICS
═══════════════════════════════════════════ */
#impact { background:var(--bg2); padding:5rem 0; border-top:1px solid var(--border); }
.impact-grid {
  display:grid; grid-template-columns:repeat(5,1fr); gap:1px;
  background:var(--border); border-radius:12px; overflow:hidden;
  border:1px solid var(--border);
}
.impact-cell { background:var(--card); padding:2rem 1.2rem; text-align:center; }
.impact-n {
  font-family:'Syne',sans-serif; font-weight:800;
  font-size:2.4rem; color:var(--primary); display:block; line-height:1; margin-bottom:0.4rem;
}
.impact-n.blue { color:var(--blue2); }
.impact-n.amber { color:var(--amber2); }
.impact-l {
  font-family:'JetBrains Mono',monospace; font-size:0.6rem;
  letter-spacing:0.12em; text-transform:uppercase; color:var(--muted2); line-height:1.4;
}

/* ═══════════════════════════════════════════
   RESEARCH EXPERIENCE
═══════════════════════════════════════════ */
#research { background:var(--bg); padding:7rem 0; }
.research-grid { display:grid; grid-template-columns:1fr 1fr; gap:1.5rem; }
.rc {
  background:var(--card); border:1px solid var(--border); border-radius:12px; padding:2rem;
  position:relative; overflow:hidden; transition:transform 0.25s, border-color 0.25s;
}
.rc:hover { transform:translateY(-4px); border-color:rgba(0,229,176,0.18); }
.rc::before {
  content:''; position:absolute; top:0; left:0; right:0; height:2px;
  background:linear-gradient(90deg,var(--primary),transparent);
}
.rc-when { font-family:'JetBrains Mono',monospace; font-size:0.62rem; letter-spacing:0.1em; text-transform:uppercase; color:var(--amber); margin-bottom:0.6rem; }
.rc-title { font-family:'Syne',sans-serif; font-weight:700; font-size:1.1rem; color:var(--white); margin-bottom:0.25rem; }
.rc-inst { font-size:0.82rem; color:var(--muted2); margin-bottom:1rem; }
.rc-tags { display:flex; flex-wrap:wrap; gap:0.4rem; margin-bottom:1rem; }
.tag {
  font-family:'JetBrains Mono',monospace; font-size:0.6rem; letter-spacing:0.06em; text-transform:uppercase;
  color:var(--primary2); background:rgba(0,229,176,0.06); border:1px solid rgba(0,229,176,0.14);
  padding:0.18rem 0.55rem; border-radius:3px;
}
.rc-ul { list-style:none; border-top:1px solid var(--border); padding-top:1rem; }
.rc-ul li {
  font-size:0.83rem; color:var(--text2); padding:0.4rem 0 0.4rem 1.1rem;
  position:relative; line-height:1.55;
}
.rc-ul li::before { content:'▸'; position:absolute; left:0; color:var(--primary); font-size:0.65rem; top:0.55rem; }

/* ═══════════════════════════════════════════
   PUBLICATIONS
═══════════════════════════════════════════ */
#publications { background:var(--bg2); padding:7rem 0; border-top:1px solid var(--border); }
.pub-featured {
  background:var(--card); border-radius:12px; border:1px solid rgba(0,229,176,0.15);
  padding:2rem 2.2rem; margin-bottom:1rem; position:relative; overflow:hidden;
  transition:transform 0.2s, border-color 0.2s;
}
.pub-featured:hover { transform:translateX(4px); border-color:rgba(0,229,176,0.3); }
.pub-featured::before { content:''; position:absolute; left:0; top:0; bottom:0; width:3px; background:var(--primary); }
.pub-year { position:absolute; right:2rem; top:1.8rem; font-family:'JetBrains Mono',monospace; font-size:0.68rem; color:var(--muted); }
.pub-bdg {
  display:inline-flex; align-items:center; gap:0.4rem;
  font-family:'JetBrains Mono',monospace; font-size:0.58rem; letter-spacing:0.1em; text-transform:uppercase;
  color:var(--amber); background:rgba(245,158,11,0.08); border:1px solid rgba(245,158,11,0.2);
  padding:0.22rem 0.65rem; border-radius:100px; margin-bottom:0.7rem;
}
.pub-title { font-family:'Instrument Serif',serif; font-size:1.05rem; color:var(--white); line-height:1.45; margin-bottom:0.4rem; }
.pub-authors { font-size:0.8rem; color:var(--muted2); margin-bottom:0.3rem; }
.pub-journal { font-size:0.8rem; color:var(--primary); font-style:italic; }
.pub-review-list { margin-top:1rem; }
.pub-row {
  display:grid; grid-template-columns:48px 1fr; gap:1.5rem; padding:1.3rem 0;
  border-bottom:1px solid var(--border); align-items:start; transition:opacity 0.2s;
}
.pub-row:hover { opacity:0.82; }
.pub-yr { font-family:'JetBrains Mono',monospace; font-size:0.7rem; color:var(--muted); padding-top:3px; }
.pub-t2 { font-size:0.9rem; color:var(--text); margin-bottom:0.3rem; line-height:1.45; }
.pub-m2 { font-size:0.78rem; color:var(--muted2); font-style:italic; }
.pub-status {
  display:inline-block; font-family:'JetBrains Mono',monospace;
  font-size:0.58rem; letter-spacing:0.08em; text-transform:uppercase;
  color:var(--amber); background:rgba(245,158,11,0.07); border:1px solid rgba(245,158,11,0.18);
  padding:0.12rem 0.45rem; border-radius:3px; margin-left:0.4rem; vertical-align:middle;
}

/* ═══════════════════════════════════════════
   SEMICONDUCTOR FABRICATION EXPERIENCE
═══════════════════════════════════════════ */
#semicon-exp {
  background:var(--bg3); padding:7rem 0;
  border-top:1px solid var(--border);
  position:relative; z-index:1;
}
#semicon-exp::before {
  content:''; position:absolute; inset:0; pointer-events:none;
  background-image:
    linear-gradient(rgba(0,229,176,0.025) 1px,transparent 1px),
    linear-gradient(90deg,rgba(0,229,176,0.025) 1px,transparent 1px);
  background-size:40px 40px;
}
.se-intro { font-size:1rem; color:var(--text2); max-width:680px; line-height:1.85; margin-bottom:3.5rem; }
.se-intro strong { color:var(--text); }
.se-pillars { display:grid; grid-template-columns:repeat(3,1fr); gap:1.5rem; margin-bottom:3rem; }
.se-pillar {
  background:var(--card); border-radius:14px; border:1px solid var(--border);
  padding:2rem; position:relative; overflow:hidden;
  transition:transform 0.25s, border-color 0.25s;
}
.se-pillar:hover { transform:translateY(-5px); }
.se-pillar.p-mems   { border-top:3px solid var(--primary); }
.se-pillar.p-sensor { border-top:3px solid var(--blue); }
.se-pillar.p-clean  { border-top:3px solid var(--amber); }
.se-pillar.p-mems:hover   { border-color:rgba(0,229,176,0.35); }
.se-pillar.p-sensor:hover { border-color:rgba(59,130,246,0.35); }
.se-pillar.p-clean:hover  { border-color:rgba(245,158,11,0.35); }
.se-pillar-icon { font-size:2rem; display:block; margin-bottom:1rem; }
.se-pillar-cat {
  font-family:'JetBrains Mono',monospace; font-size:0.6rem;
  letter-spacing:0.15em; text-transform:uppercase; margin-bottom:0.5rem;
}
.p-mems   .se-pillar-cat { color:var(--primary); }
.p-sensor .se-pillar-cat { color:var(--blue2); }
.p-clean  .se-pillar-cat { color:var(--amber); }
.se-pillar-title { font-family:'Syne',sans-serif; font-weight:700; font-size:1.05rem; color:var(--white); line-height:1.3; margin-bottom:1rem; }
.se-pillar-list { list-style:none; }
.se-pillar-list li {
  font-size:0.82rem; color:var(--text2); line-height:1.6;
  padding:0.45rem 0 0.45rem 1.1rem; position:relative;
  border-bottom:1px solid rgba(255,255,255,0.04);
}
.se-pillar-list li:last-child { border-bottom:none; }
.se-pillar-list li::before { content:'▸'; position:absolute; left:0; font-size:0.62rem; top:0.65rem; }
.p-mems   li::before { color:var(--primary); }
.p-sensor li::before { color:var(--blue2); }
.p-clean  li::before { color:var(--amber); }

/* Process flow */
.se-process {
  background:var(--card2); border:1px solid rgba(0,229,176,0.1);
  border-radius:12px; padding:2rem 2.4rem; margin-bottom:2.5rem;
}
.se-process-title {
  font-family:'JetBrains Mono',monospace; font-size:0.62rem;
  letter-spacing:0.18em; text-transform:uppercase; color:var(--muted2); margin-bottom:1.4rem;
}
.se-flow { display:flex; align-items:center; flex-wrap:wrap; }
.se-flow-step {
  display:flex; flex-direction:column; align-items:center;
  text-align:center; flex:1; min-width:80px; padding:0 0.5rem;
}
.se-flow-node {
  width:48px; height:48px; border-radius:50%;
  display:flex; align-items:center; justify-content:center;
  font-size:1.1rem; margin-bottom:0.6rem; transition:transform 0.2s;
}
.se-flow-step:hover .se-flow-node { transform:scale(1.12); }
.se-flow-node.teal  { background:rgba(0,229,176,0.12); border:1px solid rgba(0,229,176,0.3); }
.se-flow-node.blue  { background:rgba(59,130,246,0.1);  border:1px solid rgba(59,130,246,0.25); }
.se-flow-node.amber { background:rgba(245,158,11,0.1);  border:1px solid rgba(245,158,11,0.25); }
.se-flow-label { font-family:'JetBrains Mono',monospace; font-size:0.6rem; letter-spacing:0.05em; text-transform:uppercase; color:var(--muted2); line-height:1.4; }
.se-flow-arrow { color:rgba(0,229,176,0.25); font-size:1.2rem; flex-shrink:0; margin-bottom:1.5rem; }

/* Badges */
.se-badges { display:flex; flex-wrap:wrap; gap:0.6rem; margin-top:1rem; }
.se-badge {
  font-family:'JetBrains Mono',monospace; font-size:0.65rem;
  letter-spacing:0.06em; text-transform:uppercase;
  padding:0.35rem 0.85rem; border-radius:4px; transition:filter 0.2s;
}
.se-badge:hover { filter:brightness(1.2); }
.se-badge.teal  { color:var(--primary); background:rgba(0,229,176,0.07); border:1px solid rgba(0,229,176,0.2); }
.se-badge.blue  { color:var(--blue2);   background:rgba(59,130,246,0.07); border:1px solid rgba(59,130,246,0.2); }
.se-badge.amber { color:var(--amber2);  background:rgba(245,158,11,0.07); border:1px solid rgba(245,158,11,0.2); }

/* ═══════════════════════════════════════════
   TAIWAN SEMICONDUCTOR
═══════════════════════════════════════════ */
#taiwan { background:var(--bg); padding:7rem 0; border-top:1px solid var(--border); }
.tw-intro { font-size:1rem; color:var(--text2); max-width:700px; line-height:1.85; margin-bottom:3.5rem; }
.tw-intro strong { color:var(--text); }
.tw-layout { display:grid; grid-template-columns:1fr 1fr; gap:2rem; align-items:start; }
.tw-wafer-wrap { display:flex; justify-content:center; align-items:center; }
.tw-wafer-svg { width:100%; max-width:380px; }
.tw-cards { display:flex; flex-direction:column; gap:1rem; }
.tw-card {
  background:var(--card); border-radius:10px; padding:1.4rem 1.6rem;
  border:1px solid var(--border);
  display:grid; grid-template-columns:42px 1fr; gap:1rem; align-items:start;
  transition:border-color 0.2s, transform 0.2s;
}
.tw-card:hover { border-color:rgba(0,229,176,0.2); transform:translateX(4px); }
.tw-card-ico {
  width:42px; height:42px; border-radius:8px;
  display:flex; align-items:center; justify-content:center; font-size:1.2rem; flex-shrink:0;
}
.tw-card-ico.teal  { background:rgba(0,229,176,0.08); }
.tw-card-ico.blue  { background:rgba(59,130,246,0.08); }
.tw-card-ico.amber { background:rgba(245,158,11,0.08); }
.tw-card-ico.rose  { background:rgba(244,63,94,0.08); }
.tw-card-label { font-family:'JetBrains Mono',monospace; font-size:0.6rem; letter-spacing:0.12em; text-transform:uppercase; color:var(--muted2); margin-bottom:0.3rem; }
.tw-card-title { font-family:'Syne',sans-serif; font-weight:700; font-size:0.92rem; color:var(--white); margin-bottom:0.3rem; }
.tw-card-desc { font-size:0.8rem; color:var(--text2); line-height:1.55; }
.tw-ecosystem {
  margin-top:2.5rem; padding:1.4rem 1.8rem;
  background:var(--card2); border:1px solid rgba(0,229,176,0.1); border-radius:10px;
}
.tw-eco-label { font-family:'JetBrains Mono',monospace; font-size:0.6rem; letter-spacing:0.15em; text-transform:uppercase; color:var(--muted2); margin-bottom:1rem; }
.tw-eco-logos { display:flex; flex-wrap:wrap; gap:0.6rem; }
.tw-eco-tag {
  font-family:'JetBrains Mono',monospace; font-size:0.68rem; letter-spacing:0.06em;
  padding:0.35rem 0.9rem; border-radius:4px;
  border:1px solid rgba(255,255,255,0.08); color:var(--text2); background:var(--card);
  transition:border-color 0.2s, color 0.2s;
}
.tw-eco-tag:hover { border-color:rgba(0,229,176,0.25); color:var(--primary); }
.tw-eco-tag.highlight { border-color:rgba(0,229,176,0.2); color:var(--primary); background:rgba(0,229,176,0.05); }
.mems-bridge {
  margin-top:3.5rem;
  background:linear-gradient(135deg,rgba(59,130,246,0.06),rgba(0,229,176,0.05));
  border:1px solid rgba(59,130,246,0.15); border-radius:12px; padding:2rem 2.2rem;
  display:grid; grid-template-columns:1fr auto 1fr auto 1fr; gap:1.2rem;
  align-items:center; text-align:center;
}
.mb-item-icon { font-size:1.6rem; display:block; margin-bottom:0.5rem; }
.mb-item-title { font-family:'Syne',sans-serif; font-weight:700; font-size:0.9rem; color:var(--white); margin-bottom:0.3rem; }
.mb-item-desc { font-size:0.78rem; color:var(--text2); line-height:1.5; }
.mb-arrow { font-size:1.6rem; color:var(--primary); opacity:0.4; display:flex; align-items:center; justify-content:center; }

/* ═══════════════════════════════════════════
   INDUSTRY APPLICATIONS
═══════════════════════════════════════════ */
#applications { background:var(--bg2); padding:7rem 0; border-top:1px solid var(--border); }
.app-intro { font-size:1rem; color:var(--text2); max-width:640px; line-height:1.8; margin-bottom:3rem; }
.app-grid { display:grid; grid-template-columns:repeat(3,1fr); gap:1.2rem; }
.app-card {
  background:var(--card); border:1px solid var(--border); border-radius:12px; padding:1.8rem;
  transition:transform 0.2s, border-color 0.2s;
}
.app-card:hover { transform:translateY(-4px); border-color:rgba(0,229,176,0.15); }
.app-icon { font-size:1.8rem; display:block; margin-bottom:1rem; }
.app-sector { font-family:'JetBrains Mono',monospace; font-size:0.6rem; letter-spacing:0.12em; text-transform:uppercase; color:var(--blue2); margin-bottom:0.5rem; }
.app-name { font-family:'Syne',sans-serif; font-weight:700; font-size:0.98rem; color:var(--white); margin-bottom:0.6rem; line-height:1.3; }
.app-desc { font-size:0.82rem; color:var(--text2); line-height:1.6; }

/* ═══════════════════════════════════════════
   ACHIEVEMENTS
═══════════════════════════════════════════ */
#achievements { background:var(--bg); padding:7rem 0; }
.ach-grid { display:grid; grid-template-columns:repeat(3,1fr); gap:1.2rem; }
.ach-card {
  background:var(--card); border:1px solid var(--border); border-radius:10px; padding:1.6rem;
  transition:transform 0.2s, border-color 0.2s;
}
.ach-card:hover { transform:translateY(-3px); border-color:rgba(245,158,11,0.2); }
.ach-ico { font-size:1.3rem; display:block; margin-bottom:0.9rem; }
.ach-t { font-size:0.9rem; color:var(--white); font-weight:500; margin-bottom:0.4rem; line-height:1.4; }
.ach-d { font-size:0.78rem; color:var(--muted2); line-height:1.6; }

/* ═══════════════════════════════════════════
   SKILLS
═══════════════════════════════════════════ */
#skills { background:var(--bg2); padding:7rem 0; border-top:1px solid var(--border); }
.skills-wrap { display:grid; grid-template-columns:repeat(4,1fr); gap:2.5rem; }
.sg-title { font-family:'JetBrains Mono',monospace; font-size:0.65rem; letter-spacing:0.15em; text-transform:uppercase; color:var(--amber); margin-bottom:1.4rem; }
.skill-row {
  display:flex; justify-content:space-between; align-items:center;
  padding:0.65rem 0; border-bottom:1px solid rgba(255,255,255,0.04);
}
.skill-nm { font-size:0.85rem; color:var(--text2); }
.skill-bar { width:90px; height:2px; background:rgba(255,255,255,0.06); border-radius:1px; overflow:hidden; }
.skill-fill {
  height:100%; border-radius:1px;
  background:linear-gradient(90deg,var(--primary),var(--primary2));
  transform:scaleX(0); transform-origin:left;
}

/* ═══════════════════════════════════════════
   CONTACT
═══════════════════════════════════════════ */
#contact { background:var(--bg); padding:7rem 0; }
.contact-wrap { display:grid; grid-template-columns:3fr 2fr; gap:5rem; align-items:start; }
.contact-hl { font-family:'Syne',sans-serif; font-weight:700; font-size:clamp(1.8rem,3.5vw,2.8rem); color:var(--white); line-height:1.2; margin-bottom:1.2rem; }
.contact-hl em { font-family:'Instrument Serif',serif; font-style:italic; color:var(--primary); font-weight:400; }
.contact-note { font-size:0.92rem; color:var(--muted2); line-height:1.8; max-width:440px; margin-bottom:2rem; }
.contact-links { display:flex; flex-direction:column; gap:0.8rem; }
.cl {
  display:flex; align-items:center; gap:1rem;
  background:var(--card); border:1px solid var(--border); border-radius:8px; padding:1rem 1.2rem;
  text-decoration:none; color:var(--text2); transition:border-color 0.2s, transform 0.15s;
}
.cl:hover { border-color:rgba(0,229,176,0.2); transform:translateX(4px); }
.cl-ico {
  width:38px; height:38px; border-radius:6px; background:rgba(0,229,176,0.07);
  display:flex; align-items:center; justify-content:center; flex-shrink:0;
}
.cl-ico svg { width:16px; height:16px; stroke:var(--primary); fill:none; stroke-width:1.6; }
.cl-lbl { font-family:'JetBrains Mono',monospace; font-size:0.6rem; text-transform:uppercase; letter-spacing:0.08em; color:var(--muted); margin-bottom:1px; }
.cl-v { font-size:0.86rem; color:var(--text2); }

/* ═══════════════════════════════════════════
   FOOTER
═══════════════════════════════════════════ */
footer {
  position:relative; z-index:1; background:var(--bg2);
  border-top:1px solid var(--border); padding:2rem 3rem;
  display:flex; justify-content:space-between; align-items:center; flex-wrap:wrap; gap:1rem;
}
.footer-left  { font-family:'JetBrains Mono',monospace; font-size:0.62rem; color:var(--muted); letter-spacing:0.08em; }
.footer-right { font-family:'JetBrains Mono',monospace; font-size:0.6rem;  color:var(--muted); letter-spacing:0.06em; }

/* ═══════════════════════════════════════════
   SCROLL REVEAL
═══════════════════════════════════════════ */
.reveal { opacity:0; transform:translateY(24px); transition:opacity 0.7s cubic-bezier(.4,0,.2,1), transform 0.7s cubic-bezier(.4,0,.2,1); }
.reveal.in { opacity:1; transform:none; }
.d1 { transition-delay:0.1s; } .d2 { transition-delay:0.2s; }
.d3 { transition-delay:0.3s; } .d4 { transition-delay:0.4s; }

/* ═══════════════════════════════════════════
   RESPONSIVE
═══════════════════════════════════════════ */
@media(max-width:1100px) {
  .skills-wrap { grid-template-columns:1fr 1fr; gap:2rem; }
}
@media(max-width:980px) {
  #hero { grid-template-columns:1fr; padding:8rem 1.5rem 4rem; }
  .hero-visual { display:none; }
  .about-grid, .contact-wrap { grid-template-columns:1fr; gap:3rem; }
  .dt-grid, .research-grid, .edu-wrap, .app-grid, .ach-grid, .se-pillars { grid-template-columns:1fr; }
  .skills-wrap { grid-template-columns:1fr 1fr; }
  .tw-layout { grid-template-columns:1fr; }
  .tw-wafer-wrap { display:none; }
  .mems-bridge { grid-template-columns:1fr; }
  .mb-arrow { transform:rotate(90deg); }
  .impact-grid { grid-template-columns:repeat(3,1fr); }
  nav { padding:1rem 1.5rem; }
  .nav-links { gap:1rem; }
  .nav-cta { display:none; }
}
@media(max-width:640px) {
  .container { padding:0 1.2rem; }
  #hero { padding-left:1.2rem; padding-right:1.2rem; }
  .impact-grid { grid-template-columns:1fr 1fr; }
  .skills-wrap { grid-template-columns:1fr; }
}
</style>
</head>
<body>
<canvas id="bg-canvas"></canvas>

<!-- ══ NAV ══════════════════════════════════ -->
<nav id="nav">
  <a class="nav-logo" href="#"><span class="nav-logo-dot"></span>PKS · Research</a>
  <ul class="nav-links">
    <li><a href="#about">About</a></li>
    <li><a href="#research">Research</a></li>
    <li><a href="#publications">Publications</a></li>
    <li><a href="#semicon-exp">Fabrication</a></li>
    <li><a href="#taiwan">Semiconductor</a></li>
    <li><a href="#applications">Industry</a></li>
    <li><a href="#achievements">Awards</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
  <a class="nav-cta" href="mailto:prashant94580@gmail.com">Collaborate</a>
</nav>

<!-- ══ HERO ══════════════════════════════════ -->
<section style="position:relative;z-index:1;">
<div id="hero">
  <div class="hero-content reveal">
    <div class="hero-eyebrow"><span class="hero-eyebrow-dot"></span>PhD Candidate · NCKU Taiwan · 3rd Year</div>
    <h1 class="hero-h1">Prashant<br/><span>Kishor Sharma</span></h1>
    <p class="hero-desc">
      <strong>AI-Integrated Microfluidics · MEMS · Biomedical Engineering · Semiconductor Systems</strong><br/>
      Developing next-generation microfluidic and MEMS platforms, artificial cilia actuation systems, and physics-informed neural networks — at the intersection of biomedical engineering and Taiwan's semiconductor ecosystem.
    </p>
    <div class="hero-tags">
      <span class="htag">Microfluidics</span>
      <span class="htag">MEMS</span>
      <span class="htag">Artificial Cilia</span>
      <span class="htag">PINNs</span>
      <span class="htag">CFD</span>
      <span class="htag">Semiconductor Sensors</span>
      <span class="htag">SU-8 Lithography</span>
      <span class="htag">BioMEMS</span>
      <span class="htag">Hemodynamics</span>
      <span class="htag">Micro-Robotics</span>
    </div>
    <div class="hero-btns">
      <a href="#publications" class="btn-p">View Publications</a>
      <a href="#contact" class="btn-g">Get In Touch</a>
    </div>
  </div>

  <div class="hero-visual reveal d2">
    <div class="hero-vis-wrap">
      <svg class="hero-vis-svg" viewBox="0 0 440 440" xmlns="http://www.w3.org/2000/svg">
        <defs>
          <radialGradient id="rg1" cx="50%" cy="50%" r="50%">
            <stop offset="0%" stop-color="#00e5b0" stop-opacity="0.07"/>
            <stop offset="100%" stop-color="#00e5b0" stop-opacity="0"/>
          </radialGradient>
          <radialGradient id="rg2" cx="50%" cy="50%" r="50%">
            <stop offset="0%" stop-color="#3b82f6" stop-opacity="0.05"/>
            <stop offset="100%" stop-color="#3b82f6" stop-opacity="0"/>
          </radialGradient>
          <filter id="glow"><feGaussianBlur stdDeviation="3" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
          <path id="path1" d="M80 160 Q150 120 220 160 Q290 200 360 160"/>
          <path id="path2" d="M80 220 Q150 180 220 220 Q290 260 360 220"/>
          <path id="path3" d="M80 280 Q150 240 220 280 Q290 320 360 280"/>
        </defs>
        <circle cx="220" cy="220" r="200" fill="none" stroke="#00e5b0" stroke-width="0.5" opacity="0.12"/>
        <circle cx="220" cy="220" r="165" fill="none" stroke="#00e5b0" stroke-width="0.5" opacity="0.08" stroke-dasharray="4 8">
          <animateTransform attributeName="transform" type="rotate" from="0 220 220" to="360 220 220" dur="30s" repeatCount="indefinite"/>
        </circle>
        <circle cx="220" cy="220" r="130" fill="none" stroke="#3b82f6" stroke-width="0.5" opacity="0.1" stroke-dasharray="3 6">
          <animateTransform attributeName="transform" type="rotate" from="360 220 220" to="0 220 220" dur="18s" repeatCount="indefinite"/>
        </circle>
        <circle cx="220" cy="220" r="190" fill="url(#rg1)"/>
        <circle cx="220" cy="220" r="140" fill="url(#rg2)"/>
        <g filter="url(#glow)">
          <circle cx="220" cy="55" r="5" fill="#00e5b0">
            <animateTransform attributeName="transform" type="rotate" from="0 220 220" to="360 220 220" dur="8s" repeatCount="indefinite"/>
          </circle>
          <circle cx="385" cy="220" r="3.5" fill="#3b82f6">
            <animateTransform attributeName="transform" type="rotate" from="0 220 220" to="360 220 220" dur="13s" repeatCount="indefinite"/>
          </circle>
          <circle cx="220" cy="385" r="4" fill="#f59e0b">
            <animateTransform attributeName="transform" type="rotate" from="0 220 220" to="360 220 220" dur="6s" repeatCount="indefinite"/>
          </circle>
          <circle cx="90" cy="130" r="3" fill="#00e5b0">
            <animateTransform attributeName="transform" type="rotate" from="180 220 220" to="540 220 220" dur="10s" repeatCount="indefinite"/>
          </circle>
        </g>
        <path d="M80 160 Q150 120 220 160 Q290 200 360 160" fill="none" stroke="#00e5b0" stroke-width="1" opacity="0.18"/>
        <path d="M80 220 Q150 180 220 220 Q290 260 360 220" fill="none" stroke="#3b82f6" stroke-width="1" opacity="0.14"/>
        <path d="M80 280 Q150 240 220 280 Q290 320 360 280" fill="none" stroke="#00e5b0" stroke-width="1" opacity="0.1"/>
        <circle r="3" fill="#00e5b0" opacity="0.7" filter="url(#glow)"><animateMotion dur="4s" repeatCount="indefinite"><mpath href="#path1"/></animateMotion></circle>
        <circle r="2.5" fill="#3b82f6" opacity="0.6" filter="url(#glow)"><animateMotion dur="5s" repeatCount="indefinite" begin="1.5s"><mpath href="#path2"/></animateMotion></circle>
        <circle r="2" fill="#f59e0b" opacity="0.6" filter="url(#glow)"><animateMotion dur="3.5s" repeatCount="indefinite" begin="0.5s"><mpath href="#path3"/></animateMotion></circle>
      </svg>
      <div class="metrics-float">
        <div class="metric-cell"><span class="metric-n">8+</span><span class="metric-l">Publications</span></div>
        <div class="metric-cell"><span class="metric-n">2</span><span class="metric-l">Cover Articles</span></div>
        <div class="metric-cell"><span class="metric-n">3+</span><span class="metric-l">Years PhD</span></div>
        <div class="metric-cell"><span class="metric-n">1</span><span class="metric-l">Patent</span></div>
      </div>
    </div>
  </div>
</div>
</section>

<!-- ══ DUAL TRACK ═════════════════════════════ -->
<section id="dualtrack">
  <div class="container">
    <div class="chip">Value Proposition</div>
    <h2 class="stitle">Academic <em>&amp; Industry</em> Ready</h2>
    <div class="rule"></div>
    <div class="dt-grid">
      <div class="dt-card academic reveal">
        <span class="dt-badge">🎓 Academic Track</span>
        <h3>Research Leadership &amp;<br/>Scientific Contribution</h3>
        <ul class="dt-list">
          <li>8+ peer-reviewed publications in top-tier journals (AIS, Biomicrofluidics, Biosensors, Scientific Reports)</li>
          <li>2 Cover Articles — demonstrating research significance and editorial recognition</li>
          <li>First-author contributions across AI-integrated microfluidics, biomedical systems, and hemodynamics</li>
          <li>AIP Scilight featured article — selected for broad scientific community impact</li>
          <li>Patent holder in green oxygen concentration technology (App. No: 202311040898)</li>
          <li>Active conference presenter — CTAM 2025 Excellence Award, ISBF Book Shortlist</li>
        </ul>
      </div>
      <div class="dt-card industry reveal d2">
        <span class="dt-badge">🏭 Industry Track</span>
        <h3>Engineering Skills &amp;<br/>Transferable Expertise</h3>
        <ul class="dt-list">
          <li>CFD simulation fluency (ANSYS, COMSOL) for product design, semiconductor fab process engineering, and R&amp;D validation</li>
          <li>AI/ML integration (PINNs, Python) for predictive modeling in medical devices, smart fabs, and industrial systems</li>
          <li>Hands-on MEMS fabrication: SU-8 lithography, PDMS soft lithography, oxygen plasma bonding, BioMEMS sensor design</li>
          <li>Located in Taiwan's semiconductor heartland — NCKU adjacent to TSMC, UMC, ITRI in Southern Taiwan Science Park</li>
          <li>LG Electronics engineering background + IIT Jammu research fellowship — industry and deep-R&amp;D experience</li>
          <li>Chip thermal management &amp; process fluid dynamics — applicable to advanced packaging (CoWoS, SoIC) R&amp;D</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<!-- ══ ABOUT ══════════════════════════════════ -->
<section id="about">
  <div class="container">
    <div class="chip">About</div>
    <h2 class="stitle">Bridging Science<br/><em>&amp; Engineering</em></h2>
    <div class="rule"></div>
    <div class="about-grid">
      <div class="about-text reveal">
        <p class="about-p lead">Ph.D. Researcher in Mechanical Engineering working at the frontier of AI-integrated microfluidics, MEMS fabrication, computational biomechanics, and intelligent semiconductor-compatible flow control systems.</p>
        <p class="about-p">Currently in my third year at National Cheng Kung University (NCKU), Tainan, I investigate microfluidic platforms for zebrafish-based drug delivery — fabricating chips via <strong>SU-8 photolithography, PDMS soft lithography, and oxygen plasma bonding</strong>. I design and build artificial cilia microactuation systems (magnetic MEMS actuators) for on-demand particle manipulation, and apply Physics-Informed Neural Networks (PINNs) to computational hemodynamics.</p>
        <p class="about-p">My work spans the full cycle from <strong>cleanroom fabrication</strong> to <strong>computational simulation</strong> to <strong>experimental validation</strong> — developing BioMEMS sensor platforms, lab-on-chip diagnostic devices, and semiconductor-grade micro-robotic systems for biomedical applications. This positions me uniquely at the interface of Taiwan's world-leading semiconductor ecosystem and next-generation medical technology.</p>
        <p class="about-p">Before NCKU, I was a Junior Research Fellow at IIT Jammu (green energy &amp; carbon capture) and a Post-Graduate Engineering Trainee at LG Electronics India — combining deep academic grounding with hands-on industrial engineering experience across India, and now Taiwan.</p>
        <div class="patent-block reveal d2">
          <div class="patent-ico">📋</div>
          <div>
            <div class="patent-lbl">Patent Holder</div>
            <div class="patent-t">A Natural Zeolite-Based Oxygen Concentrator for Supplying Pure Oxygen</div>
            <div class="patent-n">App. No: 202311040898</div>
          </div>
        </div>
      </div>
      <div class="info-stack reveal d2">
        <div class="info-row"><div class="info-ico">📍</div><div><div class="info-lbl">Location</div><div class="info-v">Tainan City, Taiwan</div></div></div>
        <div class="info-row"><div class="info-ico">🎓</div><div><div class="info-lbl">Institution</div><div class="info-v">National Cheng Kung University (NCKU)</div></div></div>
        <div class="info-row"><div class="info-ico">🔬</div><div><div class="info-lbl">Research Focus</div><div class="info-v">Microfluidics · MEMS · CFD · PINNs · Biomedical</div></div></div>
        <div class="info-row"><div class="info-ico">🏆</div><div><div class="info-lbl">Scholarship</div><div class="info-v">Veritas Conscientia Scholarship (VCS), NCKU</div></div></div>
        <div class="info-row"><div class="info-ico">✉️</div><div><div class="info-lbl">Email</div><div class="info-v"><a href="mailto:prashant94580@gmail.com">prashant94580@gmail.com</a></div></div></div>
        <div class="info-row"><div class="info-ico">💼</div><div><div class="info-lbl">LinkedIn</div><div class="info-v"><a href="https://www.linkedin.com/in/pks18" target="_blank">linkedin.com/in/pks18</a></div></div></div>
      </div>
    </div>
  </div>
</section>

<!-- ══ EDUCATION ══════════════════════════════ -->
<section id="education">
  <div class="container">
    <div class="chip">Education</div>
    <h2 class="stitle">Academic<br/><em>Background</em></h2>
    <div class="rule"></div>
    <div class="edu-wrap">
      <div class="edu-card reveal">
        <span class="edu-badge">Pursuing · 2023 – Present</span>
        <div class="edu-deg">PhD, Mechanical Engineering</div>
        <div class="edu-uni">National Cheng Kung University</div>
        <div class="edu-loc">Tainan City, Taiwan</div>
      </div>
      <div class="edu-card reveal d1">
        <span class="edu-badge">Completed · 2020 – 2022</span>
        <div class="edu-deg">M.E., Thermal Engineering</div>
        <div class="edu-uni">Thapar Institute of Engineering &amp; Technology</div>
        <div class="edu-loc">Patiala, India</div>
      </div>
      <div class="edu-card reveal d2">
        <span class="edu-badge">Completed · 2014 – 2018</span>
        <div class="edu-deg">B.Tech., Mechanical Engineering</div>
        <div class="edu-uni">Dr. A.P.J. Abdul Kalam Technical University</div>
        <div class="edu-loc">Greater Noida, India</div>
      </div>
    </div>
  </div>
</section>

<!-- ══ IMPACT METRICS ═════════════════════════ -->
<section id="impact">
  <div class="container">
    <div class="impact-grid">
      <div class="impact-cell reveal"><span class="impact-n">8+</span><span class="impact-l">Peer-Reviewed<br/>Publications</span></div>
      <div class="impact-cell reveal d1"><span class="impact-n blue">2</span><span class="impact-l">Journal<br/>Cover Articles</span></div>
      <div class="impact-cell reveal d2"><span class="impact-n amber">5+</span><span class="impact-l">Awards &amp;<br/>Recognitions</span></div>
      <div class="impact-cell reveal d3"><span class="impact-n">1</span><span class="impact-l">Filed<br/>Patent</span></div>
      <div class="impact-cell reveal d4"><span class="impact-n blue">3</span><span class="impact-l">Countries of<br/>Research Exp.</span></div>
    </div>
  </div>
</section>

<!-- ══ RESEARCH EXPERIENCE ════════════════════ -->
<section id="research">
  <div class="container">
    <div class="chip">Research Experience</div>
    <h2 class="stitle">Work &amp;<br/><em>Research</em></h2>
    <div class="rule"></div>
    <div class="research-grid">
      <div class="rc reveal">
        <div class="rc-when">Aug 2023 – Present</div>
        <div class="rc-title">PhD Researcher</div>
        <div class="rc-inst">National Cheng Kung University, Taiwan</div>
        <div class="rc-tags"><span class="tag">Microfluidics</span><span class="tag">MEMS</span><span class="tag">Artificial Cilia</span><span class="tag">PINNs</span><span class="tag">CFD</span><span class="tag">BioMEMS</span></div>
        <ul class="rc-ul">
          <li>Microfluidic chip fabrication: SU-8 lithography, PDMS casting, oxygen plasma bonding, precision flow control &amp; PIV analysis</li>
          <li>Magnetic MEMS actuator design — artificial cilia arrays for on-demand particle manipulation — <em>Cover Article, AIS 2025</em></li>
          <li>Zebrafish cognitive studies in microfluidic environments — optical BioMEMS sensing — <em>Featured + Scilight, Biomicrofluidics 2025</em></li>
          <li>CFD &amp; PINNs for comparative hemodynamics in abdominal aortic aneurysms</li>
          <li>Micro/nano robotic assemblies — modular magnetic actuation for biomedical drug delivery</li>
        </ul>
      </div>
      <div class="rc reveal d1">
        <div class="rc-when">Dec 2022 – Jun 2023</div>
        <div class="rc-title">Junior Research Fellow</div>
        <div class="rc-inst">IIT Jammu — Green Energy &amp; Carbon Capture</div>
        <div class="rc-tags"><span class="tag">Carbon Capture</span><span class="tag">Zeolite</span><span class="tag">Solar Drying</span></div>
        <ul class="rc-ul">
          <li>N₂ and CO₂ adsorption for oxygen concentrators using zeolite materials</li>
          <li>Solar-powered drying device with optimized heat transfer</li>
          <li>Carbon capture solutions reducing industrial greenhouse gas emissions</li>
        </ul>
      </div>
      <div class="rc reveal d2">
        <div class="rc-when">Sep 2021 – Aug 2022</div>
        <div class="rc-title">Post Graduate Engineering Trainee</div>
        <div class="rc-inst">LG Electronics India Pvt. Ltd., Greater Noida</div>
        <div class="rc-tags"><span class="tag">Energy Efficiency</span><span class="tag">Refrigerant Cycles</span></div>
        <ul class="rc-ul">
          <li>Led Energy Efficiency initiatives optimizing refrigerant cycles</li>
          <li>Directly reduced power consumption in consumer appliances</li>
        </ul>
      </div>
      <div class="rc reveal d3">
        <div class="rc-when">Sep 2020 – Aug 2022</div>
        <div class="rc-title">Post-Graduate Researcher</div>
        <div class="rc-inst">Thapar Institute of Engineering &amp; Technology</div>
        <div class="rc-tags"><span class="tag">CFD</span><span class="tag">Drag Reduction</span><span class="tag">Heat Transfer</span></div>
        <ul class="rc-ul">
          <li>Shark skin denticle CFD simulations for drag reduction &amp; biofouling prevention</li>
          <li>Fractal geometries for enhanced heat transfer in manufacturing</li>
          <li>Dam break simulation using ANSYS Fluent</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<!-- ══ PUBLICATIONS ════════════════════════════ -->
<section id="publications">
  <div class="container">
    <div class="chip">Publications</div>
    <h2 class="stitle">Research<br/><em>Output</em></h2>
    <div class="rule"></div>

    <div class="pub-featured reveal">
      <div class="pub-year">Jul 2025</div>
      <div class="pub-bdg">★ Inside Front Cover</div>
      <div class="pub-title">"Microflow Switching Using Artificial Cilia for On-Demand Particle Manipulation"</div>
      <div class="pub-authors">Prashant Kishor Sharma, Po-Wei Wei, Dineshkumar Loganathan, Yueh-Hsun Lu, Chia-Yuan Chen</div>
      <div class="pub-journal">Advanced Intelligent Systems, Vol. 7, Issue 11 · DOI: 10.1002/aisy.202500431</div>
    </div>
    <div class="pub-featured reveal d1">
      <div class="pub-year">Jun 2025</div>
      <div class="pub-bdg">★ Featured + Scilight (AIP)</div>
      <div class="pub-title">"Cognitive Dynamics of Drug-Mediated Zebrafish under Sound Stimuli in a Microfluidic Environment"</div>
      <div class="pub-authors">Prashant Kishor Sharma, Dineshkumar Loganathan, Ming-Lung Chen, Yueh-Hsun Lu, Pu-Hsiang Wang, Chia-Yuan Chen</div>
      <div class="pub-journal">Biomicrofluidics · DOI: 10.1063/5.0270298</div>
    </div>
    <div class="pub-featured reveal d2">
      <div class="pub-year">Dec 2025</div>
      <div class="pub-bdg">★ Published</div>
      <div class="pub-title">"Microfluidic Mixing with the Dynamic Control of Magnetic Actuation"</div>
      <div class="pub-authors">Prashant Kishor Sharma, Tsung-Yen Lu, Chia-Yuan Chen</div>
      <div class="pub-journal">Advanced Intelligent Systems · DOI: 10.1002/aisy.202500802</div>
    </div>
    <div class="pub-featured reveal d3">
      <div class="pub-year">Dec 2025</div>
      <div class="pub-bdg">★ Published</div>
      <div class="pub-title">"AI-Integrated Micro/Nanoscale Magnetic Robots for Biomedical Applications: Recent Advances in Design, Fabrication, and Functions"</div>
      <div class="pub-authors">Prashant Kishor Sharma, Chia-Yuan Chen</div>
      <div class="pub-journal">Biosensors · DOI: 10.3390/bios15120793</div>
    </div>

    <div class="chip" style="margin-top:2.5rem;">Under Review &amp; Submitted</div>
    <div class="pub-review-list">
      <div class="pub-row reveal">
        <div class="pub-yr">2025</div>
        <div>
          <div class="pub-t2">"Enhance Sperm Activation of Zebrafish Using Swarmed Microrobots Through Superior Micromixing" <span class="pub-status">Under Review</span></div>
          <div class="pub-m2">Scientific Reports · with Chao-Wei Hsu, Tsung-Yen Lu, Yueh-Hsun Lu, Chia-Yuan Chen</div>
        </div>
      </div>
      <div class="pub-row reveal d1">
        <div class="pub-yr">2026</div>
        <div>
          <div class="pub-t2">"Modular Reconfiguration and Actuation of Microrobotic Assemblies" <span class="pub-status">Submitted</span></div>
          <div class="pub-m2">Advanced Science · with Tsung-Yen Lu, Chia-Yuan Chen</div>
        </div>
      </div>
      <div class="pub-row reveal d2">
        <div class="pub-yr">2026</div>
        <div>
          <div class="pub-t2">"Integrated Lumped Parameter Modeling of Cardiac–Vascular Interaction with Valve Dynamics and Ventricular Pressure–Volume" <span class="pub-status">Submitted</span></div>
          <div class="pub-m2">Frontiers in Bioengineering and Biotechnology · with Wen Kai Yang, Chia-Yuan Chen</div>
        </div>
      </div>
      <div class="pub-row reveal d3">
        <div class="pub-yr">2024</div>
        <div>
          <div class="pub-t2">"A Comparative Assessment of Distributive Mode Active Solar Dryers"</div>
          <div class="pub-m2">Solar Energy Journal · Feb 2024 · with Krishna Sai Kandukuri, Ravi Kumar Arun</div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ══ SEMICONDUCTOR FABRICATION EXPERIENCE ══ -->
<section id="semicon-exp">
  <div class="container">
    <div class="chip">Semiconductor &amp; Fabrication</div>
    <h2 class="stitle">Hands-On Micro/Nano<br/><em>Fabrication Experience</em></h2>
    <div class="rule"></div>
    <p class="se-intro">
      Through my PhD research at NCKU, I have developed <strong>direct, practical experience</strong> in MEMS microfabrication, semiconductor sensor design, and cleanroom-compatible thin-film processes — working with the same techniques used across Taiwan's advanced semiconductor and MEMS foundry ecosystem.
    </p>

    <div class="se-pillars">
      <div class="se-pillar p-mems reveal">
        <span class="se-pillar-icon">⚙️</span>
        <div class="se-pillar-cat">MEMS · Microfabrication</div>
        <div class="se-pillar-title">MEMS Design &amp;<br/>Microfabrication</div>
        <ul class="se-pillar-list">
          <li>Soft lithography — SU-8 master mold fabrication for microfluidic chips and MEMS structures</li>
          <li>PDMS casting, bonding, and surface modification for lab-on-chip devices</li>
          <li>Micro-actuator design — magnetic cilia arrays with controlled deflection dynamics</li>
          <li>Micro-channel geometry optimization using CFD-guided iterative fabrication</li>
          <li>Particle manipulation via acoustic, magnetic, and fluidic MEMS actuation</li>
          <li>Wafer-level microstructure design compatible with standard MEMS process flows</li>
        </ul>
      </div>
      <div class="se-pillar p-sensor reveal d1">
        <span class="se-pillar-icon">📡</span>
        <div class="se-pillar-cat">Sensors · BioMEMS</div>
        <div class="se-pillar-title">Semiconductor Sensor<br/>Design &amp; Integration</div>
        <ul class="se-pillar-list">
          <li>BioMEMS flow sensors — microfluidic sensing channels with integrated detection zones</li>
          <li>Magnetic field-responsive sensor actuation using nanoparticle-doped structures</li>
          <li>PIV (Particle Image Velocimetry) — optical flow field measurement and sensor calibration</li>
          <li>Zebrafish behavioral biosensing — real-time optical tracking in microfluidic environments</li>
          <li>Impedance-based sensing concepts for on-chip cell detection and drug assay applications</li>
          <li>Lab-on-chip sensor integration aligned with semiconductor biosensor IC roadmaps</li>
        </ul>
      </div>
      <div class="se-pillar p-clean reveal d2">
        <span class="se-pillar-icon">🏭</span>
        <div class="se-pillar-cat">Cleanroom · Thin-Film</div>
        <div class="se-pillar-title">Cleanroom Processes &amp;<br/>Thin-Film Techniques</div>
        <ul class="se-pillar-list">
          <li>Cleanroom fabrication protocols — photolithography, mask alignment, UV exposure</li>
          <li>Thin-film deposition awareness — evaporation, sputtering, CVD for MEMS functional layers</li>
          <li>Surface functionalization — oxygen plasma treatment, silane chemistry for PDMS bonding</li>
          <li>SU-8 negative photoresist: spin-coating, soft-bake, exposure, post-bake, development</li>
          <li>Wet etching and surface patterning for microstructure definition on chip substrates</li>
          <li>Quality inspection — optical microscopy, profilometry, and contact angle measurement</li>
        </ul>
      </div>
    </div>

    <!-- Process flow -->
    <div class="se-process reveal">
      <div class="se-process-title">Microfabrication Process Flow — Practiced at NCKU</div>
      <div class="se-flow">
        <div class="se-flow-step"><div class="se-flow-node teal">🎨</div><div class="se-flow-label">CAD<br/>Design</div></div>
        <div class="se-flow-arrow">›</div>
        <div class="se-flow-step"><div class="se-flow-node teal">🔲</div><div class="se-flow-label">Mask<br/>Fabrication</div></div>
        <div class="se-flow-arrow">›</div>
        <div class="se-flow-step"><div class="se-flow-node blue">☀️</div><div class="se-flow-label">SU-8<br/>Lithography</div></div>
        <div class="se-flow-arrow">›</div>
        <div class="se-flow-step"><div class="se-flow-node blue">🧪</div><div class="se-flow-label">PDMS<br/>Casting</div></div>
        <div class="se-flow-arrow">›</div>
        <div class="se-flow-step"><div class="se-flow-node amber">⚡</div><div class="se-flow-label">Plasma<br/>Bonding</div></div>
        <div class="se-flow-arrow">›</div>
        <div class="se-flow-step"><div class="se-flow-node amber">🔬</div><div class="se-flow-label">Integration<br/>&amp; Test</div></div>
        <div class="se-flow-arrow">›</div>
        <div class="se-flow-step"><div class="se-flow-node teal">📊</div><div class="se-flow-label">CFD<br/>Validation</div></div>
      </div>
    </div>

    <!-- Badge cloud -->
    <div class="reveal">
      <div style="font-family:'JetBrains Mono',monospace;font-size:0.62rem;letter-spacing:0.15em;text-transform:uppercase;color:var(--muted2);margin-bottom:1rem;">Key Fabrication Competencies</div>
      <div class="se-badges">
        <span class="se-badge teal">SU-8 Photolithography</span>
        <span class="se-badge teal">PDMS Soft Lithography</span>
        <span class="se-badge teal">Micro-Actuator Design</span>
        <span class="se-badge teal">Magnetic Cilia Arrays</span>
        <span class="se-badge teal">Microfluidic Chip Fabrication</span>
        <span class="se-badge blue">BioMEMS Sensor Design</span>
        <span class="se-badge blue">PIV Flow Measurement</span>
        <span class="se-badge blue">Lab-on-Chip Integration</span>
        <span class="se-badge blue">Nanoparticle Actuation</span>
        <span class="se-badge blue">Optical Biosensing</span>
        <span class="se-badge amber">Cleanroom Protocols</span>
        <span class="se-badge amber">Oxygen Plasma Treatment</span>
        <span class="se-badge amber">Thin-Film Awareness</span>
        <span class="se-badge amber">Surface Functionalization</span>
        <span class="se-badge amber">Wet Etching &amp; Patterning</span>
        <span class="se-badge amber">Profilometry &amp; QC</span>
      </div>
    </div>
  </div>
</section>

<!-- ══ TAIWAN SEMICONDUCTOR ECOSYSTEM ══════════ -->
<section id="taiwan">
  <div class="container">
    <div class="chip">Taiwan · Semiconductor Nexus</div>
    <h2 class="stitle">Research at the Heart of<br/><em>Global Semiconductor Innovation</em></h2>
    <div class="rule"></div>
    <p class="tw-intro">
      Based at <strong>NCKU Tainan</strong> — adjacent to the Southern Taiwan Science Park — my research sits at the convergence of microfluidics, MEMS fabrication, and semiconductor-grade engineering. Taiwan's status as the world's semiconductor capital (TSMC, UMC, ASE, MediaTek) creates unique translational opportunities for researchers working at the micro/nanoscale.
    </p>

    <div class="tw-layout">
      <div class="tw-wafer-wrap reveal">
        <svg class="tw-wafer-svg" viewBox="0 0 380 380" xmlns="http://www.w3.org/2000/svg">
          <defs>
            <radialGradient id="wg" cx="50%" cy="50%" r="50%">
              <stop offset="0%" stop-color="#1a2540"/>
              <stop offset="100%" stop-color="#0a0d16"/>
            </radialGradient>
            <filter id="wglow"><feGaussianBlur stdDeviation="4" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
          </defs>
          <circle cx="190" cy="190" r="168" fill="url(#wg)" stroke="#00e5b0" stroke-width="1" opacity="0.4"/>
          <circle cx="190" cy="190" r="168" fill="none" stroke="#3b82f6" stroke-width="0.5" opacity="0.15" stroke-dasharray="6 10">
            <animateTransform attributeName="transform" type="rotate" from="0 190 190" to="360 190 190" dur="40s" repeatCount="indefinite"/>
          </circle>
          <g opacity="0.22" stroke="#00e5b0" stroke-width="0.5" fill="none">
            <line x1="50" y1="80"  x2="330" y2="80"/>  <line x1="50" y1="110" x2="330" y2="110"/>
            <line x1="50" y1="140" x2="330" y2="140"/> <line x1="50" y1="170" x2="330" y2="170"/>
            <line x1="50" y1="200" x2="330" y2="200"/> <line x1="50" y1="230" x2="330" y2="230"/>
            <line x1="50" y1="260" x2="330" y2="260"/> <line x1="50" y1="290" x2="330" y2="290"/>
            <line x1="80"  y1="50" x2="80"  y2="330"/> <line x1="110" y1="50" x2="110" y2="330"/>
            <line x1="140" y1="50" x2="140" y2="330"/> <line x1="170" y1="50" x2="170" y2="330"/>
            <line x1="200" y1="50" x2="200" y2="330"/> <line x1="230" y1="50" x2="230" y2="330"/>
            <line x1="260" y1="50" x2="260" y2="330"/> <line x1="290" y1="50" x2="290" y2="330"/>
          </g>
          <rect x="170" y="170" width="28" height="28" fill="#00e5b0" opacity="0.15" rx="1"/>
          <rect x="200" y="170" width="28" height="28" fill="#3b82f6" opacity="0.12" rx="1"/>
          <rect x="170" y="200" width="28" height="28" fill="#f59e0b" opacity="0.10" rx="1"/>
          <rect x="140" y="140" width="28" height="28" fill="#00e5b0" opacity="0.08" rx="1"/>
          <rect x="200" y="200" width="28" height="28" fill="#00e5b0" opacity="0.12" rx="1"/>
          <rect x="230" y="140" width="28" height="28" fill="#3b82f6" opacity="0.08" rx="1"/>
          <circle cx="190" cy="190" r="6" fill="#00e5b0" opacity="0.8" filter="url(#wglow)">
            <animate attributeName="opacity" values="0.8;0.3;0.8" dur="3s" repeatCount="indefinite"/>
          </circle>
          <text x="190" y="355" text-anchor="middle" font-family="JetBrains Mono,monospace" font-size="9" fill="#4b5a72" letter-spacing="2">12&quot; SILICON WAFER · MEMS ZONE</text>
          <text x="190" y="370" text-anchor="middle" font-family="JetBrains Mono,monospace" font-size="8" fill="#3b5a72">Southern Taiwan Science Park · NCKU</text>
        </svg>
      </div>

      <div class="tw-cards reveal d2">
        <div class="tw-card">
          <div class="tw-card-ico teal">⚙️</div>
          <div>
            <div class="tw-card-label">Fabrication Bridge</div>
            <div class="tw-card-title">MEMS Process Alignment with Semiconductor Foundries</div>
            <div class="tw-card-desc">SU-8 photolithography, PDMS bonding, and micro-actuator fabrication practiced at NCKU align with front-end MEMS process flows used at Taiwan's MEMS foundries — ready for cleanroom scale-up.</div>
          </div>
        </div>
        <div class="tw-card">
          <div class="tw-card-ico blue">🏭</div>
          <div>
            <div class="tw-card-label">Industry Proximity</div>
            <div class="tw-card-title">NCKU → Southern Taiwan Science Park</div>
            <div class="tw-card-desc">Adjacent to TSMC Fab 14 and the Southern Taiwan Science Park. Active NCKU-industry collaborations in advanced packaging, MEMS, and semiconductor process R&amp;D — a direct pipeline to industry.</div>
          </div>
        </div>
        <div class="tw-card">
          <div class="tw-card-ico amber">📡</div>
          <div>
            <div class="tw-card-label">Sensor Design</div>
            <div class="tw-card-title">BioMEMS Sensors → Semiconductor Health Chips</div>
            <div class="tw-card-desc">Direct experience designing lab-on-chip optical and magnetic sensing systems — the same technology base for wearable health ICs, IoMT biosensor chips, and point-of-care semiconductor platforms.</div>
          </div>
        </div>
        <div class="tw-card">
          <div class="tw-card-ico rose">🤝</div>
          <div>
            <div class="tw-card-label">Open to Opportunities</div>
            <div class="tw-card-title">Semiconductor R&amp;D · MEMS Engineer · Post-Doc</div>
            <div class="tw-card-desc">Actively seeking R&amp;D roles, post-doctoral positions, or collaborative projects in semiconductor companies, MEMS foundries, and biomedical chip divisions across Taiwan and globally.</div>
          </div>
        </div>
      </div>
    </div>

    <!-- MEMS Bridge -->
    <div class="mems-bridge reveal">
      <div><span class="mb-item-icon">🧫</span><div class="mb-item-title">Microfluidic Chip</div><div class="mb-item-desc">PDMS soft lithography, SU-8 molds, precision flow channels — standard MEMS process techniques</div></div>
      <div class="mb-arrow">→</div>
      <div><span class="mb-item-icon">⚙️</span><div class="mb-item-title">MEMS Fabrication</div><div class="mb-item-desc">Micro-actuators, cilia arrays, magnetic components — integrated into semiconductor-compatible processes</div></div>
      <div class="mb-arrow">→</div>
      <div><span class="mb-item-icon">💡</span><div class="mb-item-title">Semiconductor Integration</div><div class="mb-item-desc">BioMEMS sensors, lab-on-chip ICs, smart diagnostic devices — the frontier of Taiwan's next-gen semiconductor roadmap</div></div>
    </div>

    <!-- Ecosystem tags -->
    <div class="tw-ecosystem reveal">
      <div class="tw-eco-label">Taiwan Semiconductor Ecosystem — Relevant Companies &amp; Research Institutions</div>
      <div class="tw-eco-logos">
        <span class="tw-eco-tag highlight">TSMC</span>
        <span class="tw-eco-tag highlight">UMC</span>
        <span class="tw-eco-tag">ASE Group</span>
        <span class="tw-eco-tag">MediaTek</span>
        <span class="tw-eco-tag">Himax</span>
        <span class="tw-eco-tag">AUO</span>
        <span class="tw-eco-tag highlight">ITRI</span>
        <span class="tw-eco-tag highlight">NCKU Research Park</span>
        <span class="tw-eco-tag">Southern Taiwan Science Park</span>
        <span class="tw-eco-tag">NARL</span>
        <span class="tw-eco-tag">Taiwan AI Labs</span>
        <span class="tw-eco-tag highlight">NCHC</span>
        <span class="tw-eco-tag">Winbond</span>
        <span class="tw-eco-tag">Macronix</span>
        <span class="tw-eco-tag">Foxconn R&amp;D</span>
      </div>
    </div>
  </div>
</section>

<!-- ══ INDUSTRY APPLICATIONS ══════════════════ -->
<section id="applications">
  <div class="container">
    <div class="chip">Industry Applications</div>
    <h2 class="stitle">Real-World<br/><em>Impact</em></h2>
    <div class="rule"></div>
    <p class="app-intro">My research translates directly into high-value industry sectors — with a particular focus on Taiwan's semiconductor and advanced manufacturing ecosystem.</p>
    <div class="app-grid">
      <div class="app-card reveal">
        <span class="app-icon">🔧</span>
        <div class="app-sector">Semiconductor / MEMS</div>
        <div class="app-name">MEMS &amp; BioMEMS Device R&amp;D</div>
        <div class="app-desc">Micro-actuator design, magnetic cilia arrays, and precision flow control map directly to MEMS foundry R&amp;D — applicable to TSMC, UMC advanced packaging or MEMS spinout divisions.</div>
      </div>
      <div class="app-card reveal d1">
        <span class="app-icon">📡</span>
        <div class="app-sector">Semiconductor Sensors</div>
        <div class="app-name">Lab-on-Chip Sensor Integration</div>
        <div class="app-desc">Particle manipulation, biosensing microfluidics, and on-chip detection translate to next-gen semiconductor biosensor chips — wearable health ICs, IoMT, and point-of-care semiconductor platforms.</div>
      </div>
      <div class="app-card reveal d2">
        <span class="app-icon">🌡️</span>
        <div class="app-sector">Semiconductor Thermal</div>
        <div class="app-name">Chip-Level Thermal Management</div>
        <div class="app-desc">Heat transfer optimization and CFD modeling expertise applicable to advanced chip thermal solutions — critical for high-density semiconductor packaging (CoWoS, SoIC) and HPC cooling.</div>
      </div>
      <div class="app-card reveal d3">
        <span class="app-icon">🧬</span>
        <div class="app-sector">MedTech / Diagnostics</div>
        <div class="app-name">Lab-on-Chip &amp; Point-of-Care Devices</div>
        <div class="app-desc">Microfluidic platform design, flow control, and particle manipulation directly applicable to diagnostic chip development for pharma and MedTech companies.</div>
      </div>
      <div class="app-card reveal">
        <span class="app-icon">🤖</span>
        <div class="app-sector">Biomedical Robotics</div>
        <div class="app-name">Micro/Nano Robotic Systems</div>
        <div class="app-desc">Magnetic microrobot design, actuation, and control — relevant to minimally invasive drug delivery, targeted therapy, and surgical robotics R&amp;D.</div>
      </div>
      <div class="app-card reveal d1">
        <span class="app-icon">❤️</span>
        <div class="app-sector">Cardiovascular Devices</div>
        <div class="app-name">Hemodynamics Simulation</div>
        <div class="app-desc">CFD + PINNs for vascular flow modeling supports medical device validation, stent design, and cardiovascular implant R&amp;D pipelines.</div>
      </div>
      <div class="app-card reveal d2">
        <span class="app-icon">💧</span>
        <div class="app-sector">Process Engineering</div>
        <div class="app-name">Fluid Systems Optimization</div>
        <div class="app-desc">CFD expertise applicable to semiconductor fab chemical process design, slurry flow in CMP, and precision wet etch/clean process engineering.</div>
      </div>
      <div class="app-card reveal d3">
        <span class="app-icon">🌱</span>
        <div class="app-sector">Green Technology</div>
        <div class="app-name">Carbon Capture &amp; Clean Energy</div>
        <div class="app-desc">Zeolite-based gas separation and solar drying research — relevant to semiconductor fab ESG goals (net-zero operations, gas recovery, PFC reduction).</div>
      </div>
      <div class="app-card reveal">
        <span class="app-icon">🧠</span>
        <div class="app-sector">AI / Digital Twin</div>
        <div class="app-name">Physics-Informed AI Modeling</div>
        <div class="app-desc">PINNs and AI-integrated simulation for semiconductor process digital twins, predictive yield modeling, and R&amp;D acceleration — applicable to smart fabs and Industry 4.0.</div>
      </div>
    </div>
  </div>
</section>

<!-- ══ ACHIEVEMENTS ════════════════════════════ -->
<section id="achievements">
  <div class="container">
    <div class="chip">Achievements</div>
    <h2 class="stitle">Awards &amp;<br/><em>Recognition</em></h2>
    <div class="rule"></div>
    <div class="ach-grid">
      <div class="ach-card reveal"><span class="ach-ico">🏅</span><div class="ach-t">Excellence Research Work Award</div><div class="ach-d">Student Paper Competition, Conference on Theoretical and Applied Mechanics (CTAM) 2025, National United University, Taiwan</div></div>
      <div class="ach-card reveal d1"><span class="ach-ico">🎖️</span><div class="ach-t">Nominated — Research Excellence Award</div><div class="ach-d">Material Scientist Awards, 2025 — nominated for outstanding contributions in material and biomedical research</div></div>
      <div class="ach-card reveal d2"><span class="ach-ico">📘</span><div class="ach-t">Veritas Conscientia Scholarship (VCS)</div><div class="ach-d">Prestigious doctoral scholarship at National Cheng Kung University, Taiwan</div></div>
      <div class="ach-card reveal d3"><span class="ach-ico">📰</span><div class="ach-t">Science Highlights — AIP Scilight</div><div class="ach-d">Zebrafish microfluidics paper selected as Scilight News — Editor's Featured Article, Biomicrofluidics</div></div>
      <div class="ach-card reveal"><span class="ach-ico">🏆</span><div class="ach-t">Best Poster Award</div><div class="ach-d">113th Annual Conference on Aerospace and Thermal Fluidics — recognized for Excellent Work</div></div>
      <div class="ach-card reveal d1"><span class="ach-ico">📕</span><div class="ach-t">Book Shortlisted — ISBF FAST 2025</div><div class="ach-d">"Storms of Change: The Physics of Monsoons, Dust Storms, and Extreme Weather" — shortlisted for India Science Book Fellowship</div></div>
      <div class="ach-card reveal d2"><span class="ach-ico">✅</span><div class="ach-t">GATE Qualified + JRF (2019)</div><div class="ach-d">Qualified GATE and awarded Junior Research Fellowship for computational and experimental research</div></div>
      <div class="ach-card reveal d3"><span class="ach-ico">🌟</span><div class="ach-t">Best Master's Thesis Presentation</div><div class="ach-d">Awarded for CFD-based study on drag reduction using bio-inspired shark skin denticle patterns</div></div>
      <div class="ach-card reveal"><span class="ach-ico">👥</span><div class="ach-t">President, Indian Students Association</div><div class="ach-d">NCKU — organized Holi, Diwali and cultural events; fostered campus community (Jan 2024 – Aug 2025)</div></div>
    </div>
  </div>
</section>

<!-- ══ SKILLS ══════════════════════════════════ -->
<section id="skills">
  <div class="container">
    <div class="chip">Expertise</div>
    <h2 class="stitle">Technical<br/><em>Skills</em></h2>
    <div class="rule"></div>
    <div class="skills-wrap">
      <div class="reveal">
        <div class="sg-title">Software &amp; Simulation</div>
        <div class="skill-row"><span class="skill-nm">ANSYS / COMSOL</span><div class="skill-bar"><div class="skill-fill" data-w="0.92"></div></div></div>
        <div class="skill-row"><span class="skill-nm">MATLAB</span><div class="skill-bar"><div class="skill-fill" data-w="0.88"></div></div></div>
        <div class="skill-row"><span class="skill-nm">Python</span><div class="skill-bar"><div class="skill-fill" data-w="0.82"></div></div></div>
        <div class="skill-row"><span class="skill-nm">SolidWorks / AutoCAD</span><div class="skill-bar"><div class="skill-fill" data-w="0.78"></div></div></div>
        <div class="skill-row"><span class="skill-nm">CREO</span><div class="skill-bar"><div class="skill-fill" data-w="0.72"></div></div></div>
      </div>
      <div class="reveal d1">
        <div class="sg-title">Research Competencies</div>
        <div class="skill-row"><span class="skill-nm">Computational Fluid Dynamics</span><div class="skill-bar"><div class="skill-fill" data-w="0.95"></div></div></div>
        <div class="skill-row"><span class="skill-nm">Microfluidics &amp; PIV</span><div class="skill-bar"><div class="skill-fill" data-w="0.90"></div></div></div>
        <div class="skill-row"><span class="skill-nm">Physics-Informed Neural Networks</span><div class="skill-bar"><div class="skill-fill" data-w="0.78"></div></div></div>
        <div class="skill-row"><span class="skill-nm">Hemodynamics Modeling</span><div class="skill-bar"><div class="skill-fill" data-w="0.80"></div></div></div>
        <div class="skill-row"><span class="skill-nm">Thermal &amp; Energy Systems</span><div class="skill-bar"><div class="skill-fill" data-w="0.85"></div></div></div>
      </div>
      <div class="reveal d2">
        <div class="sg-title">MEMS &amp; Sensor Design</div>
        <div class="skill-row"><span class="skill-nm">MEMS Micro-Actuator Design</span><div class="skill-bar"><div class="skill-fill" data-w="0.82"></div></div></div>
        <div class="skill-row"><span class="skill-nm">BioMEMS Sensor Integration</span><div class="skill-bar"><div class="skill-fill" data-w="0.78"></div></div></div>
        <div class="skill-row"><span class="skill-nm">Magnetic Cilia Arrays</span><div class="skill-bar"><div class="skill-fill" data-w="0.85"></div></div></div>
        <div class="skill-row"><span class="skill-nm">PIV Flow Sensing</span><div class="skill-bar"><div class="skill-fill" data-w="0.88"></div></div></div>
        <div class="skill-row"><span class="skill-nm">Lab-on-Chip Design</span><div class="skill-bar"><div class="skill-fill" data-w="0.86"></div></div></div>
      </div>
      <div class="reveal d3">
        <div class="sg-title">Cleanroom &amp; Thin-Film</div>
        <div class="skill-row"><span class="skill-nm">SU-8 Photolithography</span><div class="skill-bar"><div class="skill-fill" data-w="0.84"></div></div></div>
        <div class="skill-row"><span class="skill-nm">PDMS Soft Lithography</span><div class="skill-bar"><div class="skill-fill" data-w="0.86"></div></div></div>
        <div class="skill-row"><span class="skill-nm">Plasma Bonding &amp; Surface Treatment</span><div class="skill-bar"><div class="skill-fill" data-w="0.80"></div></div></div>
        <div class="skill-row"><span class="skill-nm">Thin-Film Deposition (CVD/Sputtering)</span><div class="skill-bar"><div class="skill-fill" data-w="0.68"></div></div></div>
        <div class="skill-row"><span class="skill-nm">Wet Etching &amp; Patterning</span><div class="skill-bar"><div class="skill-fill" data-w="0.72"></div></div></div>
      </div>
    </div>
  </div>
</section>

<!-- ══ CONTACT ══════════════════════════════════ -->
<section id="contact">
  <div class="container">
    <div class="chip">Contact</div>
    <h2 class="stitle">Let's<br/><em>Connect</em></h2>
    <div class="rule"></div>
    <div class="contact-wrap">
      <div class="reveal">
        <div class="contact-hl">Open for <em>collaborations,</em><br/>research discussions<br/>&amp; opportunities.</div>
        <p class="contact-note">Whether you're looking for a researcher in microfluidics, MEMS, biomedical engineering, semiconductor systems, or AI-integrated modeling — or simply want to exchange ideas on cutting-edge science — I'd love to connect. Based in Tainan, Taiwan, and open to global collaborations.</p>
        <a href="mailto:prashant94580@gmail.com" class="btn-p">Send Email</a>
      </div>
      <div class="contact-links reveal d2">
        <a class="cl" href="mailto:prashant94580@gmail.com">
          <div class="cl-ico"><svg viewBox="0 0 24 24"><rect x="2" y="4" width="20" height="16" rx="2"/><polyline points="2,4 12,13 22,4"/></svg></div>
          <div><div class="cl-lbl">Email</div><div class="cl-v">prashant94580@gmail.com</div></div>
        </a>
        <a class="cl" href="https://www.linkedin.com/in/pks18" target="_blank">
          <div class="cl-ico"><svg viewBox="0 0 24 24"><rect x="2" y="2" width="20" height="20" rx="3"/><line x1="7" y1="10" x2="7" y2="17"/><line x1="7" y1="7" x2="7" y2="7.01" stroke-linecap="round" stroke-width="2.5"/><path d="M11 17v-4a2 2 0 014 0v4"/><line x1="11" y1="10" x2="11" y2="17"/></svg></div>
          <div><div class="cl-lbl">LinkedIn</div><div class="cl-v">linkedin.com/in/pks18</div></div>
        </a>
        <a class="cl" href="tel:+886955799383">
          <div class="cl-ico"><svg viewBox="0 0 24 24"><path d="M22 16.92v3a2 2 0 01-2.18 2 19.79 19.79 0 01-8.63-3.07A19.5 19.5 0 013.07 10.8 19.79 19.79 0 01.12 2.2 2 2 0 012.11 0h3a2 2 0 012 1.72c.127.96.361 1.903.7 2.81a2 2 0 01-.45 2.11L6.09 7.91a16 16 0 006 6l1.27-1.27a2 2 0 012.11-.45c.907.339 1.85.573 2.81.7A2 2 0 0122 14.92z"/></svg></div>
          <div><div class="cl-lbl">Phone</div><div class="cl-v">+886 955 799 383</div></div>
        </a>
      </div>
    </div>
  </div>
</section>

<footer>
  <div class="footer-left">© 2025 Prashant Kishor Sharma · PhD Candidate, NCKU Taiwan</div>
  <div class="footer-right">Mechanical Engineering · Microfluidics · MEMS · Semiconductor Sensors · AI Systems</div>
</footer>

<!-- ══ SCRIPTS ════════════════════════════════ -->
<script>
/* Background particle canvas */
(function(){
  const cv=document.getElementById('bg-canvas');
  const ctx=cv.getContext('2d');
  let W,H;
  const P=[];
  const TEAL=[0,229,176], BLUE=[59,130,246], AMBER=[245,158,11];
  function resize(){ W=cv.width=window.innerWidth; H=cv.height=window.innerHeight; }
  resize(); window.addEventListener('resize',resize);
  function Particle(){
    this.x=Math.random()*W; this.y=Math.random()*H;
    this.vx=(Math.random()-0.5)*0.25; this.vy=(Math.random()-0.5)*0.25;
    this.r=Math.random()*1.5+0.4;
    const c=Math.random();
    this.color=c<0.6?TEAL:c<0.85?BLUE:AMBER;
    this.alpha=Math.random()*0.28+0.08;
  }
  Particle.prototype.update=function(){
    this.x+=this.vx; this.y+=this.vy;
    if(this.x<0)this.x=W; if(this.x>W)this.x=0;
    if(this.y<0)this.y=H; if(this.y>H)this.y=0;
  };
  for(let i=0;i<90;i++) P.push(new Particle());
  function draw(){
    ctx.clearRect(0,0,W,H);
    P.forEach(p=>{
      ctx.beginPath(); ctx.arc(p.x,p.y,p.r,0,Math.PI*2);
      ctx.fillStyle=`rgba(${p.color.join(',')},${p.alpha})`; ctx.fill();
      p.update();
    });
    for(let i=0;i<P.length;i++) for(let j=i+1;j<P.length;j++){
      const dx=P[i].x-P[j].x, dy=P[i].y-P[j].y;
      const d=Math.sqrt(dx*dx+dy*dy);
      if(d<100){
        ctx.beginPath(); ctx.moveTo(P[i].x,P[i].y); ctx.lineTo(P[j].x,P[j].y);
        ctx.strokeStyle=`rgba(0,229,176,${(1-d/100)*0.06})`; ctx.lineWidth=0.5; ctx.stroke();
      }
    }
    requestAnimationFrame(draw);
  }
  draw();
})();

/* Scroll reveal */
const revEls=document.querySelectorAll('.reveal');
const revObs=new IntersectionObserver(entries=>{
  entries.forEach(e=>{ if(e.isIntersecting) e.target.classList.add('in'); });
},{threshold:0.1});
revEls.forEach(el=>revObs.observe(el));

/* Skill bars — animate on scroll into view */
document.querySelectorAll('.skills-wrap > div').forEach(col=>{
  const obs=new IntersectionObserver(entries=>{
    entries.forEach(e=>{
      if(e.isIntersecting){
        e.target.querySelectorAll('.skill-fill').forEach((bar,i)=>{
          const w=parseFloat(bar.dataset.w)||0;
          setTimeout(()=>{
            bar.style.transition='transform 1s cubic-bezier(.4,0,.2,1)';
            bar.style.transform=`scaleX(${w})`;
          },i*90);
        });
        obs.unobserve(e.target);
      }
    });
  },{threshold:0.2});
  obs.observe(col);
});

/* Nav scroll state */
window.addEventListener('scroll',()=>{
  document.getElementById('nav').classList.toggle('scrolled',window.scrollY>60);
});
</script>
</body>
</html>
