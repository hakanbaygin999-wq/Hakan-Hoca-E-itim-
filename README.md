<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#12345a">
  <title>Hakan Hoca Eğitim</title>
  <style>
    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f2f5fa;
      color: #172b4d;
    }
    header {
      background: #12345a;
      color: white;
      padding: 28px 20px;
      text-align: center;
      border-radius: 0 0 24px 24px;
    }
    header h1 { margin: 0 0 8px; }
    header p { margin: 0; }
    main { padding: 20px; max-width: 600px; margin: auto; }
    .card {
      background: white;
      padding: 20px;
      margin: 14px 0;
      border-radius: 16px;
      box-shadow: 0 3px 12px #0000000d;
    }
    .card h2 { margin-top: 0; font-size: 19px; }
    .card p { color: #52627a; line-height: 1.5; }
    button {
      background: #1769aa;
      color: white;
      border: 0;
      padding: 12px 18px;
      border-radius: 10px;
      font-size: 15px;
      cursor: pointer;
    }
    #mesaj { font-weight: bold; color: #1769aa; }
    footer {
      text-align: center;
      padding: 24px;
      color: #65748b;
      font-size: 13px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Hakan Hoca Eğitim</h1>
    <p>Hedefine ulaşmak için bugün bir adım at!</p>
  </header>

  <main>
    <section class="card">
      <h2>📚 Öğrenci Koçluğu</h2>
      <p>Kişisel çalışma programları ve hedef takibi.</p>
      <button onclick="bilgi('Öğrenci koçluğu modülümüz hazırlanıyor.')">
        Koçluğu İncele
      </button>
    </section>

    <section class="card">
      <h2>🎯 Günlük Hedeflerim</h2>
      <p>Derslerini planla, hedeflerini takip et.</p>
      <button onclick="bilgi('Günlük hedefler modülümüz hazırlanıyor.')">
        Hedeflerimi Gör
      </button>
    </section>

    <section class="card">
      <h2>📈 İlerleme Takibi</h2>
      <p>Çalışmalarını ve gelişimini takip et.</p>
      <button onclick="bilgi('İlerleme takibi modülümüz hazırlanıyor.')">
        İlerlemeni Gör
      </button>
    </section>

    <section class="card">
      <h2>📝 Sınav Hazırlığı</h2>
      <p>LGS, YKS ve KPSS için çalışma alanı.</p>
      <p id="mesaj">Birlikte başarıya!</p>
    </section>
  </main>

  <footer>© Hakan Hoca Eğitim</footer>

  <script>
    function bilgi(metin) {
      alert(metin);
    }
  </script>
</body>
</html>
