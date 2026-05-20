<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tahmin Dünyası</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #0f172a;
      color: white;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(90deg, #1d4ed8, #2563eb);
      padding: 30px;
      text-align: center;
      box-shadow: 0 4px 10px rgba(0,0,0,0.3);
    }

    header h1 {
      font-size: 42px;
      margin-bottom: 10px;
    }

    header p {
      font-size: 18px;
      opacity: 0.9;
    }

    nav {
      background: #1e293b;
      padding: 15px;
      text-align: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    nav a:hover {
      color: #60a5fa;
    }

    .hero {
      text-align: center;
      padding: 80px 20px;
    }

    .hero h2 {
      font-size: 36px;
      margin-bottom: 20px;
    }

    .hero p {
      font-size: 20px;
      max-width: 700px;
      margin: auto;
      color: #cbd5e1;
    }

    .btn {
      display: inline-block;
      margin-top: 25px;
      padding: 14px 28px;
      background: #2563eb;
      color: white;
      text-decoration: none;
      border-radius: 10px;
      font-weight: bold;
    }

    .btn:hover {
      background: #1d4ed8;
    }

    .cards {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      padding: 40px 20px;
    }

    .card {
      background: #1e293b;
      width: 300px;
      padding: 25px;
      border-radius: 15px;
      box-shadow: 0 6px 15px rgba(0,0,0,0.3);
    }

    .card h3 {
      margin-bottom: 15px;
      color: #60a5fa;
    }

    footer {
      background: #020617;
      text-align: center;
      padding: 20px;
      color: #94a3b8;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <h1>⚽ Tahmin Dünyası</h1>
    <p>Günlük maç analizleri ve spor yorumları</p>
  </header>

  <nav>
    <a href="#">Ana Sayfa</a>
    <a href="#">Günlük Tahminler</a>
    <a href="#">Analizler</a>
    <a href="#">İletişim</a>
  </nav>

  <section class="hero">
    <h2>En Güncel Spor Tahminleri</h2>
    <p>
      Günlük maç analizleri, istatistik yorumları ve spor içerikleri ile
      takipçilerine düzenli içerik sun.
    </p>
    <a href="#" class="btn">Tahminleri Gör</a>
  </section>

  <section class="cards">
    <div class="card">
      <h3>⚽ Futbol Analizleri</h3>
      <p>Süper Lig, Şampiyonlar Ligi ve dünya liglerinden analizler.</p>
    </div>

    <div class="card">
      <h3>📊 İstatistikler</h3>
      <p>Takımların form durumları ve maç performansları.</p>
    </div>

    <div class="card">
      <h3>📝 Günlük Yorumlar</h3>
      <p>Her gün yeni içerikler ve spor değerlendirmeleri.</p>
    </div>
  </section>

  <footer>
    © 2026 Tahmin Dünyası - Tüm Hakları Saklıdır.
  </footer>

</body>
</html>
