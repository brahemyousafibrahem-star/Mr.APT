
<html lang="ar" dir="rtl">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1,viewport-fit=cover">
<title>Mr. APT — أكاديمية الأمن السيبراني</title>
<style>
:root{--bg:#070a10;--p:#0e131c;--p2:#131a26;--b:#212b3a;--t:#dde3ea;--m:#8792a3;--g:#2fbf9f;--gd:#173f37;--au:#d2a44a;--r:#e2574c}
*{box-sizing:border-box}
html{font-size:16px}
body{margin:0;background:var(--bg);color:var(--t);font-family:system-ui,"Segoe UI",Tahoma,Arial,sans-serif;line-height:1.85;min-height:100dvh;padding-bottom:env(safe-area-inset-bottom,0px)}
.hd{position:sticky;top:0;z-index:40;display:flex;align-items:center;gap:10px;padding:calc(8px + env(safe-area-inset-top,0px)) 12px 8px;background:var(--p);border-bottom:1px solid var(--b)}
.hd .xp{margin-inline-start:auto;font-size:12px;color:var(--au);white-space:nowrap}
.bt{background:var(--p2);border:1px solid var(--b);color:var(--t);border-radius:8px;min-width:34px;height:34px;font-size:14px}
.sb{position:fixed;top:0;bottom:0;right:0;width:280px;background:var(--p);border-left:1px solid var(--b);transform:translateX(100%);transition:transform .25s;z-index:30;overflow-y:auto;padding:calc(60px + env(safe-area-inset-top,0px)) 12px 30px}
.sb.op{transform:none}
.sb input{width:100%;padding:9px 12px;border-radius:8px;border:1px solid var(--b);background:var(--p2);color:var(--t);font:inherit;font-size:13px;margin-bottom:8px}
.ov{display:none;position:fixed;inset:0;background:rgba(0,0,0,.55);z-index:20}
.ov.sh{display:block}
.ni{display:flex;gap:8px;align-items:center;padding:9px;border-radius:8px;cursor:pointer;font-size:14px}
.ni:hover{background:var(--p2)}
.ni.ac{background:var(--gd);color:#b7f3e4}
.ni i{font-style:normal;width:16px;height:16px;border-radius:50%;border:1.5px solid var(--b);font-size:10px;display:flex;align-items:center;justify-content:center;flex:none}
.ni.dn i{background:var(--g);border-color:var(--g);color:#04120e}
.ng{font-size:12px;color:var(--m);font-weight:700;padding:12px 6px 4px}
.mn{padding:18px 14px 90px;max-width:820px;margin:0 auto}
@media(min-width:860px){.sb{transform:none}.mn{margin:0 280px 0 0;max-width:none;padding:26px 40px 90px}#bg,.ov{display:none!important}}
h2{font-size:24px;margin:0 0 6px}
.lead{color:var(--m);font-size:14px;margin:0 0 18px}
.ls{margin-bottom:26px;padding-bottom:20px;border-bottom:1px dashed var(--b)}
.ls h3{font-size:18px;margin:0 0 6px}
.ls p,.ls li{font-size:15px;color:#c7cfda}
.co{background:var(--p2);border:1px solid var(--b);border-inline-start:3px solid var(--g);padding:10px 14px;border-radius:8px;font-size:14px;margin:12px 0}
.co.au{border-inline-start-color:var(--au)}
.cb{background:#05070b;border:1px solid var(--b);border-radius:8px;padding:10px 14px;font:12.5px/1.7 ui-monospace,Menlo,Consolas,monospace;color:#8fe9ce;direction:ltr;text-align:left;overflow-x:auto;white-space:pre}
.btn{background:var(--p2);border:1px solid var(--b);color:var(--t);padding:8px 16px;border-radius:8px;font:inherit;font-size:13px;cursor:pointer}
.btn.ok{background:var(--gd);border-color:var(--g);color:#b7f3e4}
.btn.pr{background:var(--g);color:#04120e;border:none;font-weight:700}
.btn.au{background:var(--au);color:#221a05;border:none;font-weight:700}
.sm{font-size:12px;color:var(--m);margin-inline-start:10px}
.nb{background:var(--p2);border:1px dashed var(--b);border-radius:8px;padding:8px 10px;margin:12px 0}
.nb summary{cursor:pointer;font-size:13px;color:var(--m)}
.nb textarea{width:100%;min-height:70px;background:transparent;border:0;color:var(--t);font:inherit;font-size:14px;resize:vertical;margin-top:6px}
.hint{font-size:13px;color:var(--m);margin:12px 0 4px}
.tm{background:#03050a;border:1px solid var(--b);border-radius:10px;margin:4px 0 12px;overflow:hidden}
.to{padding:10px 12px;font:12.5px/1.6 ui-monospace,Menlo,Consolas,monospace;color:#7cf7cb;direction:ltr;text-align:left;max-height:220px;overflow:auto;white-space:pre-wrap;word-break:break-all}
.tr{display:flex;gap:6px;align-items:center;direction:ltr;padding:8px 12px;border-top:1px solid var(--b)}
.tr span{color:var(--g);font-family:ui-monospace,monospace}
.tr input{flex:1;background:transparent;border:0;outline:0;color:#7cf7cb;font:14px ui-monospace,Menlo,Consolas,monospace;min-width:0}
.q label{display:block;margin:5px 0;font-size:15px}
.xl{display:block;margin:8px 0;font-size:15px;padding:10px 12px;border:1px solid var(--b);border-radius:8px;background:var(--p2)}
.xl.sel{border-color:var(--g);background:var(--gd)}
.gh{position:fixed;bottom:calc(14px + env(safe-area-inset-bottom,0px));left:14px;width:38px;height:38px;border-radius:50%;background:var(--p2);border:1px solid var(--b);display:flex;align-items:center;justify-content:center;cursor:pointer;z-index:25;opacity:.5}
.md{display:none;position:fixed;inset:0;background:rgba(0,0,0,.82);z-index:100;align-items:center;justify-content:center;padding:16px}
.mb{background:var(--p);border:1px solid var(--au);border-radius:14px;padding:22px 20px;max-width:480px;width:100%;max-height:88dvh;overflow-y:auto}
.mb h2{color:var(--au);text-align:center}
.mb input{width:100%;padding:10px;border-radius:8px;border:1px solid var(--b);background:var(--p2);color:var(--t);font:inherit;margin:8px 0}
.ct{background:linear-gradient(160deg,#0a0d13,#060810 55%,#090c13);padding:34px 18px;position:relative;border:2px solid var(--au);border-radius:6px;text-align:center;direction:ltr;outline:1px solid rgba(210,164,74,.35);outline-offset:-9px}
.ct h1{font:700 30px Georgia,serif;color:var(--au);margin:6px 0}
.ct .nm{font:700 26px Georgia,serif;color:#f3ecd9;margin:8px 0;word-break:break-word}
.ct .sr{display:inline-block;font:12px ui-monospace,monospace;color:var(--au);border:1px solid #3a2e15;border-radius:4px;padding:4px 12px;margin-top:12px}
.ct .sg{margin-top:16px;font:italic 20px Georgia,serif;color:#f3ecd9}
.ct .sf{font-size:12px;color:var(--m)}
@media print{body *{visibility:hidden}#cx,#cx *{visibility:visible}#cx{position:absolute;left:0;top:0;width:100%}}
</style>
</head>
<body>
<div class="hd"><button class="bt" id="bg" aria-label="القائمة">☰</button><b>👻 Mr. APT <small style="color:var(--m);font-weight:400">v9</small></b><span class="xp" id="xp"></span><span><button class="bt" id="fm" aria-label="تصغير الخط">A-</button> <button class="bt" id="fp" aria-label="تكبير الخط">A+</button></span></div>
<aside class="sb" id="sb"><input id="sr" placeholder="🔍 ابحث في الدروس"><nav id="nv"></nav></aside>
<div class="ov" id="ov"></div>
<main class="mn" id="mn"></main>
<div class="gh" id="gh" title="Admin">👻</div>
<div class="md" id="dis"></div>
<div class="md" id="lk"><div class="mb"><h2>🔧 المنصة تحت الصيانة</h2><p style="text-align:center">هنرجع قريباً جداً.</p></div></div>
<script>
const CONTACT='https://t.me/MrAPT_Support_bot';
const SITE_LOCKED=false;
const H1='29624e2e4c4ccee26ed8f3e0ca1012ea57a8f2191be6149f632250f7036119cc';
const H2='270fa1445d2cd102ce2ab33bc7e1f03a5a63beabce213c1f495a00ef11e1c5f5';
const $=s=>document.querySelector(s);
const E=s=>String(s).replace(/[&<>"']/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c]));
const L=(k,d)=>{try{const v=localStorage.getItem('ma_'+k);return v===null?d:JSON.parse(v)}catch(e){return d}};
const W=(k,v)=>{try{localStorage.setItem('ma_'+k,JSON.stringify(v))}catch(e){}};
const S={done:L('done',{}),aw:L('aw',{}),xp:L('xp',0),name:L('name',''),notes:L('notes',{}),fs:L('fs',16),snd:L('snd',true),cur:L('cur','ethics'),ex:L('ex',{})};

const C=[
{id:'ethics',t:'⚠️ أخلاقيات وقانونية القرصنة (إجباري)',d:'أول درس إجباري: لازم تخلّصه كله قبل أي محتوى تاني.',
ls:[
{t:'القاعدة الذهبية',h:'<p>الاختراق الأخلاقي هو اختبار أنظمة <b>مصرّح لك كتابياً</b> باختبارها فقط. أي دخول لنظام أو حساب بدون إذن صريح <b>جريمة</b> يعاقب عليها القانون في معظم دول العالم.</p><div class="co au"><b>القاعدة:</b> لا تصريح كتابي = لا تلمس النظام. نقطة.</div>'},
{t:'التصريح والنطاق (Scope)',h:'<p>أي اختبار قانوني يبدأ بعقد أو تصريح مكتوب يحدد: الأنظمة المسموح باختبارها (النطاق)، والأوقات، والأساليب الممنوعة. الخروج عن النطاق ولو بالخطأ قد يحوّل الاختبار إلى مخالفة قانونية.</p><p>تدرّب دائماً على أجهزة تملكها أو على معامل تدريب مخصصة لهذا الغرض، ولا تجرّب أبداً على حسابات أو شبكات الآخرين.</p>'}
],
q:[{q:'اختراق نظام بدون إذن كتابي صريح يُعتبر:',o:['تدريباً عادياً','جريمة قانونية','مسموحاً لو الهدف تعليمي','غير مهم'],a:1},{q:'النطاق (Scope) في عقد الاختبار يحدد:',o:['السعر فقط','الأنظمة المسموح باختبارها والأساليب','اسم الفريق','لون التقرير'],a:1}]},
{id:'net',t:'أساسيات الشبكات',d:'حجر الأساس لأي متخصص أمن. كل درس فيه تمرين ترمنال محاكاة.',
ls:[
{t:'نموذج TCP/IP',h:'<p>كل اتصال شبكي يمر عبر طبقات. الإنترنت يعمل عملياً بنموذج <b>TCP/IP</b> المكوّن من 4 طبقات، بينما نموذج <b>OSI</b> النظري له 7 طبقات ويُستخدم للتعليم والتشخيص.</p><ul><li><b>التطبيقات:</b> HTTP وDNS وSMTP</li><li><b>النقل:</b> TCP (موثوق) وUDP (سريع) وأرقام المنافذ</li><li><b>الإنترنت:</b> عناوين IP والتوجيه</li><li><b>الوصلة:</b> عناوين MAC والسويتشات والكابلات</li></ul><div class="co"><b>ليه يهمك؟</b> أدوات مثل Wireshark بتعرض البيانات طبقة بطبقة، وفهم الطبقة الصحيحة بيسرّع اكتشاف المشكلة أو الهجوم.</div>',
cm:{'ip a':'1: lo  127.0.0.1/8\n2: wlan0  192.168.1.23/24  (محاكاة)','ping 8.8.8.8':'64 bytes from 8.8.8.8: icmp_seq=1 ttl=117 time=23 ms\n64 bytes from 8.8.8.8: icmp_seq=2 ttl=117 time=22 ms\n(محاكاة)'}},
{t:'عناوين IP والشبكات الفرعية',h:'<p>كل جهاز يحتاج عنوان IP. الشبكات الفرعية تقسّم شبكة كبيرة إلى أصغر عبر ترميز <b>CIDR</b>. الرقم بعد الشرطة المائلة هو عدد بتات الشبكة.</p><div class="cb">192.168.1.0/24  → 256 عنوان (254 قابل للاستخدام)\n10.0.0.0/8      → نطاق خاص كبير\n172.16.0.0/12   → نطاق خاص متوسط\n192.168.0.0/16  → نطاق خاص شائع في البيوت</div><div class="co au"><b>أهمية أمنية:</b> معرفة النطاقات الخاصة تساعدك تميّز الأجهزة الداخلية عن المكشوفة على الإنترنت.</div>',
cm:{'ip route':'default via 192.168.1.1 dev wlan0\n192.168.1.0/24 dev wlan0 src 192.168.1.23','ipcalc 192.168.1.0/24':'Network:   192.168.1.0/24\nBroadcast: 192.168.1.255\nHosts:     254 usable'}},
{t:'TCP والمنافذ',h:'<p>TCP يبني اتصالاً موثوقاً عبر مصافحة ثلاثية: <b>SYN ← SYN/ACK ← ACK</b>. أما UDP فأسرع لكنه لا يضمن الوصول.</p><div class="cb">22   SSH\n23   Telnet (نص صريح، غير آمن)\n53   DNS\n80   HTTP\n443  HTTPS\n3389 RDP</div><div class="co au"><b>تنبيه:</b> أي خدمة مفتوحة على منفذ هي سطح هجوم محتمل، فلا تفتح إلا ما تحتاجه.</div>',
cm:{'ss -tulnp':'tcp LISTEN 0.0.0.0:22  sshd\ntcp LISTEN 0.0.0.0:80  apache2\n(محاكاة)','nmap -sV target.lab':'PORT    STATE SERVICE VERSION\n22/tcp  open  ssh     OpenSSH 8.2\n80/tcp  open  http    Apache 2.4.41\n(محاكاة على هدف تدريبي)'}},
{t:'أجهزة الشبكة: Switch وRouter وFirewall',h:'<p>لكل جهاز دور محدد وطبقة يعمل فيها:</p><ul><li><b>Hub:</b> جهاز قديم يكرر أي بيانات لكل المنافذ فيقدر أي جهاز يشوفها. اختفى تقريباً.</li><li><b>Switch:</b> يتعلم عناوين MAC ويرسل الإطار للمنفذ المقصود فقط (الطبقة 2).</li><li><b>Router:</b> يوجّه الحزم بين شبكات مختلفة باستخدام عناوين IP (الطبقة 3). والبوابة الافتراضية (Default Gateway) هي الراوتر الذي يخرج منه جهازك للإنترنت.</li><li><b>Firewall:</b> يسمح أو يمنع الحركة حسب قواعد (مصدر ووجهة ومنفذ وبروتوكول).</li><li><b>Access Point:</b> يوصّل الأجهزة اللاسلكية بالشبكة السلكية.</li></ul><div class="co"><b>مثال:</b> لما تفتح موقعاً، يصل طلبك للراوتر ثم يمر عبر عدة راوترات حتى يصل للسيرفر. الأمر <code>traceroute</code> يعرض هذه المحطات.</div>',cm:{'traceroute 8.8.8.8':'1  192.168.1.1   1.2 ms\n2  10.20.0.1      8.4 ms\n3  172.16.5.9    14.9 ms\n4  8.8.8.8       23.1 ms\n(محاكاة)','ping 192.168.1.1':'64 bytes from 192.168.1.1: time=1.1 ms\n(محاكاة)'}},
{t:'نظام أسماء النطاقات DNS',h:'<p>الحاسوب لا يفهم <b>example.com</b> بل يحتاج عنوان IP. مهمة DNS ترجمة الاسم إلى عنوان. الخطوات المبسطة:</p><ol><li>جهازك يسأل الـ <b>Resolver</b> (غالباً عند مزود الإنترنت أو 8.8.8.8).</li><li>لو لا يعرف الإجابة يسأل خادم <b>Root</b>، ثم خادم النطاق العلوي (مثل .com)، ثم الخادم المسؤول عن الموقع.</li><li>يعود العنوان ويُحفظ مؤقتاً (Cache) لمدة TTL.</li></ol><div class="cb">A      name -> IPv4\nAAAA   name -> IPv6\nCNAME  alias of another name\nMX     mail servers\nNS     authoritative name servers\nTXT    text (SPF, ownership checks)</div><div class="co au"><b>أمنياً:</b> تسميم DNS (DNS Spoofing) يجعل المستخدم يصل لموقع مزيف بنفس الاسم. من وسائل الحماية: DNSSEC وHTTPS والحذر من الشبكات العامة.</div>',cm:{'nslookup example.com':'Name:    example.com\nAddress: 192.0.2.10\n(محاكاة: العنوان من نطاق التوثيق)','dig example.com MX':'example.com. 3600 IN MX 10 mail.example.com.\n(محاكاة)'}},
{t:'HTTP وHTTPS وTLS',h:'<p><b>HTTP</b> هو بروتوكول الطلب والرد بين المتصفح والسيرفر. المتصفح يرسل <b>طلباً</b> (Method + مسار + Headers) والسيرفر يرد <b>برد</b> فيه كود حالة ومحتوى.</p><div class="cb">GET /index.html HTTP/1.1\nHost: example.com\n\nHTTP/1.1 200 OK\nContent-Type: text/html</div><ul><li><b>GET:</b> طلب بيانات. <b>POST:</b> إرسال بيانات (نموذج تسجيل مثلاً).</li><li><b>200</b> نجاح، <b>301</b> إعادة توجيه دائمة، <b>403</b> ممنوع، <b>404</b> غير موجود، <b>500</b> خطأ في السيرفر.</li></ul><p><b>HTTPS</b> هو HTTP داخل قناة مشفرة <b>TLS</b>، ويحقق ثلاثة أشياء: السرية (لا أحد يقرأ)، والسلامة (لا أحد يعدّل)، والتحقق من هوية الموقع عبر الشهادة الرقمية.</p><div class="co au"><b>مهم:</b> القفل في المتصفح يعني أن الاتصال مشفر، ولا يعني أن الموقع نفسه موثوق أو آمن.</div>',cm:{'curl -I https://example.com':'HTTP/2 200\ncontent-type: text/html\nstrict-transport-security: max-age=31536000\n(محاكاة)'}},
{t:'DHCP وNAT وARP',h:'<p><b>DHCP</b> يمنح جهازك عنوان IP وبوابة وDNS تلقائياً عند الاتصال. خطواته الأربع: Discover ثم Offer ثم Request ثم Acknowledge.</p><p><b>NAT</b>: بيتك كله يخرج للإنترنت بعنوان عام واحد، والراوتر يسجل جدولاً يربط كل جهاز داخلي ومنفذه بالاتصال الخارجي فيعرف لأي جهاز يعيد الرد.</p><p><b>ARP</b>: داخل الشبكة المحلية، الجهاز يعرف عنوان IP للهدف لكنه يحتاج عنوان MAC، فيسأل الجميع: من يملك هذا العنوان؟ فيرد صاحبه، وتُحفظ النتيجة في جدول ARP.</p><div class="co au"><b>أمنياً:</b> ARP لا يتحقق من صحة الرد، وهذا ما يسمح بهجوم ARP Spoofing على الشبكات المحلية غير المحمية. لذلك لا تثق في الشبكات العامة.</div>',cm:{'arp -a':'gateway (192.168.1.1) at aa:bb:cc:11:22:33 on wlan0\nphone   (192.168.1.40) at aa:bb:cc:44:55:66 on wlan0\n(محاكاة)','ip neigh':'192.168.1.1 dev wlan0 lladdr aa:bb:cc:11:22:33 REACHABLE\n(محاكاة)'}},
{t:'أمن الشبكات: الجدار الناري ومراقبة الحركة',h:'<p>بعد فهم الأساسيات ننتقل للحماية:</p><ul><li><b>قواعد الجدار الناري:</b> ابدأ بمنع كل شيء ثم اسمح فقط بما تحتاجه (مبدأ أقل الصلاحيات).</li><li><b>مراقبة الحركة:</b> أدوات مثل <b>Wireshark</b> و<b>tcpdump</b> تلتقط الحزم لتحليل مشكلة أو كشف نشاط مشبوه، وتُستخدم فقط على شبكتك أو بتصريح.</li><li><b>التشفير:</b> استخدم SSH بدل Telnet وHTTPS بدل HTTP، لأن النص الصريح يمكن قراءته لو التُقطت الحزم.</li><li><b>الفصل:</b> افصل الأجهزة الحساسة عن أجهزة الضيوف في شبكات فرعية مختلفة.</li></ul><div class="co"><b>قاعدة عملية:</b> أي منفذ مفتوح لا تحتاجه اقفله، وأي خدمة قديمة لا تحدّثها ابعد عنها.</div>',cm:{'sudo ufw status':'Status: active\n22/tcp   ALLOW   Anywhere\n80/tcp   ALLOW   Anywhere\n(محاكاة)','tcpdump -i wlan0 -c 2':'IP 192.168.1.23.51544 > 192.0.2.10.443: Flags [S]\nIP 192.0.2.10.443 > 192.168.1.23.51544: Flags [S.]\n(محاكاة)'}},
{t:'الشبكات اللاسلكية Wi-Fi وأمنها',h:'<p>الشبكات اللاسلكية تبث بياناتها في الهواء، فأي جهاز في المدى يستطيع التقاط الإشارة. لذلك يعتمد أمانها على التشفير:</p><ul><li><b>WEP:</b> مكسور تماماً ويُكسر في دقائق، لا تستخدمه أبداً.</li><li><b>WPA2:</b> المعيار الشائع، وآمن مع كلمة مرور قوية.</li><li><b>WPA3:</b> الأحدث، ويحمي أفضل ضد تخمين كلمة المرور دون اتصال.</li></ul><div class="co au"><b>تأمين شبكة البيت:</b> استخدم WPA2 أو WPA3 بكلمة مرور طويلة، وعطّل WPS، وغيّر كلمة مرور لوحة الراوتر الافتراضية، وحدّث برنامج الراوتر.</div><div class="co"><b>الشبكات العامة:</b> افترض أن أي شبكة مفتوحة قد تكون مراقبة أو مزيفة. استخدم HTTPS وVPN ولا تدخل حسابات حساسة عليها.</div>',cm:{'nmcli dev wifi':'SSID        SECURITY  SIGNAL\nHomeNet     WPA2      82\nCafeFree    --        64   (شبكة مفتوحة!)\nOffice-5G   WPA3      55\n(محاكاة)'}},
{t:'IPv6 وأساسياته',h:'<p>عناوين IPv4 (32 بت) لم تعد تكفي، فجاء <b>IPv6</b> بعنوان من <b>128 بت</b> يُكتب بثمانية أجزاء سداسية عشرية، ويمكن اختصار الأصفار المتتالية مرة واحدة برمز <code>::</code>.</p><div class="cb">2001:db8:0:0:0:0:0:1  ->  2001:db8::1\n::1        loopback (this device)\nfe80::/10  link-local (same network only)\nfc00::/7   unique local (private)\n2000::/3   global unicast (public)</div><ul><li>الأجهزة غالباً تأخذ عنوانها تلقائياً (SLAAC) دون DHCP.</li><li>لا حاجة عادةً لـ NAT لأن العناوين كافية.</li></ul><div class="co au"><b>أمنياً:</b> أمّن IPv6 بالجدار الناري كما تؤمّن IPv4، فكثير من الشبكات تركته مفتوحاً دون أن ينتبه أصحابها.</div>',cm:{'ip -6 addr':'inet6 2001:db8::23/64 scope global\ninet6 fe80::a1b2:c3ff:fe00:1/64 scope link\n(محاكاة)','ping -6 ::1':'64 bytes from ::1: icmp_seq=1 ttl=64 time=0.05 ms\n(محاكاة)'}},
{t:'ICMP وتشخيص مشاكل الاتصال',h:'<p><b>ICMP</b> بروتوكول رسائل التحكم والأخطاء في الشبكة. أداة <b>ping</b> ترسل Echo Request وتنتظر Echo Reply لتعرف هل الجهاز متاح وكم زمن الاستجابة. و<b>traceroute</b> يرفع قيمة TTL تدريجياً ليكشف كل راوتر في الطريق.</p><p><b>منهجية بسيطة لتشخيص عطل الاتصال:</b></p><ol><li>اختبر جهازك: <code>ping 127.0.0.1</code></li><li>اختبر الراوتر: <code>ping 192.168.1.1</code></li><li>اختبر الإنترنت بالعنوان: <code>ping 8.8.8.8</code></li><li>اختبر الأسماء: <code>nslookup example.com</code></li></ol><div class="co">لو نجح الاختبار بالعنوان وفشل بالاسم، فالمشكلة في DNS.</div>',cm:{'ping -c 2 192.168.1.1':'64 bytes from 192.168.1.1: icmp_seq=1 time=1.1 ms\n64 bytes from 192.168.1.1: icmp_seq=2 time=1.0 ms\n2 packets transmitted, 2 received, 0% loss\n(محاكاة)','dig +short example.com':'192.0.2.10\n(محاكاة)'}},
{t:'VPN والوكيل (Proxy)',h:'<p><b>VPN</b> ينشئ نفقاً مشفراً بين جهازك وخادم VPN، فيرى مزود الإنترنت والشبكة المحلية حركة مشفرة فقط، وتظهر المواقع عنوان خادم VPN بدل عنوانك.</p><ul><li><b>يفيد في:</b> حماية بياناتك على الشبكات العامة، والوصول الآمن لشبكة العمل.</li><li><b>لا يعني:</b> الإخفاء التام، فمزود VPN نفسه يرى حركتك، والمواقع تعرفك من حسابك وتسجيل دخولك.</li></ul><p><b>الوكيل (Proxy)</b> يمرر طلباتك عبر وسيط، لكنه في الغالب لا يشفّر حركتك.</p><div class="co au"><b>نصيحة:</b> اختر مزوداً معروفاً وموثوقاً، فالخدمات المجانية المجهولة قد تبيع بياناتك.</div>',cm:{'curl ifconfig.me':'203.0.113.5\n(محاكاة: عنوانك العام الظاهر للمواقع)','ip a show tun0':'tun0: inet 10.8.0.2/24\n(محاكاة: واجهة VPN)'}},
{t:'فحص الشبكة بأمان باستخدام Nmap',h:'<p><b>Nmap</b> أداة لاكتشاف الأجهزة والمنافذ المفتوحة، يستخدمها المدافع ليعرف ما هو مكشوف في شبكته قبل المهاجم.</p><div class="cb">nmap -sn 192.168.1.0/24    find live hosts only\nnmap -p 22,80 192.168.1.10 scan chosen ports\nnmap -sV 192.168.1.10      detect service versions</div><p>حالات المنفذ: <b>open</b> مفتوح وفيه خدمة، <b>closed</b> مغلق، <b>filtered</b> محجوب غالباً بجدار ناري فلا يمكن التأكد.</p><div class="co au"><b>قانونياً:</b> افحص فقط شبكتك أو شبكة لديك <b>تصريح كتابي</b> بفحصها. فحص شبكات الآخرين بدون إذن قد يكون جريمة.</div>',cm:{'nmap -sn 192.168.1.0/24':'Host 192.168.1.1 is up\nHost 192.168.1.23 is up\nHost 192.168.1.40 is up\nNmap done: 256 IP addresses (3 hosts up)\n(محاكاة)','nmap -p 22,80 192.168.1.10':'PORT   STATE    SERVICE\n22/tcp open     ssh\n80/tcp filtered http\n(محاكاة)'}},
{t:'تحليل الحزم: Wireshark وtcpdump',h:'<p>التقاط الحزم يعرض ما يحدث فعلاً على الشبكة. <b>Wireshark</b> بواجهة رسومية، و<b>tcpdump</b> من سطر الأوامر. استخدمهما فقط على شبكتك أو بتصريح، فالتقاط حركة الآخرين قد يكون مخالفاً للقانون.</p><div class="cb">ip.addr == 192.168.1.10   Wireshark: packets of one host\ntcp.port == 80            Wireshark: web traffic\ndns                       Wireshark: DNS only\n\ntcpdump -i wlan0 port 53 -c 5\ntcpdump -nn host 192.168.1.10 -c 5</div><div class="co">الخيار <code>-c 5</code> يوقف الالتقاط بعد 5 حزم، و<code>-nn</code> يمنع تحويل الأرقام لأسماء.</div>',cm:{'tcpdump -i wlan0 port 53 -c 2':'IP 192.168.1.23.40211 > 8.8.8.8.53: A? example.com\nIP 8.8.8.8.53 > 192.168.1.23.40211: A 192.0.2.10\n(محاكاة)','tcpdump -nn host 192.168.1.10 -c 2':'IP 192.168.1.23.51544 > 192.168.1.10.80: Flags [S]\nIP 192.168.1.10.80 > 192.168.1.23.51544: Flags [S.]\n(محاكاة)'}},
{t:'نموذج OSI بطبقاته السبع',h:'<div class="cb">7 Application   HTTP, DNS, SMTP       data\n6 Presentation  encoding, TLS          data\n5 Session       sessions between apps  data\n4 Transport     TCP, UDP, ports        segments\n3 Network       IP, routers            packets\n2 Data Link     MAC, switches          frames\n1 Physical      cables, radio          bits</div><p>حفظ الترتيب يساعد في التشخيص: لو الكابل مفصول فالمشكلة في الطبقة 1، ولو العنوان خاطئ ففي الطبقة 3، ولو الخدمة لا ترد فغالباً في الطبقة 7.</p><div class="co">ما يُسمى <b>Layer 2 Switch</b> يعمل بعناوين MAC، و<b>Layer 3 Switch</b> يوجّه بعناوين IP أيضاً.</div>',cm:{'ip link':'1: lo: <LOOPBACK,UP>\n2: wlan0: <BROADCAST,MULTICAST,UP> link/ether aa:bb:cc:11:22:33\n(محاكاة)'}},
{t:'الشبكات المحلية الافتراضية VLAN',h:'<p><b>VLAN</b> تقسّم شبكة السويتش الواحد إلى شبكات منطقية معزولة، فلا ترى الأجهزة في VLAN بعضها إلا عبر راوتر يسمح بذلك.</p><ul><li>كل VLAN لها رقم (مثل 10 للموظفين و20 للضيوف).</li><li>الرابط الذي ينقل عدة VLAN بين سويتشين يسمى <b>Trunk</b> ويستخدم معيار 802.1Q.</li><li>الانتقال بين VLAN يحتاج <b>Inter-VLAN Routing</b> مع قواعد جدار ناري.</li></ul><div class="co au"><b>فائدة أمنية:</b> فصل الضيوف وأجهزة IoT عن الأجهزة المهمة يحدّ من انتشار الاختراق لو أصيب جهاز واحد.</div>',cm:{'ip -d link show eth0.10':'eth0.10@eth0: <BROADCAST,UP>\n  vlan protocol 802.1Q id 10\n(محاكاة)'}},
{t:'التوجيه: ثابت وديناميكي',h:'<p>الراوتر يقرر لأي وجهة يرسل الحزمة بالنظر في <b>جدول التوجيه</b>، ويختار المسار ذو <b>أطول بادئة مطابقة</b> (Longest Prefix Match)، وإن لم يجد يستخدم المسار الافتراضي.</p><ul><li><b>ثابت (Static):</b> يكتبه المسؤول يدوياً، بسيط لكنه لا يتكيف.</li><li><b>ديناميكي:</b> الراوترات تتبادل المسارات بنفسها: <b>OSPF</b> داخل المؤسسة، و<b>BGP</b> بين مزودي الإنترنت.</li></ul><div class="cb">192.168.1.0/24 dev wlan0\n10.0.0.0/8     via 192.168.1.254\ndefault        via 192.168.1.1</div>',cm:{'ip route get 8.8.8.8':'8.8.8.8 via 192.168.1.1 dev wlan0 src 192.168.1.23\n(محاكاة)','ip route':'default via 192.168.1.1 dev wlan0\n192.168.1.0/24 dev wlan0 src 192.168.1.23\n(محاكاة)'}},
{t:'Port Forwarding وDMZ والخدمات المكشوفة',h:'<p><b>Port Forwarding</b> يوجّه منفذاً من عنوانك العام إلى جهاز داخلي، فيصبح الجهاز مكشوفاً للإنترنت مباشرة. استخدمه فقط عند الحاجة، وللخدمات المحدّثة والمحمية.</p><p><b>DMZ</b> شبكة معزولة تضم الخوادم التي يجب أن تُرى من الخارج (مثل الموقع)، بحيث إذا اخترقت لا يصل المهاجم مباشرة للشبكة الداخلية.</p><div class="co au"><b>قاعدة:</b> كل منفذ تفتحه على الإنترنت سيُفحص خلال دقائق من فاحصات آلية حول العالم. لا تفتح لوحة تحكم الراوتر ولا الكاميرات ولا قواعد البيانات للإنترنت.</div>',cm:{'curl -I http://203.0.113.5:8080':'HTTP/1.1 401 Unauthorized\nServer: camera-web\n(محاكاة: كاميرا مكشوفة للإنترنت، هذا خطر)'}},
{t:'هجمات الشبكة الشائعة وكيف تُكتشف',h:'<ul><li><b>DoS/DDoS:</b> إغراق الخدمة بالطلبات لتعطيلها. مثال <b>SYN Flood</b>: آلاف طلبات SYN بلا إكمال المصافحة.</li><li><b>MITM:</b> وضع مهاجم نفسه بين طرفين للتنصت أو التعديل، مثل ARP Spoofing.</li><li><b>Sniffing:</b> التقاط حركة غير مشفرة.</li><li><b>Port Scan:</b> استكشاف المنافذ المفتوحة تمهيداً لهجوم.</li></ul><div class="co au"><b>الكشف والحماية:</b> راقب أعداد الاتصالات غير المكتملة والارتفاع المفاجئ في الحركة، واستخدم HTTPS وSSH، وقيّد الحركة بالجدار الناري، واستعن بخدمات حماية DDoS.</div>',cm:{'netstat -an | grep SYN_RECV | wc -l':'412\n(محاكاة: عدد كبير غير طبيعي من اتصالات نصف مفتوحة)'}},
{t:'الجدران النارية وأنظمة IDS وIPS',h:'<ul><li><b>Stateless:</b> يفحص كل حزمة منفردة.</li><li><b>Stateful:</b> يتتبع حالة الاتصال فيسمح فقط بالردود المتوقعة.</li><li><b>NGFW:</b> جدار متقدم يفهم التطبيقات والمستخدمين.</li><li><b>WAF:</b> يحمي تطبيقات الويب من الحقن وغيره.</li></ul><p><b>IDS</b> يكتشف ويُنبّه فقط. <b>IPS</b> يكتشف ويمنع. من أشهر أدواتهما مفتوحة المصدر <b>Snort</b> و<b>Suricata</b>.</p><div class="co">التنبيه بلا مراجعة عديم الفائدة، فالمهم أن يقرأ أحد السجلات ويضبط القواعد لتقليل الإنذارات الكاذبة.</div>',cm:{'cat /var/log/suricata/fast.log':'09/29-02:14 [**] SCAN Possible port scan [**] 203.0.113.9 -> 192.168.1.10\n(محاكاة)'}},
{t:'أمان البروتوكولات: القديم مقابل الآمن',h:'<div class="cb">FTP     -> SFTP / FTPS   file transfer\nTelnet  -> SSH           remote login\nHTTP    -> HTTPS         web\nSMTP/IMAP/POP3 -> with TLS\nSNMP v1/v2 -> SNMP v3    device monitoring</div><p>البروتوكولات القديمة ترسل بيانات الدخول <b>نصاً صريحاً</b>، فأي شخص يلتقط الحزمة يقرأ كلمة المرور. عند فحص شبكتك، ابحث عن الخدمات القديمة وعطّلها أو استبدلها.</p>',cm:{'nmap -sV -p 21,22,23 192.168.1.10':'PORT   STATE  SERVICE VERSION\n21/tcp open   ftp     vsftpd 3.0.3   (قديم غير مشفر)\n22/tcp open   ssh     OpenSSH 8.2\n23/tcp closed telnet\n(محاكاة)'}},
{t:'جودة الشبكة: السرعة والتأخر وضياع الحزم',h:'<ul><li><b>Bandwidth:</b> أقصى كمية بيانات في الثانية.</li><li><b>Latency:</b> زمن تأخر وصول الحزمة (يقاس بالميلي ثانية).</li><li><b>Jitter:</b> تذبذب زمن التأخر، يفسد المكالمات والألعاب.</li><li><b>Packet Loss:</b> نسبة الحزم الضائعة في الطريق.</li></ul><p>أداة <b>ping</b> تقيس التأخر والضياع، و<b>iperf3</b> تقيس السرعة بين جهازين تملكهما. ارتفاع الضياع أو التأخر المفاجئ قد يدل على ازدحام أو عطل أو هجوم.</p>',cm:{'ping -c 3 8.8.8.8':'3 packets transmitted, 3 received, 0% packet loss\nrtt min/avg/max = 22.1/23.4/25.0 ms\n(محاكاة)','iperf3 -c 192.168.1.10':'[ ID] Interval    Transfer   Bitrate\n[  5] 0.0-10.0 sec 112 MBytes  94.0 Mbits/sec\n(محاكاة)'}},
{t:'مشروع ختامي: تصميم شبكة صغيرة آمنة',h:'<p>اجمع ما تعلمته في خطة لشبكة مكتب صغير:</p><ol><li><b>التقسيم:</b> شبكات منفصلة للموظفين والضيوف والخوادم (VLAN).</li><li><b>الجدار الناري:</b> امنع كل شيء ثم اسمح بالضروري، مع فصل الضيوف عن الداخل.</li><li><b>الواي فاي:</b> WPA3 أو WPA2 بكلمة مرور قوية، وشبكة ضيوف منفصلة.</li><li><b>الوصول عن بعد:</b> VPN وSSH بمفاتيح، بدون Telnet أو فتح منافذ الإدارة للإنترنت.</li><li><b>المراقبة:</b> جمع السجلات وتنبيهات IDS.</li><li><b>الصيانة:</b> تحديثات منتظمة ونسخ احتياطي.</li></ol><div class="co au">هذه الخطة هي طريقة تفكير أي مهندس أمن: قسّم، قيّد، شفّر، راقب، حدّث.</div>',cm:{'cat network_plan.txt':'VLAN 10 staff    192.168.10.0/24\nVLAN 20 guests   192.168.20.0/24 (no access to VLAN 10)\nVLAN 30 servers  192.168.30.0/24\nFirewall: default deny\nWiFi: WPA3, guest separate\nRemote: VPN only\n(محاكاة)'}}
],
q:[{q:'أي بروتوكول ينقل البيانات كنص صريح غير مشفر؟',o:['SSH','Telnet','HTTPS','TLS'],a:1},{q:'تسلسل مصافحة TCP الصحيح؟',o:['ACK→SYN→FIN','SYN→SYN/ACK→ACK','SYN→ACK→SYN','FIN→SYN→ACK'],a:1},{q:'192.168.0.0/16 هو نطاق:',o:['عام على الإنترنت','خاص','لـ DNS فقط','IPv6'],a:1},{q:'أي جهاز يوجّه الحزم بين شبكات مختلفة باستخدام IP؟',o:['Hub','Switch','Router','Access Point'],a:2},{q:'وظيفة DNS هي:',o:['تشفير الاتصال','ترجمة الأسماء إلى عناوين IP','توزيع عناوين MAC','منع الفيروسات'],a:1},{q:'ماذا يعني قفل HTTPS في المتصفح؟',o:['الموقع آمن تماماً','الاتصال مشفر لكن لا يضمن أمان الموقع','الموقع رسمي','لا توجد فيروسات'],a:1},{q:'خطوات DHCP بالترتيب:',o:['Discover ثم Offer ثم Request ثم Acknowledge','Request ثم Offer ثم Discover ثم Acknowledge','Offer ثم Discover ثم Request','Acknowledge ثم Request ثم Offer'],a:0}]},
{id:'linux',t:'أساسيات Linux و Kali',d:'من الصفر: الملفات، الأوامر، الصلاحيات، العمليات، والسكربتات. كل درس فيه ترمنال محاكاة.',
ls:[
{t:'ما هو Linux وما هو Kali؟',h:'<p><b>Linux</b> هو نواة (Kernel) لنظام تشغيل مفتوح المصدر، وتُوزَّع مع أدوات وبرامج في نسخ تسمى <b>توزيعات</b> مثل Ubuntu وDebian. أغلب السيرفرات في العالم تعمل بـLinux، فتعلمه أساسي لأي متخصص أمن.</p><p><b>Kali Linux</b> توزيعة مبنية على Debian من شركة Offensive Security، تأتي بمئات أدوات الفحص الأمني الجاهزة، وهي مخصصة للاختبار المصرّح به فقط.</p><div class="co au"><b>نصيحة:</b> ثبّت Kali أو Ubuntu على <b>جهاز افتراضي</b> (VirtualBox مثلاً) أو استخدم معامل تدريب، حتى لا تؤثر تجاربك على جهازك الأساسي.</div>',cm:{'uname -a':'Linux kali 6.x.x-kali-amd64 x86_64 GNU/Linux\n(محاكاة)','cat /etc/os-release':'PRETTY_NAME="Kali GNU/Linux Rolling"\nID=kali\n(محاكاة)'}},
{t:'هيكل نظام الملفات',h:'<p>في Linux كل شيء ملف أو مجلد، وكلها تبدأ من الجذر <b>/</b>. أهم المجلدات:</p><div class="cb">/        root of the whole system\n/home    users files\n/root    home of the root user\n/etc     configuration files\n/var/log logs (important in investigations)\n/tmp     temporary files\n/bin     essential commands\n/usr     programs and libraries</div><div class="co">المسارات حساسة لحالة الأحرف: <code>Notes.txt</code> غير <code>notes.txt</code>.</div>',cm:{'pwd':'/home/trainee','ls /':'bin  etc  home  root  tmp  usr  var\n(محاكاة)'}},
{t:'التنقل وإدارة الملفات',h:'<div class="cb">pwd            show current path\nls -la         list all files with details\ncd /etc        go to a folder (cd .. = up)\nmkdir project  create a folder\ntouch a.txt    create an empty file\ncp a.txt b.txt copy\nmv b.txt c.txt move or rename\nrm c.txt       delete a file</div><div class="co au"><b>تحذير:</b> <code>rm -rf</code> يحذف مجلداً بكل محتوياته <b>بدون رجعة وبدون سلة مهملات</b>. اقرأ الأمر مرتين قبل الإدخال، وخصوصاً لو كتبت معه /.</div>',cm:{'ls -la':'drwxr-xr-x 2 trainee trainee 4096 notes\n-rw-r--r-- 1 trainee trainee  120 hello.sh\n(محاكاة)','mkdir project':'(تم إنشاء المجلد project)','touch notes.txt':'(تم إنشاء الملف notes.txt)'}},
{t:'قراءة الملفات والبحث والأنابيب',h:'<div class="cb">cat file       print a whole file\nless file      read page by page\nhead -n 5 file first 5 lines\ntail -n 5 file last 5 lines\ngrep word file search inside a file\nfind / -name x search files by name\nwc -l file     count lines</div><p><b>الأنبوب |</b> يمرر ناتج أمر كمدخل لأمر آخر، مثل <code>cat log | grep Failed</code>. و<b>&gt;</b> تكتب الناتج في ملف (وتمسح القديم)، و<b>&gt;&gt;</b> تضيف في آخره.</p><div class="co">أهم أداة لمحلل الأمن في لينكس هي <b>grep</b>، لأن التحقيق غالباً يعني البحث داخل ملفات سجلات ضخمة.</div>',cm:{'cat /etc/hostname':'kali','grep root /etc/passwd':'root:x:0:0:root:/root:/bin/bash\n(محاكاة)','tail -n 2 /var/log/auth.log':'Sep 20 03:14 sshd: Failed password for admin\nSep 20 03:15 sshd: Accepted password for trainee\n(محاكاة)'}},
{t:'المستخدمون والصلاحيات',h:'<p>كل ملف له مالك ومجموعة، وثلاث صلاحيات: <b>r</b> قراءة (4) و<b>w</b> كتابة (2) و<b>x</b> تنفيذ (1) لكل من: المالك، المجموعة، الآخرين.</p><div class="cb">-rwxr-xr-x  = 755  (owner all, others read+run)\n-rw-r--r--  = 644  (owner edit, others read)\n-rw-------  = 600  (owner only)\n\nchmod 755 script.sh\nchown user:group file\nsudo command   run as admin</div><p>حساب <b>root</b> يملك كل الصلاحيات، لذلك لا تعمل به يومياً. استخدم حساباً عادياً و<b>sudo</b> عند الحاجة فقط (مبدأ أقل الصلاحيات). كلمات المرور المشفرة تُحفظ في <code>/etc/shadow</code> ولا يقرؤها إلا root.</p>',cm:{'id':'uid=1000(trainee) gid=1000(trainee) groups=1000(trainee),27(sudo)\n(محاكاة)','ls -l script.sh':'-rw-r--r-- 1 trainee trainee 60 script.sh\n(محاكاة)','chmod 755 script.sh':'(تم: الملف أصبح rwxr-xr-x)','sudo -l':'User trainee may run: (ALL : ALL) ALL\n(محاكاة)'}},
{t:'العمليات والخدمات',h:'<p><b>العملية (Process)</b> هي أي برنامج شغال. <b>الخدمة (Service)</b> هي عملية تعمل في الخلفية مثل SSH أو Apache.</p><div class="cb">ps aux                 list all processes\ntop                    live view of resources\nkill PID               ask a process to stop\nkill -9 PID            force stop\nsystemctl status ssh   check a service\nsystemctl start ssh    start it\nsystemctl enable ssh   start at boot\njournalctl -u ssh      service logs</div><div class="co au"><b>أمنياً:</b> كل خدمة شغالة سطح هجوم محتمل، فأوقف وعطّل أي خدمة لا تحتاجها.</div>',cm:{'ps aux':'USER  PID %CPU COMMAND\nroot    1  0.0 /sbin/init\nroot  512  0.0 /usr/sbin/sshd\n(محاكاة)','systemctl status ssh':'ssh.service - OpenBSD Secure Shell server\n   Active: active (running)\n(محاكاة)','journalctl -u ssh -n 2':'sshd[512]: Server listening on 0.0.0.0 port 22\nsshd[600]: Accepted password for trainee\n(محاكاة)'}},
{t:'إدارة الحزم والتحديثات',h:'<p>في Debian وKali وUbuntu تُثبَّت البرامج عبر <b>apt</b> من مستودعات رسمية موقّعة.</p><div class="cb">sudo apt update          refresh package lists\nsudo apt upgrade         install available updates\nsudo apt install nmap    install a tool\nsudo apt remove nmap     remove it\napt search wireshark     search packages</div><div class="co"><b>قاعدة أمنية:</b> أغلب الاختراقات الناجحة تستغل ثغرات معروفة لها تحديث موجود أصلاً. التحديث المنتظم من أرخص وأقوى وسائل الحماية.</div>',cm:{'sudo apt update':'Hit:1 http://kali.download/kali kali-rolling InRelease\nReading package lists... Done\n(محاكاة)','apt search nmap':'nmap/kali-rolling  Network exploration tool and security scanner\n(محاكاة)'}},
{t:'سكربتات Bash',h:'<p>السكربت ملف نصي فيه أوامر تُنفَّذ بالترتيب، وهو أساس أتمتة الأعمال المتكررة في الأمن.</p><div class="cb">#!/bin/bash\nname="Mr. APT"\necho "Hello $name"\nfor i in 1 2 3; do\n  echo "Round $i"\ndone</div><ol><li>السطر الأول <b>#!/bin/bash</b> يحدد المفسّر.</li><li>احفظه باسم hello.sh، ثم امنحه صلاحية التنفيذ: <code>chmod +x hello.sh</code>.</li><li>شغّله: <code>./hello.sh</code>.</li></ol><div class="co">المتغير يُعرَّف بدون مسافات حول علامة =، ويُقرأ بعلامة $ قبل اسمه.</div>',cm:{'cat hello.sh':'#!/bin/bash\nname="Mr. APT"\necho "Hello $name"\nfor i in 1 2 3; do echo "Round $i"; done','chmod +x hello.sh':'(تم: الملف قابل للتنفيذ)','./hello.sh':'Hello Mr. APT\nRound 1\nRound 2\nRound 3'}},
{t:'السجلات وتأمين النظام',h:'<p>السجلات هي ذاكرة النظام: من دخل، ومتى، وماذا فشل. أهمها في <code>/var/log</code>، مثل <b>auth.log</b> لمحاولات الدخول. كثرة رسائل <b>Failed password</b> من نفس العنوان تدل غالباً على محاولة تخمين كلمة المرور.</p><p><b>خطوات تأمين أساسية:</b></p><ul><li>حدّث النظام باستمرار.</li><li>استخدم مفاتيح SSH بدل كلمات المرور، وعطّل دخول root المباشر.</li><li>فعّل جدار الحماية وأغلق المنافذ غير اللازمة.</li><li>اعمل بحساب عادي وليس root.</li></ul>',cm:{'grep "Failed password" /var/log/auth.log':'Sep 20 03:14 sshd: Failed password for root from 203.0.113.9\nSep 20 03:14 sshd: Failed password for root from 203.0.113.9\n(محاكاة)','last -n 2':'trainee pts/0 192.168.1.23  still logged in\nreboot  system boot 6.x.x-kali\n(محاكاة)','ssh-keygen -t ed25519':'Generating public/private ed25519 key pair.\nYour public key: ~/.ssh/id_ed25519.pub\n(محاكاة)'}},
{t:'معالجة النصوص: cut وsort وuniq',h:'<p>أغلب عمل المحلل الأمني هو تحويل ملفات ضخمة إلى معلومة مفيدة. الأدوات الصغيرة تعمل معاً عبر الأنبوب:</p><div class="cb">cut -d: -f1 file    take field 1 using : as separator\nsort file           sort lines\nuniq -c             count repeated lines (input must be sorted)\nwc -l file          count lines\nawk \'{print $1}\' f  print first column</div><div class="co"><b>مثال عملي:</b> لمعرفة أكثر عناوين IP تكراراً في سجل: <code>cat ips.txt | sort | uniq -c | sort -nr</code>. لاحظ أن uniq لا يعمل إلا بعد sort.</div>',cm:{'cut -d: -f1 /etc/passwd':'root\ndaemon\nsshd\ntrainee\n(محاكاة)','cat ips.txt | sort | uniq -c':'      3 203.0.113.9\n      1 198.51.100.7\n(محاكاة)'}},
{t:'الشبكات من داخل لينكس',h:'<div class="cb">ip a               interfaces and addresses\nip route           routing table\nss -tulnp          listening ports and their programs\ncurl -I URL        fetch only HTTP headers\nwget URL           download a file\nssh user@host      secure remote login\nscp file user@host:/path   secure copy</div><p><b>SSH</b> يعطيك ترمنال عن بعد بتشفير كامل، وهو بديل آمن عن Telnet. وأول اتصال بجهاز جديد يطلب منك قبول بصمة مفتاحه، فلا تقبلها دون تأكد أنك تتصل بالجهاز الصحيح.</p>',cm:{'ssh trainee@192.168.1.10':'The authenticity of host 192.168.1.10 can not be established.\nAre you sure you want to continue connecting (yes/no)?\n(محاكاة)','curl -I http://192.168.1.10':'HTTP/1.1 200 OK\nServer: Apache/2.4.41\nContent-Type: text/html\n(محاكاة)'}},
{t:'الأقراص والضغط والنسخ الاحتياطي',h:'<div class="cb">df -h                     disk space per partition\ndu -sh /var/log           size of a folder\ntar -czf b.tar.gz dir     archive + compress\ntar -xzf b.tar.gz         extract\nsha256sum b.tar.gz        fingerprint of the backup</div><p>الأمر <b>tar</b> يجمع الملفات في أرشيف واحد، و<b>gz</b> يضغطه. بعد أخذ نسخة احتياطية احسب بصمتها لتتأكد لاحقاً أنها لم تتلف أو تتغير.</p><div class="co au"><b>تنبيه:</b> امتلاء القرص (100%) قد يوقف الخدمات ويوقف تسجيل السجلات، ولذلك يراقبه المسؤولون باستمرار.</div>',cm:{'df -h':'Filesystem  Size  Used Avail Use% Mounted on\n/dev/sda1    50G   21G   27G  44% /\n(محاكاة)','du -sh /var/log':'340M\t/var/log\n(محاكاة)','tar -czf backup.tar.gz project':'(تم إنشاء backup.tar.gz)'}},
{t:'المهام المجدولة Cron',h:'<p><b>cron</b> ينفّذ أوامر تلقائياً في أوقات محددة. كل سطر في جدول <code>crontab</code> فيه 5 حقول للوقت ثم الأمر:</p><div class="cb">m  h  dom mon dow  command\n0  2  *   *   *    /home/trainee/backup.sh\n*/15 * *  *   *    /usr/bin/check_disk.sh\n\ncrontab -l   list your jobs\ncrontab -e   edit your jobs</div><p>الحقول بالترتيب: الدقيقة، الساعة، اليوم من الشهر، الشهر، اليوم من الأسبوع. المثال الأول يشغّل النسخ الاحتياطي الساعة 2 فجراً يومياً.</p><div class="co au"><b>أمنياً:</b> المهاجم قد يزرع مهمة cron ليعود بها بعد إعادة التشغيل، فراجع الجداول بانتظام.</div>',cm:{'crontab -l':'0 2 * * * /home/trainee/backup.sh\n*/15 * * * * /usr/bin/check_disk.sh\n(محاكاة)','date':'Tue Sep 29 02:00:01 2026\n(محاكاة)'}},
{t:'تقوية أمان لينكس بالتفصيل',h:'<p>خطوات التقوية (Hardening) الأساسية:</p><ul><li><b>SSH:</b> في ملف <code>/etc/ssh/sshd_config</code> ضع <code>PermitRootLogin no</code> و<code>PasswordAuthentication no</code> بعد إعداد مفاتيح SSH.</li><li><b>الجدار الناري:</b> اسمح فقط بالمنافذ اللازمة.</li><li><b>الحسابات:</b> احذف الحسابات غير المستخدمة وقيّد sudo.</li><li><b>التحديثات:</b> فعّل التحديثات الأمنية التلقائية.</li><li><b>الحماية من التخمين:</b> أدوات مثل fail2ban تحظر عنوان IP بعد محاولات فاشلة متكررة.</li></ul><div class="co">أداة <b>Lynis</b> تفحص نظامك وتعطي درجة وتوصيات، وهي مفيدة لمراجعة جهازك.</div>',cm:{'grep PermitRootLogin /etc/ssh/sshd_config':'PermitRootLogin no\n(محاكاة)','sudo ufw allow 22/tcp':'Rule added\n(محاكاة)'}},
{t:'البحث المتقدم عن الملفات وحالتها',h:'<div class="cb">find /etc -name "*.conf"       by name\nfind / -type f -size +100M     files bigger than 100MB\nfind / -mtime -1               modified in the last day\nstat file                      size, owner, times\nln -s /var/log logs            create a symbolic link</div><p>البحث عن <b>الملفات المعدّلة حديثاً</b> أداة مهمة في التحقيق: بعد حادثة، ما الذي تغيّر خلال آخر ساعات؟ و<b>الرابط الرمزي</b> ملف صغير يشير إلى ملف أو مجلد آخر، وحذفه لا يحذف الأصل.</p>',cm:{'find /etc -mtime -1':'/etc/hosts\n/etc/ssh/sshd_config\n(محاكاة: ملفات تغيّرت اليوم)','stat notes.txt':'File: notes.txt\nSize: 120  Access: (0644/-rw-r--r--)  Uid: (1000/trainee)\n(محاكاة)','ln -s /var/log logs':'(تم إنشاء الرابط logs -> /var/log)'}},
{t:'الصلاحيات الخاصة: SUID وSGID وSticky',h:'<ul><li><b>SUID (s في خانة المالك):</b> الملف يُنفَّذ بصلاحيات <b>مالكه</b> وليس من يشغّله. مثل أمر passwd الذي يحتاج تعديل ملف محمي.</li><li><b>SGID:</b> نفس الفكرة لصلاحيات المجموعة.</li><li><b>Sticky bit (t):</b> على مجلد مثل <code>/tmp</code> يمنع أي مستخدم من حذف ملفات غيره.</li></ul><div class="cb">-rwsr-xr-x  /usr/bin/passwd   (SUID)\ndrwxrwxrwt  /tmp              (sticky)\n\nfind / -perm -4000 2>/dev/null</div><div class="co au"><b>تدقيق دفاعي:</b> أي ملف SUID غير معروف أو في مكان غريب يستحق التحقيق، لأن الخطأ فيه قد يرفع صلاحيات مستخدم عادي إلى root.</div>',cm:{'ls -l /usr/bin/passwd':'-rwsr-xr-x 1 root root 59976 /usr/bin/passwd\n(محاكاة)','find / -perm -4000 2>/dev/null':'/usr/bin/passwd\n/usr/bin/sudo\n/usr/bin/su\n(محاكاة: قائمة SUID الطبيعية)'}},
{t:'متغيرات البيئة وPATH والاختصارات',h:'<div class="cb">echo $PATH        folders searched for commands\nenv              all environment variables\nexport NAME=val  set a variable for child programs\nalias ll="ls -la"  shortcut\n~/.bashrc        loaded at each new terminal</div><p>عند كتابة أمر، يبحث الشل عنه في مجلدات <b>PATH</b> بالترتيب. لو أضاف مهاجم مجلداً يتحكم فيه في بداية PATH فقد ينفَّذ برنامجه بدل الأمر الأصلي، لذلك لا تضع مجلدات غير موثوقة أو <code>.</code> في PATH.</p>',cm:{'echo $PATH':'/usr/local/bin:/usr/bin:/bin:/usr/sbin\n(محاكاة)','env':'HOME=/home/trainee\nUSER=trainee\nSHELL=/bin/bash\n(محاكاة)'}},
{t:'إدارة المستخدمين والمجموعات',h:'<div class="cb">sudo useradd -m ali          create user with home\nsudo passwd ali              set password\nsudo usermod -aG sudo ali    add to a group (keep others)\ngroups ali                   list groups\nsudo userdel -r ali          delete user and home</div><p>انتبه: <code>usermod -G</code> بدون <b>-a</b> يستبدل كل مجموعات المستخدم! أما ملف <code>/etc/passwd</code> فكل سطر فيه: الاسم، رقم المستخدم UID، المجموعة، المجلد الرئيسي، والشل.</p><div class="co au"><b>أمنياً:</b> راجع دورياً من هم أعضاء sudo، واحذف الحسابات التي لم تعد مستخدمة.</div>',cm:{'sudo useradd -m ali':'(تم إنشاء المستخدم ali)','groups trainee':'trainee : trainee sudo\n(محاكاة)','sudo usermod -aG sudo ali':'(أضيف ali إلى مجموعة sudo)'}},
{t:'التحكم في المهام والعمل في الخلفية',h:'<div class="cb">command &      run in the background\njobs           list background jobs\nfg %1          bring job 1 to the front\nCtrl+Z         pause current program\nbg             continue it in background\nCtrl+C         stop current program\nnohup cmd &    keep running after logout</div><p>هذا مفيد عند تشغيل مهمة طويلة، مثل نسخ احتياطي أو فحص، دون حجز الترمنال. وأدوات مثل <b>tmux</b> تحفظ جلستك حتى لو انقطع الاتصال.</p>',cm:{'sleep 100 &':'[1] 1234','jobs':'[1]+  Running   sleep 100 &\n(محاكاة)','nohup ./long_task.sh &':'[2] 1301\nnohup: ignoring input and appending output to nohup.out\n(محاكاة)'}},
{t:'سكربتات Bash: الشروط والدوال والوسائط',h:'<div class="cb">#!/bin/bash\nfile="$1"\nif [ -f "$file" ]; then\n  echo "Found: $file"\nelse\n  echo "Missing: $file"; exit 1\nfi</div><ul><li><b>$1 و$2:</b> الوسائط الممرَّرة للسكربت.</li><li><b>$?:</b> رمز خروج آخر أمر (0 يعني نجاح).</li><li><b>[ -f file ]:</b> هل الملف موجود؟</li><li><b>exit 1:</b> إنهاء بخطأ.</li></ul><div class="co">ضع المتغيرات بين علامتي اقتباس "$var" حتى لا ينكسر السكربت عند وجود مسافات في الأسماء.</div>',cm:{'cat check.sh':'#!/bin/bash\nfile="$1"\nif [ -f "$file" ]; then echo "Found: $file"; else echo "Missing: $file"; exit 1; fi','./check.sh /etc/passwd':'Found: /etc/passwd','./check.sh /nope':'Missing: /nope'}},
{t:'النسخ الاحتياطي والمزامنة بـ rsync',h:'<div class="cb">rsync -av src/ dest/            copy changes only\nrsync -av src/ user@host:/backup/  over SSH\nrsync -av --delete src/ dest/     mirror (deletes extras!)\nrsync -av --dry-run src/ dest/    preview without changes</div><p><b>rsync</b> ينسخ الفروقات فقط فيكون أسرع بكثير من النسخ الكامل. الخيار <b>-a</b> يحفظ الصلاحيات والتواريخ، و<b>-v</b> يعرض التفاصيل. وجود الشرطة المائلة في آخر src/ يغيّر المعنى، فانتبه لها.</p><div class="co au"><b>تحذير:</b> جرّب <code>--dry-run</code> دائماً قبل <code>--delete</code>، فالخطأ فيه يحذف ملفات فعلاً.</div>',cm:{'rsync -av project/ /backup/project/':'sending incremental file list\nnotes.txt\nsent 1,204 bytes  received 35 bytes\n(محاكاة)','rsync -av --dry-run project/ /backup/project/':'sending incremental file list\n(dry run) لن يتم تغيير أي شيء\n(محاكاة)'}},
{t:'الجدار الناري في لينكس: ufw وiptables',h:'<p>الجدار الناري في لينكس يعمل داخل النواة عبر <b>netfilter</b>، وأدواته: <b>iptables/nftables</b> (تفصيلية) و<b>ufw</b> (مبسطة).</p><div class="cb">sudo ufw default deny incoming\nsudo ufw allow 22/tcp\nsudo ufw deny 23/tcp\nsudo ufw enable\nsudo ufw status verbose\n\nsudo iptables -L -n     list rules</div><div class="co au"><b>ترتيب مهم:</b> اسمح بمنفذ SSH <b>قبل</b> تفعيل الجدار إذا كنت متصلاً عن بعد، وإلا ستحبس نفسك خارج الاتصال.</div>',cm:{'sudo ufw status verbose':'Status: active\nLogging: on (low)\nDefault: deny (incoming), allow (outgoing)\n(محاكاة)','sudo iptables -L -n':'Chain INPUT (policy DROP)\ntarget     prot opt source       destination\nACCEPT     tcp  --  0.0.0.0/0    0.0.0.0/0  tcp dpt:22\n(محاكاة)'}}
],
q:[{q:'أي أمر يعرض المسار الحالي؟',o:['pwd','cd','ls','path'],a:0},{q:'أي صلاحية تعني التنفيذ؟',o:['r','w','x','e'],a:2},{q:'ما وظيفة grep؟',o:['تشفير الملفات','البحث داخل النصوص','حذف الملفات','تثبيت البرامج'],a:1},{q:'ما معنى chmod 755؟',o:['المالك كل الصلاحيات والآخرون قراءة وتنفيذ','الجميع كتابة فقط','المالك قراءة فقط','لا أحد يستطيع التنفيذ'],a:0},{q:'ما الأمر الذي يعرض العمليات؟',o:['ps aux','pwd','df','chmod'],a:0},{q:'ما مدير الحزم في Kali؟',o:['npm','apt','pip فقط','gem'],a:1},{q:'ما فائدة sudo؟',o:['تشغيل أمر بصلاحيات إدارية','حذف النظام','فتح منفذ','تشفير كلمة المرور'],a:0}]},
{id:'sec',t:'مبادئ الأمن السيبراني',d:'السرية والسلامة والتوافر، التهديدات، المصادقة، التشفير، وإدارة المخاطر.',
ls:[
{t:'مثلث CIA',h:'<p>أمن المعلومات يقوم على ثلاثة أهداف أساسية:</p><ul><li><b>Confidentiality — السرية:</b> لا يرى البيانات إلا المصرح لهم.</li><li><b>Integrity — السلامة:</b> لا تتغير البيانات دون تصريح.</li><li><b>Availability — التوافر:</b> النظام والبيانات متاحان عند الحاجة.</li></ul><div class="co">أي إجراء أمني يجب أن تفكر في تأثيره على الأهداف الثلاثة.</div>'},
{t:'التهديدات والثغرات والمخاطر',h:'<p><b>التهديد</b> شيء قد يسبب ضرراً، و<b>الثغرة</b> نقطة ضعف، و<b>الخطر</b> هو احتمال استغلال الضعف وما ينتج عنه.</p><div class="cb">Threat × Vulnerability × Impact = Risk</div><p>إدارة المخاطر لا تعني جعل الخطر صفراً، بل تحديد الأخطار وترتيبها وتقليلها إلى مستوى مقبول.</p>'},
{t:'المصادقة Authorization Authentication',h:'<p><b>Authentication</b> = من أنت؟ و<b>Authorization</b> = ماذا يسمح لك أن تفعل؟</p><ul><li>شيء تعرفه: كلمة مرور.</li><li>شيء تملكه: هاتف أو مفتاح أمني.</li><li>شيء فيك: بصمة.</li></ul><p>المصادقة متعددة العوامل تجمع عاملين أو أكثر، ولا تعني مجرد استخدام كلمتي مرور.</p>'},
{t:'كلمات المرور والتخزين الآمن',h:'<p>لا تُخزّن كلمات المرور كنص صريح. تُخزّن كـ<b>hash</b> باستخدام خوارزميات مخصصة مثل Argon2 أو bcrypt مع salt فريد.</p><div class="co au"><b>مهم:</b> التشفير يمكن فكّه بالمفتاح، أما الـhash مصمم ليكون أحادي الاتجاه.</div>'},
{t:'التشفير المتماثل وغير المتماثل',h:'<p><b>Symmetric</b> يستخدم مفتاحاً واحداً للتشفير وفك التشفير، وهو سريع للبيانات الكبيرة. <b>Asymmetric</b> يستخدم زوج مفاتيح: عام وخاص، ويُستخدم في التوقيعات وتبادل المفاتيح.</p><div class="cb">AES       symmetric encryption\nRSA/ECC   asymmetric cryptography\nSHA-256   hash (not encryption)\nEd25519   digital signatures</div>'},
{t:'الشهادات الرقمية وPKI',h:'<p>الشهادة الرقمية تربط هوية باسم نطاق بمفتاح عام، وتوقّعها جهة إصدار موثوقة CA. المتصفح يتحقق من سلسلة الثقة وصلاحية الشهادة واسم النطاق.</p><p>هذا هو الأساس الذي يجعل HTTPS يثبت أنك تتصل بالنطاق المقصود، وليس مجرد قناة مشفرة.</p>'},
{t:'الهندسة الاجتماعية والتصيد',h:'<p>الهجوم قد يستهدف الإنسان بدل التقنية. <b>Phishing</b> رسائل مزيفة تطلب بيانات أو تحثك على فتح رابط، و<b>Vishing</b> عبر الهاتف، و<b>Smishing</b> عبر الرسائل.</p><div class="co au"><b>قاعدة:</b> لا تضغط رابطاً مشبوهاً ولا تدخل كلمة مرور بعد رابط وصل إليك بشكل غير متوقع. افتح الموقع من عنوان تعرفه.</div>'},
{t:'البرمجيات الخبيثة',h:'<ul><li><b>Virus:</b> يلتصق بملف وينتشر عند تشغيله.</li><li><b>Worm:</b> ينتشر تلقائياً بين الأجهزة.</li><li><b>Trojan:</b> برنامج يبدو شرعياً لكنه خبيث.</li><li><b>Ransomware:</b> يمنع الوصول للبيانات ويطلب فدية.</li><li><b>Spyware:</b> يجمع معلومات عن المستخدم.</li></ul><p>الحماية تشمل التحديثات، أقل الصلاحيات، النسخ الاحتياطي، فلترة البريد، ومراقبة السلوك.</p>'},
{t:'الدفاع متعدد الطبقات',h:'<p>لا تعتمد على أداة واحدة. استخدم طبقات: هوية قوية، تحديثات، جدار ناري، EDR/مكافحة برمجيات خبيثة، تقسيم الشبكة، نسخ احتياطية، سجلات ومراقبة، وتدريب المستخدمين.</p><div class="co">إذا فشلت طبقة، يجب أن تمنع طبقة أخرى الحادث أو تقلل أثره.</div>'}
],
q:[{q:'ماذا تعني Confidentiality؟',o:['التوافر','السرية','السلامة','التسجيل'],a:1},{q:'ما الفرق الصحيح؟',o:['Authentication من أنت وAuthorization ماذا يسمح لك','العكس','هما نفس الشيء','لا علاقة لهما بالأمن'],a:0},{q:'أي خوارزمية هي Hash؟',o:['AES','RSA','SHA-256','TLS'],a:2},{q:'ما هو التصيد Phishing؟',o:['تشفير الملفات','خداع المستخدم للحصول على معلومات أو دفعه لفعل شيء','نسخ احتياطي','تحديث النظام'],a:1},{q:'أي نوع ينتشر تلقائياً بين الأجهزة؟',o:['Worm','Trojan','Virus فقط','Hash'],a:0}]},
{id:'crypto',t:'التشفير والتطبيقات العملية',d:'مفاهيم التشفير، التجزئة، التوقيع، TLS، والممارسات الآمنة.',
ls:[
{t:'ما المشكلة التي يحلها التشفير؟',h:'<p>التشفير يحوّل البيانات من نص مفهوم إلى صيغة لا يفهمها من لا يملك المفتاح المناسب. في الأنظمة الحديثة نستخدمه لحماية البيانات أثناء النقل وأثناء التخزين.</p>'},
{t:'AES وChaCha20',h:'<p>AES وChaCha20 خوارزميات تشفير متماثل سريعة. لا تخترع خوارزمية بنفسك؛ استخدم مكتبات موثوقة ووضعيات تشفير حديثة مثل AES-GCM أو ChaCha20-Poly1305.</p>'},
{t:'Hash وSalt',h:'<p>الـhash بصمة للبيانات. عند تخزين كلمات المرور، يستخدم كل مستخدم <b>salt</b> عشوائياً وفريداً لمنع جداول rainbow وتقليل فائدة hash المسروق.</p>'},
{t:'HMAC',h:'<p><b>HMAC</b> يجمع hash مع مفتاح سري لإثبات سلامة الرسالة ومعرفة أن من أنشأها يملك المفتاح. يستخدم مثلاً في بعض واجهات API.</p>'},
{t:'التوقيع الرقمي',h:'<p>يوقّع المرسل البيانات بمفتاحه الخاص، ويتحقق المستقبل بالمفتاح العام. التوقيع يثبت المصدر ويكشف التعديل، لكنه لا يشفّر المحتوى بالضرورة.</p>'},
{t:'TLS عملياً',h:'<p>عند فتح HTTPS، يتفاوض الطرفان على خوارزميات ومفاتيح جلسة، ويتحقق العميل من شهادة الخادم، ثم تستخدم مفاتيح الجلسة لتشفير البيانات بسرعة.</p><div class="co au"><b>ملاحظة:</b> لا تتجاوز تحذيرات الشهادة في المتصفح لمجرد فتح الموقع.</div>'}
],
q:[{q:'أي خوارزمية تشفير متماثل؟',o:['AES','RSA','Ed25519','SHA-256'],a:0},{q:'وظيفة salt مع كلمات المرور؟',o:['زيادة طول كلمة المرور','منع تشابه hashes وتقليل فائدة الجداول الجاهزة','فك التشفير','إرسال كلمة المرور'],a:1},{q:'هل التوقيع الرقمي يشفّر المحتوى؟',o:['نعم دائماً','لا، وظيفته الأساسية إثبات المصدر والسلامة','فقط في HTTP','فقط مع AES'],a:1}]}
];

const EX={};
function buildExams(){
 C.forEach(c=>{
  EX[c.id]=[];
  const n=c.ls.length;
  for(let i=5;i<=n;i+=5){
   const to=Math.min(i+4,n);
   const qs=c.q.slice(0,Math.min(c.q.length,5)).map(q=>({q:q.q,o:q.o,a:q.a}));
   if(qs.length)EX[c.id].push({t:'امتحان الدروس '+i+'–'+to,f:i,to:to,q:qs});
  }
 });
}
buildExams();

function ethicsDone(){return !!S.done['ethics:0']&&!!S.done['ethics:1']}
function award(k,n){if(S.aw[k])return;S.aw[k]=1;S.xp+=n;W('aw',S.aw);W('xp',S.xp)}
function qbest(id,sc){const k='q:'+id;if(S.aw[k])return;if(sc>=Math.ceil(C.find(x=>x.id===id).q.length*.6))award(k,25)}
function sv(){W('done',S.done);W('xp',S.xp);W('aw',S.aw);W('notes',S.notes);W('name',S.name);W('ex',S.ex)}
function closeSb(){$('#sb').classList.remove('op');$('#ov').classList.remove('sh')}
function nav(){
 const n=$('#nv'),term=($('#sr').value||'').trim().toLowerCase();
 n.innerHTML='';
 C.forEach(c=>{
  if(term&&!(c.t+' '+c.d+' '+c.ls.map(x=>x.t).join(' ')).toLowerCase().includes(term))return;
  const h=document.createElement('div');h.className='ng';h.textContent=c.t;
  n.appendChild(h);
  c.ls.forEach((l,i)=>{
   const b=document.createElement('div');b.className='ni '+(S.cur===c.id?'ac':'')+' '+(S.done[c.id+':'+i]?'dn':'');
   b.innerHTML='<i>'+(S.done[c.id+':'+i]?'✓':(i+1))+'</i><span>'+E(l.t)+'</span>';
   b.onclick=()=>{S.cur=c.id;W('cur',S.cur);closeSb();render();scrollTo(0,0)};
   n.appendChild(b)
  });
  EX[c.id].forEach((x,j)=>{
   const id='x:'+c.id+':'+j,b=document.createElement('div');b.className='ni '+(S.cur===id?'ac':'');
   b.innerHTML='<i>📝</i><span>'+E(x.t)+'</span>';
   b.onclick=()=>{S.cur=id;W('cur',S.cur);closeSb();render();scrollTo(0,0)};
   n.appendChild(b)
  })
 });
 [['cert','🏆 الشهادة'],['verify','🔎 تحقق من شهادة'],['terms','📜 الشروط والخصوصية']].forEach(([id,t])=>{
  const b=document.createElement('div');b.className='ni '+(S.cur===id?'ac':'');b.innerHTML='<i>•</i><span>'+t+'</span>';b.onclick=()=>{S.cur=id;W('cur',S.cur);closeSb();render();scrollTo(0,0)};n.appendChild(b)
 })
}
function hud(){$('#xp').textContent='XP: '+S.xp}
function beep(){if(!S.snd)return;try{const a=new AudioContext(),o=a.createOscillator(),g=a.createGain();o.frequency.value=620;g.gain.value=.025;o.connect(g);g.connect(a.destination);o.start();o.stop(a.currentTime+.035)}catch(e){}}
function course(c){
 let h='<h2>'+c.t+'</h2><p class="lead">'+c.d+'</p>';
 c.ls.forEach((l,i)=>{
  const k=c.id+':'+i;
  h+='<section class="ls"><h3>'+(i+1)+'. '+l.t+'</h3>'+l.h;
  if(l.cm){
   h+='<div class="hint">🖥️ ترمنال محاكاة — جرّب أحد الأوامر التالية:</div><div class="tm"><div class="to" data-o="'+k+'"></div><div class="tr"><span>trainee@lab:~$</span><input data-t="'+k+'" placeholder="اكتب أمراً ثم Enter"></div></div>'
  }
  h+='<details class="nb"><summary>📝 ملاحظتي الشخصية</summary><textarea data-n="'+k+'" placeholder="اكتب ملاحظتك هنا...">'+E(S.notes[k]||'')+'</textarea></details>';
  h+='<button class="btn '+(S.done[k]?'ok':'')+'" data-l="'+k+'">'+(S.done[k]?'✓ مكتمل':'تحديد كمكتمل')+'</button></section>'
 });
 h+='<div class="co"><b>اختبار الوحدة:</b> '+c.q.length+' أسئلة. احصل على 60% أو أكثر لتسجيل أفضل نتيجة.</div><div class="q" id="qf">';
 c.q.forEach((q,i)=>{h+='<div class="ls"><p><b>'+(i+1)+'. '+q.q+'</b></p>'+q.o.map((o,j)=>'<label><input type="radio" name="q'+i+'" value="'+j+'"> '+o+'</label>').join('')+'</div>'});
 h+='</div><button class="btn pr" id="qc">تصحيح الاختبار</button> <span id="qr" class="sm"></span>';
 return h
}
function serial(n){let x=n.trim()||'Student Name';let z=0;for(let i=0;i<x.length;i++)z=(z*31+x.charCodeAt(i))>>>0;return'MRA-'+z.toString(16).toUpperCase().padStart(8,'0')}
function certPg(){return '<h2>🏆 شهادة إتمام</h2><p class="lead">اكتب اسمك كما تريد ظهوره على الشهادة.</p><input id="cn" style="width:100%;padding:10px;border-radius:8px;border:1px solid var(--b);background:var(--p2);color:var(--t);font:inherit;margin-bottom:12px" placeholder="اسم الطالب"><div class="ct" id="cx"><h1>Certificate of Completion</h1><div class="sf">This certifies that</div><div class="nm" id="cnm"></div><div class="sf">has successfully completed the Foundations Track</div><div class="sr" id="cs"></div><div class="sg">Mr. Taha</div><div class="sf">Mr. Taha — Founder</div></div><br><button class="btn pr" id="cp">طباعة / حفظ PDF</button>'}
function verifyPg(){return '<h2>✅ تحقق من شهادة</h2><p class="lead">اكتب اسم صاحب الشهادة ورقمها التسلسلي.</p><input id="vn" style="width:100%;padding:10px;border-radius:8px;border:1px solid var(--b);background:var(--p2);color:var(--t);font:inherit;margin-bottom:8px" placeholder="الاسم"><input id="vs" style="width:100%;padding:10px;border-radius:8px;border:1px solid var(--b);background:var(--p2);color:var(--t);font:inherit;margin-bottom:8px;direction:ltr" placeholder="MRA-XXXXXXXX"><button class="btn pr" id="vb">تحقق</button><p id="vr"></p>'}
function terms(){return '<h2>📜 الشروط والخصوصية</h2><div class="ls"><h3>الاستخدام</h3><p>المنصة للتعليم الأخلاقي فقط، وهي وصاحبها غير مسؤولين عن أي استخدام غير قانوني للمحتوى.</p></div><div class="ls"><h3>البيانات</h3><p>تقدمك وملاحظاتك تُحفظ محلياً في متصفحك فقط ولا تُرسل لأي طرف.</p></div><div class="ls"><h3>الاسترجاع</h3><p>لو حصلت مشكلة تقنية منعتك من الوصول لمحتوى اشتريته، تواصل معنا على <a href="'+CONTACT+'" target="_blank" rel="noopener">بوت الدعم</a> وسنحلها أو نرجع المبلغ.</p></div>'}

const exList=id=>EX[id]||[];
const exReady=(cid,x)=>{for(let i=x.f;i<=x.to;i++)if(!S.done[cid+':'+(i-1)])return false;return true};
function exInfo(id){const p=id.split(':'),c=C.find(z=>z.id===p[1]),x=exList(p[1])[+p[2]];return{c:c,x:x,k:p[1]+':'+p[2]}}
function exResult(x,st){
 const n=x.q.length,p=Math.round(st.s/n*100),ok=p>=60;
 return '<h2>📝 '+x.t+'</h2><div class="co'+(ok?'':' au')+'" style="font-size:18px">النتيجة النهائية: <b>'+st.s+' / '+n+'</b> ('+p+'%) — '+(ok?'✅ ناجح':'❌ لم تنجح')+'</div><p class="sm" style="margin:0 0 14px">الدرجة نهائية ولا يمكن إعادة الامتحان.</p>'
 +x.q.map((q,i)=>{const u=st.a[i],r=u===q.a;return '<div class="ls"><p><b>'+(i+1)+'. '+q.q+'</b></p><p style="color:'+(r?'var(--g)':'var(--r)')+'">إجابتك: '+q.o[u]+(r?' ✓':' ✗')+'</p>'+(r?'':'<p>الإجابة الصحيحة: '+q.o[q.a]+'</p>')+'</div>'}).join('')
}
function examPg(id){
 const I=exInfo(id),c=I.c,x=I.x;
 if(!c||!x)return '<h2>الامتحان غير موجود</h2>';
 if(!exReady(c.id,x))return '<h2>📝 '+x.t+'</h2><p class="lead">أكمل الدروس '+x.f+' إلى '+x.to+' من وحدة «'+c.t+'» لتفتح هذا الامتحان.</p>';
 const st=S.ex[I.k]||{a:[],started:false,fin:false};
 if(st.fin)return exResult(x,st);
 if(!st.started)return '<h2>📝 '+x.t+'</h2><p class="lead">'+c.t+' — الدروس '+x.f+' إلى '+x.to+'</p><div class="co au"><b>تعليمات مهمة:</b><br>• '+x.q.length+' أسئلة، ومحاولة واحدة فقط.<br>• بعد «تأكيد الإجابة» لا يمكن تغييرها ولا الرجوع للسؤال.<br>• الدرجة النهائية لا تتغير ولا يمكن إعادة الامتحان.<br>• النجاح من 60% فأكثر.</div><button class="btn au" id="xs">ابدأ الامتحان</button>';
 const i=st.a.length,q=x.q[i];
 return '<h2>📝 '+x.t+'</h2><p class="lead">سؤال '+(i+1)+' من '+x.q.length+'</p><div class="ls"><p><b>'+q.q+'</b></p>'+q.o.map((o,j)=>'<label class="xl"><input type="radio" name="xa" value="'+j+'"> '+o+'</label>').join('')+'<br><button class="btn pr" id="xc">تأكيد الإجابة</button><div id="xk" class="co au" style="display:none"><b>هل أنت متأكد؟</b> بعد التأكيد لا يمكنك تغيير الإجابة.<br><br><button class="btn au" id="xy">نعم، أكّد نهائياً</button> <button class="btn" id="xn">تراجع</button></div> <span id="xm" class="sm"></span></div>'
}
function wireEx(){
 if(!S.cur.startsWith('x:'))return;
 const I=exInfo(S.cur),x=I.x,k=I.k,xs=$('#xs'),xc=$('#xc'),xy=$('#xy'),xn=$('#xn'),xk=$('#xk'),m=$('#xm');
 const radios=()=>[...document.querySelectorAll('input[name=xa]')];
 if(xs)xs.onclick=()=>{S.ex[k]={a:[],started:true,fin:false};W('ex',S.ex);render()};
 radios().forEach(r=>r.onchange=()=>{document.querySelectorAll('.xl').forEach(l=>l.classList.remove('sel'));r.parentNode.classList.add('sel')});
 if(xc)xc.onclick=()=>{if(!radios().some(r=>r.checked)){m.textContent='اختر إجابة أولاً.';return}m.textContent='';xc.style.display='none';xk.style.display='block'};
 if(xn)xn.onclick=()=>{xk.style.display='none';xc.style.display=''};
 if(xy)xy.onclick=()=>{
  const sel=radios().find(r=>r.checked);if(!sel)return;
  const st=S.ex[k]||(S.ex[k]={a:[],started:true,fin:false});if(st.fin)return;
  st.a.push(+sel.value);
  if(st.a.length===x.q.length){st.s=st.a.reduce((t,u,n)=>t+(u===x.q[n].a?1:0),0);st.fin=true;S.xp+=st.s*10}
  W('ex',S.ex);sv();render();scrollTo(0,0)}
}
function render(){
 let id=S.cur;const c=C.find(x=>x.id===id);
 if((c||id.startsWith('x:'))&&id!=='ethics'&&!ethicsDone()){id=S.cur='ethics'}
 const cc=C.find(x=>x.id===id),m=$('#mn');
 m.innerHTML=cc?course(cc):id.startsWith('x:')?examPg(id):id==='cert'?certPg():id==='verify'?verifyPg():terms();
 nav();hud();wire(cc);wireEx()
}
function wire(c){
 document.querySelectorAll('[data-l]').forEach(b=>b.onclick=()=>{const k=b.dataset.l;if(S.done[k])delete S.done[k];else{S.done[k]=1;award('l:'+k,15)}sv();render()});
 document.querySelectorAll('[data-n]').forEach(t=>t.oninput=()=>{S.notes[t.dataset.n]=t.value;W('notes',S.notes)});
 const qc=$('#qc');
 if(qc&&c)qc.onclick=()=>{const f=$('#qf'),r=$('#qr');let sc=0;for(let i=0;i<c.q.length;i++){const s=f.querySelector('input[name=q'+i+']:checked');if(!s){r.textContent='جاوب على كل الأسئلة أولاً.';return}if(+s.value===c.q[i].a)sc++}qbest(c.id,sc);sv();r.textContent='النتيجة: '+sc+'/'+c.q.length;hud()};
 document.querySelectorAll('[data-t]').forEach(inp=>inp.onkeydown=e=>{
  if(e.key!=='Enter'){beep();return}
  const key=inp.dataset.t,p=key.split(':'),cm=C.find(x=>x.id===p[0]).ls[+p[1]].cm,o=document.querySelector('[data-o="'+key+'"]'),v=inp.value.trim().replace(/\s+/g,' ');
  if(!v)return;
  if(v==='clear'){o.textContent=''}else{o.textContent+='$ '+v+'\n'+(cm[v]?cm[v]:'أمر غير معروف في هذا التمرين، جرّب أحد الأوامر المذكورة فوق.')+'\n';if(cm[v]){award('t:'+key+':'+v,5);sv();hud()}}
  inp.value='';o.scrollTop=o.scrollHeight});
 const cn=$('#cn');
 if(cn){cn.value=S.name;const up=()=>{const n=cn.value.trim()||'Student Name';$('#cnm').textContent=n;$('#cs').textContent=serial(cn.value.trim()||'Student Name');S.name=cn.value;W('name',S.name)};cn.oninput=up;up();$('#cp').onclick=()=>print()}
 const vb=$('#vb');
 if(vb)vb.onclick=()=>{const n=$('#vn').value,s=$('#vs').value.trim().toUpperCase(),r=$('#vr');r.textContent=n.trim()&&s===serial(n)?'✅ الشهادة صحيحة وصادرة من Mr. APT.':'❌ البيانات غير مطابقة.';r.style.color=n.trim()&&s===serial(n)?'var(--g)':'var(--r)'}
}

async function sha(s){const b=await crypto.subtle.digest('SHA-256',new TextEncoder().encode(s));return[...new Uint8Array(b)].map(x=>x.toString(16).padStart(2,'0')).join('')}
function closeAdm(){const a=$('#am');if(a)a.remove()}
function openAdm(limited){
 closeAdm();
 const last=L('lastadm','لا يوجد');W('lastadm',new Date().toLocaleString('ar-EG'));
 const d=document.createElement('div');d.className='md';d.id='am';d.style.display='flex';
 d.innerHTML='<div class="mb"><h2>👻 غرفة العمليات'+(limited?' (عرض)':'')+'</h2><p class="sm" style="margin:0">آخر دخول: '+E(last)+'</p>'+(limited?'<p>نسخة محدودة للعرض فقط.</p>':'<div class="co"><b>حالة المنصة:</b> '+(SITE_LOCKED?'مقفولة للجميع':'مفتوحة للجميع')+'<br><span class="sm" style="margin:0">لقفلها للجميع غيّر SITE_LOCKED إلى true في أول ملف index.html وأعد رفعه (بدون سيرفر لا يمكن القفل من هنا).</span></div><h3>تغيير كلمة السر</h3><input id="np" type="password" placeholder="كلمة سر جديدة (6 أحرف على الأقل)"><button class="btn" id="sp">تحديث</button><p class="sm" style="margin:6px 0 0">التغيير يخص هذا الجهاز فقط.</p>')+'<br><button class="btn au" id="ca">إغلاق</button></div>';
 document.body.appendChild(d);
 $('#ca').onclick=closeAdm;
 const sp=$('#sp');
 if(sp)sp.onclick=async()=>{const v=$('#np').value;if(v.length<6){alert('كلمة السر قصيرة (6 على الأقل).');return}W('ah',await sha(v));alert('تم التحديث على هذا الجهاز.')}
}
$('#gh').onclick=()=>{
 if(!(window.crypto&&crypto.subtle)){alert('لوحة المشرف تعمل فقط على رابط https.');return}
 closeAdm();
 const d=document.createElement('div');d.className='md';d.id='am';d.style.display='flex';
 d.innerHTML='<div class="mb"><h2>👻 دخول المشرف</h2><input id="pw" type="password" placeholder="كلمة السر" style="text-align:center"><div style="text-align:center"><button class="btn au" id="po">دخول</button> <button class="btn" id="pc">إلغاء</button></div></div>';
 document.body.appendChild(d);
 const pw=$('#pw');pw.focus();
 const go2=async()=>{const h=await sha(pw.value);if(h===L('ah',H1))openAdm(false);else if(h===H2)openAdm(true);else alert('كلمة سر غير صحيحة.')};
 $('#po').onclick=go2;pw.onkeydown=e=>{if(e.key==='Enter')go2()};$('#pc').onclick=closeAdm
};
document.addEventListener('visibilitychange',()=>{if(document.hidden)closeAdm()});
addEventListener('pagehide',closeAdm);

function disclaimer(){
 const d=$('#dis');let n=20;const first=!L('w',0);
 d.innerHTML='<div class="mb"><h2>⚠️ تنبيه قانوني</h2><p style="font-size:15px">هذه المنصة مخصصة للتعليم الأخلاقي للأمن السيبراني فقط. يُمنع استخدام أي مهارة ضد أي نظام دون تصريح كتابي صريح، والمنصة وصاحبها غير مسؤولين عن أي استخدام غير قانوني.</p>'+(first?'<p style="color:var(--g)">👻 أهلاً بك في Mr. APT! ابدأ بالدرس الإجباري من القائمة.</p>':'')+'<p class="sm" style="margin:0">يختفي خلال <b id="cd">20</b> ثانية</p></div>';
 d.style.display='flex';W('w',1);
 const t=setInterval(()=>{n--;const c=$('#cd');if(c)c.textContent=n;if(n<=0){clearInterval(t);d.style.display='none'}},1000)
}

$('#bg').onclick=()=>{$('#sb').classList.add('op');$('#ov').classList.add('sh')};
$('#ov').onclick=closeSb;
$('#sr').oninput=nav;
const setFs=v=>{S.fs=Math.max(13,Math.min(24,v));document.documentElement.style.fontSize=S.fs+'px';W('fs',S.fs)};
$('#fm').onclick=()=>setFs(S.fs-1);$('#fp').onclick=()=>setFs(S.fs+1);
setFs(S.fs);
if(SITE_LOCKED){$('#lk').style.display='flex';$('#mn').style.display='none'}
else{disclaimer();render()}
</script>
</body>
</html>
