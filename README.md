<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Fundraising Website</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Campaigns</a></li>
        <li><a href="#">Donate</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section class="hero">
      <h1>Help Us Make a Difference</h1>
      <p>Join our fundraising efforts and support our cause.</p>
      <a href="#" class="btn">Donate Now</a>
    </section>

    <section class="about">
      <h2>About Our Fundraising</h2>
      <p>Learn more about our organization and the impact of our fundraising efforts.</p>
      <a href="#" class="btn">Read More</a>
    </section>

    <section class="campaigns">
      <h2>Our Current Campaigns</h2>
      <div class="campaign-list">
        <div class="campaign-card">
          <img src="campaign1.jpg" alt="Campaign 1">
          <h3>Campaign 1</h3>
          <p>Description of Campaign 1</p>
          <a href="#" class="btn">Donate</a>
        </div>
        <div class="campaign-card">
          <img src="campaign2.jpg" alt="Campaign 2">
          <h3>Campaign 2</h3>
          <p>Description of Campaign 2</p>
          <a href="#" class="btn">Donate</a>
        </div>
        <!-- Add more campaign cards as needed -->
      </div>
    </section>

    <section class="contact">
      <h2>Get in Touch</h2>
      <form>
        <input type="text" placeholder="Name" required>
        <input type="email" placeholder="Email" required>
        <textarea placeholder="Message" required></textarea>
        <button type="submit" class="btn">Submit</button>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2023 Fundraising Website. All rights reserved.</p>
  </footer>
/* Global Styles */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

/* Header and Navigation */
header {
  background-color: #333;
  color: #fff;
  padding: 20px;
}

nav ul {
  list-style-type: none;
  display: flex;
  justify-content: center;
  margin: 0;
  padding: 0;
}

nav li {
  margin: 0 10px;
}

nav a {
  color: #fff;
  text-decoration: none;
}

/* Main Content */
.hero, .about, .campaigns, .contact {
  padding: 50px;
  text-align: center;
}

.hero h1 {
  font-size: 36px;
  margin-bottom: 20px;
}

.btn {
  display: inline-block;
  background-color: #333;
  color: #fff;
  padding: 10px 20px;
  text-decoration: none;
  border-radius: 5px;
}

.campaign-list {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 20px;
}

.campaign-card {
  width: 300px;
  border: 1px solid #ccc;
  border-radius: 5px;
  overflow: hidden;
}

.campaign-card img {
  width: 100%;
  height: 200px;
  object-fit: cover;
}

.contact form {
  max-width: 400px;
  margin: 0 auto;
}

.contact input, .contact textarea {
  width: 100%;
  padding: 10px;
  margin-bottom: 20px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

/* Footer */
footer {
  background-color: #333;
  color: #fff;
  padding: 20px;
  text-align: center;
}

  <script src="script.js"></script>
</body>
</html>
