# V4U-Website
V4U is a website that bridges the gap between people who aspire to practice their passion and the experts in their domain. 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>V4U – We For You</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <h1>V4U – We For You</h1>
</header>

<nav>
  <a href="V4U.html">Home</a>
  <a href="music.html">Music</a>
  <a href="dance.html">Dance</a>
  <a href="yoga.html">Yoga</a>
  <a href="fitness.html">Fitness</a>
  <a href="meditation.html">Meditation</a>
</nav>

<section>
  <h2>Our Mission</h2>
  <p>To empower individuals in their pursuit of passion by connecting them with expert facilitators across music, dance, yoga, fitness, and meditation.</p>

  <h2>Services</h2>
  <p>We provide access to skilled facilitators who guide clients with personalized attention in the domains they are passionate about.</p>

  <div class="services">
    <div class="facilitator-list">
      <div class="facilitator"><h3>Music</h3><a href="music.html">Explore</a></div>
      <div class="facilitator"><h3>Dance</h3><a href="dance.html">Explore</a></div>
      <div class="facilitator"><h3>Yoga</h3><a href="yoga.html">Explore</a></div>
      <div class="facilitator"><h3>Fitness</h3><a href="fitness.html">Explore</a></div>
      <div class="facilitator"><h3>Meditation</h3><a href="meditation.html">Explore</a></div>
    </div>
  </div>

  <h2>About Us</h2>
  <p>We are here to help people build their passion by providing them the contacts of experts in each domain.</p>
</section>

<footer>
  <p>Contact Us: info@v4u.com | +91 98765 43210</p>
  <p>&copy; 2025 V4U – We For You</p>
</footer>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Music Facilitators</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <h1>Music Facilitators</h1>
</header>

<nav>
  <a href="V4U.html">Home</a>
  <a href="music.html">Music</a>
  <a href="dance.html">Dance</a>
  <a href="yoga.html">Yoga</a>
  <a href="fitness.html">Fitness</a>
  <a href="meditation.html">Meditation</a>
</nav>

<section>
  <h2>Explore our talented music facilitators ready to guide your passion.</h2>
  <div class="facilitator-list">
    <div class="facilitator">
      <img src="https://via.placeholder.com/300x180?text=Music+Mentor+1" alt="Facilitator 1">
      <h3>Rhea Fernandes</h3>
      <p>Vocal Coach – 5 years experience</p>
    </div>
    <div class="facilitator">
      <img src="https://via.placeholder.com/300x180?text=Music+Mentor+2" alt="Facilitator 2">
      <h3>Arjun Menon</h3>
      <p>Guitarist & Performer – 7 years</p>
    </div>
    <div class="facilitator">
      <img src="https://via.placeholder.com/300x180?text=Music+Mentor+3" alt="Facilitator 3">
      <h3>Sneha Pillai</h3>
      <p>Piano Instructor – 10 years</p>
    </div>
  </div>

  <form onsubmit="confirmBooking(event)">
    <h3>Book a Session</h3>
    <input type="text" name="name" placeholder="Your Name" required>
    <input type="date" name="date" required>
    <select name="time" required>
      <option value="">Select Time</option>
      <option>08:00 AM</option>
      <option>10:00 AM</option>
      <option>02:00 PM</option>
      <option>04:00 PM</option>
    </select>
    <button type="submit">Confirm Booking</button>
    <p id="confirmation-message" style="color: green; font-weight: bold;"></p>
  </form>
</section>

<footer>
  <p>Contact Us: info@v4u.com | +91 98765 43210</p>
  <p>&copy; 2025 V4U – We For You</p>
</footer>

<script>
  function confirmBooking(event) {
    event.preventDefault();
    document.getElementById("confirmation-message").textContent = "Class Confirmed!";
  }
</script>

</body>
</html>

