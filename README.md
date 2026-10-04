cd ~
cat > create-mitidja-metal.sh <<'EOF'
#!/data/data/com.termux/files/usr/bin/bash

set -e

PROJECT="$HOME/MITIDJA-METAL-DIAB"

echo "======================================"
echo "🏭 MITIDJA METAL DIAB"
echo "🚀 إنشاء الموقع التجاري الصناعي"
echo "======================================"

rm -rf "$PROJECT"
mkdir -p "$PROJECT"

cd "$PROJECT"

cat > index.html <<'HTML'
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>MITIDJA METAL DIAB | متيجة ميتال دياب</title>

  <meta
    name="description"
    content="متيجة ميتال دياب - تصنيع المنتجات المعدنية ومفصلات التلحيم بجودة صناعية."
  >

  <link rel="stylesheet" href="style.css">
</head>

<body>

<!-- ================= TOP BAR ================= -->

<div class="topbar">

  <div>
    📞 0553 33 55 92
    <span>/</span>
    0699 40 29 15
    <span>/</span>
    0562 18 55 06
  </div>

  <div>
    ✉️ mitidjametal@yahoo.fr
  </div>

</div>


<!-- ================= HEADER ================= -->

<header class="header">

  <div class="logo-area">

    <div class="logo-circle">
      <span>MM</span>
    </div>

    <div class="brand">

      <strong>MITIDJA METAL DIAB</strong>

      <small>
        متيجة ميتال دياب
      </small>

    </div>

  </div>


  <nav>

    <a class="active" href="#home">
      الرئيسية
    </a>

    <a href="#about">
      من نحن
    </a>

    <a href="#products">
      منتجاتنا
    </a>

    <a href="#quality">
      الجودة
    </a>

    <a href="#catalog">
      الكتالوج
    </a>

    <a href="#contact">
      اتصل بنا
    </a>

  </nav>


  <a class="quote-btn" href="#contact">
    طلب عرض سعر
  </a>

</header>


<!-- ================= HERO ================= -->

<section id="home" class="hero">

  <div class="hero-overlay"></div>

  <div class="hero-content">

    <div class="hero-text">

      <div class="gold-label">
        🏭 صناعة معدنية جزائرية
      </div>

      <h1>
        MITIDJA
        <span>METAL DIAB</span>
      </h1>

      <h2>
        متيجة ميتال دياب
      </h2>

      <p>
        الجودة والدقة والثقة أساس نجاحنا.
        نختص في تصنيع المنتجات المعدنية
        ومفصلات التلحيم بمواصفات صناعية
        متعددة لتلبية احتياجات السوق.
      </p>

      <div class="hero-buttons">

        <a class="gold-btn" href="#products">
          🔩 اكتشف منتجاتنا
        </a>

        <a class="outline-btn" href="#contact">
          📋 اطلب عرض سعر
        </a>

      </div>

    </div>


    <div class="hero-logo">

      <div class="big-logo">

        <div class="big-mm">
          M
        </div>

        <div class="big-brand">
          MITIDJA METAL
        </div>

        <div class="big-diab">
          DIAB
        </div>

      </div>

    </div>


    <div class="manager-card">

      <div class="manager-avatar">
        👔
      </div>

      <div>
        <small>
          مدير المؤسسة
        </small>

        <strong>
          دياب
        </strong>
      </div>

    </div>

  </div>

</section>


<!-- ================= FEATURES ================= -->

<section class="features">

  <div class="feature">

    <div class="feature-icon">
      🛡️
    </div>

    <div>
      <strong>جودة عالية</strong>
      <span>منتجات مصنعة بعناية</span>
    </div>

  </div>


  <div class="feature">

    <div class="feature-icon">
      ⚙️
    </div>

    <div>
      <strong>تصنيع احترافي</strong>
      <span>دقة في التصنيع</span>
    </div>

  </div>


  <div class="feature">

    <div class="feature-icon">
      🤝
    </div>

    <div>
      <strong>ثقة وموثوقية</strong>
      <span>شراكة طويلة المدى</span>
    </div>

  </div>


  <div class="feature">

    <div class="feature-icon">
      🚚
    </div>

    <div>
      <strong>توصيل سريع</strong>
      <span>خدمة مرنة وسريعة</span>
    </div>

  </div>


  <div class="feature">

    <div class="feature-icon">
      🎧
    </div>

    <div>
      <strong>خدمة العملاء</strong>
      <span>نحن في خدمتكم</span>
    </div>

  </div>

