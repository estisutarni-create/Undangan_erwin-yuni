<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Undangan Pernikahan Erwin & Yuni</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Poppins:wght@300;400&display=swap" rel="stylesheet">
<style>
body{
  margin:0;
  font-family:'Poppins',sans-serif;
  background:#f5efe6;
  color:#5c4b3b;
  text-align:center;
}
section{
  padding:60px 20px;
}
.cover{
  height:100vh;
  display:flex;
  flex-direction:column;
  justify-content:center;
  align-items:center;
  background:#efe6d8;
}
.cover h1{
  font-family:'Playfair Display',serif;
  font-size:42px;
  margin:10px 0;
}
.cover h2{
  font-weight:300;
}
.btn{
  margin-top:20px;
  padding:12px 24px;
  border:none;
  background:#c8b6a6;
  color:white;
  border-radius:30px;
  font-size:16px;
}
.card{
  background:white;
  max-width:500px;
  margin:auto;
  padding:30px;
  border-radius:12px;
  box-shadow:0 10px 30px rgba(0,0,0,0.05);
}
h2{
  font-family:'Playfair Display',serif;
}
.maps-btn{
  display:inline-block;
  margin-top:15px;
  padding:12px 22px;
  background:#c8b6a6;
  color:white;
  border-radius:25px;
  text-decoration:none;
}
footer{
  padding:30px;
  font-size:14px;
}
</style>
</head>
<body>

<section class="cover">
  <h2>Undangan Pernikahan</h2>
  <h1>Erwin Pandu Wardana</h1>
  <h2>&</h2>
  <h1>Yuni Purwati</h1>
  <p>29 Mei 2026</p>
  <button class="btn" onclick="document.getElementById('acara').scrollIntoView({behavior:'smooth'})">Lihat Undangan</button>
</section>

<section>
  <div class="card">
  <h2>Dengan Hormat</h2>
  <p>Kami mengundang Bapak/Ibu/Saudara/i untuk menghadiri acara pernikahan kami.</p>
  </div>
</section>

<section id="acara">
  <div class="card">
  <h2>Akad Nikah</h2>
  <p>Jumat, 29 Mei 2026</p>
  <p>08.00 WIB</p>
  </div>
</section>

<section>
  <div class="card">
  <h2>Resepsi</h2>
  <p>Jumat, 29 Mei 2026</p>
  <p>10.00 WIB</p>
  </div>
</section>

<section>
  <div class="card">
  <h2>Lokasi Acara</h2>
  <p>Jl. Jeruk Manis RT 2/1<br>Kedawung, Kroya</p>
  <a class="maps-btn" href="https://maps.app.goo.gl/5soKb2CHy6sVmqFCA" target="_blank">Buka Google Maps</a>
  </div>
</section>

<section>
  <div class="card">
  <h2>Terima Kasih</h2>
  <p>Merupakan suatu kehormatan bagi kami apabila Bapak/Ibu/Saudara/i berkenan hadir dan memberikan doa restu.</p>
  </div>
</section>

<footer>
  <p>Erwin & Yuni - 2026</p>
</footer>

</body>
</html>
