[index.html](https://github.com/user-attachments/files/34879020/index.html)
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>وحدة كرة اليد – الصف السابع</title>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;600;800&display=swap">
<style>
:root{--bg:#f3f6f5;--card:#fff;--ink:#14232b;--mut:#4f6068;--line:#d5dedc;--acc:#c85a14;--att:#1d5fa8;--def:#c23b3b;--floor:#2f6f73;--ok:#17663a;--er:#a3201a;box-sizing:border-box;padding:env(safe-area-inset-top,0px) env(safe-area-inset-right,0px) env(safe-area-inset-bottom,0px) env(safe-area-inset-left,0px)}
@media (prefers-color-scheme:dark){:root{--bg:#0f1b20;--card:#172830;--ink:#e8f0ef;--mut:#a9bcc2;--line:#2b414a;--acc:#f08a45;--att:#5b9ae0;--def:#e86a6a;--floor:#1f4f53;--ok:#7fd9a1;--er:#ff9c94}}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--ink);font:400 16px/1.7 Cairo,Tahoma,system-ui,sans-serif}
.wrap{max-width:760px;margin:0 auto;padding:16px}
h1{font-size:26px;font-weight:800;line-height:1.35;margin:4px 0}
h2{font-size:18px;margin:18px 0 6px}
h3{margin:14px 0 4px;font-size:16px}
.sub{color:var(--mut);font-size:14px;margin:0}
.stages{display:flex;gap:8px;overflow-x:auto;padding:12px 0 4px;margin:0;list-style:none}
.stages li{flex:0 0 auto;background:var(--card);border:1px solid var(--line);border-radius:999px;padding:2px 12px;font-size:13px;white-space:nowrap}
.stages b{color:var(--acc);margin-inline-end:6px}
nav{display:flex;border-bottom:2px solid var(--line);margin:12px 0 16px}
nav button{flex:1;border:0;background:none;color:var(--mut);font:600 15px Cairo,Tahoma,sans-serif;padding:12px 2px;min-height:44px;border-bottom:3px solid transparent;margin-bottom:-2px;cursor:pointer}
nav button.on{color:var(--ink);border-color:var(--acc)}
.pane{display:none}.pane.on{display:block}
details.les,details.hs{background:var(--card);border:1px solid var(--line);border-radius:10px;margin-bottom:10px}
summary{display:flex;gap:12px;align-items:center;padding:12px 14px;cursor:pointer;list-style:none;font-weight:600;min-height:44px}
summary::-webkit-details-marker{display:none}
summary b.n{flex:0 0 32px;height:32px;border-radius:50%;background:var(--att);color:#fff;display:grid;place-items:center}
summary small{display:block;color:var(--mut);font-weight:400;font-size:13px}
dl{margin:0;padding:0 14px 14px}
dt{font-weight:800;font-size:13px;color:var(--acc);margin-top:10px}
dd{margin:2px 0 0}
.btn{border:1px solid var(--line);background:var(--card);color:var(--ink);font:600 14px Cairo,Tahoma,sans-serif;padding:8px 14px;min-height:44px;border-radius:8px;cursor:pointer;margin-top:10px}
.btn.on{background:var(--ink);color:var(--bg)}
.btn.pri{background:var(--acc);color:#fff;border-color:var(--acc);font-size:16px;width:100%}
.btn.pri[disabled]{opacity:.6;cursor:wait}
.btn.sm{margin:0;min-height:40px;padding:4px 12px}
.btn.dng{color:var(--er);border-color:var(--er)}
.box{background:var(--card);border:1px solid var(--line);border-radius:10px;padding:12px 14px;margin-top:12px}
.chips{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:10px}
.chips .btn{margin:0}
svg.board{width:100%;height:auto;touch-action:none;display:block;border-radius:10px;background:var(--floor)}
svg.chart{width:100%;height:auto;display:block;border-radius:10px;background:var(--card);border:1px solid var(--line)}
.p circle{stroke:#fff;stroke-width:2;cursor:grab}
.p text{fill:#fff;font:700 12px Cairo,sans-serif;text-anchor:middle;pointer-events:none}
.a circle{fill:var(--att)}.d circle{fill:var(--def)}.b circle{fill:#e8742c}
.row{display:grid;grid-template-columns:1fr auto;gap:8px;align-items:center;padding:8px 0;border-bottom:1px solid var(--line)}
.ctr{display:flex;align-items:center;gap:6px;justify-content:center}
.ctr button{width:46px;height:46px;border-radius:10px;border:1px solid var(--line);background:var(--card);color:var(--ink);font-size:22px;cursor:pointer}
.ctr output{min-width:30px;text-align:center;font-weight:800;font-size:18px}
.lbl{display:flex;justify-content:space-between;font-size:14px}
.bar{height:14px;border-radius:7px;background:var(--line);overflow:hidden;margin:2px 0 8px}
.bar{display:flex}
.bar i{display:block;height:100%;transition:width .3s}
.grp{font-weight:800;margin:14px 0 2px;font-size:15px}
.grp.a{color:var(--att)}.grp.d{color:var(--def)}
.row small{display:block;color:var(--mut);font-size:12px;line-height:1.4;font-weight:400}
.sum{font-size:13px;margin-top:6px;color:var(--ink)}
textarea,input[type=date],select{width:100%;font:14px/1.6 Cairo,Tahoma,sans-serif;background:var(--bg);color:var(--ink);border:1px solid var(--line);border-radius:8px;padding:8px;min-height:44px}
label.f{display:block;font-weight:600;font-size:14px;margin-top:10px}
.g2{display:grid;grid-template-columns:1fr 1fr;gap:10px}
.tcs{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-top:10px}
.tc{background:var(--card);border:2px solid var(--line);border-radius:12px;padding:10px 12px}
.tc .th{font-weight:800;margin-bottom:4px;display:flex;align-items:center;gap:6px}
.kv{display:flex;align-items:baseline;gap:6px;flex-wrap:wrap;font-size:13px;color:var(--mut)}
.kv b{font-size:22px;color:var(--ink);font-weight:800;line-height:1.3}
.dl{font-size:12px;font-weight:700}
.dl.up{color:var(--ok)}.dl.dn{color:var(--er)}.dl.eq{color:var(--mut)}
.mini{font-size:12px;color:var(--mut);margin-top:4px}
.empty{text-align:center;color:var(--mut);padding:22px 14px}
.goal{border-inline-start:4px solid var(--acc)}
.tb{width:100%;border-collapse:collapse;font-size:13px;margin:0 0 10px}
.tb th,.tb td{border-bottom:1px solid var(--line);padding:5px 4px;text-align:center}
.tb th:first-child,.tb td:first-child{text-align:start}
.leg{display:flex;gap:12px;flex-wrap:wrap;font-size:13px;margin:6px 0 2px}
.leg span{display:inline-flex;align-items:center;gap:4px}
[hidden]{display:none!important}
.ctl{display:flex;gap:6px;align-items:center;margin-top:8px}
.ctl .btn{margin:0;min-width:0;min-height:40px;padding:4px 10px;flex:0 0 auto}
.ctl input[type=range]{flex:1 1 40px;min-width:40px;min-height:40px;accent-color:var(--acc)}
svg.board{width:min(100%,60vh);margin:0 auto}
.stg{font-size:13px;font-weight:700;margin:0 0 6px;display:flex;align-items:center;gap:6px;flex-wrap:wrap}
.stg b{background:var(--acc);color:#fff;border-radius:999px;padding:0 10px;white-space:nowrap}
.stg b.off{background:none;color:var(--mut);box-shadow:inset 0 0 0 1px var(--line)}
.stg span{color:var(--mut);font-weight:600}
.tq{margin:8px 0 0;padding-top:8px;border-top:1px dashed var(--line);font-size:14px}
.tq b{color:var(--acc)}
.bgrid{display:grid;gap:10px;grid-template-columns:minmax(0,1fr)}
.bside>*:first-child{margin-top:0}
.bside .box{margin-top:8px;padding:10px 12px}
.bside .chips{margin:8px 0 0}
.chips.sc{flex-wrap:nowrap;overflow-x:auto;padding-bottom:4px;margin-bottom:8px}
.chips.sc .btn.pt-a{border-inline-start:4px solid var(--att)}
.chips.sc .btn.pt-d{border-inline-start:4px solid var(--def)}
.chips.sc .btn{flex:0 0 auto;white-space:nowrap;min-height:40px;padding:4px 12px}
.wrap.cmp>.sub,.wrap.cmp>.stages{display:none}
.wrap.cmp h1{font-size:20px}
.wrap.cmp nav{margin:6px 0 10px}
details.tips summary{padding:0;min-height:0;font-size:14px}
details.tips p{margin:6px 0 0;font-size:14px}
@media (min-width:700px){.bgrid{grid-template-columns:minmax(0,400px) minmax(0,1fr);align-items:start;gap:14px}.chips.sc{flex-wrap:wrap;overflow:visible}svg.board{width:100%}}
.tag{display:inline-block;padding:0 10px;border-radius:999px;font-size:12px;font-weight:700;color:#fff;margin-inline-end:6px}
.tag.a{background:var(--att)}.tag.d{background:var(--def)}
.p.q circle{stroke:#ffd54a;stroke-width:3.5}
.pulse{animation:plz 1.6s ease-in-out infinite}
@keyframes plz{0%,100%{fill-opacity:.12}50%{fill-opacity:.38}}
.btn[disabled]{opacity:.5;cursor:not-allowed}
@media (prefers-reduced-motion:reduce){.pulse{animation:none}}
.sync{display:flex;justify-content:space-between;align-items:center;gap:8px;font-size:13px;color:var(--mut);margin-bottom:10px}
.sync.er{color:var(--er)}
input.pin{width:100%;font:18px Cairo,Tahoma,sans-serif;letter-spacing:3px;text-align:center;background:var(--bg);color:var(--ink);border:1px solid var(--line);border-radius:8px;padding:8px;min-height:44px}
.msg{margin-top:10px;font-weight:600;font-size:14px;min-height:22px}
.msg.ok{color:var(--ok)}.msg.er{color:var(--er)}
.sl{display:flex;justify-content:space-between;align-items:center;gap:8px;padding:8px 0;border-bottom:1px solid var(--line);font-size:14px}
.sl .acts{display:flex;gap:6px}
.ch-t{fill:var(--mut);font:11px Cairo,sans-serif}
.ch-g{stroke:var(--line);stroke-width:1}
@media (prefers-reduced-motion:reduce){.bar i{transition:none}}
</style>
</head>
<body>
<div class="wrap">
<h1>وحدة كرة اليد – الصف السابع</h1>
<p class="sub">الوحدة الثانية: ألعب بوعي! · الفصل الأول 2026–2027 · نموذج TGfU · مدرسة قطر للعلوم والتكنولوجيا – الصخامة</p>
<ol class="stages">
<li><b>1</b>لعبة مصغرة</li><li><b>2</b>تقدير اللعبة</li><li><b>3</b>الوعي التكتيكي</li><li><b>4</b>اتخاذ القرار</li><li><b>5</b>تنفيذ المهارة</li><li><b>6</b>الأداء</li>
</ol>
<nav>
<button class="on" data-t="prog">تقدم الفرق</button>
<button data-t="les">الأسابيع</button>
<button data-t="board">اللوحة</button>
<button data-t="rec">تسجيل الحصة</button>
</nav>

<section id="prog" class="pane on">
<div class="sync"><span id="sync" role="status"></span><button class="btn sm" id="rf">تحديث</button></div>
<div class="chips" id="pcls" role="group" aria-label="اختر الشعبة"></div>
<div id="pbody"></div>
</section>

<section id="les" class="pane">
<div id="lessons"></div>
<div class="box"><b>هيكل الحصة (45 دقيقة):</b> تهيئة 10 د · التعلم المرحلي 20 د · التغذية الراجعة 10 د · الغلق 5 د.<br>مراحل TGfU داخل الـ 20 دقيقة: لعبة 2 · تقدير اللعبة 2 · وعي تكتيكي 3 · قرار 4 · مهارة 4 · أداء 5.</div>
</section>

<section id="board" class="pane">
<div class="chips sc" id="plays" role="group" aria-label="اختر مجموعة المبادئ"></div>
<div class="chips sc" id="plist" role="group" aria-label="اختر المبدأ" hidden></div>
<div class="bgrid">
<div class="bcourt">
<div class="stg" id="stg" role="status"></div>
<svg id="court" class="board" viewBox="0 0 340 300" role="img" aria-label="نصف ملعب كرة اليد: اللاعبون الزرق مهاجمون والحمر مدافعون والكرة برتقالية">
<defs>
<marker id="ar-a" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto"><path d="M0 0L10 5L0 10z" fill="#bfe0ff"/></marker>
<marker id="ar-d" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto"><path d="M0 0L10 5L0 10z" fill="#ffc9c9"/></marker>
<marker id="ar-b" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto"><path d="M0 0L10 5L0 10z" fill="#fff"/></marker>
</defs>
<rect x="10" y="10" width="320" height="280" fill="none" stroke="#fff" stroke-width="2" opacity=".85"/>
<path d="M74 10A96 96 0 0 0 266 10Z" fill="#e8b44c" fill-opacity=".28" stroke="#fff" stroke-width="2"/>
<path d="M26 10A144 144 0 0 0 314 10" fill="none" stroke="#fff" stroke-width="2" stroke-dasharray="7 6" opacity=".85"/>
<rect x="146" y="2" width="48" height="8" fill="#fff"/>
<line x1="165" y1="106" x2="175" y2="106" stroke="#fff" stroke-width="2"/>
<g id="zn"></g>
<polyline id="dline" points="" fill="none" stroke="#ffc9c9" stroke-width="3" stroke-linejoin="round" opacity=".9"/>
<g id="arr"></g>
<g id="pcs"></g>
</svg>
<div class="ctl" id="ctl" hidden>
<button class="btn" id="pv">السابق</button>
<button class="btn on" id="pp">تشغيل</button>
<button class="btn" id="nx">التالي</button>
<input type="range" id="slr" min="0" max="3" step="1" value="0" aria-label="الخطوة">
<button class="btn" id="spd" aria-label="سرعة العرض">×1</button>
</div>
</div>
<div class="bside">
<div class="box" id="capbox"><b id="ft"></b><p id="fi" style="margin:4px 0 0" aria-live="polite"></p><p class="tq" id="tq" hidden></p></div>
<div class="chips" id="forms" role="group" aria-label="التشكيل الدفاعي"></div>
<div class="box goal" id="qbox" hidden>
<b id="qq"></b>
<p class="sub" id="qh" style="margin:2px 0 6px"></p>
<div class="chips" id="qopts"></div>
<div class="msg" id="qmsg" role="status" aria-live="polite"></div>
<button class="btn sm" id="qnext" hidden>تابع السيناريو</button>
<button class="btn sm" id="qskip">تخطّي السؤال</button>
</div>
<div class="chips"><button class="btn sm" id="reset">إعادة الأوضاع</button><button class="btn sm" id="dlbtn" aria-pressed="false">إظهار خط الدفاع</button></div>
<div class="sub" id="qscore" role="status" style="margin-top:6px"></div>
<details class="box tips"><summary>طريقة الاستخدام وأسئلة للنقاش</summary><p>السيناريوهات تغطي المبادئ الخمسة للهجوم (الاختراق، المساندة والدعم، الانتشار، الحركة لخلق المساحات، الإبداع والارتجال) والمبادئ الخمسة للدفاع (تأخير اللعب، التغطية، التمركز، التوازن الدفاعي، الصبر)، ومعها التحول بين الحالتين. كل سيناريو يبدأ بمرحلة الوعي التكتيكي ثم يتوقف عند سؤال في مرحلة اتخاذ القرار.</p><p>اختر سيناريو واضغط «تشغيل» لترى المبدأ يتحرك في الملعب، وأجب عن سؤاله بالضغط على الملعب أو على الإجابة. في «لعب حر» اسحب اللاعبين بإصبعك وبدّل التشكيل الدفاعي.</p><p>اسأل طلابك: أين المساحة الحرة؟ من اللاعب غير المراقَب؟ ماذا يتغير عندما نبدّل التشكيل الدفاعي؟</p></details>
</div>
</div>
</section>

<section id="rec" class="pane">
<div class="box" id="rintro"></div>
<h2>بيانات الحصة</h2>
<div class="chips" id="rcls" role="group" aria-label="اختر الشعبة"></div>
<div class="g2">
<div><label class="f" for="rdate">تاريخ الحصة</label><input type="date" id="rdate"></div>
<div><label class="f" for="rwk">الأسبوع</label><select id="rwk"></select></div>
</div>
<h2>تسجيل الأحداث</h2>
<p class="sub">اختر الفريق ثم سجّل أحداثه أثناء اللعب.</p>
<div class="chips" id="tm" style="margin-top:8px"></div>
<div id="rows"></div>
<div id="stats"></div>
<h2>مبادئ الهجوم والدفاع</h2>
<p class="sub">عدّ كل مرة طبّق فيها لاعبو الفريق المختار المبدأ بشكل صحيح أمامك في الملعب.</p>
<div id="prin"></div>
<div id="tpanel" hidden>
<label class="f" for="rgoal">هدف الفرق للحصة القادمة (يظهر للطلاب)</label>
<textarea id="rgoal" rows="2" placeholder="مثال: رفع دقة التمرير فوق 70% بالمساندة والانتشار"></textarea>
<label class="f" for="rnote">ملاحظة المعلم (تظهر للطلاب)</label>
<textarea id="rnote" rows="2" placeholder="اختياري"></textarea>
</div>
<div style="margin-top:12px"><button class="btn pri" id="save">حفظ الحصة</button></div>
<div class="chips" style="margin-top:8px"><button class="btn sm" id="zero">تصفير العدادات</button><button class="btn sm" id="cancel" hidden>إلغاء التعديل</button></div>
<div class="msg" id="msg" role="status" aria-live="polite"></div>
<div id="tsaved" hidden>
<h2>الحصص المحفوظة لهذه الشعبة</h2>
<div id="saved"></div>
</div>
<div id="tadmin" class="box" hidden>
<b>رقم المعلم</b>
<label class="f" for="mpin">تغيير رقم المعلم (4–8 أرقام)</label>
<input class="pin" id="mpin" inputmode="numeric" maxlength="8" autocomplete="off">
<button class="btn" id="mset">اعتماد رقم المعلم</button>
</div>
<details class="box" id="tlogin"><summary style="padding:0">دخول المعلم</summary>
<label class="f" for="tpin">رقم المعلم</label>
<input class="pin" type="password" id="tpin" inputmode="numeric" autocomplete="off" maxlength="8">
<button class="btn" id="tgo">دخول</button></details>
<div class="box"><b>تقرير الفريق للذكاء الاصطناعي</b><p style="margin:4px 0 8px;font-size:14px">بعد المباراة انسخ البرومبت والصقه في نموذج الذكاء الاصطناعي، ثم يرفع الطالب إجابته على منصة قطر للتعليم.</p><textarea id="pr" readonly rows="9"></textarea><button class="btn" id="cp">نسخ البرومبت</button></div>
</section>
</div>

<script>
const T=id=>document.getElementById(id);
const CLASSES=['7A','7B','7C','7D','7E'];
const M=[['pa','تمريرة ناجحة'],['pl','تمريرة مقطوعة'],['sh','تسديدة'],['gl','هدف'],['st','استرجاع كرة']];
const TM=[['a','أ','#3b82c4','circle'],['b','ب','#d1495b','square'],['c','ج','#2e9e6b','triangle'],['d','د','#8f6bd1','diamond']];
const P=[
['sp','مساندة وانتشار','a','لاعب بلا كرة يتحرك ليمنح زميله خيار تمرير'],
['pe','اختراق نحو المرمى','a','دخول نحو المرمى أو بين مدافعين'],
['fs','استغلال المساحة الحرة','a','قطع أو تمرير إلى مكان لا يوجد فيه مدافع'],
['cv','تغطية وتوازن','d','لاعب يغلق خط التمرير أو يغطي مكان زميله'],
['dy','تأخير تقدم الخصم','d','وقفة أو ضغط يبطّئ حامل الكرة ويمنع تقدمه'],
['tr','تحول سريع','d','انتقال فوري إلى الهجوم بعد استرجاع الكرة أو إلى الدفاع بعد فقدها']
];
const ALLK=M.concat(P.map(x=>[x[0],x[1]]));
const PS={sp:'مساندة',pe:'اختراق',fs:'مساحة',cv:'تغطية',dy:'تأخير',tr:'تحول'};
const NL=String.fromCharCode(10);
let ST={v:1,sessions:[]};

/* ---------- helpers ---------- */
const pct=(n,d)=>d?Math.round(n/d*100):null;
const fp=v=>v===null?'—':v+'%';
const sd=s=>{const[y,m,d]=s.date.split('-');return (+d)+'/'+(+m)};
const emptyTeams=()=>{const o={};TM.forEach(([t])=>{o[t]={};ALLK.forEach(([k])=>{o[t][k]=0})});return o};
const gv=(x,k)=>Number(x[k])||0;
const atk=x=>gv(x,'sp')+gv(x,'pe')+gv(x,'fs');
const dfn=x=>gv(x,'cv')+gv(x,'dy')+gv(x,'tr');
const hasP=s=>TM.some(([t])=>P.some(([k])=>s.teams[t][k]!==undefined));
const clone=o=>JSON.parse(JSON.stringify(o));
const today=()=>{const d=new Date();return d.getFullYear()+'-'+String(d.getMonth()+1).padStart(2,'0')+'-'+String(d.getDate()).padStart(2,'0')};
const wkOf=d=>d<='2026-11-07'?1:d<='2026-11-14'?2:d<='2026-11-21'?3:4;
const WN=['','أبني الهجوم','أطوّر الهجوم','أنظّم الدفاع','أقيّم أدائي'];
const passAcc=(s,t)=>{const x=s.teams[t];return pct(x.pa,x.pa+x.pl)};
const shootEff=(s,t)=>{const x=s.teams[t];return pct(x.gl,x.sh)};
const rawSess=c=>ST.sessions.filter(s=>s.cls===c).sort((a,b)=>a.date===b.date?(a.ts||0)-(b.ts||0):(a.date<b.date?-1:1));
const hasData=x=>ALLK.some(([k])=>gv(x,k)>0);
/* حصص نفس الشعبة في نفس اليوم تُجمع في سجل واحد: كل فريق يأخذ أحدث أرقامه المسجلة */
function bySess(c){
 const out=[],map={};
 rawSess(c).forEach(s=>{
  const m=map[s.date];
  if(!m){const n=clone(s);map[s.date]=n;out.push(n);return}
  TM.forEach(([t])=>{if(hasData(s.teams[t]))m.teams[t]=clone(s.teams[t])});
  m.wk=s.wk;m.ts=s.ts;if(s.goal)m.goal=s.goal;if(s.note)m.note=s.note;
 });
 return out;
}
function esc(s){return String(s==null?'':s).replace(/[&<>"]/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;'}[c]))}
function lsGet(k){try{return localStorage.getItem(k)}catch(e){return null}}
function lsSet(k,v){try{localStorage.setItem(k,v)}catch(e){}}
function lsDel(k){try{localStorage.removeItem(k)}catch(e){}}

/* ---------- lessons ---------- */
const W=[
{t:"أبني الهجوم",d:"1–5 نوفمبر",q:"كيف نحافظ على الكرة ونتقدم نحو الهدف؟",c:"الاستحواذ بالتمرير والتحرك · المساندة والانتشار لبناء هجوم منظم · الاختراق نحو الهدف · تغذية راجعة لتحسين الأداء الهجومي.",g:"3 ضد 3 بلا قيود لطرح المشكلة التكتيكية، ثم العودة إلى 5 ضد 5 أو 4+2 ضد 4+2.",s:"محطة تمرير وتحرك ثنائية، ومحطة مساندة وانتشار ثلاثية (أشكال مثلثية).",m:"لماذا يكون التمرير القطري أحياناً أكثر فاعلية من المستقيم لتجاوز المدافع؟",v:"«قائد التحفيز» يشجع بعد كل محاولة (الإيجابية والمثابرة)، و«سفير الاحترام» يصافح المنافس (الاحترام والتعاطف).",tab:"board",tl:"افتح اللوحة التكتيكية"},
{t:"أطوّر الهجوم",d:"8–12 نوفمبر",q:"أين المساحة الحرة؟ وما القرار الأنسب عندما يتغير الموقف؟",c:"الحركة لخلق المساحات واستغلالها · اختيار القرار الهجومي المناسب · القوة المناسبة في التمرير والاستلام · تغذية راجعة لقرارات أفضل.",g:"5 ضد 5 أو 2+5 ضد 2+5 (فريقان مع مساندين خارج الملعب).",s:"القطع نحو المساحة، وتغيير الاتجاه والسرعة، وضبط قوة التمرير.",m:"كيف تتغير سرعة الكرة عندما نغيّر قوة التمرير والمسافة بين اللاعبين؟",v:"«مسؤول الفريق» يوزع الأدوار بعدل ويشجع الجميع على المشاركة.",tab:"prog",tl:"شاهد تقدم الفرق"},
{t:"أنظّم الدفاع",d:"15–19 نوفمبر",q:"أين أقف بين الكرة والمرمى؟ ومتى أضغط ومتى أتراجع؟",c:"تأخير تقدم المنافس لاستعادة الاستحواذ · التغطية والتوازن الدفاعي · التحول بين الهجوم والدفاع · التعاون مع الزملاء.",g:"4 ضد 4 أو 5 ضد 5: يربح الدفاع نقطة باسترجاع الكرة أو بإجبار الخصم على تسديدة بعيدة.",s:"الوقفة الدفاعية، والحركة الجانبية، والتغطية والمساندة، والتحول السريع.",m:"لماذا نخفض مركز الثقل ونوسّع قاعدة الارتكاز عند الدفاع؟",v:"«قائد التعاون» ينبّه زملاءه للتغطية بصوت مشجع (الإيجابية والمثابرة).",tab:"board",tl:"افتح اللوحة التكتيكية"},
{t:"أقيّم أدائي",d:"22–26 نوفمبر",q:"أي مبدأ أثّر أكثر في نتيجة فريقي؟ وماذا سنغيّر؟",c:"دمج المبادئ الهجومية والدفاعية · تحليل الأداء الفردي والجماعي · تحديد نقاط القوة والتطوير · استخدام المصطلحات الرياضية.",g:"مباريات مصغرة بنظام دوري، مع طالب محلل بيانات في كل فريق.",s:"دمج المهارات في لعب حقيقي مع تغذية راجعة قصيرة.",m:"كيف نقرأ أرقام فريقنا (دقة التمرير وكفاءة التسديد) لنتخذ قراراً أفضل؟",v:"«سفير الاحترام» يقدّم ملاحظة إيجابية لفريق المنافس بعد المباراة.",tab:"prog",tl:"شاهد تقدم الفرق"}
];
T('lessons').innerHTML=W.map((w,i)=>`<details class="les" ${i?'':'open'}><summary><b class="n">${i+1}</b><span>${w.t}<small>${w.d}</small></span></summary><dl><dt>سؤال المرحلة</dt><dd>${w.q}</dd><dt>محتوى الأسبوع (من الخطة الفصلية)</dt><dd>${w.c}</dd><dt>اللعبة المصغرة</dt><dd>${w.g}</dd><dt>المهارة</dt><dd>${w.s}</dd><dt>سؤال STEM</dt><dd>${w.m}</dd><dt>تفعيل القيم</dt><dd>${w.v}</dd><button class="btn" data-go="${w.tab}">${w.tl}</button></dl></details>`).join('');

function show(id){document.querySelector('.wrap').classList.toggle('cmp',id==='board');document.querySelectorAll('.pane').forEach(p=>p.classList.toggle('on',p.id===id));document.querySelectorAll('nav button').forEach(b=>b.classList.toggle('on',b.dataset.t===id));lsSet('hb7tab',id);window.scrollTo(0,0)}
document.querySelectorAll('nav button').forEach(b=>b.onclick=()=>show(b.dataset.t));
document.addEventListener('click',e=>{const g=e.target.closest('[data-go]');if(g)show(g.dataset.go)});

/* ---------- tactical board ---------- */
const NS='http://www.w3.org/2000/svg',svg=T('court'),pcs=T('pcs');
const ATT=[[22,26],[95,160],[170,176],[245,160],[318,26],[170,122]];
const DEF={'6-0':[[84,40],[100,82],[140,104],[200,104],[240,82],[256,40]],'5-1':[[84,40],[110,84],[170,104],[230,84],[256,40],[170,150]],'4-2':[[84,40],[125,98],[215,98],[256,40],[130,150],[210,150]]};
const INFO={'6-0':'ستة لاعبين على خط واحد قريب من منطقة المرمى: يغلق المساحة أمام المرمى لكنه يترك مجالاً للتسديد من بعيد.','5-1':'خمسة على الخط ولاعب متقدم يضغط على حامل الكرة: يربك التمرير لكنه يترك مساحات خلف اللاعب المتقدم.','4-2':'أربعة قرب المرمى ولاعبان متقدمان: ضغط أكبر على لاعبي الخلف مع تغطية متوسطة.'};
const cp=c=>[c[0],c[1]];
const REDUCE=!!(window.matchMedia&&matchMedia('(prefers-reduced-motion: reduce)').matches);
/* سيناريوهات متحركة: a/d = تغييرات مواقع المهاجمين/المدافعين (رقم اللاعب-1)، b = موقع الكرة */
/* السيناريوهات مبنية على المبادئ الخمسة للهجوم والمبادئ الخمسة للدفاع، ومعها التحول بين الحالتين.
   كل سيناريو يتوقف عند سؤال قرار (مرحلة اتخاذ القرار). g: a هجوم، d دفاع، t تحول */
const PL=[
{id:'pen',g:'a',t:'الاختراق',tag:'a',tg:'هجوم: الاختراق',def:'6-0',ball:[95,160],steps:[
 {cap:'اللاعب 2 يحمل الكرة أمام الدفاع 6-0، وهناك فراغ صغير بين المدافعين 2 و3.'},
 {a:{1:[122,128]},b:[122,128],cap:'الاختراق: يندفع اللاعب 2 بالكرة نحو الفراغ بين المدافعين ليكسر التكتل الدفاعي.'},
 {d:{1:[114,98],2:[146,112]},cap:'المدافعان 2 و3 يتجمعان نحو المخترق لإيقافه.',quiz:{q:'ماذا يحدث للدفاع عندما يخترق لاعب بين مدافعين؟',opts:['يتجمع المدافعون نحوه فيتحرر زميل قريب من المرمى','يتوقف الدفاع عن الحركة','يتراجع كل المدافعين إلى منتصف الملعب'],ans:0,ok:'الاختراق يجذب المدافعين ويترك زميلًا بلا رقابة.'}},
 {b:[170,122],cap:'تمريرة في العمق إلى لاعب الدائرة 6 غير المراقَب. الاختراق فتح أقصر طريق للتسجيل.'}
]},
{id:'sup',g:'a',t:'المساندة والدعم',tag:'a',tg:'هجوم: المساندة والدعم',def:'6-0',ball:[95,160],steps:[
 {cap:'الكرة مع اللاعب 2، وزميلاه 3 و6 يشكلان معه مثلثًا يمنحه خيارات للتمرير.'},
 {a:{1:[112,188]},b:[170,176],d:{2:[150,106],3:[206,104]},cap:'اللاعب 2 يمرر إلى اللاعب 3 ثم يتحرك فورًا ليفتح زاوية تمرير جديدة خلفه.'},
 {d:{3:[182,146]},cap:'المدافع 4 يتقدم للضغط على حامل الكرة.',quiz:{q:'حامل الكرة تحت الضغط. ما الذي يحتاجه من زملائه؟',opts:['زميل قريب يفتح له زاوية تمرير آمنة','أن يبتعد الجميع عنه','أن يبقى كل زميل واقفًا في مكانه'],ans:0,ok:'المساندة تمنح حامل الكرة حلًا آمنًا تحت الضغط.'}},
 {a:{3:[236,168],2:[170,200]},b:[236,168],d:{3:[204,108],4:[238,98]},cap:'المساندة: اللاعب 4 يقترب ويفتح زاوية تمرير فيستلم تمريرة آمنة. الفريق حافظ على الاستحواذ.'}
]},
{id:'wid',g:'a',t:'الانتشار',tag:'a',tg:'هجوم: الانتشار',def:'6-0',ball:[170,176],steps:[
 {a:{1:[126,166],3:[214,166]},cap:'الكرة مع اللاعب 3، والمهاجمون متقاربون أمام دفاع 6-0 متكتل.'},
 {a:{1:[62,176],3:[278,176]},d:{0:[80,40],1:[92,84],4:[248,84],5:[260,40]},cap:'الانتشار: اللاعبان 2 و4 يتحركان نحو الجانبين لتوسيع الملعب عرضيًا.',quiz:{q:'ماذا يحدث للدفاع عندما ينتشر المهاجمون على عرض الملعب؟',opts:['يتمدد وتظهر فراغات بين المدافعين','يزداد تكتله أمام المرمى','لا يتأثر'],ans:0,ok:'الانتشار يشتت الدفاع ويفتح خطوط التمرير.'}},
 {b:[278,176],d:{0:[92,40],1:[120,84],2:[160,104],3:[222,102],4:[256,82],5:[264,42]},cap:'التمرير إلى الجهة التي تمدد فيها الدفاع، والمدافعون ينزاحون نحو الكرة.'},
 {a:{4:[306,46]},b:[306,46],d:{1:[132,86],2:[172,104],3:[234,100],4:[268,70],5:[270,40]},cap:'الجناح 5 يستلم في مساحة أقل ازدحامًا قرب المرمى. الانتشار هو الذي فكّك الدفاع.'}
]},
{id:'mob',g:'a',t:'الحركة لخلق المساحات',tag:'a',tg:'هجوم: الحركة لخلق المساحات',def:'6-0',ball:[170,176],steps:[
 {cap:'الدفاع 6-0 مغلق أمام المرمى، ولا توجد مساحة واضحة للتسديد.'},
 {a:{5:[116,116]},d:{2:[124,100]},cap:'لاعب الدائرة 6 يتحرك إلى اليسار بدون كرة، فيسحب معه المدافع 3.',quiz:{q:'أين ظهرت المساحة بعد حركة لاعب الدائرة؟',h:'اضغط على المكان في الملعب أو اختر الإجابة.',zone:{x:168,y:112,r:30},opts:['في الوسط بين المدافعين 3 و4','عند الجناح الأيمن','خلف المرمى'],ans:0,ok:'حركة لاعب بدون كرة سحبت المدافع وفرّغت الوسط.'}},
 {a:{2:[170,134]},b:[170,134],cap:'اللاعب 3 القادم من الخلف يقطع بالكرة نحو المساحة التي فُرّغت.'},
 {b:[170,16],d:{3:[192,112]},cap:'تسديدة من مكان قريب. الحركة بدون كرة هي التي صنعت الفرصة.'}
]},
{id:'cre',g:'a',t:'الإبداع والارتجال',tag:'a',tg:'هجوم: الإبداع والارتجال',def:'6-0',ball:[170,176],steps:[
 {cap:'اللاعب 3 يحمل الكرة ويقرأ وقفة المدافعين أمامه قبل أن يقرر.'},
 {a:{2:[186,160]},b:[186,160],d:{2:[154,106],3:[208,114]},cap:'خداع: اللاعب 3 يتحرك يمينًا كأنه سيمرر إلى اللاعب 4، فيتحرك المدافعان معه.',quiz:{q:'تحرّك المدافعان مع الخداع. ما الحل الأنسب الآن؟',opts:['أغيّر اتجاهي فجأة نحو الجهة التي تركاها','أكمل التمريرة التي يتوقعها المدافع','أتوقف وأنتظر'],ans:0,ok:'قراءة حركة المدافع ثم مفاجأته هي أساس الإبداع.'}},
 {a:{2:[148,136]},b:[148,136],cap:'تغيير اتجاه مفاجئ نحو اليسار، واللاعب 3 يتجاوز المدافعين.'},
 {b:[170,16],d:{2:[150,110]},cap:'تصويبة مفاجئة قبل أن يعود المدافعون. للموقف الواحد أكثر من حل، والمهم قراءة الدفاع واختيار ما يفاجئه.'}
]},
{id:'dly',g:'d',t:'تأخير اللعب',tag:'d',tg:'دفاع: تأخير اللعب',def:'6-0',ball:[245,160],steps:[
 {cap:'اللاعب 4 يستلم الكرة ويستعد للتقدم نحو المرمى.'},
 {a:{3:[238,140]},b:[238,140],cap:'المهاجم يتقدم بالكرة نحو المرمى.',quiz:{q:'ماذا يفعل أقرب مدافع ليؤخر تقدم المهاجم؟',opts:['يقترب منه بسرعة محسوبة ويضيّق المساحة أمامه دون اندفاع','يندفع لخطف الكرة بأي طريقة','ينتظر على خط منطقة المرمى'],ans:0,ok:'الاقتراب المحسوب يبطّئ الهجوم دون مخاطرة.'}},
 {d:{4:[236,112]},cap:'تأخير اللعب: المدافع 5 يقترب ويضيّق المساحة أمام حامل الكرة، فيتوقف تقدمه.'},
 {d:{3:[212,100],5:[256,62],2:[156,104]},b:[170,176],cap:'التأخير منح الزملاء وقتًا لبناء التكتل الدفاعي، فاضطر المهاجم إلى التمرير للخلف.'}
]},
{id:'cov',g:'d',t:'التغطية',tag:'d',tg:'دفاع: التغطية',def:'6-0',ball:[170,176],steps:[
 {cap:'الكرة مع اللاعب 3، والدفاع في مواقعه أمام المرمى.'},
 {b:[245,160],d:{3:[208,106],4:[244,84]},cap:'التمرير إلى اللاعب 4، والدفاع يتحرك كوحدة نحو الكرة.'},
 {d:{3:[232,132]},cap:'المدافع 4 (المدافع الأول) تقدّم للضغط على حامل الكرة، وترك خلفه فراغًا.',quiz:{q:'من يغطي المدافع 4 إذا تجاوزه المهاجم؟',h:'اضغط على اللاعب الأحمر في الملعب أو اختر الإجابة.',pick:'D3',opts:['المدافع 3 (يتحرك خلفه وإلى جانبه)','المدافع 1 (يبقى في مكانه)','لا أحد، يكفي الضغط'],ans:0,ok:'أقرب زميل يغطي المدافع الأول من الخلف أو الجانب.'}},
 {d:{2:[196,106],1:[138,100],0:[100,70]},cap:'التغطية: المدافع 3 يقف خلف زميله وإلى جانبه، لا على نفس الخط. إن تجاوز المهاجمُ المدافعَ الأول وجد من يوقفه.'}
]},
{id:'con',g:'d',t:'التمركز',tag:'d',tg:'دفاع: التمركز',def:'6-0',ball:[170,176],steps:[
 {cap:'الكرة مع اللاعب 3. كل مدافع يقف بين مهاجمه والمرمى ويرى الكرة.'},
 {b:[95,160],cap:'الكرة تنتقل إلى اللاعب 2 في الجهة اليسرى.',quiz:{q:'أين يقف المدافع الصحيح بعد انتقال الكرة؟',opts:['بين المهاجم والمرمى بحيث يرى الكرة ومهاجمه معًا','خلف المهاجم بعيدًا عن المرمى','يتبع الكرة فقط ويترك مهاجمه'],ans:0,ok:'التمركز الصحيح: بين المنافس والهدف مع مراقبة الكرة والمهاجم.'}},
 {d:{0:[78,48],1:[102,96],2:[138,108],3:[188,106],4:[230,86],5:[250,46]},cap:'التمركز: يعدّل كل مدافع موقعه نحو الكرة ويبقى بين مهاجمه والمرمى.'},
 {b:[22,26],d:{0:[52,36],1:[92,84]},cap:'الكرة عند الجناح 1، والمدافع 1 يغلق زاوية التصويب. لا توجد ثغرة في عمق الدفاع.'}
]},
{id:'bal',g:'d',t:'التوازن الدفاعي',tag:'d',tg:'دفاع: التوازن الدفاعي',def:'5-1',ball:[245,160],steps:[
 {d:{0:[120,44],1:[150,88],2:[196,104],3:[236,92],4:[262,44],5:[222,128]},cap:'الدفاع كله انضغط نحو الجهة التي فيها الكرة.',quiz:{q:'أين الثغرة في هذا الدفاع؟',h:'اضغط على المكان في الملعب أو اختر الإجابة.',zone:{x:58,y:72,r:54},opts:['الجهة العكسية البعيدة عن الكرة','أمام الكرة مباشرة','قرب منتصف المرمى'],ans:0,ok:'الدفاع غير المتوازن يترك الجانب الضعيف مكشوفًا.'}},
 {d:{0:[84,44],1:[112,88],2:[158,104],3:[206,100],4:[250,60],5:[224,130]},cap:'التوازن الدفاعي: المدافعون البعيدون عن الكرة يعودون لتأمين الجهة العكسية، ولا يقف مدافعان على نفس الخط.'},
 {b:[170,176],d:{5:[186,144]},cap:'الهجوم ينقل الكرة بسرعة ليهاجم الجهة العكسية.'},
 {b:[95,160],d:{0:[72,46],1:[106,102],5:[150,150]},cap:'الكرة تصل إلى الجهة العكسية، لكن الدفاع المتوازن في مكانه ولا مجال لهجمة مباغتة.'}
]},
{id:'pat',g:'d',t:'الصبر',tag:'d',tg:'دفاع: الصبر',def:'6-0',ball:[245,160],steps:[
 {cap:'اللاعب 4 يحمل الكرة أمام المدافع 5.'},
 {a:{3:[232,146]},b:[232,146],d:{4:[236,112]},cap:'المهاجم يتقدم ويحاول خداع المدافع بحركة الكرة.',quiz:{q:'المهاجم يخدع بالكرة. ماذا يفعل المدافع؟',opts:['يحافظ على وقفته ويترقب اللحظة المناسبة','يندفع فورًا لخطف الكرة','يدير ظهره ويتراجع'],ans:0,ok:'الصبر يمنع المهاجم من استغلال اندفاع المدافع.'}},
 {a:{3:[246,150]},b:[246,150],d:{4:[246,116]},cap:'الصبر: المدافع 5 يتحرك مع المهاجم بهدوء دون اندفاع، فلا يجد المهاجم طريقًا.'},
 {b:[196,112],d:{3:[196,112]},cap:'تمريرة متسرعة نحو لاعب الدائرة يقطعها المدافع 4. الصبر أجبر المهاجم على الخطأ دون أي مخالفة.'}
]},
{id:'trn',g:'t',t:'من الدفاع إلى الهجوم',tag:'d',tg:'تحول: من الدفاع إلى الهجوم',def:'6-0',ball:[95,160],steps:[
 {cap:'الهجوم يمرر من اللاعب 2 إلى اللاعب 3، والدفاع في وضع الاستعداد.'},
 {d:{2:[130,166]},b:[130,166],cap:'المدافع 3 يقطع التمريرة ويسترجع الكرة.',quiz:{q:'استرجع فريقك الكرة. ما القرار الأفضل؟',opts:['الانطلاق السريع للهجوم قبل أن ينتظم المنافس','الانتظار حتى يعود المنافس إلى مواقعه','الوقوف بالكرة في مكانها'],ans:0,ok:'التحول السريع يستغل لحظة عدم تنظيم المنافس.'}},
 {d:{0:[40,230],1:[90,250],2:[130,214],3:[250,250],4:[300,230],5:[170,268]},b:[130,214],cap:'التحول السريع: ينطلق اللاعبون فورًا في هجوم مرتد قبل أن يعود المنافس.'},
 {b:[300,230],cap:'تمريرة سريعة إلى الجناح المتقدم.'}
]},
{id:'rec',g:'t',t:'من الهجوم إلى الدفاع',tag:'d',tg:'تحول: من الهجوم إلى الدفاع',def:'6-0',ball:[170,176],steps:[
 {cap:'الفريق الأزرق يهاجم والكرة مع اللاعب 3.'},
 {b:[200,108],cap:'اللاعب 3 يسدد، والمدافع 4 يصد الكرة ويستحوذ عليها.'},
 {d:{0:[60,150],3:[200,150],5:[282,150]},b:[200,150],cap:'الفريق الأحمر ينطلق في هجوم مرتد.',quiz:{q:'فقد فريقك (الأزرق) الكرة. ما أول ما تفعله؟',opts:['أعود بسرعة لأقف بين الكرة ومرماي','أبقى في مكاني قرب مرمى الخصم','أنتظر حتى يصل الخصم إلى مرماي'],ans:0,ok:'العودة السريعة خلف الكرة تمنع الهجمة المرتدة.'}},
 {a:{0:[50,250],1:[110,268],2:[198,186],3:[240,268],4:[290,250],5:[170,272]},cap:'التحول للدفاع: أقرب لاعب (3) يؤخر حامل الكرة، وبقية الزملاء يعودون بسرعة خلف الكرة.'}
]}
];
const GR=[['a','مبادئ الهجوم'],['d','مبادئ الدفاع'],['t','التحول']];
/* سؤال المعلم المقترح لكل خطوة (مرحلة الوعي التكتيكي) */
const TQ={
pen:['أين الفراغ في خط الدفاع؟','لماذا اختار اللاعب 2 الاختراق بدل التمرير الجانبي؟','من أصبح بلا رقابة بعد تجمّع المدافعَين؟','متى أخترق ومتى أمرّر؟'],
sup:['كم خيار تمرير يملك حامل الكرة الآن؟','لماذا تحرّك اللاعب 2 بعد أن مرّر؟','ما الخطر إذا لم يقترب أحد من حامل الكرة؟','كيف نفتح زاوية تمرير لزميل تحت الضغط؟'],
wid:['لماذا يصعب التمرير عندما يتقارب المهاجمون؟','ماذا فعل اللاعبان 2 و4 ليوسّعا الملعب؟','لماذا تحرّك المدافعون؟ وأي جهة أصبحت أضعف؟','ما الذي صنع فرصة التسديد: المهارة الفردية أم الانتشار؟'],
mob:['لماذا يصعب التسديد أمام هذا الدفاع؟','ماذا حدث للمدافع عندما تحرّك لاعب الدائرة؟','من استفاد من حركة زميله بدون كرة؟','كيف يساعد لاعب لا يملك الكرة فريقه على التسجيل؟'],
cre:['ماذا يقرأ حامل الكرة في وقفة المدافعين؟','لماذا صدّق المدافعان الخداع؟','ما الحلول الأخرى التي كانت ممكنة هنا؟','متى يكون الحل غير المتوقع أفضل من الحل المعتاد؟'],
dly:['ما هدف المهاجم الآن؟ وما هدف الدفاع؟','من أقرب مدافع إلى حامل الكرة؟','لماذا لا يندفع المدافع لخطف الكرة فورًا؟','ماذا كسب الدفاع من تأخير المهاجم؟'],
cov:['كيف يقف المدافعون بالنسبة للكرة والمرمى؟','من المدافع الأول الآن؟ وما دوره؟','ما الخطر في الفراغ خلف المدافع المتقدم؟','لماذا لا يقف المدافع المغطي على نفس خط زميله؟'],
con:['أين يقف كل مدافع بالنسبة لمهاجمه وللمرمى؟','ماذا يجب أن يتغير في مواقع المدافعين بعد انتقال الكرة؟','كيف يراقب المدافع الكرة ومهاجمه في الوقت نفسه؟','ماذا يحدث لو تبع المدافعون الكرة فقط؟'],
bal:['كم مدافعًا في الجهة البعيدة عن الكرة؟','ماذا فعل المدافعون البعيدون عن الكرة؟','لماذا ينقل الهجوم الكرة بسرعة إلى الجهة الأخرى؟','ما الفرق بين هذا الدفاع والدفاع في الخطوة الأولى؟'],
pat:['ماذا يريد المهاجم من المدافع أن يفعل؟','ماذا يحدث لو اندفع المدافع الآن؟','إلى أين ينظر المدافع الصبور: الكرة أم جسم المهاجم؟','كيف استرجع الدفاع الكرة دون ارتكاب مخالفة؟'],
trn:['ما الذي يراقبه المدافع: الكرة أم اللاعب أم الاثنان؟','كيف توقّع المدافع 3 مسار التمريرة؟','لماذا يجب الانطلاق فورًا بعد استرجاع الكرة؟','ما أول قرار بعد قطع الكرة: التمرير أم الجري بها؟'],
rec:['أين يقف لاعبو الفريق الأزرق أثناء الهجوم؟','ماذا تغيّر في دور كل فريق لحظة فقد الكرة؟','من أقرب لاعب أزرق إلى الكرة؟ وما دوره؟','لماذا نعود خلف الكرة قبل محاولة استرجاعها؟']
};
function setStage(n){
 if(!n){T('stg').innerHTML='<b>لعب حر</b><span>يناسب المرحلتين 2 (تقدير اللعبة) و4 (اتخاذ القرار)</span>';return}
 T('stg').innerHTML=`<b class="${n===3?'':'off'}">3 الوعي التكتيكي</b><span aria-hidden="true">←</span><b class="${n===4?'':'off'}">4 اتخاذ القرار</b><span>${n===3?'شاهد وناقش':'اختر القرار الأنسب'}</span>`;
}
const NQ=PL.filter(p=>p.steps.some(x=>x.quiz)).length;
let grp=null,cur='6-0',mode=-1,dr=null,speed=1,steps=[],si=0,playing=false,raf=0,timer=0,anim=null,showLine=false,qState=0,tries=0;
let posA=ATT.map(cp),posD=DEF[cur].map(cp),posB=[192,166];
let sc={};try{sc=JSON.parse(lsGet('hb7q'))||{}}catch(e){sc={}}
const A=[],D=[];let ball;
function mk(cls,n,r,id){const g=document.createElementNS(NS,'g');g.setAttribute('class','p '+cls);if(id)g.dataset.id=id;g.innerHTML=`<circle r="${r}"/>${n?`<text y="4">${n}</text>`:''}`;pcs.appendChild(g);return g}
function put(g,x,y){x=Math.round(x*10)/10;y=Math.round(y*10)/10;g.dataset.x=x;g.dataset.y=y;g.setAttribute('transform',`translate(${x} ${y})`)}
ATT.forEach((_,i)=>A.push(mk('a',i+1,13,'A'+(i+1))));
for(let i=0;i<6;i++)D.push(mk('d',i+1,13,'D'+(i+1)));
ball=mk('b','',8,'B');
function lineUpd(){const L=T('dline');if(!showLine){L.setAttribute('points','');return}L.setAttribute('points',D.map(g=>[+g.dataset.x,+g.dataset.y]).sort((a,b)=>a[0]-b[0]).map(p=>p.join(',')).join(' '))}
function render(){A.forEach((g,i)=>put(g,posA[i][0],posA[i][1]));D.forEach((g,i)=>put(g,posD[i][0],posD[i][1]));put(ball,posB[0],posB[1]);lineUpd()}
function clearArrows(){T('arr').innerHTML=''}
function arrowsFor(i){
 clearArrows();if(i<1)return;
 const p=steps[i-1],n=steps[i];let h='';
 const ln=(a,b,end,c)=>{const dx=b[0]-a[0],dy=b[1]-a[1],d=Math.hypot(dx,dy);if(d<10)return '';const k=Math.max(0,d-end)/d;return `<line x1="${a[0]}" y1="${a[1]}" x2="${(a[0]+dx*k).toFixed(1)}" y2="${(a[1]+dy*k).toFixed(1)}" stroke="${c[0]}" stroke-width="2.5" stroke-dasharray="6 5" marker-end="url(#${c[1]})"/>`};
 n.a.forEach((q,j)=>{h+=ln(p.a[j],q,16,['#bfe0ff','ar-a'])});
 n.d.forEach((q,j)=>{h+=ln(p.d[j],q,16,['#ffc9c9','ar-d'])});
 h+=ln(p.b,n.b,10,['#ffffff','ar-b']);
 T('arr').innerHTML=h;
}
function drawZone(reveal){
 const q=steps[si]&&steps[si].quiz,z=q&&q.zone;
 T('zn').innerHTML=(reveal&&z)?`<circle class="pulse" cx="${z.x}" cy="${z.y}" r="${z.r}" fill="#ffd54a" fill-opacity=".25" stroke="#ffd54a" stroke-width="2" stroke-dasharray="6 4"/><text x="${z.x}" y="${z.y+4}" text-anchor="middle" fill="#fff" font-weight="700" font-size="13" font-family="Cairo,sans-serif">مساحة حرة</text>`:'';
}
function capText(i){const pl=PL[mode];T('ft').innerHTML=`<span class="tag ${pl.tag}">${pl.tg}</span> الخطوة ${i+1} من ${steps.length}`;T('fi').textContent=steps[i].cap||'';const q=(TQ[pl.id]||[])[i];T('tq').hidden=!q;T('tq').innerHTML=q?'<b>سؤال المعلم:</b> '+q:'';setStage(3,'الوعي التكتيكي','شاهد وناقش')}
function build(pl){
 let a=ATT.map(cp),d=DEF[pl.def].map(cp),b=cp(pl.ball);
 return pl.steps.map(s=>{
  if(s.a)for(const k in s.a)a[k]=cp(s.a[k]);
  if(s.d)for(const k in s.d)d[k]=cp(s.d[k]);
  if(s.b)b=cp(s.b);
  return{a:a.map(cp),d:d.map(cp),b:cp(b),cap:s.cap,quiz:s.quiz};
 });
}
function syncPlay(){
 const b=T('pp'),end=steps.length&&si>=steps.length-1&&!playing&&qState!==1;
 b.textContent=playing?'إيقاف':(end?'إعادة':'تشغيل');
 T('pv').disabled=si<=0;T('ctl').hidden=mode<0||qState===1;T('capbox').hidden=qState===1;T('nx').disabled=si>=steps.length-1;
}
function snap(){
 if(anim){cancelAnimationFrame(raf);anim=null;const s=steps[si];posA=s.a.map(cp);posD=s.d.map(cp);posB=cp(s.b);render()}
}
function stopAll(){clearTimeout(timer);cancelAnimationFrame(raf);anim=null;playing=false}
function tick(now){
 const s=steps[si],t=Math.min(1,(now-anim.t0)/anim.dur),e=t*t*t*(t*(6*t-15)+10);
 const L=(a,b)=>[a[0]+(b[0]-a[0])*e,a[1]+(b[1]-a[1])*e];
 posA=s.a.map((p,j)=>L(anim.f.a[j],p));posD=s.d.map((p,j)=>L(anim.f.d[j],p));posB=L(anim.f.b,s.b);
 render();
 if(t<1){raf=requestAnimationFrame(tick)}
 else{anim=null;posA=s.a.map(cp);posD=s.d.map(cp);posB=cp(s.b);render();arrive(si)}
}
function goStep(i,animate){
 clearTimeout(timer);cancelAnimationFrame(raf);anim=null;
 i=Math.max(0,Math.min(steps.length-1,i));si=i;qState=0;T('qbox').hidden=true;
 const s=steps[i];arrowsFor(i);T('slr').value=i;drawZone(false);capText(i);
 if(animate&&!REDUCE){anim={f:{a:posA.map(cp),d:posD.map(cp),b:cp(posB)},t0:performance.now(),dur:2600/speed};raf=requestAnimationFrame(tick)}
 else{posA=s.a.map(cp);posD=s.d.map(cp);posB=cp(s.b);render();arrive(i)}
 syncPlay();
}
function arrive(i){
 const s=steps[i],pl=PL[mode];
 if(s.quiz&&!sc[pl.id]){openQuiz(s);return}
 if(playing){if(i<steps.length-1)timer=setTimeout(()=>goStep(i+1,true),1500/speed);else playing=false}
 syncPlay();
}
function setQ(t,k){const m=T('qmsg');m.textContent=t;m.className='msg'+(k?' '+k:'')}
function openQuiz(s){
 const q=s.quiz;playing=false;qState=1;tries=0;setStage(4,'اتخاذ القرار','أجب عن السؤال');
 T('qbox').hidden=false;T('qq').textContent=q.q;T('qh').textContent=q.h||'';
 T('qopts').innerHTML=q.opts.map((o,k)=>`<button class="btn" data-o="${k}">${o}</button>`).join('');
 T('qnext').hidden=true;T('qskip').hidden=false;setQ('');try{T('qbox').scrollIntoView({block:'nearest',behavior:REDUCE?'auto':'smooth'})}catch(e){}
 D.concat(A).forEach(g=>g.classList.remove('q'));
 syncPlay();
}
function answerQ(ok){
 if(qState!==1)return;
 const q=steps[si].quiz;
 if(ok){
  qState=2;sc[PL[mode].id]=1;lsSet('hb7q',JSON.stringify(sc));
  setQ('صحيح! '+q.ok,'ok');drawZone(true);
  T('qopts').querySelectorAll('button').forEach((b,k)=>{b.disabled=true;if(k===q.ans)b.classList.add('on')});
  T('qnext').hidden=si>=steps.length-1;T('qskip').hidden=true;
  D.concat(A).forEach(g=>g.classList.remove('q'));
  updScore();drawPlays();syncPlay();
 }else{
  tries++;setQ('ليست الإجابة الصحيحة. حاول مرة أخرى.','er');
  if(tries>=2){
   if(q.zone){drawZone(true);setQ('ليست الإجابة الصحيحة. لاحظ المنطقة المضيئة في الملعب.','er')}
   if(q.pick){const g=D.concat(A).find(x=>x.dataset.id===q.pick);if(g){g.classList.add('q');setQ('ليست الإجابة الصحيحة. لاحظ اللاعب المميّز بالأصفر.','er')}}
  }
 }
}
T('qopts').onclick=e=>{
 const b=e.target.closest('[data-o]');if(!b||qState!==1)return;
 const ok=Number(b.dataset.o)===steps[si].quiz.ans;
 if(!ok)b.disabled=true;
 answerQ(ok);
};
function leaveQuiz(){qState=0;T('qbox').hidden=true;if(si<steps.length-1){playing=true;goStep(si+1,true)}else syncPlay()}
T('qnext').onclick=leaveQuiz;T('qskip').onclick=leaveQuiz;
function updScore(){const n=PL.filter(p=>sc[p.id]).length;T('qscore').textContent=n?`إجاباتك الصحيحة في الأسئلة: ${n} من ${NQ}`:''}
function drawPlays(){
 T('plays').innerHTML=`<button class="btn ${mode<0&&!grp?'on':''}" data-p="-1" aria-pressed="${mode<0&&!grp}">لعب حر</button>`+GR.map(([g,n])=>{const L=PL.filter(p=>p.g===g),dn=L.filter(p=>sc[p.id]).length;return `<button class="btn pt-${g} ${grp===g?'on':''}" data-g="${g}" aria-pressed="${grp===g}">${n} (${L.length})${dn===L.length?' ✓':''}</button>`}).join('');
 T('plist').hidden=!grp;
 T('plist').innerHTML=grp?PL.map((p,i)=>p.g===grp?`<button class="btn ${mode===i?'on':''}" data-p="${i}" aria-pressed="${mode===i}">${p.t}${sc[p.id]?' ✓':''}</button>`:'').join(''):'';
 document.querySelectorAll('#forms .btn').forEach(b=>b.classList.toggle('on',mode<0&&b.dataset.f===cur));T('forms').hidden=mode>=0;
}
function layout(){
 stopAll();mode=-1;grp=null;steps=[];qState=0;si=0;
 posA=ATT.map(cp);posD=DEF[cur].map(cp);posB=[192,166];render();
 clearArrows();T('zn').innerHTML='';T('ctl').hidden=true;T('capbox').hidden=false;T('qbox').hidden=true;
 D.concat(A).forEach(g=>g.classList.remove('q'));
 T('ft').textContent='الدفاع '+cur;T('fi').textContent=INFO[cur];T('tq').hidden=false;T('tq').innerHTML='<b>سؤال المعلم:</b> حرّك مدافعًا ثم اسأل: ماذا تفعل الآن، تمرر أم تخترق أم تسدد؟';setStage(0,'لعب حر','يناسب المرحلتين 2 (تقدير اللعبة) و4 (اتخاذ القرار)');T('reset').textContent='إعادة الأوضاع';
 drawPlays();
}
function loadPlay(i){
 stopAll();mode=i;grp=PL[i].g;steps=build(PL[i]);si=0;qState=0;
 const s=steps[0];posA=s.a.map(cp);posD=s.d.map(cp);posB=cp(s.b);render();
 T('ctl').hidden=false;T('slr').max=steps.length-1;T('reset').textContent='إعادة السيناريو';
 drawPlays();goStep(0,false);
}
T('plays').onclick=e=>{const g=e.target.closest('[data-g]');if(g){loadPlay(PL.findIndex(p=>p.g===g.dataset.g));return}if(e.target.closest('[data-p]'))layout()};
T('plist').onclick=e=>{const b=e.target.closest('[data-p]');if(b)loadPlay(Number(b.dataset.p))};
T('forms').innerHTML=Object.keys(DEF).map(k=>`<button class="btn" data-f="${k}">دفاع ${k}</button>`).join('');
T('forms').onclick=e=>{const b=e.target.closest('[data-f]');if(b){cur=b.dataset.f;layout()}};
T('reset').onclick=()=>{if(mode<0)layout();else{stopAll();goStep(0,false)}};
T('dlbtn').onclick=()=>{showLine=!showLine;T('dlbtn').setAttribute('aria-pressed',showLine);T('dlbtn').classList.toggle('on',showLine);T('dlbtn').textContent=showLine?'إخفاء خط الدفاع':'إظهار خط الدفاع';lineUpd()};
T('pp').onclick=()=>{
 if(playing){snap();stopAll();syncPlay();return}
 if(qState===1)return;
 if(si>=steps.length-1){playing=true;goStep(0,false)}
 else{playing=true;goStep(si+1,true)}
 syncPlay();
};
T('nx').onclick=()=>{snap();stopAll();if(qState===1)qState=0;goStep(si+1,true)};
T('pv').onclick=()=>{snap();stopAll();goStep(si-1,true)};
T('slr').oninput=e=>{snap();stopAll();goStep(Number(e.target.value),false)};
T('spd').onclick=()=>{speed=speed===1?1.5:speed===1.5?0.5:1;T('spd').textContent='×'+speed};
function pos(e){const pt=svg.createSVGPoint();pt.x=e.clientX;pt.y=e.clientY;return pt.matrixTransform(svg.getScreenCTM().inverse())}
function ring(p,ok){const c=document.createElementNS(NS,'circle');c.setAttribute('cx',p.x);c.setAttribute('cy',p.y);c.setAttribute('r',12);c.setAttribute('fill','none');c.setAttribute('stroke',ok?'#7fd9a1':'#ff9c94');c.setAttribute('stroke-width','4');T('zn').appendChild(c);setTimeout(()=>c.remove(),800)}
svg.addEventListener('pointerdown',e=>{
 if(mode>=0){
  if(qState!==1)return;
  const q=steps[si].quiz;if(!q)return;const p=pos(e);
  if(q.pick){const g=e.target.closest('g.p');if(g&&g.dataset.id&&g.dataset.id!=='B'){const ok=g.dataset.id===q.pick;ring(p,ok);answerQ(ok)}return}
  if(q.zone){const ok=Math.hypot(p.x-q.zone.x,p.y-q.zone.y)<=q.zone.r;ring(p,ok);answerQ(ok)}
  return;
 }
 const g=e.target.closest('g.p');if(!g)return;dr=g;svg.setPointerCapture(e.pointerId);pcs.appendChild(g)});
svg.addEventListener('pointermove',e=>{if(!dr)return;const p=pos(e);put(dr,Math.max(14,Math.min(326,p.x)),Math.max(14,Math.min(286,p.y)));lineUpd()});
svg.addEventListener('pointerup',()=>{dr=null});
svg.addEventListener('pointercancel',()=>{dr=null});
layout();updScore();

/* ---------- progress (student view) ---------- */
let pc=lsGet('hb7cls');
if(!CLASSES.includes(pc)){const withData=CLASSES.find(c=>bySess(c).length);pc=withData||CLASSES[0]}

function mark(shape,c,x,y,r){
 if(shape==='circle')return `<circle cx="${x}" cy="${y}" r="${r}" fill="${c}"/>`;
 if(shape==='square')return `<rect x="${x-r}" y="${y-r}" width="${2*r}" height="${2*r}" fill="${c}"/>`;
 if(shape==='triangle')return `<polygon points="${x},${y-r-1} ${x-r-1},${y+r} ${x+r+1},${y+r}" fill="${c}"/>`;
 return `<polygon points="${x},${y-r-1} ${x+r+1},${y} ${x},${y+r+1} ${x-r-1},${y}" fill="${c}"/>`;
}
function chart(list,fn,title){
 const W_=340,H_=190,L=34,R=14,Tp=12,B=30,pw=W_-L-R,ph=H_-Tp-B,n=list.length;
 const PD=16,X=i=>n===1?L+pw/2:(W_-R-PD)-i*((pw-2*PD)/(n-1));
 const Y=v=>Tp+ph*(1-v/100);
 let g='';
 [0,25,50,75,100].forEach(v=>{g+=`<line class="ch-g" x1="${L}" x2="${W_-R}" y1="${Y(v)}" y2="${Y(v)}"/><text class="ch-t" x="${L-5}" y="${Y(v)+4}" text-anchor="end">${v}</text>`});
 const step=n>8?Math.ceil(n/6):1;
 list.forEach((s,i)=>{if(i%step===0||i===n-1)g+=`<text class="ch-t" x="${X(i)}" y="${H_-10}" text-anchor="middle">${sd(s)}</text>`});
 let latest=[];
 TM.forEach(([t,nm,c,sh])=>{
  let pts=[],line='';
  list.forEach((s,i)=>{const v=fn(s,t);if(v===null){if(pts.length>1)line+=`<polyline fill="none" stroke="${c}" stroke-width="2.5" points="${pts.join(' ')}"/>`;pts=[];return}pts.push(X(i)+','+Y(v))});
  if(pts.length>1)line+=`<polyline fill="none" stroke="${c}" stroke-width="2.5" points="${pts.join(' ')}"/>`;
  g+=line;
  list.forEach((s,i)=>{const v=fn(s,t);if(v!==null)g+=mark(sh,c,X(i),Y(v),4.5)});
  const lv=fn(list[n-1],t);latest.push('فريق '+nm+' '+fp(lv));
 });
 return `<h3>${title}</h3><svg class="chart" viewBox="0 0 ${W_} ${H_}" role="img" aria-label="${title}. آخر حصة: ${latest.join('، ')}">${g}</svg>`;
}
function legend(){return '<div class="leg">'+TM.map(([t,nm,c,sh])=>`<span><svg width="14" height="14" viewBox="0 0 14 14" aria-hidden="true">${mark(sh,c,7,7,5)}</svg>فريق ${nm}</span>`).join('')+'</div>'}
function delta(cur_,prev){
 if(cur_===null||prev===null)return '';
 const d=cur_-prev;
 if(d>0)return `<span class="dl up" aria-label="ارتفاع ${d} نقطة عن الحصة السابقة">▲ ${d}</span>`;
 if(d<0)return `<span class="dl dn" aria-label="انخفاض ${-d} نقطة عن الحصة السابقة">▼ ${-d}</span>`;
 return `<span class="dl eq" aria-label="بلا تغيير عن الحصة السابقة">● 0</span>`;
}
function histTable(s){
 return `<table class="tb"><thead><tr><th>الفريق</th><th>تمرير ✓</th><th>تمرير ✗</th><th>دقة</th><th>تسديد</th><th>أهداف</th><th>كفاءة</th><th>استرجاع</th></tr></thead><tbody>`+TM.map(([t,nm])=>{const x=s.teams[t];return `<tr><td>فريق ${nm}</td><td>${x.pa}</td><td>${x.pl}</td><td>${fp(passAcc(s,t))}</td><td>${x.sh}</td><td>${x.gl}</td><td>${fp(shootEff(s,t))}</td><td>${x.st}</td></tr>`}).join('')+`</tbody></table>`;
}
function prinTable(s){
 return `<table class="tb"><thead><tr><th rowspan="2">الفريق</th><th colspan="3" class="att">هجوم</th><th colspan="3" class="dfn">دفاع</th></tr><tr>`+P.map(([k])=>`<th>${PS[k]}</th>`).join('')+`</tr></thead><tbody>`+TM.map(([t,nm])=>{const x=s.teams[t];return `<tr><td>فريق ${nm}</td>`+P.map(([k])=>`<td>${gv(x,k)}</td>`).join('')+`</tr>`}).join('')+`</tbody></table>`;
}
function prinSum(x){
 const tot=atk(x)+dfn(x);if(!tot)return '';
 const arr=P.map(([k,n])=>[n,gv(x,k)]);
 const mx=arr.reduce((a,b)=>b[1]>a[1]?b:a),mn=arr.reduce((a,b)=>b[1]<a[1]?b:a);
 return `<div class="sum">الأقوى: ${mx[0]} (${mx[1]})${mn[1]<mx[1]?` · يحتاج تحسينًا: ${mn[0]} (${mn[1]})`:''}</div>`;
}
function prinBlock(last){
 let h=`<h2>مبادئ الهجوم والدفاع</h2><p class="sub">عدد المرات التي طبّق فيها كل فريق المبدأ في آخر حصة، كما سجّلها الطالب الملاحظ.</p>`;
 h+=`<div class="box">`+TM.map(([t,nm,c])=>{const x=last.teams[t],a=atk(x),d=dfn(x),tot=a+d,pa=tot?Math.round(a/tot*100):0;return `<div class="lbl"><span>فريق ${nm}</span><b>هجوم ${a} · دفاع ${d}</b></div><div class="bar" role="img" aria-label="فريق ${nm}: هجوم ${a} ودفاع ${d}">${tot?`<i style="width:${pa}%;background:var(--att)"></i><i style="width:${100-pa}%;background:var(--def)"></i>`:''}</div>`}).join('')+`<div class="leg"><span><i style="display:inline-block;width:12px;height:12px;background:var(--att);border-radius:3px"></i>هجوم</span><span><i style="display:inline-block;width:12px;height:12px;background:var(--def);border-radius:3px"></i>دفاع</span></div></div>`;
 h+=prinTable(last);
 h+=TM.map(([t,nm])=>{const m=prinSum(last.teams[t]);return m?`<div class="sum"><b>فريق ${nm}</b> — ${m.replace(/<[^>]+>/g,'')}</div>`:''}).join('');
 h+=`<div class="box goal"><b>اسأل فريقك</b><p style="margin:4px 0 0">أي مبدأ أثّر أكثر في نتيجتنا؟ وأي مبدأ سنطبّقه أكثر في الحصة القادمة؟</p></div>`;
 return h;
}
function drawProg(){
 T('pcls').innerHTML=CLASSES.map(c=>{const n=bySess(c).length;return `<button class="btn ${c===pc?'on':''}" data-pc="${c}" aria-pressed="${c===pc}">${c}${n?` (${n})`:''}</button>`}).join('');
 const list=bySess(pc),b=T('pbody');
 if(!list.length){b.innerHTML=`<div class="box empty">لم تُسجَّل حصص للشعبة ${pc} بعد.<br>ستظهر هنا نتائج فريقك وتقدمه بعد أول حصة.</div>`;return}
 const last=list[list.length-1],prev=list.length>1?list[list.length-2]:null;
 let h=`<h2>آخر حصة: ${sd(last)} · الأسبوع ${last.wk} (${WN[last.wk]||''})</h2>`;
 h+=`<div class="tcs">`+TM.map(([t,nm,c,sh])=>{
  const x=last.teams[t],pa=passAcc(last,t),se=shootEff(last,t);
  const dp=prev?delta(pa,passAcc(prev,t)):'',ds=prev?delta(se,shootEff(prev,t)):'';
  return `<div class="tc" style="border-color:${c}"><div class="th"><svg width="14" height="14" viewBox="0 0 14 14" aria-hidden="true">${mark(sh,c,7,7,5)}</svg>فريق ${nm}</div><div class="kv">دقة التمرير <b>${fp(pa)}</b>${dp}</div><div class="kv">كفاءة التسديد <b>${fp(se)}</b>${ds}</div><div class="mini">أهداف ${x.gl} · استرجاع كرة ${x.st}</div>${hasP(last)?`<div class="mini">مبادئ: هجوم ${atk(x)} · دفاع ${dfn(x)}</div>`:''}</div>`}).join('')+`</div>`;
 if(hasP(last))h+=prinBlock(last);
 if(prev)h+=`<p class="sub" style="margin-top:6px">الأسهم تقارن مع الحصة السابقة (${sd(prev)}) بالنقاط المئوية.</p>`;
 if(last.goal)h+=`<div class="box goal"><b>هدف الفرق للحصة القادمة</b><p style="margin:4px 0 0">${esc(last.goal)}</p></div>`;
 if(last.note)h+=`<div class="box"><b>ملاحظة المعلم</b><p style="margin:4px 0 0">${esc(last.note)}</p></div>`;
 h+=`<h2>التقدم عبر الحصص</h2>`;
 if(list.length<2)h+=`<p class="sub">يظهر خط التقدم بعد تسجيل حصتين أو أكثر.</p>`;
 h+=legend()+chart(list,passAcc,'دقة التمرير (%)')+chart(list,shootEff,'كفاءة التسديد (%)');
 h+=`<h2>سجل الحصص</h2>`+list.slice().reverse().map((s,i)=>`<details class="hs" ${i?'':'open'}><summary><span>${sd(s)} · الأسبوع ${s.wk}<small>${WN[s.wk]||''}</small></span></summary><div style="padding:0 10px 4px">${histTable(s)}${hasP(s)?prinTable(s):''}</div></details>`).join('');
 b.innerHTML=h;
}
T('pcls').onclick=e=>{const b=e.target.closest('[data-pc]');if(b){pc=b.dataset.pc;lsSet('hb7cls',pc);rc=pc;drawProg();drawRec(true)}};

/* ---------- server ---------- */
const API='https://script.google.com/macros/s/AKfycbxYSiPiQVxnorfugCDZ7XOE1V4VwHm9BsENM04iiypCkcPv-8No5bJxxEnyAzBsUjA_/exec';  // رابط Apps Script (Web app)
const DEMO=!API;
function ssGet(k){try{return sessionStorage.getItem(k)}catch(e){return null}}
function ssSet(k,v){try{sessionStorage.setItem(k,v)}catch(e){}}
function ssDel(k){try{sessionStorage.removeItem(k)}catch(e){}}
function okSess(s){
 if(!s||!CLASSES.includes(s.cls)||!/^\d{4}-\d{2}-\d{2}$/.test(String(s.date)))return false;
 if(!(Number(s.wk)>=1&&Number(s.wk)<=4))return false;
 return TM.every(([t])=>s.teams&&s.teams[t]&&M.every(([k])=>Number.isFinite(Number(s.teams[t][k]))&&Number(s.teams[t][k])>=0)&&P.every(([k])=>s.teams[t][k]===undefined||(Number.isFinite(Number(s.teams[t][k]))&&Number(s.teams[t][k])>=0)));
}
function hhmm(){const d=new Date();return String(d.getHours()).padStart(2,'0')+':'+String(d.getMinutes()).padStart(2,'0')}
function setSync(t,er){const e=T('sync');e.textContent=t;T('sync').parentNode.className='sync'+(er?' er':'')}
async function api(body){
 if(DEMO)return demoApi(body);
 const ctl=new AbortController(),tm=setTimeout(()=>ctl.abort(),20000);
 try{const r=await fetch(API,{method:'POST',headers:{'Content-Type':'text/plain;charset=utf-8'},body:JSON.stringify(body),signal:ctl.signal});return await r.json()}finally{clearTimeout(tm)}
}
function demoApi(b){
 if(b.act==='check')return{ok:1,role:'teacher'};
 if(b.act==='add'){ST.sessions.push(Object.assign({},b.session,{id:Date.now().toString(36),ts:Date.now()}));return{ok:1}}
 if(b.act==='update'){const i=ST.sessions.findIndex(s=>s.id===b.id);if(i<0)return{err:'missing'};ST.sessions[i]=Object.assign({},b.session,{id:b.id,ts:ST.sessions[i].ts});return{ok:1}}
 if(b.act==='delete'){ST.sessions=ST.sessions.filter(s=>s.id!==b.id);return{ok:1}}
 return{ok:1};
}
async function loadState(){
 if(DEMO){setSync('نسخة تجريبية: لم يُربط الخادم بعد، وتُمحى البيانات عند تحديث الصفحة.',true);return}
 try{
  const r=await fetch(API+(API.indexOf('?')<0?'?':'&')+'t='+Date.now());
  const d=await r.json();
  ST={v:1,sessions:(Array.isArray(d.sessions)?d.sessions:[]).filter(okSess)};
  lsSet('hb7cache',JSON.stringify(ST));setSync('آخر تحديث '+hhmm());
 }catch(e){
  try{const c=JSON.parse(lsGet('hb7cache'));if(c&&Array.isArray(c.sessions))ST={v:1,sessions:c.sessions.filter(okSess)}}catch(_){}
  setSync('تعذّر الاتصال بالخادم. تُعرض آخر بيانات محفوظة على هذا الجهاز.',true);
 }
}
async function refresh(first){
 await loadState();
 if(first&&!lsGet('hb7cls')){const w=CLASSES.find(c=>bySess(c).length);if(w){pc=w;rc=w;if(!R.editId)R.cls=w}}
 drawProg();drawSaved();if(first)drawRec();
}
T('rf').onclick=()=>refresh(false);
document.addEventListener('visibilitychange',()=>{if(!document.hidden&&!busy)refresh(false)});
setInterval(()=>{if(!document.hidden&&!busy)refresh(false)},60000);

/* ---------- recorder ---------- */
let rc=pc,ct='a',R,busy=false,TEACHER=false,TP=ssGet('hb7tp')||'';
function freshDraft(){return{cls:rc,date:today(),wk:wkOf(today()),teams:emptyTeams(),goal:'',note:'',editId:null}}
function loadDraft(){try{const d=JSON.parse(lsGet('hb7draft'));if(d&&d.teams&&d.date){const f=freshDraft();TM.forEach(([t])=>{ALLK.forEach(([k])=>{f.teams[t][k]=Number(d.teams[t]&&d.teams[t][k])||0})});f.cls=CLASSES.includes(d.cls)?d.cls:rc;f.date=d.date;f.wk=Number(d.wk)||wkOf(d.date);return f}}catch(e){}return freshDraft()}
R=loadDraft();rc=R.cls;
function keepDraft(){if(!R.editId)lsSet('hb7draft',JSON.stringify({cls:R.cls,date:R.date,wk:R.wk,teams:R.teams}))}
function setMsg(t,k){const m=T('msg');m.textContent=t||'';m.className='msg'+(k?' '+k:'')}
function applyRole(){
 T('tpanel').hidden=!TEACHER;T('tsaved').hidden=!TEACHER;T('tadmin').hidden=!TEACHER;
 T('tlogin').hidden=TEACHER;
 T('rintro').textContent=TEACHER
  ?'وضع المعلم: سجّل الأرقام أو عدّل الحصص المحفوظة، وغيّر الأرقام السرية من الأسفل. يظهر كل ما تحفظه للطلاب في تبويب «تقدم الفرق».'
  :'وضع الطالب الملاحظ: سجّل أحداث الفرق ومبادئ الهجوم والدفاع أثناء اللعب، ثم اضغط «حفظ الحصة» مرتين للتأكيد. تظهر النتائج بعدها لجميع الطلاب في تبويب «تقدم الفرق». إن كان زملاؤك يسجّلون الفرق الأخرى في نفس الحصة، فيحفظ كل واحد فريقه، وتُجمع أرقام الفرق تلقائيًا في «تقدم الفرق». لا يمكنك تعديل حصة بعد حفظها، فراجع أرقامك قبل الحفظ. أرقامك محفوظة على جهازك حتى لو أُغلقت الصفحة.';
}
function drawSaved(){
 const list=rawSess(R.cls).slice().reverse();
 T('saved').innerHTML=list.length?list.map(s=>`<div class="sl"><span>${sd(s)} · الأسبوع ${s.wk} · ${TM.filter(([t])=>hasData(s.teams[t])).map(([t,n])=>'فريق '+n).join('، ')||'بلا أرقام'}${R.editId===s.id?' (قيد التعديل)':''}</span><span class="acts"><button class="btn sm" data-ed="${s.id}">تعديل</button><button class="btn sm dng" data-del="${s.id}">حذف</button></span></div>`).join(''):`<p class="sub">لا توجد حصص محفوظة للشعبة ${R.cls}.</p>`;
}
function drawRec(sync){
 if(sync&&!R.editId){R.cls=rc}
 T('rcls').innerHTML=CLASSES.map(c=>`<button class="btn ${c===R.cls?'on':''}" data-rc="${c}" aria-pressed="${c===R.cls}">${c}</button>`).join('');
 T('rdate').value=R.date;
 T('rwk').innerHTML=[1,2,3,4].map(w=>`<option value="${w}" ${w===R.wk?'selected':''}>${w} – ${WN[w]}</option>`).join('');
 T('tm').innerHTML=TM.map(([t,n,c])=>`<button class="btn ${t==ct?'on':''}" data-tm="${t}" style="border:2px solid ${c}" aria-pressed="${t==ct}">فريق ${n}</button>`).join('');
 T('rows').innerHTML=M.map(([k,n])=>`<div class="row"><span>${n}</span><div class="ctr"><button data-k="${k}" data-d="-1" aria-label="إنقاص ${n}">−</button><output>${R.teams[ct][k]}</output><button data-k="${k}" data-d="1" aria-label="زيادة ${n}">+</button></div></div>`).join('');
 const st=[['دقة التمرير',(t)=>pct(R.teams[t].pa,R.teams[t].pa+R.teams[t].pl)],['كفاءة التسديد',(t)=>pct(R.teams[t].gl,R.teams[t].sh)]];
 T('prin').innerHTML=[['a','الهجوم'],['d','الدفاع والتحول']].map(([g,gn])=>`<div class="grp ${g}">${gn}</div>`+P.filter(x=>x[2]===g).map(([k,n,_g,ds])=>`<div class="row"><span>${n}<small>${ds}</small></span><div class="ctr"><button data-k="${k}" data-d="-1" aria-label="إنقاص ${n}">−</button><output>${R.teams[ct][k]}</output><button data-k="${k}" data-d="1" aria-label="زيادة ${n}">+</button></div></div>`).join('')).join('');
 T('stats').innerHTML=st.map(([n,f])=>`<h3>${n}</h3>`+TM.map(([t,nm,c])=>{const v=f(t);return `<div class="lbl"><span>فريق ${nm}</span><b>${fp(v)}</b></div><div class="bar"><i style="width:${v||0}%;background:${c}"></i></div>`}).join('')).join('');
 if(document.activeElement!==T('rgoal'))T('rgoal').value=R.goal;
 if(document.activeElement!==T('rnote'))T('rnote').value=R.note;
 T('save').textContent=R.editId?'حفظ التعديلات':'حفظ الحصة';
 T('cancel').hidden=!R.editId;
 drawSaved();mkPrompt();keepDraft();
}
T('rcls').onclick=e=>{const b=e.target.closest('[data-rc]');if(!b)return;R.cls=b.dataset.rc;rc=R.cls;R.editId=null;setMsg('');drawRec();}
T('rdate').onchange=e=>{if(e.target.value){R.date=e.target.value;R.wk=wkOf(R.date);drawRec()}};
T('rwk').onchange=e=>{R.wk=Number(e.target.value);keepDraft()};
T('tm').onclick=e=>{const b=e.target.closest('[data-tm]');if(b){ct=b.dataset.tm;drawRec()}};
function bump(e){const b=e.target.closest('button');if(!b||!b.dataset.k)return;const k=b.dataset.k;R.teams[ct][k]=Math.max(0,Math.min(999,R.teams[ct][k]+Number(b.dataset.d)));drawRec()}
T('rows').onclick=bump;T('prin').onclick=bump;
T('rgoal').oninput=e=>{R.goal=e.target.value};
T('rnote').oninput=e=>{R.note=e.target.value};
T('zero').onclick=()=>{R.teams=emptyTeams();setMsg('');drawRec()};
T('cancel').onclick=()=>{R=freshDraft();R.cls=rc;setMsg('تم إلغاء التعديل.');drawRec()};
T('cp').onclick=()=>{const t=T('pr');t.select();try{navigator.clipboard.writeText(t.value)}catch(e){try{document.execCommand('copy')}catch(_){}}T('cp').textContent='تم النسخ';setTimeout(()=>T('cp').textContent='نسخ البرومبت',1500)};
function mkPrompt(){const r=t=>{const x=R.teams[t];return `تمريرات ناجحة ${x.pa}، مقطوعة ${x.pl}، دقة التمرير ${fp(pct(x.pa,x.pa+x.pl))}، تسديدات ${x.sh}، أهداف ${x.gl}، كفاءة التسديد ${fp(pct(x.gl,x.sh))}، استرجاع الكرة ${x.st}. مبادئ الهجوم المطبّقة: مساندة وانتشار ${x.sp}، اختراق ${x.pe}، استغلال المساحة ${x.fs}. مبادئ الدفاع المطبّقة: تغطية ${x.cv}، تأخير الخصم ${x.dy}، تحول سريع ${x.tr}`};
 const me=TM.find(m=>m[0]==ct)[1],o=TM.filter(m=>m[0]!=ct).map(m=>`فريق ${m[1]}: ${r(m[0])}`).join(NL);
 T('pr').value=`أنت مدرب كرة يد لطلاب الصف السابع. هذه بيانات مباراة مصغرة لأربعة فرق.${NL}فريقي (فريق ${me}): ${r(ct)}.${NL}الفرق الأخرى:${NL}${o}${NL}المطلوب بلغة بسيطة: 1) نقطة قوة واحدة لفريقي. 2) مبدأ واحد من مبادئ الهجوم أو الدفاع يحتاج إلى تحسين، مع تمرين بسيط لتطبيقه. 3) هدف واحد للمباراة القادمة. استخدم مصطلحين فنيين على الأقل مثل: الاستحواذ، المساندة، الانتشار، الاختراق، التغطية.`}

/* ---------- saving ---------- */
const ERR={full:'تم الوصول إلى الحد الأقصى للحصص المسجّلة في هذا اليوم. أخبر معلمك.',pin:'رقم المعلم غير صحيح.',role:'هذا الرقم لا يسمح بهذا الإجراء. استخدم رقم المعلم.',bad:'بيانات الحصة غير صالحة. راجع الأرقام والتاريخ.',missing:'لم تعد هذه الحصة موجودة.',badpin:'الرقم الجديد يجب أن يتكون من 4 إلى 8 أرقام.',server:'حدث خطأ في الخادم. حاول مرة أخرى.'};
const NETERR='تعذّر الاتصال بالخادم. أرقامك ما زالت محفوظة على جهازك، حاول مرة أخرى.';
async function call(body,okMsg,after){
 if(busy)return false;busy=true;setMsg('جارٍ الحفظ...');
 try{
  const res=await api(body);
  if(res&&res.ok){setMsg(okMsg+(res.dup?' (كانت محفوظة من قبل)':''),'ok');if(after)await after(res);busy=false;return true}
  setMsg(ERR[res&&res.err]||ERR.server,'er');
 }catch(e){setMsg(NETERR,'er')}
 busy=false;return false;
}
let saveArm=null;
function saveLabel(){T('save').textContent=R.editId?'حفظ التعديلات':'حفظ الحصة'}
T('save').onclick=async()=>{
 const any=TM.some(([t])=>ALLK.some(([k])=>R.teams[t][k]>0));
 if(!any){setMsg('لا توجد أرقام لحفظها. سجّل أحداث الفرق أولاً.','er');return}
 if(!R.date){setMsg('اختر تاريخ الحصة.','er');return}
 if(!R.editId&&!saveArm){
  saveArm=setTimeout(()=>{saveArm=null;saveLabel()},6000);
  const tn=TM.filter(([t])=>hasData(R.teams[t])).map(([t,n])=>n).join('، ');
  T('save').textContent='تأكيد: حفظ أرقام فريق '+tn+' للشعبة '+R.cls+' ('+sd(R)+')؟';return;
 }
 clearTimeout(saveArm);saveArm=null;
 const rec={cls:R.cls,date:R.date,wk:R.wk,teams:clone(R.teams)};
 if(TEACHER){rec.goal=R.goal.trim();rec.note=R.note.trim()}
 const body=R.editId&&TEACHER?{act:'update',pin:TP,id:R.editId,session:rec}:{act:'add',pin:TEACHER?TP:'',session:rec};
 const ok=await call(body,'تم الحفظ. النتائج ظاهرة الآن للطلاب.',async()=>{
  lsDel('hb7draft');R=freshDraft();R.cls=rc;drawRec();
  await loadState();drawProg();drawSaved();
 });
 if(!ok)saveLabel();
};
let delArm=null,delT=null;
T('saved').onclick=async e=>{
 const ed=e.target.closest('[data-ed]'),dl=e.target.closest('[data-del]');
 if(ed){const s=ST.sessions.find(x=>x.id===ed.dataset.ed);if(!s)return;R={cls:s.cls,date:s.date,wk:s.wk,teams:clone(s.teams),goal:s.goal||'',note:s.note||'',editId:s.id};rc=s.cls;setMsg('تم تحميل الحصة للتعديل. عدّل الأرقام ثم احفظ.');drawRec();T('rows').scrollIntoView({behavior:'smooth',block:'center'});return}
 if(dl){
  const id=dl.dataset.del;
  if(delArm!==id){delArm=id;dl.textContent='تأكيد الحذف؟';clearTimeout(delT);delT=setTimeout(()=>{delArm=null;drawSaved()},4000);return}
  clearTimeout(delT);delArm=null;
  await call({act:'delete',pin:TP,id},'تم حذف الحصة.',async()=>{if(R.editId===id){R=freshDraft();R.cls=rc}await loadState();drawProg();drawRec()});
 }
};
/* teacher login and PIN admin */
async function teacherLogin(pin,quiet){
 try{
  const res=await api({act:'check',pin});
  if(res&&res.ok&&res.role==='teacher'){TEACHER=true;TP=pin;ssSet('hb7tp',pin);applyRole();drawRec();if(!quiet)setMsg('تم دخول المعلم.','ok');return true}
  if(!quiet)setMsg(ERR.pin,'er');
 }catch(e){if(!quiet)setMsg(NETERR,'er')}
 return false;
}
T('tgo').onclick=async()=>{const p=T('tpin').value.trim();if(!p){setMsg('أدخل رقم المعلم.','er');return}const ok=await teacherLogin(p);if(ok)T('tpin').value=''};
T('mset').onclick=()=>{const n=T('mpin').value.trim();if(!/^\d{4,8}$/.test(n)){setMsg(ERR.badpin,'er');return}call({act:'setpin',pin:TP,which:'master',newpin:n},'تم تغيير رقم المعلم.',async()=>{TP=n;ssSet('hb7tp',n);T('mpin').value=''})};

applyRole();
const lastTab=lsGet('hb7tab');
drawProg();drawRec();
if(location.hash==='#rec'||lastTab==='rec')show('rec');else if(lastTab==='les'||lastTab==='board')show(lastTab);
(async()=>{if(TP&&!DEMO)await teacherLogin(TP,true);await refresh(true)})();
</script>
</body>
</html>
