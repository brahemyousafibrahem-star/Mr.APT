<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<meta name="theme-color" content="#070A10">
<title>Mr. APT — أكاديمية الأمن السيبراني</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=IBM+Plex+Sans+Arabic:wght@400;500;600;700&family=IBM+Plex+Mono:wght@400;500;600&family=Amiri:wght@700&display=swap" rel="stylesheet">

<style>
:root{
  --bg:#070A10;
  --panel:#0E131C;
  --panel2:#131A26;
  --panel3:#182130;
  --border:#253043;
  --text:#E7EDF4;
  --muted:#8B98AA;
  --teal:#2FBF9F;
  --teal2:#1E8E78;
  --teal-dim:#12372F;
  --gold:#D2A44A;
  --gold-dim:#3B2D13;
  --red:#E2574C;
  --blue:#4B8BFF;
  --shadow:0 18px 55px rgba(0,0,0,.38);
}

*{
  box-sizing:border-box;
}

html,body{
  margin:0;
  min-height:100%;
  background:var(--bg);
  color:var(--text);
  font-family:"IBM Plex Sans Arabic",sans-serif;
}

body{
  overflow-x:hidden;
}

button,input,textarea,select{
  font:inherit;
}

button{
  cursor:pointer;
}

#matrixBg{
  position:fixed;
  inset:0;
  width:100%;
  height:100%;
  z-index:-3;
  opacity:.20;
  pointer-events:none;
}

#matrixShade{
  position:fixed;
  inset:0;
  z-index:-2;
  pointer-events:none;
  background:
    radial-gradient(circle at 50% 0%,rgba(47,191,159,.08),transparent 42%),
    linear-gradient(180deg,rgba(7,10,16,.18),rgba(7,10,16,.78));
}

.app{
  min-height:100vh;
  display:flex;
}

.sidebar{
  width:290px;
  flex:0 0 290px;
  background:rgba(14,19,28,.96);
  border-inline-start:1px solid var(--border);
  box-shadow:var(--shadow);
  min-height:100vh;
  position:sticky;
  top:0;
  height:100vh;
  overflow:auto;
  z-index:70;
}

.brand{
  display:flex;
  align-items:center;
  gap:12px;
  padding:22px 18px 14px;
  border-bottom:1px solid var(--border);
}

.brandIcon{
  width:42px;
  height:42px;
  border-radius:12px;
  display:grid;
  place-items:center;
  background:var(--teal-dim);
  border:1px solid rgba(47,191,159,.35);
  font-size:23px;
}

.brand b{
  display:block;
  font-size:20px;
}

.brand span{
  display:block;
  color:var(--muted);
  font-size:11px;
  margin-top:2px;
}

.xpBadge{
  margin:14px;
  padding:11px 12px;
  border-radius:10px;
  background:linear-gradient(135deg,var(--teal-dim),rgba(47,191,159,.05));
  border:1px solid rgba(47,191,159,.25);
  color:#bdeee4;
  font-size:13px;
}

.searchBox{
  padding:0 14px 14px;
}

.searchBox input{
  width:100%;
  background:#090D14;
  border:1px solid var(--border);
  color:var(--text);
  padding:11px 12px;
  border-radius:9px;
  outline:none;
}

.searchBox input:focus{
  border-color:var(--teal);
  box-shadow:0 0 0 3px rgba(47,191,159,.08);
}

.navPhase{
  padding:15px 14px 6px;
  color:var(--gold);
  font-size:11px;
  font-weight:700;
}

.navItem{
  margin:3px 9px;
  padding:11px 12px;
  border-radius:9px;
  color:#b9c4d2;
  display:flex;
  align-items:center;
  justify-content:space-between;
  gap:8px;
  cursor:pointer;
  transition:.18s;
  border:1px solid transparent;
}

.navItem:hover{
  background:rgba(255,255,255,.035);
  color:white;
}

.navItem.active{
  background:var(--teal-dim);
  color:#e9fffa;
  border-color:rgba(47,191,159,.25);
}

.navItem.locked{
  color:#8994a4;
}

.navItem .title{
  min-width:0;
  line-height:1.45;
  font-size:13px;
}