</section>


<!-- ================= ABOUT ================= -->

<section id="about" class="section about">

  <div class="section-title">

    <span>من نحن</span>

    <h2>
      متيجة ميتال دياب
    </h2>

    <p>
      شريككم في المنتجات المعدنية الصناعية
    </p>

  </div>


  <div class="about-grid">

    <div class="about-card">

      <div class="about-number">
        01
      </div>

      <h3>
        خبرة صناعية
      </h3>

      <p>
        نعمل على تطوير منتجات معدنية
        تلائم متطلبات الحرفيين والمهنيين
        والسوق الصناعي.
      </p>

    </div>


    <div class="about-card">

      <div class="about-number">
        02
      </div>

      <h3>
        دقة في التصنيع
      </h3>

      <p>
        نهتم بالمقاسات والمواد والتشطيب
        للحصول على منتج عملي وموثوق.
      </p>

    </div>


    <div class="about-card">

      <div class="about-number">
        03
      </div>

      <h3>
        خدمة تجارية
      </h3>

      <p>
        نوفر حلولاً واضحة للزبائن
        مع إمكانية طلب الأسعار والمنتجات
        والتواصل المباشر.
      </p>

    </div>

  </div>

</section>


<!-- ================= PRODUCTS ================= -->

<section id="products" class="section products">

  <div class="section-title">

    <span>منتجاتنا</span>

    <h2>
      مفصلات التلحيم
      <b>(PAUMELLES)</b>
    </h2>

    <p>
      مجموعة متنوعة من المقاسات والمواصفات
    </p>

  </div>


  <div class="products-grid">


    <article class="product-card">

      <div class="product-image">
        🔩
      </div>

      <div class="product-info">

        <small>
          PAUMELLES
        </small>

        <h3>
          PAUMELLES 60
        </h3>

        <p>
          AXE 06 · 1.5MM
        </p>

        <div class="product-bottom">

          <strong>
            22.00
          </strong>

          <span>
            DA
          </span>

        </div>

      </div>

    </article>


    <article class="product-card">

      <div class="product-image">
        🔩
      </div>

      <div class="product-info">

        <small>
          PAUMELLES
        </small>

        <h3>
          PAUMELLES 80
        </h3>

        <p>
          AXE 08 · 03MM
        </p>

        <div class="product-bottom">

          <strong>
            51.00
          </strong>

          <span>
            DA
          </span>

        </div>

      </div>

    </article>


    <article class="product-card">

      <div class="product-image">
        🔩
      </div>

      <div class="product-info">

        <small>
          PAUMELLES
        </small>

        <h3>
          PAUMELLES 100
        </h3>

        <p>
          AXE 08 · 03MM
        </p>

        <div class="product-bottom">

          <strong>
            63.00
          </strong>

          <span>
            DA
          </span>

        </div>

      </div>

    </article>


    <article class="product-card">

      <div class="product-image">
        🔩
      </div>

      <div class="product-info">

        <small>
          PAUMELLES
        </small>

        <h3>
          PAUMELLES 120
        </h3>

        <p>
          AXE 12 · 04MM
        </p>

        <div class="product-bottom">

          <strong>
            126.00
          </strong>

          <span>
            DA
          </span>

        </div>

      </div>

    </article>


    <article class="product-card">

      <div class="product-image">
        🔩
      </div>

      <div class="product-info">

        <small>
          PAUMELLES
        </small>

        <h3>
          PAUMELLES 140
        </h3>

        <p>
          AXE 16 · 04MM
        </p>

        <div class="product-bottom">

          <strong>
            197.50
          </strong>

          <span>
            DA
          </span>

        </div>

      </div>

    </article>


    <article class="product-card">

      <div class="product-image">
        🔩
      </div>

      <div class="product-info">

        <small>
          PAUMELLES
        </small>

        <h3>
          PAUMELLES 160
        </h3>

        <p>
          AXE 19 · 05MM
        </p>

        <div class="product-bottom">

          <strong>
            285.00
          </strong>

          <span>
            DA
          </span>

        </div>

      </div>

    </article>


  </div>


  <div class="center">

    <a class="gold-btn" href="#catalog">
      📋 مشاهدة الكتالوج الكامل
    </a>

  </div>

