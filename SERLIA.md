# Belajar-Pemprograman-Web
# index.html
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Selamat Datang</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #e3f2fd;
      text-align: center;
      padding-top: 100px;
    }
    h1 {
      font-size: 48px;
      color: #1976d2;
    }
    a.button {
      display: inline-block;
      margin-top: 30px;
      padding: 12px 24px;
      background-color: #1976d2;
      color: white;
      text-decoration: none;
      border-radius: 6px;
      font-size: 18px;
      cursor: pointer;
    }
    a.button:hover {
      background-color: #0d47a1;
    }
  </style>
</head>
<body>

  <h1>Selamat Datang di Website Saya</h1>
  <p>Klik tombol di bawah ini untuk melihat profil saya.</p>
  <a href="profil.html" class="button">Masuk ke Profil</a>

</body>
</html>




# profil.html
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Profil Saya</title>
  <!-- Link ke Font Awesome -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" integrity="sha512-..." crossorigin="anonymous" referrerpolicy="no-referrer" />
  <style>
    body {
      font-family: Arial, sans-serif;
      max-width: 800px;
      margin: 40px auto;
      padding: 20px;
      background-color: white;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    img {
      width: 220px;
      height: 220px;
      border-radius: 50%;
      border: 5px solid #3498db;
      object-fit: cover;
      display: block;
      margin: 0 auto 20px auto;
    }
    h1, h2 {
      text-align: center;
      color: #3498db;
    }
    p, ul {
      font-size: 18px;
      line-height: 1.6;
    }
    ul {
      list-style: none;
      padding: 0;
      text-align: center;
    }
    ul li {
      margin: 10px 0;
    }
    a {
      color: #1976d2;
      text-decoration: none;
      font-size: 20px;
    }
    a i {
      margin-right: 8px;
      color: #3498db;
    }
  </style>
  <style>
    body {
      font-family: Arial, sans-serif;
      max-width: 800px;
      margin: 40px auto;
      padding: 20px;
      background-image: url("penulis.jpg");
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      background-attachment: fixed;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      background-color: rgba(255, 255, 255, 0.8); /* fallback jika gambar tidak tampil */
    }
  
    /* Tambahan: tambahkan overlay putih agar teks tetap terbaca */
    body::before {
      content: "";
      position: fixed;
      top: 0; left: 0; right: 0; bottom: 0;
      background-color: rgba(255, 255, 255, 0.8);
      z-index: -1;
    }
  
    img {
      width: 220px;
      height: 220px;
      border-radius: 50%;
      border: 5px solid #3498db;
      object-fit: cover;
      display: block;
      margin: 0 auto 20px auto;
    }
    h1, h2 {
      text-align: center;
      color: #3498db;
    }
    p, ul {
      font-size: 18px;
      line-height: 1.6;
    }
    ul {
      list-style: none;
      padding: 0;
      text-align: center;
    }
    ul li {
      margin: 10px 0;
    }
    a {
      color: #1976d2;
      text-decoration: none;
      font-size: 20px;
    }
    a i {
      margin-right: 8px;
      color: #3498db;
    }
  </style>
</head>
<body>

  <h1>Serlia Turu Allo</h1>
  <img src="serliaserlia.jpg" alt="Foto Profil">
  <p style="text-align:center;">
  <strong>
    <a href="penulis.html" title="Klik untuk melihat karya saya sebagai penulis" style="color:#0c35eb; text-decoration:none;">
      Penulis
    </a>
  </strong>
</p>


  </p>

  <h2 style="text-align: center;">Tentang Saya</h2>
<p style="text-align: center; font-style: italic;">
  Halo!<br>
  Saya adalah seorang penulis yang mencintai dunia kata-kata, menjadikannya sebagai ruang untuk berbagi cerita, gagasan, dan makna yang menginspirasi.
</p>


  <h2 style="text-align: center;">Kontak dan Media Sosial</h2>

<div class="sosmed-grid">
  <div class="sosmed-kiri">
    <a href="mailto:serlia121204@gmail.com"><i class="fas fa-envelope"></i>Email</a>
    <a href="https://t.me/S3rl1a" target="_blank"><i class="fab fa-telegram"></i>Telegram</a>
    <a href="https://github.com/Serlia-could/Belajar-Pemprograman-Web" target="_blank"><i class="fab fa-github"></i>GitHub</a>
  </div>
  <div class="sosmed-kanan">
    <a href="https://www.instagram.com/srly.aaa?igsh=MWF5dXRuZHA2MGFvcA==" target="_blank"><i class="fab fa-instagram"></i>Instagram</a>
    <a href="https://wa.me/6282311512315" target="_blank"><i class="fab fa-whatsapp"></i>WhatsApp</a>
  </div>
</div>

<style>
  .sosmed-grid {
    display: flex;
    justify-content: center;
    gap: 50px;
    flex-wrap: wrap;
    text-align: left;
  }
  .sosmed-kiri, .sosmed-kanan {
    display: flex;
    flex-direction: column;
    gap: 12px;
  }
  .sosmed-kiri a, .sosmed-kanan a {
    font-size: 18px;
    color: #1976d2;
    text-decoration: none;
  }
  .sosmed-kiri a i, .sosmed-kanan a i {
    margin-right: 8px;
    color: #3498db;
  }
</style>


</body>
</html>


# penulis.html
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Karya Penulis - Serlia Turu Allo</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      max-width: 800px;
      margin: 40px auto;
      padding: 20px;
      background-color: white;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    h1, h2 {
      color: #3498db;
      text-align: center;
    }
    article {
      background: #f9f9f9;
      padding: 15px;
      border-radius: 8px;
      box-shadow: 0 0 5px rgba(0,0,0,0.1);
      margin-bottom: 30px;
    }
    nav {
      text-align: center;
      margin-bottom: 30px;
    }
    nav a {
      color: #1976d2;
      text-decoration: none;
      font-size: 18px;
      font-weight: bold;
      border: 2px solid #1976d2;
      padding: 8px 16px;
      border-radius: 6px;
      transition: background-color 0.3s, color 0.3s;
    }
    nav a:hover {
      background-color: #1976d2;
      color: white;
    }
  </style>
  <style>
    body {
      font-family: Arial, sans-serif;
      max-width: 800px;
      margin: 40px auto;
      padding: 20px;
      background-image: url("toraja.jpeg");
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      background-attachment: fixed;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      background-color: rgba(255, 255, 255, 0.8); /* fallback jika gambar tidak tampil */
    }
  
    /* Tambahan: tambahkan overlay putih agar teks tetap terbaca */
    body::before {
      content: "";
      position: fixed;
      top: 0; left: 0; right: 0; bottom: 0;
      background-color: rgba(255, 255, 255, 0.8);
      z-index: -1;
    }
  
    img {
      width: 220px;
      height: 220px;
      border-radius: 50%;
      border: 5px solid #3498db;
      object-fit: cover;
      display: block;
      margin: 0 auto 20px auto;
    }
    h1, h2 {
      text-align: center;
      color: #3498db;
    }
    p, ul {
      font-size: 18px;
      line-height: 1.6;
    }
    ul {
      list-style: none;
      padding: 0;
      text-align: center;
    }
    ul li {
      margin: 10px 0;
    }
    a {
      color: #1976d2;
      text-decoration: none;
      font-size: 20px;
    }
    a i {
      margin-right: 8px;
      color: #3498db;
    }
  </style>
</head>
<body>

  <nav>
    <a href="profil.html">← Kembali ke Profil</a>
  </nav>
  <style>
    p {
      text-align: justify;
    }
  </style>
  <h1>Karya Penulis</h1>

  <article>
    <h2>Kebudayaan Suku Toraja, Tarian Pa’gellu’</h2>
    <p>
        Di sebuah daerah yang dikenal dengan adat yang di anut masih sangat kental hingga saat ini, yakni Suku Toraja tepatnya berada di Provinsi Sulawesi Selatan. 
        Di daerah itu, terdapat seorang gadis yang baru pertama kali menginjakkan kakinya di Suku Toraja, yang sedari kecil ia tinggal di Negeri orang bersama kedua orang Tuanya . Hingga berada disuatu keadaan, ia pindah ke Toraja dengan alasan yang diberikan kedua orang tuanya, bahwa sang Nenek yang tinggal di Toraja sedang sakit yang membuat mereka dengan terpaksa pindah ke Toraja.
        Nathalia ada gadis yang baru saja pindah dari Negeri orang ke Toraja, ia gadis yang manis dan juga polos, memiliki karakter keingin tahuan yang tinggi. 
        Suatu  ketika ia dan kedua orang tuanya mengahadiri pernikahan di desa seberang. Pernikahan itu digelar dengan sangat megah dan meriah yang dihadiri ratusan masyarakat. Acara yang menampilkan begitu banyak pertujunkan. Namun yang membuat Nathalia terpanah adalah Tarian Pa’gellu’.
        Nathalia yang pertama kali melihat pernikahan Suku Toraja merasa asing dengan semua yang ia lihat. Namun, disisi lain ia sangat takjub dengan apa yang ia saksikan secara langsung  dengan mata telanjang. Nathalia larut dalam kekagumannya tanpa sadar ia tertinggal oleh kedua orang tuanya. 
        Nathalia terkaguma-kagum dengan tarian yang ditampilkan oleh  gadis Toraja yakni, Tarian Pa’gellu’. 
        Nathalia memandang penari di atas podium dengan mata tanpa berkedip sedikitpun, seolah-olah ia berada pada dimensi yang berbeda memberikan kehangatan bagi setiap yang menyaksikan. 
        Nathalia yang larut dalam kekagumannya tanpa tersadar seorang laki-laki datang menghampiri dan menepuk pundaknya, sontak saja Nathalia kaget dan melirik siapa yang menepuk pundaknya. 
        Kelvin anak laki-laki yang datang menepuk pundak Nathalia itu tersenyum kepada Nathalia sambil menyodorkan tanganya memperkenalkan dirinya.
        “Nama aku Kelvin, nama kamu siapa?, dan kenapa kamu disini diam seperti patung?”, tanya Kevin berturut-turut.                 
    </p>
    <p>
      Nathalia yang mendengar pertanyaan dari kevin secara berturut-turut itu binging dan linglung apa yang harus ia jawab kepada seseorang yang tiba-tiba saja datang menghampirinya, Nathalia pun tak mengenal siapa pria ini. Dengan ragu Nathalia mengajukan pertanyaan yang begitu mengganjal dalam hatinya, seraya menunjuk pada penari yang masih menampilkan tarian Khas Suku Toraja.    
      “Tarian apa yang mereka tampilkan?, mengapa begitu indah dan mampu membawaku seolah-olah aku berada ada dimensi yang lain?”, tanya Nathalia dengan ragu.
      Kelvin yang mendengar pertanyaan Nathalia itu tersenyum sambil memandangi gadis-gadis  Toraja yang begitu lihai dalam memainkan perannya. Dengan pakaian adat yang begitu memukau dipadukan dengan hiasan pakaian yang sering di sebut oleh Masyarakat Toraja Kandaure, terdapat juga Keris Emas yang disematkan pada pinggang penari dengan rambut yang di sanggul, yang menggambarkan  bahwa Suku Toraja adalah Suku bangsawan yang berani baik wanita maupun laki-laki.
     Kelvin yang semula terdiam kini menatap Nathalia seraya menjawab pertanyaan Nathalia,                                  
     “Itu adalah Tarian Khas Suku Toraja yang dinamakan Tarian Pa’gellu’, tarian yang diiringi dengan suara gendang. Tarian yang dimainkan dengan 12 gerakan dalam 1 gerakan berbeda-beda tetapi memiliki makna dan tujuan yang sama yakni merayakan kemenangan,” jawab Kelvin seraya terus menatap gadis-gadis yang menanpilkan tarian.
     “Tarian ini memberikan kesan dan makna terhadap nilai-nilai sosial bagi masyarakat Suku Toraja, tarian ini juga sebagai bentuk rasa syukur masyarakat Toraja”, tambahnya.
     Nathalia yang mendengar itu jiwa keingin tahuannya merasa tertantang dan ingin tahu lebih dalam tentang Tarian Pa’gellu’.
     “Apa maksud dari bentuk rasa syukur masyarakat Toraja dengan mengadakan tarian-tarian seperti itu?’, tanya Nathalia Kembali dengan rasa penasaran yang tinggi.
     Kelvin yang mendengar pertanyaan itu lagi-lagi tersenyum memperlihatkan lesung pipi yang tergambar jelas di pipi kanannya.
    </p>
    <p>
        “Suku Toraja yang dikenal oleh masyarakat luar dengan adat dan kebudayaan yang sangat kental. Meskipun sekarang sudah berada pada zaman modernisasi, tetapi masyarakat disini bisa mengimbangi kebudayaan itu. Masyarakat yang mengikuti perkembangan zaman namun mereka juga tidak meninggalkan kebudayaan sukunya. Nah, dahulunya masyarakat Toraja  memliki konflik antar daerah dimana setiap daerah saling berperang, tetapi masyarakat Toraja mampu melawan dan menang dari peperangan itu, hingga mereka mengadakan perayaan besar-besaran atas kemenangan yang telah diraih. Dalam perayaan itu mereka mengadakan suatu pertunjukan yaitu Tarian Pa’gellu’, tarian ini diciptakan oleh Nek Datu Bua’ sepulangnya dari medang peperangan”, jelas Kelvin pajang lebar.
Dari penjelasan Kelvin mebuat dirinya Paham mengapa kebudayaan Suku Toraja masih di anut dan dijaga hingga zaman moderen seperti ini serta ia memahami bahwa begitu penting menjaga kebudyaan lokal karena didalamnya terkandung makna yang begitu besar serta pengorbanan yang takkan pernah bisa terlupakan.
Disisi lain, Nathalia bingung mengapa sesorang yang secara tiba-tiba ini tahu semua terkait dengan semua hal yang menyangkut kebudayan Adat Suku Toraja. 
Kelvin yang peka dengan apa yang difikirkan oleh Nathalia segera menjawab,                                                               “Semua yang aku sampaikan tadi, itu semua dari pengetahuan ayahku. Beliau adalah Kepala Suku Toraja dan mencerikan semua hal yang aku tahu saat ini,” jawabnya.                                                                                          Kepala Suku adalah Ketua adat di Toraja atau yang biasa di sebut dengan Ambek Tondo’.
Nathalia yang mendengar itu, kini semakin paham dan rasa ingin mencoba tarian yang begitu mengagumkan itu. Namun disisi lain, ia merasa dirinya tidak pantas karena ia hanyalah gadis berdarah Toraja yang baru mengenal tentang kebudayaan Sukunya sendiri. Dalam hati Nathalia, ia sudah membayangkan bagaimana jika dirinya yang memainkan tarian itu, tetapi lagi-lagi ia patahkan dengan fikirannya sendiri. Apakah aku pantas?, Apakah aku bisa?, Aapakah orang-orang disini bisa menerimaku?. 
Itulah yang ada dalam fikiran Natahlia yang terlihat gundah becampur bingung dan ragu.                                                           Melihat ekspersi Nathalia, Kelvin menawarkan apakah ia mau mempelajari tarian itu.                                                       “Apakah kamu mau mempelajarinya?, aku bisa membantumu , aku tahu tempat latihan tarian disini”, tawar Kelvin.

    </p>
    <p>
        Mendengar itu, Nathalia yang masih bingung, takut, dan ragu terdiam beberapa saat, kemudian memberanikan diri menjawab.
“Aku mau, tapi aku ragu dan takut orang-orang disini tidak menyukaiku, karena aku hanyalah gadis pendatang. Meskipun aku terlahir dari keturunan Suku Toraja tetapi aku baru disini”, jawab Nathalia seraya menundukkan kepalanya dengan perasaan sedih. 
“Jangan takut, tidak ada seorangpun yang bisa tanpa mencoba dan berjuang, buang rasa takut itu yakinkan dalam diri kamu bahwa kamu mau dan kamu bisa”, jawab Kelvin memberikan semangat. 
Nathalia yang mendengar itu tersenyum dan meyakinkan dirinya bahwa ia mampu mencintai budayanya sendiri yang begitu menakjubkan serta memberikan makna dan pelajaran yang sangat mendalam, dan juga membangkitkan jiwa seninya.
Dari hari itu, Nathalia yang mulai sibuk dalam pelatihan Tarian Pa’gellu’ , di tempat yang direkomendasikan Kelvin tepatnya berada di Makale. Ia terus berusaha walaupun dalam latihannya, ia tidak mudah mempelajari semua gerakan-gerakan yang ada. Namun, agar ia bisa menjadi gadis Toraja yang pandai dalam dalam kesenian dan menjadi gadis Toraja yang mencintai budayanya sendiri dan mampu menghargai buaya lain, Nathalia terus berjuang dan tak pernah menyerah.
Hari-hari yang Nathalia lalui dengan latihan menari, hingga ia mampu dan lihai memperagakan Tarian Pa’gellu’. 
Dari kelihaiannya, ia diikut sertakan untuk menampilkan tarian dalam sebuah acara pernikahan anak dari Sekertaris desanya.
Di acara itu, Nathalia begitu menghayati tarian yang ia bawakan merasakan kehangatan yang belum pernah ia rasakan, merasakan kekuatan perjuangan yang sangat luar biasa. Di dalam hati ia berkata, mencintai kebudyaan sendiri dan menghargai kebudayaan orang lain adalah puncak seni tertinggi di dalam diri seseorang dan itu sudah ia dapatkan, serta mampu mengimbangkan kebudayaan dengan zaman modernisasi seperti sekarang ini.
Masyarakat yang menyaksika Nathalia membawakan Tarian Pa’gellu’ sebagai ciri khas Suku Toraja. Bagai terhipnotis dengan kecantikan dan kelihaian Nathalia, gerakan jari-jari Nathalia yang begitu lentur dan lentik menambah kesan seluruh masyarakat Toraja. Seluruh 
    </p>
    <p>
        masyarakat yang menyaksikan tenggelam dalam alunan gerakan Nathalia yang di padukan dengan suara gendang yang mendayu-dayu ditelinga. 
Disini Nathalia sadar bahwa tanpa berjuang dan terus meyakinkan dirinya bahwa ia mampu dan bisa ia takkan pernah sampai dititik ini. Begitupun dengan makna dari tarian Pa’gellu’ tanpa perjuangan dan ketangguhan serta keyakinan masyarakat Toraja tidak akan pernah tercipta yang namanya Tarian Pa’gellu’ sebagai Tarian Kebudayaan Suku Toraja. 

    </p>
</article>
<article>
    <style>
      p {
        text-align: center;
      }
    </style>
    <p>
      <strong><em>
        Serlia Turu Allo<br>
        Mahasiswa Aktif Universitas Sulawesi Barat<br>
        Program Studi Sistem Informasi<br>
        Fakultas Teknik<br>
        Pada Karya Ini Menang pada tahun 2024 Tingkat Universitas<br>
        Dengan Juara Harapan 1
      </em></strong>
    </p>
  </article>
  <nav>
    <a href="penulis2.html"display: inline-block; margin-top: 20px;">
      Selanjutnya → 
    </a>
  </nav>
  


</body>
</html>