.navItem .state{
  flex:none;
  font-size:11px;
  color:var(--muted);
}

.main{
  flex:1;
  min-width:0;
  width:100%;
  max-width:1050px;
  margin:auto;
  padding:30px clamp(15px,4vw,42px) 60px;
}

.topbar{
  display:none;
  height:48px;
  align-items:center;
  justify-content:space-between;
  margin-bottom:15px;
}

.burger{
  border:1px solid var(--border);
  background:var(--panel);
  color:white;
  border-radius:9px;
  width:44px;
  height:42px;
}

.card{
  background:rgba(14,19,28,.92);
  border:1px solid var(--border);
  border-radius:15px;
  padding:22px;
  box-shadow:0 10px 35px rgba(0,0,0,.16);
}

.hero{
  padding:30px;
  border-radius:18px;
  background:
    linear-gradient(135deg,rgba(47,191,159,.12),rgba(14,19,28,.96) 48%),
    var(--panel);
  border:1px solid rgba(47,191,159,.22);
}

h1,h2,h3{
  margin-top:0;
}

.hero h1{
  font-size:clamp(27px,4vw,43px);
  margin-bottom:9px;
}

.hero p{
  color:#aab6c5;
  line-height:1.9;
}

.eyebrow{
  color:var(--teal);
  font-family:"IBM Plex Mono",monospace;
  font-size:12px;
  margin-bottom:10px;
}

.grid{
  display:grid;
  grid-template-columns:repeat(2,minmax(0,1fr));
  gap:14px;
}

.stats{
  display:grid;
  grid-template-columns:repeat(3,minmax(0,1fr));
  gap:12px;
  margin-top:18px;
}

.stat{
  background:rgba(255,255,255,.025);
  border:1px solid var(--border);
  border-radius:12px;
  padding:16px;
}

.stat b{
  display:block;
  font-size:24px;
  color:white;
}

.stat span{
  color:var(--muted);
  font-size:12px;
}

.sectionTitle{
  margin:30px 0 13px;
  display:flex;
  align-items:center;
  justify-content:space-between;
  gap:10px;
}

.lesson{
  background:rgba(14,19,28,.94);
  border:1px solid var(--border);
  border-radius:14px;
  margin-bottom:14px;
  overflow:hidden;
}

.lessonHead{
  padding:17px 19px;
  display:flex;
  align-items:center;
  justify-content:space-between;
  gap:12px;
  background:rgba(255,255,255,.015);
  border-bottom:1px solid var(--border);
}

.lessonHead h3{
  margin:0;
  font-size:17px;
}

.lessonBody{
  padding:19px;
}

.lessonBody p{
  line-height:2;
  color:#c3ccd7;
  margin:0 0 13px;
}

.lessonBody ul{
  line-height:2;
  color:#c3ccd7;
}

.lessonBody li{
  margin:4px 0;
}

.codebox{
  direction:ltr;
  text-align:left;
  font-family:"IBM Plex Mono",monospace;
  white-space:pre-wrap;
  background:#06090e;
  border:1px solid #1e2938;
  color:#a8eee0;
  border-radius:10px;
  padding:15px;
  margin:15px 0;
  overflow:auto;
  font-size:13px;
}

.note{
  border-right:3px solid var(--teal);
  background:rgba(47,191,159,.06);
  padding:13px 15px;
  border-radius:9px;
  color:#c8eee7;
  line-height:1.9;
  margin:14px 0;
}

.warning{
  border-right:3px solid var(--gold);
  background:rgba(210,164,74,.06);
  padding:13px 15px;
  border-radius:9px;
  color:#ead8ad;
  line-height:1.9;
}

.danger{
  border-right:3px solid var(--red);
  background:rgba(226,87,76,.06);
  padding:13px 15px;
  border-radius:9px;
  color:#f0bbb7;
  line-height:1.9;
}

.btn{
  border:1px solid var(--border);
  background:#111925;
  color:white;
  padding:10px 15px;
  border-radius:9px;
  transition:.18s;
}

.btn:hover{
  transform:translateY(-1px);
  border-color:#41516a;
}

.btn.primary{
  background:var(--teal);
  color:#04110e;
  border-color:var(--teal);
  font-weight:700;
}

