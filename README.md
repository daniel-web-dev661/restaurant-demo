<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Delicious Bites Restaurant</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: Arial, sans-serif;
}

body{
    background:#111;
    color:white;
}

header{
    background:#000;
    padding:20px;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

header h1{
    color:#f39c12;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:20px;
}

.hero{
    height:90vh;
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    text-align:center;
    background:linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)),
    url('https://images.unsplash.com/photo-1555992336-03a23c7b20ee');
    background-size:cover;
    background-position:center;
}

.hero h2{
    font-size:3rem;
}

.hero button{
    margin-top:20px;
    padding:12px 25px;
    border:none;
    background:#f39c12;
    color:black;
    font-weight:bold;
    cursor:pointer;
    border-radius:5px;
}

.section{
    padding:60px 20px;
    text-align:center;
}

.menu-items{
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
    gap:20px;
    margin-top:30px;
}

.card{
    background:#222;
    padding:20px;
    width:250px;
    border-radius:10px;
}

.card h3{
    color:#f39c12;
}

.whatsapp{
    position:fixed;
    bottom:20px;
    right:20px;
    background:#25D366;
    color:white;
    padding:15px;
    border-radius:50%;
    text-decoration:none;
    font-weight:bold;
}

@media(max-width:768px){
    .hero h2{
        font-size:2rem;
    }
}
</style>
</head>

<body>

<header>
    <h1>Delicious Bites</h1>
    <nav>
        <a href="#">Home</a>
        <a href="#">Menu</a>
        <a href="#">Contact</a>
    </nav>
</header>

<section class="hero">
    <h2>Fresh. Hot. Delicious.</h2>
    <p>Order the best meals in town.</p>
    <button>View Menu</button>
</section>

<section class="section">
    <h2>Our Popular Meals</h2>
    <div class="menu-items">
        <div class="card">
            <h3>Burger & Fries</h3>
            <p>R89</p>
        </div>
        <div class="card">
            <h3>Grilled Chicken</h3>
            <p>R110</p>
        </div>
        <div class="card">
            <h3>Pizza Special</h3>
            <p>R120</p>
        </div>
    </div>
</section>

<section class="section">
    <h2>Contact Us</h2>
    <p>Call: 071 234 5678</p>
    <p>Location: Johannesburg, South Africa</p>
</section>

<a href="https://wa.me/27712345678" class="whatsapp">WA</a>

</body>
</html>