<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Chebbo Tech - IT Consulting Services</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
  <link rel="stylesheet" href="styles.css">
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
    }
    .hero {
      background: linear-gradient(to right, #0d6efd, #6610f2);
      color: white;
      text-align: center;
      padding: 50px 20px;
    }
    .services, .about, .contact {
      padding: 50px 20px;
    }
    .service-item {
      text-align: center;
      padding: 20px;
      border: 1px solid #ddd;
      border-radius: 8px;
    }
    .service-item:hover {
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }
    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 30px;
    }
    .contact-form input, .contact-form textarea {
      margin-bottom: 15px;
    }
  </style>
</head>
<body>
  <!-- Hero Section -->
  <div class="hero">
    <h1>Welcome to Chebbo Tech</h1>
    <p>Innovative IT Consulting Solutions for a Digital World</p>
    <a href="#services" class="btn btn-light btn-lg">Our Services</a>
    <a href="#contact" class="btn btn-outline-light btn-lg">Contact Us</a>
  </div>

  <!-- About Section -->
  <section class="about bg-light" id="about">
    <div class="container">
      <div class="row">
        <div class="col-md-6">
          <h2>About Chebbo Tech</h2>
          <p>At Chebbo Tech, we specialize in delivering cutting-edge IT consulting services to businesses of all sizes. Our expertise spans cloud solutions, cybersecurity, digital transformation, and more. We partner with you to drive your business forward with technology.</p>
        </div>
        <div class="col-md-6">
          <img src="https://via.placeholder.com/500x300" alt="IT Consulting" class="img-fluid rounded">
        </div>
      </div>
    </div>
  </section>

  <!-- Services Section -->
  <section class="services" id="services">
    <div class="container">
      <h2 class="text-center">Our Services</h2>
      <p class="text-center">Explore the wide range of IT consulting services we offer:</p>
      <div class="row g-4 mt-4">
        <div class="col-md-4">
          <div class="service-item">
            <h3>Cloud Solutions</h3>
            <p>Leverage the power of cloud computing to scale your business operations efficiently.</p>
          </div>
        </div>
        <div class="col-md-4">
          <div class="service-item">
            <h3>Cybersecurity</h3>
            <p>Protect your business from threats with our advanced cybersecurity solutions.</p>
          </div>
        </div>
        <div class="col-md-4">
          <div class="service-item">
            <h3>Digital Transformation</h3>
            <p>Revolutionize your business with cutting-edge technology and processes.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Testimonials Section -->
  <section class="testimonials bg-light">
    <div class="container">
      <h2 class="text-center">What Our Clients Say</h2>
      <div class="row g-4 mt-4">
        <div class="col-md-4">
          <blockquote class="blockquote">
            <p>"Chebbo Tech helped us transition to the cloud seamlessly. Their expertise is unmatched!"</p>
            <footer class="blockquote-footer">John Doe, CEO of XYZ Corp</footer>
          </blockquote>
        </div>
        <div class="col-md-4">
          <blockquote class="blockquote">
            <p>"Our cybersecurity posture has improved dramatically thanks to Chebbo Tech's guidance."</p>
            <footer class="blockquote-footer">Jane Smith, CTO of ABC Inc.</footer>
          </blockquote>
        </div>
        <div class="col-md-4">
          <blockquote class="blockquote">
            <p>"Their IT consultants are knowledgeable and responsive. Highly recommended!"</p>
            <footer class="blockquote-footer">Emily Johnson, Director of IT at LMN Ltd.</footer>
          </blockquote>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section class="contact" id="contact">
    <div class="container">
      <h2 class="text-center">Contact Us</h2>
      <p class="text-center">Have a question or need help? Reach out to us today!</p>
      <form class="contact-form mt-4" action="#" method="POST">
        <div class="row">
          <div class="col-md-6">
            <input type="text" class="form-control" name="name" placeholder="Your Name" required>
          </div>
          <div class="col-md-6">
            <input type="email" class="form-control" name="email" placeholder="Your Email" required>
          </div>
        </div>
        <textarea class="form-control mt-3" name="message" rows="5" placeholder="Your Message" required></textarea>
        <button type="submit" class="btn btn-primary mt-3">Send Message</button>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Chebbo Tech. All rights reserved. | Designed with ❤️</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
