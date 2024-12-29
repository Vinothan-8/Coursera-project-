# Coursera-project-

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Travel Recommendation Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
      background-color: #f4f4f4;
    }

    nav {
      background: #333;
      color: white;
      padding: 10px 0;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      margin: 0;
      padding: 0;
    }

    nav ul li {
      margin: 0 15px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      padding: 8px 15px;
    }

    nav ul li a:hover {
      background: #575757;
      border-radius: 5px;
    }

    section {
      padding: 20px;
      max-width: 900px;
      margin: 20px auto;
      background: white;
      border-radius: 5px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }

    h1, h2 {
      text-align: center;
    }

    img {
      max-width: 100%;
      height: auto;
      display: block;
      margin: 10px 0;
      border-radius: 5px;
    }

    form label {
      display: block;
      margin: 10px 0 5px;
    }

    form input, form button {
      width: 100%;
      padding: 10px;
      margin-bottom: 10px;
      border: 1px solid #ddd;
      border-radius: 5px;
    }

    form button {
      background: #333;
      color: white;
      cursor: pointer;
    }

    form button:hover {
      background: #575757;
    }

    .recommendations img {
      width: 48%;
      margin: 1%;
    }

    .recommendations {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
    }
  </style>
</head>
<body>

  <!-- Navigation Bar -->
  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About Us</a></li>
      <li><a href="#contact">Contact Us</a></li>
    </ul>
  </nav>

  <!-- Home Section -->
  <section id="home">
    <h1>Welcome to Our Travel Recommendation Website</h1>
    <p>Discover the best destinations around the world, from serene beaches to historic temples and vibrant cities.</p>

    <h2>Beach Recommendations</h2>
    <div class="recommendations">
      <div>
        <img src="beach1.jpg" alt="Beach 1">
        <p>Sunset Beach</p>
      </div>
      <div>
        <img src="beach2.jpg" alt="Beach 2">
        <p>Crystal Cove</p>
      </div>
    </div>

    <h2>Temple Recommendations</h2>
    <div class="recommendations">
      <div>
        <img src="temple1.jpg" alt="Temple 1">
        <p>Ancient Pagoda</p>
      </div>
      <div>
        <img src="temple2.jpg" alt="Temple 2">
        <p>Sacred Shrine</p>
      </div>
    </div>

    <h2>Recommendations by Country</h2>
    <div class="recommendations">
      <div>
        <img src="country1.jpg" alt="Country 1">
        <p>Explore Japan</p>
      </div>
      <div>
        <img src="country2.jpg" alt="Country 2">
        <p>Discover Italy</p>
      </div>
    </div>
  </section>

  <!-- About Us Section -->
  <section id="about">
    <h2>About Us</h2>
    <p>We are passionate about helping travelers discover the most breathtaking destinations around the world. Whether you are looking for adventure, relaxation, or cultural experiences, we've got you covered.</p>
  </section>

  <!-- Contact Us Section -->
  <section id="contact">
    <h2>Contact Us</h2>
    <form id="contactForm">
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>
      
      <label for="message">Message:</label>
      <textarea id="message" name="message" required></textarea>
      
      <button type="submit">Submit</button>
    </form>
  </section>

  <script>
    // Form submission handling
    document.getElementById('contactForm').addEventListener('submit', function(event) {
      event.preventDefault();
      alert('Thank you for reaching out! We will get back to you soon.');
    });
  </script>

</body>
</html>
