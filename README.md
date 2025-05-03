<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Arsip Soal</title>
  <style>
    /* Global Styles */
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: url('https://files.catbox.moe/k149m3.jpg') no-repeat center center fixed;
      background-size: cover;
      color: #c7c7c7;
    }
    header {
      background-color: rgba(23, 26, 33, 0.8);
      padding: 20px;
      text-align: center;
      color: #66c0f4;
    }
    header h1 {
      margin: 0;
      font-size: 2em;
    }
    /* Navigation Bar */
    header nav {
      margin-top: 10px;
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
    }
    header nav a {
      text-decoration: none;
      color: #66c0f4;
      font-size: 1.1em;
      transition: color 0.3s;
    }
    header nav a:hover {
      color: #fff;
    }
    .hero {
      display: flex;
      align-items: center;
      justify-content: center;
      height: 300px;
      color: #fff;
      font-size: 2em;
      font-weight: bold;
      text-shadow: 2px 2px 4px #000;
    }
    .container {
      padding: 30px 20px;
      max-width: 1200px;
      margin: 20px auto;
      background: rgba(26, 26, 26, 0.8);
      border-radius: 10px;
    }
    /* Points Menu Section (original clickable list) */
    .points-menu {
      display: flex;
      flex-direction: column;
      gap: 15px;
      margin-bottom: 40px;
    }
    .point-item {
      background: rgba(42, 42, 42, 0.8);
      border-radius: 5px;
      padding: 15px 20px;
    }
    .point-link {
      text-decoration: none;
      color: #c7c7c7;
      display: block;
      cursor: pointer;
      border-left: 5px solid #66c0f4;
      padding-left: 10px;
      transition: background-color 0.3s;
    }
    .point-link:hover {
      background-color: rgba(51, 51, 51, 0.8);
    }
    .point-content {
      overflow: hidden;
      max-height: 0;
      opacity: 0;
      transition: max-height 0.5s ease-out, opacity 0.5s ease-out;
      margin-top: 15px;
      padding-top: 15px;
      border-top: 1px solid #444;
    }
    .point-content.open {
      max-height: 1000px;
      opacity: 1;
    }
    .point-content h2 {
      color: #66c0f4;
    }
    footer {
      background-color: rgba(23, 26, 33, 0.8);
      text-align: center;
      padding: 20px;
      color: #7f8c8d;
      font-size: 0.9em;
    }
    /* Responsive Styles */
    @media (max-width: 600px) {
      .hero {
        font-size: 1.5em;
        height: 200px;
      }
      .container {
        padding: 15px 10px;
        margin: 10px;
      }
      .point-item {
        padding: 10px 15px;
      }
      .point-link {
        font-size: 1em;
        padding-left: 8px;
        border-left-width: 3px;
      }
      header, footer {
        padding: 15px;
      }
      header nav a {
        font-size: 1em;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Kesultanan Arsip</h1>
    <!-- Navigation Bar -->
    <nav>
      <!-- Note the link now goes to profiles.html -->
      <a href="profiles.html">Our Profiles</a>
      <a href="#documentary">Documentary</a>
      <a href="#instagram">Our Instagram Pages</a>
    </nav>
  </header>

  <div class="hero">
    Kesultanan Arsip Soal adalah kerajaan yang didirikan di Jawa pada abad ke-21.
  </div>

  <div class="container">
    <!-- Points Menu Section (your existing content) -->
    <div class="points-menu">
      <div class="point-item">
        <a class="point-link" href="#">1. Awal Berdirinya</a>
        <div class="point-content">
          <h2>Awal Berdirinya</h2>
          
            Kesultanan Arsip pertama di dirikan pada abad
            ke-21 oleh sekelompok orang.<br>
            Pada awalnya dinamakan "Biologi nyehhh"
            sebelum diubah menjadi Arsip Soal setahun kemudian.
          
        </div>
      </div>
      
      <div class="point-item">
        <a class="point-link" href="#">2. Letak</a>
        <div class="point-content">
          <h2>Letak</h2>
          
            Kesultanan Arsip terletak di Kalasan, dengan
            ibu kota berada di depan F1.<br>
            Pada awalnya ibukota kerajaan arsip berada di 
            Rumah Ana sebelum dipindahkan ke depan F1.
          
        </div>
      </div>
      
      <div class="point-item">
        <a class="point-link" href="#">3. Tokoh</a>
        <div class="point-content">
          <h2>Tokoh</h2>
          <h3>Septiana</h3>
          
            Dia adalah salah satu tokoh penting yang mengide 
            untuk membuat Kesultanan Arsip, dengan rumahnya
            menjadi ibu kota awal kesultanan Arsip.
          
          <h3>Astrid</h3>
          
            Dia adalah tokoh yang berperan penting dalam projek 
            pertama kerajaan, yaitu projek "Kimchi Radiasi."
          
          <h3>Atha</h3>
          
            Dia merupakan tokoh yang berperan penting terhadap 
            kebudayaan Arsip dikarenakan jiwa seninya yang begitu 
            hebatnya.
          
          <h3>Hardana</h3>
          
            Juga dikenal sebagai Lidya, dia adalah tokoh penting 
            yang berperan dalam proses penyusunan Kesultanan Arsip 
            bersama Septiana.
          
          <h3>Affan</h3>
          
            Tidak banyak yang diketahui tentang tokoh ini karena 
            jarang kehadirannya, namun dia adalah satu-satunya tokoh
            yang normal, membuat Kerajaan Arsip kokoh.
          
          <h3>Raju</h3>
          
            Juga dikenal sebagai Rafi', dia adalah supplier utama dan
            pemilik markas rahasia bernama "Muara Salju" yang
            digunakan untuk eksperimen Arsip seperti Projek Kimchi Radiasi.
          
          <h3>Akmal</h3>
          
            Awalnya dia bukanlah warga Kesultanan, namun dia diterima
            atas request istimewa dari pendiri-pendiri arsip.<br>
            Bersama dengan Atha, dia telah membawa budaya India kepada
            Kesultanan Arsip.
          
        </div>
      </div>
      
      <div class="point-item">
        <a class="point-link" href="#">4. Politik</a>
        <div class="point-content">
          <h2>Politik</h2>
          <p>apa lek</p>
        </div>
      </div>
      
      <div class="point-item">
        <a class="point-link" href="#">5. Ekonomi</a>
        <div class="point-content">
          <h2>Ekonomi</h2>
          <p>Kita kaya</p>
        </div>
      </div>
      
      <div class="point-item">
        <a class="point-link" href="#">6. Budaya</a>
        <div class="point-content">
          <h2>Budaya</h2>
          <p>Stress semua lek</p>
        </div>
      </div>
      
      <div class="point-item">
        <a class="point-link" href="#">7. Bukti Sejarah</a>
        <div class="point-content">
          <h2>Bukti Sejarah</h2>
          <p></p>
          <img src="https://files.catbox.moe/yifsiu.jpg" alt="Bukti Sejarah" style="width: 500px; height:500px; border-radius: 5px;">
        </div>
      </div>
    </div>
    
   
  </div>
  
  <footer>
    &copy; 2025 Explore Arsip coy | IJIIIJIJIJ
  </footer>
  
  <script>
    // Toggle script for the points-menu sections
    document.addEventListener("DOMContentLoaded", function() {
      const links = document.querySelectorAll(".point-link");
      links.forEach(link => {
        link.addEventListener("click", function(e) {
          e.preventDefault();
          const content = this.nextElementSibling;
          content.classList.toggle("open");
        });
      });
    });
  </script>
</body>
</html>