.btn.gold{
  background:var(--gold);
  color:#171106;
  border-color:var(--gold);
  font-weight:700;
}

.btn.danger{
  background:rgba(226,87,76,.1);
  border-color:rgba(226,87,76,.35);
  color:#ffaaa4;
}

.btn.small{
  padding:7px 10px;
  font-size:12px;
}

.lessonAction{
  margin-top:16px;
  display:flex;
  gap:8px;
  flex-wrap:wrap;
}

.quiz{
  margin-top:20px;
  padding:20px;
  border:1px solid rgba(210,164,74,.25);
  background:rgba(210,164,74,.045);
  border-radius:14px;
}

.quiz h3{
  color:#e7ca8d;
}

.quizOption{
  display:block;
  padding:12px;
  margin:8px 0;
  border:1px solid var(--border);
  border-radius:9px;
  background:rgba(0,0,0,.13);
  cursor:pointer;
}

.quizOption:hover{
  border-color:#53637b;
}

.quizResult{
  margin-top:12px;
  padding:12px;
  border-radius:9px;
  display:none;
}

.quizResult.ok{
  display:block;
  background:rgba(47,191,159,.08);
  border:1px solid rgba(47,191,159,.25);
  color:#b9eee4;
}

.quizResult.bad{
  display:block;
  background:rgba(226,87,76,.08);
  border:1px solid rgba(226,87,76,.25);
  color:#efb3ae;
}

.lockCard{
  text-align:center;
  padding:35px 22px;
}

.lockIcon{
  font-size:45px;
  margin-bottom:10px;
}

.price{
  color:var(--gold);
  font-size:25px;
  font-weight:700;
}

.formGrid{
  display:grid;
  grid-template-columns:repeat(2,minmax(0,1fr));
  gap:12px;
}

.field{
  display:flex;
  flex-direction:column;
  gap:6px;
}

.field label{
  color:#aab6c5;
  font-size:12px;
}

.field input,
.field textarea,
.field select{
  width:100%;
  background:#080C13;
  color:white;
  border:1px solid var(--border);
  border-radius:9px;
  padding:10px 12px;
  outline:none;
}

.field textarea{
  min-height:100px;
  resize:vertical;
}

.field input:focus,
.field textarea:focus,
.field select:focus{
  border-color:var(--teal);
}

.tableWrap{
  overflow:auto;
  border:1px solid var(--border);
  border-radius:10px;
}

table{
  width:100%;
  border-collapse:collapse;
  min-width:580px;
}

th,td{
  padding:11px;
  border-bottom:1px solid var(--border);
  text-align:right;
  font-size:12px;
}

th{
  background:#111824;
  color:#d7e0ea;
}

td{
  color:#aeb9c7;
}

.terminal{
  background:#05080c;
  border:1px solid #1e2938;
  border-radius:13px;
  overflow:hidden;
  direction:ltr;
}

.termTop{
  padding:10px 13px;
  background:#0d131c;
  border-bottom:1px solid #1e2938;
  color:#8290a3;
  font:12px "IBM Plex Mono",monospace;
}

.termOutput{
  min-height:330px;
  max-height:480px;
  overflow:auto;
  padding:16px;
  font:13px/1.8 "IBM Plex Mono",monospace;
  color:#b4eade;
  white-space:pre-wrap;
}

.termInputRow{
  display:flex;
  border-top:1px solid #1e2938;
}

.termPrompt{
  padding:13px 8px 13px 0;
  color:var(--teal);
  font:13px "IBM Plex Mono",monospace;
}

.termInput{
  flex:1;
  background:transparent;
  border:0;
  outline:0;
  color:white;
  padding:13px 8px;
  direction:ltr;
  font:13px "IBM Plex Mono",monospace;
}

.glossaryItem{
  border-bottom:1px solid var(--border);
  padding:15px 0;
}

.glossaryItem:last-child{
  border-bottom:0;
}

.glossaryItem b{
  color:var(--teal);
}

.cert{
  position:relative;
  overflow:hidden;
  background:
    radial-gradient(circle at 50% 0%,rgba(210,164,74,.14),transparent 42%),
    #10151d;
  border:2px solid rgba(210,164,74,.55);
  padding:55px 35px;
  text-align:center;
  min-height:560px;
}

