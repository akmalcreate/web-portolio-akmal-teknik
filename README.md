<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Akmal - Belajar & Berbagi tentang Teknologi Jaringan</title>

  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">

  <style>
    * { box-sizing: border-box; }
    html { scroll-behavior: smooth; }

    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      background-color: #111;
      color: #fff;
      animation: fadeIn 1.2s ease-in-out;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    header, footer {
      text-align: center;
      padding: 2rem;
      background-color: #000;
    }

    section {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }

    .hero img {
      width: 200px;
      border-radius: 50%;
      display: block;
      margin: 1rem auto;
      box-shadow: 0 0 10px rgba(255,255,255,0.3);
    }

    /* ===== PORTOFOLIO ===== */
    .portfolio-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 1.2rem;
      margin-top: 1.5rem;
    }

    .portfolio-card {
      background: #1a1a1a;
      padding: 1.2rem;
      border-radius: 12px;
      text-align: center;
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .portfolio-card:hover {
      transform: translateY(-6px);
      box-shadow: 0 10px 25px rgba(255,255,255,0.1);
    }

    .portfolio-card img {
      width: 100%;
      max-height: 140px;
      object-fit: contain;
      background: #fff;
      padding: 10px;
      border-radius: 8px;
      margin-bottom: 0.8rem;
    }

    /* ===== AKTIVITAS ===== */
    .activity-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.2rem;
      margin-top: 1.5rem;
    }

    .activity-card {
      background: #1a1a1a;
      border-radius: 12px;
      overflow: hidden;
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .activity-card:hover {
      transform: translateY(-6px);
      box-shadow: 0 10px 25px rgba(255,255,255,0.1);
    }

    .activity-card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }

    .activity-card h3 {
      padding: 1rem 1rem 0.3rem;
    }

    .activity-card p {
      padding: 0 1rem 1rem;
      font-size: 14px;
      color: #ccc;
    }

    /* ===== SOSIAL ===== */
    .social-links a {
      color: #fff;
      margin: 0.5rem;
      text-decoration: none;
      display: inline-block;
      transition: transform 0.3s;
    }

    .social-links a:hover {
      transform: scale(1.1);
    }

    .contact-form input,
    .contact-form textarea {
      width: 100%;
      margin-bottom: 1rem;
      padding: 0.75rem;
      border: none;
      border-radius: 6px;
    }

    .contact-form button {
      background: #fff;
      color: #000;
      padding: 0.75rem 1.5rem;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      transition: background 0.3s, transform 0.3s;
    }

    .contact-form button:hover {
      background: #ddd;
      transform: scale(1.05);
    }

    @media (max-width: 600px) {
      section { padding: 1rem; }
      .hero img { width: 150px; }
      .social-links a { display: block; margin: 0.5rem 0; }
    }
  </style>
</head>

<body>

<header>
  <h1>Akmal</h1>
  <p>Belajar & Berbagi tentang Teknologi Jaringan</p>
  <div class="hero">
    <img src="akmal1.png" alt="Foto Akmal">
  </div>
</header>

<section>
  <h2>Tentang Saya</h2>
  <p>Teknologi adalah passion saya. Saya senang mempelajari sistem jaringan, konfigurasi perangkat, dan solusi digital.</p>
</section>

<section>
  <h2>Keahlian</h2>
  <ul>
    <li>Konfigurasi Mikrotik</li>
    <li>Desain visual (Canva)</li>
    <li>Editing video (CapCut)</li>
    <li>Software pendukung teknologi</li>
  </ul>
</section>

<section>
  <h2>Portofolio</h2>
  <div class="portfolio-grid">

    <div class="portfolio-card">
      <img src="logosepatukucing.png">
      <h3>Shoe Cat</h3>
      <p>Logo brand sepatu Shoe Cat dengan konsep sport & street.</p>
    </div>

    <div class="portfolio-card">
      <img src="logoPendepokan.png">
      <h3>Pencak Silat Walet Putih</h3>
      <p>Logo pendepokan Mustika Walet Putih.</p>
    </div>

    <div class="portfolio-card">
      <img src="waletputih.png">
      <h3>Walet Putih Kab. Bogor</h3>
      <p>Logo pencak silat Walet Putih Kabupaten Bogor.</p>
    </div>

    <div class="portfolio-card">
      <img src="promosepatu.png">
      <h3>Desain Promosi Sepatu</h3>
      <p>Desain visual promosi sepatu.</p>
    </div>

  </div>
</section>

<!-- ===== AKTIVITAS WINBOX ===== -->
<section>
  <h2>Dokumentasi Praktik TKJ - 25 Mei 2025</h2>

  <div class="activity-grid">

    <div class="activity-card">
      <img src="komputer.png">
      <h3>Konfigurasi Awal Router MikroTik</h3>
      <p>Pengaturan IP Address, konfigurasi interface, dan pengecekan koneksi jaringan menggunakan Winbox.</p>
    </div>

    <div class="activity-card">
      <img src="tkj.png">
      <h3>Praktik Jaringan di Lab TKJ</h3>
      <p>Praktik konfigurasi jaringan bersama di laboratorium TKJ dengan pengawasan guru.</p>
    </div>

    <div class="activity-card">
      <img src="tkj2.png">
      <h3>Monitoring & Troubleshooting</h3>
      <p>Monitoring traffic jaringan serta troubleshooting untuk memastikan koneksi stabil.</p>
    </div>

  </div>
</section>

<section>
  <h2>Kontak</h2>
  <div class="social-links">
    <a href="https://www.instagram.com/akmal.mgr?igsh=anBsODV1ZmJxNHVh" target="_blank">Instagram</a>
    <a href="https://wa.me/6288214263826" target="_blank">WhatsApp</a>
    <a href="https://t.me/akmalcher" target="_blank">Telegram</a>
    <a href="mailto:akmalalmagribi6@gmail.com">Email</a>
    <a href="https://youtube.com/@noircam" target="_blank">YouTube</a>
  </div>
</section>

<section>
  <h2>Formulir Kontak</h2>
  <form class="contact-form">
    <input type="text" placeholder="Nama Lengkap">
    <input type="email" placeholder="Email Aktif">
    <textarea rows="5" placeholder="Tulis pesan kamu di sini..."></textarea>
    <button type="submit">Kirim</button>
  </form>
</section>

<footer>
  <p>&copy; 2025 Akmal. All rights reserved.</p>
</footer>

</body>
</html>
