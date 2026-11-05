<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="theme-color" content="#C2185B">
<title>استوديو فلاتر | تصميم فلاتر سناب</title>
<link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;500;700;800&display=swap" rel="stylesheet">

<style>
:root {
  --bg:#FBF6F9;
  --surface:#FFFFFF;
  --text:#2A1530;
  --muted:#6B5870;
  --line:#EADCE5;
  --accent:#C2185B;
  --shadow:0 12px 32px rgba(42,21,48,.09);
}
[data-theme="dark"] {
  --bg:#1A0E1F;
  --surface:#26152E;
  --text:#F8EAF2;
  --muted:#BFA6C3;
  --line:#3B2545;
  --accent:#FF7FB1;
  --shadow:0 12px 32px rgba(0,0,0,.3);
}
* {box-sizing:border-box}
html {scroll-behavior:smooth;scroll-padding-top:90px}
body {
  margin:0;
  padding:0 16px;
  background:var(--bg);
  color:var(--text);
  font-family:'Tajawal',sans-serif;
  line-height:1.8;
  transition:.3s;
}
a {color:inherit;text-decoration:none}
button,input,select,textarea {font:inherit}
button {cursor:pointer}
.wrap {max-width:1120px;margin:auto}
header {
  position:sticky;top:10px;z-index:20;
  display:flex;align-items:center;justify-content:space-between;
  gap:12px;padding:12px 18px;margin-top:10px;
  border:1px solid var(--line);border-radius:50px;
  background:var(--surface);box-shadow:var(--shadow);
}
.brand {font-size:22px;font-weight:800;color:var(--accent)}
nav {display:flex;gap:20px}
nav a {color:var(--muted)}
nav a:hover {color:var(--accent)}
.tools {display:flex;gap:8px;align-items:center}
.btn {
  display:inline-flex;justify-content:center;align-items:center;
  padding:11px 22px;border:0;border-radius:50px;
  background:var(--accent);color:white;font-weight:700;
  transition:.2s;
}
.btn:hover {transform:translateY(-2px);opacity:.9}
.ghost {background:transparent;color:var(--text);border:1px solid var(--line)}
.theme {
  width:40px;height:40px;border-radius:50%;
  border:1px solid var(--line);background:var(--surface);
  color:var(--text);
}
.hero {
  display:grid;grid-template-columns:1.1fr .9fr;
  gap:50px;align-items:center;padding:70px 0;
}
.eyebrow {
  display:inline-block;padding:6px 15px;border-radius:30px;
  color:var(--accent);background:var(--surface);
  border:1px solid var(--line);font-weight:700;
}
h1 {font-size:clamp(35px,5vw,60px);line-height:1.3;margin:15px 0}
h1 em {color:var(--accent);font-style:normal}
.lead {font-size:18px;color:var(--muted)}
.cta {display:flex;gap:12px;flex-wrap:wrap;margin-top:25px}
.try {
  margin-top:25px;padding:15px;border-radius:18px;
  background:var(--surface);border:1px solid var(--line);
}
.try input {
  width:100%;padding:12px;margin-top:8px;
  border:1px solid var(--line);border-radius:12px;
  background:var(--bg);color:var(--text);
}
.stage {display:flex;flex-direction:column;align-items:center;gap:18px}
.phone {
  width:min(290px,100%);aspect-ratio:9/17;
  background:#17101d;border:7px solid #17101d;
  border-radius:42px;position:relative;overflow:hidden;
  box-shadow:var(--shadow);
}
.screen {
  position:absolute;inset:0;overflow:hidden;
  border-radius:34px;
  background:linear-gradient(150deg,#F9A8D4,#8B5CF6);
}
.person {
  position:absolute;bottom:-5%;left:50%;transform:translateX(-50%);
  width:75%;height:55%;border-radius:50% 50% 0 0;
  background:#29304f;
}
.person:before {
  content:"";position:absolute;top:-40px;left:50%;
  transform:translateX(-50%);width:100px;height:100px;
  border-radius:50%;background:#E9C8A8;
}
.overlay {
  position:absolute;inset:0;display:none;color:white;
  text-align:center;text-shadow:0 2px 8px #0008;
}
.overlay.active {display:block}
.overlay h2 {font-size:27px;margin-top:50px}
.overlay p {font-size:19px}
.frame {
  position:absolute;inset:12px;border:2px solid white;
  border-radius:25px;
}
.snapbar {
  position:absolute;bottom:15px;left:50%;
  transform:translateX(-50%);
  width:52px;height:52px;border:4px solid white;
  border-radius:50%;
}
.chips {display:flex;gap:7px;flex-wrap:wrap;justify-content:center}
.chip {
  padding:8px 16px;border:1px solid var(--line);
  border-radius:30px;background:var(--surface);
  color:var(--text);
}
.chip.active {background:var(--accent);color:white;border-color:var(--accent)}
.note {color:var(--muted);font-size:13px}
.trust {
  display:grid;grid-template-columns:repeat(4,1fr);
  background:var(--surface);border:1px solid var(--line);
  border-radius:22px;box-shadow:var(--shadow);overflow:hidden;
}
.trust div {padding:20px;text-align:center;border-left:1px solid var(--line)}
.trust b {display:block;color:var(--accent);font-size:26px}
.trust span {color:var(--muted)}
section {padding:65px 0}
.head {margin-bottom:30px}
.head h2 {font-size:32px;margin:5px 0}
.head p {color:var(--muted)}
.kicker {color:var(--accent);font-weight:700}
.grid {
  display:grid;grid-template-columns:repeat(3,1fr);gap:18px;
}
.card {
  background:var(--surface);border:1px solid var(--line);
  border-radius:24px;padding:25px;box-shadow:var(--shadow);
  transition:.2s;
}
.card:hover {transform:translateY(-5px)}
.ico {
  width:52px;height:52px;border-radius:16px;
  display:grid;place-items:center;background:#FCE4EF;
  font-size:25px;margin-bottom:12px;
}
.card h3 {font-size:21px}
.card p,.card li {color:var(--muted)}
.card ul {padding-right:20px}
.card .go {
  border:0;background:none;color:var(--accent);
  font-weight:800;padding:5px 0;
}
.gtabs {display:flex;gap:8px;flex-wrap:wrap;margin-bottom:25px}
.gallery {
  display:grid;grid-template-columns:repeat(4,1fr);gap:18px;
}
.design {min-width:0}
.preview {
  aspect-ratio:9/16;border-radius:22px;
  display:flex;flex-direction:column;align-items:center;
  justify-content:space-around;color:white;text-align:center;
  padding:15px;box-shadow:var(--shadow);
  overflow:hidden;
}
.preview strong {font-size:25px}
.preview small {font-size:14px}
.design h3 {font-size:17px}
.design button {
  border:0;background:none;color:var(--accent);
  font-weight:700;padding:5px 0;
}
.steps {
  display:grid;grid-template-columns:repeat(4,1fr);gap:15px;
}
.step {
  background:var(--surface);border:1px solid var(--line);
  border-radius:20px;padding:22px;box-shadow:var(--shadow);
}
.step b {color:var(--accent);display:block;font-size:19px}
.step p {color:var(--muted)}
.order {
  display:grid;grid-template-columns:1fr 1fr;gap:30px;
  padding:30px;background:var(--surface);
  border:1px solid var(--line);border-radius:28px;
  box-shadow:var(--shadow);
}
form {display:flex;flex-direction:column;gap:13px}
.field {display:flex;flex-direction:column;gap:6px}
.field label {font-weight:700}
.field input,.field select,.field textarea {
  width:100%;padding:13px;border-radius:12px;
  border:1px solid var(--line);background:var(--bg);
  color:var(--text);
}
.field textarea {min-height:100px;resize:vertical}
.output {
  padding:20px;border-radius:20px;
  background:var(--bg);border:1px dashed var(--line);
}
#message {white-space:pre-wrap;overflow-wrap:anywhere}
.actions {display:flex;gap:10px;flex-wrap:wrap;margin-top:15px}
footer {
  display:flex;justify-content:space-between;flex-wrap:wrap;
  gap:10px;padding:30px 0 90px;color:var(--muted);
  border-top:1px solid var(--line);
}
.fab {
  position:fixed;bottom:20px;left:20px;z-index:30;
  width:58px;height:58px;border-radius:50%;
  display:grid;place-items:center;background:#0F8A44;
  color:white;font-size:26px;box-shadow:var(--shadow);
}
@media(max-width:850px) {
  nav {display:none}
  .hero {grid-template-columns:1fr}
  .grid {grid-template-columns:repeat(2,1fr)}
  .gallery {grid-template-columns:repeat(3,1fr)}
  .steps {grid-template-columns:repeat(2,1fr)}
}
@media(max-width:600px) {
  .grid,.gallery {grid-template-columns:repeat(2,1fr);gap:12px}
  .order {grid-template-columns:1fr;padding:18px}
  .trust {grid-template-columns:repeat(2,1fr)}
  .trust div {border-bottom:1px solid var(--line)}
  .steps {grid-template-columns:1fr 1fr}
  section {padding:45px 0}
  .head h2 {font-size:26px}
  header {padding:10px}
  .tools .btn {display:none}
}
</style>
</head>

<body>
<div class="wrap">

<header>
  <a class="brand" href="#top">✧ استوديو فلاتر</a>
  <nav>
    <a href="#services">الخدمات</a>
    <a href="#gallery">التصاميم</a>
    <a href="#process">طريقة العمل</a>
    <a href="#order">اطلب فلترك</a>
  </nav>
  <div class="tools">
    <button class="theme" id="theme">◐</button>
    <a class="btn" href="#order">اطلب الآن</a>
  </div>
</header>

<main id="top">

<div class="hero">
  <div>
    <span class="eyebrow">استوديو تصميم فلاتر سناب</span>
    <h1>فلتر سناب يحمل <em>اسمك</em> ومناسبتك</h1>
    <p class="lead">
      نصمم فلاتر سناب لحفلات الزفاف والتخرج وأعياد الميلاد
      والمناسبات الخاصة والحملات التجارية.
    </p>
    <div class="cta">
      <a class="btn" href="#order">ابدأ تصميم فلترك</a>
      <a class="btn ghost" href="#gallery">شاهد التصاميم</a>
    </div>
    <div class="try">
      <label for="nameIn">جرّب بنفسك: اكتب اسماً وشاهد المعاينة</label>
      <input id="nameIn" value="سارة" maxlength="18">
    </div>
  </div>

  <div class="stage">
    <div class="phone">
      <div class="screen">
        <div class="person"></div>
        <div class="overlay active" data-type="wedding">
          <div class="frame"></div>
          <h2>حفل زفاف</h2>
          <p><span class="name">سارة</span> & خالد</p>
          <p>١٤ · ١٢ · ٢٠٢٦</p>
        </div>
        <div class="overlay" data-type="grad">
          <div class="frame"></div>
          <h2>مبروك التخرج</h2>
          <p class="name">سارة</p>
          <p>دفعة ٢٠٢٦</p>
        </div>
        <div class="overlay" data-type="bday">
          <div class="frame"></div>
          <h2>🎈 عيد ميلاد 🎈</h2>
          <p class="name">سارة</p>
          <p>يوم مميز</p>
        </div>
        <div class="overlay" data-type="special">
          <div class="frame"></div>
          <h2>ذكرى لا تنسى</h2>
          <p class="name">سارة</p>
          <p>مناسبة خاصة</p>
        </div>
        <div class="overlay" data-type="ads">
          <div class="frame"></div>
          <h2>عرض خاص</h2>
          <p>خصم ٢٠٪</p>
          <p>اليوم فقط</p>
        </div>
        <div class="overlay" data-type="name">
          <div class="frame"></div>
          <h2 class="name">سارة</h2>
          <p>تصميم خاص باسمك</p>
        </div>
        <div class="snapbar"></div>
      </div>
    </div>
    <div class="chips">
      <button class="chip active" data-show="wedding">زفاف</button>
      <button class="chip" data-show="grad">تخرج</button>
      <button class="chip" data-show="bday">ميلاد</button>
      <button class="chip" data-show="special">مناسبة</button>
      <button class="chip" data-show="ads">إعلان</button>
      <button class="chip" data-show="name">اسم</button>
    </div>
    <p class="note">معاينة توضيحية للتصميم النهائي.</p>
  </div>
</div>

<div class="trust">
  <div><b>٦</b><span>أنواع فلاتر</span></div>
  <div><b>١٢</b><span>نموذج تصميم</span></div>
  <div><b>مميز</b><span>تصميم حسب الطلب</span></div>
  <div><b>جاهز</b><span>ملف للتسليم</span></div>
</div>

<section id="services">
  <div class="head">
    <span class="kicker">الخدمات</span>
    <h2>فلاتر لكل مناسبة</h2>
    <p>اختر نوع الفلتر الذي يناسب مناسبتك.</p>
  </div>

  <div class="grid">
    <article class="card">
      <div class="ico">💍</div>
      <h3>فلاتر الأعراس والخطوبة</h3>
      <p>تصاميم أنيقة بأسماء العروسين وتاريخ الحفل.</p>
      <ul><li>أسماء العروسين</li><li>ألوان الحفل</li><li>زخارف وورود</li></ul>
      <button class="go" data-pick="wedding">اطلب هذا الفلتر ←</button>
    </article>

    <article class="card">
      <div class="ico">🎓</div>
      <h3>فلاتر التخرج والنجاح</h3>
      <p>احتفل بإنجازك بتصميم يحمل اسمك وتخصصك.</p>
      <ul><li>اسم الخريج</li><li>سنة التخرج</li><li>شعار الجامعة</li></ul>
      <button class="go" data-pick="grad">اطلب هذا الفلتر ←</button>
    </article>

    <article class="card">
      <div class="ico">🎂</div>
      <h3>فلاتر أعياد الميلاد</h3>
      <p>ألوان مرحة وتصاميم جميلة لعيد ميلادك.</p>
      <ul><li>العمر والاسم</li><li>بالونات</li><li>ألوان مميزة</li></ul>
      <button class="go" data-pick="bday">اطلب هذا الفلتر ←</button>
    </article>

    <article class="card">
      <div class="ico">❤️</div>
      <h3>المناسبات الخاصة</h3>
      <p>تصاميم للمولود الجديد والذكريات والأعياد.</p>
      <ul><li>مولود جديد</li><li>ذكرى سنوية</li><li>مناسبات موسمية</li></ul>
      <button class="go" data-pick="special">اطلب هذا الفلتر ←</button>
    </article>

    <article class="card">
      <div class="ico">🏷️</div>
      <h3>فلاتر إعلانية وتجارية</h3>
      <p>فلتر يحمل شعار متجرك وعروضك التجارية.</p>
      <ul><li>شعار المتجر</li><li>عروض وخصومات</li><li>افتتاحات ومعارض</li></ul>
      <button class="go" data-pick="ads">اطلب هذا الفلتر ←</button>
    </article>

    <article class="card">
      <div class="ico">✨</div>
      <h3>تصاميم خاصة</h3>
      <p>نصمم لك فلتر من فكرتك الخاصة.</p>
      <ul><li>اسمك وتوقيعك</li><li>ألوانك المفضلة</li><li>تصميم من الصفر</li></ul>
      <button class="go" data-pick="name">اطلب هذا الفلتر ←</button>
    </article>
  </div>
</section>

<section id="gallery">
  <div class="head">
    <span class="kicker">معرض التصاميم</span>
    <h2>نماذج من أعمالنا</h2>
    <p>اختر تصميماً يعجبك وسنخصصه حسب طلبك.</p>
  </div>

  <div class="gtabs" id="filters">
    <button class="chip active" data-filter="all">الكل</button>
    <button class="chip" data-filter="wedding">زفاف</button>
    <button class="chip" data-filter="grad">تخرج</button>
    <button class="chip" data-filter="bday">ميلاد</button>
    <button class="chip" data-filter="special">مناسبات</button>
    <button class="chip" data-filter="ads">إعلانات</button>
    <button class="chip" data-filter="name">أسماء</button>
  </div>

  <div class="gallery" id="galleryList">
    <div class="design" data-category="wedding">
      <div class="preview" style="background:linear-gradient(160deg,#59452e,#c9a56a)">
        <small>حفل زفاف</small><strong>سارة & خالد</strong><small>ذهب وورد</small>
      </div>
      <h3>ذهب وورد</h3>
      <button data-design="wedding">اطلب هذا التصميم ←</button>
    </div>

    <div class="design" data-category="wedding">
      <div class="preview" style="background:linear-gradient(160deg,#7d8bb3,#cdbbe0)">
        <small>خطوبة</small><strong>ليان & عمر</strong><small>أبيض ناعم</small>
      </div>
      <h3>أبيض ناعم</h3>
      <button data-design="wedding">اطلب هذا التصميم ←</button>
    </div>

    <div class="design" data-category="grad">
      <div class="preview" style="background:linear-gradient(160deg,#1b2a5c,#3b5bd6)">
        <small>مبروك التخرج</small><strong>أحمد</strong><small>دفعة ٢٠٢٦</small>
      </div>
      <h3>ذهبي وكحلي</h3>
      <button data-design="grad">اطلب هذا التصميم ←</button>
    </div>

    <div class="design" data-category="grad">
      <div class="preview" style="background:linear-gradient(160deg,#0b4f3d,#14916f)">
        <small>٢٠٢٦</small><strong>خريج وفخور</strong><small>كلية الهندسة</small>
      </div>
      <h3>دفعة السنة</h3>
      <button data-design="grad">اطلب هذا التصميم ←</button>
    </div>

    <div class="design" data-category="bday">
      <div class="preview" style="background:linear-gradient(160deg,#f08a24,#f2305a)">
        <small>🎈 حفلة 🎈</small><strong>عيد ميلاد سعيد</strong><small>بالونات</small>
      </div>
      <h3>بالونات</h3>
      <button data-design="bday">اطلب هذا التصميم ←</button>
    </div>

    <div class="design" data-category="bday">
      <div class="preview" style="background:linear-gradient(160deg,#1a1040,#5b2bd6)">
        <small>ليلة الحفلة</small><strong>عيد ميلاد ريم</strong><small>٢٥ مارس</small>
      </div>
      <h3>ليلة الحفلة</h3>
      <button data-design="bday">اطلب هذا التصميم ←</button>
    </div>

    <div class="design" data-category="special">
      <div class="preview" style="background:linear-gradient(160deg,#9ec9f0,#f6c6d8)">
        <small>مرحباً بك</small><strong>مولودنا الجديد</strong><small>مناسبة سعيدة</small>
      </div>
      <h3>مولود جديد</h3>
      <button data-design="special">اطلب هذا التصميم ←</button>
    </div>

    <div class="design" data-category="special">
      <div class="preview" style="background:linear-gradient(160deg,#0b3d2e,#14916f)">
        <small>🌙 ✨</small><strong>رمضان كريم</strong><small>كل عام وأنتم بخير</small>
      </div>
      <h3>رمضان كريم</h3>
      <button data-design="special">اطلب هذا التصميم ←</button>
    </div>

    <div class="design" data-category="ads">
      <div class="preview" style="background:linear-gradient(160deg,#12162b,#2f6bff)">
        <small>اسم علامتك</small><strong>افتتاح فرع</strong><small>ننتظركم</small>
      </div>
      <h3>افتتاح فرع</h3>
      <button data-design="ads">اطلب هذا التصميم ←</button>
    </div>

    <div class="design" data-category="ads">
      <div class="preview" style="background:linear-gradient(160deg,#f2305a,#7a4fe0)">
        <small>عرض خاص</small><strong>٣٠٪</strong><small>لفترة محدودة</small>
      </div>
      <h3>عرض خاص</h3>
      <button data-design="ads">اطلب هذا التصميم ←</button>
    </div>

    <div class="design" data-category="name">
      <div class="preview" style="background:linear-gradient(160deg,#7a4fe0,#2f6bff)">
        <small>تصميم خاص</small><strong>ملاك</strong><small>اسمك بأسلوبك</small>
      </div>
      <h3>اسم بخط كبير</h3>
      <button data-design="name">اطلب هذا التصميم ←</button>
    </div>

    <div class="design" data-category="name">
      <div class="preview" style="background:linear-gradient(160deg,#12162b,#7a4fe0)">
        <small>ضيف الشرف</small><strong>أبو سلطان</strong><small>لقب وشعار</small>
      </div>
      <h3>لقب وشعار</h3>
      <button data-design="name">اطلب هذا التصميم ←</button>
    </div>
  </div>
</section>

<section id="process">
  <div class="head">
    <span class="kicker">طريقة العمل</span>
    <h2>من فكرتك إلى فلتر جاهز</h2>
  </div>
  <div class="steps">
    <div class="step"><b>01 - فكرتك</b><p>أرسل لنا نوع المناسبة والأسماء والألوان.</p></div>
    <div class="step"><b>02 - التصميم</b><p>نجهّز لك مسودة التصميم لمراجعتها.</p></div>
    <div class="step"><b>03 - التعديلات</b><p>ننفّذ الملاحظات المطلوبة على التصميم.</p></div>
    <div class="step"><b>04 - التسليم</b><p>تستلم الملف النهائي مع شرح الخطوات.</p></div>
  </div>
</section>

<section id="order">
  <div class="head">
    <span class="kicker">اطلب فلترك</span>
    <h2>أرسل تفاصيل طلبك</h2>
    <p>املأ البيانات وستُجهّز لك رسالة واتساب تلقائياً.</p>
  </div>

  <div class="order">
    <form id="orderForm">
      <div class="field">
        <label for="type">نوع الفلتر</label>
        <select id="type">
          <option value="wedding">فلتر زفاف أو خطوبة</option>
          <option value="grad">فلتر تخرج أو نجاح</option>
          <option value="bday">فلتر عيد ميلاد</option>
          <option value="special">فلتر مناسبة خاصة</option>
          <option value="ads">فلتر إعلاني أو تجاري</option>
          <option value="name">فلتر باسم أو تصميم خاص</option>
        </select>
      </div>

      <div class="field">
        <label for="who">الاسم على الفلتر</label>
        <input id="who" placeholder="مثال: سارة وخالد">
      </div>

      <div class="field">
        <label for="date">تاريخ المناسبة</label>
        <input id="date" placeholder="مثال: ١٤ ديسمبر ٢٠٢٦">
      </div>

      <div class="field">
        <label for="colors">الألوان المفضلة</label>
        <input id="colors" placeholder="مثال: ذهبي وأبيض">
      </div>

      <div class="field">
        <label for="notes">ملاحظات إضافية</label>
        <textarea id="notes" placeholder="اكتب تفاصيل التصميم الذي تريده..."></textarea>
      </div>

      <div class="field">
        <label for="customer">اسمك</label>
        <input id="customer" placeholder="اسمك الكريم">
      </div>

      <div class="field">
        <label for="phone">رقم هاتفك</label>
        <input id="phone" type="tel" placeholder="09XXXXXXXX" dir="ltr">
      </div>
    </form>

    <div class="output">
      <h3>معاينة رسالة الطلب</h3>
      <pre id="message"></pre>
      <div class="actions">
        <a class="btn" id="whatsapp" href="#" target="_blank" rel="noopener">إرسال عبر واتساب</a>
        <button class="btn ghost" id="copy" type="button">نسخ الرسالة</button>
      </div>
      <p id="status" class="note"></p>
    </div>
  </div>
</section>

</main>

<footer>
  <span>استوديو فلاتر · تصميم فلاتر سناب حسب الطلب</span>
  <span>تصميم مميز لكل مناسبة ✨</span>
</footer>

<a class="fab" href="https://wa.me/218930684125" target="_blank" rel="noopener" aria-label="واتساب">✆</a>

</div>

<script>
// غيّر الرقم إلى رقم واتساب الخاص بك بصيغة دولية دون +
const WA_NUMBER = "218930684125";

const $ = selector => document.querySelector(selector);
const $$ = selector => [...document.querySelectorAll(selector)];

// الوضع الليلي
$("#theme").addEventListener("click", () => {
  const dark = document.documentElement.getAttribute("data-theme") === "dark";
  document.documentElement.setAttribute("data-theme", dark ? "light" : "dark");
});

// معاينة الفلاتر
function showFilter(type) {
  $$(".overlay").forEach(item => {
    item.classList.toggle("active", item.dataset.type === type);
  });

  $$(".chips .chip").forEach(button => {
    button.classList.toggle("active", button.dataset.show === type);
  });
}

$$("[data-show]").forEach(button => {
  button.addEventListener("click", () => showFilter(button.dataset.show));
});

// تغيير الاسم في المعاينة
$("#nameIn").addEventListener("input", event => {
  const name = event.target.value.trim() || "اسمك";
  $$(".name").forEach(element => element.textContent = name);
});

// تصفية معرض التصاميم
$$("[data-filter]").forEach(button => {
  button.addEventListener("click", () => {
    const category = button.dataset.filter;

    $$(".gtabs .chip").forEach(item => {
      item.classList.toggle("active", item === button);
    });

    $$(".design").forEach(item => {
      item.style.display =
        category === "all" || item.dataset.category === category
          ? ""
          : "none";
    });
  });
});

// اختيار تصميم أو خدمة
function chooseType(type) {
  $("#type").value = type;
  document.querySelector("#order").scrollIntoView({behavior:"smooth"});
  updateMessage();
}

$$("[data-pick]").forEach(button => {
  button.addEventListener("click", () => chooseType(button.dataset.pick));
});

$$("[data-design]").forEach(button => {
  button.addEventListener("click", () => chooseType(button.dataset.design));
});

// بناء رسالة الطلب تلقائياً
function updateMessage() {
  const type = $("#type").selectedOptions[0].textContent;
  const who = $("#who").value.trim();
  const date = $("#date").value.trim();
  const colors = $("#colors").value.trim();
  const notes = $("#notes").value.trim();
  const customer = $("#customer").value.trim();
  const phone = $("#phone").value.trim();

  let lines = [
    "السلام عليكم ورحمة الله وبركاته 🌟",
    "أرغب في طلب تصميم فلتر سناب.",
    "",
    "📌 نوع الفلتر: " + type
  ];

  if (who) lines.push("✍️ الاسم على الفلتر: " + who);
  if (date) lines.push("📅 تاريخ المناسبة: " + date);
  if (colors) lines.push("🎨 الألوان: " + colors);
  if (notes) lines.push("📝 ملاحظات: " + notes);
  if (customer) lines.push("👤 الاسم: " + customer);
  if (phone) lines.push("📞 رقم الهاتف: " + phone);

  lines.push("", "أرجو إفادتي بالسعر ومدة التنفيذ. شكراً لكم 🙏");

  const message = lines.join("\n");
  $("#message").textContent = message;

  $("#whatsapp").href =
    "https://wa.me/" + WA_NUMBER + "?text=" + encodeURIComponent(message);
}

$("#orderForm").addEventListener("input", updateMessage);
$("#orderForm").addEventListener("change", updateMessage);
$("#copy").addEventListener("click", async () => {
  try {
    await navigator.clipboard.writeText($("#message").textContent);
    $("#status").textContent = "تم نسخ الرسالة بنجاح ✓";
  } catch {
    $("#status").textContent = "يمكنك تحديد الرسالة ونسخها يدوياً.";
  }
});

updateMessage();
</script>

</body>
</html>
