<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Chased Bank — Banking that keeps up with the chase</title>
<meta name="description" content="Chased Bank: zero-fee everyday accounts, 4.35% APY savings & CDs, instant transfers, transparent loans, cards, FX and full USSD banking. HQ: 256 Chapman Road STE, Orlando, Florida. Led by Robbin Mack Darius. Call +1 (302) 713-0106 · Mon–Fri 9AM–6PM ET.">
<meta name="robots" content="noindex, nofollow">
<meta name="theme-color" content="#F6F9FC">
<link rel="icon" href="data:image/svg+xml,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20viewBox%3D%220%200%2064%2064%22%3E%3Cdefs%3E%3ClinearGradient%20id%3D%22cg%22%20x1%3D%220%22%20y1%3D%220%22%20x2%3D%221%22%20y2%3D%221%22%3E%3Cstop%20offset%3D%220%22%20stop-color%3D%22%231E6FE0%22%2F%3E%3Cstop%20offset%3D%221%22%20stop-color%3D%22%230E7C86%22%2F%3E%3C%2FlinearGradient%3E%3C%2Fdefs%3E%3Ccircle%20cx%3D%2232%22%20cy%3D%2232%22%20r%3D%2230%22%20fill%3D%22%23FFFFFF%22%2F%3E%3Cpath%20d%3D%22M49.5%2015.5%20A24%2024%200%201%200%2049.5%2048.5%22%20fill%3D%22none%22%20stroke%3D%22url%28%23cg%29%22%20stroke-width%3D%227%22%20stroke-linecap%3D%22round%22%2F%3E%3Cpath%20d%3D%22M30%2022l11%2010-11%2010%22%20fill%3D%22none%22%20stroke%3D%22%231E6FE0%22%20stroke-width%3D%226%22%20stroke-linecap%3D%22round%22%20stroke-linejoin%3D%22round%22%2F%3E%3Cpath%20d%3D%22M42%2025l8%207-8%207%22%20fill%3D%22none%22%20stroke%3D%22%230E7C86%22%20stroke-width%3D%225%22%20stroke-linecap%3D%22round%22%20stroke-linejoin%3D%22round%22%2F%3E%3C%2Fsvg%3E">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Unbounded:wght@500;600;700;800&family=Space+Grotesk:wght@400;500;600;700&family=IBM+Plex+Mono:wght@400;500;600&family=Caveat:wght@600&display=swap" rel="stylesheet">
<style>
/* ============ LIGHT TOKENS ============ */
:root{
  --bg0:#F6F9FC; --bg1:#FFFFFF; --bg2:#FFFFFF; --bg3:#E8F0F8;
  --line:rgba(18,60,110,.14); --line2:rgba(18,60,110,.24);
  --ink:#12263A; --mut:#51677D; --dim:#5D7285;
  --blue:#1E6FE0; --blue2:#1554B0; --blueT:#EAF2FD;
  --cyan:#0E7C86; --cyanT:#E4F4F5;
  --gold:#9A6B00; --goldT:#FBF3DF; --goldBright:#F5B93E;
  --success:#0B7A42; --successT:#E7F6EE;
  --danger:#C03030; --dangerT:#FDECEC;
  --warn:#9A6B00; --info:#1554B0;
  --bone:#F4EFE4; --bone2:#E9E1CF; --boneInk:#12241A;
  --acc:var(--blue);
  --nav:74px;
  --r:18px; --r2:26px;
  --disp:'Unbounded','Arial Black',sans-serif;
  --body:'Space Grotesk',system-ui,sans-serif;
  --mono:'IBM Plex Mono',ui-monospace,monospace;
  --shadow:0 24px 60px -24px rgba(21,60,110,.18);
}
@media (max-width:900px){:root{--nav:64px}}