.cert:before{
  content:"";
  position:absolute;
  inset:13px;
  border:1px solid rgba(210,164,74,.3);
  pointer-events:none;
}

.cert .ornament{
  color:var(--gold);
  font-size:30px;
}

.cert h1{
  font-family:Amiri,serif;
  color:#f0d18e;
  font-size:38px;
  margin:20px 0 8px;
}

.cert .name{
  font-size:30px;
  color:white;
  margin:28px 0;
}

.cert small{
  color:#9ca8b7;
}

.certCode{
  margin-top:35px;
  color:#a9b3c0;
  font:11px "IBM Plex Mono",monospace;
}

.ghostIcon{
  position:fixed;
  left:18px;
  bottom:18px;
  z-index:90;
  width:46px;
  height:46px;
  border-radius:50%;
  display:grid;
  place-items:center;
  background:#101722;
  border:1px solid #344155;
  box-shadow:0 10px 30px rgba(0,0,0,.4);
  cursor:pointer;
}

.overlay{
  position:fixed;
  inset:0;
  background:rgba(0,0,0,.72);
  backdrop-filter:blur(3px);
  z-index:80;
}

.modal{
  position:fixed;
  inset:0;
  z-index:100;
  display:grid;
  place-items:center;
  padding:18px;
}

.modalBox{
  width:min(620px,100%);
  max-height:90vh;
  overflow:auto;
  background:#0d131c;
  border:1px solid var(--border);
  border-radius:16px;
  box-shadow:0 30px 90px rgba(0,0,0,.65);
  padding:24px;
}

.modalBox h2{
  margin-bottom:8px;
}

.modalActions{
  display:flex;
  gap:8px;
  flex-wrap:wrap;
  margin-top:18px;
}

.adminTabs{
  display:flex;
  gap:7px;
  flex-wrap:wrap;
  margin-bottom:15px;
}

.adminSection{
  display:none;
}

.adminSection.active{
  display:block;
}

.searchResults{
  margin-top:6px;
  display:none;
}

.searchResults.show{
  display:block;
}

.searchResult{
  padding:9px 11px;
  border:1px solid var(--border);
  background:#0a0f17;
  border-radius:7px;
  margin-top:4px;
  font-size:12px;
  cursor:pointer;
}

.empty{
  padding:45px 20px;
  text-align:center;
  color:var(--muted);
}

.progressBar{
  height:8px;
  background:#080C12;
  border-radius:20px;
  overflow:hidden;
  margin-top:12px;
}

.progressBar span{
  display:block;
  height:100%;
  width:0;
  background:var(--teal);
  transition:.3s;
}

@media(max-width:880px){
  .topbar{
    display:flex;
  }

  .sidebar{
    position:fixed;
    right:0;
    top:0;
    bottom:0;
    height:100dvh;
    transform:translateX(100%);
    transition:transform .25s ease;
    border-inline-start:1px solid var(--border);
    border-inline-end:0;
  }

  .sidebar.open{
    transform:translateX(0);
  }

  .overlay.mobile{
    display:block;
    z-index:65;
  }

  .main{
    padding-top:14px;
  }

  .grid,
  .formGrid{
    grid-template-columns:1fr;
  }

  .stats{
    grid-template-columns:1fr;
  }

  .hero{
    padding:22px;
  }
}

@media(min-width:881px){
  .mobileOverlay{
    display:none!important;
  }
}

@media print{
  body{
    background:white;
    color:black;
  }

  #matrixBg,
  #matrixShade,
  .sidebar,
  .topbar,
  .ghostIcon,
  .noPrint,
  .overlay,
  .modal{
    display:none!important;
  }

  .app,
  .main{
    display:block;
    max-width:none;
    padding:0;
  }

  .cert{
    color:#111;
    min-height:95vh;
    page-break-inside:avoid;
    box-shadow:none;
  }

  .cert .name{
    color:#111;
  }
}
</style>
</head>

<body>

<canvas id="matrixBg"></canvas>
<div id="matrixShade"></div>

