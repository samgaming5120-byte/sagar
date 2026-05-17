<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Sagar Singh Official Website</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#0f172a;
    color:white;
}

header{
    background:#111827;
    padding:20px;
    text-align:center;
    border-bottom:3px solid cyan;
}

header h1{
    font-size:45px;
    color:cyan;
}

nav{
    margin-top:15px;
}

nav a{
    color:white;
    text-decoration:none;
    margin:15px;
    font-size:18px;
}

.hero{
    height:500px;
    display:flex;
    justify-content:center;
    align-items:center;
    flex-direction:column;
    background:linear-gradient(to right,#1e3a8a,#0f172a);
}

.hero h2{
    font-size:55px;
    margin-bottom:20px;
}

.hero p{
    font-size:22px;
    width:70%;
    text-align:center;
}

.btn{
    margin-top:30px;
    padding:15px 40px;
    background:cyan;
    color:black;
    border:none;
    border-radius:10px;
    font-size:20px;
    cursor:pointer;
    transition:0.3s;
}

.btn:hover{
    background:white;
    transform:scale(1.1);
}

.section{
    padding:80px 50px;
}

.section h2{
    text-align:center;
    font-size:40px;
    margin-bottom:50px;
    color:cyan;
}

.cards{
    display:flex;
    justify-content:center;
    gap:30px;
    flex-wrap:wrap;
}

.card{
    background:#1e293b;
    width:300px;
    padding:25px;
    border-radius:20px;
    transition:0.4s;
    box-shadow:0 0 15px rgba(0,255,255,0.3);
}

.card:hover{
    transform:translateY(-10px);
}

.card h3{
    margin-bottom:15px;
    color:cyan;
}

.gallery{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.gallery div{
    background:#334155;
    height:200px;
    border-radius:15px;
    display:flex;
    align-items:center;
    justify-content:center;
    font-size:25px;
}

.contact{
    text-align:center;
}

input, textarea{
    width:70%;
    padding:15px;
    margin:10px;
    border:none;
    border-radius:10px;
}

footer{
    background:#111827;
    text-align:center;
    padding:30px;
    margin-top:40px;
    border-top:3px solid cyan;
}

</style>
</head>

<body>

<header>
    <h1>🔥 SAGAR SINGH 🔥</h1>

    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Skills</a>
        <a href="#">Gallery</a>
        <a href="#">Contact</a>
    </nav>
</header>

<section class="hero">

    <h2>Welcome To My Website 😎</h2>

    <p>
        Ye ek stylish HTML + CSS website hai.
        Isme animation, cards, gallery aur contact form sab hai.
    </p>

    <button class="btn">Explore Now</button>

</section>

<section class="section">

    <h2>💻 My Skills</h2>

    <div class="cards">

        <div class="card">
            <h3>HTML</h3>
            <p>
                Website structure banane ke liye use hota hai.
            </p>
        </div>

        <div class="card">
            <h3>CSS</h3>
            <p>
                Website ko stylish aur attractive banata hai.
            </p>
        </div>

        <div class="card">
            <h3>JavaScript</h3>
            <p>
                Website me functionality add karta hai.
            </p>
        </div>

    </div>

</section>

<section class="section">

    <h2>🖼 Gallery</h2>

    <div class="gallery">

        <div>Image 1</div>
        <div>Image 2</div>
        <div>Image 3</div>
        <div>Image 4</div>
        <div>Image 5</div>
        <div>Image 6</div>

    </div>

</section>

<section class="section contact">

    <h2>📞 Contact Me</h2>

    <input type="text" placeholder="Enter Your Name">

    <br>

    <input type="email" placeholder="Enter Your Email">

    <br>

    <textarea rows="6" placeholder="Write Message"></textarea>

    <br>

    <button class="btn">Send Message</button>

</section>

<footer>

    <h3>© 2026 Sagar Singh | All Rights Reserved</h3>

</footer>

</body>
</html>
