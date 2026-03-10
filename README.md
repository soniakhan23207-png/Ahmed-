<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday Bro</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family: 'Segoe UI', sans-serif;
}

body{
background:#0f172a;
color:white;
text-align:center;
}

/* HERO SECTION */

.hero{
height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
background:linear-gradient(135deg,#6366f1,#9333ea);
padding:20px;
}

.hero h1{
font-size:48px;
margin-bottom:10px;
animation:fadeIn 2s ease;
}

.hero p{
font-size:18px;
opacity:0.9;
animation:fadeIn 3s ease;
}

/* GALLERY */

.gallery{
padding:60px 20px;
}

.gallery h2{
margin-bottom:30px;
font-size:32px;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
gap:15px;
max-width:900px;
margin:auto;
}

.grid img{
width:100%;
height:220px;
object-fit:cover;
border-radius:12px;
transition:0.4s;
}

.grid img:hover{
transform:scale(1.05);
}

/* NOTE */

.note{
background:#1e293b;
padding:60px 20px;
}

.note h2{
font-size:30px;
margin-bottom:20px;
}

.note p{
max-width:600px;
margin:auto;
line-height:1.7;
font-size:18px;
}

/* FOOTER */

footer{
padding:20px;
font-size:14px;
opacity:0.7;
}

/* ANIMATION */

@keyframes fadeIn{
from{
opacity:0;
transform:translateY(20px);
}
to{
opacity:1;
transform:translateY(0);
}
}

</style>
</head>

<body>

<section class="hero">
<h1>Happy Birthday Brother 🎂</h1>
<p>A small corner of the internet for our memories</p>
</section>

<section class="gallery">
<h2>Our Memories</h2>

<div class="grid">
<img src="photo1.jpg">
<img src="photo2.jpg">
<img src="photo3.jpg">
<img src="photo4.jpg">
<img src="photo5.jpg">
<img src="photo6.jpg">
</div>

</section>

<section class="note">

<h2>A Note For You</h2>

<p>
Bro, life gave me many friends but very few brothers,
and you are one of them.  
Every photo here is a reminder of the crazy,
funny and unforgettable moments we shared.  

No matter where life takes us,
these memories will always stay special.  

Happy Birthday once again.  
More memories are waiting for us.
</p>

</section>

<footer>
Made with brotherhood ❤️
</footer>

</body>
</html>
