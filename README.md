# VTTOW.github.io
Website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Vermont Towing & Plowing LLC</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f4f4f4; color: #333; }
    header { background: #2c3e50; color: #fff; padding: 20px; text-align: center; }
    nav a { color: white; margin: 0 15px; text-decoration: none; }
    .container { padding: 20px; max-width: 1000px; margin: auto; }
    h2 { color: #2c3e50; }
    .gallery img { width: 100%; max-width: 300px; margin: 10px; border-radius: 10px; }
    form { display: flex; flex-direction: column; max-width: 600px; margin-top: 20px; }
    input, textarea { margin-bottom: 10px; padding: 10px; border: 1px solid #ccc; border-radius: 5px; }
    button { padding: 10px; background: #2c3e50; color: white; border: none; border-radius: 5px; cursor: pointer; }
    footer { text-align: center; padding: 20px; background: #2c3e50; color: white; margin-top: 30px; }
  </style>
</head>
<body>
  <header>
    <h1>Vermont Towing & Plowing LLC</h1>
    <nav>
      <a href="#services">Services</a>
      <a href="#gallery">Gallery</a>
      <a href="#contact">Quote Form</a>
      <a href="#about">About</a>
    </nav>
  </header>

  <div class="container">
    <section id="services">
      <h2>Our Services</h2>
      <ul>
        <li>Local & Long-Distance Towing</li>
        <li>Junk Car Buying (within 40 miles)</li>
        <li>Roadside Assistance (Lockouts & Jumpstarts)</li>
        <li>Snow Plowing (seasonal)</li>
      </ul>
    </section>

    <section id="gallery">
      <h2>Gallery</h2>
      <div class="gallery">
        <!-- Add your photos here -->
        <img src="https://via.placeholder.com/300x200?text=Tow+Truck+1" alt="Tow Truck 1">
        <img src="https://via.placeholder.com/300x200?text=Junk+Car+Pickup" alt="Junk Car Pickup">
      </div>
    </section>

    <section id="contact">
      <h2>Get a Quote</h2>
      <form action="https://formspree.io/f/yourFormID" method="POST">
        <input type="text" name="name" placeholder="Your Name" required />
        <input type="email" name="email" placeholder="Your Email" required />
        <input type="text" name="phone" placeholder="Phone Number" required />
        <input type="text" name="location" placeholder="Pickup/Service Location" required />
        <textarea name="message" placeholder="What do you need?" rows="5" required></textarea>
        <button type="submit">Send Quote Request</button>
      </form>
      <p><small>We will respond quickly to your request.</small></p>
    </section>

    <section id="about">
      <h2>About Vermont Towing & Plowing LLC</h2>
      <p>
        Based in Alstead, NH, we proudly serve NH and VT — and beyond for long-distance towing.
        We offer reliable and prompt towing services, junk car buying, roadside assistance, and seasonal plowing.
      </p>
      <p><strong>Contact us:</strong><br>
      Phone: <a href="tel:18024283550">1-802-428-3550</a><br>
      Email: <a href="mailto:logantillson1@gmail.com">logantillson1@gmail.com</a><br>
      Location: Gilsum Mine Road, Alstead, NH
      </p>
    </section>
  </div>

  <footer>
    &copy; 2025 Vermont Towing & Plowing LLC | Serving NH, VT & beyond
  </footer>
</body>
</html>


