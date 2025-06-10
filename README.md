# web-portolio-akmal-teknik
web portolio sederhana
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Akmal - Konfigurasi Mikrotik</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
    }
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #111;
      color: #fff;
      animation: fadeIn 1.2s ease-in-out;
    }
    @keyframes fadeIn {
      0% { opacity: 0; transform: translateY(20px); }
      100% { opacity: 1; transform: translateY(0); }
    }
    header, footer {
      text-align: center;
      padding: 2rem;
      background-color: #000;
    }
    header h1 {
      margin-bottom: 0.5rem;
      animation: fadeIn 1s ease-in-out;
    }
    section {
      padding: 2rem;
      max-width: 800px;
      margin: auto;
      animation: fadeIn 1.5s ease-in-out;
    }
    .hero img {
      width: 200px;
      border-radius: 50%;
      display: block;
      margin: 1rem auto;
      box-shadow: 0 0 10px rgba(255, 255, 255, 0.3);
    }
    .social-links a {
      color: #fff;
      margin: 0 0.5rem;
      text-decoration: none;
      display: inline-block;
      transition: transform 0.3s;
    }
    .social-links a:hover {
      transform: scale(1.1);
    }
    .contact-form input, .contact-form textarea {
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
    }@media (max-width: 600px) {
  header, section, footer {
    padding: 1rem;
  }
  .hero img {
    width: 150px;
  }
  .social-links a {
    display: block;
    margin: 0.5rem 0;
  }
}

  </style>
</head>
<body>
  <header>
    <h1>Akmal</h1>
    <p>Konfigurasi Mikrotik</p>
    <div class="hero">
      <!-- Ganti dengan foto profil kamu -->
      <img src="akmal1.png" alt="akmal1.png">
    </div>
  </header>  <section>
    <h2>Tentang Saya</h2>
    <p>Saya adalah pribadi yang menyukai hal baru dan teknologi.</p>
  </section>  <section>
    <h2>Keahlian</h2>
    <ul>
      <li>Mengkonfigurasi jaringan</li>
    </ul>
  </section>  <section>
    <h2>Portofolio</h2>
    <p>Lihat hasil kerja saya di <a href="https://github.com/akmalcreate" target="_blank">GitHub Akmal</a>.</p>
  </section>  <section>
    <h2>Kontak</h2>
    <div class="social-links">
      <a href="https://www.instagram.com/max_verstamall" target="_blank">Instagram</a>
      <a href="https://wa.me/6288214263826" target="_blank">WhatsApp</a>
      <a href="https://t.me/akmalcher" target="_blank">Telegram</a>
      <a href="mailto:akmalalmagribi6@gmail.com">Email</a>
    </div>
  </section>  <section>
    <h2>Formulir Kontak</h2>
    <form class="contact-form">
      <input type="text" placeholder="Nama">
      <input type="email" placeholder="Email">
      <textarea rows="5" placeholder="Pesan Anda"></textarea>
      <button type="submit">Kirim</button>
    </form>
  </section>  <footer>
    <p>&copy; 2025 Akmal. All rights reserved.</p>
  </footer>
</body>
</html>
