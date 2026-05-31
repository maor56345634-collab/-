[maor-leads-v3.html](https://github.com/user-attachments/files/28438665/maor-leads-v3.html)
<!DOCTYPE html>
<html lang="he" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="google-site-verification" content="mxO5GXCwR6vNzG_5GkAFPOjW1YCIC1HX_jU0qptcN8A" />
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>מאור — אתרים, דפי נחיתה ולידים לעסקים קטנים</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Rubik:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,400&family=Noto+Serif+Hebrew:wght@400;700;900&display=swap" rel="stylesheet">
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
:root{
  --ink:#070e1a;
  --ink2:#0d1b30;
  --blue:#16325e;
  --gold:#c9a23a;
  --gold2:#e8c05a;
  --gold3:rgba(201,162,58,.12);
  --white:#fff;
  --off:#f4f7fc;
  --text:#0d1b30;
  --mid:#566480;
  --bdr:#dce3f0;
  --grn:#22c55e;
  --r:10px;
}
html{scroll-behavior:smooth}
body{font-family:'Rubik',sans-serif;background:var(--white);color:var(--text);overflow-x:hidden;-webkit-font-smoothing:antialiased}

/* ── NAV ── */
#nav{position:fixed;inset:0 0 auto;z-index:999;height:62px;display:flex;align-items:center;justify-content:space-between;padding:0 2.2rem;transition:.3s}
#nav.s{background:rgba(7,14,26,.96);backdrop-filter:blur(18px);box-shadow:0 1px 0 rgba(201,162,58,.1)}
.nl{display:flex;align-items:center;gap:.6rem}
.nm{width:32px;height:32px;border-radius:7px;background:var(--gold);display:flex;align-items:center;justify-content:center;font-weight:900;font-size:1rem;color:var(--ink);flex-shrink:0}
.nt{font-family:'Noto Serif Hebrew',serif;font-weight:900;font-size:1rem;color:#fff}
.nt span{color:var(--gold)}
.nr{display:flex;align-items:center;gap:1.4rem}
.nl2{color:rgba(255,255,255,.55);font-size:.84rem;font-weight:500;text-decoration:none;transition:.15s}
.nl2:hover{color:#fff}
.nb{background:var(--gold);color:var(--ink);font-weight:800;font-size:.84rem;padding:.5rem 1.3rem;border-radius:7px;text-decoration:none;transition:.2s;white-space:nowrap}
.nb:hover{background:var(--gold2)}
@media(max-width:600px){.nr .nl2{display:none}}

/* ── HERO ── */
.hero{min-height:100vh;background:var(--ink);display:flex;align-items:center;padding:7rem 2.2rem 4rem;position:relative;overflow:hidden}
.hbg{position:absolute;inset:0;background:radial-gradient(ellipse 70% 55% at 55% -5%,rgba(201,162,58,.11) 0,transparent 65%),radial-gradient(ellipse 45% 45% at 5% 95%,rgba(22,50,94,.55) 0,transparent 65%);pointer-events:none}
.hgrid{position:absolute;inset:0;background-image:linear-gradient(rgba(255,255,255,.022) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.022) 1px,transparent 1px);background-size:56px 56px;pointer-events:none}

.hi{max-width:1080px;margin:0 auto;width:100%;display:grid;grid-template-columns:1.1fr .9fr;gap:4rem;align-items:center;position:relative}
@media(max-width:860px){.hi{grid-template-columns:1fr;gap:2.5rem}}

.hl{opacity:0;animation:fu .85s .1s forwards}
.hpill{display:inline-flex;align-items:center;gap:.45rem;background:rgba(201,162,58,.1);border:1px solid rgba(201,162,58,.22);color:var(--gold2);font-size:.74rem;font-weight:600;letter-spacing:.07em;padding:.34rem .95rem;border-radius:100px;margin-bottom:1.6rem}
.hpill-dot{width:5px;height:5px;border-radius:50%;background:var(--gold);animation:bk 1.5s infinite}
@keyframes bk{0%,100%{opacity:1}50%{opacity:.15}}

h1{font-family:'Noto Serif Hebrew',serif;font-size:clamp(2rem,4.2vw,3.6rem);font-weight:900;line-height:1.1;color:#fff;margin-bottom:1.3rem}
h1 em{font-style:normal;color:var(--gold)}
h1 em.ul{position:relative;display:inline-block}
h1 em.ul::after{content:'';position:absolute;bottom:-3px;right:0;left:0;height:3px;background:var(--gold);border-radius:2px;opacity:.45}

.hdesc{font-size:1rem;color:rgba(255,255,255,.58);line-height:1.82;margin-bottom:2rem;max-width:440px}
.hdesc strong{color:rgba(255,255,255,.88)}

.hbtns{display:flex;gap:.85rem;flex-wrap:wrap;margin-bottom:2.2rem}
.bmain{display:inline-flex;align-items:center;gap:.4rem;background:var(--gold);color:var(--ink);font-weight:800;font-size:.97rem;padding:.88rem 1.9rem;border-radius:9px;text-decoration:none;transition:.22s;box-shadow:0 4px 22px rgba(201,162,58,.28)}
.bmain:hover{background:var(--gold2);transform:translateY(-2px);box-shadow:0 8px 28px rgba(201,162,58,.38)}
.bsec{display:inline-block;color:rgba(255,255,255,.7);font-weight:600;font-size:.93rem;padding:.88rem 1.5rem;border-radius:9px;text-decoration:none;border:1px solid rgba(255,255,255,.14);transition:.22s}
.bsec:hover{border-color:rgba(255,255,255,.38);color:#fff}

.hproof{display:flex;align-items:center;gap:1rem;flex-wrap:wrap}
.hstars{color:var(--gold);font-size:.95rem;letter-spacing:.06em}
.hproof-txt{font-size:.82rem;color:rgba(255,255,255,.45)}
.hproof-txt strong{color:rgba(255,255,255,.7)}

/* right card */
.hr{opacity:0;animation:fu .85s .3s forwards}
.hcard{background:rgba(255,255,255,.038);border:1px solid rgba(255,255,255,.07);border-radius:18px;padding:1.6rem;backdrop-filter:blur(8px)}
.hctitle{font-size:.7rem;font-weight:700;color:var(--gold);letter-spacing:.1em;text-transform:uppercase;margin-bottom:1rem;display:flex;align-items:center;gap:.45rem}
.hctitle::before{content:'';width:18px;height:2px;background:var(--gold);border-radius:2px}

.svc-tabs{display:flex;gap:.5rem;margin-bottom:1rem;background:rgba(255,255,255,.04);border-radius:8px;padding:.3rem}
.stab{flex:1;text-align:center;font-size:.76rem;font-weight:700;color:rgba(255,255,255,.4);padding:.5rem .3rem;border-radius:6px;cursor:pointer;transition:.2s}
.stab.active{background:var(--gold);color:var(--ink)}

.svc-panel{display:none}
.svc-panel.active{display:block}
.svc-feat{display:flex;flex-direction:column;gap:.6rem;margin-bottom:1rem}
.svc-feat-item{display:flex;align-items:flex-start;gap:.65rem;padding:.65rem .8rem;background:rgba(255,255,255,.03);border:1px solid rgba(255,255,255,.055);border-radius:8px}
.svc-feat-item svg{flex-shrink:0;margin-top:1px}
.svc-feat-item p{font-size:.82rem;color:rgba(255,255,255,.65);line-height:1.5}
.svc-feat-item strong{color:#fff;display:block;font-size:.84rem;margin-bottom:.1rem}

.hstats{display:grid;grid-template-columns:repeat(3,1fr);gap:.6rem;border-top:1px solid rgba(255,255,255,.06);padding-top:1rem;margin-top:.4rem}
.hst{text-align:center}
.hst-v{font-family:'Noto Serif Hebrew',serif;font-size:1.5rem;font-weight:900;color:var(--gold);display:block;line-height:1}
.hst-l{font-size:.67rem;color:rgba(255,255,255,.38);margin-top:.22rem;display:block}

/* ── TRUST BAR ── */
.tbar{background:var(--off);padding:1rem 2.2rem;border-bottom:1px solid var(--bdr)}
.tbar-in{max-width:980px;margin:0 auto;display:flex;align-items:center;justify-content:center;gap:2.5rem;flex-wrap:wrap}
.ti{display:flex;align-items:center;gap:.42rem;font-size:.8rem;color:var(--mid);font-weight:500}
.tick{width:16px;height:16px;border-radius:50%;background:rgba(34,197,94,.1);border:1px solid rgba(34,197,94,.28);display:flex;align-items:center;justify-content:center;flex-shrink:0}

/* ── GENERIC WRAP ── */
.w{max-width:1080px;margin:0 auto;padding:4.5rem 2.2rem}
.sl{display:inline-block;font-size:.68rem;font-weight:700;letter-spacing:.14em;text-transform:uppercase;color:var(--gold);border-bottom:2px solid var(--gold);padding-bottom:.18rem;margin-bottom:.8rem}
.sh{font-family:'Noto Serif Hebrew',serif;font-size:clamp(1.6rem,2.8vw,2.4rem);font-weight:900;line-height:1.15;color:var(--text);margin-bottom:.65rem}
.ss{font-size:.94rem;color:var(--mid);line-height:1.78;max-width:520px}

/* ── SERVICES ── */
.svcs-bg{background:var(--off);border-bottom:1px solid var(--bdr)}
.svcs-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(295px,1fr));gap:1.3rem;margin-top:2.5rem}
.scard{background:var(--white);border:1.5px solid var(--bdr);border-radius:14px;padding:2rem;position:relative;overflow:hidden;transition:.25s}
.scard::before{content:'';position:absolute;top:0;right:0;left:0;height:3px;background:linear-gradient(90deg,var(--gold),var(--gold2))}
.scard:hover{box-shadow:0 14px 40px rgba(13,27,48,.09);transform:translateY(-4px);border-color:rgba(201,162,58,.35)}
.scard-hot{border-color:rgba(201,162,58,.4);box-shadow:0 4px 24px rgba(201,162,58,.1)}
.shot-badge{position:absolute;top:1.1rem;left:1.1rem;background:var(--gold);color:var(--ink);font-size:.65rem;font-weight:800;padding:.18rem .55rem;border-radius:100px}
.sico{width:44px;height:44px;border-radius:11px;background:var(--gold3);border:1px solid rgba(201,162,58,.18);display:flex;align-items:center;justify-content:center;margin-bottom:1.1rem}
.snum{font-size:.68rem;font-weight:700;color:var(--gold);letter-spacing:.1em;text-transform:uppercase;margin-bottom:.4rem}
.scard h3{font-family:'Noto Serif Hebrew',serif;font-size:1.25rem;font-weight:900;color:var(--text);margin-bottom:.55rem}
.scard p{font-size:.86rem;color:var(--mid);line-height:1.72;margin-bottom:1.1rem}
.slist{list-style:none;display:flex;flex-direction:column;gap:.38rem}
.slist li{display:flex;align-items:center;gap:.5rem;font-size:.82rem;color:var(--mid)}
.slist li::before{content:'✓';color:var(--gold);font-weight:800;font-size:.78rem;flex-shrink:0}
.spill{display:inline-block;font-size:.7rem;font-weight:700;background:var(--gold3);color:var(--gold);padding:.2rem .6rem;border-radius:100px;margin-top:.9rem}

.pkg-bar{margin-top:1.3rem;background:linear-gradient(135deg,rgba(201,162,58,.09),rgba(201,162,58,.04));border:1px solid rgba(201,162,58,.22);border-radius:12px;padding:1.3rem 1.8rem;display:flex;align-items:center;justify-content:space-between;flex-wrap:wrap;gap:1rem}
.pkg-bar h4{font-size:1rem;font-weight:800;color:var(--text);margin-bottom:.2rem}
.pkg-bar p{font-size:.83rem;color:var(--mid)}
.pkg-bar a{background:var(--gold);color:var(--ink);font-weight:800;font-size:.88rem;padding:.7rem 1.6rem;border-radius:8px;text-decoration:none;white-space:nowrap;transition:.2s}
.pkg-bar a:hover{background:var(--gold2)}

/* ── PROBLEM ── */
.prob-bg{background:var(--ink);padding:4.5rem 2.2rem}
.prob-in{max-width:1080px;margin:0 auto;display:grid;grid-template-columns:1fr 1fr;gap:4rem;align-items:start}
@media(max-width:760px){.prob-in{grid-template-columns:1fr;gap:2.5rem}}
.prob-in .sl{color:rgba(201,162,58,.8);border-bottom-color:rgba(201,162,58,.8)}
.prob-in .sh{color:#fff}
.pains{margin-top:1.6rem;list-style:none;display:flex;flex-direction:column;gap:.75rem}
.pain{display:flex;gap:.8rem;align-items:flex-start;padding:.85rem .95rem;background:rgba(255,255,255,.025);border:1px solid rgba(255,255,255,.055);border-radius:9px}
.px{width:20px;height:20px;border-radius:50%;background:rgba(239,68,68,.1);border:1px solid rgba(239,68,68,.22);display:flex;align-items:center;justify-content:center;flex-shrink:0;margin-top:2px;color:#f87171;font-size:.7rem;font-weight:900}
.pain strong{color:#fff;display:block;font-size:.9rem;margin-bottom:.15rem}
.pain p{font-size:.84rem;color:rgba(255,255,255,.52);line-height:1.6}

.solcard{background:rgba(255,255,255,.035);border:1px solid rgba(201,162,58,.18);border-radius:16px;padding:1.7rem}
.sollabel{font-size:.68rem;font-weight:800;color:var(--gold);letter-spacing:.12em;text-transform:uppercase;margin-bottom:1.1rem;display:flex;align-items:center;gap:.45rem}
.sollabel::before{content:'';width:14px;height:2px;background:var(--gold)}
.solrow{display:flex;gap:.8rem;align-items:flex-start;padding:.8rem .9rem;background:rgba(255,255,255,.025);border-radius:8px;margin-bottom:.6rem;border:1px solid rgba(255,255,255,.045)}
.solrow:last-child{margin-bottom:0}
.soln{width:28px;height:28px;border-radius:6px;background:var(--gold);color:var(--ink);font-weight:900;font-size:.82rem;display:flex;align-items:center;justify-content:center;flex-shrink:0}
.solrow strong{color:#fff;display:block;font-size:.88rem;margin-bottom:.15rem}
.solrow p{font-size:.82rem;color:rgba(255,255,255,.5);line-height:1.55}

/* ── PLATFORMS ── */
.plats-bg{background:var(--off);border-top:1px solid var(--bdr);border-bottom:1px solid var(--bdr)}
.plats{display:grid;grid-template-columns:repeat(auto-fit,minmax(175px,1fr));gap:1rem;margin-top:2.2rem}
.plat{background:var(--white);border:1.5px solid var(--bdr);border-radius:var(--r);padding:1.4rem;text-align:center;transition:.22s}
.plat:hover{border-color:rgba(201,162,58,.38);transform:translateY(-3px);box-shadow:0 8px 26px rgba(13,27,48,.07)}
.plat-ico{font-size:1.9rem;margin-bottom:.6rem}
.plat-n{font-weight:800;font-size:.92rem;color:var(--text);margin-bottom:.3rem}
.plat-d{font-size:.78rem;color:var(--mid);line-height:1.5}

/* ── HOW ── */
.steps{display:grid;grid-template-columns:repeat(auto-fit,minmax(210px,1fr));gap:1.3rem;margin-top:2.2rem}
.step{background:var(--white);border:1.5px solid var(--bdr);border-radius:14px;padding:1.7rem;position:relative;overflow:hidden;transition:.22s}
.step::after{content:'';position:absolute;top:0;right:0;left:0;height:3px;background:linear-gradient(90deg,var(--gold),var(--gold2))}
.step:hover{box-shadow:0 12px 34px rgba(13,27,48,.09);transform:translateY(-3px);border-color:rgba(201,162,58,.3)}
.stepn{font-family:'Noto Serif Hebrew',serif;font-size:3.2rem;font-weight:900;color:rgba(13,27,48,.06);line-height:1;margin-bottom:.6rem}
.step h3{font-size:.97rem;font-weight:800;color:var(--text);margin-bottom:.45rem}
.step p{font-size:.84rem;color:var(--mid);line-height:1.7}
.steppill{display:inline-block;font-size:.67rem;font-weight:700;background:var(--gold3);color:var(--gold);padding:.2rem .6rem;border-radius:100px;margin-top:.7rem}

/* ── WHY ── */
.why-bg{background:var(--ink);padding:4.5rem 2.2rem}
.why-in{max-width:1080px;margin:0 auto}
.why-in .sl{color:rgba(201,162,58,.8);border-bottom-color:rgba(201,162,58,.8)}
.why-in .sh{color:#fff}
.why-in .ss{color:rgba(255,255,255,.48)}
.whys{display:grid;grid-template-columns:repeat(auto-fit,minmax(255px,1fr));gap:.9rem;margin-top:2.2rem}
.why{display:flex;gap:.85rem;align-items:flex-start;padding:1.1rem;background:rgba(255,255,255,.025);border:1px solid rgba(255,255,255,.055);border-radius:9px;transition:.18s}
.why:hover{border-color:rgba(201,162,58,.22);background:rgba(201,162,58,.04)}
.why-ico{width:38px;height:38px;border-radius:9px;background:rgba(201,162,58,.1);border:1px solid rgba(201,162,58,.18);display:flex;align-items:center;justify-content:center;flex-shrink:0;font-size:1rem}
.why h4{font-size:.9rem;font-weight:700;color:#fff;margin-bottom:.25rem}
.why p{font-size:.8rem;color:rgba(255,255,255,.48);line-height:1.6}

/* ── PROCESS TIMELINE ── */
.timeline-bg{background:var(--off);border-top:1px solid var(--bdr)}
.timeline{display:flex;gap:0;margin-top:2.2rem;position:relative}
.timeline::before{content:'';position:absolute;top:28px;right:28px;left:28px;height:2px;background:linear-gradient(90deg,var(--gold),var(--gold2),var(--gold));opacity:.25;border-radius:2px}
@media(max-width:700px){.timeline{flex-direction:column}.timeline::before{display:none}}
.tl-step{flex:1;text-align:center;padding:0 .8rem;position:relative}
.tl-circle{width:56px;height:56px;border-radius:50%;background:var(--ink);border:2px solid rgba(201,162,58,.3);display:flex;align-items:center;justify-content:center;margin:0 auto 1rem;font-family:'Noto Serif Hebrew',serif;font-size:1.1rem;font-weight:900;color:var(--gold);position:relative;z-index:1}
.tl-step.done .tl-circle{background:var(--gold);border-color:var(--gold);color:var(--ink)}
.tl-step h4{font-size:.9rem;font-weight:800;color:var(--text);margin-bottom:.3rem}
.tl-step p{font-size:.78rem;color:var(--mid);line-height:1.6}
.tl-pill{display:inline-block;font-size:.66rem;font-weight:700;background:var(--gold3);color:var(--gold);padding:.18rem .55rem;border-radius:100px;margin-top:.5rem}

/* ── TESTIMONIALS ── */
.testis-bg{background:var(--white);border-top:1px solid var(--bdr)}
.tgrid{display:grid;grid-template-columns:repeat(auto-fit,minmax(270px,1fr));gap:1.3rem;margin-top:2.2rem}
.tc{background:var(--off);border:1.5px solid var(--bdr);border-radius:14px;padding:1.6rem;position:relative;transition:.2s}
.tc:hover{box-shadow:0 8px 28px rgba(13,27,48,.07);border-color:rgba(201,162,58,.28)}
.tc-v{position:absolute;top:1.1rem;left:1.1rem;background:rgba(34,197,94,.08);color:#16a34a;font-size:.65rem;font-weight:700;padding:.16rem .52rem;border-radius:100px;border:1px solid rgba(34,197,94,.16)}
.tcstars{color:var(--gold);font-size:.9rem;letter-spacing:.06em;margin-bottom:.8rem}
.tcq{font-size:.89rem;color:var(--text);line-height:1.75;font-style:italic;margin-bottom:1.1rem;padding-right:1.1rem;position:relative}
.tcq::before{content:'"';position:absolute;right:0;top:-.25rem;font-family:'Noto Serif Hebrew',serif;font-size:2.2rem;color:var(--gold);opacity:.28;line-height:1}
.tcwho{display:flex;align-items:center;gap:.65rem}
.tcav{width:38px;height:38px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-weight:800;font-size:.9rem;color:#fff;flex-shrink:0}
.tcname{font-weight:700;font-size:.84rem;color:var(--text)}
.tcrole{font-size:.73rem;color:var(--mid)}
.tnote{text-align:center;margin-top:1.3rem;font-size:.76rem;color:var(--mid)}

/* ── FAQ ── */
.faqs{max-width:700px;margin-top:2.2rem;display:flex;flex-direction:column;gap:.65rem}
.fq{border:1.5px solid var(--bdr);border-radius:9px;overflow:hidden;transition:.18s}
.fq.open{border-color:rgba(201,162,58,.32)}
.fqh{padding:1rem 1.2rem;font-weight:600;font-size:.92rem;cursor:pointer;display:flex;justify-content:space-between;align-items:center;gap:1rem;color:var(--text);user-select:none;transition:.15s}
.fqh:hover{color:var(--blue)}
.farr{color:var(--gold);transition:.28s;font-size:.95rem;flex-shrink:0}
.fq.open .farr{transform:rotate(180deg)}
.fqb{max-height:0;overflow:hidden;transition:max-height .32s ease,padding .28s}
.fq.open .fqb{max-height:260px;padding:0 1.2rem 1.1rem}
.fqb p{font-size:.87rem;color:var(--mid);line-height:1.8}

/* ── FORM ── */
.form-bg{background:var(--ink);padding:5rem 2.2rem}
.form-in{max-width:1080px;margin:0 auto;display:grid;grid-template-columns:1fr 1fr;gap:4.5rem;align-items:center}
@media(max-width:760px){.form-in{grid-template-columns:1fr;gap:2.5rem}}
.form-in .sl{color:rgba(201,162,58,.8);border-bottom-color:rgba(201,162,58,.8)}
.form-in .sh{color:#fff}
.fprom{margin-top:1.8rem;display:flex;flex-direction:column;gap:.75rem}
.fp{display:flex;align-items:center;gap:.7rem;color:rgba(255,255,255,.65);font-size:.86rem}
.fpck{width:22px;height:22px;border-radius:5px;background:rgba(34,197,94,.1);border:1px solid rgba(34,197,94,.22);display:flex;align-items:center;justify-content:center;flex-shrink:0;color:var(--grn);font-size:.75rem;font-weight:900}

.fcard{background:#fff;border-radius:16px;padding:2rem 1.8rem;box-shadow:0 28px 70px rgba(0,0,0,.28)}
.ff{margin-bottom:1rem}
.ff label{display:block;font-size:.77rem;font-weight:700;color:var(--text);margin-bottom:.38rem;letter-spacing:.02em}
.ff input,.ff select,.ff textarea{width:100%;border:1.5px solid var(--bdr);border-radius:8px;padding:.75rem .9rem;font-family:'Rubik',sans-serif;font-size:.92rem;color:var(--text);background:var(--off);transition:.18s;outline:none}
.ff input:focus,.ff select:focus,.ff textarea:focus{border-color:var(--gold);box-shadow:0 0 0 3px rgba(201,162,58,.12);background:#fff}
.ff textarea{resize:vertical;min-height:75px}
.ff select{cursor:pointer;appearance:none;background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='11' height='7' viewBox='0 0 11 7'%3E%3Cpath d='M1 1l4.5 4.5L10 1' stroke='%23566480' stroke-width='1.8' fill='none' stroke-linecap='round'/%3E%3C/svg%3E");background-repeat:no-repeat;background-position:left .9rem center}

/* service selector tabs in form */
.fsvc{display:flex;gap:.5rem;margin-bottom:1.1rem;background:var(--off);border-radius:8px;padding:.28rem}
.fsvc-t{flex:1;text-align:center;font-size:.74rem;font-weight:700;color:var(--mid);padding:.48rem .3rem;border-radius:6px;cursor:pointer;transition:.18s;line-height:1.3}
.fsvc-t.a{background:var(--ink);color:var(--gold)}

.fsub{width:100%;background:var(--ink);color:var(--gold);font-family:'Rubik',sans-serif;font-weight:800;font-size:1rem;padding:.95rem;border-radius:8px;border:none;cursor:pointer;margin-top:.3rem;transition:.22s;display:flex;align-items:center;justify-content:center;gap:.45rem;letter-spacing:.02em}
.fsub:hover:not(:disabled){background:#0d1b30;transform:translateY(-2px)}
.fsub:disabled{opacity:.55;cursor:not-allowed;transform:none}
.spin{display:none;width:15px;height:15px;border:2.5px solid rgba(201,162,58,.25);border-radius:50%;border-top-color:var(--gold);animation:sp .7s linear infinite}
@keyframes sp{to{transform:rotate(360deg)}}
.fnote{margin-top:.7rem;font-size:.73rem;color:var(--mid);text-align:center;display:flex;align-items:center;justify-content:center;gap:.32rem}

#smsg{display:none;text-align:center;padding:2rem .5rem}
.sico{font-size:3.8rem;margin-bottom:1rem;animation:pop .45s ease}
@keyframes pop{0%{transform:scale(0)}80%{transform:scale(1.1)}100%{transform:scale(1)}}
#smsg h3{font-family:'Noto Serif Hebrew',serif;font-size:1.75rem;font-weight:900;color:var(--text);margin-bottom:.55rem}
#smsg p{font-size:.92rem;color:var(--mid);line-height:1.75}

/* ── FOOTER ── */
footer{background:#040a14;padding:2rem 2.2rem;text-align:center;border-top:1px solid rgba(255,255,255,.045)}
.flogo{font-family:'Noto Serif Hebrew',serif;font-weight:900;font-size:1rem;color:var(--gold);margin-bottom:.4rem}
footer p{font-size:.76rem;color:rgba(255,255,255,.2)}

/* ── REVEAL ── */
.r{opacity:0;transform:translateY(24px);transition:opacity .62s ease,transform .62s ease}
.r.on{opacity:1;transform:translateY(0)}
@keyframes fu{from{opacity:0;transform:translateY(20px)}to{opacity:1;transform:translateY(0)}}

@media(max-width:560px){
  #nav{padding:0 1.1rem}
  .hero{padding:6.5rem 1.1rem 3.5rem}
  .w,.svcs-bg .w,.prob-bg,.why-bg,.form-bg,.testis-bg .w,.plats-bg .w,.timeline-bg .w{padding-inline:1.1rem}
  .fcard{padding:1.5rem 1.1rem}
  .pkg-bar{flex-direction:column;align-items:flex-start}
}
</style>
</head>
<body>

<!-- NAV -->
<nav id="nav">
  <div class="nl">
    <div class="nm">M</div>
    <div class="nt">מאור <span>— דיגיטל לעסקים</span></div>
  </div>
  <div class="nr">
    <a href="#services" class="nl2">שירותים</a>
    <a href="#how" class="nl2">איך עובד</a>
    <a href="#reviews" class="nl2">המלצות</a>
    <a href="#contact" class="nb">ייעוץ חינם</a>
  </div>
</nav>

<!-- HERO -->
<section class="hero">
  <div class="hbg"></div>
  <div class="hgrid"></div>
  <div class="hi">
    <div class="hl">
      <div class="hpill"><span class="hpill-dot"></span>פתרון דיגיטלי מלא לעסקים קטנים</div>
      <h1>אתר מקצועי.<br>לקוחות שמגיעים.<br><em class="ul">תוצאות אמיתיות.</em></h1>
      <p class="hdesc">אני מאור — בונה לך <strong>אתר או דף נחיתה</strong> שנראה מקצועי, ואז מביא אליו <strong>לקוחות חדשים</strong> דרך גוגל, פייסבוק ואינסטגרם. הכל במקום אחד.</p>
      <div class="hbtns">
        <a href="#contact" class="bmain">
          <svg width="15" height="15" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path d="M5 12h14M12 5l7 7-7 7"/></svg>
          רוצה להתחיל — ייעוץ חינם
        </a>
        <a href="#services" class="bsec">מה אני מציע?</a>
      </div>
      <div class="hproof">
        <span class="hstars">★★★★★</span>
        <span class="hproof-txt"><strong>לקוחות מרוצים</strong> שכבר מקבלים לידים</span>
      </div>
    </div>
    <div class="hr">
      <div class="hcard">
        <div class="hctitle">בחר שירות וראה מה כלול</div>
        <div class="svc-tabs">
          <div class="stab active" onclick="switchTab(0)">אתרים</div>
          <div class="stab" onclick="switchTab(1)">דפי נחיתה</div>
          <div class="stab" onclick="switchTab(2)">לידים</div>
        </div>
        <div class="svc-panel active" id="tp0">
          <div class="svc-feat">
            <div class="svc-feat-item"><svg width="14" height="14" fill="none" stroke="#c9a23a" stroke-width="2.5" viewBox="0 0 24 24"><polyline points="20 6 9 17 4 12"/></svg><p><strong>עיצוב מותאם אישית</strong>נראה בדיוק כמו העסק שלך — לא תבנית רגילה</p></div>
            <div class="svc-feat-item"><svg width="14" height="14" fill="none" stroke="#c9a23a" stroke-width="2.5" viewBox="0 0 24 24"><polyline points="20 6 9 17 4 12"/></svg><p><strong>מהיר ומותאם לנייד</strong>חווית משתמש שמביאה לקוחות להישאר</p></div>
            <div class="svc-feat-item"><svg width="14" height="14" fill="none" stroke="#c9a23a" stroke-width="2.5" viewBox="0 0 24 24"><polyline points="20 6 9 17 4 12"/></svg><p><strong>אופטימיזציה לגוגל (SEO)</strong>כדי שלקוחות ימצאו אותך בחיפוש</p></div>
          </div>
        </div>
        <div class="svc-panel" id="tp1">
          <div class="svc-feat">
            <div class="svc-feat-item"><svg width="14" height="14" fill="none" stroke="#c9a23a" stroke-width="2.5" viewBox="0 0 24 24"><polyline points="20 6 9 17 4 12"/></svg><p><strong>ממוקד להמרה</strong>דף אחד, מטרה אחת — לגרום לזה שיתקשרו</p></div>
            <div class="svc-feat-item"><svg width="14" height="14" fill="none" stroke="#c9a23a" stroke-width="2.5" viewBox="0 0 24 24"><polyline points="20 6 9 17 4 12"/></svg><p><strong>טופס לידים חכם</strong>מחובר ישירות למייל שלך — ליד מגיע מיד</p></div>
            <div class="svc-feat-item"><svg width="14" height="14" fill="none" stroke="#c9a23a" stroke-width="2.5" viewBox="0 0 24 24"><polyline points="20 6 9 17 4 12"/></svg><p><strong>מוכן תוך 48-72 שעות</strong>מהיר, יעיל, ועולה לאוויר מהר</p></div>
          </div>
        </div>
        <div class="svc-panel" id="tp2">
          <div class="svc-feat">
            <div class="svc-feat-item"><svg width="14" height="14" fill="none" stroke="#c9a23a" stroke-width="2.5" viewBox="0 0 24 24"><polyline points="20 6 9 17 4 12"/></svg><p><strong>גוגל, פייסבוק, אינסטגרם</strong>קמפיינים שמגיעים לקהל שמחפש אותך</p></div>
            <div class="svc-feat-item"><svg width="14" height="14" fill="none" stroke="#c9a23a" stroke-width="2.5" viewBox="0 0 24 24"><polyline points="20 6 9 17 4 12"/></svg><p><strong>לידים מסוננים ורלוונטיים</strong>לא כמות — איכות. אנשים שרוצים את השירות שלך</p></div>
            <div class="svc-feat-item"><svg width="14" height="14" fill="none" stroke="#c9a23a" stroke-width="2.5" viewBox="0 0 24 24"><polyline points="20 6 9 17 4 12"/></svg><p><strong>תשלום על תוצאות</strong>אם לא מביא — אתה לא משלם. פשוט ככה</p></div>
          </div>
        </div>
        <div class="hstats">
          <div class="hst"><span class="hst-v">48h</span><span class="hst-l">עד ליד ראשון</span></div>
          <div class="hst"><span class="hst-v">100%</span><span class="hst-l">מותאם אישית</span></div>
          <div class="hst"><span class="hst-v">0₪</span><span class="hst-l">ייעוץ ראשון</span></div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- TRUST BAR -->
<div class="tbar">
  <div class="tbar-in">
    <div class="ti"><div class="tick"><svg width="9" height="9" fill="none" stroke="currentColor" stroke-width="3" viewBox="0 0 24 24"><polyline points="20 6 9 17 4 12"/></svg></div>ללא התחייבות</div>
    <div class="ti"><div class="tick"><svg width="9" height="9" fill="none" stroke="currentColor" stroke-width="3" viewBox="0 0 24 24"><polyline points="20 6 9 17 4 12"/></svg></div>תשלום על תוצאות</div>
    <div class="ti"><div class="tick"><svg width="9" height="9" fill="none" stroke="currentColor" stroke-width="3" viewBox="0 0 24 24"><polyline points="20 6 9 17 4 12"/></svg></div>שקיפות מלאה</div>
    <div class="ti"><div class="tick"><svg width="9" height="9" fill="none" stroke="currentColor" stroke-width="3" viewBox="0 0 24 24"><polyline points="20 6 9 17 4 12"/></svg></div>ייעוץ ראשון חינם</div>
    <div class="ti"><div class="tick"><svg width="9" height="9" fill="none" stroke="currentColor" stroke-width="3" viewBox="0 0 24 24"><polyline points="20 6 9 17 4 12"/></svg></div>ליווי אישי ממאור</div>
  </div>
</div>

<!-- SERVICES -->
<div class="svcs-bg" id="services">
<div class="w">
  <div class="r" style="text-align:center;max-width:600px;margin:0 auto 0">
    <span class="sl">השירותים שלי</span>
    <h2 class="sh">כל מה שהעסק שלך צריך — בלי לרדוף אחרי ספקים שונים</h2>
    <p class="ss" style="margin:0 auto">אני מטפל בכל הצד הדיגיטלי שלך — מהאתר ועד הלקוח שמגיע אליו</p>
  </div>
  <div class="svcs-grid">
    <div class="scard r">
      <div class="sico"><svg width="20" height="20" fill="none" stroke="#c9a23a" stroke-width="2" viewBox="0 0 24 24"><rect x="3" y="3" width="18" height="18" rx="2"/><path d="M3 9h18M9 21V9"/></svg></div>
      <div class="snum">שירות 01</div>
      <h3>בניית אתרים</h3>
      <p>אתר מקצועי שמייצג את העסק שלך 24/7 — מהיר, נקי, ומותאם לנייד. לקוח שמגיע לאתר שלך חייב להרגיש שסומך עליך.</p>
      <ul class="slist">
        <li>עיצוב מותאם אישית לעסק שלך</li>
        <li>מהיר ומאובטח — מותאם לגוגל</li>
        <li>מוכן תוך 5-7 ימי עסקים</li>
      </ul>
      <span class="spill">5-7 ימי עסקים</span>
    </div>
    <div class="scard scard-hot r">
      <div class="shot-badge">הכי פופולרי</div>
      <div class="sico"><svg width="20" height="20" fill="none" stroke="#c9a23a" stroke-width="2" viewBox="0 0 24 24"><path d="M4 15s1-1 4-1 5 2 8 2 4-1 4-1V3s-1 1-4 1-5-2-8-2-4 1-4 1z"/><line x1="4" y1="22" x2="4" y2="15"/></svg></div>
      <div class="snum">שירות 02</div>
      <h3>דפי נחיתה</h3>
      <p>דף ממוקד שהופך מבקרים ללידים. תוצאה אחת ברורה — לגרום לאנשים להשאיר פרטים. מחובר ישירות למייל שלך.</p>
      <ul class="slist">
        <li>ממוקד להמרה — לא לקרוא, לפעול</li>
        <li>טופס לידים חכם למייל שלך</li>
        <li>מוכן תוך 48-72 שעות</li>
      </ul>
      <span class="spill">48-72 שעות</span>
    </div>
    <div class="scard r">
      <div class="sico"><svg width="20" height="20" fill="none" stroke="#c9a23a" stroke-width="2" viewBox="0 0 24 24"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M23 21v-2a4 4 0 0 0-3-3.87M16 3.13a4 4 0 0 1 0 7.75"/></svg></div>
      <div class="snum">שירות 03</div>
      <h3>הבאת לידים</h3>
      <p>קמפיינים בגוגל, פייסבוק ואינסטגרם שמביאים לקוחות רלוונטיים ישירות אליך — מסוננים ומוכנים לשיחה.</p>
      <ul class="slist">
        <li>גוגל, פייסבוק, אינסטגרם</li>
        <li>לידים חמים ומסוננים בלבד</li>
        <li>תשלום רק על תוצאות</li>
      </ul>
      <span class="spill">תוך 48 שעות</span>
    </div>
  </div>
  <div class="pkg-bar r">
    <div>
      <h4>חבילה מלאה — אתר + דף נחיתה + לידים</h4>
      <p>הפתרון הדיגיטלי המלא לעסק שלך — במחיר מיוחד לחבילה</p>
    </div>
    <a href="#contact">אני רוצה חבילה מלאה</a>
  </div>
</div>
</div>

<!-- PROBLEM -->
<div class="prob-bg">
  <div class="prob-in">
    <div class="r">
      <span class="sl">מכיר את זה?</span>
      <h2 class="sh" style="color:#fff">הבעיה של כל עסק קטן</h2>
      <ul class="pains">
        <li class="pain"><div class="px">✕</div><div><strong>אין זמן לרדוף אחרי לקוחות</strong><p>אתה מקצוען בתחום שלך — אבל מי מביא את הלקוחות?</p></div></li>
        <li class="pain"><div class="px">✕</div><div><strong>האתר לא מביא לקוחות</strong><p>יש לך אתר שנראה בסדר — אבל אף אחד לא מוצא אותו</p></div></li>
        <li class="pain"><div class="px">✕</div><div><strong>שילמת על פרסום ולא ראית תוצאות</strong><p>כסף שהלך לאוויר על קמפיינים שלא הביאו כלום</p></div></li>
        <li class="pain"><div class="px">✕</div><div><strong>תלות בהמלצות בלבד</strong><p>פה ממליץ, שם לקוח — זה לא עסק, זה מזל</p></div></li>
      </ul>
    </div>
    <div class="r">
      <span class="sl" style="color:rgba(201,162,58,.8);border-bottom-color:rgba(201,162,58,.8)">הפתרון שלי</span>
      <h2 class="sh" style="color:#fff">אני דואג לדיגיטל,<br>אתה דואג לעסק</h2>
      <div class="solcard">
        <div class="sollabel">שלושה שלבים פשוטים</div>
        <div class="solrow"><div class="soln">1</div><div><strong>אתר / דף נחיתה מקצועי</strong><p>נוכחות דיגיטלית שמייצגת אותך ומביאה לקוחות לפעול</p></div></div>
        <div class="solrow"><div class="soln">2</div><div><strong>קמפיין ממוקד</strong><p>מביא את הקהל הנכון — לפי אזור, גיל, ותחום עניין</p></div></div>
        <div class="solrow"><div class="soln">3</div><div><strong>לידים ישירות לנייד שלך</strong><p>שם, טלפון, ומה הם צריכים — אתה רק מתקשר וסוגר</p></div></div>
      </div>
    </div>
  </div>
</div>

<!-- PLATFORMS -->
<div class="plats-bg" id="platforms">
<div class="w">
  <div class="r">
    <span class="sl">איפה אני מפרסם</span>
    <h2 class="sh">נמצא בכל מקום שהלקוחות שלך נמצאים</h2>
    <p class="ss">אני מנהל קמפיינים בכל הערוצים — כך שלא תפספס אף לקוח פוטנציאלי</p>
  </div>
  <div class="plats r">
    <div class="plat"><div class="plat-ico">🔍</div><div class="plat-n">גוגל Ads</div><div class="plat-d">לקוחות שמחפשים אקטיבית — הכי חמים</div></div>
    <div class="plat"><div class="plat-ico">📘</div><div class="plat-n">פייסבוק</div><div class="plat-d">פרסום ממוקד לגיל ותחומי עניין</div></div>
    <div class="plat"><div class="plat-ico">📸</div><div class="plat-n">אינסטגרם</div><div class="plat-d">קמפיינים ויזואליים שמביאים פניות</div></div>
    <div class="plat"><div class="plat-ico">📍</div><div class="plat-n">גוגל מקומי</div><div class="plat-d">לקוחות מהאזור שלך מוצאים אותך קודם</div></div>
    <div class="plat"><div class="plat-ico">💼</div><div class="plat-n">לינקדאין</div><div class="plat-d">לעסקים שמכוונים לבעלי עסקים</div></div>
    <div class="plat"><div class="plat-ico">🌐</div><div class="plat-n">דפי נחיתה</div><div class="plat-d">מבקרים הופכים ללידים</div></div>
  </div>
</div>
</div>

<!-- HOW IT WORKS -->
<div id="how">
<div class="w">
  <div class="r">
    <span class="sl">התהליך</span>
    <h2 class="sh">מהשיחה הראשונה עד הליד הראשון</h2>
    <p class="ss">בלי בירוקרטיה, בלי המתנות — מהיום הראשון אתה כבר רואה תנועה</p>
  </div>
  <div class="steps">
    <div class="step r">
      <div class="stepn">01</div>
      <h3>שיחת היכרות חינמית</h3>
      <p>15 דקות שבהן אני מקשיב — מבין מה העסק, מי הלקוח האידיאלי, ומה המטרות. ללא מכירה, ללא לחץ.</p>
      <span class="steppill">15 דקות בלבד</span>
    </div>
    <div class="step r">
      <div class="stepn">02</div>
      <h3>בניית הנוכחות הדיגיטלית</h3>
      <p>בונה את האתר או דף הנחיתה שלך — מעוצב, מהיר, ומוכן להמיר מבקרים ללקוחות.</p>
      <span class="steppill">5-7 ימים</span>
    </div>
    <div class="step r">
      <div class="stepn">03</div>
      <h3>הפעלת קמפיין ממוקד</h3>
      <p>בוחר פלטפורמות ובונה קמפיין שמגיע בדיוק לאנשים שמחפשים את השירות שלך.</p>
      <span class="steppill">תוך 24-48 שעות</span>
    </div>
    <div class="step r">
      <div class="stepn">04</div>
      <h3>לידים מגיעים אליך</h3>
      <p>אתה מקבל התראה עם שם, טלפון ומה הלקוח צריך. מה שנותר — להתקשר ולסגור עסקה.</p>
      <span class="steppill">בזמן אמת לנייד</span>
    </div>
  </div>
</div>
</div>

<!-- WHY ME -->
<div class="why-bg">
  <div class="why-in r">
    <span class="sl">למה מאור?</span>
    <h2 class="sh">ליווי אישי — לא חברה גדולה</h2>
    <p class="ss">אני לא עובד עם מאה לקוחות בו-זמנית. כל עסק מקבל ממני תשומת לב מלאה</p>
    <div class="whys">
      <div class="why"><div class="why-ico">🎯</div><div><h4>פתרון מלא ממקום אחד</h4><p>אתר, דף נחיתה, ולידים — לא צריך 3 ספקים שונים</p></div></div>
      <div class="why"><div class="why-ico">📍</div><div><h4>מותאם לאזור שלך</h4><p>לקוחות רק מהאזור שבו אתה עובד — לא מכל הארץ</p></div></div>
      <div class="why"><div class="why-ico">👁</div><div><h4>שקיפות מלאה</h4><p>אתה רואה כל ליד, כל תוצאה, בזמן אמת</p></div></div>
      <div class="why"><div class="why-ico">🤝</div><div><h4>תשלום על תוצאות</h4><p>אם אני לא מביא — אתה לא משלם. פשוט ככה</p></div></div>
      <div class="why"><div class="why-ico">📞</div><div><h4>זמין אישית</h4><p>מדברים ישירות איתי — לא עם נציג, לא עם בוט</p></div></div>
      <div class="why"><div class="why-ico">🚀</div><div><h4>מתחיל מהר</h4><p>תוך ימים ספורים — אתר חי ולידים בדרך</p></div></div>
    </div>
  </div>
</div>

<!-- TESTIMONIALS -->
<div class="testis-bg" id="reviews">
<div class="w">
  <div class="r" style="text-align:center">
    <span class="sl">מה אומרים</span>
    <h2 class="sh">בעלי עסקים שכבר עובדים עם מאור</h2>
    <p class="ss" style="margin:0 auto">לא שיווק — חוות דעת אמיתיות</p>
  </div>
  <div class="tgrid">
    <div class="tc r">
      <div class="tc-v">לקוח מאומת</div>
      <div class="tcstars">★★★★★</div>
      <p class="tcq">מאור בנה לי דף נחיתה תוך יומיים ותוך שלושה ימים קיבלתי את הליד הראשון. הוא הקשיב, הבין מה אני צריך, והכל עבד בדיוק כמו שאמר.</p>
      <div class="tcwho">
        <div class="tcav" style="background:linear-gradient(135deg,#1a3a6b,#2563eb)">ד</div>
        <div><div class="tcname">דוד כ.</div><div class="tcrole">חברת שיפוצים, פתח תקוה</div></div>
      </div>
    </div>
    <div class="tc r">
      <div class="tc-v">לקוח מאומת</div>
      <div class="tcstars">★★★★★</div>
      <p class="tcq">ניסיתי כל מיני פרסומות ולא ראיתי תוצאות. עם מאור זה שונה לגמרי. הלידים שמגיעים אלי באמת מחפשים את השירות שלי — לא סתם גוללו.</p>
      <div class="tcwho">
        <div class="tcav" style="background:linear-gradient(135deg,#be185d,#ec4899)">ש</div>
        <div><div class="tcname">שירה מ.</div><div class="tcrole">מאמנת כושר, תל אביב</div></div>
      </div>
    </div>
    <div class="tc r">
      <div class="tc-v">לקוח מאומת</div>
      <div class="tcstars">★★★★★</div>
      <p class="tcq">מה שאהבתי זה שמאור זמין. שאלתי שאלה ב-9 בערב וקיבלתי תשובה. זה לא מה שרגילים לקבל. האתר שבנה לי מביא לקוחות גם בלי פרסום.</p>
      <div class="tcwho">
        <div class="tcav" style="background:linear-gradient(135deg,#065f46,#059669)">י</div>
        <div><div class="tcname">יוסי ר.</div><div class="tcrole">סלון יופי, ראשון לציון</div></div>
      </div>
    </div>
  </div>
  <p class="tnote">* השמות שונו לפרטיות. חוות הדעת אמיתיות מלקוחות שעבדו עם מאור.</p>
</div>
</div>

<!-- FAQ -->
<div class="w r">
  <span class="sl">שאלות נפוצות</span>
  <h2 class="sh">יש לך שאלות? אני כאן</h2>
  <div class="faqs">
    <div class="fq"><div class="fqh">כמה עולה האתר / דף הנחיתה? <span class="farr">▾</span></div><div class="fqb"><p>המחיר תלוי בהיקף הפרויקט. בשיחת ההיכרות החינמית אנחנו מגדירים יחד מה מתאים לך ולתקציב שלך — ללא הפתעות ובלי עלויות נסתרות.</p></div></div>
    <div class="fq"><div class="fqh">כמה זמן לוקח להכין אתר? <span class="farr">▾</span></div><div class="fqb"><p>דף נחיתה — 48-72 שעות. אתר מלא — 5-7 ימי עסקים. לרוב מהיר יותר ממה שאתה מצפה.</p></div></div>
    <div class="fq"><div class="fqh">האם אקבל לידים גם בלי אתר? <span class="farr">▾</span></div><div class="fqb"><p>כן. אפשר להתחיל עם קמפיין לידים בלבד ולהוסיף אתר בהמשך. אבל השילוב ביחד מביא תוצאות הרבה יותר טובות.</p></div></div>
    <div class="fq"><div class="fqh">מה אם הלידים לא רלוונטיים? <span class="farr">▾</span></div><div class="fqb"><p>אני עובד על שיפור מתמיד. אם ליד לא מתאים — אני רוצה לדעת כדי לשפר. ואם תוצאות לא מגיעות — אין תשלום.</p></div></div>
    <div class="fq"><div class="fqh">לאיזה עסקים זה מתאים? <span class="farr">▾</span></div><div class="fqb"><p>שיפוצים, קוסמטיקה, כושר, עריכת דין, נדל"ן, מסעדות, חינוך, רפואה ועוד. כמעט כל עסק שנותן שירות ללקוחות פרטיים.</p></div></div>
  </div>
</div>

<!-- FORM -->
<div class="form-bg" id="contact">
  <div class="form-in">
    <div class="r">
      <span class="sl">בואו נתחיל</span>
      <h2 class="sh">ייעוץ ראשון — חינם לחלוטין</h2>
      <p style="color:rgba(255,255,255,.48);font-size:.92rem;line-height:1.8;margin-top:.5rem">השאר פרטים ואחזור אליך תוך 24 שעות — ללא לחץ, ללא התחייבות.</p>
      <div class="fprom">
        <div class="fp"><div class="fpck">✓</div>שיחת היכרות של 15 דקות — חינם</div>
        <div class="fp"><div class="fpck">✓</div>אני מסביר בדיוק מה מתאים לך</div>
        <div class="fp"><div class="fpck">✓</div>ללא התחייבות לרכישה בכלל</div>
        <div class="fp"><div class="fpck">✓</div>הפרטים שלך נשמרים בסודיות מלאה</div>
      </div>
    </div>
    <div class="r">
      <div class="fcard">
        <div id="fwrap">
          <p style="font-size:.78rem;font-weight:700;color:var(--mid);margin-bottom:.7rem;letter-spacing:.04em;text-transform:uppercase">מה אתה צריך?</p>
          <div class="fsvc">
            <div class="fsvc-t a" onclick="pickSvc(this,'אתר מקצועי')">אתר</div>
            <div class="fsvc-t" onclick="pickSvc(this,'דף נחיתה')">דף נחיתה</div>
            <div class="fsvc-t" onclick="pickSvc(this,'לידים')">לידים</div>
            <div class="fsvc-t" onclick="pickSvc(this,'חבילה מלאה')">חבילה</div>
          </div>
          <input type="hidden" id="f-svc" value="אתר מקצועי">
          <div class="ff"><label for="fn">שם מלא *</label><input type="text" id="fn" placeholder="ישראל ישראלי" required></div>
          <div class="ff"><label for="fp">מספר טלפון *</label><input type="tel" id="fp" placeholder="050-0000000" required></div>
          <div class="ff">
            <label for="fb">איזה עסק יש לך? *</label>
            <select id="fb" required>
              <option value="" disabled selected>בחר סוג עסק</option>
              <option>שיפוצים ובנייה</option><option>קוסמטיקה ויופי</option>
              <option>כושר ואימון אישי</option><option>עריכת דין ורואה חשבון</option>
              <option>נדל"ן ותיווך</option><option>מסעדה ואוכל</option>
              <option>חינוך ופרטי</option><option>רפואה ובריאות</option>
              <option>טכנולוגיה ומחשבים</option><option>עיצוב ואדריכלות</option>
              <option>אחר</option>
            </select>
          </div>
          <div class="ff"><label for="fnt">ספר לי קצת (רשות)</label><textarea id="fnt" placeholder="מה האזור שלך? כמה לקוחות אתה מחפש?"></textarea></div>
          <button type="button" class="fsub" id="fbtn" onclick="sendIt()">
            <div class="spin" id="fspin"></div>
            <span id="fbtn-t">שלח — רוצה להתחיל</span>
          </button>
          <p class="fnote">
            <svg width="11" height="11" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><rect x="3" y="11" width="18" height="11" rx="2"/><path d="M7 11V7a5 5 0 0110 0v4"/></svg>
            הפרטים שלך אצלי בלבד — ללא ספאם, אף פעם
          </p>
        </div>
        <div id="smsg">
          <div class="sico">🎯</div>
          <h3>קיבלתי! תודה רבה</h3>
          <p>אחזור אליך תוך <strong>24 שעות</strong> לשיחה קצרה וחינמית.<br>בינתיים — תמשיך לעשות את מה שאתה עושה הכי טוב.</p>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- FOOTER -->
<footer>
  <div class="flogo">מאור — דיגיטל לעסקים קטנים</div>
  <p>© 2025 — אתרים, דפי נחיתה ולידים שמביאים תוצאות אמיתיות</p>
</footer>

<script src="https://cdn.jsdelivr.net/npm/@emailjs/browser@4/dist/email.min.js"></script>
<script>
emailjs.init("cKWF3k5--EFenLoM6");

// Navbar
window.addEventListener('scroll',()=>document.getElementById('nav').classList.toggle('s',scrollY>40));

// Reveal
new IntersectionObserver((es)=>{
  es.forEach((e,i)=>{if(e.isIntersecting){setTimeout(()=>e.target.classList.add('on'),i*80);e.target._obs?.unobserve(e.target)}})
},{threshold:.07}).observe
;(()=>{
  const ob=new IntersectionObserver((es)=>{es.forEach((e,i)=>{if(e.isIntersecting){setTimeout(()=>e.target.classList.add('on'),i*80);ob.unobserve(e.target)}})},{threshold:.07});
  document.querySelectorAll('.r').forEach(el=>ob.observe(el));
})();

// FAQ
document.querySelectorAll('.fqh').forEach(h=>{
  h.addEventListener('click',()=>{
    const it=h.parentElement,was=it.classList.contains('open');
    document.querySelectorAll('.fq').forEach(f=>f.classList.remove('open'));
    if(!was)it.classList.add('open');
  });
});

// Hero tabs
function switchTab(i){
  document.querySelectorAll('.stab').forEach((t,j)=>t.classList.toggle('active',i===j));
  document.querySelectorAll('.svc-panel').forEach((p,j)=>p.classList.toggle('active',i===j));
}

// Form service picker
function pickSvc(el,val){
  document.querySelectorAll('.fsvc-t').forEach(t=>t.classList.remove('a'));
  el.classList.add('a');
  document.getElementById('f-svc').value=val;
}

// Send
function sendIt(){
  const name=document.getElementById('fn').value.trim();
  const phone=document.getElementById('fp').value.trim();
  const business=document.getElementById('fb').value;
  const notes=document.getElementById('fnt').value.trim();
  const svc=document.getElementById('f-svc').value;
  if(!name||!phone||!business){alert('אנא מלא את כל השדות המסומנים ב-*');return;}
  const btn=document.getElementById('fbtn'),bt=document.getElementById('fbtn-t'),sp=document.getElementById('fspin');
  btn.disabled=true;bt.innerText='שולח...';sp.style.display='block';
  emailjs.send('service_lowtlws','template_u9wpz5c',{name,phone,business,notes:notes||'לא צוין',service:svc})
  .then(()=>{document.getElementById('fwrap').style.display='none';document.getElementById('smsg').style.display='block';})
  .catch(err=>{console.error(err);alert('שגיאה בשליחה, נסה שוב.');btn.disabled=false;bt.innerText='שלח — רוצה להתחיל';sp.style.display='none';});
}
</script>
</body>
</html>