<div class="app">

  <aside class="sidebar" id="sidebar">

    <div class="brand">
      <div class="brandIcon">👻</div>
      <div>
        <b>Mr. APT</b>
        <span>أكاديمية الأمن السيبراني</span>
      </div>
    </div>

    <div class="xpBadge">
      🎖️ <span id="tierName">مستكشف</span>
      · <b id="xpCount">0</b> XP
    </div>

    <div class="searchBox">
      <input id="searchInput" type="search" placeholder="🔍 ابحث عن درس أو مصطلح...">
      <div id="searchResults" class="searchResults"></div>
    </div>

    <nav id="nav"></nav>

  </aside>

  <main class="main">

    <div class="topbar">
      <button class="burger" id="burgerBtn">☰</button>
      <b>Mr. APT</b>
      <span></span>
    </div>

    <div id="content"></div>

  </main>

</div>

<div class="ghostIcon" id="ghostIcon" title="لوحة الأدمن">👻</div>

<script>
"use strict";

/* =========================================================
   أدوات عامة
========================================================= */

const $ = id => document.getElementById(id);

function safeJSON(value, fallback){
  try{
    return JSON.parse(value);
  }catch{
    return fallback;
  }
}

function saveJSON(key,value){
  localStorage.setItem(key,JSON.stringify(value));
}

