

<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <link rel="stylesheet" href="style.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <title>BrowniesNurca</title>
</head>
<body>

  <nav class="navbar">
    <input type="checkbox" id="menu-toggle" />
    <label for="menu-toggle" class="menu-icon">&#9776;</label>
  
    <div class="nav-content">
      <div class="nav-left">
        <a href="#beranda">Beranda</a>
        <a href="#produk">Produk</a>
        <a href="#keranjang">Keranjang</a>
        <a href="#kontak">Kontak</a>
      </div>
      <div class="nav-right">
        <span class="toko-nama">BrowniesNurca</span>
      </div>
    </div>
  </nav>

<section id="beranda">
  <div class="jumbotron">
    <h2>Deskripsi Toko</h2>
    <div class="deskripsi-grid">
      <div>
        <p><strong>Brownies Nurca</strong> adalah toko kue rumahan yang berfokus pada pembuatan brownies berkualitas tinggi dengan cita rasa autentik dan tekstur lembut. Kami menggunakan bahan-bahan pilihan seperti cokelat premium, mentega asli, dan tepung berkualitas.</p>
      </div>
      <div>
        <p>Produk unggulan kami antara lain: Brownies Original, Brownies Banana Cheese, Brownies Green Tea, Brownies Tiramisu, Dan kami juga menyediakan varian mini dan brownies kering yang cocok untuk oleh-oleh atau camilan praktis.</p>
      </div>
      <div>
        <p>Keunggulan kami meliputi penggunaan bahan alami tanpa pengawet, proses pembuatan higienis, serta kemasan menarik untuk berbagai kebutuhan seperti hampers, acara spesial, atau oleh-oleh khas Bandung.</p>
      </div>
    </div>
  </div>
</section>

<section id="produk">
  <h2>Produk Kami</h2>
  <div class="grid-produk">
    <div class="produk">
      <img src="img/brownies original.webp" alt="Produk 1" width="150" height="150">
      <h3>Original Brownies</h3>
      <p>Rp50.000</p>
      <br>
      <button><i class="fas fa-shopping-cart"></i> Tambahkan ke Keranjang</button>
    </div>
    <div class="produk">
      <img src="img/BrowniesKering2.webp" alt="Produk 2" width="150" height="150">
      <h3>Brownies Kering</h3>
      <p>Rp80.000</p>
      <br>
      <button><i class="fas fa-shopping-cart"></i> Tambahkan ke Keranjang</button>
    </div>
    <div class="produk">
      <img src="img/Tiramisu1.png" alt="Produk 3" width="150" height="150">
      <h3>Brownies Tiramisu</h3>
      <p>Rp70.000</p>
      <br>
      <button><i class="fas fa-shopping-cart"></i> Tambahkan ke Keranjang</button>
    </div>
    <div class="produk">
      <img src="img/Greentea1.webp" alt="Produk 4" width="150" height="150">
      <h3>Brownies Green Tea</h3>
      <p>Rp80.000</p>
      <br>
      <button><i class="fas fa-shopping-cart"></i> Tambahkan ke Keranjang</button>
    </div>
    <div class="produk">
      <img src="img/BananaCheese1.webp" alt="Produk 5"width="150" height="150">
      <h3>Brownies Banana Cheese</h3>
      <p>Rp90.000</p>
      <button><i class="fas fa-shopping-cart"></i> Tambahkan ke Keranjang</button>
    </div>
    <div class="produk">
      <img src="img/CheeseCream1.webp" alt="Produk 6" width="150" height="150">
      <h3>Brownies Cheese Cream</h3>
      <p>Rp100.000</p>
      <button><i class="fas fa-shopping-cart"></i> Tambahkan ke Keranjang</button>
    </div>
  </div>
</section>

<section id="keranjang">
  <h2><i class="fas fa-shopping-cart"></i> Keranjang Belanja</h2>
  <p>Produk di keranjang:</p>
  <div class="grid-produk">
    <div class="produk">
      <img src="img/BananaCheese1.webp" alt="Produk 5"  width="150" height="150">
      <h3>Brownies Banana Cheese</h3>
      <p>Rp90.000</p>
    </div>
    <div class="produk">
      <img src="img/Tiramisu1.png" alt="Produk 3"  width="150" height="150">
      <h3>Brownies Tiramisu</h3>
      <p>Rp70.000</p>
    </div>
  </div>
<p><strong>Total: Rp160.000</strong></p>
<button style="margin-top: 20px;">Bayar Sekarang</button>
</section>

<section id="kontak">
  <h2>Kontak Kami</h2>
  <form action="#" method="post">
    <input type="text" id="nama" name="nama" required placeholder="Nama Anda">
<input type="email" id="email" name="email" required placeholder="Email Anda">
<textarea id="pesan" name="pesan" rows="5" required placeholder="Tulis pesan Anda..."></textarea>
    <button type="submit">Kirim</button>
  </form>
</section>
<footer>
  <p>&copy; 2025 BrowniesNurca.All Rights Reserved.</p>
</footer>
</body>
</html>
