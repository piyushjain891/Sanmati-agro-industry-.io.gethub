<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sanmati Agro Industry</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>
body {
  margin: 0;
  font-family: 'Poppins', sans-serif;
  background: #f8fafc;
  color: #1e293b;
}

/* NAVBAR */
nav {
  display: flex;
  justify-content: space-between;
  padding: 15px 40px;
  background: white;
  box-shadow: 0 2px 10px rgba(0,0,0,0.05);
  position: sticky;
  top: 0;
}

nav h2 {
  margin: 0;
}

nav a {
  text-decoration: none;
  margin-left: 20px;
  color: #1e293b;
  font-weight: 500;
}

/* HERO */
.hero {
  height: 80vh;
  background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)),
              url('https://images.unsplash.com/photo-tractor');
  background-size: cover;
  background-position: center;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  color: white;
}

.hero h1 {
  font-size: 40px;
}

.hero p {
  margin-top: 10px;
}

/* SECTION */
section {
  padding: 60px 40px;
  max-width: 1100px;
  margin: auto;
}

h2 {
  text-align: center;
  margin-bottom: 30px;
}

/* PRODUCTS */
.products {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px,1fr));
  gap: 25px;
}

.card {
  background: white;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 5px 15px rgba(0,0,0,0.05);
  transition: 0.3s;
}

.card:hover {
  transform: translateY(-5px);
}

.card img {
  width: 100%;
  height: 180px;
  object-fit: cover;
}

.card h3 {
  padding: 10px;
}

.card p {
  padding: 0 10px 15px;
  font-size: 14px;
}

/* CONTACT */
.contact {
  text-align: center;
}

/* FOOTER */
footer {
  background: #0f172a;
  color: white;
  text-align: center;
  padding: 15px;
}
</style>
</head>

<body>

<nav>
  <h2>Sanmati Agro</h2>
  <div>
    <a href="#about">About</a>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
  </div>
</nav>

<div class="hero">
  <div>
    <h1>Sanmati Agro Industry</h1>
    <p>Strong. Reliable. Built for Farmers.</p>
  </div>
</div>

<section id="about">
  <h2>About Us</h2>
  <p>
    Sanmati Agro Industry manufactures high-quality tractor accessories including hitch, bumpers, and other essential parts. 
    We focus on durability, performance, and trust for every farmer.
  </p>
</section>

<section id="products">
  <h2>Our Products</h2>
  <div class="products">

    <div class="card">
      <img src="https://via.placeholder.com/400" alt="">
      <h3>Tractor Hitch</h3>
      <p>Durable and high-strength hitch for all tractors.</p>
    </div>

    <div class="card">
      <img src="https://via.placeholder.com/400" alt="">
      <h3>Tractor Bumper</h3>
      <p>Heavy-duty bumper for protection and long life.</p>
    </div>

    <div class="card">
      <img src="https://via.placeholder.com/400" alt="">
      <h3>Accessories</h3>
      <p>Complete range of tractor accessories available.</p>
    </div>

  </div>
</section>

<section id="contact" class="contact">
  <h2>Contact Us</h2>
  <p><strong>Owner:</strong> Ankur Jain</p>
  <p><strong>Phone:</strong> +91 9897073003</p>
</section>

<footer>
  <p>© 2026 Sanmati Agro Industry</p>
</footer>

</body>
</html>
