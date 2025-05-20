SELAMAT DATANG!
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nokomi PrintShop</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background-color: #0b1f40;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    nav {
      background-color: #122d5c;
      display: flex;
      justify-content: center;
    }
    nav a {
      color: white;
      padding: 1rem;
      text-decoration: none;
    }
    nav a:hover {
      background-color: #1e3d7c;
    }
    section {
      padding: 2rem;
    }
    .produk, .galeri {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
    }
    .card {
      background-color: white;
      border: 1px solid #ddd;
      padding: 1rem;
      border-radius: 6px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.05);
    }
    footer {
      background-color: #0b1f40;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>

<header>
  <h1>Nokomi PrintShop</h1>
  <p>Solusi Cetak dan Desain Anda</p>
</header>

<nav>
  <a href="#beranda">Beranda</a>
  <a href="#produk">Produk</a>
  <a href="#galeri">Galeri</a>
  <a href="#kontak">Kontak</a>
</nav>

<section id="beranda">
  <h2>Selamat Datang di Nokomi PrintShop</h2>
  <p>Kami menyediakan layanan cetak dan desain berkualitas tinggi seperti nota custom, undangan, Jasa desain karikatur dan banner. Dengan sentuhan profesional dan harga terjangkau, kami siap membantu kebutuhan percetakan Anda.</p>
</section>

<section id="produk">
  <h2>Produk & Layanan</h2>
  <div class="produk">
    <div class="card">
      <h3>Cetak Nota Custom</h3>
      <p>Berbagai ukuran dan desain sesuai kebutuhan usaha Anda.</p>
    </div>
    <div class="card">
      <h3>Cetak Undangan</h3>
      <p>Undangan pernikahan, khitanan, ulang tahun, dan lainnya.</p>
    </div>
    <div class="card">
      <h3>Desain Karikatur</h3>
      <p>Ilustrasi karikatur unik dan personal untuk hadiah atau branding.</p>
    </div>
    <div class="card">
      <h3>Desain Banner/Spanduk</h3>
      <p>Desain profesional untuk kebutuhan promosi Anda.</p>
    </div>
  </div>
</section>

<section id="galeri">
  <h2>Galeri</h2>
  <div class="galeri">
    <div class="card"><p>Contoh Desain Nota</p></div>
    <div class="card"><p>Contoh Undangan</p></div>
    <div class="card"><p>Contoh Karikatur</p></div>
    <div class="card"><p>Contoh Banner</p></div>
  </div>
</section>

<section id="kontak">
  <h2>Kontak Kami</h2>
  <p>WhatsApp: <a href=https://wa.link/trmn3y</a></p>
  <p>Instagram: <a href="https://instagram.com/nokomi.printshop">@nokomi_printshop</a></p>
  <p>Alamat: Jl. Sengkawit , Tanjung Selor</p>
</section>

<footer>
  <p>&copy; 2025 Nokomi PrintShop. All rights reserved.</p>
</footer>

</body>
</html>