/* ============ BASE ============ */
*{margin:0;padding:0;box-sizing:border-box}
html{scroll-behavior:smooth}
html,body{overflow-x:hidden;overflow-x:clip}
body{background:var(--bg0);color:var(--ink);font-family:var(--body);font-size:16px;line-height:1.6;-webkit-font-smoothing:antialiased}
body.locked{overflow:hidden}
::selection{background:var(--blue);color:#fff}
*{scrollbar-width:thin;scrollbar-color:#B9CCE2 var(--bg0)}
::-webkit-scrollbar{width:11px;height:11px}
::-webkit-scrollbar-track{background:var(--bg0)}
::-webkit-scrollbar-thumb{background:linear-gradient(#7FA8D9,#B9CCE2);border-radius:8px;border:2px solid var(--bg0)}
::-webkit-scrollbar-thumb:hover{background:var(--blue)}
img,svg{display:block;max-width:100%}
a{color:inherit;text-decoration:none}
button{font-family:inherit;cursor:pointer;color:inherit;background:none;border:none}
input,select{font-family:inherit;font-size:1rem;color:var(--ink)}
:focus-visible{outline:2px solid var(--blue);outline-offset:3px;border-radius:6px}
[id]{scroll-margin-top:calc(var(--nav) + 16px)}
.ic{width:1em;height:1em;stroke:currentColor;fill:none;stroke-width:2;stroke-linecap:round;stroke-linejoin:round;display:inline-block;vertical-align:-.13em;flex:none}
.mono{font-family:var(--mono)}
.wrap{width:min(1220px,92vw);margin-inline:auto}
h1,h2,h3{line-height:1.12;letter-spacing:-.01em}
.disp{font-family:var(--disp)}

/* ============ ATMOSPHERE (light blue) ============ */
.atmo{position:fixed;inset:0;z-index:-2;overflow:hidden;pointer-events:none;
  background:
    radial-gradient(1100px 700px at 85% -10%, rgba(30,111,224,.10), transparent 60%),
    radial-gradient(900px 600px at -10% 30%, rgba(14,124,134,.08), transparent 60%),
    linear-gradient(180deg,#FFFFFF 0%, var(--bg0) 40%, #EFF5FB 100%);}
.orb{position:absolute;border-radius:50%;filter:blur(90px);opacity:.6;will-change:transform}
.orb.a{width:560px;height:560px;left:-160px;top:-120px;background:radial-gradient(circle,rgba(30,111,224,.16),transparent 65%);animation:drift1 46s ease-in-out infinite alternate}
.orb.b{width:640px;height:640px;right:-220px;top:16%;background:radial-gradient(circle,rgba(14,124,134,.12),transparent 65%);animation:drift2 58s ease-in-out infinite alternate}
.orb.c{width:520px;height:520px;left:30%;bottom:-260px;background:radial-gradient(circle,rgba(245,185,62,.12),transparent 65%);animation:drift1 64s ease-in-out infinite alternate-reverse}
@keyframes drift1{to{transform:translate(120px,90px) scale(1.15)}}
@keyframes drift2{to{transform:translate(-140px,120px) scale(.9)}}
.gridlines{position:fixed;inset:0;z-index:-1;pointer-events:none;opacity:.5;
  background-image:linear-gradient(rgba(21,84,176,.05) 1px,transparent 1px),linear-gradient(90deg,rgba(21,84,176,.05) 1px,transparent 1px);
  background-size:72px 72px;
  mask-image:radial-gradient(900px 600px at 50% 0%,#000 30%,transparent 80%)}

/* ============ NAV ============ */
#progress{position:fixed;top:0;left:0;height:3px;width:0;z-index:120;background:linear-gradient(90deg,var(--blue),var(--cyan),var(--goldBright));box-shadow:0 0 12px rgba(30,111,224,.4)}
header#siteNav{position:fixed;top:0;left:0;right:0;z-index:110;height:var(--nav);display:flex;align-items:center;transition:.3s;border-bottom:1px solid transparent}
header#siteNav.scrolled{background:rgba(255,255,255,.92);backdrop-filter:blur(16px);-webkit-backdrop-filter:blur(16px);border-color:var(--line);box-shadow:0 12px 40px -18px rgba(21,60,110,.25)}
.nav-in{width:min(1280px,94vw);margin-inline:auto;display:flex;align-items:center;gap:18px}
.brand{display:flex;align-items:center;gap:11px;flex:none}
.brand svg{width:38px;height:38px}
.brand .wordmark{font-family:var(--disp);font-weight:700;font-size:1.06rem;letter-spacing:.06em}
.brand .wordmark em{font-style:normal;color:var(--blue)}
.nav-links{display:flex;gap:2px;margin-left:auto}
.nav-links a{position:relative;padding:9px 11px;border-radius:10px;font-size:.9rem;font-weight:500;color:var(--mut);transition:.2s}
.nav-links a:hover{color:var(--ink);background:var(--blueT)}
.nav-links a.active{color:var(--blue2)}
.nav-links a.active::after{content:"";position:absolute;left:11px;right:11px;bottom:4px;height:2px;border-radius:2px;background:linear-gradient(90deg,var(--blue),var(--cyan))}
.nav-cta{display:flex;align-items:center;gap:10px;flex:none}
#hoursPill{display:inline-flex;align-items:center;gap:7px;padding:7px 12px;border:1px solid var(--line);border-radius:99px;font-family:var(--mono);font-size:.7rem;color:var(--mut);background:#fff}
#hoursPill .dot{width:7px;height:7px;border-radius:50%;background:var(--success);box-shadow:0 0 8px rgba(11,122,66,.5);animation:blink 2.4s infinite}
@keyframes blink{50%{opacity:.4}}
#acctChip{display:none;align-items:center;gap:8px;padding:8px 13px;border:1px solid var(--line2);border-radius:99px;font-family:var(--mono);font-size:.8rem;color:var(--blue2);background:var(--blueT);transition:.2s}
#acctChip:hover{border-color:var(--blue)}
#acctChip.show{display:flex}
#acctChip .dot{width:7px;height:7px;border-radius:50%;background:var(--success);animation:blink 2.4s infinite}
#menuBtn{display:none;width:42px;height:42px;border:1px solid var(--line2);border-radius:11px;align-items:center;justify-content:center;font-size:1.2rem;background:#fff}
.m-panel{display:none}
@media (max-width:1120px){#hoursPill{display:none}}
@media (max-width:940px){
  .nav-links{display:none}
  #menuBtn{display:flex}
  .m-panel{display:block;position:fixed;top:var(--nav);left:0;right:0;z-index:109;background:rgba(255,255,255,.98);backdrop-filter:blur(20px);border-bottom:1px solid var(--line);padding:14px 5vw 24px;transform:translateY(-12px);opacity:0;pointer-events:none;transition:.28s;box-shadow:0 30px 60px -30px rgba(21,60,110,.3)}
  .m-panel.open{transform:none;opacity:1;pointer-events:auto}
  .m-panel a{display:flex;justify-content:space-between;align-items:center;padding:13px 6px;border-bottom:1px solid var(--line);font-weight:600;font-size:1.02rem}
  .m-panel a .ic{color:var(--blue)}
  .m-panel .btn{width:100%;justify-content:center;margin-top:16px}
}

/* ============ BUTTONS / CHIPS ============ */
.btn{display:inline-flex;align-items:center;gap:9px;padding:13px 22px;border-radius:13px;font-weight:700;font-size:.95rem;transition:.18s;border:1px solid transparent;position:relative}
.btn:active{transform:translateY(1px) scale(.99)}
.btn-p{background:linear-gradient(135deg,var(--blue),var(--blue2));color:#fff;box-shadow:0 10px 30px -10px rgba(30,111,224,.5)}
.btn-p:hover{transform:translateY(-2px);box-shadow:0 16px 40px -10px rgba(30,111,224,.6)}
.btn-g{border-color:var(--line2);color:var(--ink);background:#fff}
.btn-g:hover{border-color:var(--blue);background:var(--blueT);transform:translateY(-2px)}
.btn-sm{padding:9px 15px;font-size:.85rem;border-radius:10px}
.btn[disabled]{opacity:.55;cursor:not-allowed;transform:none!important}
.btn.loading{pointer-events:none;color:transparent!important}
.btn.loading::after{content:"";position:absolute;width:18px;height:18px;border:2.5px solid rgba(255,255,255,.4);border-top-color:#fff;border-radius:50%;animation:spin .7s linear infinite;left:calc(50% - 9px);top:calc(50% - 9px)}
@keyframes spin{to{transform:rotate(360deg)}}
.chip{display:inline-flex;align-items:center;gap:7px;padding:7px 13px;border-radius:99px;border:1px solid var(--line);background:#fff;font-size:.82rem;font-weight:600;color:var(--mut)}
.chip .ic{color:var(--acc)}
.pill{display:inline-flex;align-items:center;gap:6px;padding:4px 11px;border-radius:99px;font-size:.74rem;font-weight:700;letter-spacing:.05em;text-transform:uppercase}
.pill.ok{background:var(--successT);color:var(--success);border:1px solid rgba(11,122,66,.3)}
.pill.warn{background:var(--goldT);color:var(--warn);border:1px solid rgba(154,107,0,.3)}
.pill.bad{background:var(--dangerT);color:var(--danger);border:1px solid rgba(192,48,48,.3)}
.pill.info{background:var(--blueT);color:var(--info);border:1px solid rgba(21,84,176,.3)}

/* ============ SECTIONS ============ */
section{position:relative;padding:104px 0}
section::before{content:"";position:absolute;top:-40px;left:50%;transform:translateX(-50%);width:min(900px,90vw);height:340px;background:radial-gradient(closest-side,color-mix(in srgb,var(--acc) 7%,transparent),transparent);pointer-events:none;filter:blur(10px)}
.sec-head{max-width:720px;margin-bottom:52px}
.kicker{display:flex;align-items:center;gap:12px;font-family:var(--mono);font-size:.8rem;letter-spacing:.22em;text-transform:uppercase;color:var(--acc);margin-bottom:18px}
.kicker::after{content:"";height:1px;width:70px;background:linear-gradient(90deg,var(--acc),transparent)}
.sec-head h2{font-family:var(--disp);font-weight:700;font-size:clamp(1.7rem,3.6vw,2.7rem);margin-bottom:16px}
.sec-head h2 em{font-style:normal;color:var(--acc)}
.sec-head p{color:var(--mut);font-size:1.05rem;max-width:60ch}
.panel{background:var(--bg1);border:1px solid var(--line);border-radius:var(--r2);box-shadow:var(--shadow)}
.split{display:grid;grid-template-columns:360px 1fr;gap:56px;align-items:start}
.split .sticky{position:sticky;top:calc(var(--nav) + 28px)}
@media (max-width:1000px){.split{grid-template-columns:1fr;gap:34px}.split .sticky{position:static}}
.reveal{opacity:0;transform:translateY(30px);transition:opacity .8s cubic-bezier(.2,.7,.3,1),transform .8s cubic-bezier(.2,.7,.3,1);transition-delay:var(--d,0s)}
.reveal.in{opacity:1;transform:none}

/* ============ HERO ============ */
.hero{padding:calc(var(--nav) + 66px) 0 40px;min-height:96vh;display:flex;flex-direction:column;justify-content:center}
.hero::before{display:none}
.hero-grid{display:grid;grid-template-columns:1.04fr .96fr;gap:44px;align-items:center}
.hero-copy>*{opacity:0;animation:stage .9s cubic-bezier(.2,.7,.3,1) forwards}
.hero-copy>*:nth-child(1){animation-delay:.1s}.hero-copy>*:nth-child(2){animation-delay:.22s}
.hero-copy>*:nth-child(3){animation-delay:.34s}.hero-copy>*:nth-child(4){animation-delay:.46s}
.hero-copy>*:nth-child(5){animation-delay:.58s}
@keyframes stage{from{opacity:0;transform:translateY(26px)}to{opacity:1;transform:none}}
.hero-eyebrow{display:inline-flex;align-items:center;gap:9px;padding:8px 15px;border-radius:99px;border:1px solid rgba(30,111,224,.3);background:var(--blueT);font-family:var(--mono);font-size:.78rem;letter-spacing:.14em;color:var(--blue2);margin-bottom:26px}
.hero-eyebrow .dot{width:7px;height:7px;border-radius:50%;background:var(--blue);box-shadow:0 0 10px rgba(30,111,224,.6);animation:blink 2s infinite}
.hero h1{font-family:var(--disp);font-weight:800;font-size:clamp(2.3rem,5.4vw,4.15rem);letter-spacing:-.015em;margin-bottom:22px}
.hero h1 .grad{background:linear-gradient(92deg,var(--blue) 10%,var(--cyan) 60%,var(--blue2) 100%);-webkit-background-clip:text;background-clip:text;color:transparent}
.hero-sub{color:var(--mut);font-size:clamp(1rem,1.4vw,1.16rem);max-width:52ch;margin-bottom:32px}
.hero-sub b{color:var(--ink)}
.hero-ctas{display:flex;gap:14px;flex-wrap:wrap;margin-bottom:30px}
.hero-trust{display:flex;gap:10px;flex-wrap:wrap}
.hero-vis{position:relative;perspective:1300px;opacity:0;animation:stage 1s .5s cubic-bezier(.2,.7,.3,1) forwards}
.hv-stack{position:relative;width:min(430px,100%);margin-inline:auto}
.ghost{position:absolute;inset:0;border-radius:22px;border:1px solid var(--line);background:linear-gradient(150deg,#fff,var(--bg3))}
.ghost.g1{transform:rotate(-7deg) translate(-16px,18px);opacity:.7}
.ghost.g2{transform:rotate(5deg) translate(18px,10px);opacity:.9}
.float-chip{position:absolute;z-index:5;display:flex;align-items:center;gap:9px;padding:10px 15px;border-radius:14px;background:rgba(255,255,255,.95);backdrop-filter:blur(8px);border:1px solid var(--line2);font-size:.82rem;font-weight:600;box-shadow:0 16px 40px -14px rgba(21,60,110,.3);animation:bob 5.5s ease-in-out infinite}
.float-chip .ic{font-size:1rem}
.float-chip.fc1{top:-26px;right:-8px;animation-delay:.4s}.float-chip.fc1 .ic{color:var(--success)}
.float-chip.fc2{bottom:52px;left:-34px;animation-delay:1.6s}.float-chip.fc2 .ic{color:var(--gold)}
.float-chip.fc3{bottom:-24px;right:22px;animation-delay:2.7s}.float-chip.fc3 .ic{color:var(--cyan)}
.float-chip small{display:block;color:var(--dim);font-weight:500;font-size:.7rem}
@keyframes bob{50%{transform:translateY(-11px)}}
/* bank cards stay DARK for brand pop */
.bankcard3d{position:relative;aspect-ratio:1.586;border-radius:22px;cursor:pointer;transform-style:preserve-3d;transition:transform .15s linear;will-change:transform}
.bc-inner{position:absolute;inset:0;transform-style:preserve-3d;transition:transform .7s cubic-bezier(.3,.8,.3,1)}
.bankcard3d.flipped .bc-inner{transform:rotateY(180deg)}
.bc-face{position:absolute;inset:0;border-radius:22px;backface-visibility:hidden;-webkit-backface-visibility:hidden;overflow:hidden;border:1px solid rgba(30,111,224,.4);padding:22px 24px;display:flex;flex-direction:column;color:#EAF2FA}
.bc-front{background:radial-gradient(120% 150% at 100% 0%,rgba(30,111,224,.35),transparent 50%),radial-gradient(100% 120% at 0% 100%,rgba(14,124,134,.2),transparent 55%),linear-gradient(140deg,#12365E 0%,#0B1B2E 55%,#071120 100%);box-shadow:0 30px 70px -22px rgba(11,27,46,.55),inset 0 1px 0 rgba(255,255,255,.12)}
.bc-front::after{content:"";position:absolute;inset:0;background:repeating-radial-gradient(circle at 115% -20%,transparent 0 26px,rgba(124,192,255,.06) 26px 27px);pointer-events:none}
.bc-back{background:linear-gradient(140deg,#123055,#071120);transform:rotateY(180deg);box-shadow:0 30px 70px -22px rgba(11,27,46,.55)}
.bc-top{display:flex;justify-content:space-between;align-items:flex-start}
.bc-brand{display:flex;align-items:center;gap:8px;font-family:var(--disp);font-weight:700;font-size:.92rem;letter-spacing:.1em}
.bc-brand em{font-style:normal;color:#7CC0FF}
.bc-brand .cmark{width:24px;height:24px;color:#7CC0FF}
.cd-credit .bc-brand .cmark,.cd-credit .bc-brand em{color:var(--goldBright)}
.cd-go .bc-brand .cmark,.cd-go .bc-brand em{color:#7CD6C6}
.bc-type{font-family:var(--mono);font-size:.68rem;letter-spacing:.24em;color:#9FB4CC;text-transform:uppercase}
.bc-mid{display:flex;align-items:center;gap:14px;margin-top:16px}
.bc-bal-label{font-size:.7rem;letter-spacing:.16em;text-transform:uppercase;color:#9FB4CC}
.bc-bal{font-family:var(--mono);font-weight:600;font-size:clamp(1.3rem,2.4vw,1.7rem);color:#7CC0FF;text-shadow:0 0 24px rgba(124,192,255,.35)}
.bc-num{font-family:var(--mono);font-size:clamp(.92rem,1.7vw,1.12rem);letter-spacing:.14em;margin-top:auto;color:#D7E4F2}
.bc-bottom{display:flex;justify-content:space-between;align-items:flex-end;margin-top:12px}
.bc-holder{font-size:.8rem;letter-spacing:.12em;font-weight:600}
.bc-holder small{display:block;font-size:.62rem;color:#7E93AB;letter-spacing:.2em;font-weight:500}
.bc-net{font-family:var(--disp);font-size:.72rem;color:#9FB4CC;letter-spacing:.08em}
.bc-stripe{height:40px;background:#04090F;margin:14px -24px 16px}
.bc-cvv{background:var(--bone);color:#111;border-radius:6px;padding:7px 12px;font-family:var(--mono);font-size:.82rem;display:flex;justify-content:space-between;width:70%}
.bc-back p{font-size:.68rem;color:#7E93AB;margin-top:auto;line-height:1.5}
.bc-limit-line{font-family:var(--mono);font-size:.74rem;color:#9FB4CC;margin-top:12px}
.frost{position:absolute;inset:0;border-radius:22px;z-index:6;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:8px;background:rgba(140,190,220,.2);backdrop-filter:blur(5px) saturate(.4);border:1px solid rgba(160,220,255,.5);color:#CFEFFF;font-family:var(--disp);font-size:.85rem;letter-spacing:.28em;opacity:0;pointer-events:none;transition:.35s}
.frost .ic{font-size:1.7rem;color:#9FDcff}
.bankcard3d.frozen .frost{opacity:1}
.flip-hint{text-align:center;font-size:.74rem;color:var(--dim);margin-top:14px;font-family:var(--mono);letter-spacing:.1em}
.ticker{margin-top:64px;border-block:1px solid var(--line);background:#EEF4FA;overflow:hidden;position:relative}
.ticker::before,.ticker::after{content:"";position:absolute;top:0;bottom:0;width:90px;z-index:2;pointer-events:none}
.ticker::before{left:0;background:linear-gradient(90deg,var(--bg0),transparent)}
.ticker::after{right:0;background:linear-gradient(-90deg,var(--bg0),transparent)}
.ticker-track{display:flex;width:max-content;animation:tick 36s linear infinite;padding:13px 0}
.ticker:hover .ticker-track{animation-play-state:paused}
@keyframes tick{to{transform:translateX(-50%)}}
.tk{display:flex;align-items:center;gap:9px;padding:0 26px;font-family:var(--mono);font-size:.83rem;color:var(--mut);white-space:nowrap}
.tk b{color:var(--ink);font-weight:600}
.tk .up{color:var(--success)}.tk .dn{color:var(--danger)}
.tk .sep{color:var(--blue);font-size:.6rem}
@media (max-width:940px){
  .hero{min-height:auto;padding-top:calc(var(--nav) + 44px)}
  .hero-grid{grid-template-columns:1fr;gap:70px}
  .float-chip.fc2{left:-6px}.float-chip.fc1{right:-4px}
}

/* ============ STATS ============ */
.stats{padding:66px 0 30px}
.stats::before{display:none}
.stats-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:16px}
.stat{padding:26px 24px;border:1px solid var(--line);border-radius:var(--r);background:#fff;position:relative;overflow:hidden;box-shadow:var(--shadow)}
.stat::after{content:"";position:absolute;top:0;left:24px;right:24px;height:2px;background:linear-gradient(90deg,var(--sc,var(--blue)),transparent)}
.stat .num{font-family:var(--disp);font-weight:700;font-size:clamp(1.5rem,2.6vw,2.15rem);color:var(--sc,var(--blue))}
.stat .lbl{color:var(--mut);font-size:.88rem;margin-top:6px}
@media (max-width:820px){.stats-grid{grid-template-columns:repeat(2,1fr)}}

/* ============ ACCOUNTS ============ */
#accounts{--acc:var(--blue)}
.acct-tabs{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:22px}
.acct-tab{padding:11px 18px;border-radius:12px;border:1px solid var(--line);font-weight:600;font-size:.9rem;color:var(--mut);transition:.2s;display:flex;gap:8px;align-items:center;background:#fff}
.acct-tab:hover{border-color:var(--line2);color:var(--ink)}
.acct-tab[aria-selected="true"]{background:var(--blueT);border-color:rgba(30,111,224,.5);color:var(--blue2)}
.acct-panel{padding:32px;display:grid;grid-template-columns:1.1fr .9fr;gap:30px}
.acct-panel h3{font-family:var(--disp);font-size:1.35rem;margin-bottom:6px}
.acct-panel .tag{color:var(--mut);font-size:.94rem;margin-bottom:20px}
.feat-list{list-style:none;display:grid;gap:11px}
.feat-list li{display:flex;gap:11px;align-items:flex-start;font-size:.93rem;color:#33475C}
.feat-list .ic{color:var(--blue);margin-top:4px}
.acct-meta{display:grid;gap:12px;align-content:start}
.meta-box{border:1px solid var(--line);border-radius:14px;padding:15px 17px;background:var(--bg0)}
.meta-box .k{font-size:.72rem;letter-spacing:.16em;text-transform:uppercase;color:var(--dim)}
.meta-box .v{font-family:var(--mono);font-weight:600;font-size:1.15rem;color:var(--blue2);margin-top:3px}
.meta-box .v.gold{color:var(--gold)}
.meta-box small{color:var(--dim);font-size:.74rem}
@media (max-width:760px){.acct-panel{grid-template-columns:1fr;padding:24px}}
.calc{margin-top:26px;padding:30px 32px}
.calc-head{display:flex;justify-content:space-between;align-items:center;gap:14px;flex-wrap:wrap;margin-bottom:22px}
.calc-head h4{font-family:var(--disp);font-size:1.05rem}
.calc-grid{display:grid;grid-template-columns:1.05fr .95fr;gap:34px}
@media (max-width:860px){.calc-grid{grid-template-columns:1fr}}
.field label{display:block;font-size:.8rem;font-weight:600;letter-spacing:.08em;text-transform:uppercase;color:var(--mut);margin-bottom:9px}
.range-row{display:flex;align-items:center;gap:16px}
input[type=range]{-webkit-appearance:none;appearance:none;flex:1;height:6px;border-radius:6px;background:linear-gradient(90deg,var(--blue) var(--fill,30%),var(--bg3) var(--fill,30%));outline-offset:6px}
input[type=range]::-webkit-slider-thumb{-webkit-appearance:none;width:22px;height:22px;border-radius:50%;background:var(--blue);border:4px solid #fff;box-shadow:0 0 0 2px var(--blue),0 4px 14px rgba(30,111,224,.4);cursor:grab;transition:transform .15s}
input[type=range]::-webkit-slider-thumb:hover{transform:scale(1.15)}
input[type=range]::-moz-range-thumb{width:16px;height:16px;border-radius:50%;background:var(--blue);border:3px solid #fff;box-shadow:0 0 0 2px var(--blue);cursor:grab}
.range-out{font-family:var(--mono);font-weight:600;font-size:1rem;color:var(--blue2);min-width:96px;text-align:right}
.num-in{width:100%;background:#fff;border:1px solid var(--line2);border-radius:12px;padding:12px 15px;font-family:var(--mono);transition:.2s}
.num-in:focus{border-color:var(--blue);outline:none;box-shadow:0 0 0 3px rgba(30,111,224,.15)}
.tenor-chips{display:flex;gap:8px;flex-wrap:wrap}
.tchip{padding:9px 16px;border-radius:10px;border:1px solid var(--line);font-family:var(--mono);font-size:.84rem;color:var(--mut);transition:.2s;background:#fff}
.tchip:hover{color:var(--ink);border-color:var(--line2)}
.tchip.on{background:var(--blueT);border-color:rgba(30,111,224,.55);color:var(--blue2);font-weight:600}
.calc-out{border:1px solid rgba(30,111,224,.3);border-radius:18px;padding:22px;background:linear-gradient(160deg,var(--blueT),#fff)}
.co-row{display:flex;justify-content:space-between;align-items:baseline;padding:7px 0;font-size:.92rem;color:var(--mut)}
.co-row b{font-family:var(--mono);font-size:1.05rem;color:var(--ink);font-weight:600}
.co-row.big{border-top:1px dashed var(--line2);margin-top:8px;padding-top:14px}
.co-row.big b{font-size:1.5rem;color:var(--blue2)}
.bars{display:flex;align-items:flex-end;gap:7px;height:86px;margin-top:18px}
.bars .bar{flex:1;border-radius:6px 6px 3px 3px;background:linear-gradient(180deg,var(--blue),#9CC0EE);min-height:8%;transition:height .6s cubic-bezier(.2,.7,.3,1)}
.bars .bar:hover{background:linear-gradient(180deg,var(--cyan),#9CC0EE)}
.calc-note{font-size:.76rem;color:var(--dim);margin-top:14px}

/* ============ PAYMENTS ============ */
#payments{--acc:var(--cyan)}
.rail-list{display:grid;gap:12px;margin-top:26px}
.rail{display:flex;gap:15px;padding:17px 18px;border:1px solid var(--line);border-radius:15px;background:#fff;transition:.2s}
.rail:hover{border-color:rgba(14,124,134,.45);transform:translateX(5px)}
.rail .ic{font-size:1.3rem;color:var(--cyan);margin-top:3px}
.rail b{display:block;font-size:.95rem}
.rail span{font-size:.83rem;color:var(--mut)}
.tw{padding:30px}
.tw h4{font-family:var(--disp);font-size:1.1rem;display:flex;align-items:center;gap:10px}
.tw h4 .ic{color:var(--cyan)}
.tw-sub{color:var(--mut);font-size:.86rem;margin:6px 0 22px}
.tw-grid{display:grid;grid-template-columns:1fr 1fr;gap:16px}
.tw-grid .full{grid-column:1/-1}
@media (max-width:560px){.tw-grid{grid-template-columns:1fr}}
select.num-in{appearance:none;background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='14' height='14' viewBox='0 0 24 24' fill='none' stroke='%2351677D' stroke-width='2.4'%3E%3Cpath d='M6 9l6 6 6-6'/%3E%3C/svg%3E");background-repeat:no-repeat;background-position:right 14px center;padding-right:40px}
.quick-amts{display:flex;gap:8px;margin-top:9px}
.qa{padding:6px 12px;border-radius:8px;border:1px solid var(--line);font-family:var(--mono);font-size:.76rem;color:var(--mut);transition:.15s;background:#fff}
.qa:hover{border-color:var(--cyan);color:var(--cyan)}
.name-chip{display:none;align-items:center;gap:8px;margin-top:9px;font-size:.83rem;font-weight:600;color:var(--success)}
.name-chip.show{display:flex}
.name-chip.resolving{color:var(--dim)}
.name-chip.resolving .ic{animation:spin 1s linear infinite}
.fee-line{display:flex;justify-content:space-between;font-size:.85rem;color:var(--mut);padding:13px 2px;border-top:1px dashed var(--line);margin-top:18px}
.fee-line b{color:var(--success);font-family:var(--mono)}
.invalid{border-color:var(--danger)!important;animation:shake .35s}
@keyframes shake{25%{transform:translateX(-5px)}75%{transform:translateX(5px)}}
.tw-steps{list-style:none;margin:20px 0 4px;display:none}
.tw-steps.show{display:grid}
.tw-steps li{display:flex;gap:13px;align-items:flex-start;padding:9px 0;color:var(--dim);font-size:.9rem;position:relative}
.tw-steps li::before{content:"";width:15px;height:15px;border-radius:50%;border:2px solid var(--line2);margin-top:4px;flex:none;transition:.3s}
.tw-steps li:not(:last-child)::after{content:"";position:absolute;left:7px;top:30px;bottom:-6px;width:2px;background:var(--line)}
.tw-steps li.done{color:var(--ink)}
.tw-steps li.done::before{background:var(--success);border-color:var(--success)}
.tw-steps li.doing{color:var(--cyan)}
.tw-steps li.doing::before{border-color:var(--cyan);animation:blink 1s infinite}
.receipt{display:none;margin-top:20px;border:1px solid rgba(11,122,66,.35);border-radius:16px;padding:22px;background:linear-gradient(160deg,var(--successT),#fff);position:relative;overflow:hidden}
.receipt.show{display:block;animation:stage .5s}
.receipt::before{content:"";position:absolute;top:0;left:0;right:0;height:3px;background:linear-gradient(90deg,var(--success),var(--cyan))}
.rc-ok{display:flex;align-items:center;gap:10px;color:var(--success);font-weight:700;margin-bottom:14px}
.rc-ok .ic{font-size:1.3rem}
.rc-row{display:flex;justify-content:space-between;font-size:.87rem;padding:5px 0;color:var(--mut)}
.rc-row b{color:var(--ink);font-family:var(--mono);font-weight:500;text-align:right}
.rc-actions{display:flex;gap:10px;margin-top:16px;flex-wrap:wrap}
.hist{margin-top:26px}
.hist h5{font-size:.78rem;letter-spacing:.18em;text-transform:uppercase;color:var(--dim);margin-bottom:12px}
.hist-list{list-style:none;display:grid;gap:9px}
.hist-list li{display:flex;align-items:center;gap:13px;padding:12px 15px;border:1px solid var(--line);border-radius:12px;background:#fff;font-size:.88rem;animation:stage .45s}
.hist-list .avatar{width:34px;height:34px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-weight:700;font-size:.78rem;background:var(--blueT);color:var(--blue2);flex:none}
.hist-list .who b{display:block;font-size:.88rem}
.hist-list .who small{color:var(--dim);font-size:.74rem}
.hist-list .amt{margin-left:auto;font-family:var(--mono);font-weight:600}

/* ============ LOANS ============ */
#loans{--acc:var(--gold)}
#loans input[type=range]{background:linear-gradient(90deg,var(--goldBright) var(--fill,30%),var(--bg3) var(--fill,30%))}
#loans input[type=range]::-webkit-slider-thumb{background:var(--goldBright);box-shadow:0 0 0 2px var(--gold),0 4px 14px rgba(245,185,62,.5)}
#loans input[type=range]::-moz-range-thumb{background:var(--goldBright);box-shadow:0 0 0 2px var(--gold)}
#loans .range-out,#loans .co-row.big b{color:var(--gold)}
#loans .calc-out{border-color:rgba(154,107,0,.3);background:linear-gradient(160deg,var(--goldT),#fff)}
.stepper{display:flex;align-items:center;gap:12px}
.stepper button{width:38px;height:38px;border-radius:11px;border:1px solid var(--line2);display:flex;align-items:center;justify-content:center;font-size:1rem;transition:.15s;color:var(--gold);background:#fff}
.stepper button:hover{border-color:var(--gold);background:var(--goldT)}
.stepper .val{font-family:var(--mono);font-weight:600;font-size:1.05rem;min-width:88px;text-align:center}
.donut-wrap{display:flex;align-items:center;gap:20px;margin-top:16px}
.donut{width:120px;height:120px;flex:none}
.donut circle{fill:none;stroke-width:15;stroke-linecap:round}
.donut .base{stroke:var(--bg3)}
.donut .int{stroke:url(#goldGrad);transition:stroke-dasharray .6s}
.donut text{fill:var(--ink);font-family:var(--mono);font-size:15px;font-weight:600}
.legend{display:grid;gap:8px;font-size:.83rem;color:var(--mut)}
.legend i{display:inline-block;width:10px;height:10px;border-radius:3px;margin-right:8px}
.loan-cards{display:grid;gap:14px;margin-top:26px}
.loan-card{padding:22px;border:1px solid var(--line);border-radius:16px;background:#fff;transition:.2s}
.loan-card:hover{border-color:rgba(154,107,0,.45);transform:translateY(-3px)}
.loan-card .lc-top{display:flex;justify-content:space-between;align-items:center;gap:10px;margin-bottom:8px}
.loan-card b{font-family:var(--disp);font-size:.98rem}
.loan-card p{font-size:.86rem;color:var(--mut)}
.loan-card .req{font-size:.76rem;color:var(--dim);margin-top:10px;font-family:var(--mono)}
.elig{margin-top:26px;padding:24px;border:1px dashed rgba(154,107,0,.4);border-radius:16px;background:var(--goldT)}
.elig h5{font-family:var(--disp);font-size:.95rem;margin-bottom:16px;display:flex;gap:9px;align-items:center}
.elig h5 .ic{color:var(--gold)}
.switch{position:relative;display:inline-flex;align-items:center;gap:11px;cursor:pointer;font-size:.88rem;color:var(--mut);user-select:none}
.switch input{position:absolute;opacity:0;width:0}
.switch .tr{width:44px;height:24px;border-radius:99px;background:var(--bg3);border:1px solid var(--line2);position:relative;transition:.25s;flex:none}
.switch .tr::after{content:"";position:absolute;top:2px;left:2px;width:18px;height:18px;border-radius:50%;background:#fff;border:1px solid var(--line2);transition:.25s}
.switch input:checked + .tr{background:rgba(30,111,224,.25);border-color:var(--blue)}
.switch input:checked + .tr::after{left:22px;background:var(--blue);border-color:var(--blue)}
.switch input:focus-visible + .tr{outline:2px solid var(--blue);outline-offset:3px}
.elig-out{margin-top:16px;display:flex;align-items:center;gap:12px;flex-wrap:wrap}
.elig-out .amt{font-family:var(--mono);font-weight:600;font-size:1.3rem;color:var(--gold)}

/* ============ CARDS ============ */
#cards{--acc:var(--gold)}
.cards-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:26px}
@media (max-width:1020px){.cards-grid{grid-template-columns:1fr;max-width:480px;margin-inline:auto}}
.card-item .bankcard3d{width:100%}
.card-item .bc-face{padding:19px 21px}
.cd-credit .bc-front{background:radial-gradient(120% 150% at 100% 0%,rgba(245,185,62,.26),transparent 50%),radial-gradient(100% 120% at 0% 100%,rgba(255,107,94,.12),transparent 55%),linear-gradient(140deg,#3D2E0E 0%,#221A08 55%,#120E05 100%);border-color:rgba(245,185,62,.45)}
.cd-credit .bc-front::after{background:repeating-radial-gradient(circle at 115% -20%,transparent 0 26px,rgba(245,185,62,.06) 26px 27px)}
.cd-credit .bc-bal{color:var(--goldBright);text-shadow:0 0 24px rgba(245,185,62,.35)}
.cd-go .bc-front{background:radial-gradient(120% 150% at 100% 0%,rgba(58,214,198,.26),transparent 50%),radial-gradient(100% 120% at 0% 100%,rgba(30,111,224,.16),transparent 55%),linear-gradient(140deg,#0E3A3F 0%,#0A2226 55%,#051214 100%);border-color:rgba(58,214,198,.45)}
.cd-go .bc-front::after{background:repeating-radial-gradient(circle at 115% -20%,transparent 0 26px,rgba(58,214,198,.07) 26px 27px)}
.cd-go .bc-bal{color:#7CD6C6;text-shadow:0 0 24px rgba(58,214,198,.35)}
.card-info{margin-top:18px}
.card-info .ci-top{display:flex;justify-content:space-between;align-items:center;gap:10px}
.card-info h3{font-family:var(--disp);font-size:1.02rem}
.card-info p{font-size:.85rem;color:var(--mut);margin-top:6px;min-height:42px}
.card-controls{margin-top:16px;display:grid;gap:14px;border-top:1px solid var(--line);padding-top:16px}
.cc-row{display:flex;justify-content:space-between;align-items:center;gap:12px;font-size:.84rem;color:var(--mut)}
.cc-limit{display:grid;gap:8px}
.cc-limit .lbl{display:flex;justify-content:space-between;font-size:.78rem;color:var(--mut)}
.cc-limit .lbl output{font-family:var(--mono);color:var(--ink);font-weight:600}
.cc-limit input[type=range]{height:5px}
.cd-credit .cc-limit input[type=range]{background:linear-gradient(90deg,var(--goldBright) var(--fill,30%),var(--bg3) var(--fill,30%))}
.cd-go .cc-limit input[type=range]{background:linear-gradient(90deg,var(--cyan) var(--fill,30%),var(--bg3) var(--fill,30%))}

/* ============ FX ============ */
#fx{--acc:var(--cyan)}
.fx-grid{display:grid;grid-template-columns:1.05fr .95fr;gap:26px;align-items:start}
@media (max-width:980px){.fx-grid{grid-template-columns:1fr}}
.fx-board{padding:26px}
.fx-board h4,.fx-conv h4{font-family:var(--disp);font-size:1.02rem;display:flex;align-items:center;gap:10px;margin-bottom:4px}
.fx-board h4 .ic{color:var(--cyan)}
.fx-live{display:inline-flex;align-items:center;gap:7px;font-family:var(--mono);font-size:.7rem;color:var(--success);letter-spacing:.14em}
.fx-live .dot{width:6px;height:6px;border-radius:50%;background:var(--success);animation:blink 1.6s infinite}
table.fx{width:100%;border-collapse:collapse;margin-top:16px}
table.fx th{font-size:.68rem;letter-spacing:.18em;text-transform:uppercase;color:var(--dim);text-align:right;padding:8px 10px;border-bottom:1px solid var(--line)}
table.fx th:first-child{text-align:left}
table.fx td{padding:13px 10px;border-bottom:1px solid var(--line);font-family:var(--mono);font-size:.9rem;text-align:right;transition:background .4s}
table.fx td:first-child{text-align:left;font-family:var(--body);font-weight:700;font-size:.95rem}
table.fx tr.flash-up td{background:rgba(11,122,66,.07)}
table.fx tr.flash-dn td{background:rgba(192,48,48,.07)}
table.fx .cur{display:flex;align-items:center;gap:9px}
table.fx .trend{font-size:.72rem;margin-left:6px}
.trend.up{color:var(--success)}.trend.dn{color:var(--danger)}
.spark{width:86px;height:26px;margin-left:auto}
.fx-note{font-size:.74rem;color:var(--dim);margin-top:12px}
.fx-conv{padding:26px}
.conv-row{display:grid;grid-template-columns:1fr auto 1fr;gap:12px;align-items:end;margin-top:18px}
#fxSwap{width:44px;height:44px;border-radius:50%;border:1px solid var(--line2);display:flex;align-items:center;justify-content:center;color:var(--cyan);transition:.3s;margin-bottom:1px;background:#fff}
#fxSwap:hover{border-color:var(--cyan);background:var(--cyanT)}
#fxSwap.spin{transform:rotate(180deg)}
.conv-out{margin-top:20px;border:1px solid rgba(14,124,134,.3);border-radius:16px;padding:20px;background:linear-gradient(160deg,var(--cyanT),#fff)}
.conv-out .big{font-family:var(--mono);font-weight:600;font-size:clamp(1.5rem,3vw,2rem);color:var(--cyan)}
.conv-out .rate{font-size:.8rem;color:var(--mut);margin-top:6px;font-family:var(--mono)}
.corridors{display:grid;grid-template-columns:repeat(3,1fr);gap:14px;margin-top:26px}
@media (max-width:760px){.corridors{grid-template-columns:1fr}}
.corr{padding:18px;border:1px solid var(--line);border-radius:15px;background:#fff;transition:.2s}
.corr:hover{border-color:rgba(14,124,134,.45);transform:translateY(-3px)}
.corr .flags{font-size:1.3rem;letter-spacing:.1em}
.corr b{display:block;margin-top:9px;font-size:.92rem}
.corr span{font-size:.78rem;color:var(--mut)}
.corr .pill{margin-top:10px}

/* ============ DIGITAL ============ */
#digital{--acc:var(--blue)}
.dev-grid{display:grid;grid-template-columns:auto 1fr auto;gap:36px;align-items:start;justify-content:center}
@media (max-width:1120px){.dev-grid{grid-template-columns:1fr 1fr}.dev-web{grid-column:1/-1;order:3}}
@media (max-width:760px){.dev-grid{grid-template-columns:1fr;justify-items:center}.dev-web{order:0}}
.dev-cap{text-align:center;font-family:var(--mono);font-size:.74rem;letter-spacing:.2em;text-transform:uppercase;color:var(--dim);margin-top:16px}
.dev-cap b{color:var(--blue2)}
.phone{width:min(296px,88vw);border-radius:42px;border:9px solid #16283C;background:#0B1B2E;box-shadow:0 40px 90px -30px rgba(11,27,46,.5),inset 0 0 0 1px var(--line2);overflow:hidden;position:relative}
.phone .notch{position:absolute;top:9px;left:50%;transform:translateX(-50%);width:96px;height:21px;border-radius:99px;background:#16283C;z-index:5}
.p-screen{height:560px;display:flex;flex-direction:column;background:linear-gradient(175deg,#0E2440,#081527);color:#EAF2FA}
.p-status{display:flex;justify-content:space-between;padding:12px 20px 4px;font-family:var(--mono);font-size:.62rem;color:#7E93AB}
.p-body{flex:1;overflow-y:auto;padding:16px 17px 12px}
.p-body::-webkit-scrollbar{width:5px}
.p-body::-webkit-scrollbar-thumb{background:#28496E;border:none}
.p-head{display:flex;justify-content:space-between;align-items:center;margin-bottom:15px}
.p-head .hi{font-size:.76rem;color:#9FB4CC}
.p-head .hi b{display:block;font-size:.95rem;color:#EAF2FA}
.p-ava{width:34px;height:34px;border-radius:50%;background:linear-gradient(135deg,#7CC0FF,#3AD6C6);display:flex;align-items:center;justify-content:center;color:#0B1B2E;font-weight:700;font-size:.75rem;overflow:hidden}
.p-ava svg{width:22px;height:22px}
.p-bal-card{border-radius:18px;padding:17px;background:linear-gradient(140deg,#12365E,#0B2038);border:1px solid rgba(124,192,255,.35);position:relative;overflow:hidden}
.p-bal-card::after{content:"";position:absolute;right:-30px;top:-30px;width:110px;height:110px;border-radius:50%;background:radial-gradient(circle,rgba(124,192,255,.2),transparent 70%)}
.p-bal-card .k{font-size:.64rem;letter-spacing:.18em;color:#9FB4CC;text-transform:uppercase}
.p-bal-card .v{font-family:var(--mono);font-weight:600;font-size:1.42rem;color:#7CC0FF;margin:4px 0 12px}
.p-bal-card .row{display:flex;gap:8px}
.p-mini{flex:1;padding:8px 6px;border-radius:10px;background:rgba(124,192,255,.14);border:1px solid rgba(124,192,255,.35);font-size:.7rem;font-weight:700;color:#7CC0FF;display:flex;align-items:center;justify-content:center;gap:5px;transition:.15s}
.p-mini:hover{background:rgba(124,192,255,.24)}
.p-sec{font-size:.66rem;letter-spacing:.18em;text-transform:uppercase;color:#7E93AB;margin:16px 0 9px}
.p-tx{list-style:none;display:grid;gap:8px}
.p-tx li{display:flex;align-items:center;gap:10px;padding:9px 11px;border-radius:12px;background:rgba(124,192,255,.06);border:1px solid rgba(124,192,255,.14);font-size:.76rem;animation:stage .4s}
.p-tx .tic{width:27px;height:27px;border-radius:9px;display:flex;align-items:center;justify-content:center;font-size:.8rem;flex:none}
.p-tx .tic.in{background:rgba(87,227,137,.16);color:#57E389}
.p-tx .tic.out{background:rgba(245,185,62,.15);color:#F5B93E}
.p-tx .tl b{display:block;font-size:.76rem;font-weight:600}
.p-tx .tl small{color:#7E93AB;font-size:.62rem}
.p-tx .ta{margin-left:auto;font-family:var(--mono);font-size:.72rem;font-weight:600}
.p-tx .ta.pos{color:#57E389}
.p-tabs{display:flex;border-top:1px solid rgba(124,192,255,.15);background:rgba(8,21,39,.9)}
.p-tabs button{flex:1;padding:11px 4px 13px;display:flex;flex-direction:column;align-items:center;gap:4px;font-size:.6rem;letter-spacing:.08em;color:#7E93AB;transition:.2s}
.p-tabs button .ic{font-size:1.1rem}
.p-tabs button.on{color:#7CC0FF}
.p-form{display:grid;gap:11px}
.p-form .num-in{padding:10px 13px;font-size:.85rem;border-radius:11px;background:#0B2038;border-color:rgba(124,192,255,.3);color:#EAF2FA}
.p-cardrow{display:flex;align-items:center;gap:10px;padding:11px;border:1px solid rgba(124,192,255,.15);border-radius:13px;margin-bottom:9px;background:rgba(124,192,255,.05)}
.p-cardrow .swatch{width:36px;height:24px;border-radius:5px;flex:none}
.p-cardrow b{font-size:.76rem;display:block}
.p-cardrow small{font-size:.62rem;color:#7E93AB;font-family:var(--mono)}
.p-cardrow button{margin-left:auto;font-size:.64rem;font-weight:700;padding:6px 10px;border-radius:8px;border:1px solid rgba(124,192,255,.3);color:#9FB4CC;transition:.15s}
.p-cardrow button:hover{color:#EAF2FA;border-color:#7CC0FF}
.pulse{animation:pulseBal .6s}
@keyframes pulseBal{30%{transform:scale(1.04);filter:brightness(1.4)}}
.dev-web{max-width:420px}
.browser{border-radius:18px;border:1px solid var(--line2);overflow:hidden;background:#fff;box-shadow:var(--shadow)}
.b-bar{display:flex;align-items:center;gap:8px;padding:11px 15px;background:var(--bg0);border-bottom:1px solid var(--line)}
.b-dots{display:flex;gap:5px}
.b-dots i{width:9px;height:9px;border-radius:50%}
.b-dots i:nth-child(1){background:#FF6B5E}.b-dots i:nth-child(2){background:#F5B93E}.b-dots i:nth-child(3){background:#57E389}
.b-url{flex:1;font-family:var(--mono);font-size:.7rem;color:var(--mut);background:#fff;border:1px solid var(--line);border-radius:8px;padding:5px 11px;display:flex;align-items:center;gap:7px}
.b-url .ic{color:var(--success);font-size:.8rem}
.b-url .cmark{width:14px;height:14px;color:var(--blue)}
.b-body{padding:20px}
.b-body .k{font-size:.66rem;letter-spacing:.18em;text-transform:uppercase;color:var(--dim)}
.b-body .v{font-family:var(--mono);font-weight:600;font-size:1.55rem;color:var(--blue2);margin:4px 0 14px}
.b-actions{display:flex;gap:9px;flex-wrap:wrap}
.web-feats{list-style:none;margin-top:22px;display:grid;gap:11px}
.web-feats li{display:flex;gap:11px;font-size:.88rem;color:var(--mut);align-items:flex-start}
.web-feats .ic{color:var(--blue);margin-top:4px}
/* feature phone LCD stays dark green */
.fphone{width:min(262px,84vw);border-radius:30px;border:8px solid #1B2C3E;background:linear-gradient(170deg,#243B52,#152638);box-shadow:0 40px 90px -30px rgba(11,27,46,.5),inset 0 0 0 1px var(--line);padding:14px 13px 16px}
.fp-screen{height:222px;border-radius:12px;background:#04120B;border:1px solid rgba(182,240,74,.4);padding:12px;font-family:var(--mono);font-size:.74rem;line-height:1.55;color:#B6F04A;overflow-y:auto;text-shadow:0 0 8px rgba(182,240,74,.35)}
.fp-screen::-webkit-scrollbar{width:4px}
.fp-screen::-webkit-scrollbar-thumb{background:#2C4A12;border:none}
.fp-screen .ul{white-space:pre-wrap}
.fp-screen .ul.dim{color:#5E8A4A;text-shadow:none}
.fp-screen .ul.head{color:#D9FF7A;font-weight:600;border-bottom:1px dashed rgba(182,240,74,.3);padding-bottom:4px;margin-bottom:6px}
.fp-screen .cursor{display:inline-block;width:7px;height:12px;background:#B6F04A;animation:blink 1s steps(1) infinite;vertical-align:-2px}
.fp-dial{width:100%;margin-top:11px;padding:9px;border-radius:10px;background:rgba(182,240,74,.15);border:1px solid rgba(182,240,74,.45);color:#B6F04A;font-family:var(--mono);font-size:.78rem;font-weight:600;transition:.15s}
.fp-dial:hover{background:rgba(182,240,74,.25)}
.fp-keys{display:grid;grid-template-columns:repeat(3,1fr);gap:7px;margin-top:11px}
.fp-key{padding:9px 4px;border-radius:10px;background:linear-gradient(170deg,#2E4A66,#1B3048);border:1px solid rgba(124,192,255,.2);font-family:var(--mono);font-weight:600;font-size:.92rem;color:#D7E4F2;transition:.12s;line-height:1.1}
.fp-key small{display:block;font-size:.5rem;color:#7E93AB;letter-spacing:.14em}
.fp-key:hover{border-color:rgba(124,192,255,.55);color:#7CC0FF}
.fp-key:active{transform:scale(.94);background:#12365E}
.fp-key.send{background:linear-gradient(170deg,rgba(87,227,137,.3),rgba(87,227,137,.12));border-color:rgba(87,227,137,.5);color:#57E389;font-size:.72rem}
.fp-key.util{color:#F5B93E;font-size:.78rem}
.fp-hint{font-size:.62rem;color:#9FB4CC;text-align:center;margin-top:10px;font-family:var(--mono);line-height:1.5}

/* ============ MORE ============ */
#more{--acc:var(--blue)}
.more-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:22px}
@media (max-width:960px){.more-grid{grid-template-columns:1fr;max-width:520px;margin-inline:auto}}
.more-card{padding:28px;position:relative;overflow:hidden;transition:.25s}
.more-card:hover{transform:translateY(-5px);border-color:var(--line2)}
.more-card .big-ic{width:52px;height:52px;border-radius:15px;display:flex;align-items:center;justify-content:center;font-size:1.5rem;margin-bottom:18px;border:1px solid}
.mc-invest .big-ic{background:var(--blueT);border-color:rgba(30,111,224,.35);color:var(--blue)}
.mc-cover .big-ic{background:var(--cyanT);border-color:rgba(14,124,134,.35);color:var(--cyan)}
.mc-pay .big-ic{background:var(--goldT);border-color:rgba(154,107,0,.35);color:var(--gold)}
.more-card h3{font-family:var(--disp);font-size:1.08rem;margin-bottom:8px}
.more-card p{font-size:.88rem;color:var(--mut);margin-bottom:16px}
.more-card .stat-line{font-family:var(--mono);font-size:.8rem;border-top:1px dashed var(--line);padding-top:14px;margin-bottom:18px}
.more-card .stat-line b{color:var(--acc)}
.mc-invest{--acc:var(--blue2)}.mc-cover{--acc:var(--cyan)}.mc-pay{--acc:var(--gold)}
.more-spark{position:absolute;right:-10px;top:14px;width:130px;height:50px;opacity:.5}
.btn.joined{background:var(--successT);border-color:rgba(11,122,66,.5);color:var(--success)}

/* ============ CONTACT HUB ============ */
#contact{--acc:var(--blue)}
.contact-grid{display:grid;grid-template-columns:1.1fr .9fr;gap:26px;align-items:start}
@media (max-width:980px){.contact-grid{grid-template-columns:1fr}}
.msg-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:14px}
@media (max-width:560px){.msg-grid{grid-template-columns:1fr}}
.msg-btn{display:flex;align-items:center;gap:14px;padding:18px 20px;border-radius:16px;color:#fff;font-weight:700;transition:.2s;box-shadow:0 14px 34px -14px rgba(21,60,110,.4)}
.msg-btn:hover{transform:translateY(-3px);filter:brightness(1.06)}
.msg-btn .mic{width:44px;height:44px;border-radius:12px;background:rgba(255,255,255,.18);display:flex;align-items:center;justify-content:center;font-size:1.4rem;flex:none}
.msg-btn small{display:block;font-weight:500;font-size:.72rem;opacity:.9;letter-spacing:.06em}
.msg-btn b{font-size:1rem}
.msg-call{background:linear-gradient(135deg,#1E6FE0,#1554B0)}
.msg-wa{background:linear-gradient(135deg,#1FA855,#128C4B)}
.msg-sig{background:linear-gradient(135deg,#3A76F0,#2C6BED)}
.msg-tg{background:linear-gradient(135deg,#2AABEE,#1B7FB5)}
.hours-card{padding:26px}
.hours-card h4{font-family:var(--disp);font-size:1.02rem;display:flex;align-items:center;gap:10px;margin-bottom:16px}
.hours-card h4 .ic{color:var(--blue)}
.h-row{display:flex;justify-content:space-between;padding:9px 0;border-bottom:1px dashed var(--line);font-size:.9rem}
.h-row:last-of-type{border:none}
.h-row span{color:var(--mut)}
.h-row b{font-family:var(--mono);font-weight:600}
.h-row.closed b{color:var(--danger)}
.h-note{margin-top:14px;font-size:.8rem;color:var(--dim)}
.contact-lines{margin-top:18px;display:grid;gap:9px}
.contact-lines a{display:flex;align-items:center;gap:10px;font-size:.9rem;color:var(--mut);padding:9px 12px;border:1px solid var(--line);border-radius:11px;background:#fff;transition:.15s;word-break:break-word}
.contact-lines a:hover{border-color:var(--blue);color:var(--blue2)}
.contact-lines .ic{color:var(--blue)}

/* ============ LEADERSHIP ============ */
#leadership{--acc:var(--gold)}
.lead-panel{background:linear-gradient(150deg,var(--bone) 0%,var(--bone2) 100%);color:var(--boneInk);border-radius:var(--r2);padding:clamp(28px,5vw,56px);display:grid;grid-template-columns:300px 1fr;gap:clamp(26px,4vw,54px);align-items:center;position:relative;overflow:hidden;box-shadow:0 40px 90px -30px rgba(21,60,110,.3)}
.lead-panel::before{content:"";position:absolute;inset:0;background:repeating-linear-gradient(-45deg,transparent 0 34px,rgba(18,36,26,.035) 34px 35px);pointer-events:none}
.lead-panel::after{content:"CHASED";position:absolute;right:-20px;bottom:-34px;font-family:var(--disp);font-weight:800;font-size:8rem;color:rgba(18,36,26,.05);pointer-events:none}
@media (max-width:860px){.lead-panel{grid-template-columns:1fr}.ceo-portrait{max-width:300px;margin-inline:auto}}
.ceo-portrait{position:relative;aspect-ratio:4/5;border-radius:24px;background:linear-gradient(150deg,#12241A,#0B1A12);border:1px solid rgba(18,36,26,.3);display:flex;align-items:center;justify-content:center;overflow:hidden;box-shadow:0 24px 60px -20px rgba(18,36,26,.5)}
.ceo-photo{position:absolute;inset:0;width:100%;height:100%;object-fit:cover;object-position:center top;z-index:1}
.ceo-portrait .ring{position:absolute;inset:12px;border-radius:18px;border:1px dashed rgba(124,192,255,.5);animation:slowspin 40s linear infinite;z-index:2;pointer-events:none}
.ceo-portrait::after{content:"";position:absolute;inset:0;z-index:2;pointer-events:none;background:linear-gradient(180deg,transparent 62%,rgba(6,13,20,.55) 100%)}
@keyframes slowspin{to{transform:rotate(360deg)}}
.ceo-badge{position:absolute;bottom:14px;left:50%;transform:translateX(-50%);background:var(--blue);color:#fff;font-family:var(--mono);font-size:.62rem;font-weight:600;letter-spacing:.22em;padding:6px 14px;border-radius:99px;white-space:nowrap;z-index:3}
.lead-copy .kicker{color:#8A6A14}
.lead-copy .kicker::after{background:linear-gradient(90deg,#8A6A14,transparent)}
.lead-copy h2{font-family:var(--disp);font-weight:800;font-size:clamp(1.6rem,3.4vw,2.5rem);margin-bottom:6px}
.lead-copy .role{font-family:var(--mono);font-size:.86rem;letter-spacing:.2em;text-transform:uppercase;color:#5C6E58;margin-bottom:22px}
.lead-quote{font-size:clamp(1.05rem,1.7vw,1.3rem);line-height:1.55;font-weight:500;max-width:52ch;padding-left:22px;border-left:3px solid #E09A18}
.lead-quote b{background:linear-gradient(transparent 62%,rgba(245,185,62,.55) 62%)}
.lead-sig{font-family:'Caveat',cursive;font-size:2rem;color:#2A4432;margin-top:20px;transform:rotate(-2deg);display:inline-block}
.lead-chips{display:flex;gap:10px;flex-wrap:wrap;margin-top:20px}
.lead-chips .chip{border-color:rgba(18,36,26,.25);background:rgba(18,36,26,.05);color:#41543F}
.lead-chips .chip .ic{color:#8A6A14}
.roles{margin-top:34px;display:grid;grid-template-columns:repeat(3,1fr);gap:14px}
@media (max-width:760px){.roles{grid-template-columns:1fr}}
.role-card{padding:18px 20px;border:1px solid var(--line);border-radius:15px;background:#fff;display:flex;justify-content:space-between;align-items:center;gap:12px}
.role-card b{font-size:.92rem;display:block}
.role-card small{color:var(--dim);font-size:.76rem}

/* ============ FAQ ============ */
#faq{--acc:var(--cyan)}
.faq-list{max-width:820px;display:grid;gap:12px}
.faq-item{border:1px solid var(--line);border-radius:16px;background:#fff;overflow:hidden;transition:.25s}
.faq-item.open{border-color:rgba(14,124,134,.4)}
.faq-q{width:100%;display:flex;justify-content:space-between;align-items:center;gap:16px;padding:19px 22px;font-weight:600;font-size:.98rem;text-align:left;transition:.2s}
.faq-q:hover{color:var(--cyan)}
.faq-q .ic{transition:transform .3s;color:var(--cyan);flex:none}
.faq-item.open .faq-q .ic{transform:rotate(180deg)}
.faq-a{display:grid;grid-template-rows:0fr;transition:grid-template-rows .35s}
.faq-item.open .faq-a{grid-template-rows:1fr}
.faq-a>div{overflow:hidden}
.faq-a p{padding:0 22px 20px;color:var(--mut);font-size:.92rem}

/* ============ CTA ============ */
.cta-band{padding:60px 0 110px}
.cta-inner{position:relative;border-radius:30px;overflow:hidden;padding:clamp(36px,6vw,72px);text-align:center;border:1px solid rgba(30,111,224,.3);
  background:radial-gradient(80% 130% at 15% 0%,rgba(30,111,224,.14),transparent 55%),radial-gradient(70% 120% at 90% 100%,rgba(14,124,134,.12),transparent 55%),linear-gradient(150deg,#FFFFFF,#EAF2FD)}
.cta-inner::before{content:"";position:absolute;inset:0;background:repeating-radial-gradient(circle at 50% 130%,transparent 0 42px,rgba(30,111,224,.05) 42px 43px);pointer-events:none}
.cta-logo{width:74px;height:74px;margin:0 auto 22px}
.cta-inner h2{font-family:var(--disp);font-weight:800;font-size:clamp(1.9rem,4.6vw,3.3rem);margin-bottom:16px}
.cta-inner h2 em{font-style:normal;background:linear-gradient(90deg,var(--blue),var(--cyan));-webkit-background-clip:text;background-clip:text;color:transparent}
.cta-inner p{color:var(--mut);max-width:52ch;margin:0 auto 30px}
.cta-actions{display:flex;gap:14px;justify-content:center;flex-wrap:wrap;position:relative}
.store-btn{display:inline-flex;align-items:center;gap:11px;padding:11px 20px;border-radius:13px;border:1px solid var(--line2);background:#fff;transition:.2s;text-align:left}
.store-btn:hover{border-color:var(--blue);transform:translateY(-2px)}
.store-btn .ic{font-size:1.5rem;color:var(--blue)}
.store-btn small{display:block;font-size:.62rem;color:var(--dim);letter-spacing:.1em;text-transform:uppercase}
.store-btn b{font-size:.92rem}

/* ============ FOOTER ============ */
footer{border-top:1px solid var(--line);background:linear-gradient(180deg,#F0F5FA,#E8F0F8);padding:64px 0 34px}
.f-grid{display:grid;grid-template-columns:1.4fr repeat(3,.8fr) 1.3fr;gap:34px}
@media (max-width:1020px){.f-grid{grid-template-columns:1fr 1fr;gap:38px}}
@media (max-width:560px){.f-grid{grid-template-columns:1fr}}
.f-brand p{color:var(--mut);font-size:.88rem;margin:14px 0 18px;max-width:34ch}
.f-social{display:flex;gap:10px;flex-wrap:wrap}
.f-social a{width:38px;height:38px;border-radius:11px;border:1px solid var(--line);display:flex;align-items:center;justify-content:center;color:var(--mut);transition:.2s;font-size:1rem;background:#fff}
.f-social a:hover{color:var(--blue);border-color:var(--blue);transform:translateY(-3px)}
.f-col h5{font-size:.74rem;letter-spacing:.22em;text-transform:uppercase;color:var(--dim);margin-bottom:16px}
.f-col a{display:block;padding:5px 0;color:var(--mut);font-size:.9rem;transition:.15s;word-break:break-word}
.f-col a:hover{color:var(--blue2);transform:translateX(4px)}
.f-col address{font-style:normal;color:var(--mut);font-size:.88rem;line-height:1.7;padding:5px 0}
.f-hours{font-family:var(--mono);font-size:.78rem;color:var(--blue2);padding:6px 0}
.nl p{color:var(--mut);font-size:.86rem;margin-bottom:14px}
.nl-form{display:flex;gap:8px}
.nl-form input{flex:1;min-width:0;background:#fff;border:1px solid var(--line2);border-radius:11px;padding:11px 14px;font-size:.88rem}
.nl-form input:focus{border-color:var(--blue);outline:none}
#nlMsg{font-size:.8rem;margin-top:9px;min-height:1.2em;color:var(--success)}
.f-bottom{margin-top:52px;padding-top:24px;border-top:1px solid var(--line);display:flex;justify-content:space-between;gap:16px;flex-wrap:wrap;font-size:.78rem;color:var(--dim)}
.f-bottom .mono{color:var(--blue2)}
.f-disc{max-width:78ch;font-size:.72rem;color:#6B7F93;margin-top:14px;line-height:1.6}

/* ============ MODAL ============ */
#modal{position:fixed;inset:0;z-index:200;display:none;align-items:center;justify-content:center;padding:20px}
#modal.open{display:flex}
.m-scrim{position:absolute;inset:0;background:rgba(18,38,58,.45);backdrop-filter:blur(8px);animation:fadein .3s}
@keyframes fadein{from{opacity:0}}
.m-card{position:relative;width:min(560px,100%);max-height:min(88vh,760px);overflow-y:auto;background:#fff;border:1px solid var(--line2);border-radius:24px;padding:30px clamp(20px,4vw,36px) 32px;box-shadow:0 60px 140px -30px rgba(11,27,46,.5);animation:mpop .45s cubic-bezier(.2,.8,.3,1.1)}
@keyframes mpop{from{opacity:0;transform:translateY(34px) scale(.96)}}
.m-card::-webkit-scrollbar{width:8px}
.m-top{display:flex;justify-content:space-between;align-items:flex-start;gap:14px;margin-bottom:6px}
.m-top h3{font-family:var(--disp);font-size:1.25rem;display:flex;align-items:center;gap:10px}
.m-top h3 .cmark{width:26px;height:26px;color:var(--blue)}
.m-close{width:38px;height:38px;border-radius:11px;border:1px solid var(--line);display:flex;align-items:center;justify-content:center;color:var(--mut);transition:.2s;flex:none}
.m-close:hover{color:var(--danger);border-color:var(--danger)}
.m-dots{display:flex;gap:7px;margin:14px 0 24px}
.m-dots i{height:4px;flex:1;border-radius:4px;background:var(--bg3);transition:.3s}
.m-dots i.on{background:linear-gradient(90deg,var(--blue),var(--cyan))}
.m-view{display:none}
.m-view.on{display:block;animation:stage .4s}
.m-sub{color:var(--mut);font-size:.9rem;margin-bottom:20px}
.type-opts{display:grid;gap:11px}
.type-opt{position:relative;display:flex;gap:15px;align-items:center;padding:17px 18px;border:1px solid var(--line);border-radius:15px;cursor:pointer;transition:.2s}
.type-opt:hover{border-color:var(--line2)}
.type-opt input{position:absolute;opacity:0}
.type-opt .radio{width:20px;height:20px;border-radius:50%;border:2px solid var(--line2);flex:none;position:relative;transition:.2s}
.type-opt input:checked ~ .radio{border-color:var(--blue)}
.type-opt input:checked ~ .radio::after{content:"";position:absolute;inset:3px;border-radius:50%;background:var(--blue)}
.type-opt:has(input:checked){border-color:rgba(30,111,224,.55);background:var(--blueT)}
.type-opt b{display:block;font-size:.95rem}
.type-opt small{color:var(--mut);font-size:.8rem}
.type-opt .rate-tag{margin-left:auto;font-family:var(--mono);font-size:.8rem;color:var(--blue2);font-weight:600;flex:none}
.m-form{display:grid;gap:16px}
.f-field label{display:block;font-size:.78rem;font-weight:600;letter-spacing:.08em;text-transform:uppercase;color:var(--mut);margin-bottom:7px}
.f-field .num-in{font-family:var(--body)}
.f-err{display:none;font-size:.76rem;color:var(--danger);margin-top:6px}
.f-field.invalid .f-err{display:block}
.f-field.invalid .num-in{border-color:var(--danger)}
.m-actions{display:flex;gap:12px;margin-top:24px}
.m-actions .btn{flex:1;justify-content:center}
.rv-box{border:1px solid var(--line);border-radius:15px;padding:6px 18px;background:var(--bg0)}
.rv-row{display:flex;justify-content:space-between;gap:14px;padding:11px 0;border-bottom:1px dashed var(--line);font-size:.88rem}
.rv-row:last-child{border:none}
.rv-row span{color:var(--dim)}
.rv-row b{font-weight:600;text-align:right;word-break:break-word}
.terms{display:flex;gap:11px;align-items:flex-start;margin-top:18px;font-size:.82rem;color:var(--mut);cursor:pointer}
.terms input{width:17px;height:17px;margin-top:2px;accent-color:var(--blue);flex:none}
.terms a{color:var(--blue2);text-decoration:underline}
.ok-wrap{text-align:center;padding:8px 0}
.ok-check{width:84px;height:84px;margin:0 auto 18px}
.ok-check circle{stroke:var(--success);stroke-width:2.5;fill:var(--successT);stroke-dasharray:260;stroke-dashoffset:260;animation:draw 1s .1s forwards}
.ok-check path{stroke:var(--success);stroke-width:3.5;fill:none;stroke-linecap:round;stroke-linejoin:round;stroke-dasharray:60;stroke-dashoffset:60;animation:draw .5s .7s forwards}
@keyframes draw{to{stroke-dashoffset:0}}
.ok-wrap h4{font-family:var(--disp);font-size:1.3rem;margin-bottom:8px}
.acct-no-box{border:1px dashed rgba(30,111,224,.5);border-radius:15px;padding:18px;background:var(--blueT);margin-bottom:18px}
.acct-no-box .k{font-size:.68rem;letter-spacing:.22em;text-transform:uppercase;color:var(--mut)}
.acct-no-box .no{font-family:var(--mono);font-weight:600;font-size:clamp(1.4rem,4vw,1.9rem);color:var(--blue2);letter-spacing:.12em;margin:6px 0}
.ok-meta{font-size:.8rem;color:var(--mut);margin-bottom:20px}
.ok-meta b{color:var(--ink)}
#okReset{display:inline-block;margin-top:16px;font-size:.76rem;color:var(--dim);text-decoration:underline}
#okReset:hover{color:var(--danger)}

/* ============ TOASTS / MISC ============ */
#toasts{position:fixed;bottom:22px;right:22px;z-index:300;display:flex;flex-direction:column;gap:10px;max-width:min(360px,calc(100vw - 40px))}
.toast{display:flex;gap:12px;align-items:flex-start;padding:14px 17px;border-radius:14px;background:#fff;border:1px solid var(--line2);font-size:.87rem;box-shadow:0 20px 50px -14px rgba(21,60,110,.35);animation:toastin .4s;border-left-width:3px}
.toast.out{animation:toastout .3s forwards}
@keyframes toastin{from{opacity:0;transform:translateX(40px)}}
@keyframes toastout{to{opacity:0;transform:translateX(40px)}}
.toast .ic{font-size:1.15rem;margin-top:2px}
.toast.success{border-left-color:var(--success)}.toast.success .ic{color:var(--success)}
.toast.danger{border-left-color:var(--danger)}.toast.danger .ic{color:var(--danger)}
.toast.warn{border-left-color:var(--warn)}.toast.warn .ic{color:var(--warn)}
.toast.info{border-left-color:var(--info)}.toast.info .ic{color:var(--info)}
#confetti{position:fixed;inset:0;z-index:400;pointer-events:none;overflow:hidden}
#confetti span{position:absolute;display:block}
#toTop{position:fixed;bottom:22px;left:22px;z-index:150;width:46px;height:46px;border-radius:14px;border:1px solid var(--line2);background:#fff;color:var(--blue);display:flex;align-items:center;justify-content:center;font-size:1.1rem;opacity:0;pointer-events:none;transform:translateY(14px);transition:.3s;box-shadow:var(--shadow)}
#toTop.show{opacity:1;pointer-events:auto;transform:none}
#toTop:hover{border-color:var(--blue)}
@media (max-width:640px){#toasts{right:12px;bottom:12px}#toTop{left:12px;bottom:12px}}
@media (prefers-reduced-motion:reduce){
  *,*::before,*::after{animation-duration:.01ms!important;animation-iteration-count:1!important;transition-duration:.01ms!important}
  html{scroll-behavior:auto}
  .ticker-track{animation:none;flex-wrap:wrap;width:auto}
  .hero-copy>*,.hero-vis{opacity:1;animation:none}
  .reveal{opacity:1;transform:none}
}
</style>
</head>
<body>

<svg width="0" height="0" style="position:absolute" aria-hidden="true">
  <defs>
    <linearGradient id="goldGrad" x1="0" y1="0" x2="1" y2="1"><stop offset="0" stop-color="#F5B93E"/><stop offset="1" stop-color="#FF6B5E"/></linearGradient>
    <linearGradient id="chasedGrad" x1="0" y1="0" x2="1" y2="1"><stop offset="0" stop-color="#1E6FE0"/><stop offset="1" stop-color="#0E7C86"/></linearGradient>
  </defs>
  <symbol id="chased-mark" viewBox="0 0 64 64">
    <circle cx="32" cy="32" r="30" fill="#FFFFFF"/>
    <path d="M49.5 15.5 A24 24 0 1 0 49.5 48.5" fill="none" stroke="url(#chasedGrad)" stroke-width="7" stroke-linecap="round"/>
    <path d="M30 22l11 10-11 10" fill="none" stroke="#1E6FE0" stroke-width="6" stroke-linecap="round" stroke-linejoin="round"/>
    <path d="M42 25l8 7-8 7" fill="none" stroke="#0E7C86" stroke-width="5" stroke-linecap="round" stroke-linejoin="round"/>
  </symbol>
  <symbol id="chased-mark-mono" viewBox="0 0 64 64">
    <path d="M49.5 15.5 A24 24 0 1 0 49.5 48.5" fill="none" stroke="currentColor" stroke-width="7" stroke-linecap="round"/>
    <path d="M30 22l11 10-11 10" fill="none" stroke="currentColor" stroke-width="6" stroke-linecap="round" stroke-linejoin="round"/>
    <path d="M42 25l8 7-8 7" fill="none" stroke="currentColor" stroke-width="5" stroke-linecap="round" stroke-linejoin="round" opacity=".65"/>
  </symbol>
  <symbol id="i-check" viewBox="0 0 24 24"><path d="M4 12.5l5 5L20 6.5"/></symbol>
  <symbol id="i-x" viewBox="0 0 24 24"><path d="M6 6l12 12M18 6L6 18"/></symbol>
  <symbol id="i-arrow-r" viewBox="0 0 24 24"><path d="M4 12h15M13 6l6 6-6 6"/></symbol>
  <symbol id="i-send" viewBox="0 0 24 24"><path d="M21 3L10.5 13.5M21 3l-7 18-3.5-7.5L3 10l18-7z"/></symbol>
  <symbol id="i-shield" viewBox="0 0 24 24"><path d="M12 3l8 3v6c0 4.5-3.2 7.7-8 9-4.8-1.3-8-4.5-8-9V6l8-3z"/><path d="M8.5 12l2.5 2.5 4.5-4.5"/></symbol>
  <symbol id="i-bolt" viewBox="0 0 24 24"><path d="M13 2L4 14h6l-1 8 9-12h-6l1-8z"/></symbol>
  <symbol id="i-lock" viewBox="0 0 24 24"><rect x="5" y="11" width="14" height="9" rx="2"/><path d="M8 11V7a4 4 0 018 0v4"/></symbol>
  <symbol id="i-phone" viewBox="0 0 24 24"><rect x="7" y="2.5" width="10" height="19" rx="2.5"/><path d="M11 18.5h2"/></symbol>
  <symbol id="i-globe" viewBox="0 0 24 24"><circle cx="12" cy="12" r="9"/><path d="M3 12h18M12 3c3 3.5 3 14 0 18-3-4-3-14.5 0-18z"/></symbol>
  <symbol id="i-snow" viewBox="0 0 24 24"><path d="M12 2v20M4 6l16 12M20 6L4 18"/></symbol>
  <symbol id="i-copy" viewBox="0 0 24 24"><rect x="9" y="9" width="11" height="11" rx="2"/><path d="M5 15H4a2 2 0 01-2-2V4a2 2 0 012-2h9a2 2 0 012 2v1"/></symbol>
  <symbol id="i-download" viewBox="0 0 24 24"><path d="M12 3v12M7 10l5 5 5-5M4 20h16"/></symbol>
  <symbol id="i-chev" viewBox="0 0 24 24"><path d="M6 9l6 6 6-6"/></symbol>
  <symbol id="i-menu" viewBox="0 0 24 24"><path d="M4 7h16M4 12h16M4 17h16"/></symbol>
  <symbol id="i-plus" viewBox="0 0 24 24"><path d="M12 5v14M5 12h14"/></symbol>
  <symbol id="i-minus" viewBox="0 0 24 24"><path d="M5 12h14"/></symbol>
  <symbol id="i-card" viewBox="0 0 24 24"><rect x="2.5" y="5" width="19" height="14" rx="2.5"/><path d="M2.5 10h19M6 15h4"/></symbol>
  <symbol id="i-coins" viewBox="0 0 24 24"><ellipse cx="9" cy="7" rx="6.5" ry="3"/><path d="M2.5 7v5c0 1.7 2.9 3 6.5 3s6.5-1.3 6.5-3V7"/><path d="M2.5 12v5c0 1.7 2.9 3 6.5 3s6.5-1.3 6.5-3v-5"/></symbol>
  <symbol id="i-chart" viewBox="0 0 24 24"><path d="M4 20V4M4 20h16M8 16v-5M12 16V8M16 16v-3M20 16V6"/></symbol>
  <symbol id="i-bag" viewBox="0 0 24 24"><path d="M5 8h14l-1.2 12H6.2L5 8z"/><path d="M8.5 10V6.5a3.5 3.5 0 017 0V10"/></symbol>
  <symbol id="i-umbrella" viewBox="0 0 24 24"><path d="M12 3a9 9 0 019 9H3a9 9 0 019-9zM12 12v6.5a2 2 0 004 0"/></symbol>
  <symbol id="i-wallet" viewBox="0 0 24 24"><path d="M3 7a2 2 0 012-2h13v3"/><path d="M3 7v11a2 2 0 002 2h15a1 1 0 001-1V9a1 1 0 00-1-1H5a2 2 0 01-2-2z"/><circle cx="16.5" cy="14.5" r="1.2"/></symbol>
  <symbol id="i-top" viewBox="0 0 24 24"><path d="M12 19V5M6 11l6-6 6 6"/></symbol>
  <symbol id="i-swap" viewBox="0 0 24 24"><path d="M7 4v13M3.5 7.5L7 4l3.5 3.5M17 20V7M13.5 16.5L17 20l3.5-3.5"/></symbol>
  <symbol id="i-home" viewBox="0 0 24 24"><path d="M4 11l8-7 8 7v9a1 1 0 01-1 1h-5v-6h-4v6H5a1 1 0 01-1-1v-9z"/></symbol>
  <symbol id="i-cal" viewBox="0 0 24 24"><rect x="3.5" y="5" width="17" height="16" rx="2"/><path d="M3.5 10h17M8 3v4M16 3v4"/></symbol>
  <symbol id="i-grid" viewBox="0 0 24 24"><rect x="4" y="4" width="7" height="7" rx="1.5"/><rect x="13" y="4" width="7" height="7" rx="1.5"/><rect x="4" y="13" width="7" height="7" rx="1.5"/><rect x="13" y="13" width="7" height="7" rx="1.5"/></symbol>
  <symbol id="i-play" viewBox="0 0 24 24"><path d="M7 4.5l13 7.5-13 7.5v-15z"/></symbol>
  <symbol id="i-apple" viewBox="0 0 24 24"><path d="M16 3c.3 1.6-.9 3.4-2.6 3.3C13.1 4.7 14.4 3.1 16 3zM12.5 7.5c1.2 0 2.2-.9 3.8-.9 1.4 0 2.7.8 3.4 2-3 1.7-2.5 5.8.5 7-.6 1.5-1.4 3-2.6 4.3-1.1 1.2-2.3 1.2-3.6.6-1.2-.5-2.3-.5-3.5 0-1.3.6-2.4.6-3.5-.6C4.6 17.3 3.4 12.6 5.5 9.4c1-1.6 2.7-2.6 4.3-2.6 1.4 0 2 .7 2.7.7z"/></symbol>
  <symbol id="i-info" viewBox="0 0 24 24"><circle cx="12" cy="12" r="9"/><path d="M12 11v5M12 7.5v.5"/></symbol>
  <symbol id="i-alert" viewBox="0 0 24 24"><path d="M12 3L2.5 20h19L12 3zM12 10v4.5M12 17.5v.5"/></symbol>
  <symbol id="i-refresh" viewBox="0 0 24 24"><path d="M20 12a8 8 0 11-2.3-5.6M20 3v4h-4"/></symbol>
  <symbol id="i-star" viewBox="0 0 24 24"><path d="M12 3l2.7 5.8 6.3.8-4.6 4.3 1.2 6.1L12 17l-5.6 3 1.2-6.1L3 9.6l6.3-.8L12 3z"/></symbol>
  <symbol id="i-pin" viewBox="0 0 24 24"><path d="M12 21s-7-6.1-7-11a7 7 0 0114 0c0 4.9-7 11-7 11z"/><circle cx="12" cy="10" r="2.6"/></symbol>
  <symbol id="i-tel" viewBox="0 0 24 24"><path d="M5 4h4l2 5-2.5 1.5a12 12 0 005 5L15 13l5 2v4a2 2 0 01-2 2A16 16 0 013 6a2 2 0 012-2z"/></symbol>
  <symbol id="i-mail" viewBox="0 0 24 24"><rect x="3" y="5" width="18" height="14" rx="2.5"/><path d="M3.5 7l8.5 6 8.5-6"/></symbol>
  <symbol id="i-clock" viewBox="0 0 24 24"><circle cx="12" cy="12" r="9"/><path d="M12 7v5l3.5 2"/></symbol>
  <symbol id="i-wa" viewBox="0 0 24 24"><path d="M12 3a9 9 0 00-7.8 13.5L3 21l4.6-1.2A9 9 0 1012 3z"/><path d="M8.8 8.5c-.3 2.5 3.2 6.3 6 6.6l1.2-1.5-2-1.2-.9.7c-1-.5-2-1.5-2.5-2.5l.7-.9-1.2-2-1.3.8z" fill="currentColor" stroke="none"/></symbol>
  <symbol id="i-sig" viewBox="0 0 24 24"><path d="M12 3a9 9 0 00-7.8 13.5L3 21l4.6-1.2A9 9 0 1012 3z" stroke-dasharray="3 2.2"/></symbol>
  <symbol id="i-tg" viewBox="0 0 24 24"><path d="M21 4L3 11l5.5 2L10 19l3-3.5 5 3.5L21 4z"/><path d="M8.5 13L18 6.5"/></symbol>
</svg>

<div class="atmo" aria-hidden="true"><div class="orb a"></div><div class="orb b"></div><div class="orb c"></div></div>
<div class="gridlines" aria-hidden="true"></div>
<div id="progress" aria-hidden="true"></div>

<header id="siteNav">
  <div class="nav-in">
    <a class="brand" href="#home" aria-label="Chased Bank home">
      <svg viewBox="0 0 64 64" aria-hidden="true"><use href="#chased-mark"/></svg>
      <span class="wordmark">CHASED<em>.</em></span>
    </a>
    <nav class="nav-links" aria-label="Primary">
      <a href="#accounts" data-nav>Accounts</a>
      <a href="#payments" data-nav>Payments</a>
      <a href="#loans" data-nav>Loans</a>
      <a href="#cards" data-nav>Cards</a>
      <a href="#fx" data-nav>FX</a>
      <a href="#digital" data-nav>Digital</a>
      <a href="#contact" data-nav>Contact</a>
      <a href="#leadership" data-nav>About</a>
    </nav>
    <div class="nav-cta">
      <span id="hoursPill"><span class="dot"></span>MON–FRI · 9AM–6PM ET</span>
      <button id="acctChip" type="button" aria-label="View your Chased account"><span class="dot"></span><span id="acctChipTxt">•••• 0000</span></button>
      <button class="btn btn-p btn-sm" type="button" data-open-account>Open account <svg class="ic"><use href="#i-arrow-r"/></svg></button>
      <button id="menuBtn" type="button" aria-label="Menu" aria-expanded="false"><svg class="ic"><use href="#i-menu"/></svg></button>
    </div>
  </div>
</header>
<div class="m-panel" id="mPanel">
  <a href="#accounts">Accounts <svg class="ic"><use href="#i-arrow-r"/></svg></a>
  <a href="#payments">Payments &amp; transfers <svg class="ic"><use href="#i-arrow-r"/></svg></a>
  <a href="#loans">Loans &amp; credit <svg class="ic"><use href="#i-arrow-r"/></svg></a>
  <a href="#cards">Cards <svg class="ic"><use href="#i-arrow-r"/></svg></a>
  <a href="#fx">FX &amp; remittances <svg class="ic"><use href="#i-arrow-r"/></svg></a>
  <a href="#digital">App · Online · USSD <svg class="ic"><use href="#i-arrow-r"/></svg></a>
  <a href="#contact">Contact · Mon–Fri <svg class="ic"><use href="#i-tel"/></svg></a>
  <a href="#leadership">Leadership <svg class="ic"><use href="#i-arrow-r"/></svg></a>
  <a href="#faq">FAQ <svg class="ic"><use href="#i-arrow-r"/></svg></a>
  <a href="tel:+13027130106">Call +1 (302) 713-0106 <svg class="ic"><use href="#i-tel"/></svg></a>
  <a href="https://wa.me/+13027130106" target="_blank" rel="noopener">WhatsApp us <svg class="ic"><use href="#i-wa"/></svg></a>
  <button class="btn btn-p" type="button" data-open-account>Open free account <svg class="ic"><use href="#i-arrow-r"/></svg></button>
</div>

<main id="home">

<section class="hero" aria-label="Welcome">
  <div class="wrap hero-grid">
    <div class="hero-copy">
      <span class="hero-eyebrow"><span class="dot"></span> ORLANDO, FL · DIGITAL-FIRST BANK · EST. 2026</span>
      <h1>Banking that keeps up with <span class="grad">the chase.</span></h1>
      <p class="hero-sub">Zero-fee everyday accounts, savings earning up to <b>4.35% APY</b>, transfers that land in <b>seconds</b> — on a flagship app, a full web bank, or a simple <b>*347#</b> code on any phone. All amounts in <b>USD ($)</b>.</p>
      <div class="hero-ctas">
        <button class="btn btn-p" type="button" data-open-account>Open free account <svg class="ic"><use href="#i-arrow-r"/></svg></button>
        <a class="btn btn-g" href="#contact"><svg class="ic"><use href="#i-wa"/></svg> Message us — Mon–Fri</a>
      </div>
      <div class="hero-trust">
        <span class="chip"><svg class="ic"><use href="#i-shield"/></svg> Deposit protection*</span>
        <span class="chip"><svg class="ic"><use href="#i-lock"/></svg> 256-bit encryption</span>
        <span class="chip"><svg class="ic"><use href="#i-tel"/></svg> +1 (302) 713-0106</span>
      </div>
    </div>
    <div class="hero-vis" id="heroVis">
      <div class="hv-stack">
        <div class="ghost g1" aria-hidden="true"></div>
        <div class="ghost g2" aria-hidden="true"></div>
        <div class="bankcard3d" id="heroCard3d" role="button" tabindex="0" aria-label="Chased debit card preview — activate to flip" aria-pressed="false">
          <div class="bc-inner">
            <div class="bc-face bc-front">
              <div class="bc-top">
                <span class="bc-brand"><svg class="cmark" viewBox="0 0 64 64" aria-hidden="true"><use href="#chased-mark-mono"/></svg>CHASED<em>.</em></span>
                <span class="bc-type">Everyday · Debit</span>
              </div>
              <div class="bc-mid">
                <svg width="42" height="32" viewBox="0 0 42 32" aria-hidden="true"><rect x="1" y="1" width="40" height="30" rx="6" fill="#F5B93E"/><path d="M1 12h13M28 12h13M1 20h13M28 20h13M14 1v30M28 1v30" stroke="#8A6A14" stroke-width="1.6" fill="none"/></svg>
                <svg width="24" height="24" viewBox="0 0 24 24" aria-hidden="true" style="color:#9FB4CC"><path d="M6 8.5a9 9 0 010 7M10 6a13 13 0 010 12M14 3.5a17 17 0 010 17" stroke="currentColor" stroke-width="1.8" fill="none" stroke-linecap="round"/></svg>
              </div>
              <div style="margin-top:10px">
                <div class="bc-bal-label">Available balance</div>
                <div class="bc-bal" data-balance>$12,480.50</div>
              </div>
              <div class="bc-num">4821&nbsp;&nbsp;••••&nbsp;&nbsp;••••&nbsp;&nbsp;3401</div>
              <div class="bc-bottom">
                <span class="bc-holder"><small>CARD HOLDER</small><span data-holder>A. CUSTOMER</span></span>
                <span class="bc-net">VISA</span>
              </div>
            </div>
            <div class="bc-face bc-back">
              <div class="bc-stripe"></div>
              <div class="bc-cvv"><span>CVV</span><b>•••</b></div>
              <p>This card is issued by Chased Bank pursuant to network licence. If found, call +1 (302) 713-0106, Mon–Fri 9AM–6PM ET.</p>
            </div>
          </div>
          <div class="frost"><svg class="ic"><use href="#i-snow"/></svg>FROZEN</div>
        </div>
        <div class="float-chip fc1"><svg class="ic"><use href="#i-check"/></svg><span>+$1,250.00<small>From Marcus T. · 09:12</small></span></div>
        <div class="float-chip fc2"><svg class="ic"><use href="#i-bolt"/></svg><span>Transfer delivered<small>RTP / FedNow · 3.8 seconds</small></span></div>
        <div class="float-chip fc3"><svg class="ic"><use href="#i-globe"/></svg><span>£200 → $253.58<small>Chased Global · 0.4% spread</small></span></div>
      </div>
      <p class="flip-hint">TAP CARD TO FLIP · MOVE POINTER TO TILT</p>
    </div>
  </div>
  <div class="ticker" aria-label="Live bank ticker">
    <div class="ticker-track" id="tickerTrack">
      <span class="tk"><b>GBP/USD</b> 1.2730 <span class="up">▲ 0.2%</span> <span class="sep">◆</span></span>
      <span class="tk"><b>EUR/USD</b> 1.0845 <span class="dn">▼ 0.1%</span> <span class="sep">◆</span></span>
      <span class="tk">SAVINGS UP TO <b>4.35% APY</b> <span class="sep">◆</span></span>
      <span class="tk">12-MONTH CD <b>4.75% APY</b> <span class="sep">◆</span></span>
      <span class="tk">AVG TRANSFER <b>4.2s</b> <span class="sep">◆</span></span>
      <span class="tk">USSD <b>*347#</b> — WORKS OFFLINE <span class="sep">◆</span></span>
      <span class="tk">SUPPORT <b>MON–FRI 9AM–6PM ET</b> <span class="sep">◆</span></span>
      <span class="tk">CALL · WHATSAPP · SIGNAL · TELEGRAM <b>+1 (302) 713-0106</b> <span class="sep">◆</span></span>
      <span class="tk">EMAIL <b>chasedbank56@gmail.com</b> <span class="sep">◆</span></span>
    </div>
  </div>
</section>

<section class="stats" aria-label="Chased in numbers">
  <div class="wrap stats-grid">
    <div class="stat reveal" style="--sc:var(--blue)"><div class="num"><span data-count="1.2" data-dec="1" data-prefix="$" data-suffix="B+">$0B+</span></div><div class="lbl">moved every month</div></div>
    <div class="stat reveal" style="--sc:var(--cyan);--d:.1s"><div class="num"><span data-count="182" data-suffix="k+">0k+</span></div><div class="lbl">accounts chasing more</div></div>
    <div class="stat reveal" style="--sc:var(--gold);--d:.2s"><div class="num"><span data-count="4.2" data-dec="1" data-suffix="s">0s</span></div><div class="lbl">average transfer settlement</div></div>
    <div class="stat reveal" style="--sc:var(--blue2);--d:.3s"><div class="num"><span data-count="99.98" data-dec="2" data-suffix="%">0%</span></div><div class="lbl">platform uptime, last 12 months</div></div>
  </div>
</section>

<section id="accounts">
  <div class="wrap">
    <div class="split">
      <div class="sticky reveal">
        <div class="kicker">01 — Deposit accounts</div>
        <h2 class="disp" style="font-size:clamp(1.7rem,3vw,2.4rem);margin-bottom:16px">Three ways to <em style="font-style:normal;color:var(--blue)">hold your dollars.</em></h2>
        <p style="color:var(--mut)">Spend from Everyday, compound in Grow, lock away in Vault CDs. Open all three in one app — switch between them like tabs, sweep idle cash automatically. Everything in USD.</p>
        <div style="margin-top:24px;display:grid;gap:11px">
          <span class="chip"><svg class="ic"><use href="#i-check"/></svg> No minimum balance, ever</span>
          <span class="chip"><svg class="ic"><use href="#i-check"/></svg> Interest paid monthly, compounded daily</span>
          <span class="chip"><svg class="ic"><use href="#i-check"/></svg> Free account number in 2 minutes</span>
        </div>
        <button class="btn btn-p" style="margin-top:26px" type="button" data-open-account>Open an account <svg class="ic"><use href="#i-arrow-r"/></svg></button>
      </div>
      <div>
        <div class="acct-tabs reveal" role="tablist" aria-label="Account types">
          <button class="acct-tab" role="tab" data-acct="everyday" aria-selected="false"><svg class="ic"><use href="#i-wallet"/></svg> Chased Everyday</button>
          <button class="acct-tab" role="tab" data-acct="grow" aria-selected="true"><svg class="ic"><use href="#i-chart"/></svg> Chased Grow</button>
          <button class="acct-tab" role="tab" data-acct="vault" aria-selected="false"><svg class="ic"><use href="#i-lock"/></svg> Chased Vault</button>
        </div>
        <div class="panel acct-panel reveal" data-acct-panel="everyday" hidden>
          <div>
            <h3>Chased Everyday <span class="pill info">Checking</span></h3>
            <p class="tag">Your spending engine. Paycheck in, bills out, zero drama.</p>
            <ul class="feat-list">
              <li><svg class="ic"><use href="#i-check"/></svg> $0 monthly fee · $0 minimum balance</li>
              <li><svg class="ic"><use href="#i-check"/></svg> Free ACH &amp; instant transfers during launch</li>
              <li><svg class="ic"><use href="#i-check"/></svg> Free virtual Visa debit card at signup</li>
              <li><svg class="ic"><use href="#i-check"/></svg> Idle cash auto-sweeps to 1.00% APY overnight</li>
              <li><svg class="ic"><use href="#i-check"/></svg> Standing orders, bulk pay &amp; bill schedules</li>
            </ul>
          </div>
          <div class="acct-meta">
            <div class="meta-box"><div class="k">Overnight sweep</div><div class="v">1.00% APY</div><small>on idle balances, compounded daily</small></div>
            <div class="meta-box"><div class="k">Opening deposit</div><div class="v gold">$0</div><small>really — start with nothing</small></div>
            <div class="meta-box"><div class="k">Monthly fee</div><div class="v gold">$0</div><small>no maintenance fees, no overdraft traps</small></div>
          </div>
        </div>
        <div class="panel acct-panel reveal" data-acct-panel="grow">
          <div>
            <h3>Chased Grow <span class="pill ok">Savings</span></h3>
            <p class="tag">High-yield savings with goal pockets and daily compounding.</p>
            <ul class="feat-list">
              <li><svg class="ic"><use href="#i-check"/></svg> Up to <b>4.35% APY</b>, tiered by balance</li>
              <li><svg class="ic"><use href="#i-check"/></svg> Goal sub-accounts: Rent, Trip, Emergency, New Car</li>
              <li><svg class="ic"><use href="#i-check"/></svg> Auto-save rules: round-ups, paycheck %, weekly drip</li>
              <li><svg class="ic"><use href="#i-check"/></svg> Unlimited withdrawals — your money stays liquid</li>
              <li><svg class="ic"><use href="#i-check"/></svg> Interest credited monthly — watch it tick</li>
            </ul>
          </div>
          <div class="acct-meta">
            <div class="meta-box"><div class="k">Headline rate</div><div class="v">4.35% APY</div><small>balances above $10,000</small></div>
            <div class="meta-box"><div class="k">Entry tier</div><div class="v">3.50% APY</div><small>from your first $100</small></div>
            <div class="meta-box"><div class="k">Lock-in</div><div class="v gold">None</div><small>withdraw whenever you want</small></div>
          </div>
        </div>
        <div class="panel acct-panel reveal" data-acct-panel="vault" hidden>
          <div>
            <h3>Chased Vault <span class="pill warn">Fixed deposit · CD</span></h3>
            <p class="tag">Lock it. Forget it. Collect the biggest rate we publish.</p>
            <ul class="feat-list">
              <li><svg class="ic"><use href="#i-check"/></svg> <b>4.75% APY</b> on 12-month CDs — rate fixed at booking</li>
              <li><svg class="ic"><use href="#i-check"/></svg> Terms from 3 to 12 months, from $1,000</li>
              <li><svg class="ic"><use href="#i-check"/></svg> Transparent early withdrawal: 90 days of interest penalty</li>
              <li><svg class="ic"><use href="#i-check"/></svg> Auto-renewal with rate re-quote at maturity</li>
              <li><svg class="ic"><use href="#i-check"/></svg> Use your CD as collateral for a secured credit card</li>
            </ul>
          </div>
          <div class="acct-meta">
            <div class="meta-box"><div class="k">12-month CD</div><div class="v">4.75% APY</div><small>fixed for the full term</small></div>
            <div class="meta-box"><div class="k">6-month CD</div><div class="v">4.40% APY</div><small>short lock, solid yield</small></div>
            <div class="meta-box"><div class="k">Minimum</div><div class="v gold">$1,000</div><small>top up any time before lock</small></div>
          </div>
        </div>
        <div class="panel calc reveal">
          <div class="calc-head">
            <h4><svg class="ic" style="color:var(--blue)"><use href="#i-chart"/></svg> <span id="svCalcTitle">Chased Grow projection</span></h4>
            <span class="pill ok">Live calculator · USD</span>
          </div>
          <div class="calc-grid">
            <div style="display:grid;gap:20px;align-content:start">
              <div class="field">
                <label for="svAmt">Amount to deposit ($)</label>
                <div class="range-row">
                  <input type="range" id="svAmt" min="500" max="250000" step="500" value="10000">
                  <span class="range-out" id="svAmtOut">$10,000</span>
                </div>
                <input type="number" class="num-in" id="svAmtN" min="100" max="1000000" step="100" value="10000" style="margin-top:12px" aria-label="Deposit amount (typed)">
              </div>
              <div class="field"><label>Term</label><div class="tenor-chips" id="svTenors"></div></div>
            </div>
            <div class="calc-out">
              <div class="co-row"><span>Rate applied</span><b id="svRate">4.35% APY</b></div>
              <div class="co-row"><span>Interest earned</span><b id="svInterest" style="color:var(--success)">$0.00</b></div>
              <div class="co-row big"><span>Value at maturity</span><b id="svTotal">$0.00</b></div>
              <div class="bars" id="svChart" aria-hidden="true"><div class="bar"></div><div class="bar"></div><div class="bar"></div><div class="bar"></div><div class="bar"></div><div class="bar"></div></div>
              <p class="calc-note">Illustrative projection, daily compounding. Rates confirmed at booking. All figures in USD.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="payments">
  <div class="wrap">
    <div class="split">
      <div class="sticky reveal">
        <div class="kicker">02 — Payments &amp; transfers</div>
        <h2 class="disp" style="font-size:clamp(1.7rem,3vw,2.4rem);margin-bottom:16px">Money that arrives <em style="font-style:normal;color:var(--cyan)">before the excuse.</em></h2>
        <p style="color:var(--mut)">Instant RTP/FedNow rails with live name-lookup, free ACH, scheduled payments, bulk payouts and every bill in one place. Try a transfer on the demo wallet — the USD balance updates everywhere on this page.</p>
        <div class="rail-list">
          <div class="rail"><svg class="ic"><use href="#i-bolt"/></svg><div><b>Instant transfers</b><span>RTP &amp; FedNow · any US bank · avg 4.2s</span></div></div>
          <div class="rail"><svg class="ic"><use href="#i-cal"/></svg><div><b>Scheduled &amp; recurring</b><span>Rent, tuition, allowance — set once</span></div></div>
          <div class="rail"><svg class="ic"><use href="#i-grid"/></svg><div><b>Bulk payouts &amp; ACH</b><span>Pay 5,000 staff or vendors from one CSV</span></div></div>
          <div class="rail"><svg class="ic"><use href="#i-phone"/></svg><div><b>Bills &amp; top-ups</b><span>Utilities, phone, streaming, insurance</span></div></div>
        </div>
      </div>
      <div>
        <div class="panel tw reveal">
          <div id="twForm">
            <h4><svg class="ic"><use href="#i-send"/></svg> Send money — live demo</h4>
            <p class="tw-sub">Pulls from your demo balance of <b class="mono" data-balance>$12,480.50</b>. No real funds move.</p>
            <div class="tw-grid">
              <div class="field">
                <label for="twAmt">Amount ($)</label>
                <input type="number" class="num-in" id="twAmt" min="1" step="1" placeholder="250" value="250">
                <div class="quick-amts">
                  <button class="qa" type="button" data-qa="50">$50</button>
                  <button class="qa" type="button" data-qa="250">$250</button>
                  <button class="qa" type="button" data-qa="1000">$1k</button>
                  <button class="qa" type="button" data-qa="2500">$2.5k</button>
                </div>
              </div>
              <div class="field">
                <label for="twBank">Destination bank</label>
                <select class="num-in" id="twBank">
                  <option value="Chase">Chase</option><option value="Bank of America">Bank of America</option>
                  <option value="Wells Fargo">Wells Fargo</option><option value="Citibank">Citibank</option>
                  <option value="Capital One">Capital One</option><option value="Truist">Truist</option>
                  <option value="Cash App">Cash App</option><option value="Chime">Chime</option>
                </select>
              </div>
              <div class="field full">
                <label for="twAcct">10-digit account number</label>
                <input type="text" class="num-in" id="twAcct" inputmode="numeric" maxlength="10" placeholder="0123456789" autocomplete="off">
                <div class="name-chip" id="twNameChip"><svg class="ic"><use href="#i-check"/></svg><span id="twNameTxt"></span></div>
              </div>
            </div>
            <div class="fee-line"><span>Transfer fee (launch offer)</span><b>$0.00 — FREE</b></div>
            <button class="btn btn-p" id="twSend" type="button" style="width:100%;justify-content:center">Send now <svg class="ic"><use href="#i-send"/></svg></button>
            <ol class="tw-steps" id="twSteps">
              <li>Queued at Chased core</li>
              <li>Switched via RTP / FedNow instant rail</li>
              <li id="twStep3">Delivered</li>
            </ol>
          </div>
          <div class="receipt" id="twDone" role="status">
            <div class="rc-ok"><svg class="ic"><use href="#i-check"/></svg> Transfer delivered</div>
            <div class="rc-row"><span>Amount</span><b id="rcAmt">$250.00</b></div>
            <div class="rc-row"><span>Beneficiary</span><b id="rcTo">—</b></div>
            <div class="rc-row"><span>Bank</span><b id="rcBank">—</b></div>
            <div class="rc-row"><span>Fee</span><b style="color:var(--success)">$0.00</b></div>
            <div class="rc-row"><span>Reference</span><b id="rcRef">—</b></div>
            <div class="rc-row"><span>Time</span><b id="rcTime">—</b></div>
            <div class="rc-actions">
              <button class="btn btn-g btn-sm" id="twShare" type="button"><svg class="ic"><use href="#i-copy"/></svg> Copy receipt</button>
              <button class="btn btn-p btn-sm" id="twAgain" type="button"><svg class="ic"><use href="#i-refresh"/></svg> New transfer</button>
            </div>
          </div>
        </div>
        <div class="hist reveal">
          <h5>Recent transfers</h5>
          <ul class="hist-list" id="transferHistory"></ul>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="loans">
  <div class="wrap">
    <div class="sec-head reveal">
      <div class="kicker">03 — Loans &amp; credit</div>
      <h2>Credit with the maths <em>on the table.</em></h2>
      <p>One reducing-balance rate, one page of terms, zero hidden charges. Slide the numbers — the repayment updates live. All figures in USD.</p>
    </div>
    <div class="split" style="grid-template-columns:1.1fr .9fr">
      <div class="panel calc reveal" style="margin-top:0">
        <div class="calc-head">
          <h4><svg class="ic" style="color:var(--gold)"><use href="#i-coins"/></svg> Repayment calculator</h4>
          <span class="pill warn">1.49% / month · reducing</span>
        </div>
        <div style="display:grid;gap:22px">
          <div class="field">
            <label for="lnAmt">Loan amount ($)</label>
            <div class="range-row">
              <input type="range" id="lnAmt" min="1000" max="100000" step="500" value="25000">
              <span class="range-out" id="lnAmtOut">$25,000</span>
            </div>
          </div>
          <div class="field">
            <label>Term (months)</label>
            <div class="stepper">
              <button type="button" id="lnMinus" aria-label="One month less"><svg class="ic"><use href="#i-minus"/></svg></button>
              <span class="val" id="lnTenorOut">12 months</span>
              <button type="button" id="lnPlus" aria-label="One month more"><svg class="ic"><use href="#i-plus"/></svg></button>
              <input type="range" id="lnTenor" min="1" max="24" step="1" value="12" style="flex:1" aria-label="Loan term in months">
            </div>
          </div>
          <div class="calc-out">
            <div class="co-row big" style="border:none;margin:0;padding-top:0"><span>Monthly repayment</span><b id="lnMonthly">$0.00</b></div>
            <div class="co-row"><span>Total interest</span><b id="lnInterest">$0.00</b></div>
            <div class="co-row"><span>Total repayable</span><b id="lnTotal">$0.00</b></div>
            <div class="co-row"><span>Effective APR</span><b id="lnApr" style="color:var(--warn)">19.4%</b></div>
            <div class="donut-wrap">
              <svg class="donut" viewBox="0 0 120 120" aria-hidden="true">
                <circle class="base" cx="60" cy="60" r="48"/>
                <circle class="int" id="lnDonutInt" cx="60" cy="60" r="48" transform="rotate(-90 60 60)" stroke-dasharray="0 302"/>
                <text x="60" y="65" text-anchor="middle" id="lnDonutPct">0%</text>
              </svg>
              <div class="legend">
                <span><i style="background:var(--bg3)"></i>Principal — what you received</span>
                <span><i style="background:linear-gradient(135deg,#F5B93E,#FF6B5E)"></i>Interest — what it costs</span>
                <span style="color:var(--dim);font-size:.76rem">No origination, insurance or "processing" fees added.</span>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div>
        <div class="loan-cards reveal">
          <div class="loan-card">
            <div class="lc-top"><b>Chased Advance</b><span class="pill ok">Instant decision</span></div>
            <p>$200 – $5,000 micro-loans scored on your account behaviour. Money in under 60 seconds.</p>
            <div class="req">REQ: 60 DAYS OF ACCOUNT HISTORY</div>
          </div>
          <div class="loan-card">
            <div class="lc-top"><b>Chased Personal</b><span class="pill info">Up to $100k</span></div>
            <p>Paycheck-backed term loans, 1–24 months. Repay early any time — interest stops that day.</p>
            <div class="req">REQ: DIRECT DEPOSIT OR 3 MONTHS STATEMENTS</div>
          </div>
          <div class="loan-card">
            <div class="lc-top"><b>Chased Business</b><span class="pill warn">Phase 2</span></div>
            <p>SME working capital &amp; invoice lines, priced from your Chased Pay settlement flow.</p>
            <div class="req">REQ: 6 MONTHS MERCHANT HISTORY · JOIN WAITLIST</div>
          </div>
        </div>
        <div class="elig reveal">
          <h5><svg class="ic"><use href="#i-bolt"/></svg> 10-second eligibility check</h5>
          <div class="field">
            <label for="incAmt">Monthly income ($)</label>
            <div class="range-row">
              <input type="range" id="incAmt" min="2000" max="20000" step="250" value="6000">
              <span class="range-out" id="incOut">$6,000</span>
            </div>
          </div>
          <label class="switch" style="margin-top:16px">
            <input type="checkbox" id="salaryT" checked><span class="tr"></span>
            I'll set up direct deposit with Chased
          </label>
          <div class="elig-out">
            <span class="pill ok" id="eligPill">Pre-qualified</span>
            <span style="font-size:.86rem;color:var(--mut)">up to</span>
            <span class="amt" id="eligOut">$0</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="cards">
  <div class="wrap">
    <div class="sec-head reveal">
      <div class="kicker">04 — Cards</div>
      <h2>Three cards. <em>One tap to freeze any of them.</em></h2>
      <p>Tap a card to flip it, drag its daily limit, freeze it instantly — the app mockup and USSD demo stay in sync. Physical cards ship in 3–5 business days anywhere in the US.</p>
    </div>
    <div class="cards-grid">
      <article class="card-item reveal" data-card="debit">
        <div class="bankcard3d" role="button" tabindex="0" aria-label="Chased Debit card — activate to flip" aria-pressed="false">
          <div class="bc-inner">
            <div class="bc-face bc-front">
              <div class="bc-top"><span class="bc-brand"><svg class="cmark" viewBox="0 0 64 64" aria-hidden="true"><use href="#chased-mark-mono"/></svg>CHASED<em>.</em></span><span class="bc-type">Debit</span></div>
              <div class="bc-mid">
                <svg width="38" height="29" viewBox="0 0 42 32" aria-hidden="true"><rect x="1" y="1" width="40" height="30" rx="6" fill="#F5B93E"/><path d="M1 12h13M28 12h13M1 20h13M28 20h13M14 1v30M28 1v30" stroke="#8A6A14" stroke-width="1.6" fill="none"/></svg>
                <span class="pill ok" data-card-status="debit" style="margin-left:auto">Active</span>
              </div>
              <div class="bc-num" style="margin-top:auto">4821&nbsp;••••&nbsp;••••&nbsp;3401</div>
              <div class="bc-bottom"><span class="bc-holder"><small>CARD HOLDER</small><span data-holder>A. CUSTOMER</span></span><span class="bc-net">VISA</span></div>
            </div>
            <div class="bc-face bc-back">
              <div class="bc-stripe"></div>
              <div class="bc-cvv"><span>CVV</span><b>•••</b></div>
              <div class="bc-limit-line">DAILY LIMIT · <span data-limit-back="debit">$2,000</span></div>
              <p>Zero issuance fee. Zero maintenance. Lost card? Call +1 (302) 713-0106, Mon–Fri 9AM–6PM ET.</p>
            </div>
          </div>
          <div class="frost"><svg class="ic"><use href="#i-snow"/></svg>FROZEN</div>
        </div>
        <div class="card-info">
          <div class="ci-top"><h3>Chased Debit</h3><span class="chip" style="font-size:.72rem"><svg class="ic"><use href="#i-bolt"/></svg> Virtual instantly</span></div>
          <p>Linked to Everyday. Freeze, set limits and replace from the app or *347#.</p>
          <div class="card-controls">
            <div class="cc-row">
              <label class="switch"><input type="checkbox" data-freeze="debit"><span class="tr"></span> Freeze card</label>
              <button class="btn btn-g btn-sm" type="button" data-order="debit">Order physical</button>
            </div>
            <div class="cc-limit">
              <div class="lbl"><span>Daily spend limit</span><output data-limit-out="debit">$2,000</output></div>
              <input type="range" data-limit="debit" min="100" max="10000" step="100" value="2000" aria-label="Debit card daily limit">
            </div>
          </div>
        </div>
      </article>
      <article class="card-item cd-credit reveal" data-card="credit" style="--d:.12s">
        <div class="bankcard3d" role="button" tabindex="0" aria-label="Chased Credit card — activate to flip" aria-pressed="false">
          <div class="bc-inner">
            <div class="bc-face bc-front">
              <div class="bc-top"><span class="bc-brand"><svg class="cmark" viewBox="0 0 64 64" aria-hidden="true"><use href="#chased-mark-mono"/></svg>CHASED<em>.</em></span><span class="bc-type">Credit · Secured</span></div>
              <div class="bc-mid">
                <svg width="38" height="29" viewBox="0 0 42 32" aria-hidden="true"><rect x="1" y="1" width="40" height="30" rx="6" fill="#EAF6EC"/><path d="M1 12h13M28 12h13M1 20h13M28 20h13M14 1v30M28 1v30" stroke="#8A8F84" stroke-width="1.6" fill="none"/></svg>
                <span class="pill ok" data-card-status="credit" style="margin-left:auto">Active</span>
              </div>
              <div class="bc-num" style="margin-top:auto">5399&nbsp;••••&nbsp;••••&nbsp;1177</div>
              <div class="bc-bottom"><span class="bc-holder"><small>CARD HOLDER</small><span data-holder>A. CUSTOMER</span></span><span class="bc-net">MASTERCARD</span></div>
            </div>
            <div class="bc-face bc-back">
              <div class="bc-stripe"></div>
              <div class="bc-cvv"><span>CVV</span><b>•••</b></div>
              <div class="bc-limit-line">DAILY LIMIT · <span data-limit-back="credit">$5,000</span></div>
              <p>Backed by your Vault CD — build US credit history safely, graduate to unsecured after 6 months.</p>
            </div>
          </div>
          <div class="frost"><svg class="ic"><use href="#i-snow"/></svg>FROZEN</div>
        </div>
        <div class="card-info">
          <div class="ci-top"><h3>Chased Credit</h3><span class="chip" style="font-size:.72rem"><svg class="ic"><use href="#i-lock"/></svg> CD-secured</span></div>
          <p>Credit line up to 90% of your Vault CD. Your deposit keeps earning 4.75% while you spend.</p>
          <div class="card-controls">
            <div class="cc-row">
              <label class="switch"><input type="checkbox" data-freeze="credit"><span class="tr"></span> Freeze card</label>
              <button class="btn btn-g btn-sm" type="button" data-order="credit">Order physical</button>
            </div>
            <div class="cc-limit">
              <div class="lbl"><span>Daily spend limit</span><output data-limit-out="credit">$5,000</output></div>
              <input type="range" data-limit="credit" min="100" max="25000" step="100" value="5000" aria-label="Credit card daily limit">
            </div>
          </div>
        </div>
      </article>
      <article class="card-item cd-go reveal" data-card="go" style="--d:.24s">
        <div class="bankcard3d" role="button" tabindex="0" aria-label="Chased Go prepaid card — activate to flip" aria-pressed="false">
          <div class="bc-inner">
            <div class="bc-face bc-front">
              <div class="bc-top"><span class="bc-brand"><svg class="cmark" viewBox="0 0 64 64" aria-hidden="true"><use href="#chased-mark-mono"/></svg>CHASED<em>.</em></span><span class="bc-type">Go · Prepaid</span></div>
              <div class="bc-mid">
                <svg width="38" height="29" viewBox="0 0 42 32" aria-hidden="true"><rect x="1" y="1" width="40" height="30" rx="6" fill="#3AD6C6"/><path d="M1 12h13M28 12h13M1 20h13M28 20h13M14 1v30M28 1v30" stroke="#0E5A52" stroke-width="1.6" fill="none"/></svg>
                <span class="pill ok" data-card-status="go" style="margin-left:auto">Active</span>
              </div>
              <div class="bc-num" style="margin-top:auto">4028&nbsp;••••&nbsp;••••&nbsp;9034</div>
              <div class="bc-bottom"><span class="bc-holder"><small>CARD HOLDER</small><span data-holder>A. CUSTOMER</span></span><span class="bc-net">VISA</span></div>
            </div>
            <div class="bc-face bc-back">
              <div class="bc-stripe"></div>
              <div class="bc-cvv"><span>CVV</span><b>•••</b></div>
              <div class="bc-limit-line">DAILY LIMIT · <span data-limit-back="go">$500</span></div>
              <p>Load only what you plan to spend. Perfect for teens, subscriptions and travel budgets.</p>
            </div>
          </div>
          <div class="frost"><svg class="ic"><use href="#i-snow"/></svg>FROZEN</div>
        </div>
        <div class="card-info">
          <div class="ci-top"><h3>Chased Go</h3><span class="chip" style="font-size:.72rem"><svg class="ic"><use href="#i-wallet"/></svg> Budget-safe</span></div>
          <p>Standalone prepaid — can never overdraft, can never touch your main balance.</p>
          <div class="card-controls">
            <div class="cc-row">
              <label class="switch"><input type="checkbox" data-freeze="go"><span class="tr"></span> Freeze card</label>
              <button class="btn btn-g btn-sm" type="button" data-order="go">Order physical</button>
            </div>
            <div class="cc-limit">
              <div class="lbl"><span>Daily spend limit</span><output data-limit-out="go">$500</output></div>
              <input type="range" data-limit="go" min="50" max="3000" step="50" value="500" aria-label="Prepaid card daily limit">
            </div>
          </div>
        </div>
      </article>
    </div>
  </div>
</section>

<section id="fx">
  <div class="wrap">
    <div class="sec-head reveal">
      <div class="kicker">05 — FX &amp; remittances</div>
      <h2>The dollar rate you see is <em>the rate you get.</em></h2>
      <p>Chased Global holds GBP, EUR, CAD and NGN beside your US dollars. One transparent 0.4% spread. The board below ticks live.</p>
    </div>
    <div class="fx-grid">
      <div class="panel fx-board reveal">
        <div style="display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap">
          <h4><svg class="ic"><use href="#i-globe"/></svg> USD rate board</h4>
          <span class="fx-live"><span class="dot"></span> LIVE · DEMO FEED</span>
        </div>
        <table class="fx">
          <thead><tr><th>Currency</th><th>We buy $</th><th>We sell $</th><th>24h</th></tr></thead>
          <tbody id="fxBody"></tbody>
        </table>
        <p class="fx-note">Mid-market ± 0.4% spread, quoted in USD per unit. Simulated feed for preview.</p>
        <div class="corridors">
          <div class="corr"><div class="flags">🇬🇧 → 🇺🇸</div><b>UK to Dollars</b><span>via Faster Payments</span><br><span class="pill ok">Instant</span></div>
          <div class="corr"><div class="flags">🇪🇺 → 🇺🇸</div><b>Europe to Dollars</b><span>SEPA Instant</span><br><span class="pill info">≤ 1 hour</span></div>
          <div class="corr"><div class="flags">🇨🇦 → 🇺🇸</div><b>Canada to Dollars</b><span>Interac &amp; wire</span><br><span class="pill info">≤ 2 hours</span></div>
        </div>
      </div>
      <div class="panel fx-conv reveal" style="--d:.12s">
        <h4><svg class="ic"><use href="#i-swap"/></svg> Convert currencies</h4>
        <p class="tw-sub">Uses the live board above. Spread already included.</p>
        <div class="field">
          <label for="fxAmt">You send</label>
          <input type="number" class="num-in" id="fxAmt" min="0" step="10" value="200">
        </div>
        <div class="conv-row">
          <div class="field"><label for="fxFrom">From</label>
            <select class="num-in" id="fxFrom"><option selected>GBP</option><option>EUR</option><option>CAD</option><option>NGN</option><option>USD</option></select>
          </div>
          <button id="fxSwap" type="button" aria-label="Swap currencies"><svg class="ic"><use href="#i-swap"/></svg></button>
          <div class="field"><label for="fxTo">To</label>
            <select class="num-in" id="fxTo"><option selected>USD</option><option>GBP</option><option>EUR</option><option>CAD</option><option>NGN</option></select>
          </div>
        </div>
        <div class="conv-out">
          <div style="font-size:.7rem;letter-spacing:.2em;text-transform:uppercase;color:var(--mut)">Recipient gets</div>
          <div class="big" id="fxOut">$0.00</div>
          <div class="rate" id="fxRateLine">—</div>
        </div>
        <div style="display:grid;gap:9px;margin-top:18px">
          <span class="chip"><svg class="ic"><use href="#i-check"/></svg> Hold 5 currencies in one wallet</span>
          <span class="chip"><svg class="ic"><use href="#i-check"/></svg> Lock a rate for 60 seconds at checkout</span>
          <span class="chip"><svg class="ic"><use href="#i-check"/></svg> Outbound wires unlock with full KYC</span>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="digital">
  <div class="wrap">
    <div class="sec-head reveal" style="max-width:760px">
      <div class="kicker">06 — Digital banking</div>
      <h2>One bank. <em>Every screen you own.</em></h2>
      <p>A flagship app, a complete web bank, and *347# for the phone in your other pocket. All three are working demos wired to the same live USD wallet.</p>
    </div>
    <div class="dev-grid">
      <div class="reveal">
        <div class="phone">
          <div class="notch" aria-hidden="true"></div>
          <div class="p-screen">
            <div class="p-status"><span>09:41</span><span>CHASED NET ▮▮▮▮</span></div>
            <div class="p-body">
              <div data-app-panel="home">
                <div class="p-head">
                  <div class="hi">Good morning 👋<b id="appGreet">Chaser</b></div>
                  <div class="p-ava" id="appAva"><svg viewBox="0 0 64 64" style="color:#0B1B2E" aria-hidden="true"><use href="#chased-mark-mono"/></svg></div>
                </div>
                <div class="p-bal-card">
                  <div class="k">Everyday · available</div>
                  <div class="v" data-balance>$12,480.50</div>
                  <div class="row">
                    <button class="p-mini" type="button" id="appTopup"><svg class="ic"><use href="#i-plus"/></svg> Add $500</button>
                    <button class="p-mini" type="button" data-app-goto="send"><svg class="ic"><use href="#i-send"/></svg> Send</button>
                  </div>
                </div>
                <div class="p-sec">Today</div>
                <ul class="p-tx" id="appTx"></ul>
              </div>
              <div data-app-panel="send" hidden>
                <div class="p-sec" style="margin-top:4px">Quick send</div>
                <div class="p-form">
                  <input type="number" class="num-in" id="appSendAmt" placeholder="Amount $" min="1" value="120" aria-label="App send amount">
                  <input type="text" class="num-in" id="appSendTo" placeholder="Beneficiary name" value="Sofia R." aria-label="App send beneficiary">
                  <button class="btn btn-p btn-sm" type="button" id="appSendBtn" style="justify-content:center">Send instantly <svg class="ic"><use href="#i-send"/></svg></button>
                  <p style="font-size:.66rem;color:#7E93AB">Demo wallet · settles in ~4s on RTP/FedNow. Fee $0 during launch.</p>
                </div>
              </div>
              <div data-app-panel="cards" hidden>
                <div class="p-sec" style="margin-top:4px">Your cards</div>
                <div class="p-cardrow"><span class="swatch" style="background:linear-gradient(135deg,#12365E,#7CC0FF)"></span><div><b>Debit · 3401</b><small data-app-card="debit">ACTIVE</small></div><button type="button" data-app-freeze="debit">Freeze</button></div>
                <div class="p-cardrow"><span class="swatch" style="background:linear-gradient(135deg,#3D2E0E,#F5B93E)"></span><div><b>Credit · 1177</b><small data-app-card="credit">ACTIVE</small></div><button type="button" data-app-freeze="credit">Freeze</button></div>
                <div class="p-cardrow"><span class="swatch" style="background:linear-gradient(135deg,#0E3A3F,#3AD6C6)"></span><div><b>Go · 9034</b><small data-app-card="go">ACTIVE</small></div><button type="button" data-app-freeze="go">Freeze</button></div>
                <p style="font-size:.66rem;color:#7E93AB">Synced with the cards section — and with USSD option 4.</p>
              </div>
            </div>
            <div class="p-tabs" role="tablist" aria-label="App screens">
              <button type="button" class="on" data-app-tab="home"><svg class="ic"><use href="#i-home"/></svg>HOME</button>
              <button type="button" data-app-tab="send"><svg class="ic"><use href="#i-send"/></svg>SEND</button>
              <button type="button" data-app-tab="cards"><svg class="ic"><use href="#i-card"/></svg>CARDS</button>
            </div>
          </div>
        </div>
        <p class="dev-cap"><b>CHASED APP</b> · iOS &amp; ANDROID</p>
      </div>
      <div class="dev-web reveal" style="--d:.12s">
        <div class="browser">
          <div class="b-bar">
            <div class="b-dots"><i></i><i></i><i></i></div>
            <span class="b-url"><svg class="cmark" viewBox="0 0 64 64" aria-hidden="true"><use href="#chased-mark-mono"/></svg> online.chased.bank</span>
          </div>
          <div class="b-body">
            <div class="k">Chased Online · Everyday</div>
            <div class="v" data-balance>$12,480.50</div>
            <div class="b-actions">
              <button class="btn btn-p btn-sm" type="button" data-open-account>Open account</button>
              <button class="btn btn-g btn-sm" type="button" id="webPayBtn"><svg class="ic"><use href="#i-bolt"/></svg> Pay electric bill $85</button>
            </div>
          </div>
        </div>
        <ul class="web-feats">
          <li><svg class="ic"><use href="#i-check"/></svg><span><b style="color:var(--ink)">Full feature parity</b> — everything the app does, in any browser.</span></li>
          <li><svg class="ic"><use href="#i-check"/></svg><span><b style="color:var(--ink)">Session security</b> — device binding, 2FA, auto-lock after 3 minutes idle.</span></li>
          <li><svg class="ic"><use href="#i-check"/></svg><span><b style="color:var(--ink)">Tiered KYC</b> — phone + email opens Tier 1 in 2 minutes; SSN/ID unlocks $50k+ limits.</span></li>
          <li><svg class="ic"><use href="#i-check"/></svg><span><b style="color:var(--ink)">Real-time alerts</b> — push, SMS and email on every debit.</span></li>
        </ul>
      </div>
      <div class="reveal" style="--d:.24s">
        <div class="fphone" id="ussdWrap" tabindex="0" aria-label="USSD simulator. Dial star 3 4 7 hash.">
          <div class="fp-screen" id="ussdScreen" role="log" aria-live="polite"></div>
          <button class="fp-dial" type="button" id="ussdDial">📞 Dial *347#</button>
          <div class="fp-keys" id="ussdKeys">
            <button class="fp-key" type="button" data-key="1">1<small>&nbsp;</small></button>
            <button class="fp-key" type="button" data-key="2">2<small>ABC</small></button>
            <button class="fp-key" type="button" data-key="3">3<small>DEF</small></button>
            <button class="fp-key" type="button" data-key="4">4<small>GHI</small></button>
            <button class="fp-key" type="button" data-key="5">5<small>JKL</small></button>
            <button class="fp-key" type="button" data-key="6">6<small>MNO</small></button>
            <button class="fp-key" type="button" data-key="7">7<small>PQRS</small></button>
            <button class="fp-key" type="button" data-key="8">8<small>TUV</small></button>
            <button class="fp-key" type="button" data-key="9">9<small>WXYZ</small></button>
            <button class="fp-key" type="button" data-key="*">*<small>&nbsp;</small></button>
            <button class="fp-key" type="button" data-key="0">0<small>+</small></button>
            <button class="fp-key" type="button" data-key="#">#<small>&nbsp;</small></button>
            <button class="fp-key util" type="button" data-key="C">C<small>CLEAR</small></button>
            <button class="fp-key send" type="button" data-key="SEND">SEND ↵<small>&nbsp;</small></button>
            <button class="fp-key util" type="button" data-key="BACK">⌫<small>DEL</small></button>
          </div>
          <p class="fp-hint">MENUS: TAP A NUMBER · AMOUNTS: TYPE + SEND<br>NO DATA? NO PROBLEM. SAME BANK.</p>
        </div>
        <p class="dev-cap"><b>*347#</b> · WORKS ON ANY PHONE</p>
      </div>
    </div>
  </div>
</section>

<section id="more">
  <div class="wrap">
    <div class="sec-head reveal">
      <div class="kicker">07 — The ecosystem</div>
      <h2>Beyond the account: <em>invest, cover, get paid.</em></h2>
      <p>Phase 3 rolls out to Chased customers first. Join a waitlist and you'll be first through the door.</p>
    </div>
    <div class="more-grid">
      <div class="panel more-card mc-invest reveal">
        <svg class="more-spark" viewBox="0 0 130 50" aria-hidden="true"><polyline points="0,42 18,36 36,38 54,26 72,28 90,16 108,18 130,6" fill="none" stroke="#1E6FE0" stroke-width="2.5" stroke-linecap="round"/></svg>
        <div class="big-ic"><svg class="ic"><use href="#i-chart"/></svg></div>
        <h3>Chased Invest</h3>
        <p>US Treasury bills, brokerage CDs and curated index funds — from $100, straight inside the app.</p>
        <div class="stat-line">T-BILL 52-WK · <b>4.6%</b> indicative</div>
        <button class="btn btn-g btn-sm" type="button" data-waitlist="Invest"><span>Join waitlist</span> <svg class="ic"><use href="#i-arrow-r"/></svg></button>
      </div>
      <div class="panel more-card mc-cover reveal" style="--d:.12s">
        <div class="big-ic"><svg class="ic"><use href="#i-umbrella"/></svg></div>
        <h3>Chased Cover</h3>
        <p>Health, device and term-life micro-insurance from regulated partners. Claims tracked in-app.</p>
        <div class="stat-line">PLANS FROM · <b>$9/mo</b></div>
        <button class="btn btn-g btn-sm" type="button" data-waitlist="Cover"><span>Join waitlist</span> <svg class="ic"><use href="#i-arrow-r"/></svg></button>
      </div>
      <div class="panel more-card mc-pay reveal" style="--d:.24s">
        <div class="big-ic"><svg class="ic"><use href="#i-bag"/></svg></div>
        <h3>Chased Pay · Merchants</h3>
        <p>Tap-to-pay terminals, payment links and storefront checkout. Next-day settlement, one flat fee.</p>
        <div class="stat-line">FLAT RATE · <b>1.9%</b> · no rental fees</div>
        <button class="btn btn-g btn-sm" type="button" data-waitlist="Pay"><span>Join waitlist</span> <svg class="ic"><use href="#i-arrow-r"/></svg></button>
      </div>
    </div>
  </div>
</section>

<!-- ============ CONTACT HUB ============ -->
<section id="contact">
  <div class="wrap">
    <div class="sec-head reveal">
      <div class="kicker">08 — Contact us</div>
      <h2>One number. <em>Every channel you use.</em></h2>
      <p>Call, WhatsApp, Signal or Telegram — all reach the same Chased support desk on <b>+1 (302) 713-0106</b>. We're open <b>Monday to Friday, 9:00 AM – 6:00 PM (ET)</b>. Messages sent outside hours are answered next business morning.</p>
    </div>
    <div class="contact-grid">
      <div class="reveal">
        <div class="msg-grid">
          <a class="msg-btn msg-call" href="tel:+13027130106">
            <span class="mic"><svg class="ic"><use href="#i-tel"/></svg></span>
            <span><small>DIRECT CALL</small><b>+1 (302) 713-0106</b></span>
          </a>
          <a class="msg-btn msg-wa" href="https://wa.me/+13027130106" target="_blank" rel="noopener">
            <span class="mic"><svg class="ic"><use href="#i-wa"/></svg></span>
            <span><small>WHATSAPP MESSAGE</small><b>+1 (302) 713-0106</b></span>
          </a>
          <a class="msg-btn msg-sig" href="https://signal.me/#p/+13027130106" target="_blank" rel="noopener">
            <span class="mic"><svg class="ic"><use href="#i-sig"/></svg></span>
            <span><small>SIGNAL · ENCRYPTED</small><b>+1 (302) 713-0106</b></span>
          </a>
          <a class="msg-btn msg-tg" href="https://t.me/+13027130106" target="_blank" rel="noopener">
            <span class="mic"><svg class="ic"><use href="#i-tg"/></svg></span>
            <span><small>TELEGRAM CHAT</small><b>+1 (302) 713-0106</b></span>
          </a>
        </div>
        <div class="contact-lines">
          <a href="mailto:chasedbank56@gmail.com"><svg class="ic"><use href="#i-mail"/></svg> chasedbank56@gmail.com</a>
          <a href="#leadership"><svg class="ic"><use href="#i-pin"/></svg> 256 Chapman Road STE, Orlando, Florida, USA</a>
        </div>
      </div>
      <div class="panel hours-card reveal" style="--d:.12s">
        <h4><svg class="ic"><use href="#i-clock"/></svg> Opening hours</h4>
        <div class="h-row"><span>Monday</span><b>9:00 AM – 6:00 PM</b></div>
        <div class="h-row"><span>Tuesday</span><b>9:00 AM – 6:00 PM</b></div>
        <div class="h-row"><span>Wednesday</span><b>9:00 AM – 6:00 PM</b></div>
        <div class="h-row"><span>Thursday</span><b>9:00 AM – 6:00 PM</b></div>
        <div class="h-row"><span>Friday</span><b>9:00 AM – 6:00 PM</b></div>
        <div class="h-row closed"><span>Saturday</span><b>Closed</b></div>
        <div class="h-row closed"><span>Sunday</span><b>Closed</b></div>
        <p class="h-note">All times Eastern (ET). The app, web bank and *347# work 24/7 — only human support keeps office hours. Lost or stolen card? Freeze it instantly in-app or via *347# option 4, any time.</p>
      </div>
    </div>
  </div>
</section>

<section id="leadership">
  <div class="wrap">
    <div class="lead-panel reveal">
      <div class="ceo-portrait" id="ceoPortrait">
        <div class="ring" aria-hidden="true"></div>
        <!-- CEO PHOTO: Save your portrait as ceo.jpg in the same folder as this file -->
        <img class="ceo-photo" alt="Robbin Mack Darius, Founder & CEO of Chased Bank" src="ceo.jpg">
        <span class="ceo-badge">FOUNDER &amp; CEO</span>
      </div>
      <div class="lead-copy">
        <div class="kicker">09 — Leadership</div>
        <h2>ROBBIN MACK DARIUS</h2>
        <div class="role">Founder &amp; Chief Executive Officer</div>
        <p class="lead-quote">"A bank should never be the reason you slow down. We built Chased so that <b>opening an account takes two minutes</b>, a transfer takes four seconds, and the simplest phone in the room still gets the fullest bank in the country."</p>
        <span class="lead-sig">Robbin Mack Darius</span>
        <div class="lead-chips">
          <span class="chip"><svg class="ic"><use href="#i-star"/></svg> 15+ years in payments &amp; fintech</span>
          <span class="chip"><svg class="ic"><use href="#i-pin"/></svg> HQ: 256 Chapman Road STE, Orlando, Florida</span>
          <span class="chip"><svg class="ic"><use href="#i-tel"/></svg> +1 (302) 713-0106 · Mon–Fri</span>
          <span class="chip"><svg class="ic"><use href="#i-mail"/></svg> chasedbank56@gmail.com</span>
        </div>
      </div>
    </div>
    <div class="roles reveal">
      <div class="role-card"><div><b>Chief Financial Officer</b><small>Search underway</small></div><a class="btn btn-g btn-sm" href="mailto:chasedbank56@gmail.com?subject=CFO%20role%20application">Apply</a></div>
      <div class="role-card"><div><b>Chief Technology Officer</b><small>Search underway</small></div><a class="btn btn-g btn-sm" href="mailto:chasedbank56@gmail.com?subject=CTO%20role%20application">Apply</a></div>
      <div class="role-card"><div><b>Chief Risk Officer</b><small>Search underway</small></div><a class="btn btn-g btn-sm" href="mailto:chasedbank56@gmail.com?subject=CRO%20role%20application">Apply</a></div>
    </div>
  </div>
</section>

<section id="faq">
  <div class="wrap">
    <div class="sec-head reveal">
      <div class="kicker">10 — Questions</div>
      <h2>Straight answers, <em>no fine-print ambush.</em></h2>
    </div>
    <div class="faq-list reveal">
      <div class="faq-item">
        <button class="faq-q" type="button" aria-expanded="false">Is Chased Bank live today? <svg class="ic"><use href="#i-chev"/></svg></button>
        <div class="faq-a"><div><p>Chased Bank is a launch-stage venture headquartered at 256 Chapman Road STE, Orlando, Florida. Banking services go live once licensing is completed. Join the newsletter, call +1 (302) 713-0106, or email chasedbank56@gmail.com to hear first.</p></div></div>
      </div>
      <div class="faq-item">
        <button class="faq-q" type="button" aria-expanded="false">What does it cost to open and run an account? <svg class="ic"><use href="#i-chev"/></svg></button>
        <div class="faq-a"><div><p>$0 to open, $0 monthly, $0 minimum balance, $0 card maintenance. Transfers are free during launch. FX carries one 0.4% spread. That's the whole price list — in plain US dollars.</p></div></div>
      </div>
      <div class="faq-item">
        <button class="faq-q" type="button" aria-expanded="false">How does *347# work without internet? <svg class="ic"><use href="#i-chev"/></svg></button>
        <div class="faq-a"><div><p>USSD runs over your mobile network's signalling channel — the same one calls use — so it works on any handset with a signal, no data, no app. Check balances, transfer, top up and freeze your card in seconds. Try the simulator above.</p></div></div>
      </div>
      <div class="faq-item">
        <button class="faq-q" type="button" aria-expanded="false">What do I need to open an account? <svg class="ic"><use href="#i-chev"/></svg></button>
        <div class="faq-a"><div><p>Just a phone number, email and your name for Tier 1 ($500 daily limit). Add SSN/government ID and proof of address for Tier 3 with $50k+ limits, outbound wires and credit products. Upgrade entirely in-app.</p></div></div>
      </div>
      <div class="faq-item">
        <button class="faq-q" type="button" aria-expanded="false">How is my money and data protected? <svg class="ic"><use href="#i-chev"/></svg></button>
        <div class="faq-a"><div><p>256-bit encryption in transit and at rest, device-bound sessions, 2FA on every login, instant card freeze, and real-time alerts on every debit. Deposits will sit under the applicable federal deposit-insurance scheme once licensed. We never sell your data.</p></div></div>
      </div>
      <div class="faq-item">
        <button class="faq-q" type="button" aria-expanded="false">What if something goes wrong with a transfer? <svg class="ic"><use href="#i-chev"/></svg></button>
        <div class="faq-a"><div><p>Failed-but-debited transfers auto-reverse within 24 hours — watch the dispute timeline in-app. Human support answers <b>Monday–Friday, 9:00 AM–6:00 PM (ET)</b> via call, WhatsApp, Signal or Telegram on +1 (302) 713-0106, or chasedbank56@gmail.com. Outside hours, message us and we reply next business morning. Card emergencies: freeze instantly in-app or *347#, 24/7.</p></div></div>
      </div>
    </div>
  </div>
</section>

<section class="cta-band" aria-label="Get started">
  <div class="wrap">
    <div class="cta-inner reveal">
      <svg class="cta-logo" viewBox="0 0 64 64" aria-hidden="true"><use href="#chased-mark"/></svg>
      <h2>Start <em>the chase.</em></h2>
      <p>Two minutes, one phone number, zero fees. Your Chased USD account number is waiting on the other side of this button.</p>
      <div class="cta-actions">
        <button class="btn btn-p" type="button" data-open-account>Open free account <svg class="ic"><use href="#i-arrow-r"/></svg></button>
        <a class="store-btn" href="tel:+13027130106"><svg class="ic"><use href="#i-tel"/></svg><span><small>Call · Mon–Fri</small><b>+1 (302) 713-0106</b></span></a>
        <a class="store-btn" href="https://wa.me/+13027130106" target="_blank" rel="noopener"><svg class="ic"><use href="#i-wa"/></svg><span><small>WhatsApp</small><b>Message us</b></span></a>
        <a class="store-btn" href="mailto:chasedbank56@gmail.com"><svg class="ic"><use href="#i-mail"/></svg><span><small>Email us</small><b>chasedbank56@gmail.com</b></span></a>
      </div>
    </div>
  </div>
</section>

</main>

<footer>
  <div class="wrap">
    <div class="f-grid">
      <div class="f-brand">
        <a class="brand" href="#home">
          <svg viewBox="0 0 64 64" width="36" height="36" aria-hidden="true"><use href="#chased-mark"/></svg>
          <span class="wordmark">CHASED<em>.</em></span>
        </a>
        <p>For everyone chasing more. Building the fastest honest bank in America — all accounts in USD.</p>
        <div class="f-social">
          <a href="tel:+13027130106" aria-label="Call us"><svg class="ic"><use href="#i-tel"/></svg></a>
          <a href="https://wa.me/+13027130106" target="_blank" rel="noopener" aria-label="WhatsApp"><svg class="ic"><use href="#i-wa"/></svg></a>
          <a href="https://signal.me/#p/+13027130106" target="_blank" rel="noopener" aria-label="Signal"><svg class="ic"><use href="#i-sig"/></svg></a>
          <a href="https://t.me/+13027130106" target="_blank" rel="noopener" aria-label="Telegram"><svg class="ic"><use href="#i-tg"/></svg></a>
          <a href="mailto:chasedbank56@gmail.com" aria-label="Email"><svg class="ic"><use href="#i-mail"/></svg></a>
        </div>
      </div>
      <div class="f-col">
        <h5>Products</h5>
        <a href="#accounts">Everyday · Grow · Vault</a>
        <a href="#payments">Payments &amp; transfers</a>
        <a href="#loans">Loans &amp; credit</a>
        <a href="#cards">Cards</a>
        <a href="#fx">Chased Global FX</a>
        <a href="#more">Invest · Cover · Pay</a>
      </div>
      <div class="f-col">
        <h5>Company</h5>
        <a href="#leadership">Leadership</a>
        <a href="mailto:chasedbank56@gmail.com?subject=Careers%20at%20Chased%20Bank">Careers</a>
        <a href="mailto:chasedbank56@gmail.com?subject=Press%20inquiry">Press</a>
        <a href="#contact">Contact</a>
      </div>
      <div class="f-col">
        <h5>Headquarters &amp; support</h5>
        <address><svg class="ic" style="color:var(--blue)"><use href="#i-pin"/></svg> 256 Chapman Road STE<br>Orlando, Florida, USA</address>
        <a href="tel:+13027130106"><svg class="ic" style="color:var(--blue)"><use href="#i-tel"/></svg> +1 (302) 713-0106</a>
        <a href="https://wa.me/+13027130106" target="_blank" rel="noopener"><svg class="ic" style="color:var(--blue)"><use href="#i-wa"/></svg> WhatsApp · same number</a>
        <a href="https://signal.me/#p/+13027130106" target="_blank" rel="noopener"><svg class="ic" style="color:var(--blue)"><use href="#i-sig"/></svg> Signal · same number</a>
        <a href="https://t.me/+13027130106" target="_blank" rel="noopener"><svg class="ic" style="color:var(--blue)"><use href="#i-tg"/></svg> Telegram · same number</a>
        <a href="mailto:chasedbank56@gmail.com"><svg class="ic" style="color:var(--blue)"><use href="#i-mail"/></svg> chasedbank56@gmail.com</a>
        <div class="f-hours">MON–FRI · 9:00 AM – 6:00 PM ET</div>
      </div>
      <div class="f-col nl">
        <h5>Launch updates</h5>
        <p>One email a month. Rates, corridors, launch dates. No spam, unsubscribe anytime.</p>
        <form class="nl-form" id="nlForm" novalidate>
          <input type="email" id="nlEmail" placeholder="you@email.com" aria-label="Email for launch updates">
          <button class="btn btn-p btn-sm" type="submit" aria-label="Subscribe"><svg class="ic"><use href="#i-send"/></svg></button>
        </form>
        <div id="nlMsg" role="status"></div>
      </div>
    </div>
    <div class="f-bottom">
      <span>© <span id="year">2026</span> Chased Bank Ltd. · 256 Chapman Road STE, Orlando, Florida · Founder &amp; CEO: Robbin Mack Darius</span>
      <span class="mono">*347# · +1 (302) 713-0106 · MON–FRI · USD</span>
    </div>
    <p class="f-disc">Chased Bank is a launch-stage venture; this website is a product preview running on simulated data. All balances, rates, APYs, returns and statistics shown are illustrative, quoted in US dollars, and do not constitute an offer of banking services or investment advice. Banking services will be provided subject to licensing and regulatory approval. Deposit protection applies as prescribed by the applicable federal deposit-insurance scheme once licensed. Human support hours: Monday–Friday, 9:00 AM–6:00 PM Eastern. Chased Bank is an independent concept and is not affiliated with, endorsed by, or connected to JPMorgan Chase &amp; Co., Chase Bank, or Chase Corporation; all logos and marks on this site are original to Chased Bank.</p>
  </div>
</footer>

<div id="modal" role="dialog" aria-modal="true" aria-labelledby="mTitle">
  <div class="m-scrim" data-mclose></div>
  <div class="m-card">
    <div class="m-top">
      <h3 id="mTitle"><svg class="cmark" viewBox="0 0 64 64" aria-hidden="true"><use href="#chased-mark-mono"/></svg>Open your account</h3>
      <button class="m-close" type="button" data-mclose aria-label="Close"><svg class="ic"><use href="#i-x"/></svg></button>
    </div>
    <div class="m-dots" aria-hidden="true"><i class="on"></i><i></i><i></i></div>
    <div class="m-view on" data-mview="1">
      <p class="m-sub">Step 1 of 3 — pick your starting account. You can add the others later in one tap.</p>
      <div class="type-opts">
        <label class="type-opt"><input type="radio" name="mtype" value="everyday"><span class="radio"></span><span><b>Chased Everyday</b><small>Checking · zero fees · free virtual Visa debit</small></span><span class="rate-tag">1.00% APY</span></label>
        <label class="type-opt"><input type="radio" name="mtype" value="grow" checked><span class="radio"></span><span><b>Chased Grow</b><small>Savings · goal pockets · daily compounding</small></span><span class="rate-tag">4.35% APY</span></label>
        <label class="type-opt"><input type="radio" name="mtype" value="vault"><span class="radio"></span><span><b>Chased Vault</b><small>CD · 3–12 months · from $1,000</small></span><span class="rate-tag">4.75% APY</span></label>
      </div>
      <div class="m-actions"><button class="btn btn-p" type="button" id="mNext1">Continue <svg class="ic"><use href="#i-arrow-r"/></svg></button></div>
    </div>
    <div class="m-view" data-mview="2">
      <p class="m-sub">Step 2 of 3 — Tier 1 KYC. Two minutes, no paperwork.</p>
      <form class="m-form" id="mForm" novalidate>
        <div class="f-field" data-f="name"><label for="fName">Full name</label><input type="text" class="num-in" id="fName" placeholder="e.g. Jordan Rivera" autocomplete="name"><div class="f-err">Please enter your full name (at least 3 characters).</div></div>
        <div class="f-field" data-f="email"><label for="fEmail">Email</label><input type="email" class="num-in" id="fEmail" placeholder="you@email.com" autocomplete="email"><div class="f-err">That email doesn't look right.</div></div>
        <div class="f-field" data-f="phone"><label for="fPhone">Phone number</label><input type="tel" class="num-in" id="fPhone" placeholder="(302) 713-0106" autocomplete="tel"><div class="f-err">Enter a valid US number — 10 digits, e.g. (302) 713-0106.</div></div>
        <div class="f-field" data-f="state"><label for="fState">State of residence</label>
          <select class="num-in" id="fState"><option value="">Select state…</option><option selected>Florida</option><option>Delaware</option><option>New York</option><option>California</option><option>Texas</option><option>Georgia</option><option>Illinois</option><option>New Jersey</option><option>Pennsylvania</option><option>Other</option></select>
          <div class="f-err">Pick your state so we can route your account correctly.</div></div>
        <div class="m-actions"><button class="btn btn-g" type="button" id="mBack2">Back</button><button class="btn btn-p" type="submit">Review <svg class="ic"><use href="#i-arrow-r"/></svg></button></div>
      </form>
    </div>
    <div class="m-view" data-mview="3">
      <p class="m-sub">Step 3 of 3 — check it, tick it, done.</p>
      <div class="rv-box">
        <div class="rv-row"><span>Account</span><b id="rvType">Chased Grow</b></div>
        <div class="rv-row"><span>Name</span><b id="rvName">—</b></div>
        <div class="rv-row"><span>Email</span><b id="rvEmail">—</b></div>
        <div class="rv-row"><span>Phone</span><b id="rvPhone">—</b></div>
        <div class="rv-row"><span>State</span><b id="rvState">—</b></div>
        <div class="rv-row"><span>Currency</span><b>USD ($)</b></div>
        <div class="rv-row"><span>Fees</span><b style="color:var(--success)">$0 open · $0 monthly</b></div>
      </div>
      <label class="terms"><input type="checkbox" id="mTerms"><span>I agree to the <a href="#faq" data-mclose>preview terms</a> and understand this creates a demo Tier 1 account on the Chased preview platform.</span></label>
      <div class="m-actions"><button class="btn btn-g" type="button" id="mBack3">Back</button><button class="btn btn-p" type="button" id="mCreate">Create my account <svg class="ic"><use href="#i-bolt"/></svg></button></div>
    </div>
    <div class="m-view" data-mview="success">
      <div class="ok-wrap">
        <svg class="ok-check" viewBox="0 0 84 84" aria-hidden="true"><circle cx="42" cy="42" r="39"/><path d="M27 43l11 11 20-22"/></svg>
        <h4>You're in the chase.</h4>
        <p class="m-sub">Welcome, <b id="okName" style="color:var(--ink)">Chaser</b>. Your <b id="okType" style="color:var(--blue2)">Chased Grow</b> USD account is open.</p>
        <div class="acct-no-box">
          <div class="k">Your account number</div>
          <div class="no" id="okNo">34•• ••• ••••</div>
          <button class="btn btn-g btn-sm" type="button" data-copy-no><svg class="ic"><use href="#i-copy"/></svg> Copy number</button>
        </div>
        <p class="ok-meta">Tier 1 · $500 daily limit until ID verification · Dial <b>*347#</b> · Support Mon–Fri: <b>+1 (302) 713-0106</b> (call / WhatsApp / Signal / Telegram) · <b>chasedbank56@gmail.com</b></p>
        <div class="m-actions">
          <button class="btn btn-g" type="button" id="okSave"><svg class="ic"><use href="#i-download"/></svg> Save details</button>
          <button class="btn btn-p" type="button" id="okDone">Explore your bank <svg class="ic"><use href="#i-arrow-r"/></svg></button>
        </div>
        <button id="okReset" type="button">Reset demo &amp; open a different account</button>
      </div>
    </div>
  </div>
</div>

<div id="toasts" aria-live="polite"></div>
<div id="confetti" aria-hidden="true"></div>
<button id="toTop" type="button" aria-label="Back to top"><svg class="ic"><use href="#i-top"/></svg></button>

<noscript><div style="position:fixed;inset:auto 0 0 0;background:#F5B93E;color:#221604;padding:12px;text-align:center;font-weight:700;z-index:999">Enable JavaScript to use the live demos — the full product story is above.</div></noscript>

<script>
(function(){
"use strict";
const $=(s,c)=>(c||document).querySelector(s), $$=(s,c)=>[...(c||document).querySelectorAll(s)];
const RM=matchMedia('(prefers-reduced-motion: reduce)').matches;
const FINE=matchMedia('(pointer: fine)').matches;
const store={get(k){try{return JSON.parse(localStorage.getItem(k))}catch(e){return null}},set(k,v){try{localStorage.setItem(k,JSON.stringify(v))}catch(e){}},del(k){try{localStorage.removeItem(k)}catch(e){}}};
const S={balance:12480.50,tx:[{label:'From Marcus T.',amt:1250,t:'09:12'},{label:'Phone bill — Verizon',amt:-45,t:'08:47'},{label:'To Sofia R.',amt:-120,t:'08:15'},{label:'Grow interest',amt:29.84,t:'06:00'}],frozen:{debit:false,credit:false,go:false},limits:{debit:2000,credit:5000,go:500},ordered:{},account:store.get('chased.account')||null};
const NAMES=['Sofia R.','Marcus T.','Ava P.','James K.','Maya L.','Daniel O.','Grace W.','Ethan B.'];
const lookup=d=>{const s=String(d).split('').reduce((a,x)=>a+(+x||0),0);return NAMES[s%NAMES.length]};
const now=()=>new Date().toLocaleTimeString('en-US',{hour:'2-digit',minute:'2-digit'});
const F={usd:v=>'$'+Number(v).toLocaleString('en-US',{minimumFractionDigits:2,maximumFractionDigits:2}),usd0:v=>'$'+Math.round(v).toLocaleString('en-US')};
const toasts=$('#toasts');
function toast(msg,type='info'){const icons={success:'i-check',danger:'i-alert',warn:'i-alert',info:'i-info'};const el=document.createElement('div');el.className='toast '+type;el.innerHTML='<svg class="ic"><use href="#'+(icons[type]||'i-info')+'"/></svg><span></span>';el.lastElementChild.textContent=msg;toasts.appendChild(el);while(toasts.children.length>4)toasts.firstElementChild.remove();setTimeout(()=>{el.classList.add('out');setTimeout(()=>el.remove(),320)},3800)}
function renderBalance(){$$('[data-balance]').forEach(el=>{el.textContent=F.usd(S.balance);el.classList.remove('pulse');void el.offsetWidth;el.classList.add('pulse')})}
function renderTx(){const ul=$('#appTx');if(!ul)return;ul.innerHTML='';S.tx.slice(0,4).forEach(t=>{const li=document.createElement('li');const inn=t.amt>0;li.innerHTML='<span class="tic '+(inn?'in':'out')+'"><svg class="ic"><use href="#'+(inn?'i-plus':'i-send')+'"/></svg></span><span class="tl"><b></b><small></small></span><span class="ta '+(inn?'pos':'')+'"></span>';li.querySelector('b').textContent=t.label;li.querySelector('small').textContent=t.t;li.querySelector('.ta').textContent=(inn?'+':'−')+F.usd(Math.abs(t.amt));ul.appendChild(li)})}
function commitTx(label,amt){S.balance=Math.round((S.balance+amt)*100)/100;S.tx.unshift({label,amt,t:now()});if(S.tx.length>12)S.tx.pop();renderBalance();renderTx()}
function canSpend(a){if(!(a>0)){toast('Enter a valid amount first.','warn');return false}if(a>S.balance){toast('Insufficient demo balance — top up in the app mockup.','danger');return false}return true}
const CARD_NAMES={debit:'Debit',credit:'Credit',go:'Go prepaid'};
function setFrozen(card,frozen,opts={}){S.frozen[card]=frozen;$$('[data-card="'+card+'"] .bankcard3d').forEach(el=>el.classList.toggle('frozen',frozen));if(card==='debit'){const hc=$('#heroCard3d');if(hc)hc.classList.toggle('frozen',frozen)}$$('[data-card-status="'+card+'"]').forEach(p=>{p.textContent=frozen?'Frozen':'Active';p.className='pill '+(frozen?'bad':'ok')});$$('[data-freeze="'+card+'"]').forEach(i=>i.checked=frozen);$$('[data-app-card="'+card+'"]').forEach(s=>{s.textContent=frozen?'FROZEN ❄':'ACTIVE';s.style.color=frozen?'#FF8A80':''});$$('[data-app-freeze="'+card+'"]').forEach(b=>b.textContent=frozen?'Unfreeze':'Freeze');if(!opts.quiet)toast(CARD_NAMES[card]+' card '+(frozen?'frozen — all transactions declined.':'unfrozen — ready to spend.'),frozen?'info':'success')}
$$('[data-freeze]').forEach(i=>i.addEventListener('change',()=>setFrozen(i.dataset.freeze,i.checked)));
$$('[data-app-freeze]').forEach(b=>b.addEventListener('click',()=>setFrozen(b.dataset.appFreeze,!S.frozen[b.dataset.appFreeze])));
function paintRange(r){const p=(r.value-r.min)/(r.max-r.min)*100;r.style.setProperty('--fill',p+'%')}
$$('[data-limit]').forEach(r=>{paintRange(r);r.addEventListener('input',()=>{const c=r.dataset.limit;S.limits[c]=+r.value;paintRange(r);$$('[data-limit-out="'+c+'"]').forEach(o=>o.textContent=F.usd0(+r.value));$$('[data-limit-back="'+c+'"]').forEach(o=>o.textContent=F.usd0(+r.value))})});
$$('[data-order]').forEach(b=>b.addEventListener('click',()=>{const c=b.dataset.order;if(S.ordered[c])return;S.ordered[c]=true;b.textContent='Ordered ✓';b.disabled=true;toast('Physical '+CARD_NAMES[c]+' card ordered — arrives in 3–5 business days.','success')}));
$$('.bankcard3d').forEach(el=>{const flip=()=>{el.classList.toggle('flipped');el.setAttribute('aria-pressed',el.classList.contains('flipped'))};el.addEventListener('click',flip);el.addEventListener('keydown',e=>{if(e.key==='Enter'||e.key===' '){e.preventDefault();flip()}})});
const tw={amt:$('#twAmt'),bank:$('#twBank'),acct:$('#twAcct'),chip:$('#twNameChip'),chipTxt:$('#twNameTxt'),send:$('#twSend'),steps:$('#twSteps'),done:$('#twDone'),busy:false,timers:[],resolveT:null,name:''};
$$('[data-qa]').forEach(b=>b.addEventListener('click',()=>{tw.amt.value=b.dataset.qa;tw.amt.classList.remove('invalid')}));
tw.acct.addEventListener('input',()=>{tw.acct.value=tw.acct.value.replace(/\D/g,'').slice(0,10);tw.acct.classList.remove('invalid');clearTimeout(tw.resolveT);if(tw.acct.value.length===10){tw.chip.className='name-chip show resolving';tw.chip.firstElementChild.innerHTML='<use href="#i-refresh"/>';tw.chipTxt.textContent='Resolving name…';tw.resolveT=setTimeout(()=>{tw.name=lookup(tw.acct.value);tw.chip.className='name-chip show';tw.chip.firstElementChild.innerHTML='<use href="#i-check"/>';tw.chipTxt.textContent=tw.name+' · verified'},RM?0:550)}else{tw.chip.className='name-chip';tw.name=''}});
function markInvalid(el){el.classList.remove('invalid');void el.offsetWidth;el.classList.add('invalid');el.focus()}
tw.send.addEventListener('click',()=>{if(tw.busy)return;const amt=Math.round((+tw.amt.value||0)*100)/100;if(!(amt>=1)){markInvalid(tw.amt);toast('Minimum transfer is $1.','warn');return}if(amt>S.balance){markInvalid(tw.amt);toast('Insufficient demo balance. Add $500 in the app mockup.','danger');return}if(tw.acct.value.length!==10){markInvalid(tw.acct);toast('Account number must be exactly 10 digits.','warn');return}const name=tw.name||lookup(tw.acct.value),bank=tw.bank.value;tw.busy=true;tw.send.disabled=true;tw.send.classList.add('loading');tw.done.classList.remove('show');tw.steps.classList.add('show');const lis=$$('li',tw.steps);lis.forEach(l=>l.className='');$('#twStep3').textContent='Delivered to '+bank;tw.timers.forEach(clearTimeout);tw.timers=[];[0,1,2].forEach((idx,k)=>{tw.timers.push(setTimeout(()=>{lis.forEach(l=>l.classList.remove('doing'));if(idx>0)lis[idx-1].classList.add('done');lis[idx].classList.add('doing');if(idx===2){tw.timers.push(setTimeout(()=>{lis[2].classList.remove('doing');lis[2].classList.add('done');commitTx('To '+name,-amt);addHistory(name,bank,amt);$('#rcAmt').textContent=F.usd(amt);$('#rcTo').textContent=name+' · '+tw.acct.value;$('#rcBank').textContent=bank;$('#rcRef').textContent='CB'+Date.now().toString().slice(-9);$('#rcTime').textContent=new Date().toLocaleString('en-US',{day:'2-digit',month:'short',hour:'2-digit',minute:'2-digit'});tw.done.classList.add('show');tw.send.disabled=false;tw.send.classList.remove('loading');tw.busy=false;toast(F.usd(amt)+' delivered to '+name+' · '+bank,'success')},RM?0:520))}},RM?0:450+k*620))})});
$('#twAgain').addEventListener('click',()=>{tw.done.classList.remove('show');tw.steps.classList.remove('show');$$('li',tw.steps).forEach(l=>l.className='');tw.acct.value='';tw.chip.className='name-chip';tw.name='';tw.amt.focus()});
$('#twShare').addEventListener('click',()=>{copyText('CHASED BANK RECEIPT\nAmount: '+$('#rcAmt').textContent+'\nTo: '+$('#rcTo').textContent+'\nBank: '+$('#rcBank').textContent+'\nRef: '+$('#rcRef').textContent+'\nTime: '+$('#rcTime').textContent+'\nStatus: DELIVERED ✓\nSupport (Mon–Fri): +1 (302) 713-0106 · chasedbank56@gmail.com','Receipt copied to clipboard.')});
const histList=$('#transferHistory');
function histRow(h){const li=document.createElement('li');li.innerHTML='<span class="avatar"></span><span class="who"><b></b><small></small></span><span class="amt"></span>';li.querySelector('.avatar').textContent=h.name.split(' ').map(x=>x[0]).join('').slice(0,2);li.querySelector('b').textContent=h.name;li.querySelector('small').textContent=h.bank+' · '+h.t;li.querySelector('.amt').textContent='−'+F.usd0(h.amt);return li}
[{name:'Sofia R.',bank:'Chase',amt:120,t:'Yesterday'},{name:'James K.',bank:'Cash App',amt:45,t:'Tuesday'},{name:'Maya L.',bank:'Bank of America',amt:300,t:'Monday'}].forEach(h=>histList.appendChild(histRow(h)));
function addHistory(name,bank,amt){histList.prepend(histRow({name,bank,amt,t:'Just now'}));while(histList.children.length>5)histList.lastElementChild.remove()}
function copyText(txt,okMsg){const done=()=>toast(okMsg||'Copied.','success');if(navigator.clipboard&&navigator.clipboard.writeText){navigator.clipboard.writeText(txt).then(done).catch(fb)}else fb();function fb(){const ta=document.createElement('textarea');ta.value=txt;ta.style.position='fixed';ta.style.opacity='0';document.body.appendChild(ta);ta.select();try{document.execCommand('copy');done()}catch(e){toast('Copy not available.','warn')}ta.remove()}}
const ACCTS={everyday:{title:'Chased Everyday sweep',rate:.01,tenors:[90]},grow:{title:'Chased Grow projection',rate:.0435,tenors:[90,180,365]},vault:{title:'Chased Vault CD projection',rates:{90:.0410,180:.0440,270:.0455,365:.0475},tenors:[90,180,270,365]}};
const sv={prod:'grow',amt:10000,days:365};const svAmt=$('#svAmt'),svAmtN=$('#svAmtN');
function svTenorChips(){const box=$('#svTenors');box.innerHTML='';ACCTS[sv.prod].tenors.forEach(d=>{const b=document.createElement('button');b.type='button';b.className='tchip'+(d===sv.days?' on':'');b.textContent=Math.round(d/30.42)+' months';b.addEventListener('click',()=>{sv.days=d;svTenorChips();svCalc()});box.appendChild(b)})}
function svCalc(){const cfg=ACCTS[sv.prod];const rate=cfg.rates?cfg.rates[sv.days]:cfg.rate;const total=sv.amt*Math.pow(1+rate,sv.days/365);const interest=total-sv.amt;$('#svCalcTitle').textContent=cfg.title;$('#svRate').textContent=(rate*100).toFixed(2)+'% APY';$('#svInterest').textContent=F.usd(interest);$('#svTotal').textContent=F.usd(total);$$('#svChart .bar').forEach((bar,i)=>{const f=(i+1)/6;bar.style.height=Math.max(8,f*100)+'%';bar.title='Day '+Math.round(sv.days*f)+': '+F.usd0(sv.amt+interest*f)});$('#svAmtOut').textContent=F.usd0(sv.amt);paintRange(svAmt)}
svAmt.addEventListener('input',()=>{sv.amt=+svAmt.value;svAmtN.value=sv.amt;svCalc()});
svAmtN.addEventListener('input',()=>{let v=+svAmtN.value||0;v=Math.min(Math.max(v,0),1000000);sv.amt=v;svAmt.value=Math.min(Math.max(v,500),250000);svCalc()});
$$('[data-acct]').forEach(tab=>tab.addEventListener('click',()=>{sv.prod=tab.dataset.acct;$$('[data-acct]').forEach(t=>t.setAttribute('aria-selected',t===tab?'true':'false'));$$('[data-acct-panel]').forEach(p=>{p.hidden=p.dataset.acctPanel!==sv.prod;if(!p.hidden)p.classList.add('in')});const cfg=ACCTS[sv.prod];if(!cfg.tenors.includes(sv.days))sv.days=cfg.tenors[cfg.tenors.length-1];svTenorChips();svCalc()}));
svTenorChips();svCalc();
const ln={amt:$('#lnAmt'),tenor:$('#lnTenor'),i:.0149};
function lnCalc(){const P=+ln.amt.value,n=+ln.tenor.value;const emi=P*ln.i/(1-Math.pow(1+ln.i,-n));const total=emi*n,interest=total-P;$('#lnAmtOut').textContent=F.usd0(P);$('#lnTenorOut').textContent=n+(n===1?' month':' months');$('#lnMonthly').textContent=F.usd(emi);$('#lnInterest').textContent=F.usd(interest);$('#lnTotal').textContent=F.usd(total);$('#lnApr').textContent=((Math.pow(1+ln.i,12)-1)*100).toFixed(1)+'%';const C=2*Math.PI*48,f=interest/total;$('#lnDonutInt').setAttribute('stroke-dasharray',(f*C).toFixed(1)+' '+C.toFixed(1));$('#lnDonutPct').textContent=Math.round(f*100)+'%';paintRange(ln.amt);paintRange(ln.tenor);eligCalc()}
ln.amt.addEventListener('input',lnCalc);ln.tenor.addEventListener('input',lnCalc);
$('#lnMinus').addEventListener('click',()=>{ln.tenor.value=Math.max(1,+ln.tenor.value-1);lnCalc()});
$('#lnPlus').addEventListener('click',()=>{ln.tenor.value=Math.min(24,+ln.tenor.value+1);lnCalc()});
const incAmt=$('#incAmt'),salaryT=$('#salaryT');
function eligCalc(){const inc=+incAmt.value,n=+ln.tenor.value,sal=salaryT.checked;const cap=sal?100000:5000;const lim=Math.min(cap,Math.round(inc*(sal?.35:.12)*n/500)*500);$('#incOut').textContent=F.usd0(inc);$('#eligOut').textContent=F.usd0(lim);const pill=$('#eligPill');pill.textContent=sal?'Pre-qualified':'Basic tier';pill.className='pill '+(sal?'ok':'warn');paintRange(incAmt)}
incAmt.addEventListener('input',eligCalc);salaryT.addEventListener('change',eligCalc);lnCalc();
const FXC={GBP:{mid:1.2730,color:'#9A6B00',flag:'🇬🇧',sym:'£',dec:4},EUR:{mid:1.0845,color:'#1E6FE0',flag:'🇪🇺',sym:'€',dec:4},CAD:{mid:0.7315,color:'#0E7C86',flag:'🇨🇦',sym:'C$',dec:4},NGN:{mid:0.000676,color:'#0B7A42',flag:'🇳🇬',sym:'₦',dec:6}};
Object.values(FXC).forEach(c=>{c.hist=Array.from({length:24},(_,i)=>c.mid*(1+Math.sin(i*.6)*.002))});
const fxBody=$('#fxBody');
function sparkPoints(h){const mn=Math.min(...h),mx=Math.max(...h),sp=(mx-mn)||1;return h.map((v,i)=>(i*(100/23)).toFixed(1)+','+(24-((v-mn)/sp)*20).toFixed(1)).join(' ')}
Object.entries(FXC).forEach(([code,c])=>{const tr=document.createElement('tr');tr.dataset.fx=code;tr.innerHTML='<td><span class="cur">'+c.flag+' '+code+'<span class="trend up" data-trend>▲</span></span></td><td data-buy></td><td data-sell></td><td><svg class="spark" viewBox="0 0 100 26" preserveAspectRatio="none"><polyline data-spark fill="none" stroke="'+c.color+'" stroke-width="2" stroke-linecap="round" points="'+sparkPoints(c.hist)+'"/></svg></td>';fxBody.appendChild(tr)});
function paintFx(flash){Object.entries(FXC).forEach(([code,c])=>{const tr=$('[data-fx="'+code+'"]',fxBody);if(!tr)return;const prev=c.prev||c.mid;$('[data-buy]',tr).textContent=(c.mid*.996).toFixed(c.dec);$('[data-sell]',tr).textContent=(c.mid*1.004).toFixed(c.dec);const t=$('[data-trend]',tr),up=c.mid>=prev;t.textContent=up?'▲':'▼';t.className='trend '+(up?'up':'dn');$('[data-spark]',tr).setAttribute('points',sparkPoints(c.hist));if(flash&&!RM){tr.classList.remove('flash-up','flash-dn');void tr.offsetWidth;tr.classList.add(up?'flash-up':'flash-dn');setTimeout(()=>tr.classList.remove('flash-up','flash-dn'),900)}c.prev=c.mid})}
paintFx(false);
const fxAmt=$('#fxAmt'),fxFrom=$('#fxFrom'),fxTo=$('#fxTo');
function fxCalc(){const amt=+fxAmt.value||0,from=fxFrom.value,to=fxTo.value;const mid=c=>c==='USD'?1:FXC[c].mid;const sym=c=>c==='USD'?'$':FXC[c].sym;let out=amt*mid(from)/mid(to);if(from!==to)out*=.996;$('#fxOut').textContent=sym(to)+out.toLocaleString('en-US',{minimumFractionDigits:2,maximumFractionDigits:2});if(from===to){$('#fxRateLine').textContent='Same currency — nothing to convert.'}else{const u=(mid(from)/mid(to))*.996;$('#fxRateLine').textContent='1 '+from+' = '+sym(to)+u.toLocaleString('en-US',{minimumFractionDigits:2,maximumFractionDigits:6})+' · 0.4% spread included'}}
[fxAmt,fxFrom,fxTo].forEach(el=>el.addEventListener('input',fxCalc));
$('#fxSwap').addEventListener('click',function(){const a=fxFrom.value;fxFrom.value=fxTo.value;fxTo.value=a;this.classList.toggle('spin');fxCalc()});
fxCalc();
setInterval(()=>{if(document.hidden)return;Object.values(FXC).forEach(c=>{c.mid=+(c.mid*(1+(Math.random()-.5)*.003)).toFixed(6);c.hist.push(c.mid);c.hist.shift()});paintFx(true);fxCalc()},4000);
function appTab(n){$$('[data-app-tab]').forEach(b=>b.classList.toggle('on',b.dataset.appTab===n));$$('[data-app-panel]').forEach(p=>p.hidden=p.dataset.appPanel!==n)}
$$('[data-app-tab]').forEach(b=>b.addEventListener('click',()=>appTab(b.dataset.appTab)));
$$('[data-app-goto]').forEach(b=>b.addEventListener('click',()=>appTab(b.dataset.appGoto)));
$('#appTopup').addEventListener('click',()=>{commitTx('Card top-up',500);toast('$500 added to your demo wallet.','success')});
$('#appSendBtn').addEventListener('click',()=>{const amt=Math.round((+$('#appSendAmt').value||0)*100)/100;const to=$('#appSendTo').value.trim()||'Beneficiary';if(!canSpend(amt))return;commitTx('To '+to,-amt);addHistory(to,'Chased instant',amt);toast(F.usd(amt)+' sent to '+to+' — delivered in 3.9s','success');appTab('home')});
$('#webPayBtn').addEventListener('click',()=>{if(!canSpend(85))return;commitTx('Electric bill — OUC',-85);toast('Electric bill paid · $85.00 · receipt sent to email.','success')});
const U={mode:'idle',buf:'',tmp:{},t:null};const uScreen=$('#ussdScreen');
function uRender(lines){uScreen.innerHTML='';lines.forEach(l=>{const d=document.createElement('div');d.className='ul'+(l.cls?' '+l.cls:'');d.textContent=l.txt;uScreen.appendChild(d)});uScreen.scrollTop=uScreen.scrollHeight}
function uCursorLine(txt){const d=document.createElement('div');d.className='ul';d.textContent=txt;const c=document.createElement('span');c.className='cursor';d.appendChild(c);uScreen.appendChild(d)}
const HEAD={txt:'CHASED BANK · *347#',cls:'head'},FOOT={txt:'0 Back   # End session',cls:'dim'};
function uIdle(){U.mode='idle';U.buf='';U.tmp={};uRender([{txt:'CHASED USSD',cls:'head'},{txt:'Dial *347# to begin.',cls:'dim'}]);uCursorLine('> ')}
function uGo(m){clearTimeout(U.t);uRender([HEAD,{txt:'Connecting…',cls:'dim'}]);U.t=setTimeout(()=>{U.mode=m;U.buf='';uScreenFor(m)},RM?0:300)}
function uScreenFor(m){switch(m){
case 'menu':uRender([HEAD,{txt:'Welcome, Chaser.'},{txt:'1. Check balance'},{txt:'2. Transfer money'},{txt:'3. Phone top-up'},{txt:'4. Block / unblock card'},{txt:'0. Exit',cls:'dim'}]);break;
case 'balance':uRender([HEAD,{txt:'Everyday · 4821***3401'},{txt:'Balance: '+F.usd(S.balance)},{txt:'Grow: '+F.usd(8250)},{txt:'Vault CD: '+F.usd(20000),cls:'dim'},FOOT]);break;
case 'tAmt':uRender([HEAD,{txt:'TRANSFER — enter amount ($), then press SEND:'},{txt:'Bal: '+F.usd(S.balance),cls:'dim'}]);uCursorLine('$ ');break;
case 'tPhone':uRender([HEAD,{txt:'Enter beneficiary phone / acct, then SEND:'},{txt:'Amount: '+F.usd(U.tmp.amt),cls:'dim'}]);uCursorLine('> ');break;
case 'tConfirm':uRender([HEAD,{txt:'Send '+F.usd(U.tmp.amt)},{txt:'to '+U.tmp.name+' ('+U.tmp.phone+')?'},{txt:'Fee: $0.00'},{txt:'1. Confirm'},{txt:'2. Cancel',cls:'dim'}]);break;
case 'airtime':uRender([HEAD,{txt:'PHONE TOP-UP — self'},{txt:'1. $5    2. $10'},{txt:'3. $25   4. $50'},FOOT]);break;
case 'block':uRender([HEAD,{txt:'Debit ···· 3401 is '+(S.frozen.debit?'FROZEN ❄':'ACTIVE ✓')},{txt:S.frozen.debit?'1. Unfreeze card':'1. Freeze card'},{txt:'2. Report lost/stolen',cls:'dim'},FOOT]);break;
case 'tDone':uRender([HEAD,{txt:'✓ Sent '+F.usd(U.tmp.amt)},{txt:'to '+U.tmp.name},{txt:'Ref: CB'+Date.now().toString().slice(-8)},{txt:'New bal: '+F.usd(S.balance),cls:'dim'},FOOT]);break;
case 'aDone':uRender([HEAD,{txt:'✓ Top-up '+F.usd(U.tmp.air)+' sent'},{txt:'New bal: '+F.usd(S.balance),cls:'dim'},FOOT]);break;
case 'bDone':uRender([HEAD,{txt:'✓ Card '+(S.frozen.debit?'frozen. Declining all spend.':'unfrozen. Ready to use.')},FOOT]);break;
case 'err':uRender([HEAD,{txt:'✗ '+U.tmp.err,cls:'dim'},FOOT]);break;
case 'end':uRender([{txt:'Session ended.',cls:'dim'},{txt:'Dial *347# anytime.',cls:'dim'},{txt:'Press any key…',cls:'dim'}]);break}}
function uType(k){if(k==='C')U.buf='';else if(k==='BACK')U.buf=U.buf.slice(0,-1);else if(U.buf.length<14)U.buf+=k}
function ussdKey(k){clearTimeout(U.t);const m=U.mode;
if(m==='idle'){if(k==='SEND'){if(U.buf==='*347#')uGo('menu');else{uRender([{txt:'CHASED USSD',cls:'head'},{txt:'Invalid code.',cls:'dim'},{txt:'Try *347#',cls:'dim'}]);uCursorLine('> ')}return}if(k==='C'||k==='BACK'||/^[0-9*#]$/.test(k)){uType(k);uRender([{txt:'CHASED USSD',cls:'head'},{txt:'Dial *347# to begin.',cls:'dim'}]);uCursorLine('> '+U.buf);if(U.buf==='*347#')uGo('menu')}return}
if(m==='end'){uIdle();return}
if(m==='menu'){if(k==='1')uGo('balance');else if(k==='2')uGo('tAmt');else if(k==='3')uGo('airtime');else if(k==='4')uGo('block');else if(k==='0'||k==='#')uGo('end');return}
if(m==='tAmt'||m==='tPhone'){if(k==='SEND'){if(m==='tAmt'){const amt=Math.round((+U.buf||0)*100)/100;if(!(amt>=1)){uRender([HEAD,{txt:'✗ Enter at least $1.',cls:'dim'}]);uCursorLine('$ ');U.buf='';return}if(amt>S.balance){U.tmp.err='Insufficient funds.';U.mode='err';uScreenFor('err');return}U.tmp.amt=amt;uGo('tPhone')}else{if(U.buf.replace(/\D/g,'').length<10){uRender([HEAD,{txt:'✗ Need 10–11 digits.',cls:'dim'}]);uCursorLine('> ');U.buf='';return}U.tmp.phone=U.buf;U.tmp.name=lookup(U.buf);uGo('tConfirm')}return}if(k==='#'){uGo('end');return}if(k==='0'&&U.buf===''){uGo('menu');return}if(k==='C'||k==='BACK'||/^[0-9]$/.test(k)){uType(k);if(m==='tAmt'){uRender([HEAD,{txt:'TRANSFER — enter amount ($), then press SEND:'},{txt:'Bal: '+F.usd(S.balance),cls:'dim'}]);uCursorLine('$ '+U.buf)}else{uRender([HEAD,{txt:'Enter beneficiary phone / acct, then SEND:'},{txt:'Amount: '+F.usd(U.tmp.amt),cls:'dim'}]);uCursorLine('> '+U.buf)}}return}
if(m==='tConfirm'){if(k==='1'){commitTx('USSD → '+U.tmp.name,-U.tmp.amt);addHistory(U.tmp.name,'USSD *347#',U.tmp.amt);uGo('tDone')}else if(k==='2'||k==='0')uGo('menu');else if(k==='#')uGo('end');return}
if(m==='airtime'){const map={'1':5,'2':10,'3':25,'4':50};if(map[k]){if(!canSpend(map[k])){U.tmp.err='Insufficient funds.';U.mode='err';uScreenFor('err');return}U.tmp.air=map[k];commitTx('Phone top-up',-map[k]);uGo('aDone')}else if(k==='0')uGo('menu');else if(k==='#')uGo('end');return}
if(m==='block'){if(k==='1'){setFrozen('debit',!S.frozen.debit,{quiet:true});uGo('bDone')}else if(k==='2'){U.tmp.err='Line flagged. Call +1 (302) 713-0106 (Mon–Fri).';U.mode='err';uScreenFor('err')}else if(k==='0')uGo('menu');else if(k==='#')uGo('end');return}
if(k==='0')uGo('menu');else if(k==='#')uGo('end')}
$$('#ussdKeys .fp-key').forEach(b=>b.addEventListener('click',()=>ussdKey(b.dataset.key)));
$('#ussdDial').addEventListener('click',()=>{U.buf='*347#';uGo('menu')});
$('#ussdWrap').addEventListener('keydown',e=>{if(/^[0-9*#]$/.test(e.key)){e.preventDefault();ussdKey(e.key)}else if(e.key==='Enter'){e.preventDefault();ussdKey('SEND')}else if(e.key==='Backspace'){e.preventDefault();ussdKey('BACK')}else if(e.key==='Escape')ussdKey('C')});
uIdle();
const modal=$('#modal'),mCard=$('.m-card',modal);const TYPE_LABEL={everyday:'Chased Everyday',grow:'Chased Grow',vault:'Chased Vault'};
let lastFocus=null,draft={},creating=false;const dots=$$('.m-dots i',modal);
function mView(v){$$('[data-mview]',modal).forEach(x=>x.classList.toggle('on',x.dataset.mview===String(v)));const idx=v==='success'?3:+v;dots.forEach((d,i)=>d.classList.toggle('on',i<idx));$('#mTitle').innerHTML='<svg class="cmark" viewBox="0 0 64 64" aria-hidden="true"><use href="#chased-mark-mono"/></svg>'+(v==='success'?'Account opened ✓':'Open your account');mCard.scrollTop=0;const f=$('[data-mview="'+v+'"] input, [data-mview="'+v+'"] button',modal);if(f)setTimeout(()=>f.focus(),60)}
function openModal(){lastFocus=document.activeElement;modal.classList.add('open');document.body.classList.add('locked');if(S.account){fillSuccess();mView('success')}else mView(1)}
function closeModal(){if(creating)return;modal.classList.remove('open');document.body.classList.remove('locked');if(lastFocus)lastFocus.focus()}
$$('[data-open-account]').forEach(b=>b.addEventListener('click',()=>{closeMenu();openModal()}));
$$('[data-mclose]',modal).forEach(b=>b.addEventListener('click',closeModal));
document.addEventListener('keydown',e=>{if(!modal.classList.contains('open'))return;if(e.key==='Escape')closeModal();if(e.key==='Tab'){const f=$$('button,input,select,a[href]',mCard).filter(el=>el.offsetParent!==null&&!el.disabled);if(!f.length)return;const first=f[0],last=f[f.length-1];if(e.shiftKey&&document.activeElement===first){e.preventDefault();last.focus()}else if(!e.shiftKey&&document.activeElement===last){e.preventDefault();first.focus()}}});
$('#mNext1').addEventListener('click',()=>{draft.type=($('input[name="mtype"]:checked',modal)||{}).value||'grow';mView(2)});
$('#mBack2').addEventListener('click',()=>mView(1));$('#mBack3').addEventListener('click',()=>mView(2));
function fieldErr(n,bad){const f=$('[data-f="'+n+'"]',modal);f.classList.toggle('invalid',bad);return !bad}
$('#mForm').addEventListener('submit',e=>{e.preventDefault();const name=$('#fName').value.trim(),email=$('#fEmail').value.trim(),phone=$('#fPhone').value.replace(/[\s\-().]/g,''),state=$('#fState').value;let ok=true;ok=fieldErr('name',name.length<3)&&ok;ok=fieldErr('email',!/^[^\s@]+@[^\s@]+\.[^\s@]{2,}$/.test(email))&&ok;const pd=phone.replace(/^\+/,'');ok=fieldErr('phone',!(/^(\d{10}|1\d{10})$/.test(pd)))&&ok;ok=fieldErr('state',!state)&&ok;if(!ok){toast('Fix the highlighted fields to continue.','warn');return}draft={...draft,name,email,phone,state};$('#rvType').textContent=TYPE_LABEL[draft.type];$('#rvName').textContent=name;$('#rvEmail').textContent=email;$('#rvPhone').textContent=phone;$('#rvState').textContent=state;mView(3)});
$('#mCreate').addEventListener('click',function(){if(!$('#mTerms').checked){toast('Tick the terms box to create your account.','warn');return}creating=true;this.classList.add('loading');this.disabled=true;setTimeout(()=>{const no='34'+String(Math.floor(10000000+Math.random()*89999999));S.account={...draft,no,date:new Date().toISOString()};store.set('chased.account',S.account);creating=false;this.classList.remove('loading');this.disabled=false;fillSuccess();mView('success');applyAccount();confetti();toast('Welcome to the chase, '+S.account.name.split(' ')[0]+'! Account '+no+' is live.','success')},RM?50:1000)});
function fillSuccess(){if(!S.account)return;$('#okName').textContent=S.account.name.split(' ')[0];$('#okType').textContent=TYPE_LABEL[S.account.type]||'Chased';$('#okNo').textContent=S.account.no.replace(/(\d{4})(\d{3})(\d{3})/,'$1 $2 $3')}
function applyAccount(){const chip=$('#acctChip');if(S.account){chip.classList.add('show');$('#acctChipTxt').textContent='•••• '+S.account.no.slice(-4);$$('[data-holder]').forEach(el=>el.textContent=S.account.name.toUpperCase().slice(0,22));$('#appGreet').textContent=S.account.name.split(' ')[0];$('#appAva').textContent=S.account.name.split(' ').map(x=>x[0]).join('').slice(0,2).toUpperCase()}else{chip.classList.remove('show');$$('[data-holder]').forEach(el=>el.textContent='A. CUSTOMER');$('#appGreet').textContent='Chaser';$('#appAva').innerHTML='<svg viewBox="0 0 64 64" style="color:#0B1B2E" aria-hidden="true"><use href="#chased-mark-mono"/></svg>'}}
$('#acctChip').addEventListener('click',openModal);
$$('[data-copy-no]').forEach(b=>b.addEventListener('click',()=>{if(S.account)copyText(S.account.no,'Account number copied.')}));
$('#okSave').addEventListener('click',()=>{if(!S.account)return;const a=S.account;const txt='CHASED BANK — ACCOUNT DETAILS\n================================\nHolder: '+a.name+'\nAccount: '+a.no+'\nProduct: '+(TYPE_LABEL[a.type]||a.type)+'\nCurrency: USD ($)\nTier: 1 ($500 daily limit)\nEmail: '+a.email+'\nPhone: '+a.phone+'\nState: '+a.state+'\nOpened: '+new Date(a.date).toLocaleString('en-US')+'\nUSSD: *347#\nHQ: 256 Chapman Road STE, Orlando, Florida\nSupport (Mon–Fri 9AM–6PM ET): +1 (302) 713-0106\nCall · WhatsApp · Signal · Telegram — same number\nEmail: chasedbank56@gmail.com\n\nPreview account — illustrative, not a live bank offer.';const blob=new Blob([txt],{type:'text/plain'});const url=URL.createObjectURL(blob);const link=document.createElement('a');link.href=url;link.download='chased-account-'+a.no+'.txt';document.body.appendChild(link);link.click();link.remove();setTimeout(()=>URL.revokeObjectURL(url),2000);toast('Account details saved as .txt','success')});
$('#okDone').addEventListener('click',closeModal);
$('#okReset').addEventListener('click',()=>{S.account=null;store.del('chased.account');applyAccount();$('#mTerms').checked=false;mView(1);toast('Demo reset — open a fresh account.','info')});
applyAccount();
function confetti(){if(RM)return;const layer=$('#confetti');const r=mCard.getBoundingClientRect();const cx=r.left+r.width/2,cy=r.top+r.height/3;const colors=['#1E6FE0','#F5B93E','#0E7C86','#7CC0FF','#0B7A42','#FF6B5E'];for(let i=0;i<30;i++){const s=document.createElement('span');const size=5+Math.random()*7;s.style.cssText='left:'+cx+'px;top:'+cy+'px;width:'+size+'px;height:'+size*(Math.random()>.5?1:.45)+'px;background:'+colors[i%colors.length]+';border-radius:'+(Math.random()>.5?'50%':'2px');layer.appendChild(s);const dx=(Math.random()-.5)*440,up=-(90+Math.random()*180),down=140+Math.random()*260,rot=(Math.random()-.5)*720;s.animate([{transform:'translate(0,0) rotate(0deg)',opacity:1},{transform:'translate('+dx*.6+'px,'+up+'px) rotate('+rot*.5+'deg)',opacity:1,offset:.45},{transform:'translate('+dx+'px,'+down+'px) rotate('+rot+'deg)',opacity:0}],{duration:1000+Math.random()*600,easing:'cubic-bezier(.2,.7,.3,1)'}).onfinish=()=>s.remove()}}
$$('[data-waitlist]').forEach(b=>b.addEventListener('click',()=>{if(b.classList.contains('joined'))return;b.classList.add('joined');b.querySelector('span').textContent='On the list ✓';toast("You're on the Chased "+b.dataset.waitlist+' waitlist — first in line at launch.','success')}));
$('#nlForm').addEventListener('submit',e=>{e.preventDefault();const em=$('#nlEmail').value.trim(),msg=$('#nlMsg');if(!/^[^\s@]+@[^\s@]+\.[^\s@]{2,}$/.test(em)){msg.style.color='var(--danger)';msg.textContent='Enter a valid email to subscribe.';return}msg.style.color='var(--success)';msg.textContent='✓ Subscribed — see you at launch.';$('#nlEmail').value='';toast('Launch updates locked in for '+em,'success')});
$$('.faq-item').forEach(item=>{const q=$('.faq-q',item);q.addEventListener('click',()=>{const open=item.classList.contains('open');$$('.faq-item.open').forEach(o=>{o.classList.remove('open');$('.faq-q',o).setAttribute('aria-expanded','false')});if(!open){item.classList.add('open');q.setAttribute('aria-expanded','true')}})});
const nav=$('#siteNav'),menuBtn=$('#menuBtn'),mPanel=$('#mPanel'),progress=$('#progress'),toTop=$('#toTop');
function closeMenu(){mPanel.classList.remove('open');menuBtn.setAttribute('aria-expanded','false');menuBtn.innerHTML='<svg class="ic"><use href="#i-menu"/></svg>'}
menuBtn.addEventListener('click',()=>{const open=!mPanel.classList.contains('open');mPanel.classList.toggle('open',open);menuBtn.setAttribute('aria-expanded',open);menuBtn.innerHTML='<svg class="ic"><use href="#'+(open?'i-x':'i-menu')+'"/></svg>'});
$$('a',mPanel).forEach(a=>a.addEventListener('click',closeMenu));
addEventListener('resize',()=>{if(innerWidth>940)closeMenu()});
let ticking=false;
addEventListener('scroll',()=>{if(ticking)return;ticking=true;requestAnimationFrame(()=>{const y=scrollY,h=document.documentElement.scrollHeight-innerHeight;progress.style.width=(h>0?(y/h)*100:0)+'%';nav.classList.toggle('scrolled',y>8);toTop.classList.toggle('show',y>600);ticking=false})},{passive:true});
toTop.addEventListener('click',()=>scrollTo({top:0,behavior:RM?'auto':'smooth'}));
const spy=new IntersectionObserver(es=>{es.forEach(en=>{if(en.isIntersecting)$$('[data-nav]').forEach(a=>a.classList.toggle('active',a.getAttribute('href')==='#'+en.target.id))})},{rootMargin:'-40% 0px -55% 0px'});
['accounts','payments','loans','cards','fx','digital','contact','leadership'].forEach(id=>{const el=document.getElementById(id);if(el)spy.observe(el)});
const rio=new IntersectionObserver(es=>{es.forEach(en=>{if(en.isIntersecting){en.target.classList.add('in');rio.unobserve(en.target)}})},{threshold:.12,rootMargin:'0px 0px -6%'});
$$('.reveal').forEach(el=>rio.observe(el));
const cio=new IntersectionObserver(es=>{es.forEach(en=>{if(!en.isIntersecting)return;cio.unobserve(en.target);const el=en.target,target=+el.dataset.count,dec=+(el.dataset.dec||0),pre=el.dataset.prefix||'',suf=el.dataset.suffix||'';if(RM){el.textContent=pre+target.toFixed(dec)+suf;return}const t0=performance.now(),dur=1400;(function step(t){const p=Math.min(1,(t-t0)/dur),e=1-Math.pow(1-p,3);el.textContent=pre+(target*e).toFixed(dec)+suf;if(p<1)requestAnimationFrame(step)})(t0)})},{threshold:.6});
$$('[data-count]').forEach(el=>cio.observe(el));
const heroVis=$('#heroVis'),heroCard=$('#heroCard3d');
if(FINE&&!RM&&heroVis&&heroCard){let tx=0,ty=0,cx=0,cy=0;heroVis.addEventListener('pointermove',e=>{const r=heroVis.getBoundingClientRect();tx=((e.clientX-r.left)/r.width-.5)*14;ty=-((e.clientY-r.top)/r.height-.5)*12});heroVis.addEventListener('pointerleave',()=>{tx=0;ty=0});(function loop(){cx+=(tx-cx)*.08;cy+=(ty-cy)*.08;heroCard.style.transform='rotateY('+cx.toFixed(2)+'deg) rotateX('+cy.toFixed(2)+'deg)';requestAnimationFrame(loop)})()}
const track=$('#tickerTrack');const dup=document.createElement('span');dup.style.display='contents';dup.setAttribute('aria-hidden','true');dup.innerHTML=track.innerHTML;track.appendChild(dup);
$('#year').textContent=new Date().getFullYear();
renderBalance();renderTx();
$$('input[type=range]').forEach(paintRange);
})();
</script>
</body>
</html>
