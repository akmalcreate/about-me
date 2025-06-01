# about-me
inilah cerita saya
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Profil Moch Akmal Almagribi</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background: #f4f4f4;
      color: #333;
    }
    header {
      background-color: #242424;
      color: white;
      padding: 30px 20px;
      text-align: center;
    }
    .about {
      padding: 20px;
      text-align: center;
    }
    .slider {
      display: flex;
      overflow: hidden;
      max-width: 100%;
      height: 400px;
      margin: 20px auto;
      position: relative;
    }
    .slider img {
      width: 100%;
      object-fit: cover;
      animation: slide 16s infinite;
    }
    @keyframes slide {
      0% {transform: translateX(0);}
      25% {transform: translateX(-100%);}
      50% {transform: translateX(-200%);}
      75% {transform: translateX(-300%);}
      100% {transform: translateX(0);}
    }
    .skills {
      padding: 20px;
      background: white;
      text-align: center;
    }
    audio {
      display: none;
    }
  </style>
</head>
<body>

  <header>
    <h1>Moch Akmal Almagribi</h1>
    <p>Mencintai Teknologi & Eksplorasi</p>
  </header>

  <section class="about">
    <h2>Tentang Saya</h2>
    <p>Lulusan Teknik Komputer dan Jaringan (TKJ) dari SMK Bina Profesi Bogor dengan keahlian dalam konfigurasi jaringan, instalasi perangkat komputer, serta penguasaan software perkantoran dasar. Teliti, cepat belajar, dan memiliki pengalaman kerja lapangan di bidang teknis dan administrasi. Tertarik untuk berkembang sebagai Network Engineer.</p>
  </section>

  <section class="slider">
    <img src="foto1.png" alt="foto1.png">
    <img src="foto2.png" alt="foto2.png">
    <img src="foto3.png" alt="foto3.png">
    <img src="foto4.png" alt="foto4.png">
  </section>

  <section class="skills">
    <h2>Keahlian Saya</h2>
    <ul style="list-style: none; padding: 0;">
      <li>✔️ Konfigurasi Jaringan</li>
      <li>✔️ Instalasi Perangkat Komputer</li>
      <li>✔️ Software Perkantoran (Word, Excel, dll)</li>
      <li>✔️ Administrasi Teknik</li>
    </ul>
  </section>

  <audio autoplay loop>
    <source src="musik.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
  </audio>

</body>
</html>