</section>


<!-- ================= QUALITY ================= -->

<section id="quality" class="quality">

  <div class="quality-content">

    <span>
      MITIDJA METAL DIAB
    </span>

    <h2>
      الجودة تبدأ من التفاصيل
    </h2>

    <p>
      نركز على الجودة، الدقة، والاستمرارية
      في كل منتج يخرج من المؤسسة.
    </p>

    <a class="gold-btn" href="#contact">
      تواصل معنا
    </a>

  </div>

</section>


<!-- ================= STATS ================= -->

<section class="stats">

  <div>
    <strong>15+</strong>
    <span>سنة خبرة</span>
  </div>

  <div>
    <strong>500+</strong>
    <span>عميل</span>
  </div>

  <div>
    <strong>1000+</strong>
    <span>منتج مصنع</span>
  </div>

  <div>
    <strong>100%</strong>
    <span>اهتمام بالجودة</span>
  </div>

</section>


<!-- ================= CATALOG ================= -->

<section id="catalog" class="section catalog">

  <div class="section-title">

    <span>الكتالوج</span>

    <h2>
      أسعار ومواصفات المنتجات
    </h2>

    <p>
      يمكنكم طلب الكتالوج التجاري الكامل
    </p>

  </div>


  <div class="catalog-box">

    <div class="catalog-icon">
      📋
    </div>

    <div>

      <h3>
        Catalogue MITIDJA METAL DIAB
      </h3>

      <p>
        جميع المقاسات والمواصفات والأسعار
        الخاصة بمنتجاتنا.
      </p>

    </div>

    <a class="gold-btn" href="#contact">
      طلب الكتالوج
    </a>

  </div>

</section>


<!-- ================= CONTACT ================= -->

<section id="contact" class="section contact">

  <div class="section-title">

    <span>اتصل بنا</span>

    <h2>
      نحن في خدمتكم
    </h2>

    <p>
      تواصل معنا للحصول على الأسعار والطلبات
    </p>

  </div>


  <div class="contact-grid">


    <div class="contact-card">

      <div>
        📞
      </div>

      <h3>
        الهاتف
      </h3>

      <p>
        0553 33 55 92
      </p>

      <p>
        0699 40 29 15
      </p>

      <p>
        0562 18 55 06
      </p>

    </div>


    <div class="contact-card">

      <div>
        ✉️
      </div>

      <h3>
        البريد الإلكتروني
      </h3>

      <p>
        mitidjametal@yahoo.fr
      </p>

    </div>


    <div class="contact-card">

      <div>
        📍
      </div>

      <h3>
        الجزائر
      </h3>

      <p>
        متيجة ميتال دياب
      </p>

    </div>

  </div>


  <div class="whatsapp-box">

    <div>

      <strong>
        تريد طلب عرض سعر؟
      </strong>

      <span>
        تواصل معنا مباشرة
      </span>

    </div>

    <a href="https://wa.me/213553335592" target="_blank">
      💬 WhatsApp
    </a>

  </div>

</section>


<!-- ================= FOOTER ================= -->

<footer>

  <div class="footer-brand">

    <div class="logo-circle small">
      MM
    </div>

    <div>

      <strong>
        MITIDJA METAL DIAB
      </strong>

      <span>
        متيجة ميتال دياب
      </span>

    </div>

  </div>


  <p>
    © 2026 MITIDJA METAL DIAB — جميع الحقوق محفوظة
  </p>

</footer>


<script src="script.js"></script>

</body>
</html>
HTML


cat > style.css <<'CSS'
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

body {
  background: #080a0d;
  color: #f5f5f5;
  font-family: Arial, Tahoma, sans-serif;
  line-height: 1.7;
  overflow-x: hidden;
}

a {
  color: inherit;
  text-decoration: none;
}

