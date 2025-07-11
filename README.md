<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Sストレッチ｜久留米の神経ストレッチ専門</title>
  <link rel="stylesheet" href="style.css" />
  <link href="https://fonts.googleapis.com/css2?family=Noto+Serif+JP&family=Noto+Sans+JP:wght@400;700&display=swap" rel="stylesheet" />
</head>
<body>
  <header class="header">
    <div class="container">
      <h1 class="logo">Sストレッチ</h1>
      <nav>
        <ul class="nav-list">
          <li><a href="#home" class="nav-link">ホーム</a></li>
          <li><a href="#about" class="nav-link">概要</a></li>
          <li><a href="#features" class="nav-link">特徴</a></li>
          <li><a href="#price" class="nav-link">料金</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section id="home" class="hero">
    <div class="container">
      <h2 class="hero-title">あなたの体を、根本から変える</h2>
      <p class="hero-subtitle">神経×ストレッチの融合で、今までにない感動を。</p>
      <a href="https://lin.ee/xxxxxxx" class="btn-line" target="_blank" rel="noopener noreferrer">LINE予約はこちら</a>
    </div>
  </section>

  <section id="about" class="section-light">
    <div class="container">
      <h2 class="section-title">概要</h2>
      <p class="section-text">
        Sストレッチは、久留米市にある神経ストレッチ専門サロンです。長年の不調に悩む方へ、根本からのアプローチを提供します。
      </p>
    </div>
  </section>

  <section id="features" class="section-dark">
    <div class="container">
      <h2 class="section-title">特徴</h2>
      <ul class="features-list">
        <li>神経と筋膜を同時に整える独自技術</li>
        <li>痛みの出にくい体を目指す再発予防型施術</li>
        <li>完全予約制でプライベート空間</li>
      </ul>
    </div>
  </section>

  <section id="price" class="section-light">
    <div class="container">
      <h2 class="section-title">料金</h2>
      <ul class="price-list">
        <li><span class="price-item">初回体験：</span>3,980円（カウンセリング込み）</li>
        <li><span class="price-item">1回：</span>6,000円</li>
        <li><span class="price-item">回数券（4回）：</span>22,000円</li>
      </ul>
    </div>
  </section>

  <footer class="footer">
    <div class="container">
      <p>&copy; 2025 Sストレッチ | 久留米市</p>
    </div>
  </footer>
</body>
</html>
/* ベース */
body {
  margin: 0;
  font-family: 'Noto Sans JP', 'Noto Serif JP', serif, sans-serif;
  background: #121212; /* ダーク背景 */
  color: #e0e0e0;
  line-height: 1.7;
}

/* コンテナ幅調整 */
.container {
  width: 90%;
  max-width: 1024px;
  margin: 0 auto;
}

/* ヘッダー */
.header {
  background-color: #1a1a1a;
  padding: 1.5rem 0;
  box-shadow: 0 4px 10px rgba(0,0,0,0.7);
  position: sticky;
  top: 0;
  z-index: 100;
}

.logo {
  font-family: 'Noto Serif JP', serif;
  font-size: 2.4rem;
  font-weight: 700;
  color: #d4af37; /* ゴールド */
  letter-spacing: 0.1em;
  margin: 0;
}

.nav-list {
  list-style: none;
  display: flex;
  gap: 2rem;
  padding: 0;
  margin: 0.5rem 0 0 0;
}

.nav-link {
  color: #e0e0e0;
  text-decoration: none;
  font-weight: 600;
  padding-bottom: 3px;
  border-bottom: 2px solid transparent;
  transition: border-color 0.3s ease;
}

.nav-link:hover,
.nav-link:focus {
  border-bottom-color: #d4af37;
}

/* ヒーローセクション */
.hero {
  background: linear-gradient(135deg, #2c2c2c 0%, #000000 100%);
  padding: 5rem 0;
  text-align: center;
}

.hero-title {
  font-family: 'Noto Serif JP', serif;
  font-size: 3rem;
  font-weight: 700;
  margin-bottom: 1rem;
  color: #d4af37;
  text-shadow: 0 0 8px rgba(212, 175, 55, 0.7);
}

.hero-subtitle {
  font-size: 1.3rem;
  margin-bottom: 3rem;
  color: #ccc;
}

/* ボタン */
.btn-line {
  background: linear-gradient(45deg, #bfb84d, #6f6a1e);
  color: #fff;
  padding: 0.9rem 2rem;
  border-radius: 40px;
  font-weight: 700;
  text-decoration: none;
  box-shadow: 0 4px 12px rgba(191, 184, 77, 0.7);
  transition: background 0.3s ease, box-shadow 0.3s ease;
}

.btn-line:hover,
.btn-line:focus {
  background: linear-gradient(45deg, #d4af37, #8c8400);
  box-shadow: 0 6px 18px rgba(212, 175, 55, 0.9);
}

/* セクション共通 */
.section-light {
  background-color: #1e1e1e;
  padding: 4rem 0;
  border-top: 1px solid #444;
  border-bottom: 1px solid #444;
}

.section-dark {
  background-color: #2a2a2a;
  padding: 4rem 0;
  border-top: 1px solid #555;
  border-bottom: 1px solid #555;
}

.section-title {
  font-family: 'Noto Serif JP', serif;
  font-size: 2.4rem;
  font-weight: 700;
  color: #d4af37;
  margin-bottom: 2rem;
  border-left: 6px solid #d4af37;
  padding-left: 1rem;
}

/* リスト */
.features-list,
.price-list {
  list-style-type: none;
  padding-left: 0;
  color: #ddd;
  font-size: 1.1rem;
  line-height: 2;
}

.price-item {
  font-weight: 700;
  color: #d4af37;
}

/* フッター */
.footer {
  background-color: #111;
  color: #666;
  text-align: center;
  padding: 1.5rem 0;
  font-size: 0.9rem;
  letter-spacing: 0.05em;
}
