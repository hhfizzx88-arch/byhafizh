```
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>The Wedding Of Zeen & Rahmah</title>
<link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;600&family=Poppins:wght@300;400;500&display=swap" rel="stylesheet">
<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
}

body{
font-family:'Poppins',sans-serif;
background:#0f0f0f;
color:white;
line-height:1.8;
}

.hero{
height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
padding:20px;
background:linear-gradient(rgba(0,0,0,.65),rgba(0,0,0,.65)),
url('https://images.unsplash.com/photo-1519741497674-611481863552?q=80&w=1400');
background-size:cover;
background-position:center;
}

.hero h1{
font-size:18px;
letter-spacing:5px;
}

.hero h2{
font-family:'Cinzel',serif;
font-size:48px;
color:#d4af37;
margin:20px 0;
}

.hero p{
font-size:18px;
}

.section{
padding:70px 20px;
}

.card{
max-width:850px;
margin:auto;
background:#181818;
padding:35px;
border-radius:20px;
box-shadow:0 0 20px rgba(212,175,55,.15);
}

h2{
color:#d4af37;
margin-bottom:20px;
}

.arab{
font-size:28px;
line-height:2;
}

.countdown{
display:flex;
justify-content:center;
gap:15px;
flex-wrap:wrap;
margin-top:25px;
}

.box{
background:#222;
padding:15px;
width:90px;
border-radius:15px;
}

.box span{
display:block;
font-size:28px;
font-weight:bold;
color:#d4af37;
}

.btn{
display:inline-block;
margin-top:25px;
padding:12px 30px;
background:#d4af37;
color:black;
text-decoration:none;
border-radius:30px;
font-weight:bold;
}

footer{
padding:40px;
text-align:center;
color:#999;
}
</style>
</head>
<body>
<section class="hero">
<h1>THE WEDDING OF</h1>
<h2>MUHAMMAD ZEEN AL HADDAD<br>&<br>SITI RAHMAH</h2>
<p>21 Juni 2026 • 09.00 WITA</p>
</section>
<section class="section">
<div class="card">
<div class="arab">
بِسْمِ اللّٰهِ الرَّحْمٰنِ الرَّحِيْمِ
</div>
<br>
<div class="arab" style="font-size:22px;">
اَلسَّلَامُ عَلَيْكُمْ وَرَحْمَةُ اللّٰهِ وَبَرَكَاتُهُ
</div>
<br>
<p>
Dengan memohon rahmat, ridha, dan keberkahan Allah Subhanahu Wa Ta'ala,
kami bermaksud menyelenggarakan akad dan walimatul 'ursy putra-putri kami.
</p>
<br>
<p>
"Maha Suci Allah yang telah menciptakan makhluk-Nya berpasang-pasangan.
Semoga ikatan suci ini menjadi jalan menuju keluarga yang sakinah,
mawaddah, wa rahmah."
</p>
<br>
<p class="arab" style="font-size:20px;">
وَمِنْ آيَاتِهِ أَنْ خَلَقَ لَكُمْ مِنْ أَنْفُسِكُمْ أَزْوَاجًا لِتَسْكُنُوا إِلَيْهَا وَجَعَلَ بَيْنَكُمْ مَوَدَّةً وَرَحْمَةً
</p>
<p>
(QS. Ar-Rum: 21)
</p>
<br>
<p>
Merupakan suatu kehormatan dan kebahagiaan bagi kami apabila
Bapak/Ibu/Saudara/i berkenan hadir serta memberikan doa restu kepada kedua mempelai.
</p>
<br>
<p>
Jazakumullahu Khairan Katsiran atas kehadiran dan doa yang diberikan.
</p>
</div>
</section>
<section class="section">
<div class="card">
<h2>Hitung Mundur Acara</h2>
<div class="countdown">
<div class="box"><span id="days">0</span>Hari</div>
<div class="box"><span id="hours">0</span>Jam</div>
<div class="box"><span id="minutes">0</span>Menit</div>
<div class="box"><span id="seconds">0</span>Detik</div>
</div>
</div>
</section>
<section class="section">
<div class="card">
<h2>Detail Acara</h2>
<p><strong>Tanggal:</strong> 21 Juni 2026</p>
<p><strong>Waktu:</strong> 09.00 WITA</p>
<br>
<p><strong>Mempelai Pria</strong></p>
<p>Muhammad Zeen Al Haddad</p>
<br>
<p><strong>Mempelai Wanita</strong></p>
<p>Siti Rahmah</p>
<p>Putri dari Bapak Sakrani & Ibu Salbiah</p>
<a class="btn" href="https://maps.app.goo.gl/Abvqd26crx1HEBmLA?g_st=ic" target="_blank">
Lihat Lokasi
</a>
</div>
</section>
<footer>
Made With ❤️ For Zeen & Rahmah
</footer>
<script>
const targetDate = new Date("June 21, 2026 09:00:00").getTime();

setInterval(() => {
const now = new Date().getTime();
const distance = targetDate - now;

document.getElementById("days").innerHTML =
Math.floor(distance/(1000*60*60*24));

document.getElementById("hours").innerHTML =
Math.floor((distance%(1000*60*60*24))/(1000*60*60));

document.getElementById("minutes").innerHTML =
Math.floor((distance%(1000*60*60))/(1000*60));

document.getElementById("sec

```