:root {
  --black: #080a0d;
  --dark: #0e1116;
  --dark2: #151a20;
  --gold: #d5a52a;
  --gold2: #f0c75e;
  --silver: #cbd0d5;
  --muted: #9ca3af;
  --border: rgba(213,165,42,.28);
}


/* TOPBAR */

.topbar {
  min-height: 38px;
  background: #050608;
  border-bottom: 1px solid var(--border);
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 7px 5%;
  color: #ddd;
  font-size: 13px;
  gap: 20px;
}

.topbar span {
  color: var(--gold);
  margin: 0 6px;
}


/* HEADER */

.header {
  height: 84px;
  background: rgba(8,10,13,.96);
  border-bottom: 1px solid rgba(213,165,42,.3);
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 5%;
  position: sticky;
  top: 0;
  z-index: 1000;
  backdrop-filter: blur(12px);
}

.logo-area {
  display: flex;
  align-items: center;
  gap: 12px;
}

.logo-circle {
  width: 52px;
  height: 52px;
  border: 2px solid var(--gold);
  border-radius: 50%;
  display: grid;
  place-items: center;
  color: var(--gold);
  font-size: 19px;
  font-weight: 900;
  box-shadow: 0 0 25px rgba(213,165,42,.18);
}

.brand {
  display: flex;
  flex-direction: column;
}

.brand strong {
  color: #fff;
  font-size: 17px;
  letter-spacing: .5px;
}

.brand small {
  color: var(--gold2);
  font-size: 13px;
}

nav {
  display: flex;
  align-items: center;
  gap: 25px;
}

nav a {
  color: #d5d7da;
  font-size: 14px;
  transition: .25s;
}

nav a:hover,
nav a.active {
  color: var(--gold2);
}

