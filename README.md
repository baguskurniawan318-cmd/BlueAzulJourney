<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Blue Azul Journey</title>

<link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;600&family=Poppins:wght@300;400&display=swap" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
}

body{
font-family:'Poppins',sans-serif;
background:linear-gradient(180deg,#0b132b,#1c2541,#3a506b);
color:white;
overflow-x:hidden;
}

.hero{
height:100vh;
background:
linear-gradient(rgba(0,0,0,.5),rgba(0,0,0,.7)),
url('cover.jpg');
background-size:cover;
background-position:center;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
}

.hero h1{
font-family:'Cinzel',serif;
font-size:5rem;
letter-spacing:5px;
color:silver;
text-shadow:0 0 20px rgba(255,255,255,.4);
}

.hero h2{
font-weight:300;
margin-top:10px;
}

.moon{
position:absolute;
top:80px;
right:100px;
width:150px;
height:150px;
border-radius:50%;
background:#f5f5f5;
box-shadow:0 0 60px white;
opacity:.8;
}

.quote{
padding:80px 20px;
text-align:center;
font-size:1.4rem;
font-style:italic;
max-width:800px;
margin:auto;
}

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:20px;
padding:50px;
}

.gallery img{
width:100%;
height:350px;
object-fit:cover;
border-radius:15px;
transition:.5s;
box-shadow:0 0 20px rgba(255,255,255,.1);
}

.gallery img:hover{
transform:scale(1.05);
}

.story{
padding:80px 10%;
line-height:2;
text-align:center;
}

.story h2{
font-family:'Cinzel',serif;
margin-bottom:20px;
color:silver;
}

footer{
text-align:center;
padding:40px;
background:#050816;
}

footer h3{
font-family:'Cinzel',serif;
color:silver;
}
</style>
</head>

<body>

<div class="moon"></div>

<section class="hero">
<h1>BLUE AZUL</h1>
<h2>Vespa Super 1975</h2>
</section>

<section class="quote">
"Setiap kilometer menyimpan cerita,
setiap perjalanan menghadirkan makna."
</section>

<section class="story">
<h2>Blue Azul Journey</h2>
<p>
Blue Azul bukan sekadar Vespa Super 1975.
Ia adalah sahabat perjalanan yang menemani
setiap petualangan, menyusuri jalan-jalan hutan,
pantai, pegunungan, dan kisah yang tak terlupakan.
</p>
</section>

<section class="gallery">
<img src="foto1.jpg">
<img src="foto2.jpg">
<img src="foto3.jpg">
<img src="foto4.jpg">
</section>

<footer>
<h3>Blue Azul • Since 1975</h3>
<p>Ride Slow, Live Fully</p>
</footer>

</body>
</html>