function escapeHTML(value){
  return String(value ?? "")
    .replace(/&/g,"&amp;")
    .replace(/</g,"&lt;")
    .replace(/>/g,"&gt;")
    .replace(/"/g,"&quot;")
    .replace(/'/g,"&#039;");
}

function validTelegramURL(url){
  try{
    const u = new URL(url);
    return u.protocol === "https:" && u.hostname === "t.me";
  }catch{
    return false;
  }
}

async function sha256(text){
  const data = new TextEncoder().encode(text);
  const hash = await crypto.subtle.digest("SHA-256",data);
  return [...new Uint8Array(hash)]
    .map(x=>x.toString(16).padStart(2,"0"))
    .join("");
}

function randomCode(){
  const alphabet = "ABCDEFGHJKLMNPQRSTUVWXYZ23456789";
  const bytes = new Uint8Array(12);
  crypto.getRandomValues(bytes);

  let out = "";
  for(let i=0;i<bytes.length;i++){
    out += alphabet[bytes[i] % alphabet.length];
    if((i+1)%4===0 && i!==bytes.length-1) out += "-";
  }
  return out;
}

function notify(message){
  alert(message);
}

/* =========================================================
   المنهج
========================================================= */

const CURRICULUM = [
  {
    phase:"البداية",
    items:[
      {
        id:"ethics",
        type:"module",
        title:"⚠️ أخلاقيات وقانونية الأمن السيبراني",
        mandatory:true
      }
    ]
  },
  {
    phase:"المرحلة ١ — الأساسيات",
    items:[
      {
        id:"net",
        type:"module",
        title:"🌐 أساسيات الشبكات"
      },
      {
        id:"linux",
        type:"module",
        title:"🐧 أساسيات Linux"
      }
    ]
  },
  {
    phase:"المرحلة ٢ — مبادئ الأمن",
    items:[
      {
        id:"sec",
        type:"module",
        title:"🛡️ مبادئ الأمن السيبراني"
      },
      {
        id:"crypto",
        type:"module",
        title:"🔐 أساسيات التشفير"
      }
    ]
  },
  {
    phase:"مسار الصياد 🔒",
    items:[
      {
        id:"offense",
        type:"locked",
        title:"🎯 الهجوم الأخلاقي واختبار الاختراق",
        tier:"hunter"
      },
      {
        id:"defense",
        type:"locked",
        title:"🛰️ الدفاع والاستجابة للحوادث",
        tier:"hunter"
      }
    ]
  },
  {
    phase:"مسار الشبح 🔒",
    items:[
      {
        id:"reverse",
        type:"locked",
        title:"🧩 الهندسة العكسية وتحليل البرمجيات",
        tier:"ghost"
      },
      {
        id:"bugbounty",
        type:"locked",
        title:"🔎 اكتشاف الثغرات وبناء تقاريرها",
        tier:"ghost"
      }
    ]
  },
  {
    phase:"أدوات الأكاديمية",
    items:[
      {
        id:"freeterm",
        type:"terminal",
        title:"💻 الترمنال التدريبي"
      },
      {
        id:"glossary",
        type:"glossary",
        title:"📖 قاموس المصطلحات"
      },
      {
        id:"cert",
        type:"certpage",
        title:"🎓 شهاداتي"
      }
    ]
  }
];

/* =========================================================
   الدروس المجانية
========================================================= */

const MODULES = {

ethics:{
  title:"أخلاقيات وقانونية الأمن السيبراني",
  lead:"أول درس في الأكاديمية. الهدف أن يتعلم الطالب الفرق بين التعلم الأمني المصرح به وبين الوصول غير المصرح به.",
  lessons:[
    {
      title:"1 — القاعدة الذهبية في الأمن السيبراني",
      body:`
        <p>الأمن السيبراني ليس مجرد معرفة الأدوات. أهم مهارة هي معرفة <b>متى وأين وكيف</b> تستخدم المعرفة.</p>

        <p>أي اختبار أمني حقيقي يجب أن يكون داخل نطاق مصرح به بوضوح، مثل مختبر تعليمي، جهاز شخصي، بيئة CTF، أو نظام توجد موافقة مكتوبة لاختباره.</p>

        <div class="note">
          القاعدة الذهبية: امتلك تصريحًا واضحًا قبل اختبار أي نظام لا تملكه.
        </div>

        <h4>لماذا التصريح مهم؟</h4>
        <ul>
          <li>يحدد الأنظمة المسموح باختبارها.</li>
          <li>يحدد الفترة الزمنية للاختبار.</li>
          <li>يحدد أنواع الاختبارات المسموحة.</li>
          <li>يحدد طريقة التعامل مع البيانات التي تظهر أثناء الاختبار.</li>
          <li>يمنع الخلط بين التدريب الأمني والوصول غير المصرح به.</li>
        </ul>

        <div class="warning">
          في الأكاديمية سيتم استخدام أمثلة تعليمية ومحاكاة وبيئات تدريبية. لا تستخدم المعرفة المكتسبة على حسابات أو أجهزة أو مواقع أشخاص آخرين.
        </div>
      `
    },
    {
      title:"2 — نطاق الاختبار وقواعد الاشتباك",
      body:`
        <p>في الاختبارات الاحترافية يوجد مفهوم مهم يسمى <b>Scope</b>، أي النطاق المسموح باختباره.</p>

        <p>قد يحدد العميل مثلًا تطبيقًا معينًا أو بيئة تجريبية محددة. وجود تصريح لا يعني أن كل أنظمة الشركة أصبحت متاحة للاختبار.</p>

        <h4>قواعد مهمة</h4>
        <ul>
          <li>التزم بالنطاق المحدد.</li>
          <li>لا تجمع بيانات لا تحتاج إليها.</li>
          <li>لا تحاول الوصول إلى حسابات مستخدمين حقيقيين.</li>
          <li>لا توقف خدمة أو تغير بيانات إنتاجية.</li>
          <li>احتفظ بسجل واضح لما فعلته داخل المختبر.</li>
        </ul>

        <div class="codebox">TRAINING SCOPE
Target: training-lab.example
Environment: Authorized Lab
Production Systems: OUT OF SCOPE
Real User Data: PROHIBITED</div>
      `
    },
    {
      title:"3 — المسؤولية المهنية وكتابة التقرير",
      body:`
        <p>المختبر الأمني الاحترافي لا ينتهي بمجرد اكتشاف مشكلة. يجب توثيقها بطريقة تساعد المسؤول عن النظام على فهمها وإصلاحها.</p>

        <h4>التقرير الجيد يحتوي على:</h4>
        <ul>
          <li>عنوان واضح للمشكلة.</li>
          <li>وصف مختصر.</li>
          <li>الأصل أو المكوّن المتأثر.</li>
          <li>الأثر الأمني المحتمل.</li>
          <li>طريقة آمنة لإعادة إنتاج المشكلة داخل بيئة الاختبار.</li>
          <li>اقتراح إصلاح.</li>
          <