.quote-btn,
.gold-btn {
  background: linear-gradient(135deg, #b88412, #edc14f);
  color: #080808;
  font-weight: 800;
  padding: 12px 22px;
  border-radius: 6px;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 8px;
  box-shadow: 0 8px 25px rgba(213,165,42,.18);
  transition: .25s;
}

.quote-btn:hover,
.gold-btn:hover {
  transform: translateY(-2px);
  box-shadow: 0 12px 30px rgba(213,165,42,.3);
}

.outline-btn {
  border: 1px solid var(--gold);
  color: #fff;
  padding: 11px 22px;
  border-radius: 6px;
  transition: .25s;
}

.outline-btn:hover {
  background: rgba(213,165,42,.1);
}


/* HERO */

.hero {
  min-height: 620px;
  position: relative;
  overflow: hidden;
  background:
    radial-gradient(circle at 68% 40%, rgba(213,165,42,.18), transparent 27%),
    linear-gradient(100deg, #080a0d 10%, rgba(8,10,13,.84) 45%, rgba(8,10,13,.35)),
    repeating-linear-gradient(
      110deg,
      #101419 0px,
      #101419 2px,
      #0b0d10 2px,
      #0b0d10 8px
    );
}

.hero::before {
  content: "";
  position: absolute;
  inset: 0;
  background:
    radial-gradient(circle at 25% 60%, rgba(213,165,42,.14), transparent 2%),
    radial-gradient(circle at 45% 35%, rgba(255,255,255,.08), transparent 1%);
  opacity: .9;
}

.hero-overlay {
  position: absolute;
  inset: 0;
  background: linear-gradient(
    90deg,
    rgba(0,0,0,.9),
    rgba(0,0,0,.5),
    rgba(0,0,0,.2)
  );
}

.hero-content {
  position: relative;
  z-index: 2;
  max-width: 1250px;
  min-height: 620px;
  margin: auto;
  padding: 75px 5%;
  display: grid;
  grid-template-columns: 1.05fr .95fr;
  align-items: center;
  gap: 30px;
}

.hero-text {
  max-width: 650px;
}

.gold-label {
  color: var(--gold2);
  font-size: 15px;
  margin-bottom: 14px;
}

.hero h1 {
  font-size: clamp(48px, 7vw, 84px);
  line-height: .95;
  letter-spacing: 2px;
  color: var(--gold2);
  text-shadow: 0 8px 35px rgba(0,0,0,.8);
}

.hero h1 span {
  display: block;
  color: #e5e7eb;
}

.hero h2 {
  margin-top: 16px;
  color: #fff;
  font-size: 28px;
}

.hero p {
  margin-top: 16px;
  color: #c5c8cd;
  font-size: 17px;
  max-width: 600px;
}

.hero-buttons {
  margin-top: 28px;
  display: flex;
  gap: 14px;
  flex-wrap: wrap;
}

.hero-logo {
  display: grid;
  place-items: center;
}

.big-logo {
  width: 380px;
  height: 380px;
  border-radius: 50%;
  border: 13px solid;
  border-color: var(--gold) #cdd2d7 var(--gold) #cdd2d7;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  background:
    radial-gradient(circle, #1d2025, #090b0e 70%);
  box-shadow:
    0 0 60px rgba(213,165,42,.12),
    inset 0 0 50px rgba(255,255,255,.04);
  transform: rotate(-7deg);
}

.big-mm {
  font-size: 145px;
  line-height: .8;
  font-weight: 900;
  background: linear-gradient(90deg, #d7a72b, #eee, #aeb4bb);
  -webkit-background-clip: text;
  color: transparent;
}

.big-brand {
  margin-top: 25px;
  font-size: 25px;
  font-weight: 900;
  color: #eee;
}

.big-diab {
  color: var(--gold2);
  font-weight: 900;
  font-size: 20px;
  letter-spacing: 5px;
}

.manager-card {
  position: absolute;
  bottom: 35px;
  right: 5%;
  background: rgba(10,12,15,.9);
  border: 1px solid var(--border);
  border-radius: 10px;
  padding: 14px 20px;
  display: flex;
  align-items: center;
  gap: 13px;
}

.manager-avatar {
  width: 48px;
  height: 48px;
  border-radius: 50%;
  display: grid;
  place-items: center;
  background: #171b21;
  border: 1px solid var(--gold);
  font-size: 24px;
}

.manager-card small,
.manager-card strong {
  display: block;
}

.manager-card small {
  color: var(--gold2);
}

.manager-card strong {
  color: #fff;
  font-size: 19px;
}


/* FEATURES */

.features {
  background: #0d1014;
  border-top: 1px solid var(--border);
  border-bottom: 1px solid var(--border);
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  padding: 0 5%;
}

.feature {
  min-height: 105px;
  display: flex;
  align-items: center;
  gap: 14px;
  padding: 20px;
  border-left: 1px solid rgba(255,255,255,.06);
}

.feature:last-child {
  border-left: 0;
}

.feature-icon {
  color: var(--gold2);
  font-size: 30px;
}

.feature strong,
.feature span {
  display: block;
}

.feature strong {
  color: #fff;
}

.feature span {
  color: var(--muted);
  font-size: 13px;
}


/* SECTIONS */

.section {
  padding: 95px 5%;
  max-width: 1400px;
  margin: auto;
}

.section-title {
  text-align: center;
  margin-bottom: 50px;
}

.section-title > span {
  color: var(--gold2);
  font-size: 14px;
  font-weight: 800;
}

.section-title h2 {
  font-size: clamp(28px, 4vw, 44px);
  color: #fff;
  margin-top: 8px;
}

.section-title h2 b {
  color: var(--gold2);
  font-weight: 500;
}

.section-title p {
  color: var(--muted);
  margin-top: 8px;
}


/* ABOUT */

.about {
  background: #0a0d11;
}

.about-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
}

.about-card {
  background: linear-gradient(145deg, #151a20, #0e1116);
  border: 1px solid rgba(213,165,42,.18);
  padding: 35px;
  border-radius: 12px;
  position: relative;
  overflow: hidden;
}

.about-number {
  position: absolute;
  top: 12px;
  left: 20px;
  color: rgba(213,165,42,.16);
  font-size: 65px;
  font-weight: 900;
}

.about-card h3 {
  color: var(--gold2);
  font-size: 22px;
  margin-bottom: 10px;
}

.about-card p {
  color: #aeb3ba;
}


/* PRODUCTS */

.products {
  max-width: 1500px;
}

.products-grid {
  display: grid;
  grid-template-columns: repeat(6, 1fr);
  gap: 16px;
}

.product-card {
  background: linear-gradient(145deg, #191d22, #0d1014);
  border: 1px solid rgba(213,165,42,.2);
  border-radius: 9px;
  overflow: hidden;
  transition: .3s;
}

.product-card:hover {
  transform: translateY(-8px);
  border-color: var(--gold);
  box-shadow: 0 20px 50px rgba(0,0,0,.35);
}

.product-image {
  height: 170px;
  display: grid;
  place-items: center;
  font-size: 72px;
  background:
    radial-gradient(circle, #353a40, #121519 65%);
  filter: grayscale(.25);
}

.product-info {
  padding: 18px;
}

.product-info small {
  color: var(--gold2);
  font-size: 11px;
}

.product-info h3 {
  color: #fff;
  font-size: 17px;
  margin-top: 3px;
}

.product-info p {
  color: #8f969f;
  font-size: 12px;
}

.product-bottom {
  margin-top: 12px;
  padding-top: 12px;
  border-top: 1px solid rgba(255,255,255,.08);
  display: flex;
  align-items: baseline;
  gap: 6px;
}

.product-bottom strong {
  color: var(--gold2);
  font-size: 22px;
}

.product-bottom span {
  color: #aaa;
  font-size: 12px;
}

.center {
  text-align: center;
  margin-top: 38px;
}


/* QUALITY */

.quality {
  min-height: 390px;
  display: grid;
  place-items: center;
  text-align: center;
  background:
    linear-gradient(rgba(5,7,9,.86), rgba(5,7,9,.94)),
    repeating-linear-gradient(
      120deg,
      #24292f,
      #24292f 2px,
      #11151a 2px,
      #11151a 10px
    );
  border-top: 1px solid var(--border);
  border-bottom: 1px solid var(--border);
}

.quality-content {
  max-width: 750px;
  padding: 50px 5%;
}

.quality-content > span {
  color: var(--gold2);
  font-weight: 900;
  letter-spacing: 3px;
}

.quality h2 {
  font-size: clamp(32px, 5vw, 58px);
  margin: 10px 0;
}

.quality p {
  color: #b6bbc1;
  font-size: 17px;
  margin-bottom: 25px;
}


/* STATS */

.stats {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  border-bottom: 1px solid var(--border);
  background: #0b0e12;
}

.stats div {
  padding: 38px;
  text-align: center;
  border-left: 1px solid rgba(255,255,255,.07);
}

.stats strong,
.stats span {
  display: block;
}

.stats strong {
  color: var(--gold2);
  font-size: 38px;
}

.stats span {
  color: #9ca3af;
}


/* CATALOG */

.catalog-box {
  max-width: 950px;
  margin: auto;
  padding: 30px;
  border: 1px solid var(--border);
  border-radius: 12px;
  background: linear-gradient(145deg, #171b20, #0c0f13);
  display: flex;
  align-items: center;
  gap: 25px;
}

.catalog-icon {
  font-size: 50px;
}

.catalog-box h3 {
  color: #fff;
}

.catalog-box p {
  color: var(--muted);
}

.catalog-box .gold-btn {
  margin-right: auto;
  white-space: nowrap;
}


/* CONTACT */

.contact {
  background: #0a0d11;
}

.contact-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
}

.contact-card {
  text-align: center;
  background: #11151a;
  border: 1px solid rgba(213,165,42,.16);
  border-radius: 10px;
  padding: 35px 20px;
}

.contact-card > div {
  font-size: 35px;
}

.contact-card h3 {
  color: var(--gold2);
  margin: 10px 0;
}

.contact-card p {
  color: #d0d4d8;
}

.whatsapp-box {
  max-width: 950px;
  margin: 35px auto 0;
  background: linear-gradient(135deg, #171b20, #0c0f13);
  border: 1px solid var(--border);
  border-radius: 10px;
  padding: 25px 30px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.whatsapp-box strong,
.whatsapp-box span {
  display: block;
}

.whatsapp-box strong {
  color: #fff;
  font-size: 20px;
}

.whatsapp-box span {
  color: var(--muted);
}

.whatsapp-box a {
  background: #16a34a;
  color: #fff;
  padding: 12px 25px;
  border-radius: 7px;
  font-weight: 800;
}


/* FOOTER */

footer {
  background: #050608;
  border-top: 1px solid var(--border);
  padding: 35px 5%;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 20px;
}

.footer-brand {
  display: flex;
  align-items: center;
  gap: 12px;
}

.logo-circle.small {
  width: 44px;
  height: 44px;
  font-size: 15px;
}

.footer-brand strong,
.footer-brand span {
  display: block;
}

.footer-brand strong {
  color: #eee;
}

.footer-brand span,
footer > p {
  color: #777f88;
}


/* ================= MOBILE ================= */

@media (max-width: 1050px) {

  nav {
    gap: 14px;
  }

  .products-grid {
    grid-template-columns: repeat(3, 1fr);
  }

  .features {
    grid-template-columns: repeat(3, 1fr);
  }

}

@media (max-width: 800px) {

  .topbar {
    flex-direction: column;
    align-items: center;
    text-align: center;
    font-size: 11px;
  }

  .header {
    height: auto;
    min-height: 74px;
    padding: 10px 16px;
  }

  .brand {
    display: none;
  }

  nav {
    display: none;
  }

  .quote-btn {
    padding: 9px 12px;
    font-size: 12px;
  }

  .logo-circle {
    width: 45px;
    height: 45px;
  }

  .hero-content {
    grid-template-columns: 1fr;
    text-align: center;
    padding: 65px 20px 110px;
  }

  .hero-text {
    margin: auto;
  }

  .hero h1 {
    font-size: 52px;
  }

  .hero h2 {
    font-size: 23px;
  }

  .hero p {
    font-size: 15px;
  }

  .hero-buttons {
    justify-content: center;
  }

  .hero-logo {
    display: none;
  }

  .manager-card {
    right: 50%;
    transform: translateX(50%);
    bottom: 25px;
  }

  .features {
    grid-template-columns: repeat(2, 1fr);
    padding: 0;
  }

  .feature {
    min-height: 85px;
    padding: 13px;
  }

  .about-grid,
  .contact-grid {
    grid-template-columns: 1fr;
  }

  .products-grid {
    grid-template-columns: repeat(2, 1fr);
  }

  .stats {
    grid-template-columns: repeat(2, 1fr);
  }

  .catalog-box,
  .whatsapp-box,
  footer {
    flex-direction: column;
    text-align: center;
  }

  .catalog-box .gold-btn {
    margin: 0;
  }

}

@media (max-width: 480px) {

  .hero {
    min-height: 640px;
  }

  .hero-content {
    min-height: 640px;
  }

  .hero h1 {
    font-size: 43px;
  }

  .hero h2 {
    font-size: 20px;
  }

  .hero-buttons a {
    width: 100%;
  }

  .features {
    grid-template-columns: 1fr;
  }

  .products-grid {
    grid-template-columns: 1fr;
  }

  .product-image {
    height: 200px;
  }

  .stats strong {
    font-size: 30px;
  }

  .section {
    padding: 65px 16px;
  }

}
CSS


cat > script.js <<'JS'
document.querySelectorAll('nav a').forEach(link => {

  link.addEventListener('click', () => {

    document.querySelectorAll('nav a')
      .forEach(item => item.classList.remove('active'));

    link.classList.add('active');

  });

});


window.addEventListener('scroll', () => {

  const sections = document.querySelectorAll('section[id]');

  let current = '';

  sections.forEach(section => {

    const top = section.offsetTop - 150;

    if (window.scrollY >= top) {
      current = section.id;
    }

  });

  document.querySelectorAll('nav a').forEach(link => {

    link.classList.remove('active');

    if (link.getAttribute('href') === '#' + current) {
      link.classList.add('active');
    }

  });

});
JS


echo ""
echo "======================================"
echo "✅ الموقع تخلق بنجاح"
echo "📁 $PROJECT"
echo "======================================"
echo ""
echo "لتشغيله:"
echo "cd ~/MITIDJA-METAL-DIAB"
echo "python -m http.server 5173 --bind 0.0.0.0"
echo ""
echo "ثم افتح:"
echo "http://localhost:5173"
echo ""
EOF

chmod +x create-mitidja-metal.sh
./create-mitidja-metal.sh
