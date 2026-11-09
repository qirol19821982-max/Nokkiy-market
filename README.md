<!DOCTYPE html>
<html lang="uz">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bozor — Onlayn do‘kon</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="site-header">
    <div class="topbar">
      <a class="logo" href="#" aria-label="Bozor bosh sahifa">bozor<span>.</span></a>

      <button class="catalog-button" type="button">☰ <span>Katalog</span></button>

      <form class="search" role="search">
        <input type="search" placeholder="Mahsulotlarni qidiring..." aria-label="Mahsulotlarni qidiring">
        <button type="submit" aria-label="Qidirish">⌕</button>
      </form>

      <nav class="header-links" aria-label="Asosiy menyu">
        <a href="#">♡ <span>Sevimlilar</span></a>
        <a href="#">♙ <span>Kirish</span></a>
        <a href="#">🛒 <span>Savat</span></a>
      </nav>
    </div>

    <nav class="categories" aria-label="Kategoriyalar">
      <a href="#">Elektronika</a>
      <a href="#">Kiyim</a>
      <a href="#">Uy va bog‘</a>
      <a href="#">Go‘zallik</a>
      <a href="#">Bolalar uchun</a>
      <a href="#">Sport</a>
      <a href="#">Aksiyalar</a>
    </nav>
  </header>

  <main class="container">
    <section class="hero">
      <div class="hero-content">
        <p class="eyebrow">Katta chegirmalar</p>
        <h1>Yaxshi xaridlar<br>shu yerdan boshlanadi</h1>
        <p>Sevimli mahsulotlaringizni qulay narxlarda toping.</p>
        <a class="primary-button" href="#mahsulotlar">Xarid qilish</a>
      </div>
      <div class="hero-art" aria-hidden="true">🛍️</div>
    </section>

    <section class="section" aria-labelledby="categories-title">
      <div class="section-heading">
        <h2 id="categories-title">Kategoriyalar</h2>
        <a href="#">Barchasini ko‘rish →</a>
      </div>
      <div class="category-grid">
        <a class="category-card" href="#"><span>📱</span>Elektronika</a>
        <a class="category-card" href="#"><span>👕</span>Kiyim</a>
        <a class="category-card" href="#"><span>🛋️</span>Uy uchun</a>
        <a class="category-card" href="#"><span>💄</span>Go‘zallik</a>
        <a class="category-card" href="#"><span>🧸</span>Bolalar uchun</a>
        <a class="category-card" href="#"><span>⚽</span>Sport</a>
      </div>
    </section>

    <section class="section" id="mahsulotlar" aria-labelledby="products-title">
      <div class="section-heading">
        <h2 id="products-title">Ommabop mahsulotlar</h2>
        <a href="#">Barchasini ko‘rish →</a>
      </div>

      <div class="product-grid">
        <article class="product-card">
          <div class="product-image lavender">🎧<span class="discount">−20%</span><button aria-label="Sevimlilarga qo‘shish">♡</button></div>
          <div class="product-info">
            <p class="rating">★ 4.8 <span>· 124 ta sharh</span></p>
            <h3>Simsiz quloqchinlar</h3>
            <p class="old-price">499 000 so‘m</p>
            <p class="price">399 000 so‘m</p>
            <button class="cart-button" type="button">Savatga qo‘shish</button>
          </div>
        </article>

        <article class="product-card">
          <div class="product-image peach">⌚<span class="discount">−15%</span><button aria-label="Sevimlilarga qo‘shish">♡</button></div>
          <div class="product-info">
            <p class="rating">★ 4.7 <span>· 86 ta sharh</span></p>
            <h3>Aqlli soat</h3>
            <p class="old-price">799 000 so‘m</p>
            <p class="price">679 000 so‘m</p>
            <button class="cart-button" type="button">Savatga qo‘shish</button>
          </div>
        </article>

        <article class="product-card">
          <div class="product-image mint">🎒<span class="discount">−10%</span><button aria-label="Sevimlilarga qo‘shish">♡</button></div>
          <div class="product-info">
            <p class="rating">★ 4.9 <span>· 203 ta sharh</span></p>
            <h3>Kundalik ryukzak</h3>
            <p class="old-price">350 000 so‘m</p>
            <p class="price">315 000 so‘m</p>
            <button class="cart-button" type="button">Savatga qo‘shish</button>
          </div>
        </article>

        <article class="product-card">
          <div class="product-image butter">☕<span class="discount">−25%</span><button aria-label="Sevimlilarga qo‘shish">♡</button></div>
          <div class="product-info">
            <p class="rating">★ 4.6 <span>· 57 ta sharh</span></p>
            <h3>Qahva uchun krujka</h3>
            <p class="old-price">120 000 so‘m</p>
            <p class="price">90 000 so‘m</p>
            <button class="cart-button" type="button">Savatga qo‘shish</button>
          </div>
        </article>
      </div>
    </section>
  </main>

  <footer class="footer">
    <a class="logo" href="#">bozor<span>.</span></a>
    <p>Onlayn xaridlar — oson va qulay.</p>
    <small>© 2026 Bozor. Barcha huquqlar himoyalangan.</small>
  </footer>
</body>
</html>
