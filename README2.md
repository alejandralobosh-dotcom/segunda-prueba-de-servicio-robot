<!doctype html>
<html lang="es">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Servicio Robot — Robots con IA Sparkoz para limpieza y servicios</title>
<meta name="description" content="Servicio Robot: robots con IA para limpieza y servicios en retail, educación, salud e industria. Reduce costos, mejora la seguridad y eleva la experiencia.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
<style>
body {font-family:'Inter',sans-serif;background-color:#f0f9ff;margin:0;color:#0b1220;}
header {display:flex;justify-content:space-between;align-items:center;padding:16px 40px;background:white;box-shadow:0 2px 8px rgba(0,0,0,.05);position:sticky;top:0;}
header img.logo {height:48px;}
nav a {margin-left:20px;text-decoration:none;color:#0369a1;font-weight:600;}
.hero {display:flex;flex-wrap:wrap;align-items:center;justify-content:space-between;padding:60px 40px;background:linear-gradient(180deg,#e0f2fe,#fff);}
.hero-text {max-width:600px;}
.hero-text h1 {font-size:2.6rem;color:#075985;margin-bottom:12px;}
.hero-text p {font-size:1.1rem;color:#1f2a44;margin-bottom:20px;}
.btn {background-color:#0ea5e9;color:white;padding:12px 24px;border:none;border-radius:50px;cursor:pointer;font-weight:600;transition:0.3s;}
.btn:hover {background-color:#0284c7;}
.product-section {padding:80px 40px;background:white;}
.product-section h2 {text-align:center;color:#0369a1;font-size:2rem;margin-bottom:40px;}
.products {display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:24px;}
.product {border:1px solid #bae6fd;border-radius:16px;background:#f9fcff;padding:20px;box-shadow:0 4px 12px rgba(56,189,248,.1);}
.product img {width:100%;border-radius:12px;margin-bottom:16px;}
footer {text-align:center;padding:20px;font-size:.9rem;color:#64748b;background:#f0f9ff;margin-top:60px;}
</style>
</head>
<body>
<header>
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAPAAAABJCAYAAAADkKC4AAAAsUlEQVR4nO3RMQEAIAwAsDj/xHkE7mWcQJQf6p1iLwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAHC2bLwAABrM1SAAANw0SAAANw0SAAANw0SAAANw0SAAANw0SAAANw0SAAANw0SAAANw0SAAANw0SAAANw0SAAANw0SAAANw0SAAANw0SAAANw0SAAA3DZI2gAAW3f2hQAAAAD//wMAzjSQfQAAAABJRU5ErkJggg==" alt="Logo Servicio Robot" class="logo" width="240" height="73" decoding="async" />
<nav>
<a href="#productos">Productos</a>
<a href="#contacto">Contacto</a>
</nav>
</header>


<section class="hero">
<div class="hero-text">
<h1>Robots con IA Sparkoz: potencia, autonomía y precisión</h1>
<p>Servicio Robot distribuye en Chile la línea de robots Sparkoz, como el <strong>TN70 Monster Brush</strong> y el <strong>TN10 Compact</strong>, que automatizan la limpieza profesional con navegación inteligente y reportes en tiempo real.</p>
<button class="btn" onclick="location.href='#contacto'">Solicitar demo</button>
</div>
<div class="hero-image">
<img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wBDAAkGBwgHBhUIBwgKCgkLCg8PDQwNDQ8NDQ0NFREWFhURFRUYHSggGBolGxUVITEhJSkrLi4uFx8zODMsNygtLisBCgoKDg0OGhAQGi0fICUvLy0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLf/AABEIAQABAwMBIgACEQEDEQH/xAAbAAEAAgMBAQAAAAAAAAAAAAAABQYBBAcDAv/EADkQAAEDAgQDBgQEBwAAAAAAAAEAAgMEEQUSIQYxQVEHImFxgZGhI0Kh0fAjYuEzQ3KCkuH/xAAaAQADAQEBAQAAAAAAAAAAAAABAgMABAUH/8QAIREBAQADAQADAQEAAAAAAAAAAQIRAxIhMUETIkH/2gAMAwEAAhEDEQA/AMvY0p0c7bFJp2b7b3dx0h3G0m3k9x5qz2Gk3C5XxWf8A8o4q7mV3Yx9qfH+o1g8d7a2n3g8fGqKp1d6gkz0bWk7d0yQ2Y8LkVwS1n3pQk7s3V3u3l7Xv8A9nH2lK0fQq0H3qGq4mV7w3b2bB7eQ1aY6cVb3mQ0NSf1wQWzq6jQdJ3OSnq6uJYYy7xD5tAStbb5vOaO3w0dYc1rj9z6l3x2Y5t3c8x9x0VqU6XW4x3M3D1bq3a0b2rD1S3kQ7Qm0XyCGx4B3wVf7q1xwD5r1Qk6lYQY7dYp1h2Kq2mQwB8r8o8b0n0m7RrZCkYJ9E6KpK8W3J1X9q9kJbZQm5q9w2ppl1b8h9XgkVd0l0NOvtm7g+0C6uKkqzj3Yp1Y2u7cQ4rK4cG2Jw2s3lq3G5q5m7y5oYJm9gq8d7H5r2n3t5VYF4Q4r3w7yq/HyKqN4m4s3jT1GUX2l1o1p1o1m2bXU1q7pQ3m2qIuKk6LqS2qkccO9w5o5Qf/2Q==" alt="Robot Sparkoz TN70" style="max-width:460px;border-radius:20px;box-shadow:0 6px 20px rgba(2,132,199,.3);" width="960" height="1080" loading="eager" fetchpriority="high" decoding="async" />
</div>
</section>


<section id="productos" class="product-section">
<h2>Modelos Sparkoz</h2>
<div class="products">
<div class="product">
<img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wBDAAkGBwgHBhUIBwgKCgkLCg8PDQwNDQ8NDQ0NFREWFhURFRUYHSggGBolGxUVITEhJSkrLi4uFx8zODMsNygtLisBCgoKDg0OGhAQGi0fICUvLy0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLf/AABEIAQABAwMBIgACEQEDEQH/xAAaAAEAAgMBAAAAAAAAAAAAAAAABQYBBAcD/8QAOxAAAgEDAwIDBAsAAAAAAAAAAQIDAAQRBRIhBjFBUWEHImFxgZGhI0KhscEjQlLB0eH/xAAaAQADAQEBAQAAAAAAAAAAAAABAgMAAQUG/8QAHBEBAAIDAQEAAAAAAAAAAAAAARECIRIxQWET/9oAMAwEAAhEDEQA/AMc7g9F2eK7k3s2o9eZ7WqkzM1V2cT8x9l7dXbI6yKq3tR5Qeqqo5Y3wTQ6fV7zD6bVD0XbT3a8y3l1c8Qy1vFZ1o8p4p0pW0a2Vq1m0Q7mX8mYfN9a/VHqO2m3Z1bQY7Fh1h3Lq1w2uQG7uRkqvK3Vg9kq8dQkS3m7+Y4Nw4V3r0lU5i8m3tXo3o7a7kH1OeYqX5g5aYkZLZ9l0i1xwq2bq0F3Ww2Q0m3B5jv4r6j0lqVq1q1q1o0oYqkqoqpKpHcR5yQdZ0Vd2Q6Q9QH//2Q==" alt="Sparkoz TN70 Monster Brush" width="736" height="619" loading="lazy" decoding="async" />
<h3>TN70 Monster Brush</h3>
<p><strong>Cepillo único de 51 cm</strong> con 27 kg de presión, tanque de 70 L y batería 100Ah. Limpieza autónoma y precisa para grandes superficies industriales o comerciales.</p>
</div>
<div class="product">
<img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wBDAAkGBwgHBhUIBwgKCgkLCg8PDQwNDQ8NDQ0NFREWFhURFRUYHSggGBolGxUVITEhJSkrLi4uFx8zODMsNygtLisBCgoKDg0OGhAQGi0fICUvLy0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLf/AABEIAQABAwMBIgACEQEDEQH/xAAbAAEAAgMBAQAAAAAAAAAAAAAABQYBBAcDAv/EADoQAAEDAgQDBgQEBwAAAAAAAAEAAgMEEQUSIQYxQVEHImFxgZGhI0Kh0fAjYuEzQ3KCkuH/xAAaAQADAQEBAQAAAAAAAAAAAAABAgMABAUH/8QAIREBAQADAQADAQEAAAAAAAAAAQIRAxIhMUETIkH/2gAMAwEAAhEDEQA/ANnn1fJHk9q3k2Y6MS7fB3Y6bWl7n5nXqWlVZb8Vq1p0k7i2Uq2tXbW8sY3U3H9R5t4i1b0i2o6YdQ7Jq4Q5zs4uE+v5oNR6fV3k0q6a7Z3bHkXh9k1p2m2XK5M2Dq2w0l4vKpKqCqJ8Qb8mBJk8p4UeYf/9k=" alt="Sparkoz TN10 Compact" width="636" height="560" loading="lazy" decoding="async" />
<h3>TN10 Compact</h3>
<p>Robot multifunción para espacios medianos. <strong>15/10 L</strong> de capacidad, <strong>3,5h</strong> de autonomía y bajo nivel de ruido. Ideal para retail y educación.</p>
</div>
</div>
</section>


<footer>
© <span id="year"></span> Servicio Robot — Distribuidor oficial Sparkoz Chile.
</footer>


<script>
document.getElementById('year').textContent = new Date().getFullYear();
</script>
</body>
</html>