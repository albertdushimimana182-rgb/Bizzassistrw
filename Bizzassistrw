<!DOCTYPE html>
<html lang="rw">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>BizzAssist Rwanda</title>
<link rel="manifest" href="manifest.webmanifest">
<meta name="theme-color" content="#0b3d2d">
<meta name="mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="apple-mobile-web-app-title" content="BizzAssist">
<link rel="icon" type="image/png" href="icon-192.png">
<link rel="apple-touch-icon" href="icon-192.png">
<style>
:root{--bg:#04120d;--cd:#0a2019;--ln:#17463a;--g:#00e070;--tx:#f2fbf7;--mu:#9fbdb0;--rd:#ff4d4d;--am:#f5a524;--fd:#06190f;--bl:#1d8cff}
body.light{--bg:#eef6f2;--cd:#fff;--ln:#cfe3d9;--tx:#0b2a20;--mu:#5b7a6c;--fd:#f3faf6}
*{box-sizing:border-box;margin:0;padding:0;-webkit-tap-highlight-color:transparent}
body{background:var(--bg);color:var(--tx);font:14px system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;padding-bottom:calc(86px + env(safe-area-inset-bottom,0px))}
.mu{color:var(--mu)}.pos{color:var(--g)}.neg{color:#ff8a8a}
.top{display:flex;align-items:center;gap:10px;padding:12px 14px;padding-top:calc(12px + env(safe-area-inset-top,0px));background:linear-gradient(100deg,#0b3d2d,#0a2a21 60%,#07150f);color:#f2fbf7;border-bottom:1px solid var(--ln)}
.logo{width:40px;height:40px;border-radius:12px;background:transparent;display:grid;place-items:center;font-size:20px;flex:none;overflow:hidden}
.logo img{width:100%;height:100%;object-fit:cover;display:block}
.top h1,.brand h1{font-size:18px;line-height:1.1}.top h1 span,.brand h1 span{color:var(--g)}
.top p,.brand p{font-size:11.5px;color:#b9d8cb}
.sp{flex:1}
.usr{display:flex;align-items:center;gap:6px;font-weight:600;background:#0d241d;border-radius:20px;padding:4px 12px 4px 4px}
.usr b{width:28px;height:28px;border-radius:50%;background:#12a85a;display:grid;place-items:center}
.wrap{max-width:560px;margin:0 auto;padding:0 12px}
.hd{display:flex;align-items:center;gap:10px;padding:14px 2px 10px}
.hd>a{color:var(--g);font-size:26px;text-decoration:none;line-height:1}
.hd h2{font-size:21px}.hd p{font-size:12px;color:var(--mu)}
.hb{margin-left:auto;background:var(--g);color:#03150c;border:0;border-radius:12px;padding:10px 14px;font:700 13.5px system-ui;cursor:pointer}
.c{background:var(--cd);border:1px solid var(--ln);border-radius:14px;padding:13px;margin-bottom:12px}
.c h3{font-size:15.5px;margin-bottom:10px;display:flex;justify-content:space-between;align-items:center}
.g2{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-bottom:12px}
.g2>.btn{margin:0}
.s{display:flex;align-items:center;gap:10px;background:var(--cd);border:1px solid var(--ln);border-radius:14px;padding:11px;cursor:pointer}
.s i{font-style:normal;width:40px;height:40px;border-radius:12px;background:#0f3a2e;display:grid;place-items:center;font-size:20px;flex:none}
.s small{font-size:11.5px;color:var(--mu);display:block}.s b{font-size:15.5px;display:block}.s em{font-style:normal;font-size:11px;color:var(--g)}
.btn{width:100%;height:46px;border:0;border-radius:13px;background:var(--g);color:#03150c;font:700 15px system-ui;cursor:pointer;margin-bottom:10px}
.btn.o{background:transparent;border:1.5px solid var(--g);color:var(--tx)}
.btn.d{border-color:var(--rd);color:var(--rd)}
input,select,textarea{width:100%;padding:11px 12px;border-radius:11px;border:1px solid var(--ln);background:var(--fd);color:var(--tx);font:14.5px system-ui;outline:none;margin-bottom:10px}
input:focus,select:focus,textarea:focus{border-color:var(--g)}
label{display:block;font-size:12px;color:var(--mu);margin:0 0 4px 2px}
.tabs{display:flex;gap:6px;overflow-x:auto;margin:6px 0 10px}
.tab{white-space:nowrap;padding:8px 14px;border-radius:10px;border:1px solid var(--ln);background:transparent;color:var(--mu);font:600 13px system-ui;cursor:pointer}
.tab.on{background:#0f8a4f;color:#fff;border-color:#0f8a4f}
.row{display:flex;align-items:center;gap:10px;padding:9px;background:var(--cd);border:1px solid var(--ln);border-radius:14px;margin-bottom:8px;cursor:pointer}
.c .row{background:none;border:0;border-bottom:1px solid var(--ln);border-radius:0;margin:0}
.em{width:44px;height:44px;border-radius:10px;background:#e9f4ee;display:grid;place-items:center;font-size:22px;flex:none}
.m{flex:1;min-width:0}.m b{display:block;font-size:13.5px}.m small{font-size:11.5px;color:var(--mu)}
.r{text-align:right}.r b{font-size:13.5px;display:block}.r small{font-size:11px;color:var(--mu)}
.bd{display:inline-block;font-size:10.5px;font-weight:600;padding:3px 9px;border-radius:10px;margin-top:3px}
.in{background:rgba(0,224,112,.2);color:var(--g)}
.low{background:var(--am);color:#2b1c00}
.out{background:rgba(255,77,77,.22);color:var(--rd)}
.opt{display:grid;grid-template-columns:repeat(auto-fit,minmax(88px,1fr));gap:8px}
.op{padding:10px 4px;border-radius:11px;border:1px solid var(--ln);background:transparent;color:var(--tx);font:600 12.5px system-ui;cursor:pointer}
.op.on{background:#0c4a31;border-color:var(--g);color:var(--g)}
.add,.ib{border:1.5px solid var(--g);background:transparent;color:var(--g);border-radius:10px;padding:7px 12px;font:600 13px system-ui;cursor:pointer}
.q{display:flex;align-items:center;border:1px solid var(--ln);border-radius:9px}
.q button{width:28px;height:28px;border:0;background:none;color:var(--g);font-size:17px;cursor:pointer}
.q span{min-width:20px;text-align:center}
.tt{display:flex;justify-content:space-between;padding:5px 0}
.tt.big{border-top:1px solid var(--ln);margin-top:6px;padding-top:9px;color:var(--g);font-weight:700;font-size:17px}
.it{display:grid;grid-template-columns:1fr 34px 76px 84px;gap:4px;font-size:12.5px;padding:7px 0;border-bottom:1px solid var(--ln)}
.it span:nth-child(n+2){text-align:right}.it.h{color:var(--mu);font-size:11.5px}
.ok{text-align:center;padding:18px;background:linear-gradient(135deg,#0c3a2c,#0a241d);border:1px solid #1b6a4b;border-radius:14px;margin-bottom:12px;color:#f2fbf7}
.ok i{font-style:normal;width:58px;height:58px;border-radius:50%;background:var(--g);color:#03150c;font-size:30px;display:grid;place-items:center;margin:0 auto 8px}
.inv{display:inline-block;margin:8px 0 4px;padding:4px 14px;border:1px solid var(--g);border-radius:16px;color:var(--g);font-weight:700}
.emp{text-align:center;color:var(--mu);padding:20px}
.chip{display:inline-block;font-size:12px;font-weight:600;padding:3px 11px;border-radius:12px;background:rgba(0,224,112,.16);color:var(--g)}
.big-em{height:150px;border-radius:12px;background:#eef5f1;display:grid;place-items:center;font-size:80px;margin-bottom:10px}
.avatar{width:60px;height:60px;border-radius:50%;background:#12a85a;display:grid;place-items:center;font-size:30px;flex:none}
.err{color:var(--rd);font-size:12.5px;min-height:16px;margin-bottom:8px}
.sw{text-align:center;margin-top:4px;color:var(--mu)}.sw a{color:var(--g);font-weight:600;text-decoration:none}
.auth{padding-top:26px}
.brand{display:flex;gap:12px;align-items:center;justify-content:center}.brand p{color:var(--mu)}
.dn{width:128px;height:128px;border-radius:50%;display:grid;place-items:center;flex:none}
.dn div{width:88px;height:88px;border-radius:50%;background:var(--cd);display:grid;place-items:center;text-align:center;font-size:11px;color:var(--mu);align-content:center}
.dn b{display:block;color:var(--tx);font-size:12.5px}
.cc{display:inline-block;font-size:10.5px;font-weight:600;padding:3px 10px;border-radius:10px;color:#fff;margin-top:3px}
.dot{width:9px;height:9px;border-radius:50%;display:inline-block;margin-right:6px}
nav{position:fixed;left:0;right:0;bottom:0;display:none;justify-content:flex-start;background:var(--cd);border-top:1px solid var(--ln);padding:8px 0 calc(10px + env(safe-area-inset-bottom,0px));z-index:5;overflow-x:auto;scrollbar-width:none;-webkit-overflow-scrolling:touch}
nav::-webkit-scrollbar{display:none}
nav a{flex:1 0 68px;min-width:68px;display:flex;flex-direction:column;align-items:center;gap:3px;color:var(--mu);font:600 11px system-ui;text-decoration:none;padding:2px 4px;white-space:nowrap;cursor:pointer}
nav i{font-style:normal;font-size:21px;line-height:1.35;padding:0 16px;border-radius:14px}nav a.on{color:var(--g)}nav a.on i{background:rgba(0,224,112,.16)}
.md{position:fixed;inset:0;background:rgba(0,0,0,.65);display:none;align-items:flex-end;justify-content:center;z-index:20}
.md.on{display:flex}
.sh{background:var(--cd);border:1px solid var(--ln);border-radius:20px 20px 0 0;width:100%;max-width:560px;padding:18px;max-height:90vh;overflow:auto}
.sh h3{margin-bottom:12px}
.toast{position:fixed;left:50%;bottom:96px;transform:translateX(-50%);background:var(--g);color:#03150c;padding:10px 18px;border-radius:22px;font-weight:700;opacity:0;transition:.3s;z-index:30;pointer-events:none}
.toast.on{opacity:1}
.pw{position:relative}.pw input{padding-right:46px}.pw button{position:absolute;right:6px;top:5px;width:36px;height:36px;border:0;background:none;color:var(--g);font-size:18px;cursor:pointer}
.em,.big-em,.avatar,.usr b{overflow:hidden}.em img,.big-em img,.avatar img,.usr b img{width:100%;height:100%;object-fit:cover;display:block}
.tb{position:relative;background:none;border:0;font-size:20px;cursor:pointer;padding:4px 6px}
.top{gap:6px}.top>div:nth-child(2){min-width:0}.top .usr,.top .tb{flex:none}
@media(max-width:470px){.usr .un{display:none}.usr{padding:4px}.top h1{font-size:16px}}
.tb.lgb{font-size:13px;font-weight:800;letter-spacing:.5px;color:#f2fbf7;padding:6px 8px;border:1.5px solid #17463a;border-radius:10px;background:#0d241d}
.tb.dots{font-size:22px;font-weight:800;line-height:1;color:#f2fbf7;padding:6px 8px}
.tb em{position:absolute;top:-3px;right:-2px;background:#ff3b30;color:#fff;font:700 10px system-ui;font-style:normal;border-radius:9px;padding:1px 5px}
.sh2{display:flex;align-items:center;gap:10px;margin:16px 2px 8px}.sh2>i{font-style:normal;font-size:22px}.sh2 b{display:block;font-size:15.5px}.sh2 small{color:var(--mu);font-size:11.5px}
.sg{display:flex;align-items:center;gap:10px;padding:10px 2px;border-bottom:1px solid var(--ln)}
.sg:last-child{border-bottom:0}
.sg[onclick]{cursor:pointer}
.sg>i{font-style:normal;width:38px;height:38px;border-radius:50%;background:#0f3a2e;display:grid;place-items:center;font-size:18px;flex:none}
.sg .m b{font-size:14px}
.sg select{width:auto;margin:0;padding:8px 10px;font-size:13px}
.chv{color:var(--mu);font-size:22px}
.tg{width:46px;height:26px;border-radius:13px;background:var(--ln);position:relative;flex:none;border:0;cursor:pointer}
.tg::after{content:"";position:absolute;top:3px;left:3px;width:20px;height:20px;border-radius:50%;background:#fff;transition:.2s}
.tg.on{background:var(--g)}.tg.on::after{left:23px}
.au{min-height:100vh;color:#f2fbf7;background:radial-gradient(900px 420px at 80% 0%,#0d5a3f 0%,transparent 60%),radial-gradient(500px 400px at 0% 40%,#0a4a30 0%,transparent 70%),linear-gradient(165deg,#052a1d,#04120d 65%);padding-bottom:30px}
.au .hero{position:relative;min-height:290px;margin:6px -2px 0}
.au .himg{position:absolute;right:-14px;top:0;width:60%;height:100%;object-fit:cover;object-position:center top;-webkit-mask-image:linear-gradient(to right,transparent 0,#000 38%);mask-image:linear-gradient(to right,transparent 0,#000 38%);border-radius:0 0 0 24px}
.au .ht{position:relative;z-index:1;width:62%;padding-top:6px}.au .ht.full{width:100%}
.au h2{font-size:27px;line-height:1.12}.au h2 span{color:var(--g)}.au .tl{color:#b9d8cb;margin:8px 0 12px;line-height:1.4;font-size:13.5px}
.feat{display:flex;align-items:center;gap:10px;margin-top:9px;font-size:13.5px}.feat i{font-style:normal;width:30px;height:30px;border-radius:50%;background:#12a85a;display:grid;place-items:center;font-size:15px;flex:none}
.au .c{background:rgba(7,30,22,.88);border-color:#17463a;color:#f2fbf7;backdrop-filter:blur(6px)}
.au input{background:#06190f;color:#f2fbf7;border-color:#17463a}.au label,.au .mu{color:#9fbdb0}
.au .ai{position:relative}.au .ai>i{z-index:2;position:absolute;left:13px;top:12px;font-style:normal;opacity:.85}.au .ai input{padding-left:42px}
.au .pw button{color:#9fbdb0}
.gb{width:100%;height:46px;border-radius:13px;border:1.5px solid var(--g);background:transparent;color:#f2fbf7;font:600 14.5px system-ui;display:flex;align-items:center;justify-content:center;gap:10px;cursor:pointer;margin-bottom:10px}
.or{display:flex;align-items:center;gap:10px;color:#9fbdb0;font-size:12px;margin:2px 0 10px}.or:before,.or:after{content:"";flex:1;height:1px;background:#17463a}
.lg{display:flex;gap:6px;justify-content:flex-end;padding-top:10px}.lg button{background:#0d241d;color:#b9d8cb;border:1px solid #17463a;border-radius:10px;padding:5px 10px;font:600 12px system-ui;cursor:pointer}.lg button.on{background:#0f8a4f;color:#fff;border-color:#0f8a4f}
.ring{width:104px;height:104px;border-radius:50%;display:grid;place-items:center;flex:none}.ring>div{width:76px;height:76px;border-radius:50%;background:var(--cd);display:grid;place-content:center;text-align:center}.ring b{font-size:20px}.ring small{color:var(--mu);font-size:11px}
.sn{width:26px;height:26px;border-radius:50%;background:var(--g);color:#03150c;display:inline-grid;place-items:center;font-weight:800;font-size:13px;margin-right:8px}
.gal{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:10px}.gal .gt{width:64px;height:64px;border-radius:10px;overflow:hidden;position:relative;border:2px solid var(--ln);background:var(--fd);display:grid;place-items:center;cursor:pointer}.gal .gt.m{border-color:var(--g)}.gal .gt img{width:100%;height:100%;object-fit:cover}.gal .gt b{position:absolute;right:2px;top:2px;background:rgba(0,0,0,.6);color:#fff;border-radius:50%;width:18px;height:18px;font-size:11px;display:grid;place-items:center}
.fa{display:grid;grid-template-columns:repeat(2,1fr);gap:10px;margin-bottom:12px}
@media(min-width:520px){.fa{grid-template-columns:repeat(4,1fr)}}
.fa>*{position:relative;overflow:hidden;border-radius:16px;padding:14px 10px 12px;text-align:center;color:#fff;cursor:pointer;border:0;min-height:118px;display:flex;flex-direction:column;align-items:center;justify-content:center;background:var(--ag,linear-gradient(135deg,#2f6fe0,#1a4fb0))}
.fa>*::after{content:"";position:absolute;right:-18px;top:-18px;width:70px;height:70px;border-radius:50%;background:rgba(255,255,255,.12)}
.fa .ac-up{--ag:linear-gradient(135deg,#2f6fe0,#1a4fb0)}.fa .ac-new{--ag:linear-gradient(135deg,#1fb36b,#0c7a4a)}.fa .ac-cam{--ag:linear-gradient(135deg,#e8841a,#b35a00)}.fa .ac-gal{--ag:linear-gradient(135deg,#8a4fe0,#5b2aa8)}
.fa i{font-style:normal;width:46px;height:46px;border-radius:14px;background:rgba(255,255,255,.2);display:grid;place-items:center;margin:0 auto 8px;font-size:22px;position:relative}
.fa b{display:block;font-size:14px;font-weight:700;position:relative}.fa small{display:block;font-size:11px;opacity:.85;position:relative;margin-top:2px}
.stc{display:flex;align-items:center;gap:14px;background:linear-gradient(135deg,#0b3d2d,#07251b);border:1px solid #1b6a4b;border-radius:18px;padding:14px;margin-bottom:12px;color:#f2fbf7}
.stc .sr{width:74px;height:74px;border-radius:50%;display:grid;place-items:center;flex:none}
.stc .sr>div{width:58px;height:58px;border-radius:50%;background:#07251b;display:grid;place-items:center;font-weight:800;font-size:13px}
.stc .sx{flex:1;min-width:0}.stc .sx small{color:#b9d8cb;font-size:11.5px;display:block}.stc .sx b{font-size:14px}
.fo{display:grid;grid-template-columns:repeat(2,1fr);gap:8px;margin-bottom:12px}
@media(min-width:500px){.fo{grid-template-columns:repeat(3,1fr)}}
.fo>div{background:var(--cd);border:1px solid var(--ln);border-radius:14px;padding:10px;display:flex;gap:10px;align-items:center;cursor:pointer;min-width:0}
.fo i{font-style:normal;width:44px;height:44px;border-radius:12px;display:grid;place-items:center;font-size:21px;flex:none;color:#fff}
.fo>div{position:relative}
.fo b{display:block;font-size:13px}.fo small{font-size:11px;color:var(--mu)}.fo .m{min-width:0}
.ft{width:44px;height:44px;border-radius:10px;display:grid;place-items:center;font-weight:800;font-size:12px;color:#fff;flex:none;overflow:hidden;cursor:pointer}.ft img{width:100%;height:100%;object-fit:cover}
.pg{display:grid;grid-template-columns:repeat(3,1fr);gap:6px}.pt{aspect-ratio:1;border-radius:10px;background:var(--fd);overflow:hidden;display:grid;place-items:center;cursor:pointer;font-size:24px}.pt img{width:100%;height:100%;object-fit:cover}
.sech{display:flex;justify-content:space-between;align-items:center;margin:14px 2px 8px}.sech b{font-size:15px}.sech a{color:var(--g);font-size:12.5px;font-weight:600;cursor:pointer}
.fs{position:relative;overflow:hidden;border-radius:14px}
.fs-track{display:flex;transition:transform .5s ease}
.fs-slide{min-width:100%;box-sizing:border-box;display:grid;grid-template-columns:96px 1fr;gap:12px;align-items:center;padding:6px 46px;cursor:pointer}
@media(min-width:600px){.fs-slide{grid-template-columns:150px 1fr;padding:8px 58px}}
.fs-img{width:100%;aspect-ratio:1/1;border-radius:12px;overflow:hidden;background:var(--fd);display:grid;place-items:center;font-size:40px}
.fs-img img{width:100%;height:100%;object-fit:cover;display:block}
.fs-n{display:block;font-size:15px;margin-bottom:4px}
.fs-p{font-size:17px;font-weight:700;color:var(--g);margin:6px 0 2px}.fs-p small{font-size:11px;color:var(--mu);font-weight:400;margin-left:4px}
.fs-s{font-size:12px;color:var(--mu);display:flex;gap:6px;align-items:center;flex-wrap:wrap}
.fs-btn{position:absolute;top:50%;transform:translateY(-50%);width:34px;height:34px;border-radius:50%;border:0;background:rgba(0,0,0,.45);color:#fff;font-size:20px;cursor:pointer;z-index:2}
.fs-l{left:6px}.fs-r{right:6px}
.fs-dots{display:flex;justify-content:center;gap:6px;padding:8px 0 2px}.fs-dots i{width:8px;height:8px;border-radius:6px;background:var(--ln);cursor:pointer;transition:.3s}.fs-dots i.on{background:var(--g);width:20px}
.xamt{display:flex;align-items:center;gap:10px;background:var(--fd);border:1px solid var(--ln);border-radius:12px;padding:0 14px;margin-bottom:12px}
.xamt span{color:var(--mu);font-size:16px;font-weight:600}
.xamt input{border:0;background:none;margin:0;padding:12px 0;font-size:22px;font-weight:700;color:var(--tx)}
.xch{display:flex;flex-wrap:wrap;gap:8px;margin-bottom:12px}
.xch button{border:1px solid var(--ln);background:var(--fd);color:var(--mu);border-radius:20px;padding:9px 14px;font:600 13px system-ui;cursor:pointer}
.xch button.on{background:#ffb300;border-color:#ffb300;color:#2b1c00}
.xbtn{width:100%;height:52px;border:0;border-radius:16px;background:#ffb300;color:#2b1c00;font:700 16px system-ui;cursor:pointer;margin-top:10px}
.hmg{display:grid;grid-template-columns:1fr 1fr;gap:10px;height:50vh;height:50dvh;overflow-y:auto;align-content:start;padding:6px!important;-webkit-overflow-scrolling:touch;background:transparent!important;border:0!important}
.hmg .sg{display:flex;align-items:center;gap:10px;background:var(--cd);border:1px solid var(--ln);border-radius:18px;padding:12px 10px;margin:0;cursor:pointer;min-width:0}
.hmg .sg>i{width:50px;height:50px;border-radius:50%;background:var(--hc);display:grid;place-items:center;font-size:22px;flex:none;font-style:normal;box-shadow:0 4px 12px rgba(0,0,0,.25)}
.hmg .sg .m{min-width:0;flex:1}
.hmg .sg .m b{font-size:13.5px;display:block;line-height:1.2}
.hmg .sg .m small{font-size:10.5px;color:var(--mu);display:block;line-height:1.3;margin-top:2px}
.hmg .sg .chv{color:var(--mu);font-size:18px;flex:none}
.hsplit{display:grid;grid-template-columns:1fr 1fr;gap:10px;height:50vh;height:50dvh;min-height:260px}
.hsplit>div{overflow-y:auto;min-width:0;-webkit-overflow-scrolling:touch;padding:2px}
.hcol{display:flex;flex-direction:column;gap:8px}
.hcol .sg{display:flex;align-items:center;gap:8px;background:var(--cd);border:1px solid var(--ln);border-radius:14px;padding:8px;cursor:pointer;margin:0}
.hcol .sg>i{width:36px;height:36px;border-radius:50%;background:var(--hc);display:grid;place-items:center;font-size:17px;flex:none;font-style:normal}
.hcol .sg .m{min-width:0;flex:1}.hcol .sg .m b{font-size:12.5px;display:block;line-height:1.2}
.hcol .sg .chv{color:var(--mu);font-size:15px;flex:none}
.dcol .btn{margin-bottom:8px}
.dstat{display:grid;grid-template-columns:1fr 1fr;gap:6px;margin-bottom:10px}.dstat>div{background:var(--cd);border:1px solid var(--ln);border-radius:12px;padding:8px;min-width:0}.dstat small{display:block;font-size:10.5px;color:var(--mu);line-height:1.2}.dstat b{display:block;font-size:13px;margin-top:3px;overflow:hidden;text-overflow:ellipsis;white-space:nowrap}

#hpanel{position:fixed;top:0;bottom:76px;right:0;width:50vw;min-width:170px;max-width:50vw;transform:translateX(105%);transition:transform .25s ease;z-index:6;background:var(--cd);border-left:1px solid var(--ln);box-shadow:-8px 0 22px rgba(0,0,0,.4);overflow:hidden}
#hpanel.on{transform:translateX(0)}
#hpanel .hp-in{height:100%;display:flex;flex-direction:column}
#hpanel .hp-h{display:flex;align-items:center;justify-content:space-between;padding:12px 12px 10px;border-bottom:1px solid var(--ln);font-size:15px}
#hpanel .hp-h .tb{font-size:18px;padding:2px 6px}
#hpanel .hp-l{flex:1;overflow-y:auto;padding:10px;display:flex;flex-direction:column;gap:8px;-webkit-overflow-scrolling:touch}
#hpanel .sg{display:flex;align-items:center;gap:8px;background:var(--bg);border:1px solid var(--ln);border-radius:14px;padding:8px;cursor:pointer;margin:0}
#hpanel .sg>i{width:36px;height:36px;border-radius:50%;background:var(--hc);display:grid;place-items:center;font-size:17px;flex:none;font-style:normal}
#hpanel .sg .m{min-width:0;flex:1}#hpanel .sg .m b{font-size:12.5px;display:block;line-height:1.2}
#hpanel .sg .chv{color:var(--mu);font-size:15px;flex:none}
.it5{display:grid;grid-template-columns:16px 1fr 26px 74px 78px;gap:4px;align-items:center;font-size:12px;padding:8px 0;border-bottom:1px solid var(--ln)}
.it5.h{color:var(--mu);font-size:11.5px}
.it5>span:nth-child(n+3){text-align:right;white-space:nowrap}
.it5 .pn{display:flex;gap:6px;align-items:center;min-width:0}
.it5 .pn>span{min-width:0}
.it5 .th{font-style:normal;width:34px;height:34px;border-radius:8px;background:#e9f4ee;display:grid;place-items:center;font-size:18px;flex:none;overflow:hidden}
.it5 .th img{width:100%;height:100%;object-fit:cover}
.it5 b{display:block;font-size:12px}.it5 small{color:var(--mu);font-size:10.5px;display:block}
.rw{display:flex;align-items:center;gap:10px;padding:10px 0;border-bottom:1px solid var(--ln)}.rw:last-child{border-bottom:0}
.rw .ic{font-style:normal;width:38px;height:38px;border-radius:50%;background:#0f3a2e;display:grid;place-items:center;font-size:18px;flex:none}
.rw small{display:block;color:var(--mu);font-size:11.5px}
.tg2{font-size:11px;font-weight:700;padding:4px 12px;border-radius:12px;background:rgba(0,224,112,.2);color:var(--g);white-space:nowrap}
.tg2.Partial{background:var(--am);color:#2b1c00}.tg2.Debt{background:rgba(255,77,77,.22);color:var(--rd)}
.ck{display:flex;align-items:center;gap:8px;color:var(--tx);font-size:13.5px;margin:0 0 10px}.ck input{width:auto;margin:0}
.rcp{background:#f3f7f5;color:#12281f;border-radius:16px;padding:16px;margin-bottom:12px;font-size:12px;line-height:1.35}
.rcp .rh{display:flex;gap:10px;align-items:center;margin-bottom:10px}
.rcp .rh b{font-size:16px;display:block}.rcp .rh b span{color:#0f8a4f}.rcp small{color:#5b7a6c;display:block;font-size:10.5px}
.rcp h3{text-align:center;font-size:17px;letter-spacing:.5px;margin:6px 0 0;display:block}
.rcp .mid{text-align:center;color:#33493f;margin-bottom:10px}
.rcp .two{display:flex;justify-content:space-between;gap:8px;margin-bottom:8px}
.rcp .cu{display:flex;align-items:center;gap:8px;padding:8px 0;border-top:1px solid #d3e3da;border-bottom:1px solid #d3e3da;margin-bottom:8px}
.rcp .cu .tg2{margin-left:auto;background:#0f8a4f;color:#fff}
.r5{display:grid;grid-template-columns:14px 1fr 28px 70px 74px;gap:4px;padding:6px 0;font-size:11.5px}
.r5.h{background:#0f8a4f;color:#fff;border-radius:6px;padding:6px;font-weight:600}
.r5>span:nth-child(n+3){text-align:right;white-space:nowrap}
.rcp .dash{border-top:1.5px dashed #9ec2b0;margin:8px 0}
.rcp .ln{display:flex;justify-content:space-between;padding:3px 0}
.rcp .ttl{background:#d9efe3;color:#0f8a4f;font-weight:700;font-size:15px;padding:8px 10px;border-radius:8px;margin-top:4px;display:flex;justify-content:space-between}
.rcp .pay{display:flex;align-items:center;gap:8px;padding:10px 0}
.rcp .ty{text-align:center;margin-top:8px}.rcp .ty b{display:block}
.rcp .bc{display:block;margin:8px auto 4px;max-width:100%}
.bar{height:8px;border-radius:6px;background:var(--ln);overflow:hidden;margin:2px 0 8px}.bar i{display:block;height:100%;background:var(--g)}
.chart{display:flex;gap:8px;align-items:flex-end;height:120px}.cb{flex:1;text-align:center}.cb small{color:var(--mu);font-size:10.5px}.cs{height:100px;display:flex;gap:3px;align-items:flex-end;justify-content:center}.cs i{width:42%;border-radius:4px 4px 0 0;min-height:2px;display:block}
.rt{width:100%;border-collapse:collapse;font-size:12px}.rt th,.rt td{padding:7px 6px;border-bottom:1px solid var(--ln);text-align:left;white-space:nowrap}.rt th{color:var(--mu);font-weight:600}.rt .n{text-align:right}
@media print{.top,nav,.hd,.md,.toast,.no-p{display:none!important}body{background:#fff!important;padding:0!important}.rcp{border-radius:0}}
#lblp{display:none}
@media print{
  #app,#nav,.md,.toast,.top{display:none!important}
  #lblp{display:flex!important;flex-wrap:wrap;align-content:flex-start;background:#fff}
  .lab{box-sizing:border-box;width:var(--lw);height:var(--lh);padding:1.5mm 2mm;overflow:hidden;page-break-inside:avoid;color:#000;background:#fff;display:flex;flex-direction:column;justify-content:space-between;font-family:Arial,sans-serif}
  .lab b{font-size:9pt;line-height:1.1;display:block;white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
  .lab .pr{font-size:12pt;font-weight:700}
  .lab .cd{font-size:7pt}
  .lab svg{height:7mm;width:100%;display:block}
  @page{size:auto;margin:3mm}
}
#prn{display:none}
body.printing #prn{display:block!important;background:#fff;color:#000;padding:8px}
body.printing #prn .no-p{display:none!important}
body.printing #app,body.printing #nav,body.printing #hpanel,body.printing .md,body.printing .toast{display:none!important}
body.printing #lblp{display:flex!important}
@media print{#app,#nav,#hpanel,.md,.toast{display:none!important} #prn{display:block!important}}
#pvw{display:none;position:fixed;inset:0;z-index:50;background:#4b4f54;flex-direction:column}
#pvw.on{display:flex}
#pvw .pv-bar{display:flex;align-items:center;justify-content:space-between;gap:8px;padding:10px 12px;background:#1f2326;color:#fff;flex-wrap:wrap}
#pvw .pv-bar b{font-size:14px;max-width:40%;overflow:hidden;text-overflow:ellipsis;white-space:nowrap}
#pvw .pv-acts{display:flex;gap:6px;flex-wrap:wrap}
#pvw .pv-b{border:0;border-radius:10px;padding:9px 12px;font:700 13px system-ui;background:#3a3f44;color:#fff;cursor:pointer}
#pvw .pv-p{background:#0f8a4f}
#pvw .pv-sheet{flex:1;overflow:auto;padding:14px;-webkit-overflow-scrolling:touch}
#pvw .pv-paper{background:#fff;color:#000;max-width:800px;margin:0 auto;padding:16px;box-shadow:0 4px 18px rgba(0,0,0,.4);min-height:60vh}
#pvw .pv-paper *{color:#000;background-color:transparent}
#pvw .pv-paper .rcp{background:#fff!important}
#pvw .pv-paper .no-p{display:none!important}
#pvw .pv-msg{position:absolute;left:0;right:0;bottom:6px;text-align:center;color:#fff;font-size:12px}
</style>
</head>
<body>
<div id="app"></div>
<nav id="nav"></nav>
<div class="md" id="md" onclick="if(event.target===this)closeM()"><div class="sh" id="sh"></div></div>
<div class="toast" id="toast"></div>
<div id="lblp"></div>

<script src="config.js"></script>
<script src="sync.js"></script>
<script>
const LOGO="data:image/jpeg;base64,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";
const MEMS={};
const LS={
  getItem:k=>{try{return window.localStorage.getItem(k)}catch(e){return k in MEMS?MEMS[k]:null}},
  setItem:(k,v)=>{try{window.localStorage.setItem(k,v)}catch(e){MEMS[k]=String(v)}},
  removeItem:k=>{try{window.localStorage.removeItem(k)}catch(e){delete MEMS[k]}}
};
const $=i=>document.getElementById(i),
ld=(k,d)=>{try{const v=JSON.parse(LS.getItem(k));return v==null?d:v}catch(e){return d}},
sv=(k,v)=>{try{LS.setItem(k,JSON.stringify(v))}catch(e){toast("Ububiko bwuzuye - ifoto ni nini cyane")}},
esc=s=>String(s==null?"":s).replace(/[&<>"']/g,c=>({"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;","'":"&#39;"}[c])),
fmt=n=>"RWF "+Math.round(n).toLocaleString("en-US"),
when=t=>{const d=new Date(t);return d.toLocaleDateString("en-GB",{day:"2-digit",month:"short",year:"numeric"})+" - "+d.toLocaleTimeString("en-US",{hour:"2-digit",minute:"2-digit"})},
toast=m=>{const t=$("toast");t.textContent=(typeof trTxt==="function"&&trTxt(m))||m;t.classList.add("on");setTimeout(()=>t.classList.remove("on"),2000)},
go=h=>{location.hash=h},
modal=h=>{$("sh").innerHTML=h;trDom($("sh"));$("md").classList.add("on")},
closeM=()=>$("md").classList.remove("on"),
card=(i,l,v,d)=>`<div class="s"><i>${i}</i><div><small>${l}</small><b>${v}</b><em>${d||""}</em></div></div>`;

const SEED=[[1,"Ibigori (Rice)","🍚",1200,900,25,"Ibiribwa","imifuka"],[2,"Amavuta (Cooking Oil)","🛢️",2500,2000,15,"Ibiribwa","amacupa"],[3,"Isukari (Sugar)","🍬",1000,800,30,"Ibiribwa","imifuka"],[4,"Soda (Fanta)","🥤",1000,700,40,"Ibinyobwa","amacupa"],[5,"Umugati (Bread)","🍞",1500,1100,8,"Ibiribwa","imigati"],[6,"Amata (Milk)","🥛",1800,1400,12,"Ibinyobwa","litiro"],[7,"Isabune (Soap)","🧼",800,550,5,"Isuku","ibice"],[8,"Ifu y'ibigori (Maize Flour)","🌽",1500,1200,20,"Ibiribwa","imifuka"],[9,"Amazi (Water)","💧",700,450,50,"Ibinyobwa","amacupa"],[10,"Bikije (Biscuits)","🍪",1200,900,18,"Ibiribwa","udupaki"],[11,"Kawa (Coffee)","☕",3500,2800,6,"Ibinyobwa","udupaki"],[12,"Amagi (Eggs)","🥚",400,300,35,"Ibiribwa","amagi"]]
.map(a=>({id:a[0],n:a[1],e:a[2],p:a[3],c:a[4],s:a[5],k:a[6],u:a[7],lw:10,mv:[]}));

let U=ld("bizz_users",[{name:"Albert Dushimimana",biz:"Albert Shop",id:"albert@bizz.rw",pw:"123456",role:"Administrator",active:true,last:Date.now()}]),
SE=ld("bizz_session",null),
P=ld("bizz_products",null)||SEED,
S=ld("bizz_sales",[]),
C=ld("bizz_customers",[]),
X=ld("bizz_expenses",[]),
Memos=ld("bizz_memos",[{id:1,t:Date.now()-86400000,text:"Memo AI: Kuri uyu munsi wungutse cyane mu bigori n'isukari. Emeza ko wongera stock y'isukari vuba."},{id:2,t:Date.now(),text:"Memo AI: Hari amafaranga y'amashanyarazi yishyuwe ejo. Bika inyemezabwishyu."}]),
Reports=ld("bizz_reports",[]),
Reqs=ld("bizz_reqs",[]),
SUP=ld("bizz_suppliers",[]),
CAT=ld("bizz_cats",null)||[...new Set(P.map(p=>p.k))].sort();

const save=()=>{if(window.bizzSync)bizzSync.schedule();sv("bizz_users",U);sv("bizz_products",P);sv("bizz_sales",S);sv("bizz_customers",C);sv("bizz_expenses",X);sv("bizz_memos",Memos);sv("bizz_reports",Reports);sv("bizz_reqs",Reqs);sv("bizz_suppliers",SUP);sv("bizz_cats",CAT)},
gp=id=>P.find(p=>p.id===id),
code=p=>p.sk||"P"+("00"+p.id).slice(-3),
st=p=>p.s<=0?"out":p.s<=(p.lw||10)?"low":"in",
LB={in:"In Stock",low:"Low Stock",out:"Out of Stock"},
badge=p=>`<span class="bd ${st(p)}">${LB[st(p)]}</span>`,
inv=id=>{const s=S.find(x=>x.id===id),y=(s?new Date(s.t):new Date()).getFullYear();return "#SALE-"+y+"-"+("0000"+id).slice(-4)},
same=(t,o)=>{const b=new Date();b.setDate(b.getDate()-o);return new Date(t).toDateString()===b.toDateString()},
agg=o=>S.filter(s=>same(s.t,o)).reduce((a,s)=>({t:a.t+s.tot,n:a.n+1,p:a.p+s.pf}),{t:0,n:0,p:0}),
dl=(v,o)=>o?(v>=o?"▲ +":"▼ ")+Math.abs(Math.round((v-o)/o*100))+"%":"";

let tmpImg="";
const okImg=s=>typeof s==="string"&&/^data:image\/(jpeg|png|webp);base64,[A-Za-z0-9+\/=]+$/.test(s),
pim=p=>okImg(p.img)?`<img src="${p.img}" alt="">`:esc(p.e),
uav=u=>u&&okImg(u.img)?`<img src="${u.img}" alt="">`:"👤",
pickImg=(inp,cb,max)=>{const f=inp.files&&inp.files[0];if(!f)return;if(!/^image\//.test(f.type))return toast("Hitamo ifoto");const r=new FileReader();r.onload=()=>{const im=new Image();im.onload=()=>{const s=Math.min(1,max/Math.max(im.width,im.height)),c=document.createElement("canvas");c.width=Math.max(1,Math.round(im.width*s));c.height=Math.max(1,Math.round(im.height*s));const x=c.getContext("2d");x.fillStyle="#fff";x.fillRect(0,0,c.width,c.height);x.drawImage(im,0,0,c.width,c.height);cb(c.toDataURL("image/jpeg",.75))};im.onerror=()=>toast("Ifoto si yo");im.src=r.result};r.onerror=()=>toast("Ifoto si yo");r.readAsDataURL(f)},
photoField=(kind,cur)=>`<label>${kind==="p"?"Product Photo":"Photo"}</label><div style="display:flex;gap:10px;align-items:center;margin-bottom:10px"><div class="${kind==="p"?"em":"avatar"}" id="ipv" style="width:64px;height:64px">${kind==="p"?pim(cur):uav(cur)}</div><div style="flex:1"><input type="file" accept="image/*" onchange="pickPhoto(this,'${kind}')" style="margin-bottom:6px"><button type="button" class="ib" onclick="clrPhoto('${kind}')">🗑 Remove photo</button></div></div>`,
pickPhoto=(inp,k)=>pickImg(inp,v=>{tmpImg=v;$("ipv").innerHTML=k==="p"?pim({img:v,e:"📦"}):uav({img:v})},k==="p"?360:160),
clrPhoto=k=>{tmpImg="";$("ipv").innerHTML=k==="p"?pim({e:($("fe")||{}).value||"📦"}):uav({})};
const NAVC=()=>[["home","🏠",L("Dashboard","Dashboard"),L("Business overview","Incamake y'ubucuruzi")],["sales","🛒",L("Sales","Igurisha"),L("Record and view sales","Andika kandi urebe igurisha")],["products","📦",L("Products","Ibicuruzwa"),L("Manage your products","Gucunga ibicuruzwa")],["customers","👥",L("Customers","Abakiriya"),L("Your customers","Abakiriya bawe")],["inventory","🏬",L("Inventory","Ububiko"),L("Stock levels & movements","Stock n'imigendekere yayo")],["finance","💰",L("Finance","Imari"),L("Income, expenses & profit","Ibyinjira, ibisohoka n'inyungu")],["reports","📊",L("Reports","Raporo"),L("Sales, profit & debts","Igurisha, inyungu n'ideni")],["suppliers","🚚",L("Suppliers","Abatanga ibicuruzwa"),L("People who supply you","Abagutangira ibicuruzwa")],["log","🕒",L("Activity Log","Ibyakozwe byose"),L("Everything done, with date & time","Ibikorwa byose n'itariki n'isaha")],["files","🗂️",L("Files & Photos","Dosiye n'amafoto"),L("Documents & images","Inyandiko n'amashusho")],["shop","🌐",L("Shop","Iduka"),L("Public shop view","Uko iduka ryerekanwa")],["expenses","🧾",L("Expenses","Amafaranga yakoreshejwe"),L("Track spending","Kurikirana ikoreshwa ry'amafaranga")],["ai","🤖","Memo AI",L("Ask about your business","Baza ku bucuruzi bwawe")],["settings","⚙️",L("Settings","Igenamiterere"),L("Account & app options","Konti n'amahitamo ya app")]];
function navCfg(){
  const all=NAVC().map(x=>x[0]).filter(k=>k!=="home");
  const uniq=a=>(a||[]).filter((k,i,arr)=>all.includes(k)&&arr.indexOf(k)===i);
  const nv=uniq(PF.nav||["sales","products","customers"]).slice(0,4);
  const qa=uniq(PF.qa||["sales","shop","expenses","ai"]).slice(0,8);
  const hm=PF.hm?uniq(PF.hm):all.filter(k=>!nv.includes(k));
  return {nv:["home",...nv],hm,qa};
}
const navItem=k=>NAVC().find(x=>x[0]===k),
navOk=x=>x&&can(x[0])&&(x[0]!=="ai"||PF.ai!==false);
function page(t,sub,body,o={}){
  const nc=ncount();
  $("app").innerHTML=imBanner()+`<div class="top"><div class="logo"><img src="${LOGO}" alt="BizzAssist"></div><div><h1>Bizz<span>Assist</span> Rwanda</h1><p>Smart Business Assistant</p></div><div class="sp"></div><button class="tb" id="bell" onclick="notif()" aria-label="Notifications">🔔${nc?`<em>${nc}</em>`:""}</button><button class="tb lgb" onclick="langPick()" aria-label="Language">${({Kinyarwanda:"RW",English:"EN","Français":"FR",Kiswahili:"SW"})[PF.lang||"English"]||"RW"}</button><div class="usr"><b>${SE?uav(me()):"👤"}</b><span class="un">${esc(SE?SE.name.split(" ")[0]:"Guest")}</span></div><button class="tb dots" onclick="go('#/more')" aria-label="Home">☰</button></div>
  <div class="wrap"><div class="hd">${o.back?`<a href="${o.back}">←</a>`:""}<div><h2>${t}</h2><p>${sub}</p></div>${o.act||""}</div>${body}</div>`;
  const n=$("nav");n.style.display=SE?"flex":"none";
  n.innerHTML=navCfg().nv.map(navItem).filter(navOk).map(x=>`<a href="#/${x[0]}" class="${x[0]===o.nav?"on":""}"><i>${x[1]}</i>${x[2]}</a>`).join("");
  const on=n.querySelector("a.on");if(on)n.scrollLeft=on.offsetLeft-(n.clientWidth-on.offsetWidth)/2;
  trDom($("app"));trDom(n);
}

const pwf=(id,ph,ac,val,strong)=>`<div class="pw"><input id="${id}" type="password" placeholder="${ph}" autocomplete="${ac}" value="${val?esc(val):""}"${strong?` oninput="pwChk('${id}')"`:""}><button type="button" onclick="tp('${id}',this)" aria-label="Show or hide password">👁️</button></div>${strong?`<div class="pwh" id="pwh_${id}"></div>`:""}`,
tp=(id,b)=>{const i=$(id),h=i.type==="password";i.type=h?"text":"password";b.textContent=h?"🙈":"👁️"};
const nid=v=>{v=String(v).trim().toLowerCase();if(v.includes("@"))return v;const d=v.replace(/[\s-]/g,"").replace(/^\+?250/,"");return /^0?7[2389]\d{7}$/.test(d)?(d[0]==="0"?d:"0"+d):v};
const okId=v=>/^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(v)||/^(\+?250|0)?7[2389]\d{7}$/.test(v.replace(/[\s-]/g,""));
const hero=()=>ld("bizz_hero","");
const RW_PROV={"Kigali City":["Gasabo","Kicukiro","Nyarugenge"],"Northern Province":["Burera","Gakenke","Gicumbi","Musanze","Rulindo"],"Southern Province":["Gisagara","Huye","Kamonyi","Muhanga","Nyamagabe","Nyanza","Nyaruguru","Ruhango"],"Eastern Province":["Bugesera","Gatsibo","Kayonza","Kirehe","Ngoma","Nyagatare","Rwamagana"],"Western Province":["Karongi","Ngororero","Nyabihu","Nyamasheke","Rubavu","Rusizi","Rutsiro"]};
const COUNTRY_PROV={
  "Tanzania":["Arusha", "Dar es Salaam", "Dodoma", "Geita", "Iringa", "Kagera", "Katavi", "Kigoma", "Kilimanjaro", "Lindi", "Manyara", "Mara", "Mbeya", "Morogoro", "Mtwara", "Mwanza", "Njombe", "Pwani", "Rukwa", "Ruvuma", "Shinyanga", "Simiyu", "Singida", "Songwe", "Tabora", "Tanga", "Mjini Magharibi", "Kusini Unguja", "Kaskazini Unguja", "Kaskazini Pemba", "Kusini Pemba"],
  "Uganda":["Central","Eastern","Northern","Western"],
  "Burundi":["Buhumuza","Bujumbura","Burunga","Butanyerera","Gitega"],
  "Kenya":["Mombasa","Kwale","Kilifi","Tana River","Lamu","Taita-Taveta","Garissa","Wajir","Mandera","Marsabit","Isiolo","Meru","Tharaka-Nithi","Embu","Kitui","Machakos","Makueni","Nyandarua","Nyeri","Kirinyaga","Murang'a","Kiambu","Turkana","West Pokot","Samburu","Trans Nzoia","Uasin Gishu","Elgeyo-Marakwet","Nandi","Baringo","Laikipia","Nakuru","Narok","Kajiado","Kericho","Bomet","Kakamega","Vihiga","Bungoma","Busia","Siaya","Kisumu","Homa Bay","Migori","Kisii","Nyamira","Nairobi"]
};
const COUNTRY_DIST={"Uganda":{"Central": ["Buikwe", "Bukomansibi", "Butambala", "Buvuma", "Gomba", "Kalangala", "Kalungu", "Kampala", "Kasanda", "Kayunga", "Kiboga", "Kyankwanzi", "Kyotera", "Luwero", "Lwengo", "Lyantonde", "Masaka", "Mityana", "Mpigi", "Mubende", "Mukono", "Nakaseke", "Nakasongola", "Rakai", "Sembabule", "Wakiso"], "Eastern": ["Amuria", "Budaka", "Bududa", "Bugiri", "Bugweri", "Bukedea", "Bukwo", "Bulambuli", "Busia", "Butaleja", "Butebo", "Buyende", "Iganga", "Jinja", "Kaberamaido", "Kalaki", "Kaliro", "Kamuli", "Kapchorwa", "Kapelebyong", "Katakwi", "Kibuku", "Kumi", "Kween", "Luuka", "Manafwa", "Mayuge", "Mbale", "Namayingo", "Namisindwa", "Namutumba", "Ngora", "Pallisa", "Serere", "Sironko", "Soroti", "Tororo"], "Northern": ["Abim", "Adjumani", "Agago", "Alebtong", "Amolatar", "Amudat", "Amuru", "Apac", "Arua", "Dokolo", "Gulu", "Kaabong", "Karenga", "Kitgum", "Koboko", "Kole", "Kotido", "Kwania", "Lamwo", "Lira", "Madi-Okollo", "Maracha", "Moroto", "Moyo", "Nabilatuk", "Nakapiripirit", "Napak", "Nebbi", "Nwoya", "Obongi", "Omoro", "Otuke", "Oyam", "Pader", "Pakwach", "Yumbe", "Zombo"], "Western": ["Buhweju", "Buliisa", "Bundibugyo", "Bunyangabu", "Bushenyi", "Hoima", "Ibanda", "Isingiro", "Kabale", "Kabarole", "Kagadi", "Kakumiro", "Kamwenge", "Kanungu", "Kasese", "Kazo", "Kibaale", "Kikuube", "Kiruhura", "Kiryandongo", "Kisoro", "Kitagwenda", "Kyegegwa", "Kyenjojo", "Masindi", "Mbarara", "Mitooma", "Ntoroko", "Ntungamo", "Rubanda", "Rubirizi", "Rukiga", "Rukungiri", "Rwampara", "Sheema"]}};
const RW_SECT={"Bugesera": ["Gashora", "Juru", "Kamabuye", "Mareba", "Mayange", "Musenyi", "Mwogo", "Ngeruka", "Ntarama", "Nyamata", "Nyarugenge", "Rilima", "Ruhuha", "Rweru", "Shyara"], "Burera": ["Bungwe", "Butaro", "Cyanika", "Cyeru", "Gahunga", "Gatebe", "Gitovu", "Kagogo", "Kinoni", "Kinyababa", "Kivuye", "Nemba", "Rugarama", "Rugengabari", "Ruhunde", "Rusarabuye", "Rwerere"], "Gakenke": ["Busengo", "Coko", "Cyabingo", "Gakenke", "Gashenyi", "Janja", "Kamubuga", "Karambo", "Kivuruga", "Mataba", "Minazi", "Mugunga", "Muhondo", "Muyongwe", "Muzo", "Nemba", "Ruli", "Rusasa", "Rushashi"], "Gasabo": ["Bumbogo", "Gatsata", "Gikomero", "Gisozi", "Jabana", "Jali", "Kacyiru", "Kimihurura", "Kimiromko", "Kinyinya", "Ndera", "Nduba", "Remera", "Rusororo", "Rutunga"], "Gatsibo": ["Gasange", "Gatsibo", "Gitoki", "Kabarore", "Kageyo", "Kiramuruzi", "Kiziguro", "Muhura", "Murambi", "Ngarama", "Nyagihanga", "Remera", "Rugarama", "Rwimbogo"], "Gicumbi": ["Bukure", "Bwisige", "Byumba", "Cyumba", "Giti", "Kageyo", "Kaniga", "Manyagiro", "Miyove", "Mukarange", "Muko", "Mutete", "Nyamiyaga", "Nyankenke", "Rubaya", "Rukomo", "Rushaki", "Rutare", "Ruvune", "Rwamiko", "Shangasha"], "Gisagara": ["Gikonko", "Gishubi", "Kansi", "Kibirizi", "Kigembe", "Mamba", "Muganza", "Mugombwa", "Mukingo", "Musha", "Ndora", "Nyanza", "Save"], "Huye": ["Gishamvu", "Huye", "Karama", "Kigoma", "Kinazi", "Maraba", "Mbazi", "Mukura", "Ngoma", "Ruhashya", "Rusatira", "Rwaniro", "Simbi", "Tumba"], "Kamonyi": ["Gacurabwenge", "Karama", "Kayenzi", "Kayumbu", "Mugina", "Musambira", "Ngamba", "Nyamiyaga", "Nyarubaka", "Rugarika", "Rukoma", "Runda"], "Karongi": ["Bwishyura", "Gishari", "Gishyita", "Gitesi", "Mubuga", "Murambi", "Murundi", "Mutuntu", "Rubengera", "Rugabano", "Ruganda", "Rwankuba", "Twumba"], "Kayonza": ["Gahini", "Kabare", "Kabarondo", "Mukarange", "Murama", "Murundi", "Mwiri", "Ndego", "Nyamirama", "Rukara", "Ruramira", "Rwinkwavu"], "Kicukiro": ["Gahanga", "Gatenga", "Gikondo", "Kagarama", "Kanombe", "Kicukiro", "Kigarama", "Masaka", "Niboye", "Nyarugunga"], "Kirehe": ["Gahara", "Gatore", "Kigarama", "Kigina", "Kirehe", "Mahama", "Mpanga", "Musaza", "Mushikiri", "Nasho", "Nyamugari", "Nyarubuye"], "Muhanga": ["Cyeza", "Kabacuzi", "Kibangu", "Kiyumba", "Muhanga", "Mushishiro", "Nyabinoni", "Nyamabuye", "Nyarusange", "Rongi", "Rugendabari", "Shyogwe"], "Musanze": ["Busogo", "Cyuve", "Gacaca", "Gashaki", "Gataraga", "Kimonyi", "Kinigi", "Muhoza", "Muko", "Musanze", "Nkotsi", "Nyange", "Remera", "Rwaza", "Shingiro"], "Ngoma": ["Gashanda", "Jarama", "Karembo", "Kazo", "Kibungo", "Mugesera", "Murama", "Mutenderi", "Remera", "Rukira", "Rukumberi", "Rurenge", "Sake", "Zaza"], "Ngororero": ["Bwira", "Gatumba", "Hindiro", "Kabaya", "Kageyo", "Kavumu", "Matyazo", "Muhanda", "Muhororo", "Ndaro", "Ngororero", "Nyange", "Sovu"], "Nyabihu": ["Bigogwe", "Jenda", "Jomba", "Kabatwa", "Karago", "Kintobo", "Mukamira", "Muringa", "Rambura", "Rugera", "Rurembo", "Shyira"], "Nyagatare": ["Gatunda", "Karama", "Karangazi", "Katabagemu", "Kiyombe", "Matimba", "Mimuri", "Mukama", "Musheri", "Nyagatare", "Rukomo", "Rwempasha", "Rwimiyaga", "Tabagwe"], "Nyamagabe": ["Buruhukiro", "Cyanika", "Gasaka", "Gatare", "Kaduha", "Kamegeri", "Kibirizi", "Kibumbwe", "Kitabi", "Mbazi", "Mugano", "Musange", "Musebeya", "Mushubi", "Nkomane", "Tare", "Uwinkingi"], "Nyamasheke": ["Bushekeri", "Bushenge", "Cyato", "Gihombo", "Kagano", "Kanjongo", "Karambi", "Karengera", "Kirimbi", "Macuba", "Mahembe", "Nyabitekeri", "Rangiro", "Ruharambuga", "Shangi"], "Nyanza": ["Busasamana", "Busoro", "Cyabakamyi", "Kibirizi", "Kigoma", "Mukingo", "Muyira", "Ntyazo", "Nyagisozi", "Rwabicuma"], "Nyarugenge": ["Gitega", "Kanyinya", "Kigali", "Kimisagara", "Mageragere", "Muhima", "Nyakabanda", "Nyamirambo", "Nyarugenge", "Rwezamenyo"], "Nyaruguru": ["Busanze", "Cyahinda", "Kibeho", "Kivu", "Mata", "Muganza", "Munini", "Ngera", "Ngoma", "Nyabimata", "Nyagisozi", "Ruheru", "Ruramba", "Rusenge"], "Rubavu": ["Bugeshi", "Busasamana", "Cyanzarwe", "Gisenyi", "Kanama", "Kanzenze", "Mudende", "Nyakiriba", "Nyamyumba", "Nyundo", "Rubavu", "Rugerero"], "Ruhango": ["Bweramana", "Byimana", "Kabagali", "Kinazi", "Kinihira", "Mbuye", "Mwendo", "Ntongwe", "Ruhango"], "Rulindo": ["Base", "Burega", "Bushoki", "Buyoga", "Cyinzuzi", "Cyungo", "Kinihira", "Kisaro", "Masoro", "Mbogo", "Murambi", "Ngoma", "Ntarabana", "Rukozo", "Rusiga", "Shyorongi", "Tumba"], "Rusizi": ["Bugarama", "Butare", "Bweyeye", "Gashonga", "Giheke", "Gihundwe", "Gikundamvura", "Gitambi", "Kamembe", "Muganza", "Mururu", "Nkanka", "Nkombo", "Nkungu", "Nyakabuye", "Nyakarenzo", "Nzahaha", "Rwimbogo"], "Rutsiro": ["Boneza", "Gihango", "Kigeyo", "Kivumu", "Manihira", "Mukura", "Murunda", "Musasa", "Mushonyi", "Mushubati", "Nyabirasi", "Ruhango", "Rusebeya"], "Rwamagana": ["Fumbwe", "Gahengeri", "Gishali", "Karenge", "Kigabiro", "Muhazi", "Munyaga", "Munyiginya", "Musha", "Muyumbu", "Mwulire", "Nyakaliro", "Nzige", "Rubona"]};
const COUNTRIES=["Rwanda","Burundi","Uganda","Kenya","Tanzania","DR Congo","South Sudan","Somalia","Ethiopia","Other"];
const locOpts=(arr,cur,ph)=>`<option value="">${ph}</option>`+arr.map(x=>`<option value="${esc(x)}" ${x===cur?"selected":""}>${esc(x)}</option>`).join("");
function locInit(){
  const c=$("lc");if(!c)return;
  c.innerHTML=locOpts(COUNTRIES,"Rwanda",L("— Choose country —","— Hitamo igihugu —"));
  c.value="Rwanda";locUp("c");
}
function locUp(level){
  const c=$("lc"),pv=$("lp"),d=$("ld"),s=$("ls");
  const other=c&&c.value!=="Rwanda"&&c.value!=="";
  ["lp","ld","ls"].forEach(i=>{const e=$(i);if(e)e.style.display=other?"none":""});
  const x=$("locx");if(x)x.style.display=other?"":"none";
  if(other){
    const list=COUNTRY_PROV[c.value]||[];
    const k=$("lpk"),t=$("lpt");
    if(k){k.style.display=list.length?"":"none";if(level==="c"||!k.options.length)k.innerHTML=locOpts(list,"",L("— Choose —","— Hitamo —"))}
    if(t)t.style.display=list.length?"none":"";
    const dd=COUNTRY_DIST[c.value];const dk=$("ldk");
    if(dk&&dd){dk.style.display="";dk.innerHTML=locOpts(dd[k?k.value:""]||[],"",L("— Choose district —","— Hitamo akarere —"))}
    else if(dk)dk.style.display="none";
    if(t&&dd)t.style.display="none";
    if(k&&dd)k.onchange=()=>locUp("p");
    if(dd){const dk2=$("ldk");if(dk2&&!dk2.innerHTML)dk2.innerHTML=""}
    return;
  }
  if(level==="c"){
    const rw=c.value==="Rwanda";
    pv.innerHTML=rw?locOpts(Object.keys(RW_PROV),"",L("— Choose province —","— Hitamo intara —")):locOpts([],"",L("Not needed","Ntibikenewe"));
    pv.disabled=!rw;
  }
  if(level==="c"||level==="p"){
    const list=RW_PROV[pv.value]||[];
    d.innerHTML=locOpts(list,"",L("— Choose district —","— Hitamo akarere —"));
    d.disabled=!list.length;
  }
  if(level==="c"||level==="p"||level==="d"){
    const list=RW_SECT[d.value]||[];
    s.innerHTML=locOpts(list,"",list.length?L("— Choose sector —","— Hitamo umurenge —"):L("Sectors not added yet","Imirenge ntirashyirwamo"));
    s.disabled=!list.length;
  }
}
function locGet(){
  const c=$("lc")?$("lc").value:"";
  if(c&&c!=="Rwanda"){const k=$("lpk"),kv=k&&k.style.display!=="none"?k.value:"";const dkv=$("ldk")&&$("ldk").style.display!=="none"?$("ldk").value:"";return {country:c,province:kv||($("lpt")?$("lpt").value.trim():""),district:dkv||($("ldt")?$("ldt").value.trim():""),sector:($("lst")?$("lst").value.trim():"")}}
  const pv=$("lp")?$("lp").value:"",d=$("ld")?$("ld").value:"",s=$("ls")?$("ls").value:"";
  return {country:c,province:pv,district:d,sector:s};
}
function auth(su){
  $("nav").style.display="none";
  const hi=hero(),ft=[["📈",L("Track Sales","Kurikirana Igurisha")],["📦",L("Manage Products","Gucunga Ibicuruzwa")],["👥",L("Follow Customers","Gukurikirana Abakiriya")],["📄",L("Get Real Reports","Kubona Raporo Nyazo")]];
  $("app").innerHTML=`<div class="au"><div class="wrap">
  <div class="lg"><select onchange="PF.lang=this.value;savePF();route()" style="width:auto;margin:0;padding:6px 8px;font-size:12px;background:#0d241d;color:#f2fbf7;border:1px solid #17463a">${LANGS.map(x=>`<option ${(PF.lang||"English")===x?"selected":""}>${x}</option>`).join("")}</select></div>
  <div class="brand" style="margin-top:4px"><div class="logo"><img src="${LOGO}" alt="BizzAssist"></div><div><h1>Bizz<span>Assist</span> Rwanda</h1><p>Smart Business Assistant</p></div></div>
  <div class="hero">${okImg(hi)?`<img class="himg" src="${hi}" alt="">`:""}<div class="ht ${okImg(hi)?"":"full"}"><h2>${L("Welcome to","Murakaza neza kuri")}<br>Bizz<span>Assist</span> Rwanda</h2><p class="tl">${L("Manage your business, grow your profits — all in one place.","Cunga ubucuruzi bwawe, uzamure inyungu — byose ahantu hamwe.")}</p>${ft.map(f=>`<div class="feat"><i>${f[0]}</i>${f[1]}</div>`).join("")}</div></div>
  <div class="c" style="margin-top:14px"><div style="display:flex;gap:12px;align-items:center;margin-bottom:12px"><div class="avatar" style="width:50px;height:50px;font-size:24px">👤</div><div><h3 style="font-size:19px;margin:0;display:block">${su?L("Create Your Account","Fungura Konti Yawe"):L("Login to Your Account","Injira muri Konti Yawe")}</h3><p class="mu" style="margin:2px 0 0;font-size:12.5px">${su?L("Start managing your business today.","Tangira gucunga ubucuruzi bwawe uyu munsi."):L("Welcome back! Please sign in to continue.","Murakaza neza! Injira kugira ngo ukomeze.")}</p></div></div>
  ${su?`<div style="display:flex;justify-content:center;margin:4px 0 10px">${photoField("u",{img:tmpImg})}</div><div class="ai"><i>👤</i><input id="a1" placeholder="${L("Full Name","Amazina yuzuye")}"></div><div class="ai"><i>🏪</i><input id="a2" placeholder="${L("Business Name","Izina ry'ubucuruzi")}"></div>`:""}
  ${su?`<div class="ai"><i>📱</i><input id="a3" inputmode="tel" placeholder="${L("Phone number","Numero ya telefone")}" autocomplete="tel"></div><div class="ai"><i>✉️</i><input id="a6" inputmode="email" placeholder="${L("Email","Email")}" autocomplete="email"></div><label style="margin-top:6px">🌍 ${L("Location","Aho uherereye")}</label><select id="lc" onchange="locUp('c')" style="margin-bottom:8px"></select><select id="lp" onchange="locUp('p')" style="margin-bottom:8px"></select><select id="ld" onchange="locUp('d')" style="margin-bottom:8px"></select><select id="ls" style="margin-bottom:8px"></select><div id="locx" style="display:none"><select id="lpk" style="display:none;margin-bottom:8px"></select><select id="ldk" style="display:none;margin-bottom:8px"></select><input id="lpt" placeholder="${L("Province / region","Intara / agace")}" style="margin-bottom:8px"><input id="ldt" placeholder="${L("District / city","Akarere / umujyi")}" style="margin-bottom:8px"><input id="lst" placeholder="${L("Sector / area (optional)","Umurenge / agace (si ngombwa)")}" style="margin-bottom:8px"></div>`:`<div class="ai"><i>✉️</i><input id="a3" placeholder="${L("Email or Phone Number","Email cyangwa Numero ya Telefone")}" autocomplete="username"></div>`}
  <div class="ai"><i>🔒</i>${pwf("a4",L("Password","Ijambobanga"),su?"new-password":"current-password",false,su)}</div>
  ${su?`<div class="ai"><i>🔒</i>${pwf("a5",L("Confirm Password","Subiramo Ijambobanga"),"new-password")}</div>`:""}
  <div class="err" id="ae"></div>
  <button class="btn" onclick="${su?"signup()":"login()"}">${su?L("Create Account","Fungura Konti"):"➜ "+L("Login","Injira")}</button>
  <div class="or">${L("OR","CYANGWA")}</div>
  <button class="gb" onclick="googleInfo()"><span style="font-weight:800;color:#4285f4">G</span> ${L("Continue with Google","Komeza na Google")}</button>
  <p class="sw">${su?L("Already have an account?","Usanzwe ufite konti?"):L("Don't have an account?","Nta konti ufite?")} <a href="#/${su?"login":"signup"}">${su?L("Login","Injira"):L("Create Account","Fungura Konti")} ›</a></p></div>
  <p class="mu" style="text-align:center;margin-top:16px;font-size:12.5px">🛡️ ${L("Your data is safe with BizzAssist Rwanda","Amakuru yawe afite umutekano kuri BizzAssist Rwanda")}</p></div></div>`;
  $("app").querySelectorAll("input").forEach(i=>i.addEventListener("keydown",e=>{if(e.key==="Enter")su?signup():login()}));
  if(su){tmpImg="";locInit();pwChk("a4")}
}
function googleInfo(){modal(`<h3>G ${L("Google sign-in","Kwinjira na Google")}</h3><p style="line-height:1.5;margin-bottom:12px">${L("Signing in with Google needs an online server, which this version does not have yet. Please use your email or phone number and a password.","Kwinjira na Google bisaba server ikora kuri internet, iyi version ntayo ifite. Koresha email cyangwa numero ya telefone n'ijambobanga.")}</p><button class="btn" onclick="closeM()">OK</button>`)}
function heroMgr(){
  if(!can("admin"))return toast(L("Only the admin can change this","Admin wenyine ni we ubihindura"));
  heroTmp=hero();
  modal(`<h3>🖼️ ${L("Login screen photo","Ifoto yo kuri login / create account")}</h3><p class="mu" style="font-size:12.5px;line-height:1.4;margin-bottom:10px">${L("This photo appears on the login and create-account screens.","Iyi foto igaragara kuri login na create account.")}</p><div id="hpv" style="height:170px;border-radius:14px;background:var(--fd);display:grid;place-items:center;overflow:hidden;margin-bottom:10px">${okImg(heroTmp)?`<img src="${heroTmp}" alt="" style="width:100%;height:100%;object-fit:cover">`:"🖼️"}</div><input type="file" accept="image/*" onchange="pickImg(this,v=>{heroTmp=v;$('hpv').innerHTML='<img src=&quot;'+v+'&quot; alt=&quot;&quot; style=&quot;width:100%;height:100%;object-fit:cover&quot;>'},900)"><button class="btn o" onclick="heroTmp='';$('hpv').textContent='🖼️'">🗑 ${L("Remove photo","Kuraho ifoto")}</button><div class="g2"><button class="btn o" onclick="closeM()">${L("Cancel","Reka")}</button><button class="btn" onclick="heroSave()">${L("Save","Bika")}</button></div>`);
}
let heroTmp="";
function heroSave(){sv("bizz_hero",heroTmp);logA("Settings changed","Login screen photo");closeM();toast(L("Saved ✔","Byabitswe ✔"))}
const pwOk=p=>String(p).length>=8&&/[A-Za-z]/.test(p)&&/\d/.test(p)&&/[^A-Za-z0-9]/.test(p);
const PWRULES=()=>[[v=>v.length>=8,L("At least 8 characters","Nibura inyuguti 8")],[v=>/[A-Za-z]/.test(v),L("Letters (A–Z, a–z)","Inyuguti (A–Z, a–z)")],[v=>/\d/.test(v),L("Numbers (0–9)","Imibare (0–9)")],[v=>/[^A-Za-z0-9]/.test(v),L("Symbols (! @ # $ % ...)","Ibimenyetso (! @ # $ % ...)")]];
function pwChk(id){
  const box=document.getElementById("pwh_"+id),inp=document.getElementById(id);
  if(!box||!inp)return;
  const v=inp.value||"";
  box.innerHTML=PWRULES().map(r=>{const ok=r[0](v);const col=!v?"var(--mu)":ok?"#22c55e":"#ff4d4d";return `<div style="color:${col};font-size:12px;line-height:1.6">${ok?"✔":"✖"} ${r[1]}</div>`}).join("");
}
const okPh=v=>/^(\+?250|0)?7[2389]\d{7}$/.test(String(v).replace(/[\s-]/g,""));
const EM_TYPO={"gmial.com":"gmail.com","gmai.com":"gmail.com","gmail.co":"gmail.com","gmal.com":"gmail.com","gnail.com":"gmail.com","gamil.com":"gmail.com","yaho.com":"yahoo.com","yahooo.com":"yahoo.com","hotmial.com":"hotmail.com","hotmal.com":"hotmail.com","outlok.com":"outlook.com","iclod.com":"icloud.com"};
const EM_BAD=["mailinator.com","tempmail.com","10minutemail.com","guerrillamail.com","yopmail.com","trashmail.com","throwawaymail.com","sharklasers.com","getnada.com","fakeinbox.com","dispostable.com","temp-mail.org","maildrop.cc"];
function emCheck(v){
  const e=String(v||"").trim().toLowerCase();
  if(!/^[a-z0-9._%+-]+@[a-z0-9-]+(\.[a-z0-9-]+)*\.[a-z]{2,24}$/.test(e)||/\.\./.test(e)||/^[._-]|[._-]@/.test(e))return {ok:false,msg:L("Email is not valid.","Email si yo.")};
  const d=e.split("@")[1];
  if(EM_BAD.includes(d))return {ok:false,msg:L("Temporary email addresses are not accepted. Use your real email.","Email z'igihe gito ntizemewe. Koresha email yawe nyayo.")};
  if(EM_TYPO[d])return {ok:false,msg:L("Did you mean ","Wari washatse kuvuga ")+e.replace(d,EM_TYPO[d])+"?"};
  return {ok:true,msg:"",email:e};
}
const okEm=v=>emCheck(v).ok;
function signup(){
  const g=i=>($(i)?$(i).value.trim():""),n=g("a1"),b=g("a2"),ph=g("a3"),em=g("a6"),p=$("a4").value,p2=$("a5").value;
  const idv=ph?nid(ph):em.toLowerCase();
  const e=n.length<2?L("Write your full name.","Andika amazina yawe yuzuye."):b.length<2?L("Write the business name.","Andika izina rya business."):(!ph||!em)?L("Enter both a phone number and an email.","Andika numero ya telefone n'email byombi."):(ph&&!okPh(ph))?L("Phone number is not valid.","Numero ya telefone si yo."):(em&&!okEm(em))?emCheck(em).msg:!pwOk(p)?L("Password must be 8+ characters with letters, numbers and symbols.","Password igomba kuba nibura inyuguti 8, harimo inyuguti, imibare n'ibimenyetso."):p!==p2?L("Passwords do not match.","Passwords ntizihuye."):U.some(u=>(nid(u.id)===nid(idv))||(em&&u.email&&u.email.toLowerCase()===em.toLowerCase()))?L("This account already exists.","Iyi konti isanzweho."):"";
  $("ae").textContent=e;if(e)return;
  const loc=locGet();
  if(!loc.country)return $("ae").textContent=L("Choose your country.","Hitamo igihugu cyawe.");
  if(loc.country==="Rwanda"&&(!loc.province||!loc.district))return $("ae").textContent=L("Choose your province and district.","Hitamo intara n'akarere.");
  if(loc.country!=="Rwanda"&&!loc.district)return $("ae").textContent=L("Write your district or city.","Andika akarere cyangwa umujyi wawe.");
  if(loc.country==="Rwanda"&&loc.district&&!loc.sector)return $("ae").textContent=L("Choose your sector.","Hitamo umurenge wawe.");
  const user={name:n,biz:b,id:idv,ph:ph?nid(ph):"",email:emCheck(em).email||em.toLowerCase(),pw:p,img:tmpImg||"",loc,role:"Administrator",active:true,last:Date.now()};
  U.push(user);SE={name:n,biz:b,id:idv,role:"Administrator"};sv("bizz_session",SE);save();logA("Account created",n);go("#/home");
}
function login(){
  const raw=$("a3").value.trim(),id=nid(raw),em=raw.toLowerCase(),u=U.find(x=>(nid(x.id)===id||(x.email&&x.email===em))&&x.pw===$("a4").value);
  if(!u){$("ae").textContent="Email/telefone cyangwa password si byo.";return}
  if(u.active===false){$("ae").textContent="Konti yawe yahagaritswe. Vugana na Admin.";return}
  u.last=Date.now();SE={name:u.name,biz:u.biz,id:u.id,role:u.role||"Administrator"};sv("bizz_session",SE);save();go("#/home");
}
function logout(){SE=null;try{LS.removeItem("bizz_session")}catch(e){}go("#/login")}

/* HOME / DASHBOARD */
function home(){
  const t=agg(0),y=agg(1),lo=P.filter(p=>p.s<=(p.lw||10)).length,h=new Date().getHours();
  page(`<span>${h<12?"Good morning":h<18?"Good afternoon":"Good evening"}</span>, ${esc(SE.name.split(" ")[0])}!`,"Manage your business, grow your profits",
  `<div class="g2">${card("🛒","Today's Sales",fmt(t.t),dl(t.t,y.t))}${card("📈","Today's Profit",fmt(t.p),dl(t.p,y.p))}${card("🧾","Today's Orders",t.n,dl(t.n,y.n))}${card("⚠️","Low Stock",lo,"items")}</div>
  ${can("admin")&&pend().length?`<div class="c" style="display:flex;align-items:center;gap:10px"><div class="em">🔐</div><div class="m"><b>${pend().length} ubusabe bw'uruhushya butegereje</b><small>Staff are asking for approval</small></div><button class="add" onclick="notif()">${L("View","Reba")}</button></div>`:""}${debtBanner()}${featHTML()}${aiCard()}
  <div class="c"><h3>⚡ Quick Actions</h3><div class="g2" style="margin:0">${qaHTML()}</div></div>${stockCard()}`,{nav:"home"});homeStock();fsInit();
}

/* SALES */
let sT="All",sQ="";
function sales(){
  const t=agg(0),y=agg(1);
  page("Sales","Manage your sales and track your revenue",
  `<div class="g2">${card("🛒","Total Sales",fmt(t.t),dl(t.t,y.t))}${card("🧾","Orders",t.n,dl(t.n,y.n))}${card("👥","Avg. Order",fmt(t.n?t.t/t.n:0),"")}${card("🪙","Profit",fmt(t.p),dl(t.p,y.p))}</div>
  <button class="btn" onclick="go('#/sale')">＋ Add New Sale</button>
  <input id="sq" placeholder="🔍 Search customer or invoice…" oninput="sQ=this.value;sr()">
  <div class="tabs">${["All","Completed","Pending"].map(x=>`<button class="tab ${x===sT?"on":""}" onclick="sT='${x}';sales()">${x}</button>`).join("")}</div><div id="sl"></div>`,{back:"#/home",nav:"sales"});
  $("sq").value=sQ;sr();
}
function sr(){
  const q=sQ.toLowerCase();
  $("sl").innerHTML=S.filter(s=>(sT==="All"||s.st===sT)&&(!q||(s.cu+inv(s.id)).toLowerCase().includes(q)))
  .map(s=>`<div class="row" onclick="go('#/receipt/${s.id}')"><div class="em">👤</div><div class="m"><b>${esc(s.cu)}</b><small>${s.items.length} items • ${inv(s.id)}<br>${when(s.t)}</small></div><div class="r"><b>${fmt(s.tot)}</b><span class="bd ${s.st==="Completed"?"in":"low"}">${s.st}</span>${s.debt>0?`<br><small class="neg">Ideni ${fmt(s.debt)} • ${dday(s.due)}</small>`:""}</div></div>`).join("")||'<div class="emp">No sales found.</div>';
}

let cart=[],pm="Cash",ps="Paid",custPhone="",dDays=5,paidNow="",mmNet="mtn",mmVia="code",mmAmt="",mmFrom="";
const discAmt=s=>{const v=+($("dv")||{}).value||0,t=($("dvt")||{}).value;return Math.round(Math.max(0,Math.min(t==="%"?s*v/100:v,s)))},
ctot=()=>{const s=csub();return s-discAmt(s)},
saleT=()=>{const e=$("sdt");if(!e||!e.value||e.value===ymd(new Date()))return Date.now();const d=new Date(e.value+"T"+new Date().toTimeString().slice(0,8));return isNaN(d)?Date.now():d.getTime()},
dueNow=()=>{const t=ctot();return ps==="Paid"?(pm==="Mobile Money"&&mmAmt!==""?Math.max(0,Math.min(+mmAmt||0,t)):t):ps==="Partial"?Math.max(0,Math.min(+paidNow||0,t)):0},
dday=t=>new Date(t).toLocaleDateString("en-GB",{day:"2-digit",month:"short",year:"numeric"}),
dues=()=>S.filter(s=>s.debt>0&&s.due&&s.due<=Date.now()),
myDec=()=>SE?Reqs.filter(r=>r.uid===SE.id&&(r.status==="approved"||r.status==="rejected")&&!r.seen):[],
ncount=()=>SE&&PF.notif?P.filter(p=>p.s<=(p.lw||10)).length+(can("admin")?openReqs().length:0)+dues().length+myDec().length:0,
bellUpd=()=>{const b=$("bell");if(b){const n=ncount();b.innerHTML="🔔"+(n?`<em>${n}</em>`:"")}};

/* SOUND + DUE CHECK */
let AC=null;
const actx=()=>{try{if(!AC)AC=new (window.AudioContext||window.webkitAudioContext)();if(AC.state==="suspended")AC.resume();return AC}catch(e){return null}},
TONES={chime:[[880,0,.25],[1175,.22,.45]],bell:[[1318,0,.5],[987,.28,.55],[1318,.56,.7]],beep:[[800,0,.15],[800,.25,.15]],alert:[[660,0,.16],[880,.2,.16],[660,.4,.16],[880,.6,.3]],ring:[0,1,2,3,4,5].flatMap(i=>[[880,i*.8,.35],[1100,i*.8+.4,.35]]),siren:Array.from({length:17},(_,k)=>[600+k*25,k*.18,.2]),melody:[[523,0,.6],[659,.7,.6],[784,1.4,.6],[659,2.1,.6],[784,2.8,.6],[1047,3.5,1.2]]};
function ping(t,force,cat){
  if(!force&&(PF.snd===false||(cat&&PF["snd"+cat]===false)))return;
  if((t||PF.tone)==="custom"){
    if(!window.CUSTOM_URL)return ping("chime",true);
    const au=new Audio(window.CUSTOM_URL);au.volume=Math.min(1,(PF.vol===undefined?80:PF.vol)/100);au.play().catch(()=>{});
    try{if(navigator.vibrate)navigator.vibrate([120,60,120])}catch(e){}
    return;
  }
  const c=actx();if(!c)return;
  (TONES[t||PF.tone]||TONES.chime).forEach(([f,at,du])=>{
    const o=c.createOscillator(),g=c.createGain(),s=c.currentTime+at;
    o.type="sine";o.frequency.value=f;
    g.gain.setValueAtTime(0.0001,s);g.gain.exponentialRampToValueAtTime(Math.max(.02,(PF.vol===undefined?80:PF.vol)/100*.5),s+.02);g.gain.exponentialRampToValueAtTime(.0001,s+du);
    o.connect(g);g.connect(c.destination);o.start(s);o.stop(s+du+.05);
  });
  try{if(navigator.vibrate)navigator.vibrate([120,60,120])}catch(e){}
}
addEventListener("pointerdown",()=>actx(),{once:true});
function checkDue(){
  if(!SE)return;
  const now=Date.now();
  const bn=m=>{if(PF.bn&&window.Notification&&Notification.permission==="granted"){try{new Notification("BizzAssist Rwanda",{body:m})}catch(e){}}};
  const dec=myDec().filter(r=>!r.nt);
  if(dec.length){dec.forEach(r=>r.nt=1);save();const ok=dec.some(r=>r.status==="approved"),m=ok?L("✅ Admin approved your request. You can continue.","✅ Admin yemeye ubusabe bwawe. Ushobora gukomeza."):L("❌ Admin rejected your request.","❌ Admin yanze ubusabe bwawe.");toast(m);ping(ok?"chime":"beep",false,"A");bn(m)}
  const np=can("admin")?pend().filter(r=>!r.an):[];
  if(np.length){np.forEach(r=>r.an=1);save();const m=trP(L("🔐 New approval request: ","🔐 Ubusabe bushya bw'uruhushya: "))+np[0].user;toast(m);ping("alert",false,"R");bn(m)}
  const nw=S.filter(s=>s.debt>0&&s.due&&s.due<=now&&(!s.al||now-s.al>864e5));
  bellUpd();
  if(nw.length){
    nw.forEach(s=>s.al=now);save();
    const m=nw.length===1?L(`⏰ ${nw[0].cu} must pay ${fmt(nw[0].debt)}`,`⏰ ${nw[0].cu} agomba kwishyura ${fmt(nw[0].debt)}`):L(`⏰ ${nw.length} customers have debts that are due`,`⏰ Abakiriya ${nw.length} bafite ideni ryageze igihe cyo kwishyura`);
    toast(m);ping(null,false,"D");bn(m)
  }
  bellUpd();
}
function debtBanner(){
  const d=S.filter(s=>s.debt>0);if(!d.length)return "";
  const tt=d.reduce((a,s)=>a+s.debt,0),ov=dues().length;
  return `<div class="c" style="display:flex;align-items:center;gap:10px"><div class="em">💳</div><div class="m"><b>Ideni: ${fmt(tt)} (${d.length})</b><small>${ov?`⏰ ${ov} ryageze igihe cyo kwishyura`:"Nta ryageze igihe"}</small></div><button class="add" onclick="sT='Pending';go('#/sales')">${L("View","Reba")}</button></div>`;
}

function saleNew(){
  cart=[];pm="Cash";ps="Paid";custPhone="";dDays=5;paidNow="";mmNet="mtn";mmVia="code";mmAmt="";mmFrom="";
  page("Add Sale","Record a new sale and generate receipt",
  `<div id="dbn"></div><div id="sumc" style="display:grid;grid-template-columns:repeat(3,1fr);gap:8px;margin-bottom:12px"></div>
  <div class="c"><h3>👤 Customer</h3>${can("admin")?`<label>${L("Sale date","Itariki y'igurisha")}</label><input id="sdt" type="date" value="${ymd(new Date())}" max="${ymd(new Date())}">`:""}
  <label>Hitamo customer usanzwe ufite</label>
  <select id="csel" onchange="pickCu(this.value)"><option value="">— Walk-in / Customer mushya —</option>${C.map((c,i)=>`<option value="${i}">${esc(c.n)}${c.ph?" • "+esc(c.ph):""}</option>`).join("")}</select>
  <label>Cyangwa andika customer mushya</label>
  <input id="cn" placeholder="Customer name (empty = walk-in)" oninput="cuTyped()"><input id="cp" inputmode="tel" placeholder="Phone (e.g. 0788123456)" oninput="custPhone=this.value;cuTyped();momoUI()">
  <label id="svw" style="display:none;align-items:center;color:var(--tx);font-size:13px"><input type="checkbox" id="svc" checked style="width:auto;margin:0 8px 0 0"> Bika nka customer mushya</label><div id="cinfo"></div></div>
  <div class="c"><h3>📦 Products</h3><div style="display:flex;gap:8px;align-items:center"><input id="pq" placeholder="🔍 Search products…" oninput="pl()" style="flex:1"><button type="button" class="ib" style="height:44px;margin-bottom:10px;min-width:48px" aria-label="Scan" onclick="scanOpen()">📷</button></div><div class="tabs" id="sct"></div><div id="pl"></div></div>
  <div class="c"><h3>🛒 Cart <button class="ib" onclick="cart=[];cb()">🗑 Clear all</button></h3><div id="cl"></div><div style="display:flex;gap:8px"><input id="dv" type="number" min="0" inputmode="numeric" placeholder="Discount" oninput="tot()" style="flex:1"><select id="dvt" onchange="tot()" style="width:84px"><option>RWF</option><option>%</option></select></div><div id="tt"></div></div>
  <div class="c"><h3>💳 Payment Method</h3><div class="opt" id="po"></div><div id="momo"></div><h3 style="margin-top:12px">Payment Status</h3><div class="opt" id="pst"></div><div id="pdet"></div></div>
  <div class="c"><label>Notes (optional)</label><textarea id="snote" rows="2" placeholder="Add any additional notes…" style="margin:0"></textarea></div>
  <div class="g2"><button class="btn o" onclick="saveDraft()">💾 Save as Draft</button><button class="btn" onclick="finishSale()">✔ Complete Sale</button></div>`,{back:"#/sales",nav:"sales"});
  pl();cb();chips();cuTyped();sumUpd();draftBanner();
}
function pickCu(i){const c=i===""?null:C[+i];$("cn").value=c?c.n:"";$("cp").value=c?c.ph:"";custPhone=c?c.ph:"";cuTyped();momoUI()}
function cuTyped(){
  const n=$("cn").value.trim(),ph=$("cp").value.trim();
  const ex=C.some(c=>c.n.toLowerCase()===n.toLowerCase()&&nid(c.ph)===nid(ph));
  $("svw").style.display=n&&!ex?"flex":"none";cinfoUpd();
}
const chip=(a,cur,v)=>a.map(x=>`<button class="op ${x===cur?"on":""}" onclick="${v}='${x}';chips()">${x}</button>`).join("");
function chips(){
  $("po").innerHTML=chip(["Cash","Mobile Money","Bank Transfer","Card","Other"],pm,"pm");
  $("pst").innerHTML=chip(["Paid","Partial","Debt"],ps,"ps");
  momoUI();pdet();sumUpd();
}
function pdet(){
  const el=$("pdet");
  if(ps==="Paid"){el.innerHTML="";return}
  const pre=[1,3,5,7,14,30];
  el.innerHTML=`${ps==="Partial"?`<label style="margin-top:10px">Amafaranga yishyuwe ubu (RWF)</label><input id="pdv" type="number" min="0" inputmode="numeric" placeholder="Urugero: 2000" value="${esc(paidNow)}" oninput="paidNow=this.value;pcalc();momoUI()">`:""}
  <div class="tt big" id="pcalc" style="font-size:15px"></div>
  <label style="margin-top:10px">Igihe cyo kwishyura ideni (iminsi)</label>
  <div class="opt">${pre.map(d=>`<button class="op ${dDays===d?"on":""}" onclick="dDays=${d};pdet()">${d}</button>`).join("")}</div>
  <input id="ddv" type="number" min="1" inputmode="numeric" style="margin-top:8px" placeholder="Cyangwa andika iminsi" value="${pre.includes(dDays)?"":dDays}" oninput="dDays=Math.max(1,parseInt(this.value)||5);pcalc()">
  <div class="mu" id="ddl" style="font-size:12.5px"></div>`;
  pcalc();
}
function pcalc(){
  const e=$("pcalc");if(!e)return;
  const t=ctot(),pd=ps==="Debt"?0:Math.max(0,Math.min(+paidNow||0,t));
  e.innerHTML=`<span>Ideni risigaye</span><span>${fmt(t-pd)}</span>`;
  $("ddl").textContent="Azishyura bitarenze: "+dday(Date.now()+dDays*864e5)+" ("+dDays+" iminsi)";
}
function mmCfg(net,via){
  const code=net==="mtn"?PF.mtn:PF.air,num=net==="mtn"?PF.mtnN:PF.airN;
  const v=(via==="code"&&code)||(via==="num"&&num)?via:(code?"code":num?"num":via);
  const to=v==="code"?code:num,T=net==="mtn"?(v==="code"?PF.mtnT:PF.mtnNT):(v==="code"?PF.airT:PF.airNT);
  return {net,N:net==="mtn"?"MTN MoMo":"Airtel Money",via:v,to,T};
}
const ussd=(c,a)=>c.T.replace("{code}",c.to).replace("{number}",c.to).replace("{amount}",Math.round(a));
function dialModal(c,a){
  if(!c.to||!c.T)return modal(`<h3>⚙️ ${c.N}: ${L("not set up","ntiyashyizweho")}</h3><p style="line-height:1.5;margin-bottom:12px">${can("admin")?L("Set the receiving code or number in Settings → Mobile Money.","Shyiraho code cyangwa numero yo kwakira muri Settings → Mobile Money."):L("The admin has not set the receiving code/number yet. Please ask the admin.","Admin ntarashyiraho code/numero yo kwakira. Baza Admin.")}</p>${can("admin")?`<button class="btn" onclick="mmCodes()">${L("Set now","Shyiraho ubu")}</button>`:""}<button class="btn o" onclick="closeM()">${L("Close","Funga")}</button>`);
  const u=ussd(c,a);
  modal(`<h3>📲 ${c.N} • ${fmt(a)}</h3><p class="mu" style="margin-bottom:10px;line-height:1.5">${L("Dial this on the customer's phone (or give it to the customer). The network will ask for the MoMo PIN on that phone.","Kanda iyi code kuri telefone ya customer (cyangwa muyimuhe). Network izamusaba PIN ya MoMo kuri iyo telefone.")}</p><div class="c" style="text-align:center;font-size:18px;font-weight:700;word-break:break-all">${esc(u)}</div><a class="btn" style="display:grid;place-items:center;text-decoration:none" href="tel:${encodeURIComponent(u)}">📞 ${L("Open dialer","Fungura dialer")}</a><button class="btn o" onclick="cpTxt('${esc(u)}')">📋 ${L("Copy code","Koporora code")}</button><button class="btn o" onclick="closeM()">${L("Close","Funga")}</button>`);
}
function momoUI(){
  const e=$("momo");if(!e)return;
  if(pm!=="Mobile Money"){e.innerHTML="";return}
  const c=mmCfg(mmNet,mmVia),due=dueNow(),paidMode=ps==="Paid",amt=paidMode&&mmAmt!==""?mmAmt:due;
  e.innerHTML=`<div class="c" style="margin:10px 0 0;background:var(--fd)"><b>📱 Mobile Money</b>
  <div class="opt" style="margin:8px 0">${[["mtn","MTN MoMo"],["air","Airtel Money"]].map(x=>`<button class="op ${mmNet===x[0]?"on":""}" onclick="mmNet='${x[0]}';momoUI()">${x[1]}</button>`).join("")}</div>
  <div class="opt" style="margin:0 0 8px">${[["code",L("Merchant code","Code y'ubucuruzi")],["num",L("Phone number","Numero ya telefone")]].map(x=>`<button class="op ${c.via===x[0]?"on":""}" onclick="mmVia='${x[0]}';momoUI()">${x[1]}</button>`).join("")}</div>
  <div class="tt"><span>${L("Pay to","Kwishyura kuri")} ${c.N}</span><b>${c.to?esc(c.to):`<span class="neg">${L("Not set by admin","Admin ntarashyiraho")}</span>`}</b></div>
  <label>${L("Amount (automatic — you can edit)","Amafaranga (ahita aza — ushobora kuyahindura)")}</label><input id="mma" type="number" min="0" inputmode="numeric" value="${amt}" ${paidMode?"":"disabled"} oninput="mmAmt=this.value">
  <label>${L("Customer MoMo number (money leaves this number)","Numero ya MoMo ya customer (amafaranga akurwaho)")}</label><input id="mmf" inputmode="tel" value="${esc(mmFrom||($("cp")?$("cp").value:""))}" oninput="mmFrom=this.value">
  <div class="g2" style="margin:0"><button class="btn" onclick="momoPay()">📲 ${L("Dial MoMo","Fungura MoMo")}</button><button class="btn o" onclick="momoSms()">📩 ${L("Request by SMS","Saba kuri SMS")}</button></div>
  <p class="mu" style="font-size:11.5px;line-height:1.4;margin:8px 0 0">${L("The customer approves on their own phone by entering their MoMo PIN there. Never type a PIN in this app.","Customer yemeza kuri telefone ye ashyiramo PIN ya MoMo ye aho. Ntuzigere ushyira PIN muri iyi app.")}</p></div>`;
}
function msgModal(title,ph,msg){
  const p=ph.replace(/[\s-]/g,""),w=p.replace(/^\+/,"").replace(/^0/,"250");
  modal(`<h3>${title}</h3><textarea id="mmsg" rows="5">${esc(msg)}</textarea>
  <a class="btn" style="display:grid;place-items:center;text-decoration:none" href="sms:${esc(p)}?body=${encodeURIComponent(msg)}" target="_blank" rel="noopener">📩 Fungura SMS</a>
  <a class="btn o" style="display:grid;place-items:center;text-decoration:none" href="https://wa.me/${esc(w)}?text=${encodeURIComponent(msg)}" target="_blank" rel="noopener">💬 WhatsApp</a>
  <button class="btn o" onclick="cpTxt($('mmsg').value)">📋 Copy message</button><button class="btn o" onclick="closeM()">Close</button>`);
}
function cpTxt(t){navigator.clipboard?navigator.clipboard.writeText(t).then(()=>toast("Byakopowe ✔")).catch(()=>toast("Copy ntibashije")):toast("Copy ntibashije")}
function mmInfo(){const c=mmCfg(mmNet,mmVia);return {net:c.net,via:c.via,to:c.to||"",from:(mmFrom||($("cp")?$("cp").value:"")).trim(),amt:dueNow()}}
function momoSms(){
  const a=dueNow(),ph=(mmFrom||$("cp").value).trim(),n=$("cn").value.trim(),c=mmCfg(mmNet,mmVia);
  if(!ph)return toast(L("Enter the customer's phone number","Andika telefone ya customer"));
  if(!(a>0))return toast(L("No amount to pay","Nta mafaranga yo kwishyura"));
  const msg=L(`Hello${n?" "+n:""}, please pay ${fmt(a)} to ${SE.biz} via ${c.N}${c.to?(c.via==="code"?" merchant code ":" number ")+c.to:""}. Thank you!`,`Muraho${n?" "+n:""}, mwasabwe kwishyura ${fmt(a)} kuri ${SE.biz} ukoresheje ${c.N}${c.to?(c.via==="code"?" code ":" numero ")+c.to:""}. Murakoze!`);
  msgModal("📩 "+L("Payment request","Ubusabe bwo kwishyura"),ph,msg);
}
function momoPay(){
  const a=dueNow();if(!(a>0))return toast(L("No amount to pay","Nta mafaranga yo kwishyura"));
  dialModal(mmCfg(mmNet,mmVia),a);
}
function momoConfirm(a,t){
  const c=mmCfg(mmNet,mmVia);
  modal(`<h3>📱 ${L("Confirm Mobile Money payment","Emeza kwishyura kuri Mobile Money")}</h3>
  <div class="c" style="background:var(--fd)"><div class="tt"><span>${L("Network","Network")}</span><b>${c.N}</b></div><div class="tt"><span>${L("Paid to","Yishyuwe kuri")}</span><b>${esc(c.to||"-")}</b></div><div class="tt"><span>${L("From customer number","Ivuye kuri numero ya customer")}</span><b>${esc((mmFrom||$("cp").value).trim()||"-")}</b></div><div class="tt big"><span>${L("Amount","Amafaranga")}</span><span>${fmt(a)}</span></div>${a<t?`<div class="tt mu"><span>${L("Remaining as debt","Asigaye ni ideni")}</span><span>${fmt(t-a)}</span></div>`:""}</div>
  <p style="line-height:1.5;margin:10px 0">${L("The customer receives the MoMo message on their phone and approves it by entering their MoMo PIN there. Confirm only after you have received the money.","Customer abona ubutumwa bwa MoMo kuri telefone ye akemeza ashyiramo PIN ya MoMo ye. Emeza ari uko wamaze kwakira amafaranga.")}</p>
  <label class="ck"><input type="checkbox" id="mmok"> ${L("Customer approved with their MoMo PIN and the money is received","Customer yemeje ashyizemo PIN ya MoMo kandi amafaranga yinjiye")}</label>
  <div class="g2"><button class="btn o" onclick="closeM()">${L("Cancel","Reka")}</button><button class="btn" onclick="if(!$('mmok').checked)return toast(L('Tick the confirmation first','Banza ushyire ikimenyetso'));completeSaleAction()">✔ ${L("Confirm","Emeza")}</button></div>`);
}
function mmCodes(){
  if(!can("admin"))return toast(L("Only the admin can change this","Admin wenyine ni we ubihindura"));
  const f=(t,a,b,c,d)=>`<h4 style="margin:10px 0 4px">${t}</h4><label>${L("Merchant code","Code y'ubucuruzi")}</label><input id="${a}" inputmode="numeric" value="${esc(PF[b])}"><label>${L("Phone number","Numero ya telefone")}</label><input id="${c}" inputmode="tel" value="${esc(PF[d])}">`;
  modal(`<div style="max-height:75vh;overflow:auto"><h3>📲 ${L("Mobile Money receiving","Kwakira amafaranga kuri Mobile Money")}</h3><p class="mu" style="font-size:12.5px;line-height:1.4">${L("Only the admin sets these. Staff see them automatically when taking MoMo payments. In the USSD text use {code}, {number} and {amount}.","Admin wenyine ni we ubishyiraho. Abakozi babibona ubwabyo bakira MoMo. Muri USSD koresha {code}, {number} na {amount}.")}</p>
  ${f("MTN MoMo","mc1","mtn","mn1","mtnN")}<label>USSD (${L("code","code")})</label><input id="mt1" value="${esc(PF.mtnT)}"><label>USSD (${L("number","numero")})</label><input id="mt3" value="${esc(PF.mtnNT)}">
  ${f("Airtel Money","mc2","air","mn2","airN")}<label>USSD (${L("code","code")})</label><input id="mt2" placeholder="*182*...*{code}*{amount}#" value="${esc(PF.airT)}"><label>USSD (${L("number","numero")})</label><input id="mt4" placeholder="*182*...*{number}*{amount}#" value="${esc(PF.airNT)}">
  <div class="g2"><button class="btn o" onclick="closeM()">${L("Cancel","Reka")}</button><button class="btn" onclick="mmS()">${L("Save","Bika")}</button></div></div>`);
}
function mmS(){
  const g=i=>$(i).value.trim();
  PF.mtn=g("mc1");PF.mtnN=g("mn1");PF.mtnT=g("mt1");PF.mtnNT=g("mt3");PF.air=g("mc2");PF.airN=g("mn2");PF.airT=g("mt2");PF.airNT=g("mt4");
  savePF();logA("Settings changed","Mobile Money");closeM();toast(L("Saved ✔","Byabitswe ✔"));
}
const opts=p=>[...(p.sg!==false?[{u:"s",n:p.u||"Piece",q:1,p:p.p,c:p.c}]:[]),...(p.pk||[]).map(k=>({u:k.n,n:k.n,q:k.q,p:k.p,c:k.c}))],
unitOf=(p,u)=>opts(p).find(o=>o.u===u)||{u,n:u==="s"?(p.u||"Piece"):u,q:1,p:p.p,c:p.c},
uprice=l=>l.pp!=null?l.pp:unitOf(gp(l.id),l.u).p,
ltotc=l=>Math.round(uprice(l)*l.q),
ltot=l=>l.tot!=null?l.tot:Math.round(l.p*l.q),
stkTxt=p=>{const b=(p.pk||[]).reduce((m,r)=>!m||r.q>m.q?r:m,null);return b?"≈ "+Math.floor(+(p.s/b.q).toFixed(6))+" "+b.n+" + "+(+(p.s%b.q).toFixed(3))+" pcs":""},
used=id=>{const p=gp(id);return cart.filter(x=>x.id===id).reduce((a,l)=>a+l.q*unitOf(p,l.u).q,0)},
fit=id=>used(id)<=gp(id).s+1e-9;
function pqty(s){
  s=String(s).trim().replace(/,/g,".").replace(/[÷:]/g,"/");
  if(!s)return NaN;
  let m=s.match(/^(\d+(?:\.\d+)?)\s+(\d+)\s*\/\s*(\d+)$/);
  if(m){const d=+m[3];return d?(+m[1])+(+m[2])/d:NaN}
  m=s.match(/^(\d+(?:\.\d+)?)\s*\/\s*(\d+(?:\.\d+)?)$/);
  if(m){const d=+m[2];return d?(+m[1])/d:NaN}
  m=s.match(/^\d+(?:\.\d+)?$/);
  return m?+s:NaN;
}
function pl(){
  const q=$("pq").value.toLowerCase();
  $("sct").innerHTML=`<button class="tab ${saleCat?"":"on"}" onclick="saleCat='';pl()">${L("All","Byose")}</button>`+cats().map((k,i)=>`<button class="tab ${saleCat===k?"on":""}" onclick="saleCat=cats()[${i}];pl()">${esc(k)}</button>`).join("");
  $("pl").innerHTML=P.filter(p=>p.act!==false&&(!saleCat||p.k===saleCat)&&p.s>0&&p.n.toLowerCase().includes(q)).map(p=>({p,av:opts(p).map((o,i)=>({o,i})).filter(x=>x.o.q<=p.s+1e-9)})).filter(x=>x.av.length).map(({p,av})=>`<div class="row" style="cursor:default"><div class="em">${pim(p)}</div><div class="m"><b>${esc(p.n)}</b><small>Stock: ${p.s} ${esc(p.u||"")}${stkTxt(p)?"<br>"+stkTxt(p):""}</small></div><div style="display:flex;flex-direction:column;gap:6px">${av.map(x=>`<button class="add" style="padding:5px 9px;font-size:12px" onclick="ac(${p.id},${x.i})">＋ ${esc(x.o.n)} ${fmt(x.o.p)}</button>`).join("")}</div></div>`).join("")||'<div class="emp">No products.</div>';
}
function ac(id,oi){
  const p=gp(id),o=opts(p)[oi];if(!o)return;
  const l=cart.find(x=>x.id===id&&x.u===o.u),old=l?l.q:0;
  if(l){l.q=+(l.q+1).toFixed(3);l.t=String(l.q)}else cart.push({id,u:o.u,q:1,t:"1"});
  if(!fit(id)){if(l){l.q=old;l.t=String(old)}else cart.pop();toast("Stock ni "+p.s+" pieces gusa")}
  cb();
}
function qt(i,d){
  const l=cart[i];if(!l)return;
  const old=l.q,n=+(l.q+d).toFixed(3);
  if(n<=0){cart.splice(i,1);return cb()}
  l.q=n;l.t=String(n);
  if(!fit(l.id)){l.q=old;l.t=String(old);toast("Stock ni "+gp(l.id).s+" pieces gusa")}
  cb();
}
function qs(i,v){
  const l=cart[i];if(!l)return;
  const n=pqty(v);
  if(!(n>0)){toast("Umubare si wo. Koresha 3, 1.5 cyangwa 1÷2");return cb()}
  const old=l.q,ot=l.t;l.q=+n.toFixed(3);l.t=String(v).trim().replace(/\//g,"÷");
  if(!fit(l.id)){l.q=old;l.t=ot;toast("Stock ni "+gp(l.id).s+" pieces gusa")}
  cb();
}
let saleCat="";
function qLive(i,v){
  const l=cart[i];if(!l)return;const n=pqty(v);if(!(n>0))return;
  const old=l.q,ot=l.t;l.q=+n.toFixed(3);l.t=String(v).trim().replace(/\//g,"÷");
  if(!fit(l.id)){l.q=old;l.t=ot;return}
  const e=$("lt"+i);if(e)e.textContent=fmt(ltotc(l));tot();
}
function sumUpd(){
  const e=$("sumc");if(!e)return;
  const c=(i,l,v)=>`<div class="s" style="padding:8px;gap:8px;flex-direction:column;align-items:flex-start"><small>${i} ${l}</small><b style="font-size:13.5px">${v}</b></div>`;
  e.innerHTML=c("🛒",L("Items","Ibicuruzwa"),cart.length)+c("🏷️",L("Total","Igiteranyo"),fmt(ctot()))+c("💳",L("Payment","Kwishyura"),ps==="Paid"?"✅ "+L("Paid","Byishyuwe"):ps==="Partial"?"◐ "+L("Partial","Igice"):"⏳ "+L("Debt","Ideni"));
}
function cinfoUpd(){
  const e=$("cinfo");if(!e)return;
  const n=$("cn").value.trim(),ph=$("cp").value.trim(),c=n?C.find(x=>x.n.toLowerCase()===n.toLowerCase()&&(!ph||!x.ph||nid(x.ph)===nid(ph))):null;
  if(!c){e.innerHTML="";return}
  const ss=S.filter(s=>s.cu.toLowerCase()===c.n.toLowerCase()),bal=ss.reduce((a,s)=>a+(s.debt||0),0);
  e.innerHTML=`<div class="rw" style="margin-top:8px"><i class="ic">${esc(c.n[0].toUpperCase())}</i><div class="m"><b>${esc(c.n)} <span class="tg2">${ss.length>=3?L("Regular Customer","Umukiriya usanzwe"):L("Customer","Umukiriya")}</span></b><small>📞 ${esc(c.ph||"-")}${c.loc?" • 📍 "+esc(c.loc):""}</small><small>${L("Total purchases","Ibyaguzwe byose")}: ${ss.length} • ${L("Balance","Ideni")}: <b style="color:${bal?"var(--am)":"var(--g)"}">${fmt(bal)}</b></small></div></div>`;
}
function saveDraft(){
  if(!cart.length)return toast(L("Cart is empty","Cart irimo ubusa"));
  sv("bizz_draft",{cart,cn:$("cn").value,cp:$("cp").value,dv:$("dv").value,dvt:$("dvt").value,pm,ps,paidNow,dDays,note:$("snote").value,t:Date.now()});
  logA("Sale draft saved",cart.length+" items");toast(L("Draft saved ✔","Draft yabitswe ✔"));
}
function draftBanner(){
  const d=ld("bizz_draft",null),e=$("dbn");if(!e)return;
  e.innerHTML=d&&d.cart&&d.cart.length?`<div class="c" style="display:flex;align-items:center;gap:10px"><div class="em">📝</div><div class="m"><b>${L("Saved draft","Draft yabitswe")}: ${d.cart.length} ${L("items","ibicuruzwa")}</b><small>${when(d.t)}</small></div><button class="add" onclick="loadDraft()">${L("Continue","Komeza")}</button><button class="ib" onclick="try{LS.removeItem('bizz_draft')}catch(e){};draftBanner()">🗑</button></div>`:"";
}
function loadDraft(){
  const d=ld("bizz_draft",null);if(!d)return;
  cart=(d.cart||[]).filter(l=>gp(l.id));pm=d.pm||"Cash";ps=d.ps||"Paid";paidNow=d.paidNow||"";dDays=d.dDays||5;
  $("cn").value=d.cn||"";$("cp").value=d.cp||"";$("dv").value=d.dv||"";$("dvt").value=d.dvt||"RWF";$("snote").value=d.note||"";
  try{LS.removeItem("bizz_draft")}catch(e){}
  cb();chips();cuTyped();draftBanner();toast(L("Draft loaded","Draft yafunguwe"));
}
function qdiv(i){const e=$("qi"+i);if(!e)return;e.value=e.value.replace(/÷+$/,"")+"÷";e.focus()}
function qrm(i){cart.splice(i,1);cb()}
function pEd(i){
  const l=cart[i],p=gp(l.id),o=unitOf(p,l.u);
  modal(`<h3>✏️ Igiciro cya ${esc(o.n)}</h3><p class="mu" style="margin-bottom:10px">${esc(p.n)} • Igiciro risanzwe: ${fmt(o.p)}</p><input id="pep" type="number" min="0" inputmode="numeric" value="${uprice(l)}"><div class="g2"><button class="btn o" onclick="closeM()">Cancel</button><button class="btn" onclick="pEdS(${i})">Save</button></div>`);
}
function pEdS(i){const v=$("pep").value;if(v===""||!(+v>=0))return toast("Andika igiciro");cart[i].pp=Math.round(+v);closeM();cb()}
function cb(){
  $("cl").innerHTML=cart.map((l,i)=>{const p=gp(l.id),o=unitOf(p,l.u);return`<div class="row" style="cursor:default;flex-wrap:wrap"><div class="em">${pim(p)}</div><div class="m"><b>${esc(p.n)}</b><small><span class="chip" style="padding:1px 8px;font-size:11px">${esc(o.n)}${o.q>1?" ("+o.q+" pcs)":""}</span> ${fmt(uprice(l))}${l.pp!=null?" ✎":""}</small></div><b id="lt${i}">${fmt(ltotc(l))}</b><div style="flex-basis:100%;display:flex;gap:6px;align-items:center;justify-content:flex-end"><button class="ib" onclick="pEd(${i})">✏️</button><button class="ib" onclick="qt(${i},-1)">−</button><input id="qi${i}" inputmode="decimal" value="${esc(l.t)}" oninput="qLive(${i},this.value)" onchange="qs(${i},this.value)" style="width:84px;text-align:center;margin:0;padding:8px"><button class="ib" onclick="qdiv(${i})">÷</button><button class="ib" onclick="qt(${i},1)">＋</button><button class="ib" style="border-color:var(--rd);color:var(--rd)" onclick="qrm(${i})">🗑</button></div></div>`}).join("")||'<div class="emp">Cart is empty. Tap ＋ on a product.</div>';
  tot();
}
const csub=()=>cart.reduce((a,l)=>a+ltotc(l),0);
function tot(){const s=csub(),d=discAmt(s);$("tt").innerHTML=`<div class="tt"><span>Subtotal</span><b>${fmt(s)}</b></div><div class="tt"><span>Discount</span><b>- ${fmt(d)}</b></div><div class="tt big"><span>Total</span><span>${fmt(s-d)}</span></div>`;if($("pcalc"))pcalc();momoUI();sumUpd()}

function finishSale(){
  if(!cart.length)return toast(L("Pick a product first","Hitamo igicuruzwa mbere"));
  const t=ctot(),cu=$("cn").value.trim();
  if(ps==="Paid"&&pm==="Mobile Money"&&mmAmt!==""&&(+mmAmt||0)<t){
    if(!(+mmAmt>0))return toast(L("Enter the amount","Andika amafaranga"));
    ps="Partial";paidNow=String(Math.round(+mmAmt));chips();
    toast(L("Amount is less than the total — saved as a partial payment","Amafaranga ari munsi y'igiteranyo — byanditswe nk'igice cyishyuwe"));
  }
  const a=dueNow();
  if(ps!=="Paid"){
    if(!cu)return toast(L("Enter or choose a customer who owes","Andika cyangwa uhitemo umukiriya ufite ideni"));
    if(ps==="Partial"&&!(a>0&&a<t))return toast(L("Enter the amount paid (less than ","Andika amafaranga yishyuwe (munsi ya ")+fmt(t)+")");
  }
  if(pm==="Mobile Money"&&a>0)momoConfirm(a,t);else completeSaleAction();
}
function completeSaleAction(){
  if(!cart.length){closeM();return}
  const items=cart.map(l=>{const p=gp(l.id),o=unitOf(p,l.u);return{id:p.id,n:p.n,e:p.e,u:o.n,uq:o.q,p:uprice(l),c:o.c,q:l.q,qt:l.t,tot:ltotc(l)}});
  const sb=items.reduce((a,l)=>a+l.tot,0),d=discAmt(sb),cost=items.reduce((a,l)=>a+l.c*l.q,0);
  const id=S.reduce((m,s)=>Math.max(m,s.id),0)+1;
  const cu=$("cn").value.trim(),cuName=cu||"Walk-in Customer",ph=$("cp").value.trim();
  const total=sb-d,paid=ps==="Paid"?total:ps==="Partial"?Math.max(0,Math.min(+paidNow||0,total)):0,debt=total-paid;
  if(cu&&$("svc")&&$("svc").checked&&!C.some(c=>c.n.toLowerCase()===cu.toLowerCase()&&nid(c.ph)===nid(ph)))C.push({n:cu,ph,loc:""});
  const due=debt>0?Date.now()+dDays*864e5:0;
  S.unshift({id,by:SE.name,biz:SE.biz,mm:pm==="Mobile Money"?mmInfo():null,note:$("snote")?$("snote").value.trim():"",cu:cuName,ph,items,disc:d,sub:sb,tot:total,pf:total-cost,st:debt>0?"Pending":"Completed",pm,pay:ps,paid,debt,days:dDays,due,al:0,pays:paid>0?[{t:saleT(),a:paid,m:pm}]:[],t:saleT()});
  cart.forEach(l=>{const p=gp(l.id),o=unitOf(p,l.u),pcs=+(l.q*o.q).toFixed(3);p.s=+(p.s-pcs).toFixed(3);(p.mv=p.mv||[]).unshift({t:Date.now(),type:"out",q:pcs,u:SE.name,r:"Sale ("+l.t+" "+o.n+")"})});
  save();closeM();
  toast(debt>0?"Ideni "+fmt(debt)+" ryanditswe • "+dday(due):"Sale yabitswe ✔");
  go("#/receipt/"+id);
}
function payDebt(id){
  const s=S.find(x=>x.id===id);if(!s||!(s.debt>0))return;
  modal(`<h3>💵 Andika ubwishyu</h3><p class="mu" style="margin-bottom:10px">${esc(s.cu)} • Ideni: ${fmt(s.debt)}</p>
  <label>Amafaranga yishyuye (RWF)</label><input id="pdA" type="number" min="1" inputmode="numeric" value="${s.debt}">
  <label>Uburyo</label><select id="pdM"><option>Cash</option><option>Mobile Money</option><option>Bank Transfer</option><option>Card</option></select>
  <label>Iminsi y'inyongera ku asigaye (niba atarangije)</label><input id="pdD" type="number" min="0" inputmode="numeric" placeholder="Urugero: 5">
  <div class="g2"><button class="btn o" onclick="closeM()">Cancel</button><button class="btn" onclick="payDebtS(${id})">Save</button></div>`);
}
function payDebtS(id){
  const s=S.find(x=>x.id===id),a=Math.round(+$("pdA").value);
  if(!s||!(a>0))return toast("Andika amafaranga");
  if(a>s.debt)return toast("Ideni ni "+fmt(s.debt)+" gusa");
  s.paid=(s.paid||0)+a;s.debt-=a;(s.pays=s.pays||[]).push({t:Date.now(),a,m:$("pdM").value});
  if(s.debt<=0){s.debt=0;s.st="Completed";s.due=0;s.pay="Paid"}
  else{const d=parseInt($("pdD").value,10);if(d>0){s.due=Date.now()+d*864e5;s.al=0;s.days=d}}
  save();closeM();toast(s.debt?"Ubwishyu bwabitswe ✔":"Ideni ryishyuwe ryose ✔");route();
}
function remindSms(id){
  const s=S.find(x=>x.id===id);if(!s)return;
  if(!s.ph)return toast("Nta telefone ya customer");
  msgModal("📩 Ubwibutsa kwishyura",s.ph,`Muraho ${s.cu}, mwibutswe kwishyura ideni rya ${fmt(s.debt)} (${inv(s.id)}) kuri ${SE.biz}.${PF.mtn?" MTN MoMo code: "+PF.mtn+".":""} Murakoze!`);
}
const C39={"0":"nnnwwnwnn","1":"wnnwnnnnw","2":"nnwwnnnnw","3":"wnwwnnnnn","4":"nnnwwnnnw","5":"wnnwwnnnn","6":"nnwwwnnnn","7":"nnnwnnwnw","8":"wnnwnnwnn","9":"nnwwnnwnn","A":"wnnnnwnnw","B":"nnwnnwnnw","C":"wnwnnwnnn","D":"nnnnwwnnw","E":"wnnnwwnnn","F":"nnwnwwnnn","G":"nnnnnwwnw","H":"wnnnnwwnn","I":"nnwnnwwnn","J":"nnnnwwwnn","K":"wnnnnnnww","L":"nnwnnnnww","M":"wnwnnnnwn","N":"nnnnwnnww","O":"wnnnwnnwn","P":"nnwnwnnwn","Q":"nnnnnnwww","R":"wnnnnnwwn","S":"nnwnnnwwn","T":"nnnnwnwwn","U":"wwnnnnnnw","V":"nwwnnnnnw","W":"wwwnnnnnn","X":"nwnnwnnnw","Y":"wwnnwnnnn","Z":"nwwnwnnnn","-":"nwnnnnwnw",".":"wwnnnnwnn"," ":"nwwnnnwnn","*":"nwnnwnwnn"};
function bar39(t){
  const s="*"+t.toUpperCase().replace(/[^0-9A-Z.\- ]/g,"")+"*";let x=0,r="";
  for(const ch of s){const pt=C39[ch];if(!pt)continue;for(let i=0;i<9;i++){const w=pt[i]==="w"?3:1;if(i%2===0)r+=`<rect x="${x}" y="0" width="${w}" height="40" fill="#12281f"/>`;x+=w}x+=1}
  return `<svg class="bc" viewBox="0 0 ${x} 40" width="${Math.min(230,Math.round(x*1.5))}" height="40" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">${r}</svg>`;
}
const pmTxt=s=>s.pm+(s.mm&&s.mm.to?" • "+(s.mm.net==="mtn"?"MTN":"Airtel")+" "+s.mm.to:"");
function printWith(){
  const body=document.body;
  body.classList.add("printing");
  let ok=typeof window.print==="function";
  if(ok){try{window.print()}catch(e){ok=false}}
  setTimeout(()=>body.classList.remove("printing"),2500);
  return ok;
}
function printFile(html,title){
  const css=[...document.querySelectorAll("style")].map(s=>s.textContent).join("");
  const doc='<!doctype html><html><head><meta charset="utf-8"><meta name="viewport" content="width=device-width,initial-scale=1"><title>'+title+'</title><style>'+css+'body{background:#fff!important;color:#000}#app,#nav,.top,.toast,.md,#hpanel{display:none!important}#rcp,#rpb{display:block!important}</style></head><body>'+html+'</body></html>';
  saveFile(title.replace(/[^\w\- ]/g,"").trim().replace(/\s+/g,"-")+".html",doc);
  toast(L("Open the downloaded file, then press Print or Save as PDF","Fungura dosiye yamanuwe, hanyuma ukande Print cyangwa Save as PDF"));
}
const PVLIBS={h2c:"https://cdnjs.cloudflare.com/ajax/libs/html2canvas/1.4.1/html2canvas.min.js",jspdf:"https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"};
function loadLib(url,check){
  return new Promise((res,rej)=>{
    if(check())return res();
    const s=document.createElement("script");s.src=url;
    s.onload=()=>check()?res():rej(new Error("lib"));s.onerror=()=>rej(new Error("lib"));
    document.head.appendChild(s);
  });
}
function openPreview(html,title){
  let v=document.getElementById("pvw");
  if(!v){v=document.createElement("div");v.id="pvw";document.body.appendChild(v)}
  v.dataset.title=title;
  v.innerHTML='<div class="pv-bar"><b>'+esc(title)+'</b><div class="pv-acts"><select id="pvs" class="pv-b" onchange="pvSize(this.value)" style="padding:8px"><option value="a4">A4</option><option value="80">80 mm</option><option value="58">58 mm</option></select><button class="pv-b" onclick="pvPrint()">🖨 '+L("Print","Sohora")+'</button><button class="pv-b pv-p" onclick="pvPdf()">💾 '+L("Save as PDF","Bika nka PDF")+'</button><button class="pv-b" onclick="pvClose()">✕</button></div></div><div class="pv-sheet"><div class="pv-paper" id="pvp">'+html+'</div></div><div class="pv-msg" id="pvm"></div>';
  v.classList.add("on");
}
function pvSize(sz){
  const paper=document.getElementById("pvp");if(!paper)return;
  paper.dataset.size=sz;
  paper.style.maxWidth=sz==="a4"?"800px":(sz+"mm");
  paper.style.fontSize=sz==="58"?"9px":sz==="80"?"10.5px":"";
  paper.style.padding=sz==="a4"?"16px":"6px";
}
function pvClose(){const v=document.getElementById("pvw");if(v){v.classList.remove("on");v.innerHTML=""}}
function pvPrint(){
  const p=document.getElementById("prn"),paper=document.getElementById("pvp");
  const sz=(paper&&paper.dataset.size)||"a4";
  const pageCss=sz==="a4"?"":"<style>@page{size:"+sz+"mm auto;margin:2mm}</style>";
  if(p&&paper)p.innerHTML=pageCss+paper.innerHTML;
  if(!printWith())toast(L("Print is not available on this phone — use Save as PDF","Print ntiboneka kuri telefone — koresha Bika nka PDF"));
}
function makePdf(lines,title){
  const clean=s=>String(s).replace(/\t/g,"   ").replace(/[\u{1F000}-\u{1FAFF}\u2600-\u27BF\uFE0F\u200D]/gu,"").replace(/[\u2013\u2014]/g,"-").replace(/[\u2018\u2019]/g,"'").replace(/[\u201C\u201D]/g,'"').replace(/[\u2022\u25CF]/g,"*").replace(/\u20A3|\u20A3/g,"RWF").split("").map(c=>{const n=c.charCodeAt(0);return n>=32&&n<=126?c:(n>=160&&n<=255?c:"?")}).join("");
  const W=595,H=842,M=42,LH=13,FS=10,maxChars=92;
  const wrapped=[];
  lines.forEach(l=>{const t=clean(l).replace(/\s+$/,"");if(!t){wrapped.push("");return}
    let s=t;while(s.length>maxChars){let cut=s.lastIndexOf(" ",maxChars);if(cut<20)cut=maxChars;wrapped.push(s.slice(0,cut));s=s.slice(cut).replace(/^\s+/,"")}wrapped.push(s)});
  const perPage=Math.floor((H-M*2)/LH),pages=[];
  for(let i=0;i<wrapped.length;i+=perPage)pages.push(wrapped.slice(i,i+perPage));
  if(!pages.length)pages.push([""]);
  const esc2=s=>s.replace(/\\/g,"\\\\").replace(/\(/g,"\\(").replace(/\)/g,"\\)");
  const objs=[];
  const add=s=>{objs.push(s);return objs.length};
  const fontId=add("<< /Type /Font /Subtype /Type1 /BaseFont /Courier /Encoding /WinAnsiEncoding >>");
  const pagesId=objs.length+1+pages.length; // reserved below
  const catalogIdx=null;
  const pageIds=[];
  pages.forEach(lines2=>{
    let y=H-M-FS;let stream="BT /F1 "+FS+" Tf "+LH+" TL "+M+" "+y+" Td\n";
    lines2.forEach((l,i)=>{stream+="("+esc2(l)+") Tj T*\n"});
    stream+="ET";
    const cid=add("<< /Length "+stream.length+" >>\nstream\n"+stream+"\nendstream");
    const pid=add("<< /Type /Page /Parent "+pagesId+" 0 R /MediaBox [0 0 "+W+" "+H+"] /Contents "+cid+" 0 R /Resources << /Font << /F1 "+fontId+" 0 R >> >> >>");
    pageIds.push(pid);
  });
  const pagesObj=add("<< /Type /Pages /Kids ["+pageIds.map(i=>i+" 0 R").join(" ")+"] /Count "+pageIds.length+" >>");
  const catalog=add("<< /Type /Catalog /Pages "+pagesObj+" 0 R >>");
  let out="%PDF-1.4\n";const offs=[];
  objs.forEach((o,i)=>{offs.push(out.length);out+=(i+1)+" 0 obj\n"+o+"\nendobj\n"});
  const xref=out.length;
  out+="xref\n0 "+(objs.length+1)+"\n0000000000 65535 f \n"+offs.map(o=>String(o).padStart(10,"0")+" 00000 n \n").join("");
  out+="trailer\n<< /Size "+(objs.length+1)+" /Root "+catalog+" 0 R /Info << /Title ("+esc2(clean(title))+") >> >>\nstartxref\n"+xref+"\n%%EOF";
  const bytes=new Uint8Array(out.length);for(let i=0;i<out.length;i++)bytes[i]=out.charCodeAt(i)&255;
  return new Blob([bytes],{type:"application/pdf"});
}
async function pvPdf(){
  const v=document.getElementById("pvw"),paper=document.getElementById("pvp");
  const title=(v&&v.dataset.title)||"document";
  const name=title.replace(/[^\w\- ]/g,"").trim().replace(/\s+/g,"-")||"document";
  const msg=document.getElementById("pvm");
  if(msg)msg.textContent=L("Preparing PDF…","Turimo gutegura PDF…");
  try{
    const text=paper?paper.innerText:"";
    const blob=makePdf(text.split("\n"),title);
    saveFile(name+".pdf",blob);
  }catch(e){
    printFile(paper?paper.innerHTML:"",name);
  }
  if(msg)msg.textContent="";
}
function printRcp(name){
  const title=(name||"BizzAssist Rwanda").replace(/[<>&]/g,"");
  const src=document.getElementById("rcp")||document.getElementById("rpb")||document.getElementById("app");
  let el=document.getElementById("prn");
  if(!el){el=document.createElement("div");el.id="prn";document.body.appendChild(el)}
  const head=src.id==="rcp"?"":'<h2 class="prn-t" style="font-family:sans-serif;color:#000">'+title+'</h2>';
  el.innerHTML=head+src.outerHTML;
  openPreview(el.innerHTML,title);
}

function pdfRcp(){printRcp("receipt")}
function receipt(id){
  const s=S.find(x=>x.id===id);if(!s)return go("#/sales");
  const biz=s.biz||SE.biz,ow=U.find(u=>(u.role||"Administrator")==="Administrator"&&u.biz===biz)||me()||{};
  const dt=new Date(s.t),dd=dt.toLocaleDateString("en-GB",{day:"2-digit",month:"short",year:"numeric"}),tm=dt.toLocaleTimeString("en-US",{hour:"2-digit",minute:"2-digit"});
  const walk=s.cu==="Walk-in Customer",tag=walk?"Walk-in Customer":"Customer",stt=s.debt>0?(s.pay==="Partial"?"Partial":"Debt"):"Paid";
  const vat=PF.tax?fmt(s.tot*18/118):"";
  const rowsA=s.items.map((l,i)=>{const p=gp(l.id);return`<div class="it5"><span>${i+1}</span><span class="pn"><i class="th">${p?pim(p):esc(l.e||"📦")}</i><span><b>${esc(l.n)}</b><small>${esc(l.u||"Piece")}${p?" • Stock: "+p.s:""}</small></span></span><span>${esc(l.qt||l.q)}</span><span>${fmt(l.p)}</span><span>${fmt(ltot(l))}</span></div>`}).join("");
  const rowsB=s.items.map((l,i)=>`<div class="r5"><span>${i+1}</span><span><b>${esc(l.n)}</b><br><small>${esc(l.u||"Piece")}</small></span><span>${esc(l.qt||l.q)}</span><span>${fmt(l.p)}</span><span>${fmt(ltot(l))}</span></div>`).join("");
  const debtA=s.debt>0?`<div class="rw"><i class="ic">⏳</i><div class="m"><small>Yishyuwe / Ideni</small><b>${fmt(s.paid||0)} / <span class="neg">${fmt(s.debt)}</span></b><small>Igihe cyo kwishyura: ${dday(s.due)}</small></div></div>`:"";
  const debtB=s.debt>0?`<div class="ln"><span>Yishyuwe</span><span>${fmt(s.paid||0)}</span></div><div class="ln"><span>Ideni</span><b style="color:#c0392b">${fmt(s.debt)}</b></div><div class="ln"><span>Igihe cyo kwishyura</span><span>${dday(s.due)}</span></div>`:"";
  page("Sale Confirmation & Receipt","Your sale has been completed successfully",
  `<div class="ok no-p"><i>✔</i><h2>Sale Completed!</h2><p>The sale was recorded successfully.</p><span class="inv">${inv(s.id)}</span></div>
  <div class="c no-p"><div class="rw"><i class="ic">👤</i><div class="m"><small>Customer</small><b>${esc(s.cu)}</b>${s.ph?`<small>${esc(s.ph)}</small>`:""}</div><span class="tg2">${tag}</span></div>
  <div class="rw"><i class="ic">📅</i><div class="m"><small>Date & Time</small><b>${dd} - ${tm}</b></div></div>
  <div class="rw"><i class="ic">💳</i><div class="m"><small>Payment Method</small><b>${esc(pmTxt(s))}</b></div><span class="tg2 ${stt}">${stt}</span></div>${debtA}
  <div class="rw"><i class="ic">💰</i><div class="m"><small>Total Amount</small></div><b class="pos" style="font-size:20px">${fmt(s.tot)}</b></div></div>
  <div class="c no-p"><h3>🛒 Items Sold (${s.items.length})</h3><div class="it5 h"><span>#</span><span>Product</span><span>Qty</span><span>Price</span><span>Total</span></div>${rowsA}
  <div class="tt"><span>Subtotal</span><span>${fmt(s.sub)}</span></div><div class="tt"><span>Discount</span><span>${fmt(s.disc)}</span></div>${vat?`<div class="tt mu"><span>VAT 18% (included)</span><span>${vat}</span></div>`:""}<div class="tt big"><span>Total Amount</span><span>${fmt(s.tot)}</span></div></div>
  <div class="c no-p" style="display:flex;gap:10px;align-items:center"><div class="em">👍</div><div class="m"><b>Thank you!</b><small>Your support helps our business grow.</small></div></div>
  <div class="rcp" id="rcp"><div class="rh"><div class="logo"><img src="${LOGO}" alt="BizzAssist"></div><div><b>Bizz<span>Assist</span> Rwanda</b><small>Smart Business Assistant</small><small>Better Management • Bigger Growth</small></div></div>
  <h3>SALES RECEIPT</h3><div class="mid">${inv(s.id)}</div>
  <div class="two"><div><b>${esc(biz)}</b><small>📍 ${esc(ow.loc||"Rwanda")}</small>${ow.ph?`<small>📞 ${esc(ow.ph)}</small>`:""}</div><div style="text-align:right"><small>📅 ${dd}</small><small>🕘 ${tm}</small>${s.by?`<small>Served by: ${esc(s.by)}</small>`:""}</div></div>
  <div class="cu"><span style="font-size:20px">👤</span><div><small>Customer</small><b>${esc(s.cu)}</b>${s.ph?`<small>${esc(s.ph)}</small>`:""}</div><span class="tg2">${tag}</span></div>
  <div class="r5 h"><span>#</span><span>Product</span><span>Qty</span><span>Price</span><span>Total</span></div>${rowsB}
  <div class="dash"></div><div class="ln"><span>Subtotal</span><span>${fmt(s.sub)}</span></div><div class="ln"><span>Discount</span><span>${fmt(s.disc)}</span></div>${vat?`<div class="ln"><span>VAT 18% (included)</span><span>${vat}</span></div>`:""}${debtB}
  ${s.note?`<div class="ln"><span>${L("Note","Icyitonderwa")}</span><span>${esc(s.note)}</span></div>`:""}<div class="ttl"><span>Total Amount</span><span>${fmt(s.tot)}</span></div>
  <div class="pay"><span style="font-size:20px">💳</span><div><small>Payment Method</small><b>${esc(pmTxt(s))}</b></div><span class="tg2" style="margin-left:auto;background:${stt==="Paid"?"#0f8a4f":stt==="Partial"?"#f5a524":"#c0392b"};color:#fff">${stt}</span></div>
  <div class="dash"></div><div class="ty"><b>Thank you for your purchase!</b><small>— ${esc(biz)} —</small></div>${bar39(inv(s.id).slice(1))}<div style="text-align:center"><small>Smart Business Assistant</small></div></div>
  ${s.debt>0?`<div class="g2 no-p"><button class="btn" onclick="payDebt(${s.id})">💵 Andika ubwishyu</button><button class="btn o" onclick="remindSms(${s.id})">📩 Ubwibutsa</button></div>`:""}
  <div class="g2 no-p"><button class="btn o" onclick="printRcp()">🖨 Print</button><button class="btn o" onclick="share(${s.id})">↗ Share</button><button class="btn o" onclick="waInv(${s.id})">💬 WhatsApp</button><button class="btn o" onclick="pdfRcp()">⬇ Download PDF</button><button class="btn" onclick="go('#/sale')">＋ New Sale</button></div>
  <button class="btn o no-p" onclick="go('#/sales')">Back to Sales</button>`,{back:"#/sales",nav:"sales"});
}
function waInv(id){
  const s=S.find(x=>x.id===id);if(!s)return;
  const lines=[`${s.biz||SE.biz} — ${inv(id)}`,`${s.cu} • ${when(s.t)}`,...s.items.map(l=>`• ${l.n} (${l.u||"Piece"}) x${l.qt||l.q} = ${fmt(ltot(l))}`),`${L("Total","Igiteranyo")}: ${fmt(s.tot)}`];
  if(s.debt>0)lines.push(`${L("Paid","Imelipwa")}: ${fmt(s.paid||0)} • ${L("Debt","Deni")}: ${fmt(s.debt)}`);
  lines.push(L("Thank you!","Murakoze!"));
  const txt=lines.join("\n");
  let num=String(s.ph||"").replace(/\D/g,"");
  if(/^07\d{8}$/.test(num))num="250"+num.slice(1);
  if(/^7\d{8}$/.test(num))num="250"+num;
  const url="https://wa.me/"+(num||"")+"?text="+encodeURIComponent(txt);
  const w=window.open(url,"_blank");
  if(!w){if(navigator.share)navigator.share({text:txt}).catch(()=>{});else cpTxt(txt)}
}
function share(id){
  const s=S.find(x=>x.id===id);if(!s)return;
  const t=`${s.biz||SE.biz} - ${inv(id)}\n${s.cu} - ${when(s.t)}\n`+s.items.map(l=>`${l.n} (${l.u||"Piece"}) x${l.qt||l.q} = ${fmt(ltot(l))}`).join("\n")+`\nTotal: ${fmt(s.tot)}${s.debt>0?"\nIdeni: "+fmt(s.debt):""}\nMurakoze!`;
  if(navigator.share)navigator.share({text:t}).catch(()=>{});
  else if(navigator.clipboard)navigator.clipboard.writeText(t).then(()=>toast("Receipt yakopowe ✔")).catch(()=>toast("Share ntiboneka"));
  else toast("Share ntiboneka");
}

/* PRODUCTS */
let pQ="",pC="";
let pT="all";
function products(){
  const tv=P.reduce((a,p)=>a+p.s*p.c,0),c=k=>P.filter(p=>st(p)===k).length;
  page(L("Products","Ibicuruzwa"),L("Manage all your products","Gucunga ibicuruzwa byose"),
  `<div class="g2">${card("📦",L("Total products","Ibicuruzwa byose"),P.length,"")}${card("✅",L("In stock","Bihari"),c("in"),"")}${card("⚠️",L("Running low","Bigiye gushira"),c("low"),"")}${card("💰",L("Total value","Agaciro kose"),fmt(tv),"")}</div>
  <div class="tabs" id="pTb"></div>
  <input id="pq2" placeholder="${L("🔍 Search products…","🔍 Shakisha ibicuruzwa…")}" oninput="pQ=this.value;pr()"><select id="pk" onchange="pC=this.value;pr()"><option value="">${L("All categories","Ibyiciro byose")}</option>${cats().map(k=>`<option ${k===pC?"selected":""}>${esc(k)}</option>`).join("")}</select><div id="pr"></div><div id="plow"></div>`,
  {back:"#/home",nav:"products",act:`<button class="hb" onclick="pAdd()">＋ ${L("Add","Ongeramo")}</button>`});
  $("pq2").value=pQ;pr();
}
function pr(){
  const q=pQ.toLowerCase(),c=k=>P.filter(p=>st(p)===k).length;
  $("pTb").innerHTML=[["all",L("All","Byose"),P.length],["in",L("In stock","Bihari"),c("in")],["low",L("Low stock","Bigiye gushira"),c("low")],["out",L("Out","Byashize"),c("out")]].map(t=>`<button class="tab ${pT===t[0]?"on":""}" onclick="pT='${t[0]}';pr()">${t[1]} (${t[2]})</button>`).join("");
  $("pr").innerHTML=P.filter(p=>(pT==="all"||st(p)===pT)&&(!pC||p.k===pC)&&(!q||(p.n+code(p)+(p.brand||"")).toLowerCase().includes(q)))
  .map(p=>`<div class="row" onclick="go('#/product/${p.id}')"><div class="em">${pim(p)}</div><div class="m"><b>${esc(p.n)}${p.act===false?` <span class="tg2 Debt">${L("Inactive","Ntikora")}</span>`:""}</b><small>${esc(code(p))} • ${esc(p.k)}${(p.pk||[]).length?" • "+p.pk.map(k=>esc(k.n)).join("/"):""}</small></div><div class="r"><b>${fmt(p.p)}</b><small>Stock ${p.s}</small><br>${badge(p)}</div></div>`).join("")||`<div class="emp">${L("No products found.","Nta gicuruzwa kibonetse.")}</div>`;
  const lo=P.filter(p=>st(p)!=="in").slice(0,5);
  $("plow").innerHTML=lo.length?`<div class="c" style="border-color:var(--am)"><h3 style="color:var(--am)">⚠️ ${L("Products running low","Ibicuruzwa bigiye gushira")}<button class="ib" onclick="pT='low';pr()">${L("View all","Reba byose")}</button></h3>${lo.map(p=>`<div class="row" onclick="go('#/product/${p.id}')"><div class="em">${pim(p)}</div><div class="m"><b>${esc(p.n)}</b><small class="neg">Stock: ${p.s}</small></div>${badge(p)}</div>`).join("")}</div>`:"";
}
let dT="ov",dI=0;
function detail(id){
  const p=gp(id);if(!p)return go("#/products");
  const pf=p.p-p.c,pc=p.p?Math.round(pf/p.p*100):0,sup=SUP.find(s=>s.id===p.sup),imgs=(p.imgs&&p.imgs.length?p.imgs:[p.img]).filter(okImg),pct=Math.min(100,Math.round(p.s/Math.max((p.lw||10)*5,p.s,1)*100));
  if(dI>=imgs.length)dI=0;
  const mv=(p.mv||[]),sh=S.filter(s=>s.items.some(l=>l.id===p.id));
  const tab=dT==="ov"?`<div class="g2" style="align-items:start"><div class="c" style="margin:0"><h3>📄 ${L("Product Information","Ibisobanuro by'igicuruzwa")}</h3>${[[L("Product Name","Izina"),esc(p.n)],[L("Product Code","Code"),esc(code(p))],[L("Category","Icyiciro"),esc(p.k)],[L("Brand","Ikirango"),esc(p.brand||"-")],[L("Unit","Igipimo"),esc(p.u||"Piece")],[L("Selling Price","Igiciro cyo kugurisha"),fmt(p.p)],[L("Purchase Price","Igiciro cyo kugura"),fmt(p.c)],[L("Profit per Unit","Inyungu kuri 1"),fmt(pf)+" ("+pc+"%)"],[L("Location / Shelf","Aho giherereye"),esc(p.loc||"-")],[L("Expiry","Itariki izarangiriraho"),p.exp?edt(p.exp):"-"],[L("Tax rate","Umusoro"),(p.tax||0)+"%"]].map(r=>`<div class="tt"><span class="mu">${r[0]}</span><b style="text-align:right;max-width:55%">${r[1]}</b></div>`).join("")}<div class="tt"><span class="mu">${L("Status","Imiterere")}</span><span class="tg2 ${p.act===false?"Debt":""}">${p.act===false?L("Inactive","Ntikora"):L("Active","Ikora")}</span></div>${sup?`<div class="tt"><span class="mu">🚚 ${L("Supplier","Utanga")}</span><b>${esc(sup.n)}</b></div>`:""}</div>
  <div class="c" style="margin:0"><h3>📦 ${L("Stock Overview","Incamake ya stock")}</h3><div style="display:flex;gap:14px;align-items:center"><div class="ring" style="background:conic-gradient(var(--g) ${pct}%,var(--ln) 0)"><div><b>${p.s}</b><small>${L("items","ibintu")}</small></div></div><div style="flex:1"><div class="tt"><span class="mu">${L("Total stock","Stock yose")}</span><b>${p.s}</b></div><div class="tt"><span class="mu">${L("Low alert","Itangazo ryo gushira")}</span><b style="color:var(--am)">${p.lw||10}</b></div></div></div>${stkTxt(p)?`<p class="mu" style="font-size:12px;margin-top:6px">${stkTxt(p)}</p>`:""}</div></div>
  <div class="c"><h3>⚡ ${L("Quick Actions","Ibikorwa byihuse")}</h3><div class="g2" style="margin:0"><button class="btn" style="margin:0" onclick="smPre='in';gEdit(${id},'sm')">⬇ ${L("Stock In","Ongeramo stock")}</button><button class="btn o" style="margin:0" onclick="smPre='out';gEdit(${id},'sm')">⬆ ${L("Stock Out","Kuramo stock")}</button><button class="btn o" style="margin:0" onclick="gEdit(${id},'edit')">✏️ ${L("Edit Product","Hindura")}</button><button class="btn o" style="margin:0" onclick="labelModal(${id})">🏷 ${L("Print label","Sohora etiketi")}</button><button class="btn o d" style="margin:0" onclick="gEdit(${id},'del')">🗑 ${L("Delete","Siba")}</button></div></div>
  <div class="c"><h3>🕒 ${L("Recent Activity","Ibyakozwe vuba")}<button class="ib" onclick="dT='mv';detail(${id})">${L("View all","Reba byose")}</button></h3>${mvRows(mv.slice(0,5))}</div>`
  :dT==="mv"?`<div class="c"><h3>🔄 ${L("Stock Movement","Imigendekere ya stock")}</h3>${mvRows(mv)}</div>`
  :`<div class="c"><h3>🧾 ${L("Sales History","Amateka y'igurisha")}</h3>${sh.slice(0,40).map(s=>{const ls=s.items.filter(l=>l.id===p.id);return `<div class="row" onclick="go('#/receipt/${s.id}')"><div class="m"><b>${esc(s.cu)}</b><small>${inv(s.id)} • ${when(s.t)}${s.by?" • "+esc(s.by):""}</small></div><div class="r"><b>${fmt(ls.reduce((a,l)=>a+ltot(l),0))}</b><small>${ls.map(l=>esc(l.qt||l.q)+" "+esc(l.u||"")).join(", ")}</small></div></div>`}).join("")||`<div class="emp">${L("No sales yet.","Nta gurisha rirakorwa.")}</div>`}</div>`;
  page(L("Product Details","Ibisobanuro by'igicuruzwa"),L("View and manage product information","Reba kandi ucunge amakuru y'igicuruzwa"),
  `<div class="c"><div class="big-em" style="position:relative">${imgs.length?`<img src="${imgs[dI]}" alt="">`:esc(p.e)}${imgs.length>1?`<span style="position:absolute;left:8px;bottom:8px;background:rgba(0,0,0,.55);color:#fff;border-radius:10px;padding:2px 8px;font-size:11px">${dI+1} / ${imgs.length}</span><button class="ib" style="position:absolute;right:44px;bottom:6px;background:rgba(0,0,0,.5)" onclick="dI=(dI+${imgs.length}-1)%${imgs.length};detail(${id})">‹</button><button class="ib" style="position:absolute;right:6px;bottom:6px;background:rgba(0,0,0,.5)" onclick="dI=(dI+1)%${imgs.length};detail(${id})">›</button>`:""}</div><span class="chip">${esc(p.k)}</span><h2 style="margin:6px 0 2px">${esc(p.n)}</h2><small class="mu">${L("Product Code","Code")}: ${esc(code(p))}</small> ${badge(p)}${p.desc?`<p class="mu" style="margin-top:6px;line-height:1.4">${esc(p.desc)}</p>`:""}</div>
  <div class="g2">${card("🛒",L("Selling Price","Igiciro cyo kugurisha"),fmt(p.p),"/ "+esc(p.u||"piece"))}${card("📥",L("Purchase Price","Igiciro cyo kugura"),fmt(p.c),"")}${card("📦","Stock",p.s+" "+esc(p.u||""),stkTxt(p))}${card("📈",L("Profit / Unit","Inyungu / 1"),fmt(pf),pc+"%")}</div>
  <div class="c" style="padding:6px"><div class="opt" style="grid-template-columns:repeat(3,1fr)">${[["ov",L("Overview","Incamake")],["mv",L("Stock Movement","Stock")],["sh",L("Sales History","Igurisha")]].map(t=>`<button class="op ${dT===t[0]?"on":""}" onclick="dT='${t[0]}';detail(${id})">${t[1]}</button>`).join("")}</div></div>
  ${tab}
  ${st(p)!=="in"?`<div class="c" style="border-color:var(--am);display:flex;gap:10px;align-items:center"><div class="em">💡</div><div class="m"><b>${esc(p.n)} (Stock: ${p.s})</b><small>${L("This product is running low","Iki gicuruzwa kigiye gushira")}</small></div><button class="add" onclick="ivT='low';go('#/inventory')">${L("Low stock","Bigiye gushira")}</button></div>`:""}`,{back:"#/products",nav:"products"});
}
const mvRows=a=>a.map(m=>`<div class="tt" style="align-items:center"><span>${when(m.t)}<br><small class="mu">${esc(m.r)}${m.u?" • "+esc(m.u):""}</small></span><b class="${m.type==="in"?"pos":"neg"}">${m.type==="in"?"+":"-"}${m.q}</b></div>`).join("")||`<div class="emp">${L("No activity yet.","Nta bikorwa bihari.")}</div>`;
function sm(id){
  const p=gp(id);
  modal(`<h3>± Update Stock</h3><p class="mu" style="margin-bottom:10px">${esc(p.n)} • Stock: ${p.s}</p>
  <label>Type</label><select id="smt"><option value="in">Add stock (+)</option><option value="out">Remove stock (−)</option></select>
  <label>Quantity</label><div class="g2" style="margin:0"><input id="smq" inputmode="decimal" placeholder="Urugero 2 cyangwa 1÷2"><select id="smu"><option value="1">${esc(p.u||"Piece")}</option>${(p.pk||[]).map(k=>`<option value="${k.q}">${esc(k.n)} (${k.q} pcs)</option>`).join("")}</select></div>
  <label>Reason</label><input id="smr" placeholder="Urugero: Ibiyongewe bishya">
  <div class="g2"><button class="btn o" onclick="closeM()">Cancel</button><button class="btn" onclick="smS(${id})">Save</button></div>`);
}
function smS(id){
  if(!apr("prod_edit",id)){closeM();return route()}
  const p=gp(id),qv=pqty($("smq").value),q=+(qv*(+$("smu").value||1)).toFixed(3),t=$("smt").value;
  if(!(q>0))return toast("Andika umubare");
  if(t==="out"&&q>p.s)return toast("Stock ni "+p.s+" gusa");
  p.s=+(p.s+(t==="in"?q:-q)).toFixed(3);
  (p.mv=p.mv||[]).unshift({t:Date.now(),type:t,q,u:SE.name,r:$("smr").value.trim()||"Stock update"});
  save();closeM();toast("Byabitswe ✔");route();
}
function del(id){if(!apr("prod_edit",id))return needApr("prod_edit",id);const p=gp(id);ask("Siba Igicuruzwa",`Uremeza gusiba ${esc(p.n)}? Ntibishobora gusubizwa inyuma.`,()=>{logA("Product deleted",p.n);P=P.filter(x=>x.id!==id);save();toast("Cyasibwe");go("#/products")})}
function reqEdit(id){
  const p=gp(id);
  modal(`<h3>Saba Guhindura Ibirimo (Request Edit)</h3><label><span>${L("Describe what you want to change on","Sobanura icyo usaba guhindura kuri")}</span> ${esc(p.n)}</label><textarea id="reqDesc" rows="3" placeholder="Urugero: Hindura igiciro cyo kugurisha..."></textarea><button class="btn" onclick="sendReq(${id})">Ohereza kuri Admin</button>`);
}
function sendReq(id){
  const desc=$("reqDesc").value.trim();if(!desc)return toast("Andika ubusabe");
  Reqs.push({id:Date.now(),type:"product_edit",productId:id,user:SE.name,desc,t:Date.now()});
  save();closeM();toast("Ubusabe bwoherejwe kuri Admin ✔");
}
const APR=["expense_access","prod_add","prod_edit"],
TL={expense_access:"Expenses",prod_add:"Add Product",prod_edit:"Edit Product"},
LBL={prod_add:"wongere igicuruzwa",prod_edit:"uhindure igicuruzwa"},
apr=(type,pid)=>{if(can("admin"))return true;const r=Reqs.filter(x=>x.type===type&&x.uid===SE.id&&(pid==null||x.pid===pid)).sort((a,b)=>b.t-a.t)[0];return !!r&&r.status==="approved"&&r.exp>Date.now()};
function needApr(type,pid){
  const r=Reqs.filter(x=>x.type===type&&x.uid===SE.id&&(pid==null||x.pid===pid)).sort((a,b)=>b.t-a.t)[0];
  if(r&&r.status==="pending")return modal(`<h3>⏳ Utegereje Admin</h3><p style="line-height:1.5;margin-bottom:12px">Ubusabe bwawe bwoherejwe. Utegereje ko Admin abwemeza.</p><button class="btn o" onclick="closeM();route()">🔄 Reba niba byemejwe</button><button class="btn" onclick="closeM()">OK</button>`);
  const pre=r&&r.status==="rejected"?"Admin yanze ubusabe bwa mbere. ":r&&r.status==="approved"?"Uruhushya rwawe rwarangiye. ":"";
  modal(`<h3>🔒 Hakenewe Approval ya Admin</h3><p style="line-height:1.5;margin-bottom:12px">${pre}Kugira ngo ${LBL[type]} ukeneye uruhushya rwa Admin.</p><input id="arz" placeholder="Impamvu (ntibiteganywa)"><button class="btn" onclick="sendApr('${type}',${pid==null?"null":pid})">✉️ Saba Approval</button><button class="btn o" onclick="closeM()">Cancel</button>`);
}
function sendApr(type,pid){
  const p=pid!=null?gp(pid):null;
  Reqs.push({id:Date.now(),type,uid:SE.id,user:SE.name,pid:pid,desc:($("arz").value.trim()||"Nsaba uruhushya: "+TL[type])+(p?" — "+p.n:""),t:Date.now(),status:"pending"});
  save();closeM();toast("Ubusabe bwoherejwe kuri Admin ✔");
}
function pAdd(){if(!hp("add_products"))return toast(NOPERM());if(apr("prod_add"))go("#/edit/new");else needApr("prod_add",null)}
const NOPERM=()=>L("You do not have permission for this","Nta burenganzira ufite kuri ibi");
function gEdit(id,w){
  if(w==="del"?!hp("delete_products"):!hp("edit_products"))return toast(NOPERM());
  if(!apr("prod_edit",id))return needApr("prod_edit",id);
  if(w==="sm")sm(id);else if(w==="edit")go("#/edit/"+id);else del(id);
}
const PKT=["Pack","Dozen","Box","Bag","Carton"];
let pkRows=[];
const cats=()=>[...new Set([...CAT,...P.map(p=>p.k)])].filter(Boolean).sort(),
catOpts=cur=>`<option value="">— Hitamo icyiciro —</option>`+[...new Set([...cats(),...(cur?[cur]:[])])].sort().map(k=>`<option ${k===cur?"selected":""}>${esc(k)}</option>`).join(""),
supOpts=cur=>`<option value="0">— Nta supplier —</option>`+SUP.map(s=>`<option value="${s.id}" ${s.id===cur?"selected":""}>${esc(s.n)}</option>`).join(""),
base=()=>({c:+($("fcost")||{}).value||0,p:+($("fp")||{}).value||0});
function fillCat(sel){const e=$("fc");if(!e)return;e.innerHTML=catOpts(sel!==undefined?sel:e.value)}
function fillSup(sel){const e=$("fsup");if(!e)return;e.innerHTML=supOpts(sel!==undefined?sel:+e.value)}
/* packs */
function pkHint(){const b=base();pkRows.forEach((r,i)=>{const e=$("pkh"+i);if(e)e.textContent="Inyungu: "+fmt(r.p-r.c)+" • Ku giciro cya piece: "+fmt(b.p*r.q)})}
function pkSync(i){
  const b=base(),r=pkRows[i];if(!r)return;
  if(!r.mc)r.c=Math.round(b.c*r.q);
  if(!r.mp)r.p=Math.round(b.p*r.q);
  const ec=$("pkc"+i),ep=$("pkp"+i);if(ec&&!r.mc)ec.value=r.c;if(ep&&!r.mp)ep.value=r.p;
  pkHint();
}
function pkAll(){pkRows.forEach((_,i)=>pkSync(i))}
function pkQ(i,v){pkRows[i].q=Math.max(2,parseInt(v)||2);pkSync(i)}
function pkC(i,v){pkRows[i].c=+v||0;pkRows[i].mc=true;pkHint()}
function pkP(i,v){pkRows[i].p=+v||0;pkRows[i].mp=true;pkHint()}
function pkAuto(i){pkRows[i].mc=false;pkRows[i].mp=false;pkSync(i)}
function pkDel(i){pkRows.splice(i,1);pkRender()}
function pkN(i,v){const r=pkRows[i];r.t=v;r.n=v==="Other"?(PKT.includes(r.n)?"Other":r.n):v;pkRender()}
function pkNm(i,v){pkRows[i].n=v.trim()||"Other"}
function pkAdd(){
  const t=PKT.find(x=>!pkRows.some(r=>r.n===x))||"Other";
  pkRows.push({t,n:t,q:t==="Dozen"?12:10,c:0,p:0,mc:false,mp:false});
  pkSync(pkRows.length-1);pkRender();
}
function pkRender(){
  const e=$("pkl");if(!e)return;
  e.innerHTML=pkRows.map((r,i)=>`<div class="c" style="background:var(--fd);padding:10px;margin-bottom:8px">
  <div class="g2" style="margin:0 0 6px"><div><label>Ubwoko</label><select onchange="pkN(${i},this.value)">${[...PKT,"Other"].map(x=>`<option ${x===r.t?"selected":""}>${x}</option>`).join("")}</select></div><div><label>Pieces muri 1 ${esc(r.n)}</label><input type="number" min="2" inputmode="numeric" value="${r.q}" oninput="pkQ(${i},this.value)"></div></div>
  ${r.t==="Other"?`<label>Izina ry'iyi option</label><input value="${esc(r.n)}" oninput="pkNm(${i},this.value)">`:""}
  <div class="g2" style="margin:0"><div><label>Purchase / ${esc(r.n)}</label><input id="pkc${i}" type="number" min="0" inputmode="numeric" value="${r.c}" oninput="pkC(${i},this.value)"></div><div><label>Selling / ${esc(r.n)}</label><input id="pkp${i}" type="number" min="0" inputmode="numeric" value="${r.p}" oninput="pkP(${i},this.value)"></div></div>
  <div style="display:flex;justify-content:space-between;align-items:center;gap:8px"><small class="mu" id="pkh${i}"></small><div style="display:flex;gap:6px"><button type="button" class="ib" onclick="pkAuto(${i})">↺ Auto</button><button type="button" class="ib" style="border-color:var(--rd);color:var(--rd)" onclick="pkDel(${i})">🗑</button></div></div></div>`).join("")||'<div class="emp" style="padding:8px">Nta pack/box yongeweho.</div>';
  pkHint();stkHint();
}
function stkHint(){
  const e=$("stkh");if(!e)return;
  if(!pkRows.length){e.textContent="";return}
  const s=parseFloat($("fs").value)||0,b=pkRows.reduce((m,r)=>r.q>m.q?r:m,pkRows[0]);
  e.textContent="≈ "+Math.floor(s/b.q)+" "+b.n+" + "+(+(s%b.q).toFixed(3))+" pieces";
}
/* categories */
function catMgr(){
  const cs=cats();
  modal(`<h3>🏷️ Product Categories</h3>${cs.map((k,i)=>`<div class="row" style="cursor:default"><div class="m"><b>${esc(k)}</b><small>${P.filter(p=>p.k===k).length} ibicuruzwa</small></div><button class="ib" onclick="catEdit(${i})">✏️</button><button class="ib" style="border-color:var(--rd)" onclick="catDel(${i})">🗑️</button></div>`).join("")||'<div class="emp">Nta cyiciro.</div>'}
  <input id="cnw" placeholder="Icyiciro gishya" style="margin-top:10px"><button class="btn" onclick="catAdd()">＋ Add Category</button><button class="btn o" onclick="closeM()">Close</button>`);
}
function catAdd(){
  const n=$("cnw").value.trim();if(n.length<2)return toast("Andika izina ry'icyiciro");
  if(cats().some(k=>k.toLowerCase()===n.toLowerCase()))return toast("Iki cyiciro gisanzweho");
  CAT.push(n);save();fillCat();toast("Byabitswe ✔");catMgr();
}
function catEdit(i){
  const k=cats()[i];if(k===undefined)return;
  modal(`<h3>✏️ Edit Category</h3><input id="cen" value="${esc(k)}"><div class="g2"><button class="btn o" onclick="catMgr()">Cancel</button><button class="btn" onclick="catRen(${i})">Save</button></div>`);
}
function catRen(i){
  const old=cats()[i],nn=$("cen").value.trim();
  if(nn.length<2)return toast("Andika izina ry'icyiciro");
  if(nn!==old&&cats().some(k=>k.toLowerCase()===nn.toLowerCase()))return toast("Iki cyiciro gisanzweho");
  const cur=$("fc")?$("fc").value:"";
  CAT=CAT.filter(x=>x!==old);if(!CAT.includes(nn))CAT.push(nn);
  P.forEach(p=>{if(p.k===old)p.k=nn});if(pC===old)pC=nn;
  save();fillCat(cur===old?nn:cur);toast("Byabitswe ✔");catMgr();
}
function catDel(i){
  const k=cats()[i],n=P.filter(p=>p.k===k).length;if(k===undefined)return;
  if(n)return toast("Gikoreshwa n'ibicuruzwa "+n+". Banza ubihindure.");
  ask("Siba Icyiciro",`Uremeza gusiba ${esc(k)}?`,()=>{CAT=CAT.filter(x=>x!==k);save();fillCat();catMgr()});
}
/* suppliers */
function supMgr(){
  modal(`<h3>🚚 Suppliers</h3>${SUP.map(s=>`<div class="row" style="cursor:default"><div class="m"><b>${esc(s.n)}</b><small>${esc(s.ph||"")}${s.loc?" • "+esc(s.loc):""}</small></div><button class="ib" onclick="supEdit(${s.id})">✏️</button><button class="ib" style="border-color:var(--rd)" onclick="supDel(${s.id})">🗑️</button></div>`).join("")||'<div class="emp">Nta supplier ahari.</div>'}
  <button class="btn" style="margin-top:10px" onclick="supEdit(0)">＋ Add Supplier</button><button class="btn o" onclick="closeM()">Close</button>`);
}
function supEdit(id,from){
  const s=id?SUP.find(x=>x.id===id):{n:"",ph:"",loc:""};if(!s)return;
  modal(`<h3>${id?"Edit":"Add"} Supplier</h3><label>Izina</label><input id="sun" value="${esc(s.n)}"><label>Telefone</label><input id="sup" inputmode="tel" value="${esc(s.ph||"")}"><label>Aho aherereye / Icyo atanga</label><input id="sul" value="${esc(s.loc||"")}">
  <div class="g2"><button class="btn o" onclick="${from?"closeM()":"supMgr()"}">Cancel</button><button class="btn" onclick="supSave(${id},${from?1:0})">Save</button></div>`);
}
function supSave(id,from){
  const n=$("sun").value.trim(),ph=$("sup").value.trim(),loc=$("sul").value.trim();
  if(n.length<2)return toast("Andika izina rya supplier");
  if(SUP.some(x=>x.id!==id&&x.n.toLowerCase()===n.toLowerCase()))return toast("Uyu supplier asanzweho");
  let sid=id;
  if(id){const s=SUP.find(x=>x.id===id);s.n=n;s.ph=ph;s.loc=loc}
  else{sid=SUP.reduce((m,x)=>Math.max(m,x.id),0)+1;SUP.push({id:sid,n,ph,loc})}
  save();toast("Byabitswe ✔");
  if(from){fillSup(sid);closeM()}else{fillSup();supMgr()}
}
function supDel(id){
  const s=SUP.find(x=>x.id===id);if(!s)return;
  ask("Siba Supplier",`Uremeza gusiba ${esc(s.n)}? Ibicuruzwa bye ntibizaba bifite supplier.`,()=>{SUP=SUP.filter(x=>x.id!==id);P.forEach(p=>{if(p.sup===id)p.sup=0});save();fillSup();supMgr()});
}
/* product form */
let tmpImgs=[];
function galRender(){
  const e=$("gal");if(!e)return;
  e.innerHTML=tmpImgs.map((v,i)=>`<div class="gt ${i===0?"m":""}" onclick="galMain(${i})"><img src="${v}" alt="">${i===0?'<span style="position:absolute;left:2px;bottom:2px;background:var(--g);color:#03150c;border-radius:6px;font-size:9px;padding:0 4px;font-weight:700">★</span>':""}<b onclick="event.stopPropagation();galDel(${i})">×</b></div>`).join("")+(tmpImgs.length<5?`<label class="gt" style="border-style:dashed;cursor:pointer"><span style="text-align:center;font-size:11px;color:var(--g)">＋<br>${L("Add Photo","Ongeramo ifoto")}</span><input type="file" accept="image/*" style="display:none" onchange="galAdd(this)"></label>`:"");
}
function galAdd(inp){pickImg(inp,v=>{tmpImgs.push(v);galRender()},420)}
function galMain(i){if(i>0){const v=tmpImgs.splice(i,1)[0];tmpImgs.unshift(v);galRender()}}
function galDel(i){tmpImgs.splice(i,1);galRender()}
function pSum(){
  const e=$("psm");if(!e)return;
  const g=i=>($(i)||{value:""}).value,c=+g("fcost")||0,s=+g("fp")||0,mg=c?Math.round((s-c)/c*100):0;
  const r=(k,v)=>`<div class="tt"><span class="mu">${k}</span><b>${v}</b></div>`;
  e.innerHTML=r(L("Product Name","Izina"),esc(g("fn")||"-"))+r(L("Category","Icyiciro"),esc(g("fc")||"-"))+r(L("Purchase Price","Igiciro cyo kugura"),fmt(c))+r(L("Selling Price","Igiciro cyo kugurisha"),fmt(s))+r(L("Stock Quantity","Stock"),esc(g("fs")||"0"))+r(L("Low Stock Alert","Itangazo ryo gushira"),esc(g("fl")||"10"))+r(L("Profit Margin","Inyungu"),`<span class="${mg>=0?"pos":"neg"}">${mg}%</span>`);
  const m=$("pmg");if(m)m.textContent=mg+"%";
}
function pform(a){
  if(!(a==="new"?apr("prod_add"):apr("prod_edit",+a))){toast("Hakenewe approval ya Admin");return go(a==="new"?"#/products":"#/product/"+a)}
  const n=a==="new",p=n?{e:"📦",n:"",sk:"",k:"",c:"",p:"",s:"",lw:10,u:"Piece",sg:true,pk:[],sup:0,act:true}:gp(+a);
  if(!p)return go("#/products");
  tmpImg=p.img||"";tmpImgs=(p.imgs&&p.imgs.length?p.imgs:[p.img]).filter(okImg).slice();
  pkRows=(p.pk||[]).map(k=>({t:PKT.includes(k.n)?k.n:"Other",n:k.n,q:k.q,c:k.c,p:k.p,mc:k.mc!==undefined?k.mc:true,mp:k.mp!==undefined?k.mp:true}));
  page(n?L("Add Product","Ongeramo Igicuruzwa"):L("Edit Product","Hindura Igicuruzwa"),L("Fill in the product information","Uzuza amakuru y'igicuruzwa"),
  `<div class="c"><h3><span><span class="sn">1</span>${L("Basic Information","Amakuru y'ibanze")}</span></h3>
  <label>${L("Product photos (first one is the main photo)","Amafoto y'igicuruzwa (iya mbere ni yo y'ingenzi)")}</label><div class="gal" id="gal"></div>
  <label>Emoji</label><input id="fe" maxlength="4" value="${esc(p.e)}">
  <label>${L("Product Name","Izina ry'igicuruzwa")} *</label><input id="fn" value="${esc(p.n)}" oninput="pSum()">
  <label>${L("Product Code / SKU","Code / SKU y'igicuruzwa")}</label><input id="fk" placeholder="Auto" value="${esc(p.sk||"")}">
  <label>${L("Category","Icyiciro")} *</label><div style="display:flex;gap:8px"><select id="fc" style="flex:1" onchange="pSum()">${catOpts(p.k)}</select><button type="button" class="ib" style="height:44px;margin-bottom:10px" onclick="catMgr()">⚙️ ${L("Manage","Cunga")}</button></div>
  <label>${L("Supplier","Utanga ibicuruzwa")}</label><div style="display:flex;gap:8px"><select id="fsup" style="flex:1">${supOpts(p.sup||0)}</select><button type="button" class="ib" style="height:44px;margin-bottom:10px" onclick="supEdit(0,1)">＋ ${L("Add","Ongeramo")}</button></div>
  <label>${L("Brand (optional)","Ikirango (si ngombwa)")}</label><input id="fbr" value="${esc(p.brand||"")}">
  <label>${L("Description (optional)","Ibisobanuro (si ngombwa)")}</label><textarea id="fds" rows="3" maxlength="500" oninput="$('fdc').textContent=this.value.length+'/500'">${esc(p.desc||"")}</textarea><div class="mu" id="fdc" style="text-align:right;font-size:11px;margin-top:-6px">${(p.desc||"").length}/500</div></div>
  <div class="c"><h3><span><span class="sn">2</span>${L("Pricing & Stock","Ibiciro na Stock")}</span></h3><h4 style="margin:0 0 6px">① ${L("Single (1 piece)","Piece 1")}</h4><label class="ck"><input type="checkbox" id="fsg" ${p.sg!==false?"checked":""}> ${L("Sell single pieces","Gurisha piece imwe")}</label>
  <div class="g2" style="margin:0"><div><label>${L("Purchase Price / piece","Igiciro cyo kugura / piece")} *</label><input id="fcost" type="number" min="0" inputmode="numeric" value="${p.c}" oninput="pkAll();pSum()"></div><div><label>${L("Selling Price / piece","Igiciro cyo kugurisha / piece")} *</label><input id="fp" type="number" min="0" inputmode="numeric" value="${p.p}" oninput="pkAll();pSum()"></div></div>
  <div class="tt" style="margin-bottom:8px"><span class="mu">${L("Profit Margin","Inyungu")}</span><b class="pos" id="pmg">0%</b></div>
  <label>${L("Unit name","Izina rya piece (unit)")}</label><input id="fu" value="${esc(p.u||"Piece")}">
  <h4 style="margin:6px 0">② Pack / Dozen / Box / Bag…</h4><p class="mu" style="font-size:12px;margin-bottom:8px;line-height:1.4">${L("The pack price is calculated automatically (pieces × piece price). You can edit it; ↺ Auto restores it.","Igiciro cya pack kibarwa ubwacyo (pieces × igiciro cya piece). Ushobora kugihindura; ↺ Auto ikigarura.")}</p><div id="pkl"></div><button type="button" class="btn o" onclick="pkAdd()">＋ ${L("Add Pack / Box option","Ongeramo pack / box")}</button>
  <div class="g2" style="margin:0"><div><label>${L("Stock (pieces)","Stock (pieces)")} *</label><input id="fs" type="number" min="0" inputmode="decimal" value="${p.s}" oninput="stkHint();pSum()"></div><div><label>${L("Low Stock Alert (pieces)","Itangazo ryo gushira (pieces)")}</label><input id="fl" type="number" min="0" inputmode="numeric" value="${p.lw||10}" oninput="pSum()"></div></div><small class="mu" id="stkh"></small></div>
  <div class="c"><h3><span><span class="sn">3</span>${L("Additional Details","Andi makuru")}</span></h3>
  <div class="g2" style="margin:0"><div><label>${L("Expiry Date (optional)","Itariki izarangiriraho")}</label><input id="fex" type="date" value="${esc(p.exp||"")}"></div><div><label>${L("Location / Shelf","Aho giherereye")}</label><input id="flc" value="${esc(p.loc||"")}" placeholder="A1"></div></div>
  <div class="g2" style="margin:0"><div><label>${L("Tax Rate","Umusoro")}</label><select id="ftx"><option value="0" ${!p.tax?"selected":""}>0% (${L("No Tax","Nta musoro")})</option><option value="18" ${+p.tax===18?"selected":""}>18% (VAT)</option></select></div><div><label>${L("Status","Imiterere")}</label><label class="ck" style="margin-top:10px"><input type="checkbox" id="fac" ${p.act!==false?"checked":""}> ${L("Active (available for sale)","Ikora (kiragurishwa)")}</label></div></div></div>
  <div class="c"><h3>⭐ ${L("Dashboard","Dashboard")}</h3><label class="ck"><input type="checkbox" id="ffe" ${p.feat?"checked":""}> ${L("Show on Dashboard (Featured)","Shyira ku Dashboard (Featured)")}</label><label>${L("Order on the slider (1 = first)","Umwanya ku slider (1 = uwa mbere)")}</label><input id="ffo" type="number" min="1" inputmode="numeric" value="${p.fo||""}"></div>
  <div class="c"><h3>✅ ${L("Product Summary","Incamake y'igicuruzwa")}</h3><div id="psm"></div></div>
  <div class="g2"><button class="btn o" onclick="pform('${a}')">↺ ${L("Reset","Subiza uko byari")}</button><button class="btn" onclick="saveP('${a}')">💾 ${L("Save Product","Bika Igicuruzwa")}</button></div>`,{back:"#/products",nav:"products"});
  pkRender();stkHint();galRender();pSum();
}
function saveP(a){
  if(!(a==="new"?apr("prod_add"):apr("prod_edit",+a))){toast("Hakenewe approval ya Admin");return go("#/products")}
  const nw=a==="new",g=i=>$(i).value.trim(),nm=g("fn"),k=g("fc"),c=g("fcost"),pp=+g("fp"),s=+(+g("fs")).toFixed(3);
  if(nm.length<2)return toast("Andika izina");
  if(!k)return toast("Hitamo icyiciro");
  if(c===""||+c<0)return toast("Andika igiciro cyo kugura");
  if(!(pp>0))return toast("Andika igiciro cyo kugurisha");
  if(g("fs")===""||isNaN(s)||s<0)return toast("Stock si yo");
  const sg=$("fsg").checked,pk=[];
  for(const r of pkRows){
    const q=Math.round(+r.q),nmx=(r.n||"").trim()||"Pack";
    if(!(q>=2))return toast("Pieces muri "+nmx+" nibura 2");
    if(!(+r.p>0))return toast("Andika igiciro cya "+nmx);
    if(pk.some(x=>x.n.toLowerCase()===nmx.toLowerCase()))return toast("Amazina ya packs agomba kuba atandukanye");
    pk.push({n:nmx,q,c:Math.round(+r.c||0),p:Math.round(+r.p),mc:!!r.mc,mp:!!r.mp});
  }
  if(!sg&&!pk.length)return toast("Hitamo nibura option imwe yo kugurisha");
  if(!CAT.includes(k))CAT.push(k);
  tmpImg=tmpImgs[0]||"";const o={img:tmpImg,feat:$("ffe").checked,fo:+$("ffo").value||0,imgs:tmpImgs.slice(),brand:g("fbr"),desc:$("fds").value.trim(),exp:$("fex").value,loc:g("flc"),tax:+$("ftx").value,act:$("fac").checked,e:g("fe")||"📦",n:nm,sk:g("fk"),k,c:+c,p:pp,s,lw:parseInt(g("fl"),10)||10,u:g("fu")||"Piece",sg,pk,sup:+$("fsup").value||0};
  if(nw){o.id=P.reduce((m,x)=>Math.max(m,x.id),0)+1;o.mv=[{t:Date.now(),type:"in",q:s,u:SE.name,r:"Opening stock"}];P.push(o);a=o.id}
  else{const p=gp(+a),d=+(s-p.s).toFixed(3);Object.assign(p,o);if(d)(p.mv=p.mv||[]).unshift({t:Date.now(),type:d>0?"in":"out",q:Math.abs(d),u:SE.name,r:"Adjustment"})}
  save();toast("Byabitswe ✔");go("#/product/"+a);
}

/* CUSTOMERS */
function customers(){
  page("Customers","Manage all your customers",
  `<button class="btn" onclick="addCustModal()">＋ Add Customer</button><div id="custL"></div>`,{back:"#/home",nav:"customers"});
  renderCust();
}
function renderCust(){
  $("custL").innerHTML=C.map((c,i)=>`<div class="row" style="cursor:default"><div class="em">👤</div><div class="m"><b>${esc(c.n)}</b><small>📞 ${esc(c.ph)} • 📍 ${esc(c.loc||"Rwanda")}</small></div><button class="ib" style="border-color:var(--rd)" onclick="delCust(${i})">🗑️</button></div>`).join("")||'<div class="emp">No customers yet.</div>';
}
function addCustModal(){
  modal(`<h3>Add Customer</h3><input id="cuN" placeholder="Full Name"><input id="cuP" placeholder="Phone (e.g. 0788123456)"><input id="cuL" placeholder="Location"><button class="btn" onclick="saveCust()">Save</button>`);
}
function saveCust(){
  const n=$("cuN").value.trim(),ph=$("cuP").value.trim(),loc=$("cuL").value.trim();
  if(!n)return toast("Andika izina");
  C.push({n,ph,loc});save();closeM();toast("Customer yongewemo ✔");renderCust();
}
function delCust(i){ask("Siba Customer",`Uremeza gusiba ${esc((C[i]||{}).n||"")}?`,()=>{logA("Customer deleted",(C[i]||{}).n);C.splice(i,1);save();toast("Cyasibwe");renderCust()})}

/* PUBLIC SHOP */
function shop(){
  page("Public Shop","Abakiriya bashobora gusura no kureba ibicuruzwa",
  `<input id="shQ" placeholder="🔍 Shakisha ibicuruzwa…" oninput="renderShop()"><div id="shList"></div>`,{back:"#/home",nav:"shop"});
  renderShop();
}
function renderShop(){
  const q=($("shQ")?$("shQ").value:"").toLowerCase();
  $("shList").innerHTML=P.filter(p=>!q||p.n.toLowerCase().includes(q)||p.k.toLowerCase().includes(q))
  .map(p=>`<div class="row" style="cursor:default"><div class="em">${pim(p)}</div><div class="m"><b>${esc(p.n)}</b><small>${esc(p.k)} • Stock: ${p.s} ${esc(p.u)}${(p.pk||[]).map(k=>`<br>${esc(k.n)} (${k.q}): ${fmt(k.p)}`).join("")}</small></div><div class="r"><b>${fmt(p.p)}</b><span class="bd ${st(p)}">${LB[st(p)]}</span></div></div>`).join("")||'<div class="emp">Nta bicuruzwa bihari.</div>';
}

/* EXPENSES */
const EK={Rent:"#ff4d6d",Utilities:"#1d8cff",Salaries:"#8b5cf6",Transport:"#f59e0b",Supplies:"#eab308",Marketing:"#14b8a6",Maintenance:"#ef4444",Food:"#84cc16",Other:"#d4a5a5","Office Supplies":"#8b5cf6",Communication:"#eab308",Meals:"#84cc16",Repairs:"#ef4444",Others:"#d4a5a5"},
XCH=["Rent","Utilities","Salaries","Transport","Supplies","Marketing","Maintenance","Food","Other"],
EI={Rent:"🏠",Utilities:"💡",Salaries:"👥",Transport:"🚗",Supplies:"📝",Marketing:"📣",Maintenance:"🛠️",Food:"🍽️",Other:"📦","Office Supplies":"📝",Communication:"📞",Meals:"🍽️",Repairs:"🛠️",Others:"📦"},
EP=["Cash","Mobile Money","Bank Transfer","Card"];
let bud=ld("bizz_budget",3000000),eQ="",eM="",eK="",eP=1,eInit=0;
const ymd=d=>d.getFullYear()+"-"+("0"+(d.getMonth()+1)).slice(-2)+"-"+("0"+d.getDate()).slice(-2),
edt=d=>new Date(d+"T00:00:00").toLocaleDateString("en-GB",{day:"2-digit",month:"short",year:"numeric"}),
mlabel=m=>new Date(m+"-01T00:00:00").toLocaleDateString("en-US",{month:"long",year:"numeric"}),
mk=o=>{const d=new Date();d.setDate(1);d.setMonth(d.getMonth()-o);return ymd(d).slice(0,7)},
xs=f=>X.filter(f).reduce((a,x)=>a+x.a,0),
saveX=()=>sv("bizz_expenses",X),
ch=(v,o)=>o?`<span class="${v>o?"neg":"pos"}">${v>o?"▲":"▼"} ${Math.abs(Math.round((v-o)/o*100))}%</span>`:"",
xcol=k=>EK[k]||"#888";

const openReqs=()=>Reqs.filter(r=>r.status!=="approved"&&r.status!=="rejected"),
pend=()=>Reqs.filter(r=>APR.includes(r.type)&&r.status==="pending"),
xAcc=()=>Reqs.filter(r=>r.type==="expense_access"&&r.uid===SE.id).sort((a,b)=>b.t-a.t)[0]||null,
xOK=()=>{if(can("admin"))return true;const r=xAcc();return !!r&&r.status==="approved"&&r.exp>Date.now()};
function reqRow(r){
  const ex=APR.includes(r.type);
  return `<div class="row" style="cursor:default"><div class="em">${ex?"🔐":"✉️"}</div><div class="m"><b>${esc(r.user)}${ex?" • "+(TL[r.type]||""):""}</b><small>${esc(r.desc)}<br>${when(r.t)}</small></div>${ex?`<div style="display:flex;flex-direction:column;gap:6px"><button class="add" onclick="xDec(${r.id},true)">✔ Approve</button><button class="ib" style="border-color:var(--rd);color:var(--rd)" onclick="xDec(${r.id},false)">✖ Reject</button></div>`:""}</div>`;
}
function xDec(id,ok){
  const r=Reqs.find(x=>x.id===id);if(!r)return;
  r.status=ok?"approved":"rejected";r.by=SE.name;r.dt=Date.now();if(ok)r.exp=Date.now()+3600000;
  save();toast(ok?"Byemejwe ✔ (isaha 1)":"Byanzwe");closeM();route();
}
function xGate(){
  const r=xAcc(),st=r?(r.status==="pending"?"pending":r.status==="approved"&&r.exp<=Date.now()?"expired":r.status):"none";
  const msg={none:"Expenses zisaba uruhushya rwa Admin. Saba approval kugira ngo ukomeze.",pending:"Ubusabe bwawe bwoherejwe. Utegereje ko Admin abwemeza…",rejected:"Admin yanze ubusabe bwawe. Ushobora gusaba ukundi.",expired:"Uruhushya rwawe rwarangiye. Saba ukundi kugira ngo ukomeze."}[st];
  page("Expenses","Hakenewe uruhushya rwa Admin",
  `<div class="c" style="text-align:center;padding:24px 16px"><div style="font-size:46px;margin-bottom:8px">${st==="pending"?"⏳":"🔒"}</div><p style="line-height:1.5;margin-bottom:14px">${msg}</p>
  ${st==="pending"?`<button class="btn o" onclick="route()">🔄 Reba niba byemejwe</button>`:`<input id="xrs" placeholder="Impamvu (ntibiteganywa)"><button class="btn" onclick="xAsk()">✉️ Saba Approval</button>`}</div>`,{back:"#/home",nav:"expenses"});
}
function xAsk(){
  const r=xAcc();if(r&&r.status==="pending")return route();
  Reqs.push({id:Date.now(),type:"expense_access",uid:SE.id,user:SE.name,desc:$("xrs").value.trim()||"Nsaba uruhushya rwo gukoresha Expenses",t:Date.now(),status:"pending"});
  save();toast("Ubusabe bwoherejwe kuri Admin ✔");route();
}
function expenses(){
  if(!xOK())return xGate();
  if(!eInit){eM=X.some(x=>x.d.slice(0,7)===mk(0))?mk(0):"";eInit=1}
  const now=new Date(),td=ymd(now),yy=new Date();yy.setDate(yy.getDate()-1);const yd=ymd(yy);
  const m0=xs(x=>x.d.slice(0,7)===mk(0)),m1=xs(x=>x.d.slice(0,7)===mk(1)),m2=xs(x=>x.d.slice(0,7)===mk(2));
  const Y=now.getFullYear(),y0=xs(x=>+x.d.slice(0,4)===Y),y1=xs(x=>+x.d.slice(0,4)===Y-1),y2=xs(x=>+x.d.slice(0,4)===Y-2);
  const t0=xs(x=>x.d===td),t1=xs(x=>x.d===yd),tall=xs(()=>true);
  const ms=[...new Set(X.map(x=>x.d.slice(0,7)))];if(!ms.includes(mk(0)))ms.push(mk(0));ms.sort().reverse();
  const rec=[...X].sort((a,b)=>b.d.localeCompare(a.d)||b.id-a.id).slice(0,5);
  const sm2=(l,v,o)=>`<div class="tt"><span>${l}<br><b>${fmt(v)}</b></span>${ch(v,o)}</div>`;
  page("Expenses","Track and manage your business expenses",
  `<div class="g2">${card("👛","Total Expenses",fmt(tall),"")}${card("📅","This Month",fmt(m0),ch(m0,m1)+" vs last month")}${card("🪙","Today",fmt(t0),ch(t0,t1)+" vs yesterday")}<div onclick="ebud()">${card("🧾","Remaining Budget",fmt(bud-m0),"Budget "+fmt(bud)+" ✏️")}</div></div>
  <input id="xq" placeholder="🔍 Search by description or category…" oninput="eQ=this.value;eP=1;xr()">
  <div class="g2" style="margin-bottom:0"><select id="xm" onchange="eM=this.value;eP=1;xr()"><option value="">All time</option>${ms.map(m=>`<option value="${m}" ${m===eM?"selected":""}>${mlabel(m)}</option>`).join("")}</select>
  <select id="xf" onchange="eK=this.value;eP=1;xr()"><option value="">All categories</option>${Object.keys(EK).map(k=>`<option ${k===eK?"selected":""}>${k}</option>`).join("")}</select></div>
  <div class="c"><h3>📄 Expense List</h3><div id="xl"></div></div>
  <div class="c"><h3>🍩 Expenses by Category</h3><div id="xc"></div></div>
  <div class="c"><h3>🕒 Recent Expenses</h3>${rec.map(x=>`<div class="row" style="cursor:default"><div class="em" style="background:${xcol(x.k)}44">${EI[x.k]||"📦"}</div><div class="m"><b>${esc(x.ds)}</b><small>${fmt(x.a)} (${edt(x.d)})</small></div></div>`).join("")||'<div class="emp">No expenses yet.</div>'}</div>
  <div class="c"><h3>📈 Expense Summary</h3>${sm2("This Month",m0,m1)}${sm2("Last Month",m1,m2)}${sm2("This Year",y0,y1)}${sm2("Last Year",y1,y2)}</div>
  ${can("admin")?"":`<button class="btn o" onclick="reqExpModal()">✉️ Saba Admin Kongeraho Expenses (Request Expense)</button>`}`,
  {back:"#/home",nav:"expenses",act:`<button class="hb" onclick="xe(0)">＋ Add</button>`});
  $("xq").value=eQ;xr();
}
function xr(){
  const q=eQ.toLowerCase(),PS=10;
  const L=X.filter(x=>(!eM||x.d.slice(0,7)===eM)&&(!eK||x.k===eK)&&(!q||(x.ds+x.k+x.pm).toLowerCase().includes(q))).sort((a,b)=>b.d.localeCompare(a.d)||b.id-a.id);
  const pgs=Math.max(1,Math.ceil(L.length/PS));if(eP>pgs)eP=pgs;
  const A=L.slice((eP-1)*PS,eP*PS);
  $("xl").innerHTML=(A.map(x=>`<div class="row" style="cursor:default"><div class="em" style="background:${xcol(x.k)}44">${EI[x.k]||"📦"}</div><div class="m"><b>${esc(x.ds)}</b><small>${edt(x.d)} • ${esc(x.pm)}</small></div><div class="r"><b>${fmt(x.a)}</b><span class="cc" style="background:${xcol(x.k)}">${esc(x.k)}</span></div><button class="ib" style="padding:6px 8px" onclick="xe(${x.id})">✏️</button><button class="ib" style="padding:6px 8px;border-color:var(--rd)" onclick="xd(${x.id})">🗑️</button></div>`).join("")||'<div class="emp">No expenses found.</div>')
  +`<div class="tt mu" style="margin-top:8px"><span>Showing ${L.length?(eP-1)*PS+1:0}–${(eP-1)*PS+A.length} of ${L.length}</span></div>`
  +(pgs>1?`<div class="tabs">${Array.from({length:pgs},(_,i)=>`<button class="tab ${i+1===eP?"on":""}" onclick="eP=${i+1};xr()">${i+1}</button>`).join("")}</div>`:"");
  const g={};L.forEach(x=>g[x.k]=(g[x.k]||0)+x.a);
  const en=Object.entries(g).sort((a,b)=>b[1]-a[1]),T=en.reduce((a,e)=>a+e[1],0);
  let c=0;const gr=en.map(e=>{const s=c;c+=e[1]/T*100;return`${xcol(e[0])} ${s}% ${c}%`}).join(",");
  $("xc").innerHTML=T?`<div style="display:flex;gap:14px;align-items:center"><div class="dn" style="background:conic-gradient(${gr})"><div><span>RWF<b>${T.toLocaleString("en-US")}</b>Total</span></div></div><div style="flex:1">${en.map(e=>`<div class="tt" style="padding:3px 0;font-size:12.5px"><span><i class="dot" style="background:${xcol(e[0])}"></i>${esc(e[0])}</span><span>${Math.round(e[1]/T*100)}%</span></div>`).join("")}</div></div>`:'<div class="emp">No data.</div>';
}
let xSrc="cash",xNet="mtn",xVia="code";
APR.push("exp_momo");TL.exp_momo="Expense via admin MoMo";LBL.exp_momo="wishyure expense ukoresheje code/numero ya Admin";
function xe(id){
  if(!hp("add_expenses"))return toast(NOPERM());
  const x=id?X.find(v=>v.id===id):{d:ymd(new Date()),ds:"",k:"Utilities",a:"",pm:"Cash"};
  xSrc=x.src==="admin_momo"?"momo":"cash";xNet=(x.mm&&x.mm.net)||"mtn";xVia=(x.mm&&x.mm.via)||"code";
  modal(`<h3>${id?"Edit Expense":"Add Expense"}</h3>
  <label>Expense Title <span class="neg">*</span></label><input id="xds" placeholder="e.g. Monthly Rent, Electricity Bill" value="${esc(x.ds)}">
  <label>Amount <span class="neg">*</span></label><div class="xamt"><span>Frw</span><input id="xa" type="number" min="0" inputmode="numeric" placeholder="0" value="${x.a}"></div>
  <label>Category <span class="neg">*</span></label><div class="xch" id="xch">${XCH.map(k=>`<button type="button" data-k="${esc(k)}" class="${k===x.k?"on":""}" onclick="xPick('${esc(k)}')">${esc(k)}</button>`).join("")}</div><input type="hidden" id="xk" value="${esc(x.k)}">
  <label>Note <small class="mu">(optional)</small></label><textarea id="xnote" rows="3" placeholder="Additional details...">${esc(x.note||"")}</textarea>
  <label>Pay with</label><div class="opt" style="margin-bottom:8px"><button class="op ${xSrc==="cash"?"on":""}" id="xs1" onclick="xSetSrc('cash')">💵 Cash</button><button class="op ${xSrc==="momo"?"on":""}" id="xs2" onclick="xSetSrc('momo')">📲 Admin code / number</button></div>
  <div id="xsp"></div>
  <label>Date</label><input id="xdt" type="date" value="${x.d}">
  <button class="xbtn" onclick="xsv(${id||0})">💾 Save Expense</button>`);
  xSrcUI();
}
function xPick(k){
  const e=$("xk");if(e)e.value=k;
  document.querySelectorAll("#xch button").forEach(b=>b.classList.toggle("on",b.dataset.k===k));
}
function xSetSrc(s){xSrc=s;$("xs1").classList.toggle("on",s==="cash");$("xs2").classList.toggle("on",s==="momo");xSrcUI()}
function xSrcUI(){
  const e=$("xsp");if(!e)return;
  if(xSrc!=="momo"){e.innerHTML="";return}
  const c=mmCfg(xNet,xVia),adm=can("admin"),ok=apr("exp_momo"),r=Reqs.filter(x=>x.type==="exp_momo"&&x.uid===SE.id).sort((a,b)=>b.t-a.t)[0],pending=r&&r.status==="pending";
  e.innerHTML=`<div class="c" style="background:var(--fd);padding:10px"><div class="opt" style="margin-bottom:8px">${[["mtn","MTN MoMo"],["air","Airtel Money"]].map(x=>`<button class="op ${xNet===x[0]?"on":""}" onclick="xNet='${x[0]}';xSrcUI()">${x[1]}</button>`).join("")}</div>
  <div class="opt" style="margin-bottom:8px">${[["code",L("Merchant code","Code y'ubucuruzi")],["num",L("Phone number","Numero ya telefone")]].map(x=>`<button class="op ${c.via===x[0]?"on":""}" onclick="xVia='${x[0]}';xSrcUI()">${x[1]}</button>`).join("")}</div>
  <div class="tt"><span>${L("Pay to","Kwishyura kuri")}</span><b>${c.to?esc(c.to):`<span class="neg">${L("Not set by admin","Admin ntarashyiraho")}</span>`}</b></div>
  ${adm||ok?`<button class="btn" onclick="xDial()">📲 ${L("Dial / copy code","Fungura / koporora code")}</button>`:pending?`<p class="mu" style="margin:6px 0">⏳ ${L("Waiting for admin approval…","Utegereje uruhushya rwa Admin…")}</p><button class="btn o" onclick="xSrcUI()">🔄 ${L("Check","Reba")}</button>`:`<p class="mu" style="margin:6px 0;line-height:1.4">🔒 ${L("The admin must approve before you pay from the admin's code/number.","Admin agomba kubanza kwemera mbere yo kwishyura ukoresheje code/numero ye.")}</p><button class="btn" onclick="xMomoReq()">✉️ ${L("Ask admin for approval","Saba Admin uruhushya")}</button>`}</div>`;
}
function xDial(){const a=+$("xa").value;if(!(a>0))return toast(L("Enter the amount first","Banza wandike amafaranga"));dialModal(mmCfg(xNet,xVia),a)}
function xMomoReq(){
  const ds=$("xds").value.trim(),a=+$("xa").value;
  if(ds.length<2||!(a>0))return toast(L("Enter description and amount first","Banza wandike ibisobanuro n'amafaranga"));
  const r=Reqs.filter(x=>x.type==="exp_momo"&&x.uid===SE.id).sort((x,y)=>y.t-x.t)[0];
  if(r&&r.status==="pending")return toast(L("Request already sent. Please wait for the admin.","Ubusabe bwamaze koherezwa. Tegereza Admin."));
  Reqs.push({id:Date.now(),type:"exp_momo",uid:SE.id,user:SE.name,pid:null,desc:ds+" • "+fmt(a),t:Date.now(),status:"pending"});
  save();logA("Approval requested","Expense via admin MoMo • "+ds+" • "+fmt(a));toast(L("Request sent to admin ✔","Ubusabe bwoherejwe kuri Admin ✔"));xSrcUI();
}
function xsv(id){
  if(!xOK()){closeM();return route()}
  const ds=$("xds").value.trim(),a=+$("xa").value,d=$("xdt").value;
  if(ds.length<2)return toast(L("Enter a description","Andika ibisobanuro"));
  if(!(a>0))return toast(L("Enter the amount","Andika amafaranga"));
  if(!d)return toast(L("Pick a date","Hitamo itariki"));
  const old=id?X.find(v=>v.id===id):null,o={d,ds,k:$("xk").value,a,note:($("xnote")?$("xnote").value.trim():"")};
  if(xSrc==="momo"){
    if(!apr("exp_momo"))return toast(L("Admin approval is needed for this payment","Hakenewe uruhushya rwa Admin kuri iyi payment"));
    const c=mmCfg(xNet,xVia);o.pm="Mobile Money";o.src="admin_momo";o.mm={net:c.net,via:c.via,to:c.to||""};
  }else{o.pm=(old&&old.src!=="admin_momo"&&old.pm)||"Cash";o.src="cash";o.mm=null}
  if(id)Object.assign(old,o);else X.push({id:X.reduce((m,v)=>Math.max(m,v.id),0)+1,...o});
  saveX();closeM();toast(L("Saved ✔","Byabitswe ✔"));route();
}
function xd(id){if(!xOK())return route();ask("Siba Expense","Uremeza gusiba iyi expense?",()=>{const ex=X.find(v=>v.id===id);logA("Expense deleted",ex?ex.ds+" • "+fmt(ex.a):"");X=X.filter(v=>v.id!==id);saveX();toast("Cyasibwe");route()})}
function ebud(){modal(`<h3>Monthly Budget</h3><label>Amount (RWF)</label><input id="eba" type="number" min="0" inputmode="numeric" value="${bud}"><div class="g2"><button class="btn o" onclick="closeM()">Cancel</button><button class="btn" onclick="ebS()">Save</button></div>`)}
function ebS(){const v=+$("eba").value;if(!(v>0))return toast("Andika amafaranga");bud=v;sv("bizz_budget",v);closeM();route()}
function reqExpModal(){
  modal(`<h3>Saba Admin Gutanga Expense</h3><label>Sobanura ubusabe bwawe</label><textarea id="reqExpDesc" rows="3" placeholder="Urugero: Nkeneye kwishyura amazi..."></textarea><button class="btn" onclick="sendExpReq()">Ohereza</button>`);
}
function sendExpReq(){
  const desc=$("reqExpDesc").value.trim();if(!desc)return toast("Andika ubusabe");
  Reqs.push({id:Date.now(),type:"expense",user:SE.name,desc,t:Date.now()});
  save();closeM();toast("Ubusabe bwoherejwe ✔");
}

/* AI moved to V2 */
/* SETTINGS */
const theme=v=>{sv("bizz_theme",v);document.body.classList.toggle("light",v==="light")};
let PF=Object.assign({snd:true,tone:"chime",bn:false,mtn:"",air:"",mtnT:"*182*8*1*{code}*{amount}#",airT:"",ai:true,vol:80,sndA:true,sndD:true,sndR:true,mtnN:"",airN:"",mtnNT:"*182*1*1*{number}*{amount}#",airNT:""},ld("bizz_prefs",{tfa:false,notif:true,backup:true,tax:true,lang:"English",rate:0,bk:0}));
const me=()=>U.find(x=>x.id===SE.id),
savePF=()=>sv("bizz_prefs",PF),
ar=v=>Array.isArray(v)?v:[],
tgl=k=>`<button class="tg ${PF[k]?"on":""}" onclick="tg('${k}')" aria-label="${k}"></button>`,
sg=(ic,t,d,r,on)=>`<div class="sg"${on?` onclick="${on}"`:""}><i>${ic}</i><div class="m"><b>${t}</b><small>${d}</small></div>${r||""}${on?`<span class="chv">›</span>`:""}</div>`,
sec=(ic,t,d,rows)=>`<div class="sh2"><i>${ic}</i><div><b>${t}</b><small>${d}</small></div></div><div class="c" style="padding:4px 12px">${rows}</div>`,
cs=()=>(new Blob([JSON.stringify(Memos)]).size/1024).toFixed(1)+" KB";
let SNDOPEN=false;
const SNDS=[["chime","Chime","🔔"],["bell","Bell","🛎️"],["beep","Beep","📟"],["alert","Alert","🚨"],["ring","Ring (long)","📞"],["siren","Siren (long)","🚓"],["melody","Melody (long)","🎶"],["custom","My sound from phone","📁"]];
const sndLabel=k=>{const x=SNDS.find(y=>y[0]===k);return x?x[1]:"Chime"};
function sndToggle(){SNDOPEN=!SNDOPEN;settings()}
function sndPick(k){PF.tone=k;savePF();logA("Settings changed","Notification sound");ping(k,true);settings()}
function settings(){
  const u=me()||{};
  page("Settings","Customize your app and manage your account",
  `<input id="stq" placeholder="🔍 ${L("Search settings","Shakisha mu igenamiterere")}" value="${esc(stQ)}" oninput="stQ=this.value;stApply()" style="margin-bottom:12px"><div class="c" style="display:flex;gap:12px;align-items:center"><div class="avatar">${uav(u)}</div><div class="m"><b style="font-size:17px">${esc(SE.name)}</b> <span class="chip">${SE.role==="Administrator"?"Business Owner":esc(SE.role)}</span><small style="display:block;margin-top:4px">✉️ ${esc(SE.id)}<br>🏪 ${esc(SE.biz)}${u.ph?`<br>📞 ${esc(u.ph)}`:""}${u.loc?`<br>📍 ${esc(u.loc)}`:""}</small></div><button class="add" onclick="ep()">✏️ Edit Profile</button></div>
  ${can("admin")?`<button class="btn" style="margin:-4px 0 12px" onclick="go('#/admin')">🛡️ ${L("Admin Settings & Reports","Admin Settings & Reports")}</button>`:""}
  ${sec("🔒","Account & Security","Manage your login and security settings",
    sg("🔑","Change Password","Update your account password","","cpw()")+
    sg("🛡️","Two-Factor Authentication","Add an extra layer of security",tgl("tfa"))+
    sg("🕒","Login Activity","View your recent login sessions","","la()"))}
  ${sec("⚙️","App Preferences","Customize how the app works for you",
    sg("🤖","AI Assistant","Show Memo AI on dashboard, menu and quick actions",tgl("ai"))+
    (PF.ai===false?sg("💬",L("Open Memo AI","Fungura Memo AI"),L("AI is off on the dashboard but works here","AI ntigaragara kuri dashboard ariko ikorera hano"),"","go('#/ai')"):"")+
    (can("admin")?sg("☁️",L("Cloud account","Konti ya cloud"),L("Sign in to sync your data online","Injira ubike amakuru kuri internet"),"","cloudM()")+
    sg("🧩",L("Arrange buttons","Teganya buto"),L("Choose where each button appears","Hitamo aho buri buto igaragara"),"","go('#/arrange')"):"")+
    sg("🌐",L("Language","Ururimi"),L("Choose the app language","Hitamo ururimi rw'app"),`<select onchange="PF.lang=this.value;savePF();route()">${LANGS.map(x=>`<option ${PF.lang===x||(!PF.lang&&x==="English")?"selected":""}>${x}</option>`).join("")}</select>`)+
    sg("🎨","Theme","Choose your preferred theme",`<select id="th" onchange="theme(this.value)"><option value="dark">Dark</option><option value="light">Light</option></select>`)+
    sg("🔔","Notifications","Manage alerts and notifications",tgl("notif"))+
    sg("🔊","Notification Sound","Ijwi iyo notification ije",tgl("snd"))+
    sg("🔉","Volume","Ijwi riri hejuru cyangwa hasi",`<input type="range" min="0" max="100" value="${PF.vol}" oninput="PF.vol=+this.value;savePF()" onchange="ping(null,true)" style="width:110px;margin:0">`)+
    sg("🎵",L("Sound Type","Ubwoko bw'ijwi"),L("Tap to choose a sound","Kanda uhitemo ijwi"),`<span class="chip">${esc(sndLabel(PF.tone||"chime"))}</span>`,"sndToggle()")+
    (SNDOPEN?SNDS.map(x=>sg(x[2],L(x[1],x[1]),(x[0]==="custom"&&!window.CUSTOM_URL)?L("Upload a file below","Shyiramo dosiye hepfo"):"",
      `${PF.tone===x[0]?'<span class="chip">✔</span>':""}<button class="ib" style="margin-left:6px" onclick="event.stopPropagation();ping('${x[0]}',true)">▶</button>${x[0]==="custom"?`<input type="file" accept="audio/*" onclick="event.stopPropagation()" onchange="sndUp(this)" style="max-width:110px;font-size:11px;margin-left:6px">`:""}`,
      `sndPick('${x[0]}')`)).join(""):"")+
    sg("📲","Browser Notifications","Notification ya browser iyo app ifunguye",tgl("bn"))+
    sg("☁️","Auto Backup","Save your data automatically",tgl("backup")))}
  ${sec("🏪","Business Settings","Manage your business information",
    sg("🏢","Business Profile","Edit your business details","","ep()")+
    sg("💰","Currency","Set your preferred currency",`<span class="chip">RWF (Rwandan Franc)</span>`)+
    (can("edit")?sg("🏷️","Product Categories","Add, edit and save categories","","catMgr()"):"")+
    (can("admin")?sg("📲","Mobile Money Codes","MTN na Airtel codes zo kwishyura","","mmCodes()")+sg("🖼️","Login Screen Photo","Photo shown on login & create account","","heroMgr()"):"")+
    sg("🧾","Tax Settings","Show VAT 18% on receipts",tgl("tax")))}
  ${sec("🛡️","Data & Privacy","Control your data and privacy",
    sg("💾","Backup & Restore","Backup or restore your data",`<span class="chip">${PF.bk?"Up to date":"No backup yet"}</span>`,"bk()")+
    sg("🧹","Clear Cache","Clear Memo AI history",`<span class="mu" style="font-size:12px">${cs()}</span><button class="ib" onclick="event.stopPropagation();cc()">Clear</button>`)+
    sg("🔐","Privacy Policy","Read our privacy policy","","pol('p')")+
    sg("📄","Terms of Service","Read our terms of service","","pol('t')"))}
  ${can("admin")?`<div class="c"><h3>🛡️ Administration</h3><button class="btn o d" onclick="resetData()">Reset Data</button></div>`:""}
  ${!can("admin")?`<div class="c"><h3>📊 Raporo (Report)</h3><button class="btn o" onclick="reportModal()">Ohereza Raporo kuri Admin</button></div>`:""}
  ${sec("ℹ️","About","App information and support",
    sg("ℹ️","About BizzAssist","Built by Albert Dushimimana","","aboutM()")+
    sg("💾","Data storage",navigator.onLine?"Online • saved on this phone":"Offline • saved on this phone","","")+
    sg("📦","App Version","BizzAssist Rwanda v1.7.2",`<span class="chip">Up to date</span>`)+
    sg("🎧","Help & Support","Get help or contact us","","hs()")+
    sg("⭐","Rate Us","If you like our app, rate us",PF.rate?`<span style="color:var(--am)">${"★".repeat(PF.rate)}</span>`:"","rt()"))}
  <button class="btn o d" onclick="ask('Logout','Uremeza gusohoka muri konti yawe?',logout)">⎋ Logout</button>`,{back:"#/home",nav:"settings"});
  $("th").value=ld("bizz_theme","dark");
  stApply();
}
let stQ="";
function stApply(){
  const q=(stQ||"").trim().toLowerCase();
  const app=$("app");if(!app)return;
  app.querySelectorAll(".sg").forEach(e=>{e.style.display=(!q||e.textContent.toLowerCase().includes(q))?"":"none"});
  app.querySelectorAll(".sh2").forEach(hd=>{
    const card=hd.nextElementSibling;
    const rows=card?[...card.querySelectorAll(".sg")]:[];
    const any=rows.some(r=>r.style.display!=="none");
    const show=!q||any||hd.textContent.toLowerCase().includes(q);
    hd.style.display=show?"":"none";
    if(card)card.style.display=show?"":"none";
  });
  app.querySelectorAll(".c").forEach(c=>{
    if(c.previousElementSibling&&c.previousElementSibling.classList.contains("sh2"))return;
    if(!c.querySelector("h3"))return;
    c.style.display=(!q||c.textContent.toLowerCase().includes(q))?"":"none";
  });
}
function tg(k){
  PF[k]=!PF[k];
  if(k==="bn"&&PF.bn){
    if(window.Notification){Notification.requestPermission().then(r=>{if(r!=="granted"){PF.bn=false;savePF();toast("Uruhushya ntirutanzwe");settings()}}).catch(()=>{})}
    else{PF.bn=false;toast("Browser ntibishyigikira")}
  }
  savePF();
  if(k==="snd"&&PF.snd)ping(null,true);
  toast("Byabitswe ✔");settings();
}
function la(){
  const L=(can("admin")?U:[me()]).filter(Boolean);
  modal(`<h3>🕒 Login Activity</h3>${L.map(u=>`<div class="tt"><span>${esc(u.name)}<br><small class="mu">${esc(u.id)}</small></span><span class="mu">${u.last?when(u.last):"-"}</span></div>`).join("")}<button class="btn o" style="margin-top:10px" onclick="closeM()">Close</button>`);
}
function bk(){
  modal(`<h3>💾 Backup & Restore</h3><p class="mu" style="margin-bottom:10px">Backup irimo data yose (harimo na passwords). Yibike ahantu hizewe.</p><button class="btn" onclick="bkCopy()">📋 Copy backup</button><label>Restore: paste backup hano</label><textarea id="bkt" rows="4" placeholder="Paste backup…"></textarea><button class="btn o" onclick="bkRestore()">♻️ Restore</button>`);
}
function bkCopy(){
  const d=JSON.stringify({v:1,users:U,products:P,sales:S,customers:C,expenses:X,memos:Memos,reports:Reports,reqs:Reqs,budget:bud,sup:SUP,cats:CAT});
  if(!navigator.clipboard)return toast("Copy ntibashije");
  navigator.clipboard.writeText(d).then(()=>{PF.bk=Date.now();savePF();toast("Backup yakopowe ✔")}).catch(()=>toast("Copy ntibashije"));
}
function bkRestore(){
  let d;try{d=JSON.parse($("bkt").value)}catch(e){return toast("Backup si yo")}
  if(!d||!Array.isArray(d.products)||!Array.isArray(d.sales)||!Array.isArray(d.users)||!d.users.length)return toast("Backup si yo");
  ask("Restore Data","Restore izasimbura data yose iriho. Komeza?",()=>{U=d.users;P=d.products;S=d.sales;C=ar(d.customers);X=ar(d.expenses);Memos=ar(d.memos);Reports=ar(d.reports);Reqs=ar(d.reqs);SUP=ar(d.sup);CAT=ar(d.cats).length?ar(d.cats):[...new Set(P.map(p=>p.k))];
  if(d.budget>0){bud=d.budget;sv("bizz_budget",bud)}
  save();toast("Restore byakozwe ✔");
  if(!U.some(x=>x.id===SE.id)){logout();return}
  route()});
}
function cc(){ask("Clear Cache","Uremeza gusiba Memo AI history?",()=>{Memos=[];save();toast("Cache yasibwe ✔");settings()})}
function pol(k){
  const T=k==="p"?["🔐 Privacy Policy","Amakuru yawe (ibicuruzwa, sales, expenses, abakiriya) abikwa muri iyi browser yawe gusa. Ntabwo yoherezwa kuri server. Ushobora kuyasiba igihe cyose ukoresheje Reset Data cyangwa Clear Cache."]:["📄 Terms of Service","BizzAssist Rwanda ni igikoresho cyo gufasha gucunga ubucuruzi. Ni wowe ubazwa ukuri kw'amakuru winjiza no kuyabika (Backup). Porogaramu itangwa uko iri."];
  modal(`<h3>${T[0]}</h3><p style="line-height:1.5;margin-bottom:12px">${T[1]}</p><button class="btn" onclick="closeM()">OK</button>`);
}
function hs(){
  modal(`<h3>🎧 Help & Support</h3><p style="line-height:1.5;margin-bottom:12px">Ukeneye ubufasha? Koresha "Ohereza Raporo" cyangwa "Request" kugira ngo ubutumwa bugere kuri Admin, cyangwa ubaze Memo AI.</p><div class="g2"><button class="btn o" onclick="go('#/memo')">🤖 Memo AI</button><button class="btn" onclick="closeM()">OK</button></div>`);
}
function rt(){
  modal(`<h3>⭐ Rate Us</h3><div style="display:flex;justify-content:center;gap:8px;font-size:34px;margin:10px 0 16px">${[1,2,3,4,5].map(n=>`<span style="cursor:pointer;color:${n<=PF.rate?"#f5a524":"var(--mu)"}" onclick="rtS(${n})">★</span>`).join("")}</div><button class="btn o" onclick="closeM()">Close</button>`);
}
function rtS(n){PF.rate=n;savePF();closeM();toast("Murakoze! ★"+n);settings()}
function goApr(id){
  const r=Reqs.find(x=>String(x.id)===String(id));if(!r)return;
  const m={expense_access:"#/expenses",exp_momo:"#/expenses",prod_add:"#/edit/new",prod_edit:"#/edit/"+r.pid};
  go(m[r.type]||"#/home");
}
function langPick(){
  const cur=PF.lang||"English";
  modal(`<h3>🌐 ${L("Language","Ururimi")}</h3>${LANGS.map(x=>`<button class="btn ${x===cur?"":"o"}" onclick="setLang('${x}')">${x===cur?"✔ ":""}${x}</button>`).join("")}<button class="btn o" onclick="closeM()">${L("Close","Funga")}</button>`);
}
function setLang(x){PF.lang=x;savePF();closeM();route()}
function notif(){
  const lo=P.filter(p=>p.s<=(p.lw||10)),rq=can("admin")?openReqs():[],db=dues(),up=S.filter(s=>s.debt>0&&s.due>Date.now()),dc=myDec();
  const decRow=r=>{const ok=r.status==="approved";return `<div class="row" style="cursor:default"><div class="em">${ok?"✅":"❌"}</div><div class="m"><b>${ok?L("Admin approved","Admin yabyemeye"):L("Admin rejected","Admin yarabyanze")}</b><small>${esc(TL[r.type]||r.type)}${r.desc?" • "+esc(r.desc):""}</small></div>${ok?`<button class="add" onclick="closeM();goApr('${r.id}')">${L("Continue","Komeza")}</button>`:""}</div>`};
  modal(`<h3>🔔 ${L("Notifications","Amatangazo")}</h3>${dc.map(decRow).join("")}${db.map(s=>`<div class="row" style="cursor:default"><div class="em">⏰</div><div class="m"><b>${esc(s.cu)} • ${fmt(s.debt)}</b><small>${inv(s.id)} • ${L("was due","yagombaga kwishyura")} ${dday(s.due)}</small></div><div style="display:flex;flex-direction:column;gap:6px"><button class="add" onclick="closeM();payDebt(${s.id})">💵 ${L("Payment","Ubwishyu")}</button><button class="ib" onclick="closeM();remindSms(${s.id})">📩 SMS</button></div></div>`).join("")}${rq.map(reqRow).join("")}${lo.map(p=>`<div class="tt"><span>${esc(p.e)} ${esc(p.n)}</span>${badge(p)}</div>`).join("")}${up.map(s=>`<div class="tt mu"><span>💳 ${esc(s.cu)} • ${fmt(s.debt)}</span><span>${dday(s.due)}</span></div>`).join("")}${lo.length+rq.length+db.length+up.length+dc.length?"":`<div class="emp">${L("No notifications.","Nta matangazo ahari.")}</div>`}<button class="btn o" style="margin-top:10px" onclick="closeM()">${L("Close","Funga")}</button>`);
  if(dc.length){dc.forEach(r=>r.seen=1);save();bellUpd()}
}
function reportModal(){
  const t=agg(0);
  modal(`<h3>📊 Ohereza Raporo kuri Admin</h3><p class="mu" style="margin-bottom:10px">Uyu munsi: ${fmt(t.t)} • Orders ${t.n} • Profit ${fmt(t.p)}</p>
  <label>Ubwoko</label><select id="rkd"><option>Raporo y'umunsi</option><option>Gusaba amafaranga</option><option>Gusaba stock</option><option>Ikibazo / Ubundi</option></select>
  <label>Icyo ushaka kubwira / gusaba Admin</label><textarea id="rmsg" rows="4" placeholder="Urugero: Nkeneye kongera stock y'isukari..."></textarea>
  <div class="g2"><button class="btn o" onclick="closeM()">Cancel</button><button class="btn" onclick="sendReportToAdmin()">Ohereza</button></div>`);
}
function sendReportToAdmin(){
  const t=agg(0),msg=$("rmsg").value.trim();
  if(!msg)return toast("Andika ubutumwa bwawe");
  Reports.unshift({id:Date.now(),user:SE.name,kind:$("rkd").value,msg,summary:`Sales: ${fmt(t.t)}, Orders: ${t.n}, Profit: ${fmt(t.p)}`,t:Date.now()});
  save();closeM();toast("Raporo yoherejwe kuri Admin ✔");
}
function ep(){tmpImg=(me()||{}).img||"";modal(`<h3>Edit Profile</h3>${photoField("u",me()||{})}<label>Full Name</label><input id="en" value="${esc(SE.name)}"><label>Business Name</label><input id="ebz" value="${esc(SE.biz)}"><label>Phone</label><input id="eph" inputmode="tel" value="${esc((me()||{}).ph||"")}"><label>Location</label><input id="elc" value="${esc((me()||{}).loc||"")}"><button class="btn" onclick="epS()">Save</button>`)}
function epS(){
  const n=$("en").value.trim(),b=$("ebz").value.trim();
  if(n.length<2||b.length<2)return toast("Andika amakuru yose");
  SE.name=n;SE.biz=b;sv("bizz_session",SE);const u=U.find(x=>x.id===SE.id);if(u){u.name=n;u.biz=b;u.ph=$("eph").value.trim();u.loc=$("elc").value.trim();u.img=tmpImg}
  save();closeM();toast("Byabitswe ✔");route();
}
function cpw(){modal(`<h3>Change Password</h3>${pwf("p0","Current password","current-password")}${pwf("p1","New password (min. 8)","new-password",false,true)}${pwf("p2","Confirm new password","new-password")}<button class="btn" onclick="cpwS()">Update</button>`)}
function cpwS(){
  const u=U.find(x=>x.id===SE.id),n=$("p1").value;
  const e=!u||u.pw!==$("p0").value?"Password y'ubu si yo.":!pwOk(n)?"Password nshya: nibura 8, inyuguti, imibare n'ibimenyetso.":n!==$("p2").value?"Passwords ntizihuye.":"";
  if(e)return toast(e);u.pw=n;save();closeM();toast("Password yahinduwe ✔");
}
function resetData(){
  ask("Clean / Reset Data","Ibicuruzwa, sales na expenses byose bizasibwa bisubizwe uko byari bimeze mbere. Ntibishobora gusubizwa inyuma.",()=>{P=JSON.parse(JSON.stringify(SEED));S=[];X=[];save();toast("Data reset ✔");route()},"SIBA");
}

/* ADMIN SETTINGS */
const ROLES={
 Administrator:{c:"#0f8a4f",d:"Full access to all features",p:["*"]},
 Manager:{c:"#1d6fe0",d:"Manage sales, products, reports",p:["home","sales","sale","receipt","products","product","edit","inventory","settings","shop","customers","expenses","memo"]},
 Cashier:{c:"#7c3aed",d:"Process sales, view products",p:["home","sales","sale","receipt","products","product","settings","shop","customers","memo"]},
 "Stock Keeper":{c:"#f59e0b",d:"Manage inventory, products",p:["home","products","product","edit","inventory","settings","shop","memo"]},
 "Sales Person":{c:"#0ea5a5",d:"Create sales, view customers",p:["home","sales","sale","receipt","settings","shop","customers","memo"]}};
const PERMS=[["add_sales","Add Sales"],["view_sales","View Sales"],["add_products","Add Products"],["edit_products","Edit Products"],["delete_products","Delete Products"],["add_expenses","Add Expenses"],["view_expenses","View Expenses"],["view_reports","View Reports"],["manage_customers","Manage Customers"],["manage_employees","Manage Employees"]];
const PMAP={sales:"view_sales",receipt:"view_sales",sale:"add_sales",customers:"manage_customers",expenses:"view_expenses",finance:"view_reports",reports:"view_reports",log:"view_reports",admin:"manage_employees"};
const PANY={products:["add_products","edit_products","delete_products"],product:["add_products","edit_products","delete_products"],edit:["add_products","edit_products"],inventory:["add_products","edit_products"],suppliers:["add_products","edit_products"]};
const PALWAYS=["home","more","settings","shop","files","ai","memo"];
function hp(k){if(!SE)return false;if(SE.role==="Administrator")return true;const u=me();if(!u||!Array.isArray(u.perms))return true;return u.perms.includes(k)}
function can(p){
  if(!SE)return true;
  const r=ROLES[SE.role||"Administrator"]||ROLES.Administrator;
  if(r.p.includes("*"))return true;
  if(p==="admin")return false;
  const u=me();
  if(u&&Array.isArray(u.perms)){
    if(PANY[p])return PANY[p].some(x=>u.perms.includes(x));
    if(PMAP[p])return u.perms.includes(PMAP[p]);
    return PALWAYS.includes(p);
  }
  return r.p.includes(p);
}
let aT="users";

function admin(){
  const tabs=[["users","👥","Users"],["reqs","✉️","Requests"],["rep","📊","Reports"]];
  let body="";
  if(aT==="users"){
    body=`<div class="c"><div class="tt" style="align-items:center;margin-bottom:10px"><h3 style="margin:0">👥 User Management</h3><button class="hb" style="padding:8px 12px" onclick="ue(-1)">＋ Add User</button></div>
    <div id="ul"></div></div>`;
  } else if(aT==="reqs"){
    body=`<div class="c"><h3>✉️ Ubusabe bw'Abakozi (Requests)</h3><div id="reqList"></div></div>`;
  } else {
    body=`<div class="c"><h3>📊 Raporo z'Abakozi (Reports)</h3><div id="repList"></div></div>`;
  }
  page("Admin Settings","Manage users, requests and reports",
  `<div class="tabs">${tabs.map(t=>`<button class="tab ${t[0]===aT?"on":""}" onclick="aT='${t[0]}';admin()">${t[1]} ${t[2]}</button>`).join("")}</div>${body}`,{back:"#/settings",nav:"settings"});
  if(aT==="users")ul();
  else if(aT==="reqs")renderReqs();
  else renderReps();
}
function ul(){
  $("ul").innerHTML=U.map((u,i)=>`<div class="row" style="cursor:default"><div class="em">${uav(u)}</div><div class="m"><b>${esc(u.name)}</b><small>${esc(u.id)} • Role: ${esc(u.role||"Administrator")}</small></div><button class="ib" onclick="impersonate(${i})" title="Enter account">👁</button><button class="ib" onclick="ue(${i})">✏️</button><button class="ib" style="border-color:var(--rd)" onclick="ud(${i})">🗑️</button></div>`).join("")||'<div class="emp">No users.</div>';
}
function impersonate(i){
  const u=U[i];if(!u||!SE)return;
  if(u.id===SE.id)return toast(L("This is your account","Iyi ni konti yawe"));
  if(!ld("bizz_back",null))sv("bizz_back",SE);
  SE={name:u.name,biz:u.biz,id:u.id,role:u.role||"Cashier"};sv("bizz_session",SE);
  logA("Admin entered account",u.name);
  go("#/home");
}
function backAdmin(){
  const back=ld("bizz_back",null);if(!back)return;
  SE=back;sv("bizz_session",SE);try{LS.removeItem("bizz_back")}catch(e){}
  logA("Admin returned to own account",SE.name);
  go("#/admin");
}
function cloudM(){
  if(!window.bizzSync||!bizzSync.enabled)return modal(`<h3>☁️ ${L("Cloud account","Konti ya cloud")}</h3><p class="mu" style="line-height:1.5;margin-bottom:12px">${L("Cloud is not connected yet. The administrator must add the server address in config.js.","Cloud ntiratangira. Admin agomba gushyira aderesi ya server muri config.js.")}</p><button class="btn o" onclick="closeM()">${L("Close","Funga")}</button>`);
  modal(`<h3>☁️ ${L("Cloud account","Konti ya cloud")}</h3><p class="mu" style="margin-bottom:10px">${bizzSync.signedIn()?L("Signed in as ","Winjiye nka ")+esc(bizzSync.email()):L("Not signed in","Ntiwinjiye")}</p>
  <input id="cle" inputmode="email" placeholder="${L("Email","Email")}" autocomplete="username"><input id="clp" type="password" placeholder="${L("Password","Password")}" autocomplete="current-password">
  <div class="g2"><button class="btn" onclick="cloudAuth(0)">${L("Sign in","Injira")}</button><button class="btn o" onclick="cloudAuth(1)">${L("Create","Fungura")}</button></div>
  <div class="g2"><button class="btn o" onclick="cloudSync()">⟳ ${L("Sync now","Hindura ubu")}</button><button class="btn o d" onclick="bizzSync.signOut();closeM();toast(L('Signed out','Wasohotse'))">${L("Sign out","Sohoka")}</button></div>`);
}
async function cloudAuth(up){
  try{
    const e=$("cle").value.trim(),pw=$("clp").value;
    if(up){const r=await bizzSync.signUp(e,pw);toast(r==="check_email"?L("Check your email to confirm","Reba email yawe wemeze"):L("Account created ✔","Konti yafunguwe ✔"))}
    else{await bizzSync.signIn(e,pw);await bizzSync.pull();toast(L("Signed in ✔","Winjiye ✔"));closeM();location.reload();return}
    closeM();
  }catch(err){toast(L("Cloud error: ","Ikosa rya cloud: ")+err.message)}
}
async function cloudSync(){
  try{await bizzSync.push();toast(L("Synced ✔","Byahujwe ✔"))}catch(e){toast(L("Sync failed","Guhuza byanze"))}
}
function imBanner(){
  const back=ld("bizz_back",null);if(!back||!SE)return "";
  return `<div style="background:#b45309;color:#fff;padding:8px 12px;display:flex;align-items:center;justify-content:space-between;gap:8px;font-size:13px"><span>👁 ${L("Viewing as","Urareba nka")} <b>${esc(SE.name)}</b></span><button class="tb" onclick="backAdmin()" style="font-size:12px;padding:4px 10px;border:1px solid #fff;border-radius:10px">${L("Back to admin","Subira kuri admin")}</button></div>`;
}
function renderReqs(){
  $("reqList").innerHTML=openReqs().map(r=>APR.includes(r.type)?reqRow(r):`<div class="row" style="cursor:default"><div class="em">✉️</div><div class="m"><b>${esc(r.user)} (${esc(r.type)})</b><small>${esc(r.desc)}<br>${when(r.t)}</small></div><button class="add" onclick="resolveReq(${Reqs.indexOf(r)})">Emeza</button></div>`).join("")||'<div class="emp">Nta busabe buhari.</div>';
}
function resolveReq(i){Reqs.splice(i,1);save();toast("Byemejwe ✔");renderReqs()}
function renderReps(){
  $("repList").innerHTML=Reports.map(rp=>`<div class="row" style="cursor:default"><div class="em">📊</div><div class="m"><b>${esc(rp.user)}${rp.kind?` • ${esc(rp.kind)}`:""}</b><small>${rp.msg?`💬 ${esc(rp.msg)}<br>`:""}${esc(rp.summary)}<br>${when(rp.t)}</small></div></div>`).join("")||'<div class="emp">Nta raporo zihari.</div>';
}
function ue(i){
  const n=i<0,u=n?{name:"",id:"",pw:"",role:"Cashier",active:true}:U[i];
  const cur=n||!Array.isArray(u.perms)?PERMS.map(x=>x[0]):u.perms;
  tmpImg=u.img||"";
  modal(`<h3>${n?"Add Employee":"Edit Employee"}</h3>
  ${photoField("u",u)}<label>Full Name</label><input id="un1" value="${esc(u.name)}">
  <label>Email or Phone</label><input id="ui1" placeholder="Email cyangwa Telefone (urugero 0788123456)" value="${esc(u.id)}" ${n?"":"readonly"}>
  <label>Password</label>${pwf("up","Password","new-password",u.pw,true)}
  <label>Role</label><select id="ur">${Object.keys(ROLES).map(r=>`<option ${r===(u.role||"Administrator")?"selected":""}>${r}</option>`).join("")}</select>
  <div class="c" style="padding:10px;margin:8px 0 10px"><h3 style="margin-bottom:8px">🔐 Permissions</h3>
  ${PERMS.map(x=>`<label class="ck" style="padding:9px 10px;border:1px solid var(--ln);border-radius:12px;margin:0 0 6px;background:var(--fd)"><input type="checkbox" class="pmc" data-p="${x[0]}" ${cur.includes(x[0])?"checked":""} style="width:18px;height:18px;margin:0 6px 0 0"> ${x[1]}</label>`).join("")}
  </div>
  <button class="btn" onclick="us1(${i})">${n?"Add Employee":"Update Employee"}</button>`);
}
function us1(i){
  const n=i<0,g=x=>$(x).value.trim(),name=g("un1"),id=g("ui1"),pw=$("up").value,role=$("ur").value;
  const perms=[...document.querySelectorAll(".pmc:checked")].map(x=>x.dataset.p);
  if(!name||!id||!pw)return toast("Uzuza ibisabwa byose");
  if(!pwOk(pw))return toast("Password: nibura 8, inyuguti, imibare n'ibimenyetso");
  if(n){
    if(!okId(id))return toast("Andika email cyangwa telefone nyayo");
    if(U.some(u=>nid(u.id)===nid(id)))return toast("Iyi konti isanzweho");
    U.push({name,biz:SE.biz,id,pw,role,perms,active:true,last:Date.now(),img:tmpImg});
    logA("User added",name);
  } else {
    const u=U[i];u.name=name;u.role=role;u.pw=pw;u.img=tmpImg;u.perms=perms;
    logA("User permissions changed",u.name);
    if(u.id===SE.id){SE.name=name;SE.role=role;sv("bizz_session",SE)}
  }
  save();closeM();toast("Byabitswe ✔");
  if(!can("admin")){go("#/home");return}
  admin();
}
let cfFn=null;
function ask(title,msg,fn,word){
  cfFn=fn;
  modal(`<h3>⚠️ ${title}</h3><p style="line-height:1.5;margin-bottom:12px">${msg}</p>${word?`<label>${L("Type","Andika")} "${word}" ${L("to confirm","kugira ngo wemeze")}</label><input id="cfw" autocomplete="off">`:""}<div class="g2"><button class="btn o" onclick="closeM()">${L("No, cancel","Oya, Reka")}</button><button class="btn" style="background:var(--rd);color:#fff" onclick="cfGo('${word||""}')">${L("Yes, confirm","Yego, Emeza")}</button></div>`);
}
function cfGo(w){
  if(w&&$("cfw").value.trim().toUpperCase()!==w)return toast(L("Type ","Andika ")+w+L(" correctly"," neza"));
  const f=cfFn;cfFn=null;closeM();if(f)f();
}
function ud(i){
  if(U.length<=1)return toast("Ntushobora gusiba umuyobozi wa nyuma");
  if(U[i].id===SE.id)return toast("Ntushobora gusiba konti yawe");
  const uid=U[i].id;ask("Siba User",`Uremeza gusiba ${esc(U[i].name)}? Ntibishobora gusubizwa inyuma.`,()=>{const k=U.findIndex(x=>x.id===uid);if(k>=0){logA("User deleted",U[k].name);U.splice(k,1);save();toast("Cyasibwe");admin()}});
}

/* V2 FOUNDATION */
const LANGS=["Kinyarwanda","English","Français","Kiswahili"];
const TR={"Français":{"Dashboard": "Tableau de bord", "Sales": "Ventes", "Products": "Produits", "Customers": "Clients", "Inventory": "Inventaire", "Finance": "Finances", "Reports": "Rapports", "Suppliers": "Fournisseurs", "Activity Log": "Journal d'activité", "Files & Photos": "Fichiers et photos", "Shop": "Boutique", "Expenses": "Dépenses", "Settings": "Paramètres", "More": "Plus", "Home": "Accueil", "Add": "Ajouter", "Save": "Enregistrer", "Cancel": "Annuler", "Close": "Fermer", "Delete": "Supprimer", "Edit": "Modifier", "Search": "Rechercher", "Today": "Aujourd'hui", "Yesterday": "Hier", "Total": "Total", "Profit": "Bénéfice", "Revenue": "Chiffre d'affaires", "Balance": "Solde", "Paid": "Payé", "Debt": "Dette", "Partial": "Partiel", "Login": "Connexion", "Create Account": "Créer un compte", "Upload": "Téléverser", "New Folder": "Nouveau dossier", "Gallery": "Galerie", "Open Camera": "Ouvrir la caméra", "Files": "Fichiers", "Photos": "Photos", "Documents": "Documents", "Downloads": "Téléchargements", "Pictures": "Images", "Videos": "Vidéos", "Music": "Musique", "Archives": "Archives", "Storage Used": "Espace utilisé", "Recent Files": "Fichiers récents", "Folders": "Dossiers", "View All": "Tout voir", "Show less": "Afficher moins", "Everyone": "Tout le monde", "Private": "Privé", "Cash": "Espèces", "Mobile Money": "Mobile Money", "Stock": "Stock", "Low Stock": "Stock faible", "In Stock": "En stock", "Out of Stock": "Rupture", "Notifications": "Notifications", "Language": "Langue", "Select all": "Tout sélectionner", "Logout": "Déconnexion", "Sale": "Vente", "Products running low": "Produits en stock faible", "Continue": "Continuer", "Approve": "Approuver", "Reject": "Rejeter", "Confirm": "Confirmer", "Back": "Retour", "Total Sales": "Total des ventes", "Today's Sales": "Ventes du jour", "Low stock": "Stock faible", "No notifications.": "Aucune notification.", "Save Product": "Enregistrer le produit", "Add Product": "Ajouter un produit", "Edit Product": "Modifier le produit", "Choose the app language": "Choisissez la langue de l'application"},"Kiswahili":{"Dashboard": "Dashibodi", "Sales": "Mauzo", "Products": "Bidhaa", "Customers": "Wateja", "Inventory": "Hifadhi", "Finance": "Fedha", "Reports": "Ripoti", "Suppliers": "Wasambazaji", "Activity Log": "Kumbukumbu ya shughuli", "Files & Photos": "Faili na picha", "Shop": "Duka", "Expenses": "Matumizi", "Settings": "Mipangilio", "More": "Zaidi", "Home": "Nyumbani", "Add": "Ongeza", "Save": "Hifadhi", "Cancel": "Ghairi", "Close": "Funga", "Delete": "Futa", "Edit": "Hariri", "Search": "Tafuta", "Today": "Leo", "Yesterday": "Jana", "Total": "Jumla", "Profit": "Faida", "Revenue": "Mapato", "Balance": "Salio", "Paid": "Imelipwa", "Debt": "Deni", "Partial": "Sehemu", "Login": "Ingia", "Create Account": "Fungua akaunti", "Upload": "Pakia", "New Folder": "Folda mpya", "Gallery": "Matunzio", "Open Camera": "Fungua kamera", "Files": "Faili", "Photos": "Picha", "Documents": "Hati", "Downloads": "Vipakuliwa", "Pictures": "Picha", "Videos": "Video", "Music": "Muziki", "Archives": "Kumbukumbu", "Storage Used": "Hifadhi iliyotumika", "Recent Files": "Faili za hivi karibuni", "Folders": "Folda", "View All": "Ona zote", "Show less": "Onyesha kidogo", "Everyone": "Kila mtu", "Private": "Binafsi", "Cash": "Taslimu", "Mobile Money": "Mobile Money", "Stock": "Hisa", "Low Stock": "Hisa ndogo", "In Stock": "Zipo", "Out of Stock": "Zimeisha", "Notifications": "Arifa", "Language": "Lugha", "Select all": "Chagua zote", "Logout": "Toka", "Sale": "Mauzo", "Products running low": "Bidhaa zinakaribia kuisha", "Continue": "Endelea", "Approve": "Idhinisha", "Reject": "Kataa", "Confirm": "Thibitisha", "Back": "Rudi", "Total Sales": "Jumla ya mauzo", "Today's Sales": "Mauzo ya leo", "Low stock": "Hisa ndogo", "No notifications.": "Hakuna arifa.", "Save Product": "Hifadhi bidhaa", "Add Product": "Ongeza bidhaa", "Edit Product": "Hariri bidhaa", "Choose the app language": "Chagua lugha ya programu"}};
const L=(en,rw)=>{const g=PF.lang||"English";if(g==="English")return en;if(g==="Kinyarwanda")return rw;return (TR[g]||{})[en]||en};
let LOG=ld("bizz_log",[]),FL=ld("bizz_files",[]);
function logA(a,d){if(!SE)return;LOG.unshift({id:Date.now()+Math.random(),t:Date.now(),u:SE.name,uid:SE.id,a,d:d||""});if(LOG.length>3000)LOG.length=3000;sv("bizz_log",LOG)}
const W=(n,pre,post)=>{const o=window[n];window[n]=function(...a){const c=pre?pre(a):null;const r=o.apply(this,a);try{if(post)post(a,c,r)}catch(e){}return r}};
W("login",()=>!!SE,(a,was)=>{if(SE&&!was)logA("Login")});
W("signup",()=>!!SE,(a,was)=>{if(SE&&!was)logA("Account created")});
W("logout",()=>logA("Logout"));
W("completeSaleAction",()=>S.length,(a,n)=>{if(S.length>n){const s=S[0];logA("Sale",inv(s.id)+" • "+s.cu+" • "+fmt(s.tot)+(s.debt>0?" • Debt "+fmt(s.debt):""))}});
W("payDebtS",a=>{const s=S.find(x=>x.id===a[0]);return s?s.debt:0},(a,d)=>{const s=S.find(x=>x.id===a[0]);if(s&&s.debt<d)logA("Debt payment",inv(s.id)+" • "+s.cu+" • "+fmt(d-s.debt))});
W("saveP",a=>P.length,(a,n)=>{if(location.hash.startsWith("#/product/")){if(a[0]==="new"||P.length>n){const p=P[P.length-1];logA("Product added",p.n)}else{const p=gp(+a[0]);if(p)logA("Product edited",p.n)}}});
W("smS",a=>{const p=gp(a[0]);return p?{n:p.n,s:p.s}:null},(a,c)=>{const p=gp(a[0]);if(c&&p&&p.s!==c.s)logA("Stock updated",c.n+": "+c.s+" → "+p.s)});
W("xsv",()=>X.length,(a,n)=>{if(X.length>n){const x=X[X.length-1];logA("Expense added",x.ds+" • "+fmt(x.a)+" • "+x.pm)}else if(!$("md").classList.contains("on"))logA("Expense edited","")});
W("saveCust",()=>C.length,(a,n)=>{if(C.length>n)logA("Customer added",C[C.length-1].n)});
W("us1",()=>U.length,(a,n)=>{if(U.length>n)logA("User added",U[U.length-1].name);else if(!$("md").classList.contains("on"))logA("User edited","")});
W("sendApr",()=>Reqs.length,(a,n)=>{if(Reqs.length>n)logA("Approval requested",(TL[a[0]]||a[0])+" • "+Reqs[Reqs.length-1].desc)});
W("xAsk",()=>Reqs.length,(a,n)=>{if(Reqs.length>n)logA("Approval requested","Expenses")});
W("xDec",a=>{const r=Reqs.find(x=>x.id===a[0]);return r?r.status:null},(a,s)=>{const r=Reqs.find(x=>x.id===a[0]);if(r&&r.status!==s)logA(r.status==="approved"?"Approval granted":"Approval rejected",r.user+" • "+(TL[r.type]||r.type))});
W("sendReportToAdmin",()=>Reports.length,(a,n)=>{if(Reports.length>n)logA("Report sent",Reports[0].kind||"")});
ROLES.Manager.p.push("more","log","finance","reports","suppliers","files","ai");
ROLES.Cashier.p.push("more","files","ai");
ROLES["Stock Keeper"].p.push("more","suppliers","files","ai");
ROLES["Sales Person"].p.push("more","files","ai");

/* save/download helper */
const csvOf=(h,rows)=>[h,...rows].map(r=>r.map(c=>{c=String(c==null?"":c);return /[",\n]/.test(c)?'"'+c.replace(/"/g,'""')+'"':c}).join(",")).join("\n");
async function saveFile(name,data){
  try{const dl=typeof claude!=="undefined"?await claude.use("downloads"):null;if(dl){await dl.save({filename:name,data});return}}catch(e){if(e&&e.code==="declined")return}
  try{
    if(typeof data==="string"&&/\.csv$/i.test(name))data="\ufeff"+data;
    const blob=data instanceof Blob?data:new Blob([data],{type:/\.csv$/i.test(name)?"text/csv;charset=utf-8":"application/octet-stream"});
    const url=URL.createObjectURL(blob),a=document.createElement("a");
    a.href=url;a.download=name;a.rel="noopener";document.body.appendChild(a);a.click();
    setTimeout(()=>{URL.revokeObjectURL(url);a.remove()},4000);
    toast(L("Download started","Gukururwa byatangiye"));
  }catch(e){
    if(typeof data==="string")cpTxt(data);else toast(L("Download not available here","Gukuramo ntibishoboka hano"));
  }
}

/* MORE */
const HC={inventory:"#2f6fe0",finance:"#1f9d55",reports:"#8a4fe0",suppliers:"#c99a00",log:"#1d8cff",files:"#e5483f",shop:"#14b8a6",expenses:"#f08a1c",ai:"#7c3aed",settings:"#0f8a4f",sales:"#e5483f",products:"#c99a00",customers:"#1d8cff"};
function more(){
  home();
  openHP();
}
function openHP(){
  const T=navCfg().hm.map(navItem).filter(navOk);
  const rows=T.map(x=>`<div class="sg" style="--hc:${HC[x[0]]||"#0f8a4f"}" onclick="go('#/${x[0]}')"><i>${x[1]}</i><div class="m"><b>${x[2]}</b></div><span class="chv">›</span></div>`).join("")||`<div class="emp">${L("No buttons here.","Nta buto zihari.")}</div>`;
  let box=$("hpanel");
  if(!box){box=document.createElement("div");box.id="hpanel";document.body.appendChild(box)}
  box.innerHTML=`<div class="hp-in"><div class="hp-h"><b>☰ ${L("Home","Home")}</b><button class="tb" onclick="closeHP()" aria-label="Close">✕</button></div><div class="hp-l">${rows}</div></div>`;
  trDom(box);
  requestAnimationFrame(()=>box.classList.add("on"));
}
function closeHP(){
  const box=$("hpanel");if(!box)return;
  box.classList.remove("on");
  setTimeout(()=>{if(!box.classList.contains("on"))box.innerHTML=""},260);
}
function dashPanel(){
  const t=agg(0),lo=P.filter(p=>p.s<=(p.lw||10)).length;
  return `<div class="c" style="padding:10px"><b style="font-size:15px">${L("Welcome","Murakaza")}, ${esc(SE.name.split(" ")[0])}</b><div class="mu" style="font-size:11.5px">${L("Your business, our priority","Ubucuruzi bwawe, ibyo dushyira imbere")}</div></div>
  <div class="dstat">${[["🛒",L("Today's Sales","Ibyagurishijwe uyu munsi"),fmt(t.t)],["🧾",L("Today's Orders","Ibyatumijwe uyu munsi"),t.n],["📈",L("Today's Profit","Inyungu y'uyu munsi"),fmt(t.p)],["⚠️",L("Low Stock","Bigiye gushira"),lo]].map(x=>`<div><small>${x[0]} ${x[1]}</small><b>${x[2]}</b></div>`).join("")}</div>
  <div class="c" style="padding:10px"><h3 style="font-size:14px;margin-bottom:8px">⚡ ${L("Quick Actions","Ibikorwa byihuse")}</h3><div style="display:grid;gap:8px">${qaHTML()}</div></div>`;
}
function navHub(){
  page(L("Navigator & More","Navigator na Home"),L("Control where each button appears","Hitamo aho buri buto igaragara"),
  `<div class="s" onclick="go('#/navmgr')" style="margin-bottom:10px"><i>🧭</i><div><b>${L("Navigator Management","Gucunga Navigator")}</b><small>${L("Buttons in the bottom bar","Buto ziri mu murongo wo hasi")}</small></div></div>
  <div class="s" onclick="go('#/homemgr')"><i>🏠</i><div><b>${L("Home Management","Gucunga Home")}</b><small>${L("Buttons inside the Home menu (☰ top right)","Buto ziri muri menu ya Home (☰ hejuru iburyo)")}</small></div></div>
  <p class="mu" style="font-size:12.5px;line-height:1.5;margin-top:12px">${L("Every button is either in the Navigator (bottom bar) or in Home — never both. The Navigator holds up to 5 buttons.","Buri buto iba muri Navigator (umurongo wo hasi) cyangwa muri Home — ntiba hose. Navigator ifata buto 5 ntarengwa.")}</p>`,{back:"#/settings",nav:"settings"});
}
function navSave(c){PF.nav=c.nv;PF.hm=c.hm;savePF();logA("Settings changed","Navigator & Home")}
function navRe(){location.hash.indexOf("homemgr")>-1?homeMgr():navMgr()}
function navTo(k,where){
  const c=navCfg();
  if(where==="nav"){if(c.nv.includes(k))return;if(c.nv.length>=5)return toast(L("The navigator holds at most 5 buttons","Navigator ifata buto 5 gusa"));c.hm=c.hm.filter(x=>x!==k);c.nv.push(k)}
  else{if(!c.nv.includes(k))return;if(c.nv.length<=1)return toast(L("Keep at least 1 button in the navigator","Navigator igomba kugumamo nibura buto 1"));c.nv=c.nv.filter(x=>x!==k);c.hm.push(k)}
  navSave(c);navRe();
}
function navUp(list,k,d){const c=navCfg(),a=list==="nav"?c.nv:c.hm,i=a.indexOf(k),j=i+d;if(i<0||j<0||j>=a.length)return;[a[i],a[j]]=[a[j],a[i]];navSave(c);navRe()}
function navRow(k,list,i,n){
  const x=navItem(k);if(!x)return "";
  return `<div class="row" style="cursor:default"><div class="em">${x[1]}</div><div class="m"><b>${x[2]}</b><small>${x[3]}</small></div><button class="ib" style="padding:6px 8px" ${i===0?"disabled":""} onclick="navUp('${list}','${k}',-1)">▲</button><button class="ib" style="padding:6px 8px" ${i===n-1?"disabled":""} onclick="navUp('${list}','${k}',1)">▼</button><button class="add" onclick="navTo('${k}','${list==="nav"?"home":"nav"}')">${list==="nav"?"→ Home":"→ Navigator"}</button></div>`;
}
function navPrev(c){return `<div class="c" style="padding:8px"><div class="mu" style="font-size:11.5px;margin-bottom:6px">${L("Preview of the bottom bar","Uko umurongo wo hasi usa")}</div><div style="display:flex;gap:4px;justify-content:space-around;background:var(--fd);border-radius:12px;padding:8px 2px">${c.nv.map(navItem).filter(Boolean).map(x=>`<div style="text-align:center;font-size:10.5px;color:var(--mu);min-width:52px"><div style="font-size:20px">${x[1]}</div>${x[2]}</div>`).join("")}</div></div>`}
function navMgr(){
  const c=navCfg();
  page(L("Navigator Management","Gucunga Navigator"),L("Buttons shown in the bottom bar","Buto zigaragara mu murongo wo hasi"),
  `${navPrev(c)}<div class="c"><h3>🧭 ${L("In the Navigator","Muri Navigator")} (${c.nv.length}/5)</h3>${c.nv.map((k,i)=>navRow(k,"nav",i,c.nv.length)).join("")}</div>
  <div class="c"><h3>🏠 ${L("Available (in Home)","Ziriho (muri Home)")}</h3>${c.hm.map((k,i)=>navRow(k,"hm",i,c.hm.length)).join("")||`<div class="emp">—</div>`}</div>`,{back:"#/navhub",nav:"settings"});
}
function homeMgr(){
  const c=navCfg();
  page(L("Home Management","Gucunga Home"),L("Buttons shown in the Home menu (☰)","Buto zigaragara muri menu ya Home (☰)"),
  `<div class="c"><h3>🏠 ${L("In Home","Muri Home")} (${c.hm.length})</h3>${c.hm.map((k,i)=>navRow(k,"hm",i,c.hm.length)).join("")||`<div class="emp">—</div>`}</div>
  <div class="c"><h3>🧭 ${L("In the Navigator","Muri Navigator")} (${c.nv.length}/5)</h3>${c.nv.map((k,i)=>navRow(k,"nav",i,c.nv.length)).join("")}</div>`,{back:"#/navhub",nav:"settings"});
}

/* DASHBOARD PIECES */
function insights(){
  const t=agg(0),lo=P.filter(p=>p.s>0&&p.s<=(p.lw||10)),out=P.filter(p=>p.s<=0),ov=dues(),r=[];
  r.push(L(`Today: ${t.n} sale(s), ${fmt(t.t)}.`,`Uyu munsi: ibyagurishijwe ${t.n}, ${fmt(t.t)}.`));
  if(lo.length)r.push(L(`${lo.length} product(s) are running low: ${lo.slice(0,3).map(p=>p.n).join(", ")}.`,`Ibicuruzwa ${lo.length} bigiye gushira: ${lo.slice(0,3).map(p=>p.n).join(", ")}.`));
  if(out.length)r.push(L(`${out.length} product(s) are out of stock.`,`Ibicuruzwa ${out.length} byashize muri stock.`));
  if(ov.length)r.push(L(`${ov.length} customer debt(s) are due now.`,`Amadeni ${ov.length} y'abakiriya yageze igihe cyo kwishyurwa.`));
  return r;
}
function aiCard(){
  if(PF.ai===false)return "";
  return `<div class="c"><h3>🤖 Memo AI <button class="add" onclick="go('#/ai')">${L("Ask AI","Baza AI")}</button></h3>${insights().slice(0,3).map(m=>`<div style="font-size:13px;margin-bottom:6px">💡 ${esc(m)}</div>`).join("")}</div>`;
}
let hq="",hs2="all";
function stockCard(){
  return `<div class="c"><h3>📦 ${L("Products in stock","Ibicuruzwa biri muri stock")}<button class="add" onclick="go('#/${can("inventory")?"inventory":"products"}')">${L("Open","Fungura")}</button></h3><input id="hqs" value="${esc(hq)}" placeholder="${L("🔍 Search product, code or category…","🔍 Shakisha igicuruzwa, code cyangwa icyiciro…")}" oninput="hq=this.value;homeStock()"><div class="tabs" id="hqt"></div><div id="hst"></div></div>`;
}
function homeStock(){
  const e=$("hst");if(!e)return;
  const q=hq.toLowerCase(),f=hs2,cnt=k=>P.filter(p=>st(p)===k).length;
  const tabs=[["all",L("All","Byose"),P.length],["in",L("In stock","Bihari"),cnt("in")],["low",L("Low","Bigiye gushira"),cnt("low")],["out",L("Out","Byashize"),cnt("out")]];
  $("hqt").innerHTML=tabs.map(t=>`<button class="tab ${f===t[0]?"on":""}" onclick="hs2='${t[0]}';homeStock()">${t[1]} (${t[2]})</button>`).join("");
  const R=P.filter(p=>(f==="all"||st(p)===f)&&(!q||(p.n+code(p)+p.k).toLowerCase().includes(q)));
  e.innerHTML=R.map(p=>`<div class="row" onclick="go('#/product/${p.id}')"><div class="em">${pim(p)}</div><div class="m"><b>${esc(p.n)}</b><small>${esc(code(p))} • ${esc(p.k)}</small></div><div class="r"><b>${p.s} ${esc(p.u||"")}</b><br>${badge(p)}</div></div>`).join("")||`<div class="emp">${L("No products found.","Nta gicuruzwa kibonetse.")}</div>`;
}

/* ACTIVITY LOG */
let lgQ="",lgD="all",lgU="";
const LI=a=>/^Sale/.test(a)?"🛒":/Product|Stock/.test(a)?"📦":/Expense/.test(a)?"🧾":/Login|Logout|Account/.test(a)?"🔐":/Approval/.test(a)?"✅":/Debt/.test(a)?"💳":/Customer/.test(a)?"👥":/User/.test(a)?"👤":/Report/.test(a)?"📊":/File/.test(a)?"🗂️":"📝";
const trs=s=>typeof tr==="function"?tr(s):s;
function logPage(){
  page(L("Activity Log","Ibyakozwe byose"),L("Everything done in the app, with date & time","Ibikorwa byose byakozwe, hamwe n'itariki n'isaha"),
  `<input id="lgq" placeholder="${L("🔍 Search action, person or detail…","🔍 Shakisha igikorwa, umuntu cyangwa ibisobanuro…")}" oninput="lgQ=this.value;logR()">
  <div class="tabs">${[["all",L("All","Byose")],["today",L("Today","Uyu munsi")],["yest",L("Yesterday","Ejo")],["week",L("7 days","Iminsi 7")]].map(x=>`<button class="tab ${lgD===x[0]?"on":""}" onclick="lgD='${x[0]}';logPage()">${x[1]}</button>`).join("")}</div>
  <div class="g2" style="margin-bottom:0"><input id="lgdt" type="date" value="${lgD.startsWith("d:")?lgD.slice(2):""}" onchange="lgD='d:'+this.value;logPage()">${can("admin")?`<select id="lgu" onchange="lgU=this.value;logR()"><option value="">${L("All users","Abakozi bose")}</option>${[...new Set(LOG.map(l=>l.u))].map(u=>`<option ${u===lgU?"selected":""}>${esc(u)}</option>`).join("")}</select>`:"<div></div>"}</div>
  <div class="c"><div id="lgl"></div></div>
  <button class="btn o" onclick="logExport()">⬇ ${L("Export CSV","Kuramo CSV")}</button>`,{back:"#/more",nav:"log"});
  $("lgq").value=lgQ;logR();
}
function lgf(){
  const q=lgQ.toLowerCase(),n=new Date();n.setHours(0,0,0,0);const t0=n.getTime();
  return LOG.filter(l=>{
    if(!can("admin")&&l.uid!==SE.id)return false;
    if(lgU&&l.u!==lgU)return false;
    const d=l.t;
    if(lgD==="today"&&d<t0)return false;
    if(lgD==="yest"&&(d>=t0||d<t0-864e5))return false;
    if(lgD==="week"&&d<t0-6*864e5)return false;
    if(lgD.startsWith("d:")&&lgD.length>2){const s=new Date(lgD.slice(2)+"T00:00:00").getTime();if(d<s||d>=s+864e5)return false}
    return !q||(l.a+" "+trs(l.a)+" "+l.u+" "+l.d+" "+new Date(d).toLocaleDateString("en-GB",{day:"2-digit",month:"short",year:"numeric"})).toLowerCase().includes(q);
  });
}
function logR(){
  const R=lgf(),e=$("lgl");let day="",h="";
  R.slice(0,300).forEach(l=>{
    const d=new Date(l.t),ds=d.toLocaleDateString("en-GB",{weekday:"short",day:"2-digit",month:"short",year:"numeric"});
    if(ds!==day){day=ds;h+=`<div class="mu" style="font-size:12px;font-weight:700;padding:10px 0 4px">📅 ${ds}</div>`}
    h+=`<div class="row" style="cursor:default"><div class="em" style="font-size:18px">${LI(l.a)}</div><div class="m"><b>${esc(l.a)}</b><small>${esc(l.u)}${l.d?" • "+esc(l.d):""}</small></div><div class="r"><small>🕘 ${d.toLocaleTimeString("en-US",{hour:"2-digit",minute:"2-digit",second:"2-digit"})}</small></div></div>`;
  });
  e.innerHTML=(h||`<div class="emp">${L("No activity found.","Nta bikorwa bibonetse.")}</div>`)+`<div class="tt mu" style="margin-top:8px"><span>${L("Showing","Hagaragara")} ${Math.min(300,R.length)} / ${R.length}</span></div>`;
}
function logExport(){
  const R=lgf();
  saveFile("activity-log.csv",csvOf(["Date","Time","User","Action","Details"],R.map(l=>{const d=new Date(l.t);return [ymd(d),d.toLocaleTimeString("en-US"),l.u,l.a,l.d]})));
}

/* SUPPLIERS PAGE */
let spQ="";
function suppliers(){
  page(L("Suppliers","Abatanga ibicuruzwa"),L("People and companies who supply you","Abantu n'ibigo bagutangira ibicuruzwa"),`<input id="spq" placeholder="${L("🔍 Search supplier…","🔍 Shakisha utanga ibicuruzwa…")}" oninput="spQ=this.value;spR()"><button class="btn" onclick="supEdit(0,2)">＋ ${L("Add Supplier","Ongeramo utanga ibicuruzwa")}</button><div id="spl"></div>`,{back:"#/more",nav:"suppliers"});
  $("spq").value=spQ;spR();
}
function spR(){
  const q=spQ.toLowerCase();
  $("spl").innerHTML=SUP.filter(s=>!q||(s.n+(s.ph||"")+(s.loc||"")).toLowerCase().includes(q)).map(s=>{
    const ps=P.filter(p=>p.sup===s.id),val=ps.reduce((a,p)=>a+p.s*p.c,0);
    return `<div class="c"><div style="display:flex;gap:10px;align-items:center"><div class="em">🚚</div><div class="m"><b>${esc(s.n)}</b><small>${esc(s.ph||"")}${s.loc?" • "+esc(s.loc):""}</small></div><button class="ib" onclick="supEdit(${s.id},2)">✏️</button><button class="ib" style="border-color:var(--rd)" onclick="supDel2(${s.id})">🗑️</button></div>
    <div class="tt mu" style="margin-top:6px"><span>${ps.length} ${L("products","ibicuruzwa")}</span><span>${L("Stock value","Agaciro ka stock")}: ${fmt(val)}</span></div>
    <div class="g2" style="margin:8px 0 0">${s.ph?`<a class="btn o" style="display:grid;place-items:center;text-decoration:none;margin:0" href="tel:${esc(s.ph)}">📞 ${L("Call","Hamagara")}</a>`:"<div></div>"}<button class="btn o" style="margin:0" onclick="supPr(${s.id})">📦 ${L("Products","Ibicuruzwa")}</button></div></div>`;
  }).join("")||`<div class="emp">${L("No suppliers yet.","Nta batanga ibicuruzwa bahari.")}</div>`;
}
function supPr(id){
  const s=SUP.find(x=>x.id===id),ps=P.filter(p=>p.sup===id);
  modal(`<h3>🚚 ${esc(s.n)}</h3>${ps.map(p=>`<div class="row" style="cursor:default"><div class="em">${pim(p)}</div><div class="m"><b>${esc(p.n)}</b><small>${L("Cost","Igiciro cyo kugura")}: ${fmt(p.c)}</small></div><div class="r"><b>${p.s}</b><small>${esc(p.u||"")}</small></div></div>`).join("")||`<div class="emp">${L("No products linked to this supplier.","Nta bicuruzwa bihuje n'uyu utanga ibicuruzwa.")}</div>`}<button class="btn o" style="margin-top:10px" onclick="closeM()">${L("Close","Funga")}</button>`);
}
function supDel2(id){
  const s=SUP.find(x=>x.id===id);if(!s)return;
  ask(L("Delete Supplier","Siba utanga ibicuruzwa"),L(`Delete ${esc(s.n)}? His products will have no supplier.`,`Uremeza gusiba ${esc(s.n)}? Ibicuruzwa bye ntibizaba bifite utanga ibicuruzwa.`),()=>{SUP=SUP.filter(x=>x.id!==id);P.forEach(p=>{if(p.sup===id)p.sup=0});save();spR()});
}

/* AI */
let aiT=[],aiBusy=false,aiCtl=null;
function aiPage(){
  const adm=can("admin");
  const sug=adm?[L("How much did we sell today?","Uyu munsi twagurishije angahe?"),L("Explain what each seller did today","Nsobanurira ibyo buri muyuza yakoze uyu munsi"),L("Which products are running low?","Ni ibihe bicuruzwa bigiye gushira?"),L("Who owes us money?","Ni nde ufite ideni?")]:[L("How much did I sell today?","Uyu munsi nagurishije angahe?"),L("Which products are running low?","Ni ibihe bicuruzwa bigiye gushira?"),L("What is the price of sugar?","Isukari igura angahe?")];
  page("Memo AI",L("Ask in Kinyarwanda or English","Baza mu Kinyarwanda cyangwa mu Cyongereza"),
  `<div class="c"><div id="aiMsgs" style="max-height:52vh;overflow:auto"></div><div class="tabs" style="flex-wrap:wrap;margin:8px 0">${sug.map(s=>`<button class="tab" onclick="askAI(this.textContent)">${esc(s)}</button>`).join("")}</div>
  <div style="display:flex;gap:8px"><input id="aiQ" placeholder="${L("Type your question…","Andika ikibazo cyawe…")}" style="margin:0" onkeydown="if(event.key==='Enter')askAI()"><button class="add" style="height:44px;min-width:48px" onclick="askAI()">➤</button></div>
  <div style="text-align:right;margin-top:6px"><button class="ib" onclick="aiT=[];renderAI()">🗑 ${L("Clear chat","Siba ibiganiro")}</button> <button class="ib" id="aiStop" style="display:none" onclick="aiCtl&&aiCtl.abort()">⏹</button></div></div>
  <div class="c"><h3>💡 ${L("Insights","Inama n'ibyagaragaye")}</h3>${insights().map(m=>`<div style="font-size:13px;margin-bottom:6px">💡 ${esc(m)}</div>`).join("")}</div>`,{back:"#/home",nav:"ai"});
  renderAI();
}
function renderAI(){
  const e=$("aiMsgs");if(!e)return;
  e.innerHTML=aiT.map(m=>`<div style="margin:8px 0;display:flex;justify-content:${m.role==="user"?"flex-end":"flex-start"}"><div style="max-width:90%;padding:9px 12px;border-radius:14px;background:${m.role==="user"?"#0c4a31":"var(--fd)"};border:1px solid var(--ln);white-space:pre-wrap;line-height:1.45;font-size:13.5px">${esc(m.content)}</div></div>`).join("")||`<div class="emp">${L("Ask me anything about your business…","Mbaza icyo ushaka ku bucuruzi bwawe…")}</div>`;
  e.scrollTop=e.scrollHeight;
  const b=$("aiStop");if(b)b.style.display=aiBusy?"inline-block":"none";
}
const AT=(en,rw,fr,sw)=>({English:en,Kinyarwanda:rw,"Français":fr,"Kiswahili":sw})[PF.lang||"English"]||en;
async function askAI(q0){
  if(aiBusy)return;
  const inp=$("aiQ"),q=String(q0||(inp?inp.value:"")).trim();if(!q)return;if(inp)inp.value="";
  const TH=AT("Thinking…","Ndatekereza…","Je réfléchis…","Ninafikiria…");
  aiT.push({role:"user",content:q},{role:"assistant",content:TH});aiBusy=true;renderAI();
  const set=t=>{aiT[aiT.length-1].content=t;renderAI()};
  try{
    const sm=typeof claude!=="undefined"?await claude.use("sample"):null;
    if(!sm)throw {code:"none"};
    const hist=aiT.slice(0,-2).slice(-12).map(m=>({role:m.role,content:m.content}));
    while(hist.length&&hist[0].role!=="user")hist.shift();
    const msgs=[...hist,{role:"user",content:aiRules()+"\n\nUSER MESSAGE:\n"+q}];
    aiCtl=new AbortController();
    const r=await sm(msgs,{cache:false,signal:aiCtl.signal,modelTier:"default",onText:({text})=>set(text)});
    set(r.text);
  }catch(e){
    const c=e&&e.code;
    if(c==="cancelled"){const cur=aiT[aiT.length-1].content;set(cur===TH?AT("Stopped.","Byahagaritswe.","Arrêté.","Imesimamishwa."):cur)}
    else if(c==="not_granted"||c==="session_expired")set(AT("Claude access was not allowed for this view. Allow it when asked, then try again.","Claude ntiyemewe muri iyi view. Yemera igihe ubisabwe, hanyuma ugerageze.","L'accès à Claude n'a pas été autorisé. Acceptez-le lorsqu'il vous est demandé.","Ufikiaji wa Claude haujaruhusiwa. Ruhusu utakapoulizwa."));
    else if(c==="rate_limited"||c==="queue_overflow")set(AT("Too many questions at once. Wait a moment and try again.","Ibibazo byinshi icyarimwe. Tegereza gato ugerageze.","Trop de questions à la fois. Attendez un instant.","Maswali mengi kwa wakati mmoja. Subiri kidogo."));
    else set(aiLocal(q)+"\n\n"+AT("ℹ️ Answered by the built-in assistant (Claude is not available right now).","ℹ️ Igisubizo cy'umufasha wa app (Claude ntiboneka ubu).","ℹ️ Réponse de l'assistant intégré (Claude n'est pas disponible).","ℹ️ Jibu la msaidizi wa programu (Claude haipatikani sasa)."));
  }
  aiBusy=false;aiCtl=null;renderAI();
}
function aiRules(){
  const adm=can("admin"),now=new Date().toISOString().slice(0,16).replace("T"," ");
  return [
  `You are Memo AI, a friendly, smart assistant inside the BizzAssist Rwanda app. Chat naturally, like ChatGPT. Answer ANY question the user asks (general knowledge, advice, writing, maths, explanations, translations). You also know this business through the DATA below.`,
  `LANGUAGE: Reply in the language of the user's LAST message: Kinyarwanda, English, French or Kiswahili (mixed is fine). If the user asks to switch language (for example "let's speak English" or "ese twakigana English"), switch and keep using that language from then on. Write correct, natural Kinyarwanda when replying in Kinyarwanda.`,
  `FACTS: For questions about this business (sales, stock, prices, debts, customers, expenses, activity), use ONLY the DATA. Never invent numbers or records. If something is not in the DATA, say so. When you give a number, briefly say how you got it. Currency: RWF.`,
  `STYLE: Warm, clear and concise. Use short paragraphs, or a short list when it helps. Remember and use the earlier messages of this conversation.`,
  `CURRENT USER: ${SE.name} (role: ${SE.role}). Current time (UTC): ${now}.`,
  adm?`ACCESS: The current user is the admin/owner. You may explain everything in the DATA, including what each seller or cashier did, with dates and times.`
     :`ACCESS: The current user is NOT the admin. Do NOT reveal admin-only information: profit, cost/purchase prices, finance or expenses totals, other users' accounts or activity, passwords, or the owner's account. Politely refuse those in the user's language and offer what you can help with (products, prices, stock, their own sales, customers, how to use the app). General questions are fine.`,
  "DATA:\n"+aiData()
  ].join("\n\n");
}
function aiData(){
  const adm=can("admin"),me0=SE.name,iso=t=>new Date(t).toISOString().slice(0,16).replace("T"," ");
  const ss=adm?S:S.filter(s=>s.by===me0);
  const sl=ss.slice(0,150).map(s=>[inv(s.id),iso(s.t),s.cu,"by:"+(s.by||"?"),s.items.map(l=>l.n+" x"+(l.qt||l.q)+(l.u?" "+l.u:"")+"@"+l.p).join("; "),"total:"+s.tot,"paid:"+(s.paid!=null?s.paid:s.tot),"debt:"+(s.debt||0),s.due&&s.debt>0?"due:"+iso(s.due).slice(0,10):"",s.pm].filter(Boolean).join(" | "));
  const pr=P.map(p=>[p.n,code(p),p.k,"stock:"+p.s+" "+(p.u||""),"price:"+p.p+(p.pk&&p.pk.length?" packs:"+p.pk.map(k=>k.n+"("+k.q+"pcs)="+k.p).join(","):"")+(adm?" cost:"+p.c:"")].join(" | "));
  const o=["PRODUCTS ("+P.length+"):",...pr,"","SALES"+(adm?" (all users)":" (this user only)")+" ("+ss.length+" total, newest first, max 150):",...sl,"","CUSTOMERS: "+C.map(c=>c.n+(c.ph?" "+c.ph:"")).join("; ")];
  if(adm)o.push("","EXPENSES (latest 80):",...X.slice(-80).map(x=>x.d+" | "+x.ds+" | "+x.k+" | "+x.a+" | "+x.pm),"","USERS: "+U.map(u=>u.name+" ("+(u.role||"Administrator")+")").join("; "),"","SUPPLIERS: "+SUP.map(s=>s.n).join("; "),"","ACTIVITY LOG (latest 200):",...LOG.slice(0,200).map(l=>iso(l.t)+" | "+l.u+" | "+l.a+" | "+l.d));
  else o.push("","THIS USER'S ACTIVITY (latest 50):",...LOG.filter(l=>l.uid===SE.id).slice(0,50).map(l=>iso(l.t)+" | "+l.a+" | "+l.d));
  const td=ss.filter(s=>same(s.t,0));
  o.push("","TODAY: "+td.length+" sale(s), "+td.reduce((a,s)=>a+s.tot,0)+" RWF"+(adm?" (all users)":" (this user)"));
  return o.join("\n");
}
function aiLocal(q){
  const s=q.toLowerCase(),rw=/\b(angahe|nagurishije|twagurishije|ibicuruzwa|ideni|munsi|ejo|ukwezi|icyumweru|umuyuza|umukiriya|abakiriya|amafaranga|inyungu|mbwira|nsobanurira|gushira|byashize|ese|nigute|ibyo|uyu|iki|ibi|bihari|igura|ufite|nde|buri|yakoze)\b/.test(s);
  const T=(en,r)=>rw?r:en,adm=can("admin"),ss=adm?S:S.filter(x=>x.by===SE.name);
  let lab=T("today","uyu munsi"),f=x=>same(x.t,0);
  if(/yesterday|\bejo\b/.test(s)){f=x=>same(x.t,1);lab=T("yesterday","ejo")}
  else if(/week|icyumweru/.test(s)){const c=Date.now()-7*864e5;f=x=>x.t>=c;lab=T("the last 7 days","iminsi 7 ishize")}
  else if(/month|ukwezi/.test(s)){const c=Date.now()-30*864e5;f=x=>x.t>=c;lab=T("the last 30 days","iminsi 30 ishize")}
  else if(/\ball\b|byose|igihe cyose/.test(s)){f=()=>true;lab=T("all time","igihe cyose")}
  const R=ss.filter(f),sum=R.reduce((a,x)=>a+x.tot,0);
  const deny=T("Sorry, I can't share that. You can ask about products, stock, prices and your own sales.","Mbabarira, ayo makuru sinyatanga. Ushobora kumbaza ibicuruzwa, stock, ibiciro n'ibyo wagurishije.");
  if(!adm&&/admin|password|owner|nyiri|profit|inyungu|finance|imari|expense|amafaranga yakoreshejwe|igiciro cyo kugura|purchase price/.test(s))return deny;
  if(adm){
    const u=U.find(x=>x.name.toLowerCase().split(" ").some(w=>w.length>2&&s.includes(w)));
    if(u){const mine=S.filter(x=>x.by===u.name&&f(x)),lg=LOG.filter(l=>l.uid===u.id&&f({t:l.t})).slice(0,10);
      return T(`${u.name} (${u.role||"Administrator"}) — ${lab}: ${mine.length} sale(s) worth ${fmt(mine.reduce((a,x)=>a+x.tot,0))}.\n`,`${u.name} (${u.role||"Administrator"}) — ${lab}: yagurishije ${mine.length} ifite agaciro ka ${fmt(mine.reduce((a,x)=>a+x.tot,0))}.\n`)+lg.map(l=>`• ${new Date(l.t).toLocaleTimeString("en-US",{hour:"2-digit",minute:"2-digit"})} ${l.a}${l.d?" — "+l.d:""}`).join("\n")}
    if(/seller|abakozi|umuyuza|each|buri/.test(s)){const m={};R.forEach(x=>{m[x.by||"?"]=(m[x.by||"?"]||0)+x.tot});const e=Object.entries(m);return e.length?T(`Sales by person (${lab}):\n`,`Igurisha rya buri muntu (${lab}):\n`)+e.map(([k,v])=>`• ${k}: ${fmt(v)}`).join("\n"):T("No sales in that period.","Nta byagurishijwe muri iki gihe.")}
  }
  if(/ideni|debt|owe/.test(s)){const d=ss.filter(x=>x.debt>0);return d.length?T(`Open debts (${d.length}), total ${fmt(d.reduce((a,x)=>a+x.debt,0))}:\n`,`Amadeni afunguye (${d.length}), yose hamwe ${fmt(d.reduce((a,x)=>a+x.debt,0))}:\n`)+d.slice(0,10).map(x=>`• ${x.cu}: ${fmt(x.debt)} (${inv(x.id)}${x.due?", "+dday(x.due):""})`).join("\n"):T("There are no open debts.","Nta madeni afunguye ahari.")}
  if(adm&&/profit|inyungu/.test(s)){const pf=R.reduce((a,x)=>a+(x.pf||0),0),ex=X.filter(x=>f({t:new Date(x.d+"T12:00:00").getTime()})).reduce((a,x)=>a+x.a,0);return T(`Gross profit ${lab}: ${fmt(pf)}. Expenses: ${fmt(ex)}. Net: ${fmt(pf-ex)}.`,`Inyungu y'ibanze ${lab}: ${fmt(pf)}. Amafaranga yakoreshejwe: ${fmt(ex)}. Inyungu isigaye: ${fmt(pf-ex)}.`)}
  if(adm&&/expense|amafaranga yakoreshejwe|ibisohoka/.test(s)){const ex=X.filter(x=>f({t:new Date(x.d+"T12:00:00").getTime()}));return T(`Expenses ${lab}: ${fmt(ex.reduce((a,x)=>a+x.a,0))} (${ex.length}).`,`Amafaranga yakoreshejwe ${lab}: ${fmt(ex.reduce((a,x)=>a+x.a,0))} (${ex.length}).`)}
  const pm=P.find(p=>{const n=p.n.toLowerCase();return s.includes(n.split(" (")[0])||(n.match(/\((.*?)\)/)&&s.includes(n.match(/\((.*?)\)/)[1]))});
  if(pm)return T(`${pm.n}: ${pm.s} ${pm.u||"pcs"} in stock, price ${fmt(pm.p)}${(pm.pk||[]).map(k=>`, ${k.n} (${k.q}) ${fmt(k.p)}`).join("")}.`,`${pm.n}: hasigaye ${pm.s} ${pm.u||"pcs"}, igiciro ${fmt(pm.p)}${(pm.pk||[]).map(k=>`, ${k.n} (${k.q}) ${fmt(k.p)}`).join("")}.`);
  if(/stock|gushira|low|byashize|out of|bibura|bihari/.test(s)){const lo=P.filter(p=>p.s<=(p.lw||10));return lo.length?T("Low or out of stock:\n","Ibigiye gushira cyangwa byashize:\n")+lo.map(p=>`• ${p.n}: ${p.s} ${p.u||""}`).join("\n"):T("All products have enough stock.","Ibicuruzwa byose bifite stock ihagije.")}
  if(/top|best|cyane|zigurishwa/.test(s)){const m={};R.forEach(x=>x.items.forEach(l=>{m[l.n]=(m[l.n]||0)+ltot(l)}));const e=Object.entries(m).sort((a,b)=>b[1]-a[1]).slice(0,5);return e.length?T(`Top products (${lab}):\n`,`Ibicuruzwa bigurishwa cyane (${lab}):\n`)+e.map(([k,v],i)=>`${i+1}. ${k}: ${fmt(v)}`).join("\n"):T("No sales in that period.","Nta byagurishijwe muri iki gihe.")}
  if(/sales|nagurishije|twagurishije|gurisha|sold|angahe|revenue|amafaranga/.test(s))return T(`${adm?"Sales":"Your sales"} ${lab}: ${R.length} sale(s), total ${fmt(sum)}.`,`${adm?"Igurisha":"Ibyo wagurishije"} ${lab}: ${R.length}, yose hamwe ${fmt(sum)}.`);
  return T("I can answer about sales, stock, prices, debts and customers. Try: “How much did I sell today?”","Nshobora gusubiza ku igurisha, stock, ibiciro, amadeni n'abakiriya. Gerageza: “Uyu munsi nagurishije angahe?”");
}

/* FINANCE */
let fnP="month";
function pRange(k){
  const n=new Date();n.setHours(0,0,0,0);const t=n.getTime();
  return k==="today"?[t,t+864e5]:k==="week"?[t-6*864e5,Infinity]:k==="month"?[new Date(n.getFullYear(),n.getMonth(),1).getTime(),Infinity]:k==="year"?[new Date(n.getFullYear(),0,1).getTime(),Infinity]:[0,Infinity];
}
const inR=(t,r)=>t>=r[0]&&t<r[1],xt=x=>new Date(x.d+"T12:00:00").getTime();
const PTAB=()=>[["today",L("Today","Uyu munsi")],["week",L("7 days","Iminsi 7")],["month",L("This month","Uku kwezi")],["year",L("This year","Uyu mwaka")],["all",L("All time","Igihe cyose")]];
const bar=(v,m,c)=>`<div class="bar"><i style="width:${m?Math.max(2,Math.round(v/m*100)):0}%;${c?"background:"+c:""}"></i></div>`;
function finData(k){
  const r=pRange(k),ss=S.filter(s=>inR(s.t,r)),ex=X.filter(x=>inR(xt(x),r));
  const rev=ss.reduce((a,s)=>a+s.tot,0),gpf=ss.reduce((a,s)=>a+(s.pf||0),0),exp=ex.reduce((a,x)=>a+x.a,0);
  const pays=[];S.forEach(s=>{const arr=s.pays&&s.pays.length?s.pays:(s.debt>0?[]:[{t:s.t,a:s.tot,m:s.pm}]);arr.forEach(p=>{if(inR(p.t,r))pays.push(p)})});
  const cin=pays.reduce((a,p)=>a+p.a,0),inM={},outM={},cat={},top={};
  pays.forEach(p=>inM[p.m]=(inM[p.m]||0)+p.a);
  ex.forEach(x=>{outM[x.pm]=(outM[x.pm]||0)+x.a;cat[x.k]=(cat[x.k]||0)+x.a});
  ss.forEach(s=>s.items.forEach(l=>{const q=l.q;top[l.n]=(top[l.n]||0)+(ltot(l)-(l.c||0)*q)}));
  return {rev,gpf,exp,net:gpf-exp,cin,inM,outM,cat,top:Object.entries(top).sort((a,b)=>b[1]-a[1]).slice(0,5),n:ss.length};
}
function finance(){
  const d=finData(fnP),debt=S.filter(s=>s.debt>0),dtot=debt.reduce((a,s)=>a+s.debt,0),ov=dues().reduce((a,s)=>a+s.debt,0);
  const inv$=P.reduce((a,p)=>a+p.s*p.c,0),retail=P.reduce((a,p)=>a+p.s*p.p,0);
  const days=[];for(let i=6;i>=0;i--){const t=new Date();t.setHours(0,0,0,0);days.push(new Date(t.getTime()-i*864e5))}
  const dd=days.map(t=>{const a=t.getTime(),r=[a,a+864e5];return {l:t.toLocaleDateString("en-GB",{weekday:"short"}),v:S.filter(s=>inR(s.t,r)).reduce((x,s)=>x+s.tot,0),e:X.filter(x=>inR(xt(x),r)).reduce((x,y)=>x+y.a,0)}});
  const mx=Math.max(1,...dd.map(x=>Math.max(x.v,x.e)));
  const mm=Math.max(1,...Object.values(d.inM),...Object.values(d.outM)),cm=Math.max(1,...Object.values(d.cat));
  page(L("Finance","Imari"),L("Income, expenses and profit at a glance","Ibyinjira, ibisohoka n'inyungu ukireba vuba"),
  `<div class="tabs">${PTAB().map(x=>`<button class="tab ${fnP===x[0]?"on":""}" onclick="fnP='${x[0]}';finance()">${x[1]}</button>`).join("")}</div>
  <div class="g2">${card("🛒",L("Revenue","Ibyinjijwe mu igurisha"),fmt(d.rev),d.n+" "+L("sales","igurisha"))}${card("📈",L("Gross profit","Inyungu y'ibanze"),fmt(d.gpf),"")}${card("🧾",L("Expenses","Ibyakoreshejwe"),fmt(d.exp),"")}${card(d.net>=0?"🪙":"⚠️",L("Net profit","Inyungu isigaye"),`<span class="${d.net>=0?"pos":"neg"}">${fmt(d.net)}</span>`,"")}</div>
  <div class="c"><h3>💵 ${L("Cash flow","Imigendekere y'amafaranga")}</h3><div class="tt"><span>⬇ ${L("Money in","Amafaranga yinjiye")}</span><b class="pos">${fmt(d.cin)}</b></div><div class="tt"><span>⬆ ${L("Money out","Amafaranga yasohotse")}</span><b class="neg">${fmt(d.exp)}</b></div><div class="tt big"><span>${L("Balance","Asigaye")}</span><span>${fmt(d.cin-d.exp)}</span></div></div>
  <div class="c"><h3>📊 ${L("Last 7 days","Iminsi 7 ishize")}</h3><div class="chart">${dd.map(x=>`<div class="cb"><div class="cs"><i style="height:${Math.round(x.v/mx*100)}%;background:var(--g)"></i><i style="height:${Math.round(x.e/mx*100)}%;background:#ff6b6b"></i></div><small>${x.l}</small></div>`).join("")}</div><div class="mu" style="font-size:11.5px;margin-top:6px"><span class="dot" style="background:var(--g)"></span>${L("Sales","Igurisha")} <span class="dot" style="background:#ff6b6b;margin-left:10px"></span>${L("Expenses","Ibyakoreshejwe")}</div></div>
  <div class="g2">${card("💳",L("Debts owed to you","Amadeni bagufitiye"),fmt(dtot),debt.length+" "+L("open","afunguye"))}${card("⏰",L("Overdue debts","Amadeni yarengeje igihe"),fmt(ov),"")}${card("📦",L("Stock value (cost)","Agaciro ka stock (kugura)"),fmt(inv$),"")}${card("🏷️",L("Stock value (retail)","Agaciro ka stock (kugurisha)"),fmt(retail),"")}</div>
  <div class="c"><h3>⬇ ${L("Money in by method","Amafaranga yinjiye ukurikije uburyo")}</h3>${Object.entries(d.inM).sort((a,b)=>b[1]-a[1]).map(([k,v])=>`<div class="tt"><span>${esc(k)}</span><b>${fmt(v)}</b></div>${bar(v,mm)}`).join("")||`<div class="emp">${L("No data","Nta makuru")}</div>`}</div>
  <div class="c"><h3>⬆ ${L("Money out by method","Amafaranga yasohotse ukurikije uburyo")}</h3>${Object.entries(d.outM).sort((a,b)=>b[1]-a[1]).map(([k,v])=>`<div class="tt"><span>${esc(k)}</span><b>${fmt(v)}</b></div>${bar(v,mm,"#ff6b6b")}`).join("")||`<div class="emp">${L("No data","Nta makuru")}</div>`}</div>
  <div class="c"><h3>🧾 ${L("Expenses by category","Ibyakoreshejwe ukurikije icyiciro")}</h3>${Object.entries(d.cat).sort((a,b)=>b[1]-a[1]).map(([k,v])=>`<div class="tt"><span>${EI[k]||"📦"} ${esc(k)}</span><b>${fmt(v)}</b></div>${bar(v,cm,xcol(k))}`).join("")||`<div class="emp">${L("No data","Nta makuru")}</div>`}</div>
  <div class="c"><h3>🏆 ${L("Top products by profit","Ibicuruzwa bifite inyungu nyinshi")}</h3>${d.top.map(([k,v],i)=>`<div class="tt"><span>${i+1}. ${esc(k)}</span><b class="pos">${fmt(v)}</b></div>`).join("")||`<div class="emp">${L("No data","Nta makuru")}</div>`}</div>
  <button class="btn o" onclick="go('#/reports')">📊 ${L("Open Reports","Fungura Raporo")}</button>`,{back:"#/more",nav:"finance"});
}

/* REPORTS */
let rpT="sales",rpP="month";
function repData(){
  const r=pRange(rpP),ss=S.filter(s=>inR(s.t,r)),ex=X.filter(x=>inR(xt(x),r)),dt=t=>ymd(new Date(t));
  const R={};
  R.sales={h:[L("Date","Itariki"),L("Invoice","Invoice"),L("Customer","Umukiriya"),L("Seller","Umuyuza"),L("Total","Igiteranyo"),L("Paid","Yishyuwe"),L("Debt","Ideni")],n:[4,5,6],rows:ss.map(s=>[dt(s.t),inv(s.id),s.cu,s.by||"-",s.tot,s.paid!=null?s.paid:s.tot,s.debt||0])};
  const pm={};ss.forEach(s=>s.items.forEach(l=>{const o=pm[l.n]||(pm[l.n]={q:0,r:0,p:0});o.q+=l.q*(l.uq||1);o.r+=ltot(l);o.p+=ltot(l)-(l.c||0)*l.q}));
  R.vat={h:[L("Date","Itariki"),L("Invoice","Invoice"),L("Customer","Umukiriya"),L("Amount excl. VAT","Agaciro mbere ya VAT"),L("VAT 18%","VAT 18%"),L("Total incl. VAT","Igiteranyo harimo VAT")],n:[3,4,5],rows:ss.map(s=>{const v=Math.round(s.tot*18/118);return [dt(s.t),inv(s.id),s.cu,s.tot-v,v,s.tot]})};
  R.products={h:[L("Product","Igicuruzwa"),L("Pieces sold","Pieces zagurishijwe"),L("Revenue","Ayinjiye"),L("Profit","Inyungu"),L("Stock now","Stock isigaye")],n:[1,2,3,4],rows:Object.entries(pm).sort((a,b)=>b[1].r-a[1].r).map(([k,o])=>[k,+o.q.toFixed(2),o.r,o.p,(P.find(p=>p.n===k)||{}).s??"-"])};
  R.expenses={h:[L("Date","Itariki"),L("Description","Ibisobanuro"),L("Category","Icyiciro"),L("Method","Uburyo"),L("Amount","Amafaranga")],n:[4],rows:ex.sort((a,b)=>b.d.localeCompare(a.d)).map(x=>[x.d,x.ds,x.k,x.pm,x.a])};
  const rev=ss.reduce((a,s)=>a+s.tot,0),gpf=ss.reduce((a,s)=>a+(s.pf||0),0),exp=ex.reduce((a,x)=>a+x.a,0),cg={};ex.forEach(x=>cg[x.k]=(cg[x.k]||0)+x.a);
  R.pnl={h:[L("Item","Ikintu"),L("Amount","Amafaranga")],n:[1],rows:[[L("Revenue","Ayinjiye mu igurisha"),rev],[L("Cost of goods sold","Igiciro cy'ibyagurishijwe"),rev-gpf],[L("Gross profit","Inyungu y'ibanze"),gpf],...Object.entries(cg).map(([k,v])=>[L("Expense: ","Ikoreshwa: ")+k,v]),[L("Total expenses","Ibyakoreshejwe byose"),exp],[L("NET PROFIT","INYUNGU ISIGAYE"),gpf-exp]]};
  R.debts={h:[L("Customer","Umukiriya"),L("Invoice","Invoice"),L("Total","Igiteranyo"),L("Paid","Yishyuwe"),L("Debt","Ideni"),L("Due","Igihe"),L("Status","Imiterere")],n:[2,3,4],rows:S.filter(s=>s.debt>0).map(s=>[s.cu,inv(s.id),s.tot,s.paid||0,s.debt,s.due?dt(s.due):"-",s.due&&s.due<=Date.now()?L("OVERDUE","YARARENGEYE"):L("Open","Rifunguye")])};
  const sm={};ss.forEach(s=>{const o=sm[s.by||"-"]||(sm[s.by||"-"]={n:0,t:0,p:0});o.n++;o.t+=s.tot;o.p+=s.pf||0});
  R.staff={h:[L("Seller","Umuyuza"),L("Sales","Igurisha"),L("Total","Igiteranyo"),L("Profit","Inyungu")],n:[1,2,3],rows:Object.entries(sm).sort((a,b)=>b[1].t-a[1].t).map(([k,o])=>[k,o.n,o.t,o.p])};
  return R;
}
function reports(){
  const T=[["sales",L("Sales","Igurisha")],["vat",L("VAT","VAT")],["products",L("Products","Ibicuruzwa")],["expenses",L("Expenses","Ibyakoreshejwe")],["pnl",L("Profit & Loss","Inyungu n'igihombo")],["debts",L("Debts","Amadeni")],["staff",L("Staff","Abakozi")]];
  page(L("Reports","Raporo"),L("Pick a report and period, then print or export","Hitamo raporo n'igihe, hanyuma uyisohore cyangwa uyikuremo"),
  `<div class="tabs no-p">${T.map(x=>`<button class="tab ${rpT===x[0]?"on":""}" onclick="rpT='${x[0]}';reports()">${x[1]}</button>`).join("")}</div>
  <select class="no-p" onchange="rpP=this.value;reports()">${PTAB().map(x=>`<option value="${x[0]}" ${rpP===x[0]?"selected":""}>${x[1]}</option>`).join("")}</select>
  <button class="btn" onclick="reportModal()">＋ ${L("Add report","Ongeramo raporo")}</button>
  <div class="c" id="rpb"></div>
  <div class="g2 no-p"><button class="btn o" onclick="printRcp()">🖨 ${L("Print / PDF","Sohora / PDF")}</button><button class="btn o" onclick="repCsv()">⬇ CSV</button></div>`,{back:"#/more",nav:"reports"});
  const R=repData()[rpT],f=(v,i)=>R.n.includes(i)&&typeof v==="number"?(rpT==="products"&&i===1?v:rpT==="staff"&&i===1?v:fmt(v)):esc(v);
  const tot=R.rows.length&&rpT!=="pnl"?R.h.map((_,i)=>R.n.includes(i)&&!(rpT==="products"&&i===4)?R.rows.reduce((a,r)=>a+(+r[i]||0),0):""):null;
  $("rpb").innerHTML=`<h3>📊 ${esc(T.find(x=>x[0]===rpT)[1])} • ${esc(PTAB().find(x=>x[0]===rpP)[1])}</h3><div style="overflow-x:auto"><table class="rt"><tr>${R.h.map((x,i)=>`<th class="${R.n.includes(i)?"n":""}">${esc(x)}</th>`).join("")}</tr>${R.rows.map(r=>`<tr>${r.map((v,i)=>`<td class="${R.n.includes(i)?"n":""}">${f(v,i)}</td>`).join("")}</tr>`).join("")||`<tr><td colspan="${R.h.length}" class="mu">${L("No data for this period","Nta makuru muri iki gihe")}</td></tr>`}${tot?`<tr style="font-weight:700">${tot.map((v,i)=>`<td class="${R.n.includes(i)?"n":""}">${i===0?L("TOTAL","IGITERANYO"):v===""?"":(rpT==="staff"&&i===1)||(rpT==="products"&&i===1)?v:fmt(v)}</td>`).join("")}</tr>`:""}</table></div><div class="mu" style="font-size:11.5px;margin-top:8px">${esc(SE.biz)} • ${new Date().toLocaleString("en-GB")}</div>`;
}
function repCsv(){const R=repData()[rpT];saveFile(`report-${rpT}-${rpP}.csv`,csvOf(R.h,R.rows))}

/* INVENTORY */
let ivQ="",ivT="all",ivS="name",ivC="",ivPg=1,ivSel=new Set(),smPre="";
W("sm",null,()=>{if(smPre&&$("smt"))$("smt").value=smPre;smPre=""});
function inventory(){
  const tv=P.reduce((a,p)=>a+p.s*p.c,0),lo=P.filter(p=>st(p)==="low").length,out=P.filter(p=>st(p)==="out").length;
  page(L("Inventory Management","Imicungire y'ububiko"),L("Track your stock and avoid running out","Kurikirana stock yawe wirinde ko ishira"),
  `<div class="g2">${card("📦",L("Total Products","Ibicuruzwa byose"),P.length,L("Active: ","Bikora: ")+P.filter(p=>p.act!==false).length)}${card("💰",L("Total Stock Value","Agaciro ka stock"),fmt(tv),"")}${card("⚠️",L("Low Stock Items","Bigiye gushira"),lo,"")}${card("🚫",L("Out of Stock","Byashize"),out,"")}</div>
  <div class="tabs" id="ivt"></div>
  <input id="ivq" placeholder="${L("🔍 Search by product name or code…","🔍 Shakisha ku izina cyangwa code y'igicuruzwa…")}" oninput="ivQ=this.value;ivPg=1;ivR()">
  <div class="g2" style="margin-bottom:0"><select onchange="ivS=this.value;ivR()">${[["name",L("Sort: Name (A-Z)","Tondeka: Izina (A-Z)")],["stock",L("Sort: Stock (low-high)","Tondeka: Stock (make-nyinshi)")],["stockd",L("Sort: Stock (high-low)","Tondeka: Stock (nyinshi-make)")],["value",L("Sort: Value","Tondeka: Agaciro")]].map(x=>`<option value="${x[0]}" ${ivS===x[0]?"selected":""}>${x[1]}</option>`).join("")}</select>
  <select onchange="ivC=this.value;ivPg=1;ivR()"><option value="">${L("All categories","Ibyiciro byose")}</option>${cats().map(k=>`<option ${k===ivC?"selected":""}>${esc(k)}</option>`).join("")}</select></div>
  <div id="ivb"></div><div class="c" style="padding:6px 10px"><div id="ivl"></div></div><div id="ivp"></div>`,{back:"#/more",nav:"inventory",act:`<button class="hb" onclick="ivAdd()">＋ ${L("Add Stock","Ongeramo stock")}</button>`});
  $("ivq").value=ivQ;ivR();
}
function ivF(){
  const q=ivQ.toLowerCase();
  let R=P.filter(p=>(ivT==="all"||st(p)===ivT)&&(!ivC||p.k===ivC)&&(!q||(p.n+code(p)+p.k).toLowerCase().includes(q)));
  R.sort((a,b)=>ivS==="stock"?a.s-b.s:ivS==="stockd"?b.s-a.s:ivS==="value"?b.s*b.c-a.s*a.c:a.n.localeCompare(b.n));
  return R;
}
function ivR(){
  const c=k=>P.filter(p=>st(p)===k).length;
  $("ivt").innerHTML=[["all",L("All Products","Byose"),P.length],["in",L("In Stock","Bihari"),c("in")],["low",L("Low Stock","Bigiye gushira"),c("low")],["out",L("Out of Stock","Byashize"),c("out")]].map(t=>`<button class="tab ${ivT===t[0]?"on":""}" onclick="ivT='${t[0]}';ivPg=1;ivR()">${t[1]} (${t[2]})</button>`).join("");
  const R=ivF(),PS=10,pgs=Math.max(1,Math.ceil(R.length/PS));if(ivPg>pgs)ivPg=pgs;
  const A=R.slice((ivPg-1)*PS,ivPg*PS),allSel=A.length&&A.every(p=>ivSel.has(p.id));
  $("ivb").innerHTML=`<div class="tt" style="align-items:center;padding:8px 2px"><label class="ck" style="margin:0"><input type="checkbox" ${allSel?"checked":""} onchange="ivAll(this.checked)"> ${L("Select all","Hitamo byose")}</label>${ivSel.size?`<span><b>${ivSel.size}</b> ${L("selected","byatoranyijwe")} <button class="ib" onclick="ivCopy()">📋 ${L("Copy","Koporora")}</button> <button class="ib" onclick="ivSel.clear();ivR()">✖</button></span>`:""}</div>`;
  $("ivl").innerHTML=A.map(p=>`<div class="row" style="cursor:default"><input type="checkbox" ${ivSel.has(p.id)?"checked":""} onchange="ivK(${p.id},this.checked)" style="width:20px;height:20px;margin:0;padding:0;flex:none"><div class="em" onclick="go('#/product/${p.id}')" style="cursor:pointer">${pim(p)}</div><div class="m" onclick="go('#/product/${p.id}')" style="cursor:pointer"><b>${esc(p.n)}</b><small>${esc(code(p))} • ${esc(p.k)} • ${fmt(p.p)}</small></div><div class="r"><b>${p.s}</b><br>${badge(p)}</div><button class="ib" style="padding:6px 8px" onclick="gEdit(${p.id},'edit')">✏️</button><button class="ib" style="padding:6px 8px" onclick="ivMenu(${p.id})">⋯</button></div>`).join("")||`<div class="emp">${L("No products found.","Nta gicuruzwa kibonetse.")}</div>`;
  $("ivp").innerHTML=`<div class="tt mu" style="margin-top:8px"><span>${L("Showing","Hagaragara")} ${R.length?(ivPg-1)*PS+1:0}–${(ivPg-1)*PS+A.length} / ${R.length}</span></div>`+(pgs>1?`<div class="tabs">${Array.from({length:pgs},(_,i)=>`<button class="tab ${i+1===ivPg?"on":""}" onclick="ivPg=${i+1};ivR()">${i+1}</button>`).join("")}</div>`:"");
}
function ivK(id,on){on?ivSel.add(id):ivSel.delete(id);ivR()}
function ivAll(on){const q=ivF().slice((ivPg-1)*10,ivPg*10);q.forEach(p=>on?ivSel.add(p.id):ivSel.delete(p.id));ivR()}
function ivCopy(){cpTxt(P.filter(p=>ivSel.has(p.id)).map(p=>`${p.n} (${code(p)}): ${p.s}`).join("\n"))}
function ivMenu(id){
  const p=gp(id);
  modal(`<h3>${esc(p.n)}</h3><button class="btn" onclick="closeM();go('#/product/${id}')">👁 ${L("View details","Reba ibisobanuro")}</button><button class="btn o" onclick="closeM();smPre='in';gEdit(${id},'sm')">⬇ ${L("Stock In","Ongeramo stock")}</button><button class="btn o" onclick="closeM();smPre='out';gEdit(${id},'sm')">⬆ ${L("Stock Out","Kuramo stock")}</button><button class="btn o" onclick="closeM();gEdit(${id},'edit')">✏️ ${L("Edit","Hindura")}</button><button class="btn o" onclick="closeM()">${L("Close","Funga")}</button>`);
}
function ivAdd(){
  modal(`<h3>＋ ${L("Add Stock","Ongeramo stock")}</h3><input id="ivas" placeholder="${L("🔍 Search product…","🔍 Shakisha igicuruzwa…")}" oninput="ivAl()"><div id="ival" style="max-height:50vh;overflow:auto"></div>`);ivAl();
}
function ivAl(){
  const q=($("ivas")||{value:""}).value.toLowerCase();
  $("ival").innerHTML=P.filter(p=>!q||(p.n+code(p)).toLowerCase().includes(q)).map(p=>`<div class="row" onclick="closeM();smPre='in';gEdit(${p.id},'sm')"><div class="em">${pim(p)}</div><div class="m"><b>${esc(p.n)}</b><small>${esc(code(p))} • ${L("Stock","Stock")} ${p.s}</small></div></div>`).join("")||`<div class="emp">${L("No products found.","Nta gicuruzwa kibonetse.")}</div>`;
}

/* FILES & PHOTOS (IndexedDB) */
const idb=()=>new Promise((res,rej)=>{const r=indexedDB.open("bizz_files",1);r.onupgradeneeded=()=>r.result.createObjectStore("f");r.onsuccess=()=>res(r.result);r.onerror=()=>rej(r.error)});
const idbP=async(m,k,v)=>{const d=await idb();return new Promise((res,rej)=>{const t=d.transaction("f",m==="get"?"readonly":"readwrite"),s=t.objectStore("f"),q=m==="get"?s.get(k):m==="put"?s.put(v,k):s.delete(k);q.onsuccess=()=>res(q.result);q.onerror=()=>rej(q.error)})};
let flQ="",flT="all";
const fCanV=f=>can("admin")||f.all||(f.v||[]).includes(SE.id)||(f.e||[]).includes(SE.id)||f.by===SE.id,
fCanE=f=>can("admin")||(f.e||[]).includes(SE.id),
fKB=n=>n>1048576?(n/1048576).toFixed(1)+" MB":Math.max(1,Math.round(n/1024))+" KB";
let FOLD=ld("bizz_folders",[]),flTab="files",flFo="",flAll=false,flFa=false,FSET=Object.assign({share:true,compress:true,backup:false,limit:100},ld("bizz_fset",{}));
const fsSave=()=>{sv("bizz_fset",FSET);logA("Settings changed","Files & Photos")};
const FT=f=>{
  const t=f.type||"",e=(f.n||"").toLowerCase().split(".").pop();
  if(/^image\//.test(t))return {k:"img",l:L("Photo","Ifoto"),f:"pictures"};
  if(/^video\//.test(t))return {k:"vid",l:"Video",f:"videos",i:"▶",c:"#1c2a4a"};
  if(/^audio\//.test(t))return {k:"aud",l:L("Audio","Amajwi"),f:"music",i:"♪",c:"#e8841a"};
  if(/pdf/.test(t)||e==="pdf")return {k:"pdf",l:L("Document","Inyandiko"),f:"documents",i:"PDF",c:"#e5483f"};
  if(/sheet|excel/.test(t)||["xls","xlsx","csv"].includes(e))return {k:"xls",l:L("Spreadsheet","Imbonerahamwe"),f:"documents",i:"X",c:"#1f9d55"};
  if(/word|msword/.test(t)||["doc","docx","txt","rtf"].includes(e))return {k:"doc",l:L("Document","Inyandiko"),f:"documents",i:"W",c:"#2f6fe0"};
  if(/presentation|powerpoint/.test(t)||["ppt","pptx"].includes(e))return {k:"ppt",l:L("Presentation","Ikiganiro"),f:"documents",i:"P",c:"#d6532b"};
  if(/zip|rar|7z|tar|gzip/.test(t)||["zip","rar","7z","tar","gz"].includes(e))return {k:"zip",l:L("Archive","Ububiko bwa dosiye"),f:"archives",i:"🗜",c:"#e0b100"};
  return {k:"oth",l:L("File","Dosiye"),f:"downloads",i:"📄",c:"#4b5f57"};
};
const fKey=f=>f.fid?"c"+f.fid:FT(f).f,
SYSF=()=>[["documents","📄",L("Documents","Inyandiko"),"#2f6fe0"],["downloads","⬇️",L("Downloads","Ibikuruwe"),"#1f9d55"],["pictures","🖼️",L("Pictures","Amashusho"),"#8a4fe0"],["videos","🎬","Videos","#e5483f"],["music","🎵",L("Music","Umuziki"),"#e8841a"],["archives","🗜️",L("Archives","Ububiko"),"#e0b100"]],
allF=()=>[...SYSF(),...FOLD.map(x=>["c"+x.id,"📁",x.n,"#0f8a8a"])],
fWhen=t=>{const d=new Date(t),tm=d.toLocaleTimeString("en-US",{hour:"2-digit",minute:"2-digit",hour12:false});return same(t,0)?L("Today","Uyu munsi")+" "+tm:same(t,1)?L("Yesterday","Ejo")+" "+tm:d.toLocaleDateString("en-GB",{day:"2-digit",month:"short",year:"numeric"})},
fSz=n=>n>=1073741824?(n/1073741824).toFixed(1)+" GB":n>=1048576?(n/1048576).toFixed(1)+" MB":Math.max(1,Math.round(n/1024))+" KB",
fTile=f=>{const t=FT(f);return t.k==="img"?`<div class="ft" data-fid="${f.id}" style="background:#26453a" onclick="flView(${f.id})">🖼️</div>`:`<div class="ft" data-fid="${f.id}" style="background:${t.c}" onclick="flView(${f.id})">${t.i}</div>`};
function filesPage(){
  const adm=can("admin"),V=FL.filter(fCanV),fo=flFo?allF().find(x=>x[0]===flFo):null;
  if(flFo&&!fo)flFo="";
  const act=[];
  if(adm){
    act.push(`<label class="ac-up"><i>⬆</i><b>${L("Upload","Shyiraho")}</b><small>${L("Files or photos","Dosiye cyangwa amafoto")}</small><input type="file" multiple style="display:none" onchange="flUp(this)"></label>`);
    act.push(`<div class="ac-new" onclick="flNew()"><i>📁</i><b>${L("New Folder","Ububiko bushya")}</b><small>${L("Create folder","Kora ububiko")}</small></div>`);
    act.push(`<label class="ac-cam"><i>📷</i><b>${L("Open Camera","Fungura Camera")}</b><small>${L("Take a photo","Fata ifoto")}</small><input type="file" accept="image/*" capture="environment" style="display:none" onchange="flUp(this)"></label>`);
  }
  act.push(`<div class="ac-gal" onclick="flTab='photos';flFo='';filesPage()"><i>🖼️</i><b>${L("Gallery","Amafoto")}</b><small>${L("View all photos","Reba amafoto yose")}</small></div>`);
  if(flTab==="set"&&adm){
    const tg=k=>`<button class="tg ${FSET[k]?"on":""}" onclick="FSET.${k}=!FSET.${k};fsSave();filesPage()" aria-label="${k}"></button>`;
    const row=(ic,t,d,r)=>`<div class="sg"><i>${ic}</i><div class="m"><b>${t}</b><small>${d}</small></div>${r}</div>`;
    page(L("Files & Photos","Dosiye n'amafoto"),L("File settings","Igenamiterere ry'dosiye"),
    `<div class="c" style="padding:4px 12px">${row("🔗",L("Allow public sharing","Emerera gusangiza ku mugaragaro"),L("Anyone with a link can open a shared file","Umuntu ufite link yabona dosiye"),tg("share"))}${row("🗜️",L("Compress images","Gabanya ubunini bw'amafoto"),L("Make photos smaller when uploaded","Gabanya amafoto mu gushyirwaho"),tg("compress"))}${row("☁️",L("Auto backup","Kubika mu buryo bwikora"),L("Back up files automatically","Bika dosiye mu buryo bwikora"),tg("backup"))}</div>
    <div class="c"><h3>📏 ${L("File size limit","Ingano ntarengwa ya dosiye")}</h3><div class="opt" style="grid-template-columns:repeat(4,1fr)">${[25,50,100,250].map(n=>`<button class="op ${FSET.limit===n?"on":""}" onclick="FSET.limit=${n};fsSave();filesPage()">${n} MB</button>`).join("")}</div><p class="mu" style="font-size:11.5px;margin-top:8px">${L("Files bigger than this are refused on upload.","Dosiye ziruta ibi ntizemererwa gushyirwaho.")}</p></div>`,{back:"#/more",nav:"files"});
    return;
  }
  const tot=FL.reduce((a,f)=>a+f.size,0);
  const head=fo?`<div class="sech" style="margin-top:0"><b>${fo[1]} ${esc(fo[2])}</b><span><a onclick="flFo='';filesPage()">← ${L("All folders","Ububiko bwose")}</a>${fo[0][0]==="c"&&adm?` <a style="color:var(--rd);margin-left:10px" onclick="flFdel('${fo[0]}')">🗑</a>`:""}</span></div>`:"";
  page(L("Files & Photos","Dosiye n'amafoto"),L("Access and manage your files and images","Reba kandi ucunge dosiye n'amafoto yawe"),
  `<div class="opt" style="grid-template-columns:${adm?"1fr 1fr 1fr":"1fr 1fr"};margin-bottom:12px"><button class="op ${flTab==="files"?"on":""}" style="padding:13px" onclick="flTab='files';filesPage()">📁 ${L("Files","Dosiye")}</button><button class="op ${flTab==="photos"?"on":""}" style="padding:13px" onclick="flTab='photos';flFo='';filesPage()">🖼️ ${L("Photos","Amafoto")}</button>${adm?`<button class="op ${flTab==="set"?"on":""}" style="padding:13px" onclick="flTab='set';filesPage()">⚙️ ${L("Settings","Igenamiterere")}</button>`:""}</div>
  <div class="fa">${act.join("")}</div>
  <div class="stc"><div class="sr" id="sr" style="background:conic-gradient(#00e070 2%,#17463a 0)"><div id="stp">0%</div></div><div class="sx"><small>${L("Storage Used","Ububiko bukoreshwa")}</small><b id="stu">${fSz(tot)}</b><small id="stl"></small></div></div>
  <input id="flq" placeholder="${L("🔍 Search files…","🔍 Shakisha dosiye…")}" oninput="flQ=this.value;flR()">
  <div id="flb"></div>
  <p class="mu" style="font-size:11.5px;line-height:1.4">${L("Files are stored on this device (browser). They are not included in the data backup.","Dosiye zibikwa kuri iki gikoresho (browser). Ntizijya muri backup y'amakuru.")}</p>`,{back:"#/more",nav:"files"});
  $("flq").value=flQ;flR();
  try{navigator.storage.estimate().then(e=>{if(!$("stu"))return;const q=e.quota||0,pc=q?Math.min(100,tot/q*100):0;$("stl").textContent=q?L("of ","muri ")+fSz(q):"";$("stp").textContent=(pc<1?pc.toFixed(1):Math.round(pc))+"%";$("sr").style.background=`conic-gradient(#00e070 ${Math.max(1,pc)}%,#17463a 0)`})}catch(e){}
}
function flR(){
  const adm=can("admin"),q=flQ.toLowerCase(),V=FL.filter(fCanV);
  const match=f=>!q||f.n.toLowerCase().includes(q);
  let h="";
  if(flTab==="photos"){
    const R=V.filter(f=>/^image\//.test(f.type)&&match(f)).sort((a,b)=>b.t-a.t);
    h=`<div class="sech"><b>🖼️ ${L("All photos","Amafoto yose")} (${R.length})</b></div>`+(R.length?`<div class="pg">${R.map(f=>`<div class="pt" data-fid="${f.id}" onclick="flView(${f.id})">🖼️</div>`).join("")}</div>`:`<div class="emp">${L("No photos yet.","Nta mafoto ahari.")}</div>`);
    $("flb").innerHTML=h;flThumbs(R);return;
  }
  let R;
  if(flFo){R=V.filter(f=>fKey(f)===flFo&&match(f)).sort((a,b)=>b.t-a.t)}
  else{
    const F=allF(),show=flFa?F:F.slice(0,6);
    h=`<div class="sech"><b>${L("Folders","Ububiko")}</b>${F.length>6?`<a onclick="flFa=!flFa;flR()">${flFa?L("Show less","Gabanya"):L("View All","Reba byose")} ›</a>`:""}</div><div class="fo">${show.map(x=>`<div onclick="flFo='${x[0]}';filesPage()"><i style="background:${x[3]}">${x[1]}</i><div class="m"><b>${esc(x[2])}</b><small>${V.filter(f=>fKey(f)===x[0]).length} ${L("items","ibintu")}</small></div><span class="chv">›</span></div>`).join("")}</div>`;
    R=V.filter(match).sort((a,b)=>b.t-a.t);
    if(!flAll&&!q)R=R.slice(0,6);
    h+=`<div class="sech"><b>🕒 ${L("Recent Files","Dosiye ziheruka")}</b>${V.length>6&&!q?`<a onclick="flAll=!flAll;flR()">${flAll?L("Show less","Gabanya"):L("View All","Reba byose")} ›</a>`:""}</div>`;
  }
  h+=`<div class="c" style="padding:2px 10px">${R.map(f=>`<div class="row" style="cursor:default">${fTile(f)}<div class="m" onclick="flView(${f.id})" style="cursor:pointer"><b>${esc(f.n)}</b><small>${FT(f).l} • ${fSz(f.size)} • ${fWhen(f.t)}</small>${adm?`<small>${f.all?"👥 "+L("Everyone can view","Bose barareba"):((f.v||[]).length+(f.e||[]).length)?"👁 "+(f.v||[]).length+" • ✏️ "+(f.e||[]).length:"🔒 "+L("Private","Bwite")}</small>`:`<small>${fCanE(f)?"✏️ "+L("You can edit","Ushobora guhindura"):"👁 "+L("View only","Kureba gusa")}</small>`}</div><button class="ib" style="border:0;font-size:20px;padding:4px 8px" onclick="flMenu(${f.id})">☰</button></div>`).join("")||`<div class="emp">${L("No files here yet.","Nta dosiye zihari.")}</div>`}</div>`;
  $("flb").innerHTML=h;flThumbs(R);
}
function flThumbs(R){
  R.filter(f=>/^image\//.test(f.type)).forEach(async f=>{try{const b=await idbP("get",String(f.id));if(!b)return;const u=URL.createObjectURL(b);document.querySelectorAll(`[data-fid="${f.id}"]`).forEach(e=>{e.innerHTML=`<img src="${u}" alt="">`})}catch(x){}});
}
function flMenu(id){
  const f=FL.find(x=>x.id===id);if(!f||!fCanV(f))return;
  modal(`<h3>${esc(f.n)}</h3><button class="btn" onclick="closeM();flView(${id})">👁 ${L("Open","Fungura")}</button><button class="btn o" onclick="closeM();flDl(${id})">⬇ ${L("Download","Kuramo")}</button>${fCanE(f)?`<button class="btn o" onclick="flRen(${id})">✏️ ${L("Rename","Hindura izina")}</button>`:""}${can("admin")?`<button class="btn o" onclick="flMove(${id})">📁 ${L("Move to folder","Imurira mu bubiko")}</button><button class="btn o" onclick="flAcc(${id})">🔒 ${L("Access","Uburenganzira")}</button>`:""}${fCanE(f)?`<button class="btn o d" onclick="closeM();flDel(${id})">🗑 ${L("Delete","Siba")}</button>`:""}<button class="btn o" onclick="closeM()">${L("Close","Funga")}</button>`);
}
async function flDl(id){const f=FL.find(x=>x.id===id);if(!f)return;let b=null;try{b=await idbP("get",String(id))}catch(e){}if(!b)return toast(L("File not found on this device","Dosiye ntiboneka kuri iki gikoresho"));saveFile(f.n,b)}
function flNew(){
  if(!can("admin"))return;
  modal(`<h3>📁 ${L("New Folder","Ububiko bushya")}</h3><input id="fnn" placeholder="${L("Folder name","Izina ry'ububiko")}"><div class="g2"><button class="btn o" onclick="closeM()">${L("Cancel","Reka")}</button><button class="btn" onclick="flNewS()">${L("Create","Kora")}</button></div>`);
}
function flNewS(){
  const n=$("fnn").value.trim();if(n.length<2)return toast(L("Enter a folder name","Andika izina ry'ububiko"));
  if(allF().some(x=>String(x[2]).toLowerCase()===n.toLowerCase()))return toast(L("This folder already exists","Ubu bubiko busanzweho"));
  const id=FOLD.reduce((m,x)=>Math.max(m,x.id),0)+1;FOLD.push({id,n});sv("bizz_folders",FOLD);logA("Folder created",n);closeM();toast(L("Saved ✔","Byabitswe ✔"));filesPage();
}
function flFdel(k){
  const x=FOLD.find(f=>"c"+f.id===k);if(!x)return;
  if(FL.some(f=>f.fid===x.id))return toast(L("Move or delete the files in this folder first","Banza wimure cyangwa usibe dosiye ziri muri ubu bubiko"));
  ask(L("Delete folder","Siba ububiko"),L(`Delete ${esc(x.n)}?`,`Uremeza gusiba ${esc(x.n)}?`),()=>{FOLD=FOLD.filter(f=>f!==x);sv("bizz_folders",FOLD);flFo="";filesPage()});
}
function flMove(id){
  const f=FL.find(x=>x.id===id);if(!f||!can("admin"))return;
  modal(`<h3>📁 ${L("Move to folder","Imurira mu bubiko")}</h3><p class="mu" style="margin-bottom:8px">${esc(f.n)}</p><select id="fmv"><option value="0">${L("Automatic (by file type)","Ku buryo bwikora (ukurikije ubwoko)")}</option>${FOLD.map(x=>`<option value="${x.id}" ${f.fid===x.id?"selected":""}>${esc(x.n)}</option>`).join("")}</select><div class="g2"><button class="btn o" onclick="closeM()">${L("Cancel","Reka")}</button><button class="btn" onclick="flMoveS(${id})">${L("Save","Bika")}</button></div>`);
}
function flMoveS(id){const f=FL.find(x=>x.id===id);f.fid=+$("fmv").value||0;sv("bizz_files",FL);logA("File moved",f.n);closeM();toast(L("Saved ✔","Byabitswe ✔"));filesPage()}
async function flUp(inp){
  const fs=[...inp.files];let ok=0;
  for(const f of fs){
    if(f.size>FSET.limit*1048576){toast(L("File too big (max ","Dosiye ni nini cyane (max ")+FSET.limit+" MB): "+f.name);continue}
    const id=Date.now()+ok,fid=flFo&&flFo[0]==="c"?+flFo.slice(1):0;
    let blob=f;if(FSET.compress&&/^image\//.test(f.type)){try{blob=await new Promise((res,rej)=>{const r=new FileReader();r.onload=()=>{const im=new Image();im.onload=()=>{const s=Math.min(1,1600/Math.max(im.width,im.height)),c=document.createElement("canvas");c.width=Math.round(im.width*s);c.height=Math.round(im.height*s);c.getContext("2d").drawImage(im,0,0,c.width,c.height);c.toBlob(b=>b?res(b):rej(),"image/jpeg",.8)};im.onerror=rej;im.src=r.result};r.onerror=rej;r.readAsDataURL(f)})}catch(e){blob=f}}
    try{await idbP("put",String(id),blob);FL.unshift({id,n:f.name,type:blob.type||f.type||"application/octet-stream",size:blob.size,t:Date.now(),by:SE.id,byN:SE.name,v:[],e:[],all:false,fid});ok++;logA("File uploaded",f.name)}catch(e){toast(L("Could not store the file","Ntibishobotse kubika dosiye"))}
  }
  sv("bizz_files",FL);if(ok)toast(L("Saved ✔","Byabitswe ✔"));filesPage();
}
async function flView(id){
  const f=FL.find(x=>x.id===id);if(!f||!fCanV(f))return;
  let b=null;try{b=await idbP("get",String(id))}catch(e){}
  if(!b)return toast(L("File not found on this device","Dosiye ntiboneka kuri iki gikoresho"));
  const u=URL.createObjectURL(b),t=f.type||"";
  let body;
  if(/^image\//.test(t))body=`<img src="${u}" alt="" style="width:100%;border-radius:12px;margin-bottom:10px">`;
  else if(/^video\//.test(t))body=`<video src="${u}" controls playsinline style="width:100%;border-radius:12px;margin-bottom:10px;background:#000;max-height:50vh"></video>`;
  else if(/^audio\//.test(t))body=`<audio src="${u}" controls style="width:100%;margin-bottom:10px"></audio>`;
  else if(/pdf/.test(t))body=`<iframe src="${u}" style="width:100%;height:50vh;border:0;border-radius:12px;margin-bottom:10px;background:#fff"></iframe>`;
  else if(/^text\//.test(t)||/json|csv|xml/.test(t)){const tx=await b.text();body=`<pre style="white-space:pre-wrap;max-height:45vh;overflow:auto;background:var(--fd);padding:10px;border-radius:10px;font-size:12px;margin-bottom:10px">${esc(tx.slice(0,20000))}</pre>`}
  else body=`<div class="c" style="text-align:center;margin-bottom:10px"><div style="font-size:42px">📄</div><p class="mu" style="font-size:12.5px">${fKB(f.size)} • ${esc(t||"file")}</p><p class="mu" style="font-size:12px">${L("This type cannot be previewed here. Use Download.","Ubu bwoko ntibushobora kurebwa hano. Koresha Download.")}</p></div>`;
  modal(`<h3>${esc(f.n)}</h3>${body}<button class="btn" id="fdl">⬇ ${L("Download","Kuramo")}</button><button class="btn o" onclick="closeM()">${L("Close","Funga")}</button>`);
  $("fdl").onclick=()=>saveFile(f.n,b);
}
function flRen(id){
  const f=FL.find(x=>x.id===id);if(!f||!fCanE(f))return;
  modal(`<h3>✏️ ${L("Rename","Hindura izina")}</h3><input id="frn" value="${esc(f.n)}"><div class="g2"><button class="btn o" onclick="closeM()">${L("Cancel","Reka")}</button><button class="btn" onclick="flRenS(${id})">${L("Save","Bika")}</button></div>`);
}
function flRenS(id){const f=FL.find(x=>x.id===id),n=$("frn").value.trim();if(!n)return toast(L("Enter a name","Andika izina"));logA("File renamed",f.n+" → "+n);f.n=n;sv("bizz_files",FL);closeM();flR()}
function flDel(id){
  const f=FL.find(x=>x.id===id);if(!f||!fCanE(f))return;
  ask(L("Delete file","Siba dosiye"),L(`Delete ${esc(f.n)}? This cannot be undone.`,`Uremeza gusiba ${esc(f.n)}? Ntibishobora gusubizwa inyuma.`),async()=>{try{await idbP("del",String(id))}catch(e){}logA("File deleted",f.n);FL=FL.filter(x=>x.id!==id);sv("bizz_files",FL);flR()});
}
function flAcc(id){
  const f=FL.find(x=>x.id===id);if(!f||!can("admin"))return;
  const us=U.filter(u=>(u.role||"Administrator")!=="Administrator");
  modal(`<h3>🔒 ${L("Access","Uburenganzira")}: ${esc(f.n)}</h3><label class="ck"><input type="checkbox" id="fal" ${f.all?"checked":""}> ${L("Everyone can view","Bose bashobora kureba")}</label>${us.map(u=>`<div class="tt" style="align-items:center"><span>${esc(u.name)}<br><small class="mu">${esc(u.role||"")}</small></span><span><label class="ck" style="display:inline-flex;margin:0 10px 0 0"><input type="checkbox" class="fav" data-u="${esc(u.id)}" ${(f.v||[]).includes(u.id)?"checked":""}> 👁</label><label class="ck" style="display:inline-flex;margin:0"><input type="checkbox" class="fae" data-u="${esc(u.id)}" ${(f.e||[]).includes(u.id)?"checked":""}> ✏️</label></span></div>`).join("")||`<div class="emp">${L("No other users yet.","Nta bandi bakozi bahari.")}</div>`}<p class="mu" style="font-size:11.5px">👁 ${L("view","kureba")} • ✏️ ${L("edit (rename, delete)","guhindura (guhindura izina, gusiba)")}</p><div class="g2"><button class="btn o" onclick="closeM()">${L("Cancel","Reka")}</button><button class="btn" onclick="flAccS(${id})">${L("Save","Bika")}</button></div>`);
}
function flAccS(id){
  const f=FL.find(x=>x.id===id);
  f.all=$("fal").checked;f.v=[...document.querySelectorAll(".fav:checked")].map(x=>x.dataset.u);f.e=[...document.querySelectorAll(".fae:checked")].map(x=>x.dataset.u);
  logA("File access changed",f.n);sv("bizz_files",FL);closeM();toast(L("Saved ✔","Byabitswe ✔"));flR();
}

/* FULL TRANSLATION LAYER */
const TRD={"Ask AI": {"en": "Ask AI", "fr": "Demander à l'IA", "sw": "Uliza AI", "rw": "Baza AI"}, "Open": {"en": "Open", "fr": "Ouvrir", "sw": "Fungua", "rw": "Fungura"}, "Sales": {"en": "Sales", "fr": "Ventes", "sw": "Mauzo", "rw": "Igurisha"}, "Products": {"en": "Products", "fr": "Produits", "sw": "Bidhaa", "rw": "Ibicuruzwa"}, "Customers": {"en": "Customers", "fr": "Clients", "sw": "Wateja", "rw": "Abakiriya"}, "Products in stock": {"en": "Products in stock", "fr": "Produits en stock", "sw": "Bidhaa zilizopo", "rw": "Ibicuruzwa biri muri stock"}, "Items": {"en": "Items", "fr": "Articles", "sw": "Vitu", "rw": "Ibicuruzwa"}, "Total": {"en": "Total", "fr": "Total", "sw": "Jumla", "rw": "Igiteranyo"}, "Payment": {"en": "Payment", "fr": "Paiement", "sw": "Malipo", "rw": "Kwishyura"}, "Paid": {"en": "Paid", "fr": "Payé", "sw": "Imelipwa", "rw": "Byishyuwe"}, "Sale date": {"en": "Sale date", "fr": "Date de vente", "sw": "Tarehe ya mauzo", "rw": "Itariki y'igurisha"}, "All": {"en": "All", "fr": "Tout", "sw": "Zote", "rw": "Byose"}, "Manage all your products": {"en": "Manage all your products", "fr": "Gérez tous vos produits", "sw": "Simamia bidhaa zako zote", "rw": "Gucunga ibicuruzwa byose"}, "Add": {"en": "Add", "fr": "Ajouter", "sw": "Ongeza", "rw": "Ongeramo"}, "Total products": {"en": "Total products", "fr": "Total produits", "sw": "Jumla ya bidhaa", "rw": "Ibicuruzwa byose"}, "In stock": {"en": "In stock", "fr": "En stock", "sw": "Zipo", "rw": "Bihari"}, "Running low": {"en": "Running low", "fr": "Stock faible", "sw": "Zinakaribia kuisha", "rw": "Bigiye gushira"}, "Total value": {"en": "Total value", "fr": "Valeur totale", "sw": "Thamani yote", "rw": "Agaciro kose"}, "All categories": {"en": "All categories", "fr": "Toutes les catégories", "sw": "Kategoria zote", "rw": "Ibyiciro byose"}, "Products running low": {"en": "Products running low", "fr": "Produits en stock faible", "sw": "Bidhaa zinakaribia kuisha", "rw": "Ibicuruzwa bigiye gushira"}, "View all": {"en": "View all", "fr": "Tout voir", "sw": "Ona zote", "rw": "Reba byose"}, "Product Details": {"en": "Product Details", "fr": "Détails du produit", "sw": "Maelezo ya bidhaa", "rw": "Ibisobanuro by'igicuruzwa"}, "View and manage product information": {"en": "View and manage product information", "fr": "Voir et gérer les informations du produit", "sw": "Tazama na simamia taarifa za bidhaa", "rw": "Reba kandi ucunge amakuru y'igicuruzwa"}, "Selling Price": {"en": "Selling Price", "fr": "Prix de vente", "sw": "Bei ya kuuza", "rw": "Igiciro cyo kugurisha"}, "Purchase Price": {"en": "Purchase Price", "fr": "Prix d'achat", "sw": "Bei ya kununua", "rw": "Igiciro cyo kugura"}, "Profit / Unit": {"en": "Profit / Unit", "fr": "Bénéfice / unité", "sw": "Faida / kipimo", "rw": "Inyungu / 1"}, "Overview": {"en": "Overview", "fr": "Aperçu", "sw": "Muhtasari", "rw": "Incamake"}, "Stock Movement": {"en": "Stock Movement", "fr": "Mouvement de stock", "sw": "Mwenendo wa hisa", "rw": "Stock"}, "Sales History": {"en": "Sales History", "fr": "Historique des ventes", "sw": "Historia ya mauzo", "rw": "Igurisha"}, "Product Information": {"en": "Product Information", "fr": "Informations produit", "sw": "Taarifa za bidhaa", "rw": "Ibisobanuro by'igicuruzwa"}, "Product Name": {"en": "Product Name", "fr": "Nom du produit *", "sw": "Jina la bidhaa *", "rw": "Izina"}, "Product Code": {"en": "Product Code", "fr": "Code produit", "sw": "Msimbo wa bidhaa", "rw": "Code"}, "Category": {"en": "Category", "fr": "Catégorie *", "sw": "Kategoria *", "rw": "Icyiciro"}, "Brand": {"en": "Brand", "fr": "Marque", "sw": "Chapa", "rw": "Ikirango"}, "Unit": {"en": "Unit", "fr": "Unité", "sw": "Kipimo", "rw": "Igipimo"}, "Profit per Unit": {"en": "Profit per Unit", "fr": "Bénéfice par unité", "sw": "Faida kwa kipimo", "rw": "Inyungu kuri 1"}, "Location / Shelf": {"en": "Location / Shelf", "fr": "Emplacement / étagère", "sw": "Mahali / rafu", "rw": "Aho giherereye"}, "Expiry": {"en": "Expiry", "fr": "Expiration", "sw": "Muda wa kuisha", "rw": "Itariki izarangiriraho"}, "Tax rate": {"en": "Tax rate", "fr": "Taux de taxe", "sw": "Kiwango cha kodi", "rw": "Umusoro"}, "Status": {"en": "Status", "fr": "Statut", "sw": "Hali", "rw": "Imiterere"}, "Active": {"en": "Active", "fr": "Actif", "sw": "Hai", "rw": "Ikora"}, "Stock Overview": {"en": "Stock Overview", "fr": "Aperçu du stock", "sw": "Muhtasari wa hisa", "rw": "Incamake ya stock"}, "items": {"en": "items", "fr": "articles", "sw": "vitu", "rw": "ibintu"}, "Total stock": {"en": "Total stock", "fr": "Stock total", "sw": "Hisa yote", "rw": "Stock yose"}, "Low alert": {"en": "Low alert", "fr": "Alerte stock faible", "sw": "Tahadhari ya hisa ndogo", "rw": "Itangazo ryo gushira"}, "Quick Actions": {"en": "Quick Actions", "fr": "Actions rapides", "sw": "Vitendo vya haraka", "rw": "Ibikorwa byihuse"}, "Stock In": {"en": "Stock In", "fr": "Entrée de stock", "sw": "Ongeza hisa", "rw": "Ongeramo stock"}, "Stock Out": {"en": "Stock Out", "fr": "Sortie de stock", "sw": "Toa hisa", "rw": "Kuramo stock"}, "Edit Product": {"en": "Edit Product", "fr": "Modifier le produit", "sw": "Hariri bidhaa", "rw": "Hindura"}, "Delete": {"en": "Delete", "fr": "Supprimer", "sw": "Futa", "rw": "Siba"}, "Recent Activity": {"en": "Recent Activity", "fr": "Activité récente", "sw": "Shughuli za hivi karibuni", "rw": "Ibyakozwe vuba"}, "Add Product": {"en": "Add Product", "fr": "Ajouter un produit", "sw": "Ongeza bidhaa", "rw": "Ongeramo Igicuruzwa"}, "Fill in the product information": {"en": "Fill in the product information", "fr": "Remplissez les informations du produit", "sw": "Jaza taarifa za bidhaa", "rw": "Uzuza amakuru y'igicuruzwa"}, "Basic Information": {"en": "Basic Information", "fr": "Informations de base", "sw": "Taarifa za msingi", "rw": "Amakuru y'ibanze"}, "Product photos (first one is the main photo": {"en": "Product photos (first one is the main photo", "fr": "Photos du produit (la première est la principale)", "sw": "Picha za bidhaa (ya kwanza ndiyo kuu)", "rw": "Amafoto y'igicuruzwa (iya mbere ni yo y'ingenzi"}, "Add Photo": {"en": "Add Photo", "fr": "Ajouter une photo", "sw": "Ongeza picha", "rw": "Ongeramo ifoto"}, "Product Code / SKU": {"en": "Product Code / SKU", "fr": "Code / SKU produit", "sw": "Msimbo / SKU ya bidhaa", "rw": "Code / SKU y'igicuruzwa"}, "Manage": {"en": "Manage", "fr": "Gérer", "sw": "Simamia", "rw": "Cunga"}, "Supplier": {"en": "Supplier", "fr": "Fournisseur", "sw": "Msambazaji", "rw": "Utanga ibicuruzwa"}, "Brand (optional": {"en": "Brand (optional", "fr": "Marque (facultatif)", "sw": "Chapa (si lazima)", "rw": "Ikirango (si ngombwa"}, "Description (optional": {"en": "Description (optional", "fr": "Description (facultatif)", "sw": "Maelezo (si lazima)", "rw": "Ibisobanuro (si ngombwa"}, "Pricing & Stock": {"en": "Pricing & Stock", "fr": "Prix et stock", "sw": "Bei na hisa", "rw": "Ibiciro na Stock"}, "Single (1 piece": {"en": "Single (1 piece", "fr": "Unitaire (1 pièce)", "sw": "Moja moja (kipande 1)", "rw": "Piece 1"}, "Sell single pieces": {"en": "Sell single pieces", "fr": "Vendre des pièces à l'unité", "sw": "Uza vipande moja moja", "rw": "Gurisha piece imwe"}, "Purchase Price / piece": {"en": "Purchase Price / piece", "fr": "Prix d'achat / pièce *", "sw": "Bei ya kununua / kipande *", "rw": "Igiciro cyo kugura / piece"}, "Selling Price / piece": {"en": "Selling Price / piece", "fr": "Prix de vente / pièce *", "sw": "Bei ya kuuza / kipande *", "rw": "Igiciro cyo kugurisha / piece"}, "Profit Margin": {"en": "Profit Margin", "fr": "Marge bénéficiaire", "sw": "Kiwango cha faida", "rw": "Inyungu"}, "Unit name": {"en": "Unit name", "fr": "Nom de l'unité", "sw": "Jina la kipimo", "rw": "Izina rya piece (unit"}, "Add Pack / Box option": {"en": "Add Pack / Box option", "fr": "Ajouter un pack / une boîte", "sw": "Ongeza pakiti / sanduku", "rw": "Ongeramo pack / box"}, "Low Stock Alert (pieces": {"en": "Low Stock Alert (pieces", "fr": "Alerte stock faible (pièces)", "sw": "Tahadhari ya hisa ndogo (vipande)", "rw": "Itangazo ryo gushira (pieces"}, "Additional Details": {"en": "Additional Details", "fr": "Détails supplémentaires", "sw": "Maelezo ya ziada", "rw": "Andi makuru"}, "Expiry Date (optional": {"en": "Expiry Date (optional", "fr": "Date d'expiration (facultatif)", "sw": "Tarehe ya kuisha (si lazima)", "rw": "Itariki izarangiriraho"}, "Tax Rate": {"en": "Tax Rate", "fr": "Taux de taxe", "sw": "Kiwango cha kodi", "rw": "Umusoro"}, "0% (No Tax": {"en": "0% (No Tax", "fr": "0% (sans taxe)", "sw": "0% (bila kodi)", "rw": "0% (Nta musoro"}, "Active (available for sale": {"en": "Active (available for sale", "fr": "Actif (disponible à la vente)", "sw": "Hai (inauzwa)", "rw": "Ikora (kiragurishwa"}, "Product Summary": {"en": "Product Summary", "fr": "Résumé du produit", "sw": "Muhtasari wa bidhaa", "rw": "Incamake y'igicuruzwa"}, "Stock Quantity": {"en": "Stock Quantity", "fr": "Quantité en stock", "sw": "Kiasi cha hisa", "rw": "Stock"}, "Low Stock Alert": {"en": "Low Stock Alert", "fr": "Alerte stock faible", "sw": "Tahadhari ya hisa ndogo", "rw": "Itangazo ryo gushira"}, "Reset": {"en": "Reset", "fr": "Réinitialiser", "sw": "Weka upya", "rw": "Subiza uko byari"}, "Save Product": {"en": "Save Product", "fr": "Enregistrer le produit", "sw": "Hifadhi bidhaa", "rw": "Bika Igicuruzwa"}, "All your other tools": {"en": "All your other tools", "fr": "Tous vos autres outils", "sw": "Zana zako zote", "rw": "Ibindi bikoresho byawe byose"}, "Inventory": {"en": "Inventory", "fr": "Inventaire", "sw": "Hifadhi", "rw": "Ububiko"}, "Stock levels & movements": {"en": "Stock levels & movements", "fr": "Niveaux et mouvements de stock", "sw": "Viwango na mienendo ya hisa", "rw": "Stock n'imigendekere yayo"}, "Finance": {"en": "Finance", "fr": "Finances", "sw": "Fedha", "rw": "Imari"}, "Income, expenses & profit": {"en": "Income, expenses & profit", "fr": "Revenus, dépenses et bénéfices", "sw": "Mapato, matumizi na faida", "rw": "Ibyinjira, ibisohoka n'inyungu"}, "Reports": {"en": "Reports", "fr": "Rapports", "sw": "Ripoti", "rw": "Raporo"}, "Sales, profit & debts": {"en": "Sales, profit & debts", "fr": "Ventes, bénéfices et dettes", "sw": "Mauzo, faida na madeni", "rw": "Igurisha, inyungu n'ideni"}, "Suppliers": {"en": "Suppliers", "fr": "Fournisseurs", "sw": "Wasambazaji", "rw": "Abatanga ibicuruzwa"}, "People who supply you": {"en": "People who supply you", "fr": "Les personnes qui vous fournissent", "sw": "Watu wanaokuletea bidhaa", "rw": "Abagutangira ibicuruzwa"}, "Activity Log": {"en": "Activity Log", "fr": "Journal d'activité", "sw": "Kumbukumbu ya shughuli", "rw": "Ibyakozwe byose"}, "Everything done, with date & time": {"en": "Everything done, with date & time", "fr": "Tout ce qui est fait, avec date et heure", "sw": "Kila kitendo, kwa tarehe na saa", "rw": "Ibikorwa byose n'itariki n'isaha"}, "Files & Photos": {"en": "Files & Photos", "fr": "Fichiers et photos", "sw": "Faili na picha", "rw": "Dosiye n'amafoto"}, "Documents & images": {"en": "Documents & images", "fr": "Documents et images", "sw": "Hati na picha", "rw": "Inyandiko n'amashusho"}, "Shop": {"en": "Shop", "fr": "Boutique", "sw": "Duka", "rw": "Iduka"}, "Public shop view": {"en": "Public shop view", "fr": "Vue publique de la boutique", "sw": "Muonekano wa duka kwa umma", "rw": "Uko iduka ryerekanwa"}, "Expenses": {"en": "Expenses", "fr": "Dépenses", "sw": "Matumizi", "rw": "Amafaranga yakoreshejwe"}, "Track spending": {"en": "Track spending", "fr": "Suivre les dépenses", "sw": "Fuatilia matumizi", "rw": "Kurikirana ikoreshwa ry'amafaranga"}, "Ask about your business": {"en": "Ask about your business", "fr": "Posez des questions sur votre commerce", "sw": "Uliza kuhusu biashara yako", "rw": "Baza ku bucuruzi bwawe"}, "Settings": {"en": "Settings", "fr": "Paramètres", "sw": "Mipangilio", "rw": "Igenamiterere"}, "Account & app options": {"en": "Account & app options", "fr": "Compte et options de l'application", "sw": "Akaunti na chaguo za programu", "rw": "Konti n'amahitamo ya app"}, "Ask in Kinyarwanda or English": {"en": "Ask in Kinyarwanda or English", "fr": "Posez en kinyarwanda ou en anglais", "sw": "Uliza kwa Kinyarwanda au Kiingereza", "rw": "Baza mu Kinyarwanda cyangwa mu Cyongereza"}, "Ask me anything about your business": {"en": "Ask me anything about your business", "fr": "Demandez-moi ce que vous voulez sur votre commerce…", "sw": "Niulize chochote kuhusu biashara yako…", "rw": "Mbaza icyo ushaka ku bucuruzi bwawe"}, "How much did we sell today": {"en": "How much did we sell today", "fr": "Combien avons-nous vendu aujourd'hui ?", "sw": "Tumeuza kiasi gani leo?", "rw": "Uyu munsi twagurishije angahe"}, "Explain what each seller did today": {"en": "Explain what each seller did today", "fr": "Expliquez ce que chaque vendeur a fait aujourd'hui", "sw": "Eleza kila muuzaji alichofanya leo", "rw": "Nsobanurira ibyo buri muyuza yakoze uyu munsi"}, "Which products are running low": {"en": "Which products are running low", "fr": "Quels produits sont en train de s'épuiser ?", "sw": "Ni bidhaa zipi zinakaribia kuisha?", "rw": "Ni ibihe bicuruzwa bigiye gushira"}, "Who owes us money": {"en": "Who owes us money", "fr": "Qui nous doit de l'argent ?", "sw": "Nani anatudai?", "rw": "Ni nde ufite ideni"}, "Clear chat": {"en": "Clear chat", "fr": "Effacer la discussion", "sw": "Futa mazungumzo", "rw": "Siba ibiganiro"}, "Insights": {"en": "Insights", "fr": "Analyses", "sw": "Mwelekeo", "rw": "Inama n'ibyagaragaye"}, "Everything done in the app, with date & time": {"en": "Everything done in the app, with date & time", "fr": "Tout ce qui a été fait dans l'application, avec date et heure", "sw": "Kila kitendo kilichofanywa kwenye programu, kwa tarehe na saa", "rw": "Ibikorwa byose byakozwe, hamwe n'itariki n'isaha"}, "Today": {"en": "Today", "fr": "Aujourd'hui", "sw": "Leo", "rw": "Uyu munsi"}, "Yesterday": {"en": "Yesterday", "fr": "Hier", "sw": "Jana", "rw": "Ejo"}, "7 days": {"en": "7 days", "fr": "7 jours", "sw": "Siku 7", "rw": "Iminsi 7"}, "All users": {"en": "All users", "fr": "Tous les utilisateurs", "sw": "Watumiaji wote", "rw": "Abakozi bose"}, "Export CSV": {"en": "Export CSV", "fr": "Exporter en CSV", "sw": "Hamisha CSV", "rw": "Kuramo CSV"}, "People and companies who supply you": {"en": "People and companies who supply you", "fr": "Personnes et entreprises qui vous fournissent", "sw": "Watu na kampuni zinazokuletea bidhaa", "rw": "Abantu n'ibigo bagutangira ibicuruzwa"}, "Add Supplier": {"en": "Add Supplier", "fr": "Ajouter un fournisseur", "sw": "Ongeza msambazaji", "rw": "Ongeramo utanga ibicuruzwa"}, "No suppliers yet": {"en": "No suppliers yet", "fr": "Aucun fournisseur pour l'instant.", "sw": "Hakuna wasambazaji bado.", "rw": "Nta batanga ibicuruzwa bahari"}, "Income, expenses and profit at a glance": {"en": "Income, expenses and profit at a glance", "fr": "Revenus, dépenses et bénéfices en un coup d'œil", "sw": "Mapato, matumizi na faida kwa muhtasari", "rw": "Ibyinjira, ibisohoka n'inyungu ukireba vuba"}, "This month": {"en": "This month", "fr": "Ce mois", "sw": "Mwezi huu", "rw": "Uku kwezi"}, "This year": {"en": "This year", "fr": "Cette année", "sw": "Mwaka huu", "rw": "Uyu mwaka"}, "All time": {"en": "All time", "fr": "Depuis toujours", "sw": "Muda wote", "rw": "Igihe cyose"}, "Revenue": {"en": "Revenue", "fr": "Chiffre d'affaires", "sw": "Mapato", "rw": "Ibyinjijwe mu igurisha"}, "Gross profit": {"en": "Gross profit", "fr": "Bénéfice brut", "sw": "Faida ghafi", "rw": "Inyungu y'ibanze"}, "Net profit": {"en": "Net profit", "fr": "Bénéfice net", "sw": "Faida safi", "rw": "Inyungu isigaye"}, "Cash flow": {"en": "Cash flow", "fr": "Flux de trésorerie", "sw": "Mtiririko wa fedha", "rw": "Imigendekere y'amafaranga"}, "Money in": {"en": "Money in", "fr": "Entrées d'argent", "sw": "Fedha zilizoingia", "rw": "Amafaranga yinjiye"}, "Money out": {"en": "Money out", "fr": "Sorties d'argent", "sw": "Fedha zilizotoka", "rw": "Amafaranga yasohotse"}, "Balance": {"en": "Balance", "fr": "Solde", "sw": "Salio", "rw": "Asigaye"}, "Last 7 days": {"en": "Last 7 days", "fr": "7 derniers jours", "sw": "Siku 7 zilizopita", "rw": "Iminsi 7 ishize"}, "Debts owed to you": {"en": "Debts owed to you", "fr": "Dettes qui vous sont dues", "sw": "Madeni yanayokudai", "rw": "Amadeni bagufitiye"}, "Overdue debts": {"en": "Overdue debts", "fr": "Dettes en retard", "sw": "Madeni yaliyochelewa", "rw": "Amadeni yarengeje igihe"}, "Stock value (cost": {"en": "Stock value (cost", "fr": "Valeur du stock (coût)", "sw": "Thamani ya hisa (gharama)", "rw": "Agaciro ka stock (kugura"}, "Stock value (retail": {"en": "Stock value (retail", "fr": "Valeur du stock (détail)", "sw": "Thamani ya hisa (rejareja)", "rw": "Agaciro ka stock (kugurisha"}, "Money in by method": {"en": "Money in by method", "fr": "Entrées par mode de paiement", "sw": "Fedha zilizoingia kwa njia", "rw": "Amafaranga yinjiye ukurikije uburyo"}, "Money out by method": {"en": "Money out by method", "fr": "Sorties par mode de paiement", "sw": "Fedha zilizotoka kwa njia", "rw": "Amafaranga yasohotse ukurikije uburyo"}, "Expenses by category": {"en": "Expenses by category", "fr": "Dépenses par catégorie", "sw": "Matumizi kwa kategoria", "rw": "Ibyakoreshejwe ukurikije icyiciro"}, "Top products by profit": {"en": "Top products by profit", "fr": "Produits les plus rentables", "sw": "Bidhaa zenye faida zaidi", "rw": "Ibicuruzwa bifite inyungu nyinshi"}, "Open Reports": {"en": "Open Reports", "fr": "Ouvrir les rapports", "sw": "Fungua Ripoti", "rw": "Fungura Raporo"}, "Pick a report and period, then print or export": {"en": "Pick a report and period, then print or export", "fr": "Choisissez un rapport et une période, puis imprimez ou exportez", "sw": "Chagua ripoti na kipindi, kisha chapisha au hamisha", "rw": "Hitamo raporo n'igihe, hanyuma uyisohore cyangwa uyikuremo"}, "Profit & Loss": {"en": "Profit & Loss", "fr": "Compte de résultat", "sw": "Faida na hasara", "rw": "Inyungu n'igihombo"}, "Debts": {"en": "Debts", "fr": "Dettes", "sw": "Madeni", "rw": "Amadeni"}, "Staff": {"en": "Staff", "fr": "Personnel", "sw": "Wafanyakazi", "rw": "Abakozi"}, "Date": {"en": "Date", "fr": "Date", "sw": "Tarehe", "rw": "Itariki"}, "Customer": {"en": "Customer", "fr": "Client", "sw": "Mteja", "rw": "Umukiriya"}, "Seller": {"en": "Seller", "fr": "Vendeur", "sw": "Muuzaji", "rw": "Umuyuza"}, "Debt": {"en": "Debt", "fr": "Dette", "sw": "Deni", "rw": "Ideni"}, "TOTAL": {"en": "TOTAL", "fr": "TOTAL", "sw": "JUMLA", "rw": "IGITERANYO"}, "Print / PDF": {"en": "Print / PDF", "fr": "Imprimer / PDF", "sw": "Chapisha / PDF", "rw": "Sohora / PDF"}, "Inventory Management": {"en": "Inventory Management", "fr": "Gestion de l'inventaire", "sw": "Usimamizi wa hifadhi", "rw": "Imicungire y'ububiko"}, "Track your stock and avoid running out": {"en": "Track your stock and avoid running out", "fr": "Suivez votre stock et évitez les ruptures", "sw": "Fuatilia hisa yako usiishiwe", "rw": "Kurikirana stock yawe wirinde ko ishira"}, "Add Stock": {"en": "Add Stock", "fr": "Ajouter du stock", "sw": "Ongeza hisa", "rw": "Ongeramo stock"}, "Total Products": {"en": "Total Products", "fr": "Total produits", "sw": "Jumla ya bidhaa", "rw": "Ibicuruzwa byose"}, "Total Stock Value": {"en": "Total Stock Value", "fr": "Valeur totale du stock", "sw": "Thamani ya hisa yote", "rw": "Agaciro ka stock"}, "Low Stock Items": {"en": "Low Stock Items", "fr": "Articles en stock faible", "sw": "Bidhaa zenye hisa ndogo", "rw": "Bigiye gushira"}, "Out of Stock": {"en": "Out of Stock", "fr": "Rupture de stock", "sw": "Zimeisha", "rw": "Byashize"}, "Sort: Name (A-Z": {"en": "Sort: Name (A-Z", "fr": "Trier : nom (A-Z)", "sw": "Panga: Jina (A-Z)", "rw": "Tondeka: Izina (A-Z"}, "Sort: Stock (low-high": {"en": "Sort: Stock (low-high", "fr": "Trier : stock (croissant)", "sw": "Panga: Hisa (ndogo-kubwa)", "rw": "Tondeka: Stock (make-nyinshi"}, "Sort: Stock (high-low": {"en": "Sort: Stock (high-low", "fr": "Trier : stock (décroissant)", "sw": "Panga: Hisa (kubwa-ndogo)", "rw": "Tondeka: Stock (nyinshi-make"}, "Sort: Value": {"en": "Sort: Value", "fr": "Trier : valeur", "sw": "Panga: Thamani", "rw": "Tondeka: Agaciro"}, "Select all": {"en": "Select all", "fr": "Tout sélectionner", "sw": "Chagua zote", "rw": "Hitamo byose"}, "Access and manage your files and images": {"en": "Access and manage your files and images", "fr": "Accédez à vos fichiers et images et gérez-les", "sw": "Fikia na simamia faili na picha zako", "rw": "Reba kandi ucunge dosiye n'amafoto yawe"}, "Files": {"en": "Files", "fr": "Fichiers", "sw": "Faili", "rw": "Dosiye"}, "Photos": {"en": "Photos", "fr": "Photos", "sw": "Picha", "rw": "Amafoto"}, "Upload": {"en": "Upload", "fr": "Téléverser", "sw": "Pakia", "rw": "Shyiraho"}, "Files or photos": {"en": "Files or photos", "fr": "Fichiers ou photos", "sw": "Faili au picha", "rw": "Dosiye cyangwa amafoto"}, "New Folder": {"en": "New Folder", "fr": "Nouveau dossier", "sw": "Folda mpya", "rw": "Ububiko bushya"}, "Create folder": {"en": "Create folder", "fr": "Créer un dossier", "sw": "Unda folda", "rw": "Kora ububiko"}, "Open Camera": {"en": "Open Camera", "fr": "Ouvrir la caméra", "sw": "Fungua kamera", "rw": "Fungura Camera"}, "Take a photo": {"en": "Take a photo", "fr": "Prendre une photo", "sw": "Piga picha", "rw": "Fata ifoto"}, "Gallery": {"en": "Gallery", "fr": "Galerie", "sw": "Matunzio", "rw": "Amafoto"}, "View all photos": {"en": "View all photos", "fr": "Voir toutes les photos", "sw": "Ona picha zote", "rw": "Reba amafoto yose"}, "Storage Used": {"en": "Storage Used", "fr": "Espace utilisé", "sw": "Hifadhi iliyotumika", "rw": "Ububiko bukoreshwa"}, "Folders": {"en": "Folders", "fr": "Dossiers", "sw": "Folda", "rw": "Ububiko"}, "View All": {"en": "View All", "fr": "Tout voir ›", "sw": "Ona zote ›", "rw": "Reba byose"}, "Documents": {"en": "Documents", "fr": "Documents", "sw": "Hati", "rw": "Inyandiko"}, "Downloads": {"en": "Downloads", "fr": "Téléchargements", "sw": "Vipakuliwa", "rw": "Ibikuruwe"}, "Pictures": {"en": "Pictures", "fr": "Images", "sw": "Picha", "rw": "Amashusho"}, "Music": {"en": "Music", "fr": "Musique", "sw": "Muziki", "rw": "Umuziki"}, "Archives": {"en": "Archives", "fr": "Archives", "sw": "Kumbukumbu", "rw": "Ububiko"}, "Recent Files": {"en": "Recent Files", "fr": "Fichiers récents", "sw": "Faili za hivi karibuni", "rw": "Dosiye ziheruka"}, "No files here yet": {"en": "No files here yet", "fr": "Aucun fichier pour l'instant.", "sw": "Hakuna faili bado.", "rw": "Nta dosiye zihari"}, "Files are stored on this device (browser). They are not included in the data backup": {"en": "Files are stored on this device (browser). They are not included in the data backup", "fr": "Les fichiers sont stockés sur cet appareil (navigateur). Ils ne sont pas inclus dans la sauvegarde des données.", "sw": "Faili zinahifadhiwa kwenye kifaa hiki (kivinjari). Hazijumuishwi kwenye hifadhi nakala ya data.", "rw": "Dosiye zibikwa kuri iki gikoresho (browser). Ntizijya muri backup y'amakuru"}, "Navigator & More": {"en": "Navigator & More", "fr": "Navigateur et plus", "sw": "Navigator na zaidi", "rw": "Navigator na Home"}, "Control where each button appears": {"en": "Control where each button appears", "fr": "Choisissez où apparaît chaque bouton", "sw": "Chagua mahali kila kitufe kinapoonekana", "rw": "Hitamo aho buri buto igaragara"}, "Navigator Management": {"en": "Navigator Management", "fr": "Gestion du navigateur", "sw": "Usimamizi wa Navigator", "rw": "Gucunga Navigator"}, "Buttons in the bottom bar": {"en": "Buttons in the bottom bar", "fr": "Boutons de la barre du bas", "sw": "Vitufe vya upau wa chini", "rw": "Buto ziri mu murongo wo hasi"}, "Home Management": {"en": "Home Management", "fr": "Gestion de l'accueil", "sw": "Usimamizi wa Home", "rw": "Gucunga Home"}, "Buttons inside the Home menu (☰ top right": {"en": "Buttons inside the Home menu (☰ top right", "fr": "Boutons du menu Accueil (☰ en haut à droite)", "sw": "Vitufe vya menyu ya Home (☰ juu kulia)", "rw": "Buto ziri muri menu ya Home (☰ hejuru iburyo"}, "Every button is either in the Navigator (bottom bar) or in Home — never both. The Navigator holds up to 5 buttons": {"en": "Every button is either in the Navigator (bottom bar) or in Home — never both. The Navigator holds up to 5 buttons", "fr": "Chaque bouton est soit dans le navigateur (barre du bas), soit dans l'accueil — jamais les deux. Le navigateur contient jusqu'à 5 boutons.", "sw": "Kila kitufe kiko kwenye Navigator (upau wa chini) au kwenye Home — si vyote. Navigator inashikilia vitufe 5 kwa kiwango cha juu.", "rw": "Buri buto iba muri Navigator (umurongo wo hasi) cyangwa muri Home — ntiba hose. Navigator ifata buto 5 ntarengwa"}, "Buttons shown in the bottom bar": {"en": "Buttons shown in the bottom bar", "fr": "Boutons affichés dans la barre du bas", "sw": "Vitufe vinavyoonekana kwenye upau wa chini", "rw": "Buto zigaragara mu murongo wo hasi"}, "Preview of the bottom bar": {"en": "Preview of the bottom bar", "fr": "Aperçu de la barre du bas", "sw": "Muonekano wa upau wa chini", "rw": "Uko umurongo wo hasi usa"}, "Available (in Home": {"en": "Available (in Home", "fr": "Disponibles (dans l'accueil)", "sw": "Vilivyopo (kwenye Home)", "rw": "Ziriho (muri Home"}, "Buttons shown in the Home menu": {"en": "Buttons shown in the Home menu", "fr": "Boutons affichés dans le menu Accueil (☰)", "sw": "Vitufe vinavyoonekana kwenye menyu ya Home (☰)", "rw": "Buto zigaragara muri menu ya Home"}, "Choose which buttons appear in the bottom bar and in Home": {"en": "Choose which buttons appear in the bottom bar and in Home", "fr": "Choisissez les boutons à afficher dans la barre du bas et dans l'accueil", "sw": "Chagua vitufe vitakavyoonekana kwenye upau wa chini na kwenye Home", "rw": "Hitamo buto zigaragara hasi no muri Home"}, "Business overview": {"en": "Business overview", "fr": "Aperçu de l'activité", "sw": "Muhtasari wa biashara", "rw": "Incamake y'ubucuruzi"}, "Record and view sales": {"en": "Record and view sales", "fr": "Enregistrer et consulter les ventes", "sw": "Rekodi na tazama mauzo", "rw": "Andika kandi urebe igurisha"}, "Manage your products": {"en": "Manage your products", "fr": "Gérez vos produits", "sw": "Simamia bidhaa zako", "rw": "Gucunga ibicuruzwa"}, "Your customers": {"en": "Your customers", "fr": "Vos clients", "sw": "Wateja wako", "rw": "Abakiriya bawe"}, "Language": {"en": "Language", "fr": "Langue", "sw": "Lugha", "rw": "Ururimi"}, "Choose the app language": {"en": "Choose the app language", "fr": "Choisissez la langue de l'application", "sw": "Chagua lugha ya programu", "rw": "Hitamo ururimi rw'app"}, "Customize your app and manage your account": {"en": "Customize your app and manage your account", "rw": "Hindura app yawe kandi ucunge konti yawe", "fr": "Personnalisez l'application et gérez votre compte", "sw": "Badilisha programu na usimamie akaunti yako"}, "Edit Profile": {"en": "Edit Profile", "rw": "Hindura umwirondoro", "fr": "Modifier le profil", "sw": "Hariri wasifu"}, "Business Owner": {"en": "Business Owner", "rw": "Nyiri ubucuruzi", "fr": "Propriétaire", "sw": "Mmiliki wa biashara"}, "Account & Security": {"en": "Account & Security", "rw": "Konti n'umutekano", "fr": "Compte et sécurité", "sw": "Akaunti na usalama"}, "Manage your login and security settings": {"en": "Manage your login and security settings", "rw": "Gucunga kwinjira n'umutekano", "fr": "Gérez la connexion et la sécurité", "sw": "Simamia kuingia na usalama"}, "Change Password": {"en": "Change Password", "rw": "Hindura password", "fr": "Changer le mot de passe", "sw": "Badilisha nenosiri"}, "Update your account password": {"en": "Update your account password", "rw": "Vugurura password ya konti yawe", "fr": "Mettez à jour le mot de passe de votre compte", "sw": "Sasisha nenosiri la akaunti yako"}, "Two-Factor Authentication": {"en": "Two-Factor Authentication", "rw": "Kwemeza mu ntambwe ebyiri", "fr": "Authentification à deux facteurs", "sw": "Uthibitishaji wa hatua mbili"}, "Add an extra layer of security": {"en": "Add an extra layer of security", "rw": "Ongeramo urundi rwego rw'umutekano", "fr": "Ajoutez une couche de sécurité supplémentaire", "sw": "Ongeza safu ya ziada ya usalama"}, "Login Activity": {"en": "Login Activity", "rw": "Ibikorwa byo kwinjira", "fr": "Activité de connexion", "sw": "Shughuli za kuingia"}, "View your recent login sessions": {"en": "View your recent login sessions", "rw": "Reba uko winjiye vuba aha", "fr": "Voir vos dernières connexions", "sw": "Tazama vikao vyako vya hivi karibuni"}, "App Preferences": {"en": "App Preferences", "rw": "Ibyo ukunda muri app", "fr": "Préférences de l'application", "sw": "Mapendeleo ya programu"}, "Customize how the app works for you": {"en": "Customize how the app works for you", "rw": "Hindura uko app ikora ku bwawe", "fr": "Personnalisez le fonctionnement de l'application", "sw": "Badilisha jinsi programu inavyofanya kazi"}, "AI Assistant": {"en": "AI Assistant", "rw": "Umufasha wa AI", "fr": "Assistant IA", "sw": "Msaidizi wa AI"}, "Show Memo AI on dashboard, menu and quick actions": {"en": "Show Memo AI on dashboard, menu and quick actions", "rw": "Erekana Memo AI ku dashboard, menu n'ibikorwa byihuse", "fr": "Afficher Memo AI sur le tableau de bord, le menu et les actions rapides", "sw": "Onyesha Memo AI kwenye dashibodi, menyu na vitendo vya haraka"}, "Theme": {"en": "Theme", "rw": "Ibara (Theme)", "fr": "Thème", "sw": "Mandhari"}, "Choose your preferred theme": {"en": "Choose your preferred theme", "rw": "Hitamo theme ukunda", "fr": "Choisissez le thème préféré", "sw": "Chagua mandhari unayopenda"}, "Dark": {"en": "Dark", "rw": "Umwijima", "fr": "Sombre", "sw": "Giza"}, "Light": {"en": "Light", "rw": "Umucyo", "fr": "Clair", "sw": "Angavu"}, "Manage alerts and notifications": {"en": "Manage alerts and notifications", "rw": "Gucunga impuruza n'amatangazo", "fr": "Gérer les alertes et notifications", "sw": "Simamia tahadhari na arifa"}, "Notification Sound": {"en": "Notification Sound", "rw": "Ijwi ry'amatangazo", "fr": "Son des notifications", "sw": "Sauti ya arifa"}, "Volume": {"en": "Volume", "rw": "Ijwi", "fr": "Volume", "sw": "Sauti"}, "Sound Type": {"en": "Sound Type", "rw": "Ubwoko bw'ijwi", "fr": "Type de son", "sw": "Aina ya sauti"}, "Chime": {"en": "Chime", "rw": "Ijwi rya Chime", "fr": "Carillon", "sw": "Mlio wa chime"}, "Bell": {"en": "Bell", "rw": "Inzogera", "fr": "Cloche", "sw": "Kengele"}, "Beep": {"en": "Beep", "rw": "Ijwi rigufi", "fr": "Bip", "sw": "Mlio mfupi"}, "Alert": {"en": "Alert", "rw": "Impuruza", "fr": "Alerte", "sw": "Tahadhari"}, "Approval alerts": {"en": "Approval alerts", "rw": "Impuruza z'uruhushya", "fr": "Alertes d'approbation", "sw": "Tahadhari za idhini"}, "Sound when admin approves or rejects": {"en": "Sound when admin approves or rejects", "rw": "Ijwi igihe admin yemeje cyangwa yanze", "fr": "Son quand l'admin approuve ou refuse", "sw": "Sauti admin anapoidhinisha au kukataa"}, "Debt reminders": {"en": "Debt reminders", "rw": "Kwibutsa amadeni", "fr": "Rappels de dettes", "sw": "Vikumbusho vya madeni"}, "Sound when a debt is due": {"en": "Sound when a debt is due", "rw": "Ijwi igihe ideni rigeze igihe", "fr": "Son quand une dette arrive à échéance", "sw": "Sauti deni linapofika muda wake"}, "New requests": {"en": "New requests", "rw": "Ubusabe bushya", "fr": "Nouvelles demandes", "sw": "Maombi mapya"}, "Sound when staff ask for approval": {"en": "Sound when staff ask for approval", "rw": "Ijwi igihe abakozi basabye uruhushya", "fr": "Son quand le personnel demande une approbation", "sw": "Sauti wafanyakazi wanapoomba idhini"}, "Browser Notifications": {"en": "Browser Notifications", "rw": "Amatangazo ya browser", "fr": "Notifications du navigateur", "sw": "Arifa za kivinjari"}, "Business Settings": {"en": "Business Settings", "rw": "Igenamiterere ry'ubucuruzi", "fr": "Paramètres de l'entreprise", "sw": "Mipangilio ya biashara"}, "Manage your business information": {"en": "Manage your business information", "rw": "Gucunga amakuru y'ubucuruzi", "fr": "Gérez les informations de votre entreprise", "sw": "Simamia taarifa za biashara yako"}, "Business Profile": {"en": "Business Profile", "rw": "Umwirondoro w'ubucuruzi", "fr": "Profil de l'entreprise", "sw": "Wasifu wa biashara"}, "Edit your business details": {"en": "Edit your business details", "rw": "Hindura amakuru y'ubucuruzi", "fr": "Modifier les détails de l'entreprise", "sw": "Hariri maelezo ya biashara"}, "Currency": {"en": "Currency", "rw": "Ifaranga", "fr": "Devise", "sw": "Sarafu"}, "Set your preferred currency": {"en": "Set your preferred currency", "rw": "Hitamo ifaranga ukunda", "fr": "Choisissez votre devise", "sw": "Chagua sarafu unayopenda"}, "Tax Settings": {"en": "Tax Settings", "rw": "Igenamiterere ry'imisoro", "fr": "Paramètres des taxes", "sw": "Mipangilio ya kodi"}, "Show VAT 18% on receipts": {"en": "Show VAT 18% on receipts", "rw": "Erekana VAT 18% kuri receipt", "fr": "Afficher la TVA 18% sur les reçus", "sw": "Onyesha VAT 18% kwenye risiti"}, "Data & Privacy": {"en": "Data & Privacy", "rw": "Amakuru n'ibanga", "fr": "Données et confidentialité", "sw": "Data na faragha"}, "Control your data and privacy for you": {"en": "Control your data and privacy for you", "rw": "Gucunga amakuru n'ibanga ryawe", "fr": "Contrôlez vos données et votre confidentialité", "sw": "Dhibiti data na faragha yako"}, "Backup & Restore": {"en": "Backup & Restore", "rw": "Kubika no Gusubiza", "fr": "Sauvegarde et restauration", "sw": "Hifadhi nakala na urejeshe"}, "Backup or restore your data": {"en": "Backup or restore your data", "rw": "Bika cyangwa usubize amakuru", "fr": "Sauvegarder ou restaurer vos données", "sw": "Hifadhi au rejesha data yako"}, "Auto Backup": {"en": "Auto Backup", "rw": "Kubika mu buryo bwikora", "fr": "Sauvegarde automatique", "sw": "Hifadhi nakala otomatiki"}, "Save your data automatically": {"en": "Save your data automatically", "rw": "Bika amakuru yawe mu buryo bwikora", "fr": "Enregistrer vos données automatiquement", "sw": "Hifadhi data yako kiotomatiki"}, "Clear Cache": {"en": "Clear Cache", "rw": "Siba cache", "fr": "Vider le cache", "sw": "Futa cache"}, "Clear Memo AI history": {"en": "Clear Memo AI history", "rw": "Siba amateka ya Memo AI", "fr": "Effacer l'historique de Memo AI", "sw": "Futa historia ya Memo AI"}, "Privacy Policy": {"en": "Privacy Policy", "rw": "Politiki y'ibanga", "fr": "Politique de confidentialité", "sw": "Sera ya faragha"}, "Read our privacy policy": {"en": "Read our privacy policy", "rw": "Soma politiki yacu y'ibanga", "fr": "Lisez notre politique de confidentialité", "sw": "Soma sera yetu ya faragha"}, "Terms of Service": {"en": "Terms of Service", "rw": "Amategeko yo gukoresha", "fr": "Conditions d'utilisation", "sw": "Masharti ya huduma"}, "Read our terms of service": {"en": "Read our terms of service", "rw": "Soma amategeko yo gukoresha", "fr": "Lisez nos conditions d'utilisation", "sw": "Soma masharti yetu ya huduma"}, "About": {"en": "About", "rw": "Ibyerekeye", "fr": "À propos", "sw": "Kuhusu"}, "App information and support": {"en": "App information and support", "rw": "Amakuru ya app n'ubufasha", "fr": "Informations et assistance", "sw": "Taarifa za programu na msaada"}, "App Version": {"en": "App Version", "rw": "Verisiyo ya app", "fr": "Version de l'application", "sw": "Toleo la programu"}, "Help & Support": {"en": "Help & Support", "rw": "Ubufasha", "fr": "Aide et assistance", "sw": "Msaada"}, "Get help or contact us": {"en": "Get help or contact us", "rw": "Bona ubufasha cyangwa uduhamagare", "fr": "Obtenir de l'aide ou nous contacter", "sw": "Pata msaada au wasiliana nasi"}, "Rate Us": {"en": "Rate Us", "rw": "Dutange amanota", "fr": "Notez-nous", "sw": "Tupe alama"}, "If you like our app, rate us": {"en": "If you like our app, rate us", "rw": "Nukunda app yacu, dutange amanota", "fr": "Si vous aimez notre application, notez-nous", "sw": "Ukipenda programu yetu, tupe alama"}, "Mobile Money Codes": {"en": "Mobile Money Codes", "rw": "Code za Mobile Money", "fr": "Codes Mobile Money", "sw": "Misimbo ya Mobile Money"}, "Login Screen Photo": {"en": "Login Screen Photo", "rw": "Ifoto yo kwinjira", "fr": "Photo de l'écran de connexion", "sw": "Picha ya skrini ya kuingia"}, "Photo shown on login & create account": {"en": "Photo shown on login & create account", "rw": "Ifoto igaragara ku kwinjira no gufungura konti", "fr": "Photo affichée à la connexion et à la création de compte", "sw": "Picha inayoonekana wakati wa kuingia na kufungua akaunti"}, "Documents and images": {"en": "Documents and images", "rw": "Inyandiko n'amashusho", "fr": "Documents et images", "sw": "Hati na picha"}, "Administration": {"en": "Administration", "rw": "Ubuyobozi", "fr": "Administration", "sw": "Usimamizi"}, "Admin Settings & Reports": {"en": "Admin Settings & Reports", "rw": "Igenamiterere rya Admin & Raporo", "fr": "Paramètres admin et rapports", "sw": "Mipangilio ya Admin na ripoti"}, "Reset Data": {"en": "Reset Data", "rw": "Subiza data uko yari", "fr": "Réinitialiser les données", "sw": "Weka upya data"}, "Product Categories": {"en": "Product Categories", "rw": "Ibyiciro by'ibicuruzwa", "fr": "Catégories de produits", "sw": "Kategoria za bidhaa"}, "Add, edit and save categories": {"en": "Add, edit and save categories", "rw": "Ongeramo, hindura no kubika ibyiciro", "fr": "Ajouter, modifier et enregistrer les catégories", "sw": "Ongeza, hariri na hifadhi kategoria"}, "Add and manage suppliers": {"en": "Add and manage suppliers", "rw": "Ongeramo kandi ucunge abatanga ibicuruzwa", "fr": "Ajouter et gérer les fournisseurs", "sw": "Ongeza na usimamie wasambazaji"}, "Open Memo AI": {"en": "Open Memo AI", "rw": "Fungura Memo AI", "fr": "Ouvrir Memo AI", "sw": "Fungua Memo AI"}, "AI is off on the dashboard but works here": {"en": "AI is off on the dashboard but works here", "rw": "AI ntigaragara kuri dashboard ariko ikorera hano", "fr": "L'IA n'est pas affichée sur le tableau de bord mais fonctionne ici", "sw": "AI haionekani kwenye dashibodi lakini inafanya kazi hapa"}, "Report": {"en": "Report", "rw": "Raporo (Report)", "fr": "Rapport", "sw": "Ripoti"}, "Send report to admin": {"en": "Send report to admin", "rw": "Ohereza Raporo kuri Admin", "fr": "Envoyer le rapport à l'admin", "sw": "Tuma ripoti kwa admin"}, "Play a sound when a notification arrives": {"en": "Play a sound when a notification arrives", "rw": "Ijwi iyo notification ije", "fr": "Jouer un son à l'arrivée d'une notification", "sw": "Cheza sauti notifikesheni inapofika"}, "Loudness of the sound": {"en": "Loudness of the sound", "rw": "Ijwi riri hejuru cyangwa hasi", "fr": "Niveau sonore", "sw": "Kiwango cha sauti"}, "Choose a sound and tap ▶ to listen": {"en": "Choose a sound and tap ▶ to listen", "rw": "Hitamo ijwi, ukande ▶ ukumve", "fr": "Choisissez un son et appuyez sur ▶ pour l'écouter", "sw": "Chagua sauti kisha bonyeza ▶ uisikilize"}, "Browser notification when the app is open": {"en": "Browser notification when the app is open", "rw": "Notification ya browser iyo app ifunguye", "fr": "Notification du navigateur quand l'application est ouverte", "sw": "Arifa ya kivinjari programu ikiwa wazi"}, "MTN and Airtel payment codes": {"en": "MTN and Airtel payment codes", "rw": "MTN na Airtel codes zo kwishyura", "fr": "Codes de paiement MTN et Airtel", "sw": "Misimbo ya malipo ya MTN na Airtel"}, "Control your data and privacy": {"en": "Control your data and privacy", "rw": "Gucunga amakuru n'ibanga ryawe", "fr": "Contrôlez vos données et votre confidentialité", "sw": "Dhibiti data na faragha yako"}, "Clear": {"en": "Clear", "rw": "Siba", "fr": "Vider", "sw": "Futa"}, "Home": {"en": "Home", "rw": "Ahabanza", "fr": "Accueil", "sw": "Nyumbani"}, "Customers can visit and view products": {"en": "Customers can visit and view products", "rw": "Abakiriya bashobora gusura no kureba ibicuruzwa", "fr": "Les clients peuvent visiter et voir les produits", "sw": "Wateja wanaweza kutembelea na kuona bidhaa"}, "Account created": {"en": "Account created", "rw": "Konti yafunguwe", "fr": "Compte créé", "sw": "Akaunti imefunguliwa"}, "Add Customer": {"en": "Add Customer", "rw": "Ongeramo umukiriya", "fr": "Ajouter un client", "sw": "Ongeza mteja"}, "Add New Sale": {"en": "Add New Sale", "rw": "Ongeramo igurisha rishya", "fr": "Nouvelle vente", "sw": "Ongeza mauzo mapya"}, "Add Sale": {"en": "Add Sale", "rw": "Ongeramo igurisha", "fr": "Ajouter une vente", "sw": "Ongeza mauzo"}, "Avg. Order": {"en": "Avg. Order", "rw": "Igiteranyo cy'ikigura", "fr": "Panier moyen", "sw": "Wastani wa oda"}, "Bank Transfer": {"en": "Bank Transfer", "rw": "Kohereza muri banki", "fr": "Virement bancaire", "sw": "Uhamisho wa benki"}, "Save as new customer": {"en": "Save as new customer", "rw": "Bika nka customer mushya", "fr": "Enregistrer comme nouveau client", "sw": "Hifadhi kama mteja mpya"}, "Card": {"en": "Card", "rw": "Ikarita", "fr": "Carte", "sw": "Kadi"}, "Cart": {"en": "Cart", "rw": "Agaseke", "fr": "Panier", "sw": "Kikapu"}, "Cart is empty. Tap ＋ on a product": {"en": "Cart is empty. Tap ＋ on a product", "rw": "Agaseke kari ubusa. Kanda ＋ ku gicuruzwa", "fr": "Le panier est vide. Appuyez sur ＋ sur un produit", "sw": "Kikapu kiko tupu. Bonyeza ＋ kwenye bidhaa"}, "Cash": {"en": "Cash", "rw": "Amafaranga mu ntoki", "fr": "Espèces", "sw": "Taslimu"}, "Clear all": {"en": "Clear all", "rw": "Siba byose", "fr": "Tout effacer", "sw": "Futa zote"}, "Communication": {"en": "Communication", "rw": "Itumanaho", "fr": "Communication", "sw": "Mawasiliano"}, "Complete Sale": {"en": "Complete Sale", "rw": "Emeza igurisha", "fr": "Finaliser la vente", "sw": "Kamilisha mauzo"}, "Completed": {"en": "Completed", "rw": "Byarangiye", "fr": "Terminé", "sw": "Imekamilika"}, "Or type a new customer": {"en": "Or type a new customer", "rw": "Cyangwa andika customer mushya", "fr": "Ou saisissez un nouveau client", "sw": "Au andika mteja mpya"}, "Discount": {"en": "Discount", "rw": "Igabanyirizwa", "fr": "Remise", "sw": "Punguzo"}, "Emoji": {"en": "Emoji", "rw": "Emoji", "fr": "Emoji", "sw": "Emoji"}, "Expense List": {"en": "Expense List", "rw": "Urutonde rw'amafaranga yakoreshejwe", "fr": "Liste des dépenses", "sw": "Orodha ya matumizi"}, "Expense Summary": {"en": "Expense Summary", "rw": "Incamake y'amafaranga yakoreshejwe", "fr": "Résumé des dépenses", "sw": "Muhtasari wa matumizi"}, "Expenses by Category": {"en": "Expenses by Category", "rw": "Amafaranga ukurikije icyiciro", "fr": "Dépenses par catégorie", "sw": "Matumizi kwa kategoria"}, "Mon": {"en": "Mon", "rw": "Ku wa mbere", "fr": "Lun", "sw": "Jumatatu"}, "Tue": {"en": "Tue", "rw": "Ku wa kabiri", "fr": "Mar", "sw": "Jumanne"}, "Wed": {"en": "Wed", "rw": "Ku wa gatatu", "fr": "Mer", "sw": "Jumatano"}, "Thu": {"en": "Thu", "rw": "Ku wa kane", "fr": "Jeu", "sw": "Alhamisi"}, "Fri": {"en": "Fri", "rw": "Ku wa gatanu", "fr": "Ven", "sw": "Ijumaa"}, "Sat": {"en": "Sat", "rw": "Ku wa gatandatu", "fr": "Sam", "sw": "Jumamosi"}, "Sun": {"en": "Sun", "rw": "Ku cyumweru", "fr": "Dim", "sw": "Jumapili"}, "Choose an existing customer": {"en": "Choose an existing customer", "rw": "Hitamo customer usanzwe ufite", "fr": "Choisir un client existant", "sw": "Chagua mteja aliyepo"}, "Choose a category": {"en": "Choose a category", "rw": "Hitamo icyiciro", "fr": "Choisir une catégorie", "sw": "Chagua kategoria"}, "In Stock": {"en": "In Stock", "rw": "Ibiri muri stock", "fr": "En stock", "sw": "Zipo"}, "Low Stock": {"en": "Low Stock", "rw": "Bigiye gushira", "fr": "Stock faible", "sw": "Hisa ndogo"}, "Invoice": {"en": "Invoice", "rw": "Fagitire", "fr": "Facture", "sw": "Ankara"}, "Last Month": {"en": "Last Month", "rw": "Ukwezi gushize", "fr": "Mois dernier", "sw": "Mwezi uliopita"}, "Last Year": {"en": "Last Year", "rw": "Umwaka ushize", "fr": "Année dernière", "sw": "Mwaka uliopita"}, "Manage all your customers": {"en": "Manage all your customers", "rw": "Gucunga abakiriya bawe bose", "fr": "Gérez tous vos clients", "sw": "Simamia wateja wako wote"}, "Manage your sales and track your revenue": {"en": "Manage your sales and track your revenue", "rw": "Gucunga igurisha kandi ukurikirane amafaranga winjiza", "fr": "Gérez vos ventes et suivez votre chiffre d'affaires", "sw": "Simamia mauzo na ufuatilie mapato yako"}, "Meals": {"en": "Meals", "rw": "Ibyo kurya", "fr": "Repas", "sw": "Chakula"}, "Memo AI": {"en": "Memo AI", "rw": "Memo AI", "fr": "Memo AI", "sw": "Memo AI"}, "Mobile Money": {"en": "Mobile Money", "rw": "Mobile Money", "fr": "Mobile Money", "sw": "Mobile Money"}, "Navigator": {"en": "Navigator", "rw": "Navigator", "fr": "Navigateur", "sw": "Navigator"}, "Notes (optional": {"en": "Notes (optional", "rw": "Ibisobanuro (si ngombwa", "fr": "Notes (facultatif", "sw": "Maelezo (si lazima"}, "No pack/box added": {"en": "No pack/box added", "rw": "Nta pack/box yongeweho", "fr": "Aucun pack/boîte ajouté", "sw": "Hakuna pakiti/sanduku lililoongezwa"}, "No supplier": {"en": "No supplier", "rw": "Nta supplier", "fr": "Aucun fournisseur", "sw": "Hakuna msambazaji"}, "Office Supplies": {"en": "Office Supplies", "rw": "Ibikoresho byo mu biro", "fr": "Fournitures de bureau", "sw": "Vifaa vya ofisi"}, "Orders": {"en": "Orders", "rw": "Ibicuruzwa byatumijwe", "fr": "Commandes", "sw": "Oda"}, "Other": {"en": "Other", "rw": "Ikindi", "fr": "Autre", "sw": "Nyingine"}, "Others": {"en": "Others", "rw": "Ibindi", "fr": "Autres", "sw": "Nyingine"}, "Pack / Dozen / Box / Bag": {"en": "Pack / Dozen / Box / Bag", "rw": "Pack / Dozen / Box / Bag", "fr": "Pack / Douzaine / Boîte / Sac", "sw": "Pakiti / Dazani / Sanduku / Mfuko"}, "Payment Method": {"en": "Payment Method", "rw": "Uburyo bwo kwishyura", "fr": "Mode de paiement", "sw": "Njia ya malipo"}, "Payment Status": {"en": "Payment Status", "rw": "Imiterere yo kwishyura", "fr": "Statut du paiement", "sw": "Hali ya malipo"}, "Pending": {"en": "Pending", "rw": "Biracyategereje", "fr": "En attente", "sw": "Inasubiri"}, "Public Shop": {"en": "Public Shop", "rw": "Iduka rusange", "fr": "Boutique publique", "sw": "Duka la umma"}, "Recent Expenses": {"en": "Recent Expenses", "rw": "Amafaranga yakoreshejwe vuba", "fr": "Dépenses récentes", "sw": "Matumizi ya hivi karibuni"}, "Record a new sale and generate receipt": {"en": "Record a new sale and generate receipt", "rw": "Andika igurisha rishya kandi utange receipt", "fr": "Enregistrez une nouvelle vente et générez un reçu", "sw": "Rekodi mauzo mapya na utoe risiti"}, "Remaining Budget": {"en": "Remaining Budget", "rw": "Ingengo isigaye", "fr": "Budget restant", "sw": "Bajeti iliyobaki"}, "Rent": {"en": "Rent", "rw": "Ubukode", "fr": "Loyer", "sw": "Kodi ya nyumba"}, "Repairs": {"en": "Repairs", "rw": "Gusana", "fr": "Réparations", "sw": "Matengenezo"}, "Sale yabitswe": {"en": "Sale yabitswe", "rw": "Sale yabitswe", "fr": "Vente enregistrée", "sw": "Mauzo yahifadhiwa"}, "Sales • This month": {"en": "Sales • This month", "rw": "Igurisha • Uku kwezi", "fr": "Ventes • Ce mois", "sw": "Mauzo • Mwezi huu"}, "Save as Draft": {"en": "Save as Draft", "rw": "Bika nk'icyitegererezo", "fr": "Enregistrer comme brouillon", "sw": "Hifadhi kama rasimu"}, "Show on Dashboard (Featured": {"en": "Show on Dashboard (Featured", "rw": "Shyira ku Dashboard (Featured", "fr": "Afficher sur le tableau de bord (vedette", "sw": "Onyesha kwenye dashibodi (Iliyoangaziwa"}, "Smart Business Assistant": {"en": "Smart Business Assistant", "rw": "Umufasha w'ubucuruzi bwubwenge", "fr": "Assistant commercial intelligent", "sw": "Msaidizi mahiri wa biashara"}, "Stock (pieces": {"en": "Stock (pieces", "rw": "Stock (pieces", "fr": "Stock (pièces", "sw": "Hisa (vipande"}, "Subtotal": {"en": "Subtotal", "rw": "Igiteranyo cy'ibanze", "fr": "Sous-total", "sw": "Jumla ndogo"}, "The pack price is calculated automatically (pieces × piece price). You can edit it; ↺ Auto restores it": {"en": "The pack price is calculated automatically (pieces × piece price). You can edit it; ↺ Auto restores it", "rw": "Igiciro cya pack kibarwa ubwacyo (pieces × igiciro cya piece). Ushobora kugihindura; ↺ Auto ikigarura", "fr": "Le prix du pack est calculé automatiquement (pièces × prix de la pièce). Vous pouvez le modifier ; ↺ Auto le rétablit", "sw": "Bei ya pakiti inahesabiwa yenyewe (vipande × bei ya kipande). Unaweza kuibadilisha; ↺ Auto inarejesha"}, "This Month": {"en": "This Month", "rw": "Uku kwezi", "fr": "Ce mois", "sw": "Mwezi huu"}, "This Year": {"en": "This Year", "rw": "Uyu mwaka", "fr": "Cette année", "sw": "Mwaka huu"}, "Total Expenses": {"en": "Total Expenses", "rw": "Amafaranga yose yakoreshejwe", "fr": "Total des dépenses", "sw": "Jumla ya matumizi"}, "Total Sales": {"en": "Total Sales", "rw": "Igurisha ryose", "fr": "Total des ventes", "sw": "Jumla ya mauzo"}, "Track and manage your business expenses": {"en": "Track and manage your business expenses", "rw": "Kurikirana kandi ucunge amafaranga yakoreshejwe", "fr": "Suivez et gérez les dépenses de votre entreprise", "sw": "Fuatilia na usimamie matumizi ya biashara yako"}, "Transport": {"en": "Transport", "rw": "Ingendo", "fr": "Transport", "sw": "Usafiri"}, "Utilities": {"en": "Utilities", "rw": "Ibikoresho (amazi/umuriro)", "fr": "Services publics", "sw": "Huduma za umma"}, "Videos": {"en": "Videos", "rw": "Amavidewo", "fr": "Vidéos", "sw": "Video"}, "Walk-in Customer": {"en": "Walk-in Customer", "rw": "Umukiriya utaje asanzwe", "fr": "Client de passage", "sw": "Mteja wa kawaida"}, "Walk-in / New customer": {"en": "Walk-in / New customer", "rw": "Walk-in / Customer mushya", "fr": "Passage / Nouveau client", "sw": "Mpita njia / Mteja mpya"}, "vs last month": {"en": "vs last month", "rw": "ugereranyije n'ukwezi gushize", "fr": "vs mois dernier", "sw": "dhidi ya mwezi uliopita"}, "vs yesterday": {"en": "vs yesterday", "rw": "ugereranyije n'ejo", "fr": "vs hier", "sw": "dhidi ya jana"}, "Dashboard": {"en": "Dashboard", "rw": "Dashboard", "fr": "Tableau de bord", "sw": "Dashibodi"}, "Walk-in / Customer mushya": {"en": "Walk-in / Customer mushya", "rw": "Walk-in / Customer mushya", "fr": "Passage / Nouveau client", "sw": "Mpita njia / Mteja mpya"}, "Hitamo customer usanzwe ufite": {"en": "Hitamo customer usanzwe ufite", "rw": "Hitamo customer usanzwe ufite", "fr": "Choisir un client existant", "sw": "Chagua mteja aliyepo"}, "Partial": {"en": "Partial", "rw": "Igice", "fr": "Partiel", "sw": "Sehemu"}, "Profit": {"en": "Profit", "rw": "Inyungu", "fr": "Bénéfice", "sw": "Faida"}, "Sale": {"en": "Sale", "rw": "Igurisha", "fr": "Vente", "sw": "Mauzo"}, "Rwanda": {"en": "Rwanda", "rw": "Rwanda", "fr": "Rwanda", "sw": "Rwanda"}, "CSV": {"en": "CSV", "rw": "CSV", "fr": "CSV", "sw": "CSV"}, "Add Category": {"en": "Add Category", "rw": "Ongeramo icyiciro", "fr": "Ajouter une catégorie", "sw": "Ongeza kategoria"}, "Add Expense": {"en": "Add Expense", "rw": "Ongeramo expense", "fr": "Ajouter une dépense", "sw": "Ongeza matumizi"}, "Add User": {"en": "Add User", "rw": "Ongeramo user", "fr": "Ajouter un utilisateur", "sw": "Ongeza mtumiaji"}, "Add stock": {"en": "Add stock", "rw": "Ongeramo stock", "fr": "Ajouter du stock", "sw": "Ongeza hisa"}, "Admin Settings": {"en": "Admin Settings", "rw": "Igenamiterere rya Admin", "fr": "Paramètres admin", "sw": "Mipangilio ya Admin"}, "Admin code / number": {"en": "Admin code / number", "rw": "Code / numero ya Admin", "fr": "Code / numéro de l'admin", "sw": "Msimbo / namba ya Admin"}, "Administrator": {"en": "Administrator", "rw": "Administrator", "fr": "Administrateur", "sw": "Msimamizi"}, "Location / What they supply": {"en": "Location / What they supply", "rw": "Aho aherereye / Icyo atanga", "fr": "Lieu / Ce qu'il fournit", "sw": "Mahali / Anachotoa"}, "Airtel Money": {"en": "Airtel Money", "rw": "Airtel Money", "fr": "Airtel Money", "sw": "Airtel Money"}, "Amount (RWF": {"en": "Amount (RWF", "rw": "Amafaranga (RWF", "fr": "Montant (RWF", "sw": "Kiasi (RWF"}, "Approve": {"en": "Approve", "rw": "Emeza", "fr": "Approuver", "sw": "Idhinisha"}, "Auto": {"en": "Auto", "rw": "Auto", "fr": "Auto", "sw": "Auto"}, "Backup includes all data (including passwords). Keep it somewhere safe": {"en": "Backup includes all data (including passwords). Keep it somewhere safe", "rw": "Backup irimo data yose (harimo na passwords). Yibike ahantu hizewe", "fr": "La sauvegarde contient toutes les données (y compris les mots de passe). Gardez-la en lieu sûr", "sw": "Hifadhi nakala ina data yote (pamoja na nenosiri). Iweke mahali salama"}, "Business Name": {"en": "Business Name", "rw": "Izina ry'ubucuruzi", "fr": "Nom de l'entreprise", "sw": "Jina la biashara"}, "Cancel": {"en": "Cancel", "rw": "Reka", "fr": "Annuler", "sw": "Ghairi"}, "Cashier": {"en": "Cashier", "rw": "Cashier", "fr": "Caissier", "sw": "Mhudumu wa fedha"}, "Close": {"en": "Close", "rw": "Funga", "fr": "Fermer", "sw": "Funga"}, "Confirm new password": {"en": "Confirm new password", "rw": "Emeza password nshya", "fr": "Confirmer le nouveau mot de passe", "sw": "Thibitisha nenosiri jipya"}, "Copy backup": {"en": "Copy backup", "rw": "Koporora backup", "fr": "Copier la sauvegarde", "sw": "Nakili hifadhi nakala"}, "Copy message": {"en": "Copy message", "rw": "Koporora ubutumwa", "fr": "Copier le message", "sw": "Nakili ujumbe"}, "Create": {"en": "Create", "rw": "Kora", "fr": "Créer", "sw": "Unda"}, "Current password": {"en": "Current password", "rw": "Password y'ubu", "fr": "Mot de passe actuel", "sw": "Nenosiri la sasa"}, "Description": {"en": "Description", "rw": "Ibisobanuro", "fr": "Description", "sw": "Maelezo"}, "Edit": {"en": "Edit", "rw": "Hindura", "fr": "Modifier", "sw": "Hariri"}, "Email or Phone": {"en": "Email or Phone", "rw": "Email cyangwa Telefone", "fr": "Email ou téléphone", "sw": "Barua pepe au simu"}, "Folder name": {"en": "Folder name", "rw": "Izina ry'ububiko", "fr": "Nom du dossier", "sw": "Jina la folda"}, "Full Name": {"en": "Full Name", "rw": "Amazina yuzuye", "fr": "Nom complet", "sw": "Jina kamili"}, "Fungura SMS": {"en": "Fungura SMS", "rw": "Fungura SMS", "fr": "Ouvrir SMS", "sw": "Fungua SMS"}, "Gusaba amafaranga": {"en": "Gusaba amafaranga", "rw": "Gusaba amafaranga", "fr": "Demande d'argent", "sw": "Ombi la fedha"}, "Gusaba stock": {"en": "Gusaba stock", "rw": "Gusaba stock", "fr": "Demande de stock", "sw": "Ombi la hisa"}, "Icyiciro gishya": {"en": "Icyiciro gishya", "rw": "Icyiciro gishya", "fr": "Nouvelle catégorie", "sw": "Kategoria mpya"}, "What you want to tell / ask the admin": {"en": "What you want to tell / ask the admin", "rw": "Icyo ushaka kubwira / gusaba Admin", "fr": "Ce que vous voulez dire / demander à l'admin", "sw": "Unachotaka kumwambia / kuomba admin"}, "Question / Other": {"en": "Question / Other", "rw": "Ikibazo / Ubundi", "fr": "Question / Autre", "sw": "Swali / Nyingine"}, "Kinyarwanda": {"en": "Kinyarwanda", "rw": "Kinyarwanda", "fr": "Kinyarwanda", "sw": "Kinyarwanda"}, "Kiswahili": {"en": "Kiswahili", "rw": "Kiswahili", "fr": "Kiswahili", "sw": "Kiswahili"}, "English": {"en": "English", "rw": "English", "fr": "English", "sw": "English"}, "Français": {"en": "Français", "rw": "Français", "fr": "Français", "sw": "Français"}, "Location": {"en": "Location", "rw": "Aho aherereye", "fr": "Emplacement", "sw": "Mahali"}, "Login screen photo": {"en": "Login screen photo", "rw": "Ifoto yo kwinjira", "fr": "Photo de l'écran de connexion", "sw": "Picha ya skrini ya kuingia"}, "MTN MoMo": {"en": "MTN MoMo", "rw": "MTN MoMo", "fr": "MTN MoMo", "sw": "MTN MoMo"}, "MTN MoMo: not set up": {"en": "MTN MoMo: not set up", "rw": "MTN MoMo: ntiyashyizweho", "fr": "MTN MoMo : non configuré", "sw": "MTN MoMo: haijawekwa"}, "Manage users, requests and reports": {"en": "Manage users, requests and reports", "rw": "Gucunga abakozi, ubusabe na raporo", "fr": "Gérer les utilisateurs, demandes et rapports", "sw": "Simamia watumiaji, maombi na ripoti"}, "Manager": {"en": "Manager", "rw": "Manager", "fr": "Gestionnaire", "sw": "Meneja"}, "Merchant code": {"en": "Merchant code", "rw": "Code y'ubucuruzi", "fr": "Code marchand", "sw": "Msimbo wa biashara"}, "Mobile Money receiving": {"en": "Mobile Money receiving", "rw": "Kwakira Mobile Money", "fr": "Réception Mobile Money", "sw": "Kupokea Mobile Money"}, "No photos yet": {"en": "No photos yet", "rw": "Nta mafoto ahari", "fr": "Aucune photo pour l'instant", "sw": "Hakuna picha bado"}, "Ohereza": {"en": "Ohereza", "rw": "Ohereza", "fr": "Envoyer", "sw": "Tuma"}, "Ohereza kuri Admin": {"en": "Ohereza kuri Admin", "rw": "Ohereza kuri Admin", "fr": "Envoyer à l'admin", "sw": "Tuma kwa admin"}, "Only the admin sets these. Staff see them automatically when taking MoMo payments. In the USSD text use {code}, {number} and {amount": {"en": "Only the admin sets these. Staff see them automatically when taking MoMo payments. In the USSD text use {code}, {number} and {amount", "rw": "Admin wenyine ni we ubishyiraho. Abakozi babibona ubwabyo bakira MoMo. Muri USSD koresha {code}, {number} na {amount", "fr": "Seul l'admin les définit. Le personnel les voit automatiquement lors des paiements MoMo. Dans le texte USSD, utilisez {code}, {number} et {amount", "sw": "Admin pekee ndiye anaziweka. Wafanyakazi wanaziona kiotomatiki wanapopokea MoMo. Katika USSD tumia {code}, {number} na {amount"}, "Oya, Cancel": {"en": "Oya, Cancel", "rw": "Oya, Reka", "fr": "Non, annuler", "sw": "Hapana, ghairi"}, "Password": {"en": "Password", "rw": "Password", "fr": "Mot de passe", "sw": "Nenosiri"}, "Paste backup": {"en": "Paste backup", "rw": "Paste backup", "fr": "Coller la sauvegarde", "sw": "Bandika hifadhi nakala"}, "Pay with": {"en": "Pay with", "rw": "Kwishyura ukoresheje", "fr": "Payer avec", "sw": "Lipa kwa"}, "Phone": {"en": "Phone", "rw": "Telefone", "fr": "Téléphone", "sw": "Simu"}, "Phone number": {"en": "Phone number", "rw": "Numero ya telefone", "fr": "Numéro de téléphone", "sw": "Namba ya simu"}, "Photo": {"en": "Photo", "rw": "Ifoto", "fr": "Photo", "sw": "Picha"}, "Quantity": {"en": "Quantity", "rw": "Umubare", "fr": "Quantité", "sw": "Kiasi"}, "Raporo y'umunsi": {"en": "Raporo y'umunsi", "rw": "Raporo y'umunsi", "fr": "Rapport du jour", "sw": "Ripoti ya siku"}, "Reason": {"en": "Reason", "rw": "Impamvu", "fr": "Raison", "sw": "Sababu"}, "Reject": {"en": "Reject", "rw": "Anga", "fr": "Refuser", "sw": "Kataa"}, "Remove photo": {"en": "Remove photo", "rw": "Kuraho ifoto", "fr": "Supprimer la photo", "sw": "Ondoa picha"}, "Remove stock": {"en": "Remove stock", "rw": "Kuramo stock", "fr": "Retirer du stock", "sw": "Ondoa hisa"}, "Requests": {"en": "Requests", "rw": "Ubusabe", "fr": "Demandes", "sw": "Maombi"}, "Restore": {"en": "Restore", "rw": "Subiza", "fr": "Restaurer", "sw": "Rejesha"}, "Restore: paste backup hano": {"en": "Restore: paste backup hano", "rw": "Subiza: paste backup hano", "fr": "Restaurer : collez la sauvegarde ici", "sw": "Rejesha: bandika hifadhi nakala hapa"}, "Role": {"en": "Role", "rw": "Uruhare", "fr": "Rôle", "sw": "Jukumu"}, "Saba Admin Gutanga Expense": {"en": "Saba Admin Gutanga Expense", "rw": "Saba Admin Gutanga Expense", "fr": "Demander à l'admin d'ajouter une dépense", "sw": "Omba Admin aongeze matumizi"}, "Request a change (Request Edit": {"en": "Request a change (Request Edit", "rw": "Saba Guhindura Ibirimo (Request Edit", "fr": "Demander une modification (Request Edit", "sw": "Omba mabadiliko (Request Edit"}, "Sales Person": {"en": "Sales Person", "rw": "Umuyuza", "fr": "Vendeur", "sw": "Muuzaji"}, "Save": {"en": "Save", "rw": "Bika", "fr": "Enregistrer", "sw": "Hifadhi"}, "Search action, person or detail": {"en": "Search action, person or detail", "rw": "Shakisha igikorwa, umuntu cyangwa ibisobanuro", "fr": "Rechercher une action, une personne ou un détail", "sw": "Tafuta kitendo, mtu au maelezo"}, "Search by product name or code": {"en": "Search by product name or code", "rw": "Shakisha ku izina cyangwa code y'igicuruzwa", "fr": "Rechercher par nom ou code produit", "sw": "Tafuta kwa jina au msimbo wa bidhaa"}, "Search files": {"en": "Search files", "rw": "Shakisha dosiye", "fr": "Rechercher des fichiers", "sw": "Tafuta faili"}, "Search product": {"en": "Search product", "rw": "Shakisha igicuruzwa", "fr": "Rechercher un produit", "sw": "Tafuta bidhaa"}, "Search products": {"en": "Search products", "rw": "Shakisha ibicuruzwa", "fr": "Rechercher des produits", "sw": "Tafuta bidhaa"}, "Search supplier": {"en": "Search supplier", "rw": "Shakisha utanga ibicuruzwa", "fr": "Rechercher un fournisseur", "sw": "Tafuta msambazaji"}, "Set now": {"en": "Set now", "rw": "Shyiraho ubu", "fr": "Configurer maintenant", "sw": "Weka sasa"}, "Set the receiving code or number in Settings → Mobile Money": {"en": "Set the receiving code or number in Settings → Mobile Money", "rw": "Shyiraho code cyangwa numero yo kwakira muri Settings → Mobile Money", "fr": "Définissez le code ou le numéro de réception dans Paramètres → Mobile Money", "sw": "Weka msimbo au namba ya kupokea kwenye Mipangilio → Mobile Money"}, "Stock Keeper": {"en": "Stock Keeper", "rw": "Stock Keeper", "fr": "Magasinier", "sw": "Mlinzi wa hisa"}, "This photo appears on the login and create-account screens": {"en": "This photo appears on the login and create-account screens", "rw": "Iyi foto igaragara kuri login na create account", "fr": "Cette photo apparaît sur les écrans de connexion et de création de compte", "sw": "Picha hii inaonekana kwenye skrini za kuingia na kufungua akaunti"}, "Type": {"en": "Type", "rw": "Ubwoko", "fr": "Type", "sw": "Aina"}, "Type your question": {"en": "Type your question", "rw": "Andika ikibazo cyawe", "fr": "Tapez votre question", "sw": "Andika swali lako"}, "USSD (code": {"en": "USSD (code", "rw": "USSD (code", "fr": "USSD (code", "sw": "USSD (msimbo"}, "USSD (number": {"en": "USSD (number", "rw": "USSD (numero", "fr": "USSD (numéro", "sw": "USSD (namba"}, "Need help? Use \"Send report\" or \"Request\" to send a message to the admin, or ask Memo AI": {"en": "Need help? Use \"Send report\" or \"Request\" to send a message to the admin, or ask Memo AI", "rw": "Ukeneye ubufasha? Koresha \"Ohereza Raporo\" cyangwa \"Request\" kugira ngo ubutumwa bugere kuri Admin, cyangwa ubaze Memo AI", "fr": "Besoin d'aide ? Utilisez « Envoyer le rapport » ou « Request » pour écrire à l'admin, ou demandez à Memo AI", "sw": "Unahitaji msaada? Tumia \"Tuma ripoti\" au \"Request\" kumtumia admin ujumbe, au umuulize Memo AI"}, "Update": {"en": "Update", "rw": "Vugurura", "fr": "Mettre à jour", "sw": "Sasisha"}, "Update Stock": {"en": "Update Stock", "rw": "Vugurura stock", "fr": "Mettre à jour le stock", "sw": "Sasisha hisa"}, "e.g. Change the selling price": {"en": "e.g. Change the selling price", "rw": "Urugero: Hindura igiciro cyo kugurisha", "fr": "Ex. : modifier le prix de vente", "sw": "Mfano: Badilisha bei ya kuuza"}, "e.g. New additions": {"en": "e.g. New additions", "rw": "Urugero: Ibiyongewe bishya", "fr": "Ex. : nouveaux ajouts", "sw": "Mfano: Nyongeza mpya"}, "e.g. I need to increase sugar stock": {"en": "e.g. I need to increase sugar stock", "rw": "Urugero: Nkeneye kongera stock y'isukari", "fr": "Ex. : je dois augmenter le stock de sucre", "sw": "Mfano: Nahitaji kuongeza hisa ya sukari"}, "e.g. I need to pay for water": {"en": "e.g. I need to pay for water", "rw": "Urugero: Nkeneye kwishyura amazi", "fr": "Ex. : je dois payer l'eau", "sw": "Mfano: Nahitaji kulipia maji"}, "Describe your request": {"en": "Describe your request", "rw": "Sobanura ubusabe bwawe", "fr": "Décrivez votre demande", "sw": "Eleza ombi lako"}, "User Management": {"en": "User Management", "rw": "Gucunga abakozi", "fr": "Gestion des utilisateurs", "sw": "Usimamizi wa watumiaji"}, "Users": {"en": "Users", "rw": "Abakozi", "fr": "Utilisateurs", "sw": "Watumiaji"}, "View details": {"en": "View details", "rw": "Reba ibisobanuro", "fr": "Voir les détails", "sw": "Ona maelezo"}, "WhatsApp": {"en": "WhatsApp", "rw": "WhatsApp", "fr": "WhatsApp", "sw": "WhatsApp"}, "Yes, confirm": {"en": "Yes, confirm", "rw": "Yego, Emeza", "fr": "Oui, confirmer", "sw": "Ndiyo, thibitisha"}, "Telefone": {"en": "Telefone", "rw": "Telefone", "fr": "Téléphone", "sw": "Simu"}, "Ubwoko": {"en": "Ubwoko", "rw": "Ubwoko", "fr": "Type", "sw": "Aina"}, "Logout": {"en": "Logout", "rw": "Sohoka", "fr": "Déconnexion", "sw": "Toka"}, "Notifications": {"en": "Notifications", "rw": "Amatangazo", "fr": "Notifications", "sw": "Arifa"}, "New approval request": {"en": "New approval request", "rw": "Ubusabe bushya bw'uruhushya", "fr": "Nouvelle demande d'approbation", "sw": "Ombi jipya la idhini"}, "Describe what you want to change on": {"en": "Describe what you want to change on", "rw": "Sobanura icyo usaba guhindura kuri", "fr": "Décrivez ce que vous voulez modifier sur", "sw": "Eleza unachotaka kubadilisha kwenye"}, "Scan product": {"en": "Scan product", "rw": "Scan igicuruzwa", "fr": "Scan produit", "sw": "Changanua bidhaa"}, "Or type or scan the code": {"en": "Or type or scan the code", "rw": "Cyangwa andika cyangwa scan code", "fr": "Ou saisissez ou scannez le code", "sw": "Au andika au changanua msimbo"}, "Camera scanning is not available here (use the installed app on your phone). You can still type the code or use a barcode scanner.": {"en": "Camera scanning is not available here (use the installed app on your phone). You can still type the code or use a barcode scanner.", "rw": "Gusoma kamera ntibishoboka hano (koresha app yashyizwe kuri telefone). Ushobora kwandika code cyangwa gukoresha scanner.", "fr": "Le scan par caméra n'est pas disponible ici (utilisez l'application installée sur votre téléphone). Vous pouvez saisir le code ou utiliser un lecteur.", "sw": "Kuchanganua kwa kamera hakupatikani hapa (tumia programu iliyowekwa kwenye simu). Bado unaweza kuandika msimbo au kutumia kichanganuzi."}, "Point the camera at the barcode": {"en": "Point the camera at the barcode", "rw": "Lenga kamera ku barcode", "fr": "Pointez la caméra vers le code-barres", "sw": "Elekeza kamera kwenye barcode"}, "Camera permission denied or not available. Type the code instead.": {"en": "Camera permission denied or not available. Type the code instead.", "rw": "Kamera ntiyemewe cyangwa ntiboneka. Andika code.", "fr": "Caméra refusée ou indisponible. Saisissez le code.", "sw": "Ruhusa ya kamera imekataliwa au haipatikani. Andika msimbo."}, "Product not found: ": {"en": "Product not found: ", "rw": "Ntabwo igicuruzwa kiboneka: ", "fr": "Produit introuvable : ", "sw": "Bidhaa haipatikani: "}, "Product not found": {"en": "Product not found", "rw": "Igicuruzwa ntikiboneka", "fr": "Produit introuvable", "sw": "Bidhaa haipatikani"}, "Product is out of stock": {"en": "Product is out of stock", "rw": "Igicuruzwa cyashize muri stock", "fr": "Le produit est en rupture de stock", "sw": "Bidhaa imeisha kwenye hifadhi"}, "Added to cart": {"en": "Added to cart", "rw": "Cyongewe mu gaseke", "fr": "Ajouté au panier", "sw": "Kimeongezwa kwenye kikapu"}, "Add Employee": {"en": "Add Employee", "rw": "Ongeramo umukozi", "fr": "Ajouter un employé", "sw": "Ongeza mfanyakazi"}, "Edit Employee": {"en": "Edit Employee", "rw": "Hindura umukozi", "fr": "Modifier l'employé", "sw": "Hariri mfanyakazi"}, "Update Employee": {"en": "Update Employee", "rw": "Hindura umukozi", "fr": "Mettre à jour l'employé", "sw": "Sasisha mfanyakazi"}, "Permissions": {"en": "Permissions", "rw": "Uburenganzira", "fr": "Autorisations", "sw": "Ruhusa"}, "Add Sales": {"en": "Add Sales", "rw": "Ongeramo igurisha", "fr": "Ajouter des ventes", "sw": "Ongeza mauzo"}, "View Sales": {"en": "View Sales", "rw": "Reba igurisha", "fr": "Voir les ventes", "sw": "Tazama mauzo"}, "Add Products": {"en": "Add Products", "rw": "Ongeramo ibicuruzwa", "fr": "Ajouter des produits", "sw": "Ongeza bidhaa"}, "Edit Products": {"en": "Edit Products", "rw": "Hindura ibicuruzwa", "fr": "Modifier les produits", "sw": "Hariri bidhaa"}, "Delete Products": {"en": "Delete Products", "rw": "Siba ibicuruzwa", "fr": "Supprimer les produits", "sw": "Futa bidhaa"}, "Add Expenses": {"en": "Add Expenses", "rw": "Ongeramo expenses", "fr": "Ajouter des dépenses", "sw": "Ongeza matumizi"}, "View Expenses": {"en": "View Expenses", "rw": "Reba expenses", "fr": "Voir les dépenses", "sw": "Tazama matumizi"}, "View Reports": {"en": "View Reports", "rw": "Reba raporo", "fr": "Voir les rapports", "sw": "Tazama ripoti"}, "Manage Customers": {"en": "Manage Customers", "rw": "Gucunga abakiriya", "fr": "Gérer les clients", "sw": "Simamia wateja"}, "Manage Employees": {"en": "Manage Employees", "rw": "Gucunga abakozi", "fr": "Gérer les employés", "sw": "Simamia wafanyakazi"}, "You do not have permission for this": {"en": "You do not have permission for this", "rw": "Nta burenganzira ufite kuri ibi", "fr": "Vous n'avez pas l'autorisation pour cela", "sw": "Huna ruhusa ya kufanya hili"}, "Edit Expense": {"en": "Edit Expense", "rw": "Hindura expense", "fr": "Modifier la dépense", "sw": "Hariri matumizi"}, "Expense Title": {"en": "Expense Title", "rw": "Izina ry'expense", "fr": "Titre de la dépense", "sw": "Jina la matumizi"}, "Amount": {"en": "Amount", "rw": "Amafaranga", "fr": "Montant", "sw": "Kiasi"}, "Note": {"en": "Note", "rw": "Icyitonderwa", "fr": "Note", "sw": "Maelezo"}, "optional": {"en": "optional", "rw": "si ngombwa", "fr": "facultatif", "sw": "si lazima"}, "Additional details": {"en": "Additional details", "rw": "Ibisobanuro byongeweho", "fr": "Détails supplémentaires", "sw": "Maelezo ya ziada"}, "e.g. Monthly Rent, Electricity Bill": {"en": "e.g. Monthly Rent, Electricity Bill", "rw": "urugero: Ubukode bw'ukwezi, Fagitire y'amashanyarazi", "fr": "ex. : Loyer mensuel, Facture d'électricité", "sw": "mfano: Kodi ya mwezi, Bili ya umeme"}, "Save Expense": {"en": "Save Expense", "rw": "Bika expense", "fr": "Enregistrer la dépense", "sw": "Hifadhi matumizi"}, "Frw": {"en": "Frw", "rw": "Frw", "fr": "Frw", "sw": "Frw"}, "Salaries": {"en": "Salaries", "rw": "Imishahara", "fr": "Salaires", "sw": "Mishahara"}, "Supplies": {"en": "Supplies", "rw": "Ibikoresho", "fr": "Fournitures", "sw": "Vifaa"}, "Marketing": {"en": "Marketing", "rw": "Kwamamaza", "fr": "Marketing", "sw": "Masoko"}, "Maintenance": {"en": "Maintenance", "rw": "Kubungabunga", "fr": "Maintenance", "sw": "Matengenezo"}, "Food": {"en": "Food", "rw": "Ibiribwa", "fr": "Nourriture", "sw": "Chakula"}, "About BizzAssist": {"en": "About BizzAssist", "rw": "Ibyerekeye BizzAssist", "fr": "À propos de BizzAssist", "sw": "Kuhusu BizzAssist"}, "Built by Albert Dushimimana": {"en": "Built by Albert Dushimimana", "rw": "Yakozwe na Albert Dushimimana", "fr": "Créée par Albert Dushimimana", "sw": "Imetengenezwa na Albert Dushimimana"}, "Data storage": {"en": "Data storage", "rw": "Ububiko bw'amakuru", "fr": "Stockage des données", "sw": "Hifadhi ya data"}, "Online • saved on this phone": {"en": "Online • saved on this phone", "rw": "Online • ibitswe kuri telefone", "fr": "En ligne • enregistré sur ce téléphone", "sw": "Mtandaoni • imehifadhiwa kwenye simu hii"}, "Offline • saved on this phone": {"en": "Offline • saved on this phone", "rw": "Offline • ibitswe kuri telefone", "fr": "Hors ligne • enregistré sur ce téléphone", "sw": "Nje ya mtandao • imehifadhiwa kwenye simu hii"}, "Record Sale": {"en": "Record Sale", "rw": "Andika igurisha", "fr": "Enregistrer une vente", "sw": "Rekodi mauzo"}, "Arrange buttons": {"en": "Arrange buttons", "rw": "Teganya buto", "fr": "Organiser les boutons", "sw": "Panga vitufe"}, "Choose where each button appears": {"en": "Choose where each button appears", "rw": "Hitamo aho buri buto igaragara", "fr": "Choisissez où apparaît chaque bouton", "sw": "Chagua mahali kila kitufe kinapoonekana"}, "Each button can be in one place only. Dashboard always stays in the bottom bar.": {"en": "Each button can be in one place only. Dashboard always stays in the bottom bar.", "rw": "Buri buto iba ahantu hamwe gusa. Dashboard iguma buri gihe muri Navigator.", "fr": "Chaque bouton ne peut être qu'à un seul endroit. Le tableau de bord reste toujours dans la barre du bas.", "sw": "Kila kitufe kiko sehemu moja tu. Dashibodi inabaki kila wakati kwenye upau wa chini."}, "Quick actions": {"en": "Quick actions", "rw": "Ibikorwa byihuse", "fr": "Actions rapides", "sw": "Vitendo vya haraka"}, "Bottom bar (Dashboard is always here)": {"en": "Bottom bar (Dashboard is always here)", "rw": "Umurongo wo hasi (Dashboard iguma hano)", "fr": "Barre du bas (le tableau de bord y reste)", "sw": "Upau wa chini (Dashibodi iko hapa kila wakati)"}, "Buttons on the Dashboard": {"en": "Buttons on the Dashboard", "rw": "Buto ziri kuri Dashboard", "fr": "Boutons du tableau de bord", "sw": "Vitufe vya dashibodi"}, "Home menu (☰ top right)": {"en": "Home menu (☰ top right)", "rw": "Menu ya Home (☰ hejuru iburyo)", "fr": "Menu Accueil (☰ en haut à droite)", "sw": "Menyu ya Home (☰ juu kulia)"}, "In this place": {"en": "In this place", "rw": "Ziri hano", "fr": "Dans cet endroit", "sw": "Ziko hapa"}, "Other tools": {"en": "Other tools", "rw": "Ibindi bikoresho", "fr": "Autres outils", "sw": "Zana nyingine"}, "This place is full": {"en": "This place is full", "rw": "Aha huzuye", "fr": "Cet endroit est plein", "sw": "Mahali hapa pamejaa"}, "No quick actions. Add some in Settings → Arrange buttons.": {"en": "No quick actions. Add some in Settings → Arrange buttons.", "rw": "Nta quick actions. Ongeramo muri Settings → Teganya buto.", "fr": "Aucune action rapide. Ajoutez-en dans Paramètres → Organiser les boutons.", "sw": "Hakuna vitendo vya haraka. Ongeza kwenye Mipangilio → Panga vitufe."}, "Download started": {"en": "Download started", "rw": "Gukururwa byatangiye", "fr": "Téléchargement lancé", "sw": "Upakuaji umeanza"}, "Download not available here": {"en": "Download not available here", "rw": "Gukuramo ntibishoboka hano", "fr": "Téléchargement indisponible ici", "sw": "Upakuaji hauwezekani hapa"}, "Printing is not available here": {"en": "Printing is not available here", "rw": "Gucapa ntibishoboka hano", "fr": "Impression indisponible ici", "sw": "Kuchapisha hakuwezekani hapa"}, "This type cannot be previewed here. Use Download.": {"en": "This type cannot be previewed here. Use Download.", "rw": "Ubu bwoko ntibushobora kurebwa hano. Koresha Download.", "fr": "Ce type ne peut pas être prévisualisé ici. Utilisez Télécharger.", "sw": "Aina hii haiwezi kuonyeshwa hapa. Tumia Pakua."}, "No, cancel": {"en": "No, cancel", "rw": "Oya, Reka", "fr": "Non, annuler", "sw": "Hapana, ghairi"}, "to confirm": {"en": "to confirm", "rw": "kugira ngo wemeze", "fr": "pour confirmer", "sw": "kuthibitisha"}, "Add report": {"en": "Add report", "rw": "Ongeramo raporo", "fr": "Ajouter un rapport", "sw": "Ongeza ripoti"}, "Ring (long)": {"en": "Ring (long)", "rw": "Ring (ndende)", "fr": "Sonnerie (longue)", "sw": "Mlio (mrefu)"}, "Siren (long)": {"en": "Siren (long)", "rw": "Siren (ndende)", "fr": "Sirène (longue)", "sw": "King'ora (kirefu)"}, "Melody (long)": {"en": "Melody (long)", "rw": "Melody (ndende)", "fr": "Mélodie (longue)", "sw": "Wimbo (mrefu)"}, "My sound (phone)": {"en": "My sound (phone)", "rw": "Ijwi ryanjye (telefone)", "fr": "Mon son (téléphone)", "sw": "Sauti yangu (simu)"}, "My sound from phone": {"en": "My sound from phone", "rw": "Ijwi ryanjye riva kuri telefone", "fr": "Mon son depuis le téléphone", "sw": "Sauti yangu kutoka simu"}, "Upload an audio file, then choose My sound": {"en": "Upload an audio file, then choose My sound", "rw": "Shyiramo dosiye y'ijwi, hanyuma uhitemo My sound", "fr": "Importez un fichier audio, puis choisissez Mon son", "sw": "Pakia faili ya sauti, kisha chagua Sauti yangu"}, "Choose an audio file": {"en": "Choose an audio file", "rw": "Hitamo dosiye y'ijwi", "fr": "Choisissez un fichier audio", "sw": "Chagua faili ya sauti"}, "Sound file is too big (max 5 MB)": {"en": "Sound file is too big (max 5 MB)", "rw": "Dosiye y'ijwi ni nini (max 5 MB)", "fr": "Fichier audio trop grand (max 5 Mo)", "sw": "Faili ya sauti ni kubwa (max 5 MB)"}, "Sound saved ✔": {"en": "Sound saved ✔", "rw": "Ijwi ryabitswe ✔", "fr": "Son enregistré ✔", "sw": "Sauti imehifadhiwa ✔"}, "Could not save the sound": {"en": "Could not save the sound", "rw": "Ntibishobotse kubika ijwi", "fr": "Impossible d'enregistrer le son", "sw": "Haikuwezekana kuhifadhi sauti"}, "Tools on the left, your dashboard on the right": {"en": "Tools on the left, your dashboard on the right", "rw": "Ibikoresho ibumoso, dashboard iburyo", "fr": "Outils à gauche, tableau de bord à droite", "sw": "Zana upande wa kushoto, dashibodi upande wa kulia"}, "Welcome": {"en": "Welcome", "rw": "Murakaza", "fr": "Bienvenue", "sw": "Karibu"}, "Your business, our priority": {"en": "Your business, our priority", "rw": "Ubucuruzi bwawe, ibyo dushyira imbere", "fr": "Votre entreprise, notre priorité", "sw": "Biashara yako, kipaumbele chetu"}, "Today's Orders": {"en": "Today's Orders", "rw": "Ibyatumijwe uyu munsi", "fr": "Commandes d'aujourd'hui", "sw": "Oda za leo"}, "Today's Profit": {"en": "Today's Profit", "rw": "Inyungu y'uyu munsi", "fr": "Bénéfice d'aujourd'hui", "sw": "Faida ya leo"}, "No buttons here.": {"en": "No buttons here.", "rw": "Nta buto zihari.", "fr": "Aucun bouton ici.", "sw": "Hakuna vitufe hapa."}, "Open the downloaded file, then press Print or Save as PDF": {"en": "Open the downloaded file, then press Print or Save as PDF", "rw": "Fungura dosiye yamanuwe, hanyuma ukande Print cyangwa Save as PDF", "fr": "Ouvrez le fichier téléchargé, puis appuyez sur Imprimer ou Enregistrer en PDF", "sw": "Fungua faili iliyopakuliwa, kisha bonyeza Print au Save as PDF"}, "Save as PDF": {"en": "Save as PDF", "rw": "Bika nka PDF", "fr": "Enregistrer en PDF", "sw": "Hifadhi kama PDF"}, "Preparing PDF…": {"en": "Preparing PDF…", "rw": "Turimo gutegura PDF…", "fr": "Préparation du PDF…", "sw": "Inaandaa PDF…"}, "Print is not available on this phone — use Save as PDF": {"en": "Print is not available on this phone — use Save as PDF", "rw": "Print ntiboneka kuri telefone — koresha Bika nka PDF", "fr": "Impression indisponible sur ce téléphone — utilisez Enregistrer en PDF", "sw": "Kuchapisha hakuwezekani kwenye simu hii — tumia Hifadhi kama PDF"}, "Print": {"en": "Print", "rw": "Sohora", "fr": "Imprimer", "sw": "Chapisha"}, "Phone number (optional)": {"en": "Phone number (optional)", "rw": "Numero ya telefone (si ngombwa)", "fr": "Numéro de téléphone (facultatif)", "sw": "Namba ya simu (si lazima)"}, "Email (optional)": {"en": "Email (optional)", "rw": "Email (si ngombwa)", "fr": "Email (facultatif)", "sw": "Barua pepe (si lazima)"}, "Enter a phone number or an email (at least one).": {"en": "Enter a phone number or an email (at least one).", "rw": "Andika numero ya telefone cyangwa email (imwe nibura).", "fr": "Saisissez un numéro de téléphone ou un email (au moins un).", "sw": "Weka namba ya simu au barua pepe (moja angalau)."}, "Phone number is not valid.": {"en": "Phone number is not valid.", "rw": "Numero ya telefone si yo.", "fr": "Le numéro de téléphone n'est pas valide.", "sw": "Namba ya simu si sahihi."}, "Email is not valid.": {"en": "Email is not valid.", "rw": "Email si yo.", "fr": "L'email n'est pas valide.", "sw": "Barua pepe si sahihi."}, "Password must be at least 6 characters.": {"en": "Password must be at least 6 characters.", "rw": "Password nibura inyuguti 6.", "fr": "Le mot de passe doit contenir au moins 6 caractères.", "sw": "Nenosiri lazima liwe na herufi 6 angalau."}, "Passwords do not match.": {"en": "Passwords do not match.", "rw": "Passwords ntizihuye.", "fr": "Les mots de passe ne correspondent pas.", "sw": "Manenosiri hayalingani."}, "This account already exists.": {"en": "This account already exists.", "rw": "Iyi konti isanzweho.", "fr": "Ce compte existe déjà.", "sw": "Akaunti hii ipo tayari."}, "Write your full name.": {"en": "Write your full name.", "rw": "Andika amazina yawe yuzuye.", "fr": "Écrivez votre nom complet.", "sw": "Andika jina lako kamili."}, "Write the business name.": {"en": "Write the business name.", "rw": "Andika izina rya business.", "fr": "Écrivez le nom de l'entreprise.", "sw": "Andika jina la biashara."}, "— Choose country —": {"en": "— Choose country —", "rw": "— Hitamo igihugu —", "fr": "— Choisissez le pays —", "sw": "— Chagua nchi —"}, "— Choose province —": {"en": "— Choose province —", "rw": "— Hitamo intara —", "fr": "— Choisissez la province —", "sw": "— Chagua mkoa —"}, "— Choose district —": {"en": "— Choose district —", "rw": "— Hitamo akarere —", "fr": "— Choisissez le district —", "sw": "— Chagua wilaya —"}, "— Choose sector —": {"en": "— Choose sector —", "rw": "— Hitamo umurenge —", "fr": "— Choisissez le secteur —", "sw": "— Chagua kata —"}, "Sectors not added yet": {"en": "Sectors not added yet", "rw": "Imirenge ntirashyirwamo", "fr": "Secteurs pas encore ajoutés", "sw": "Kata bado hazijaongezwa"}, "Not needed": {"en": "Not needed", "rw": "Ntibikenewe", "fr": "Non requis", "sw": "Haihitajiki"}, "Choose your country.": {"en": "Choose your country.", "rw": "Hitamo igihugu cyawe.", "fr": "Choisissez votre pays.", "sw": "Chagua nchi yako."}, "Choose your province and district.": {"en": "Choose your province and district.", "rw": "Hitamo intara n'akarere.", "fr": "Choisissez votre province et district.", "sw": "Chagua mkoa na wilaya."}, "Burundi": {"en": "Burundi", "rw": "Burundi", "fr": "Burundi", "sw": "Burundi"}, "Uganda": {"en": "Uganda", "rw": "Uganda", "fr": "Ouganda", "sw": "Uganda"}, "Kenya": {"en": "Kenya", "rw": "Kenya", "fr": "Kenya", "sw": "Kenya"}, "Tanzania": {"en": "Tanzania", "rw": "Tanzaniya", "fr": "Tanzanie", "sw": "Tanzania"}, "DR Congo": {"en": "DR Congo", "rw": "RDC", "fr": "RD Congo", "sw": "DR Kongo"}, "South Sudan": {"en": "South Sudan", "rw": "Sudani y'Epfo", "fr": "Soudan du Sud", "sw": "Sudan Kusini"}, "Somalia": {"en": "Somalia", "rw": "Somaliya", "fr": "Somalie", "sw": "Somalia"}, "Ethiopia": {"en": "Ethiopia", "rw": "Ethiyopiya", "fr": "Éthiopie", "sw": "Ethiopia"}, "Kigali City": {"en": "Kigali City", "rw": "Umujyi wa Kigali", "fr": "Ville de Kigali", "sw": "Jiji la Kigali"}, "Northern Province": {"en": "Northern Province", "rw": "Intara y'Amajyaruguru", "fr": "Province du Nord", "sw": "Mkoa wa Kaskazini"}, "Southern Province": {"en": "Southern Province", "rw": "Intara y'Amajyepfo", "fr": "Province du Sud", "sw": "Mkoa wa Kusini"}, "Eastern Province": {"en": "Eastern Province", "rw": "Intara y'Iburasirazuba", "fr": "Province de l'Est", "sw": "Mkoa wa Mashariki"}, "Western Province": {"en": "Western Province", "rw": "Intara y'Iburengerazuba", "fr": "Province de l'Ouest", "sw": "Mkoa wa Magharibi"}, "Province": {"en": "Province", "rw": "Intara", "fr": "Province", "sw": "Mkoa"}, "District": {"en": "District", "rw": "Akarere", "fr": "District", "sw": "Wilaya"}, "Sector": {"en": "Sector", "rw": "Umurenge", "fr": "Secteur", "sw": "Kata"}, "Country": {"en": "Country", "rw": "Igihugu", "fr": "Pays", "sw": "Nchi"}, "Choose your sector.": {"en": "Choose your sector.", "rw": "Hitamo umurenge wawe.", "fr": "Choisissez votre secteur.", "sw": "Chagua kata yako."}, "Enter both a phone number and an email.": {"en": "Enter both a phone number and an email.", "rw": "Andika numero ya telefone n'email byombi.", "fr": "Saisissez un numéro de téléphone et un email.", "sw": "Weka namba ya simu na barua pepe zote mbili."}, "Password must be 8+ characters with letters, numbers and symbols.": {"en": "Password must be 8+ characters with letters, numbers and symbols.", "rw": "Password igomba kuba nibura inyuguti 8, harimo inyuguti, imibare n'ibimenyetso.", "fr": "Le mot de passe doit contenir 8 caractères au minimum, avec lettres, chiffres et symboles.", "sw": "Nenosiri lazima liwe na herufi 8 angalau, herufi, namba na alama."}, "Password: nibura 8, inyuguti, imibare n'ibimenyetso": {"en": "Password: nibura 8, inyuguti, imibare n'ibimenyetso", "rw": "Password: nibura 8, inyuguti, imibare n'ibimenyetso", "fr": "Mot de passe : 8 min, lettres, chiffres et symboles", "sw": "Nenosiri: angalau 8, herufi, namba na alama"}, "Email": {"en": "Email", "rw": "Email", "fr": "Email", "sw": "Barua pepe"}, "Viewing as": {"en": "Viewing as", "rw": "Urareba nka", "fr": "Vous consultez", "sw": "Unaona kama"}, "Back to admin": {"en": "Back to admin", "rw": "Subira kuri admin", "fr": "Retour à l'admin", "sw": "Rudi kwa admin"}, "Enter account": {"en": "Enter account", "rw": "Injira muri konti", "fr": "Entrer dans le compte", "sw": "Ingia kwenye akaunti"}, "Admin entered account": {"en": "Admin entered account", "rw": "Admin yinjiye muri konti", "fr": "L'admin est entré dans le compte", "sw": "Admin ameingia kwenye akaunti"}, "This is your account": {"en": "This is your account", "rw": "Iyi ni konti yawe", "fr": "C'est votre compte", "sw": "Hii ni akaunti yako"}, "At least 8 characters": {"en": "At least 8 characters", "rw": "Nibura inyuguti 8", "fr": "Au moins 8 caractères", "sw": "Angalau herufi 8"}, "Letters (A–Z, a–z)": {"en": "Letters (A–Z, a–z)", "rw": "Inyuguti (A–Z, a–z)", "fr": "Lettres (A–Z, a–z)", "sw": "Herufi (A–Z, a–z)"}, "Numbers (0–9)": {"en": "Numbers (0–9)", "rw": "Imibare (0–9)", "fr": "Chiffres (0–9)", "sw": "Namba (0–9)"}, "Symbols (! @ # $ % ...)": {"en": "Symbols (! @ # $ % ...)", "rw": "Ibimenyetso (! @ # $ % ...)", "fr": "Symboles (! @ # $ % ...)", "sw": "Alama (! @ # $ % ...)"}, "New password (min. 8)": {"en": "New password (min. 8)", "rw": "Password nshya (nibura 8)", "fr": "Nouveau mot de passe (min. 8)", "sw": "Nenosiri jipya (angalau 8)"}, "Temporary email addresses are not accepted. Use your real email.": {"en": "Temporary email addresses are not accepted. Use your real email.", "rw": "Email z'igihe gito ntizemewe. Koresha email yawe nyayo.", "fr": "Les adresses email temporaires ne sont pas acceptées. Utilisez votre vraie adresse.", "sw": "Barua pepe za muda hazikubaliwa. Tumia barua pepe yako halisi."}, "Did you mean ": {"en": "Did you mean ", "rw": "Wari washatse kuvuga ", "fr": "Vouliez-vous dire ", "sw": "Ulimaanisha "}, "Cloud account": {"en": "Cloud account", "rw": "Konti ya cloud", "fr": "Compte cloud", "sw": "Akaunti ya wingu"}, "Sign in to sync your data online": {"en": "Sign in to sync your data online", "rw": "Injira ubike amakuru kuri internet", "fr": "Connectez-vous pour synchroniser vos données", "sw": "Ingia uhifadhi data mtandaoni"}, "Cloud is not connected yet. The administrator must add the server address in config.js.": {"en": "Cloud is not connected yet. The administrator must add the server address in config.js.", "rw": "Cloud ntiratangira. Admin agomba gushyira aderesi ya server muri config.js.", "fr": "Le cloud n'est pas encore connecté. L'administrateur doit ajouter l'adresse du serveur dans config.js.", "sw": "Wingu bado halijaunganishwa. Msimamizi lazima aweke anwani ya seva kwenye config.js."}, "Signed in as ": {"en": "Signed in as ", "rw": "Winjiye nka ", "fr": "Connecté en tant que ", "sw": "Umeingia kama "}, "Not signed in": {"en": "Not signed in", "rw": "Ntiwinjiye", "fr": "Non connecté", "sw": "Hujaingia"}, "Sign in": {"en": "Sign in", "rw": "Injira", "fr": "Se connecter", "sw": "Ingia"}, "Sync now": {"en": "Sync now", "rw": "Hindura ubu", "fr": "Synchroniser", "sw": "Sawazisha sasa"}, "Sign out": {"en": "Sign out", "rw": "Sohoka", "fr": "Se déconnecter", "sw": "Toka"}, "Signed out": {"en": "Signed out", "rw": "Wasohotse", "fr": "Déconnecté", "sw": "Umetoka"}, "Check your email to confirm": {"en": "Check your email to confirm", "rw": "Reba email yawe wemeze", "fr": "Vérifiez votre email pour confirmer", "sw": "Angalia barua pepe yako uthibitishe"}, "Account created ✔": {"en": "Account created ✔", "rw": "Konti yafunguwe ✔", "fr": "Compte créé ✔", "sw": "Akaunti imeundwa ✔"}, "Signed in ✔": {"en": "Signed in ✔", "rw": "Winjiye ✔", "fr": "Connecté ✔", "sw": "Umeingia ✔"}, "Synced ✔": {"en": "Synced ✔", "rw": "Byahujwe ✔", "fr": "Synchronisé ✔", "sw": "Imesawazishwa ✔"}, "Sync failed": {"en": "Sync failed", "rw": "Guhuza byanze", "fr": "Échec de la synchronisation", "sw": "Usawazishaji umeshindwa"}, "Cloud error: ": {"en": "Cloud error: ", "rw": "Ikosa rya cloud: ", "fr": "Erreur cloud : ", "sw": "Hitilafu ya wingu: "}, "Tap to choose a sound": {"en": "Tap to choose a sound", "rw": "Kanda uhitemo ijwi", "fr": "Touchez pour choisir un son", "sw": "Gusa kuchagua sauti"}, "Upload a file below": {"en": "Upload a file below", "rw": "Shyiramo dosiye hepfo", "fr": "Importez un fichier ci-dessous", "sw": "Pakia faili hapa chini"}, "VAT": {"en": "VAT", "rw": "VAT", "fr": "TVA", "sw": "VAT"}, "Amount excl. VAT": {"en": "Amount excl. VAT", "rw": "Agaciro mbere ya VAT", "fr": "Montant hors TVA", "sw": "Kiasi bila VAT"}, "VAT 18%": {"en": "VAT 18%", "rw": "VAT 18%", "fr": "TVA 18%", "sw": "VAT 18%"}, "Total incl. VAT": {"en": "Total incl. VAT", "rw": "Igiteranyo harimo VAT", "fr": "Total TVA incluse", "sw": "Jumla pamoja na VAT"}, "Thank you!": {"en": "Thank you!", "rw": "Murakoze!", "fr": "Merci !", "sw": "Asante!"}, "Show 80 mm": {"en": "Show 80 mm", "rw": "80 mm", "fr": "80 mm", "sw": "80 mm"}, "Good morning": {"en": "Good morning", "rw": "Mwaramutse", "fr": "Bonjour", "sw": "Habari za asubuhi"}, "Good afternoon": {"en": "Good afternoon", "rw": "Mwiriwe", "fr": "Bon après-midi", "sw": "Habari za mchana"}, "Good evening": {"en": "Good evening", "rw": "Muraho neza", "fr": "Bonsoir", "sw": "Habari za jioni"}, "Manage your business, grow your profits": {"en": "Manage your business, grow your profits", "rw": "Cunga ubucuruzi bwawe, uzamure inyungu", "fr": "Gérez votre commerce, augmentez vos bénéfices", "sw": "Simamia biashara yako, ongeza faida"}, "Today's Sales": {"en": "Today's Sales", "rw": "Ibyagurishijwe uyu munsi", "fr": "Ventes d'aujourd'hui", "sw": "Mauzo ya leo"}, "View": {"en": "View", "rw": "Reba", "fr": "Voir", "sw": "Tazama"}, "Staff are asking for approval": {"en": "Staff are asking for approval", "rw": "Hari abakozi basaba uruhushya", "fr": "Le personnel demande une approbation", "sw": "Wafanyakazi wanaomba idhini"}, "Search product, code or category": {"en": "Search product, code or category", "rw": "Shakisha igicuruzwa, code cyangwa icyiciro", "fr": "Rechercher un produit, un code ou une catégorie", "sw": "Tafuta bidhaa, msimbo au kategoria"}, "Print label": {"en": "Print label", "rw": "Sohora etiketi", "fr": "Imprimer l'étiquette", "sw": "Chapisha lebo"}, "Search settings": {"en": "Search settings", "rw": "Shakisha mu igenamiterere", "fr": "Rechercher dans les paramètres", "sw": "Tafuta kwenye mipangilio"}, "Province / region": {"en": "Province / region", "rw": "Intara / agace", "fr": "Province / région", "sw": "Mkoa / eneo"}, "District / city": {"en": "District / city", "rw": "Akarere / umujyi", "fr": "District / ville", "sw": "Wilaya / jiji"}, "Sector / area (optional)": {"en": "Sector / area (optional)", "rw": "Umurenge / agace (si ngombwa)", "fr": "Secteur / zone (facultatif)", "sw": "Kata / eneo (si lazima)"}, "Write your district or city.": {"en": "Write your district or city.", "rw": "Andika akarere cyangwa umujyi wawe.", "fr": "Écrivez votre district ou ville.", "sw": "Andika wilaya au jiji lako."}, "— Choose —": {"en": "— Choose —", "rw": "— Hitamo —", "fr": "— Choisir —", "sw": "— Chagua —"}, "Central": {"en": "Central", "rw": "Ikarere", "fr": "Centre", "sw": "Kati"}, "Eastern": {"en": "Eastern", "rw": "Iburasirazuba", "fr": "Est", "sw": "Mashariki"}, "Northern": {"en": "Northern", "rw": "Amajyaruguru", "fr": "Nord", "sw": "Kaskazini"}, "Western": {"en": "Western", "rw": "Iburengerazuba", "fr": "Ouest", "sw": "Magharibi"}};
const TRP=[
[/^Stock ni ([\d.]+) pieces gusa$/,{en:"Only $1 pieces in stock",fr:"Seulement $1 pièces en stock",sw:"Zimebaki vipande $1 tu"}],
[/^Stock ni ([\d.]+) gusa$/,{en:"Only $1 in stock",fr:"Seulement $1 en stock",sw:"Zimebaki $1 tu"}],
[/^Ideni ni (.+) gusa$/,{en:"Debt is only $1",fr:"Le montant dû est seulement $1",sw:"Deni ni $1 tu"}],
[/^Ideni (.+) ryanditswe • (.+)$/,{en:"Debt $1 recorded • $2",fr:"Dette de $1 enregistrée • $2",sw:"Deni la $1 limehifadhiwa • $2"}],
[/^Murakoze! ★(\d)$/,{en:"Thank you! ★$1",fr:"Merci ! ★$1",sw:"Asante! ★$1"}],
[/^Pieces muri (.+) nibura 2$/,{en:"Pieces in $1 must be at least 2",fr:"Pièces dans $1 : minimum 2",sw:"Vipande katika $1 lazima viwe angalau 2"}],
[/^Gikoreshwa n'ibicuruzwa (\d+)\. Banza ubihindure\.$/,{en:"Used by $1 products. Change them first.",fr:"Utilisé par $1 produits. Modifiez-les d'abord.",sw:"Imetumiwa na bidhaa $1. Zibadilishe kwanza."}],
[/^Andika igiciro cya (.+)$/,{en:"Enter the price of $1",fr:"Saisissez le prix de $1",sw:"Weka bei ya $1"}],
[/^Andika (.+) neza$/,{en:"Type $1 correctly",fr:"Saisissez $1 correctement",sw:"Andika $1 vizuri"}],
];
function trPat(core){
  const l=trLang();if(l==="rw")return null;
  for(const [re,m] of TRP){const g=core.match(re);if(g){return (m[l]||m.en).replace(/\$(\d)/g,(_,i)=>g[+i])}}
  return null;
}
const TRX={};Object.values(TRD).forEach(v=>{TRX[v.en]=v;if(v.rw)TRX[v.rw]=v});
const trCore=s=>{const m=String(s).match(/^([^A-Za-zÀ-ÿ0-9]*)([\s\S]*?)([^A-Za-zÀ-ÿ0-9]*)$/);return m?[m[1],m[2].trim(),m[3]]:["",String(s).trim(),""]};
const trLang=()=>{const g=PF.lang||"English";return g==="English"?"en":g==="Kinyarwanda"?"rw":g==="Français"?"fr":g==="Kiswahili"?"sw":"en"};
function trTxt(t){
  const [pre,core,suf]=trCore(t);if(!core)return null;
  const e=TRX[core];if(!e){const pr=trPat(core);return pr===null?null:pre+pr+suf}
  const v=e[trLang()];if(!v)return null;
  return pre+v+suf;
}
const trP=s=>(typeof trTxt==='function'&&trTxt(s))||s;
function trDom(root){
  if(!root)return;
  const w=document.createTreeWalker(root,NodeFilter.SHOW_TEXT);let n;const hits=[];
  while(n=w.nextNode()){if(n.parentElement&&n.parentElement.closest("script,style"))continue;hits.push(n)}
  hits.forEach(n=>{const raw=n.textContent,lead=(raw.match(/^\s*/)||[""])[0],trail=(raw.match(/\s*$/)||[""])[0],core=raw.trim();if(!core)return;const r=trTxt(core);if(r!==null&&r!==core)n.textContent=lead+r+trail});
  root.querySelectorAll("[placeholder]").forEach(e=>{const r=trTxt(e.placeholder);if(r!==null)e.placeholder=r});
}
/* FEATURED PRODUCTS SLIDER */
const featList=()=>P.filter(p=>p.act!==false&&p.n&&p.s>0).sort((a,b)=>(b.feat?1:0)-(a.feat?1:0)||(a.fo||9999)-(b.fo||9999)||a.n.localeCompare(b.n));
let fsI=0,fsT=null,fsHov=false;
const fsImg=p=>{const u=(p.imgs&&p.imgs[0])||p.img;return okImg(u)?u:""};
function fsSlide(p){
  const im=fsImg(p);
  return `<div class="fs-slide" onclick="go('#/product/${p.id}')"><div class="fs-img">${im?`<img src="${im}" alt="${esc(p.n)}" loading="lazy">`:`<span>${esc(p.e||"📦")}</span>`}</div><div class="fs-info"><b class="fs-n">${esc(p.n)}</b>${p.k?`<span class="chip" style="font-size:11px">${esc(p.k)}</span>`:""}<div class="fs-p">${fmt(p.p)}<small>/ ${esc(p.u||"piece")}</small></div><div class="fs-s">${L("Stock","Stock")}: <b>${p.s}</b> ${esc(p.u||"")} ${badge(p)}</div></div></div>`;
}
function featHTML(){
  const F=featList();
  if(!F.length)return `<div class="c" style="text-align:center;padding:18px"><div style="font-size:34px">⭐</div><b>${L("No products in stock","Nta bicuruzwa biri muri stock")}</b><p class="mu" style="font-size:12.5px;margin:6px 0 10px;line-height:1.4">${L("Add products or update stock to show them here.","Ongeramo ibicuruzwa cyangwa uvugurure stock kugira ngo bigaragare hano.")}</p><button class="add" onclick="pAdd()">＋ ${L("Add Product","Ongeramo igicuruzwa")}</button></div>`;
  const one=F.length<2;
  return `<div class="c" style="padding:10px"><div class="sech" style="margin:0 2px 6px"><b>📦 ${L("Products in stock","Ibicuruzwa biri muri stock")}</b><a onclick="go('#/products')">${L("Manage","Cunga")} ›</a></div><div class="fs" id="fsv"><div class="fs-track" id="fst" style="transform:translateX(-${fsI*100}%)">${F.map(fsSlide).join("")}</div>${one?"":`<button class="fs-btn fs-l" aria-label="Previous" onclick="fsGo(fsI-1);fsStart()">‹</button><button class="fs-btn fs-r" aria-label="Next" onclick="fsGo(fsI+1);fsStart()">›</button><div class="fs-dots">${F.map((_,i)=>`<i class="${i===fsI?"on":""}" onclick="fsGo(${i});fsStart()"></i>`).join("")}</div>`}</div></div>`;
}
function fsGo(i){const n=featList().length;if(!n)return;fsI=((i%n)+n)%n;const t=$("fst");if(t)t.style.transform=`translateX(-${fsI*100}%)`;document.querySelectorAll("#fsv .fs-dots i").forEach((d,k)=>d.classList.toggle("on",k===fsI))}
function fsStart(){clearInterval(fsT);if(featList().length<2)return;fsT=setInterval(()=>{if(!fsHov&&$("fst"))fsGo(fsI+1)},5000)}
function fsInit(){
  const v=$("fsv");if(!v)return;
  const n=featList().length;fsI=Math.min(fsI,Math.max(0,n-1));
  if(n<2)return;
  v.onmouseenter=()=>{fsHov=true};v.onmouseleave=()=>{fsHov=false};
  let x0=null;
  v.ontouchstart=e=>{x0=e.touches[0].clientX};
  v.ontouchend=e=>{if(x0==null)return;const dx=e.changedTouches[0].clientX-x0;x0=null;if(Math.abs(dx)>40){fsGo(dx<0?fsI+1:fsI-1);fsStart()}};
  fsStart();
}

/* PRODUCT LABELS (print) */
const LBSZ={"50x30":["50mm","30mm"],"40x25":["40mm","25mm"]};
function labelModal(id){
  const p=gp(id);if(!p)return;
  modal(`<h3>🏷 ${L("Print label","Sohora etiketi")}</h3><p class="mu" style="margin-bottom:10px">${esc(p.n)} • ${esc(code(p))}</p>
  <label>${L("Label size","Ingano y'etiketi")}</label><select id="lbz"><option value="50x30">50 × 30 mm</option><option value="40x25">40 × 25 mm</option></select>
  <label>${L("Number of labels","Umubare w'etiketi")}</label><input id="lbn" type="number" min="1" max="200" inputmode="numeric" value="1">
  <label class="ck"><input type="checkbox" id="lbp" checked> ${L("Show price","Erekana igiciro")}</label>
  <div class="g2"><button class="btn o" onclick="closeM()">${L("Cancel","Reka")}</button><button class="btn" onclick="labelPrint(${id})">🖨 ${L("Print","Sohora")}</button></div>`);
}
function labelPrint(id){
  const p=gp(id);if(!p)return;
  const n=Math.min(200,Math.max(1,parseInt($("lbn").value,10)||1)),sz=LBSZ[$("lbz").value]||LBSZ["50x30"],showP=$("lbp").checked;
  const code0=code(p).replace(/[^0-9A-Za-z]/g,"").toUpperCase()||"P001";
  const one=`<div class="lab"><b>${esc(p.n)}</b>${showP?`<span class="pr">${fmt(p.p)}</span>`:""}${bar39(code0)}<span class="cd">${esc(code(p))}</span></div>`;
  const box=$("lblp");
  box.style.setProperty("--lw",sz[0]);box.style.setProperty("--lh",sz[1]);
  box.innerHTML=Array.from({length:n},()=>one).join("");
  closeM();
  setTimeout(()=>{if(!printWith())toast(L("Printing is not available here","Gucapa ntibishoboka hano"))},150);
}

/* BARCODE SCAN (sales) */
let scTimer=null,scStream=null,scDet=null,scDone=false;
function scanOpen(){
  scDone=false;
  modal(`<h3>📷 ${L("Scan product","Scan igicuruzwa")}</h3><video id="scv" autoplay playsinline muted style="width:100%;border-radius:12px;background:#000;max-height:45vh"></video><p class="mu" id="scs" style="font-size:12.5px;margin:8px 0;line-height:1.4"></p><label>${L("Or type or scan the code","Cyangwa andika cyangwa scan code")}</label><input id="scm" autocomplete="off" inputmode="text" onkeydown="if(event.key==='Enter')scanCode(this.value)"><div class="g2"><button class="btn o" onclick="scanStop();closeM()">${L("Close","Funga")}</button><button class="btn" onclick="scanCode($('scm').value)">${L("Add","Ongeramo")}</button></div>`);
  scanStart();
}
async function scanStart(){
  const st=m=>{const e=$("scs");if(e)e.textContent=m};
  if(!navigator.mediaDevices||!navigator.mediaDevices.getUserMedia||!("BarcodeDetector" in window)){
    st(L("Camera scanning is not available here (use the installed app on your phone). You can still type the code or use a barcode scanner.","Gusoma kamera ntibishoboka hano (koresha app yashyizwe kuri telefone). Ushobora kwandika code cyangwa gukoresha scanner."));
    return;
  }
  try{
    scStream=await navigator.mediaDevices.getUserMedia({video:{facingMode:{ideal:"environment"}},audio:false});
    const v=$("scv");if(!v)return scanStop();
    v.srcObject=scStream;await v.play();
    scDet=new BarcodeDetector({formats:["code_39","code_128","ean_13","ean_8","upc_a","qr_code"]});
    st(L("Point the camera at the barcode","Lenga kamera ku barcode"));
    scTimer=setInterval(async()=>{
      if(scDone||!$("scv"))return;
      try{const codes=await scDet.detect($("scv"));if(codes.length)scanCode(codes[0].rawValue)}catch(e){}
    },400);
  }catch(e){
    st(L("Camera permission denied or not available. Type the code instead.","Kamera ntiyemewe cyangwa ntiboneka. Andika code."));
  }
}
function scanStop(){
  clearInterval(scTimer);scTimer=null;
  if(scStream){scStream.getTracks().forEach(t=>t.stop());scStream=null}
}
function scanCode(raw){
  if(scDone)return;
  const v=String(raw||"").trim().toUpperCase();if(!v)return;
  const p=P.find(x=>String(code(x)).toUpperCase()===v||String(x.sk||"").toUpperCase()===v);
  if(!p){const e=$("scs");if(e)e.textContent=L("Product not found: ","Ntabwo igicuruzwa kiboneka: ")+v;toast(L("Product not found","Igicuruzwa ntikiboneka"));return}
  if(!(p.s>0)){toast(L("Product is out of stock","Igicuruzwa cyashize muri stock"));return}
  scDone=true;scanStop();
  ac(p.id,0);
  closeM();
  toast(L("Added to cart","Cyongewe mu gaseke")+": "+p.n);
}

/* CUSTOM NOTIFICATION SOUND (from the user's phone) */
async function loadCustomSnd(){
  try{const b=await idbP("get","snd_"+SE.id);if(b){if(window.CUSTOM_URL)URL.revokeObjectURL(window.CUSTOM_URL);window.CUSTOM_URL=URL.createObjectURL(b)}}catch(e){}
}
async function sndUp(inp){
  const f=inp.files&&inp.files[0];if(!f)return;
  if(!/^audio\//.test(f.type)&&!/\.(mp3|wav|ogg|m4a|aac)$/i.test(f.name))return toast(L("Choose an audio file","Hitamo dosiye y'ijwi"));
  if(f.size>5*1048576)return toast(L("Sound file is too big (max 5 MB)","Dosiye y'ijwi ni nini (max 5 MB)"));
  try{await idbP("put","snd_"+SE.id,f);await loadCustomSnd();PF.tone="custom";savePF();logA("Settings changed","Notification sound");toast(L("Sound saved ✔","Ijwi ryabitswe ✔"));settings()}
  catch(e){toast(L("Could not save the sound","Ntibishobotse kubika ijwi"))}
}

/* ABOUT / OFFLINE */
function aboutM(){
  modal(`<h3>ℹ️ About BizzAssist</h3><p style="line-height:1.6;margin-bottom:12px">BizzAssist Rwanda was built by <b>Albert Dushimimana</b>. It is a smart business assistant for shops in Rwanda: sales, stock, expenses, customers and reports in one place.</p><p class="mu" style="line-height:1.5;font-size:13px;margin-bottom:12px">It works offline: your data is saved on this phone, and you can back it up from Settings.</p><button class="btn" onclick="closeM()">OK</button>`);
}

/* BUTTON ARRANGEMENT */
const ARRW={nav:{t:"Navigator",i:"🧭",d:"Bottom bar (Dashboard is always here)",max:4},qa:{t:"Quick actions",i:"⚡",d:"Buttons on the Dashboard",max:8},hm:{t:"Home",i:"☰",d:"Home menu (☰ top right)",max:99}};
const QTGT={sales:"#/sale"};
function qaHTML(){
  const c=navCfg(),ks=c.qa.filter(k=>navOk(navItem(k)));
  const fst=ks.length?"btn":"btn o";
  if(!ks.length)return `<div class="emp" style="grid-column:1/-1">${L("No quick actions. Add some in Settings → Arrange buttons.","Nta quick actions. Ongeramo muri Settings → Teganya buto.")}</div>`;
  return ks.map((k,i)=>{const x=navItem(k),lb=k==="sales"?L("Record Sale","Andika igurisha"):x[2];return `<button class="${i===0?"btn":"btn o"}" onclick="go('${QTGT[k]||"#/"+k}')">${x[1]} ${lb}</button>`}).join("");
}
function arrangeHub(){
  page(L("Arrange buttons","Teganya buto"),L("Choose where each button appears","Hitamo aho buri buto igaragara"),
  `${Object.keys(ARRW).map(k=>{const c=navCfg(),n=k==="hm"?c.hm.length:k==="qa"?c.qa.length:c.nv.length-1;return `<div class="s" style="margin-bottom:10px" onclick="go('#/arr/${k}')"><i>${ARRW[k].i}</i><div><b>${L(ARRW[k].t,ARRW[k].t)}</b><small>${L(ARRW[k].d,ARRW[k].d)} • ${n}</small></div><span class="chv">›</span></div>`}).join("")}
  <p class="mu" style="font-size:12px;line-height:1.5;margin-top:6px">${L("Each button can be in one place only. Dashboard always stays in the bottom bar.","Buri buto iba ahantu hamwe gusa. Dashboard iguma buri gihe muri Navigator.")}</p>`,{back:"#/settings",nav:"settings"});
}
function arrangePage(k){
  const W=ARRW[k];if(!W)return go("#/arrange");
  const c=navCfg();
  const cur=k==="hm"?c.hm:k==="qa"?c.qa:c.nv.slice(1);
  const all=NAVC().map(x=>x[0]).filter(x=>x!=="home");
  const off=all.filter(x=>!cur.includes(x));
  const row=(x,i,n,sel)=>{const it=navItem(x);return `<div class="row" style="cursor:default"><div class="em">${it[1]}</div><div class="m"><b>${it[2]}</b><small>${it[3]||""}</small></div>${sel?`<button class="ib" style="padding:6px 8px" ${i===0?"disabled":""} onclick="arrMove('${k}','${x}',-1)">▲</button><button class="ib" style="padding:6px 8px" ${i===n-1?"disabled":""} onclick="arrMove('${k}','${x}',1)">▼</button><button class="ib" style="padding:6px 8px;border-color:var(--rd);color:var(--rd)" onclick="arrSet('${k}','${x}',false)">✖</button>`:`<button class="add" onclick="arrSet('${k}','${x}',true)">＋ ${L("Add","Ongeramo")}</button>`}</div>`};
  page(`${W.i} ${L(W.t,W.t)}`,`${L(W.d,W.d)} • ${cur.length}${k==="nav"?"/"+(W.max+1)+"":""}`,
  `<div class="c" style="padding:4px 12px"><h3 style="margin:8px 0 4px">✅ ${L("In this place","Ziri hano")}</h3>${cur.map((x,i)=>row(x,i,cur.length,true)).join("")||`<div class="emp">—</div>`}</div>
  <div class="c" style="padding:4px 12px"><h3 style="margin:8px 0 4px">＋ ${L("Other tools","Ibindi bikoresho")}</h3>${off.map(x=>row(x,0,0,false)).join("")||`<div class="emp">—</div>`}</div>`,{back:"#/arrange",nav:"settings"});
}
function arrSet(k,x,on){
  const c=navCfg();
  const lists={nav:c.nv.slice(1),qa:c.qa,hm:c.hm};
  if(on){
    if(lists[k].length>=ARRW[k].max)return toast(L("This place is full","Aha huzuye"));
    if(!lists[k].includes(x))lists[k].push(x);
    if(k!=="nav")lists.nav=lists.nav.filter(y=>y!==x);
  }else lists[k]=lists[k].filter(y=>y!==x);
  PF.nav=lists.nav;PF.qa=lists.qa;PF.hm=lists.hm;savePF();logA("Settings changed","Button arrangement");
  route();
}
function arrMove(k,x,d){
  const c=navCfg(),arr=k==="hm"?c.hm:k==="qa"?c.qa:c.nv.slice(1),i=arr.indexOf(x),j=i+d;
  if(i<0||j<0||j>=arr.length)return;
  [arr[i],arr[j]]=[arr[j],arr[i]];
  PF.nav=k==="nav"?arr:c.nv.slice(1);PF.qa=k==="qa"?arr:c.qa;PF.hm=k==="hm"?arr:c.hm;savePF();route();
}


/* ROUTER */

function route(){
  clearInterval(fsT);closeHP();
  const[v,a]=location.hash.slice(2).split("/");
  if(!SE&&v!=="login"&&v!=="signup")return go("#/signup");
  if(SE&&(v==="login"||v==="signup"))return go("#/home");
  closeM();
  if(SE&&v&&!can(v)&&!(v==="edit"&&(a==="new"?apr("prod_add"):apr("prod_edit",+a)))){toast("Nta burenganzira bwo kugera hano");return go("#/home")}
  ({signup:()=>auth(1),login:()=>auth(0),home,sales,sale:saleNew,receipt:()=>receipt(+a),products,product:()=>detail(+a),edit:()=>pform(a),customers,shop,expenses,memo:aiPage,ai:aiPage,more,log:logPage,suppliers,finance,reports,inventory,files:filesPage,navhub:navHub,navmgr:navMgr,homemgr:homeMgr,arrange:arrangeHub,arr:()=>arrangePage(a),admin,settings}[v]||home)();
  scrollTo(0,0);trDom($("app"));trDom($("nav"));
}
addEventListener("storage",e=>{if(e.key==="bizz_reqs"){Reqs=ld("bizz_reqs",[]);checkDue();const v=location.hash.slice(2).split("/")[0];if(SE&&(v==="expenses"||v==="admin")&&!$("md").classList.contains("on"))route()}});
addEventListener("hashchange",route);
theme(ld("bizz_theme","dark"));
route();loadCustomSnd();setInterval(checkDue,30000);setTimeout(checkDue,1500);
if("serviceWorker" in navigator&&/^https?:$/.test(location.protocol)){addEventListener("load",()=>navigator.serviceWorker.register("sw.js").catch(()=>{}))}
</script>
</body>
</html>
