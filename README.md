<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gauri Tours & Travels | Pune Taxi Service</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, sans-serif;
      color: #222;
      background: #f7f7f7;
      line-height: 1.6;
    }

    header {
      background: #111;
      color: white;
      padding: 18px 6%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    .logo {
      font-size: 24px;
      font-weight: bold;
    }

    .logo span {
      color: #f5b400;
    }

    .call-top {
      background: #f5b400;
      color: #111;
      padding: 10px 15px;
      border-radius: 25px;
      text-decoration: none;
      font-weight: bold;
      font-size: 14px;
    }

    .hero {
      min-height: 570px;
      display: flex;
      align-items: center;
      padding: 70px 7%;
      color: white;
      background:
        linear-gradient(rgba(0,0,0,.65), rgba(0,0,0,.65)),
        url("https://images.unsplash.com/photo-1549317661-bd32c8ce0db2?auto=format&fit=crop&w=1600&q=80")
        center/cover;
    }

    .hero-content {
      max-width: 650px;
    }

    .hero h1 {
      font-size: 48px;
      line-height: 1.15;
      margin-bottom: 18px;
    }

    .hero h1 span {
      color: #f5b400;
    }

    .hero p {
      font-size: 19px;
      margin-bottom: 28px;
      color: #eee;
    }

    .buttons {
      display: flex;
      gap: 12px;
      flex-wrap: wrap;
    }

    .btn {
      display: inline-block;
      padding: 14px 22px;
      border-radius: 30px;
      text-decoration: none;
      font-weight: bold;
    }

    .btn-yellow {
      background: #f5b400;
      color: #111;
    }

    .btn-green {
      background: #20b858;
      color: white;
    }

    section {
      padding: 65px 7%;
    }

    .section-title {
      text-align: center;
      margin-bottom: 40px;
    }

    .section-title h2 {
      font-size: 34px;
      margin-bottom: 8px;
    }

    .section-title p {
      color: #666;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 20px;
    }

    .service-card {
      background: white;
      padding: 30px 20px;
      text-align: center;
      border-radius: 15px;
      box-shadow: 0 5px 20px rgba(0,0,0,.08);
    }

    .service-icon {
      font-size: 42px;
      margin-bottom: 15px;
    }

    .service-card h3 {
      margin-bottom: 10px;
    }

    .service-card p {
      color: #666;
      font-size: 14px;
    }

    .about {
      background: #111;
      color: white;
    }

    .about-content {
      max-width: 850px;
      margin: auto;
      text-align: center;
    }

    .about-content p {
      color: #ddd;
      font-size: 17px;
    }

    .booking {
      background: #f5b400;
    }

    .booking-box {
      max-width: 850px;
      margin: auto;
      background: white;
      padding: 35px;
      border-radius: 18px;
      box-shadow: 0 8px 30px rgba(0,0,0,.15);
    }

    .booking-box h2 {
      text-align: center;
      margin-bottom: 25px;
    }

    .form-row {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 15px;
      margin-bottom: 15px;
    }

    input, select, textarea {
      width: 100%;
      padding: 14px;
      border: 1px solid #ddd;
      border-radius: 8px;
      font-size: 15px;
    }

    textarea {
      min-height: 100px;
      resize: vertical;
      margin-bottom: 15px;
    }

    .submit-btn {
      width: 100%;
      border: none;
      padding: 15px;
      background: #20b858;
      color: white;
      font-size: 17px;
      font-weight: bold;
      border-radius: 8px;
      cursor: pointer;
    }

    .contact {
      text-align: center;
    }

    .contact-number {
      font-size: 30px;
      font-weight: bold;
      margin: 15px 0 25px;
    }

    .contact-number a {
      color: #111;
      text-decoration: none;
    }

    footer {
      background: #111;
      color: #bbb;
      text-align: center;
      padding: 25px 10px;
    }

    footer strong {
      color: white;
    }

    .whatsapp-float {
      position: fixed;
      right: 18px;
      bottom: 18px;
      background: #20b858;
      color: white;
      width: 58px;
      height: 58px;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      text-decoration: none;
      font-size: 28px;
      box-shadow: 0 4px 15px rgba(0,0,0,.3);
      z-index: 999;
    }

    @media (max-width: 800px) {
      .hero h1 {
        font-size: 38px;
      }

      .services {
        grid-template-columns: 1fr 1fr;
      }
    }

    @media (max-width: 550px) {
      header {
        padding: 15px 4%;
      }

      .logo {
        font-size: 19px;
      }

      .call-top {
        font-size: 12px;
        padding: 8px 11px;
      }

      .hero {
        min-height: 520px;
        padding: 55px 6%;
      }

      .hero h1 {
        font-size: 35px;
      }

      .hero p {
        font-size: 16px;
      }

      section {
        padding: 50px 5%;
      }

      .services {
        grid-template-columns: 1fr;
      }

      .form-row {
        grid-template-columns: 1fr;
      }

      .booking-box {
        padding: 22px;
      }
    }
  </style>
</head>

<body>

  <header>
    <div class="logo">Gauri <span>Tours & Travels</span></div>
    <a class="call-top" href="tel:+919960703982">📞 Call Now</a>
  </header>

  <section class="hero">
    <div class="hero-content">
      <h1>Reliable Taxi Service in <span>Pune</span></h1>

      <p>
        Comfortable, safe and convenient taxi services for Pune,
        airport transfers and outstation travel across India.
      </p>

      <div class="buttons">
        <a class="btn btn-yellow" href="tel:+919960703982">
          📞 Call Now
        </a>

        <a class="btn btn-green"
           href="https://wa.me/919960703982?text=Hello%20Gauri%20Tours%20%26%20Travels%2C%20I%20want%20to%20book%20a%20taxi."
           target="_blank">
          💬 WhatsApp Booking
        </a>
      </div>
    </div>
  </section>

  <section>
    <div class="section-title">
      <h2>Our Services</h2>
      <p>Travel comfortably with Gauri Tours & Travels</p>
    </div>

    <div class="services">

      <div class="service-card">
        <div class="service-icon">🚕</div>
        <h3>Pune Local Taxi</h3>
        <p>
          Convenient taxi service for local travel throughout Pune.
        </p>
      </div>

      <div class="service-card">
        <div class="service-icon">🛣️</div>
        <h3>Outstation Taxi</h3>
        <p>
          Comfortable one-way and round-trip journeys across India.
        </p>
      </div>

      <div class="service-card">
        <div class="service-icon">✈️</div>
        <h3>Airport Transfer</h3>
        <p>
          Reliable pickup and drop-off service for airport travel.
        </p>
      </div>

      <div class="service-card">
        <div class="service-icon">🚘</div>
        <h3>One Way & Round Trip</h3>
        <p>
          Flexible travel options according to your journey and schedule.
        </p>
      </div>

    </div>
  </section>

  <section class="about">
    <div class="about-content">
      <div class="section-title">
        <h2>Why Choose Gauri Tours & Travels?</h2>
      </div>

      <p>
        We provide dependable taxi services from Pune for local,
        airport and outstation travel. Whether you need a one-way
        journey or a round trip, contact us for your booking.
      </p>
    </div>
  </section>

  <section class="booking">
    <div class="booking-box">
      <h2>Quick Booking</h2>

      <form onsubmit="sendWhatsApp(); return false;">

        <div class="form-row">
          <input type="text" id="name" placeholder="Your Name" required>

          <input type="tel" id="phone" placeholder="Phone Number" required>
        </div>

        <div class="form-row">
          <input type="text" id="pickup" placeholder="Pickup Location" required>

          <input type="text" id="drop" placeholder="Drop Location" required>
        </div>

        <select id="trip" required>
          <option value="">Select Trip Type</option>
          <option>One Way</option>
          <option>Round Trip</option>
          <option>Airport Transfer</option>
          <option>Pune Local Taxi</option>
        </select>

        <br><br>

        <textarea id="message" placeholder="Travel date, time or any other requirement"></textarea>

        <button class="submit-btn" type="submit">
          💬 Send Booking on WhatsApp
        </button>

      </form>
    </div>
  </section>

  <section class="contact">
    <div class="section-title">
      <h2>Book Your Taxi</h2>
      <p>Call or WhatsApp us for booking and enquiries</p>
    </div>

    <div class="contact-number">
      <a href="tel:+919960703982">📞 99607 03982</a>
    </div>

    <div class="buttons" style="justify-content:center;">
      <a class="btn btn-yellow" href="tel:+919960703982">
        Call 99607 03982
      </a>

      <a class="btn btn-green"
         href="https://wa.me/919960703982?text=Hello%20Gauri%20Tours%20%26%20Travels%2C%20I%20want%20to%20book%20a%20taxi."
         target="_blank">
        WhatsApp Us
      </a>
    </div>
  </section>

  <footer>
    © 2026 <strong>Gauri Tours & Travels</strong> |
    Pune Taxi & Outstation Services
  </footer>

  <a class="whatsapp-float"
     href="https://wa.me/919960703982?text=Hello%20Gauri%20Tours%20%26%20Travels%2C%20I%20want%20to%20book%20a%20taxi."
     target="_blank"
     aria-label="WhatsApp">
    💬
  </a>

  <script>
    function sendWhatsApp() {

      var name = document.getElementById("name").value;
      var phone = document.getElementById("phone").value;
      var pickup = document.getElementById("pickup").value;
      var drop = document.getElementById("drop").value;
      var trip = document.getElementById("trip").value;
      var message = document.getElementById("message").value;

      var text =
        "Hello Gauri Tours & Travels,%0A%0A" +
        "Name: " + name + "%0A" +
        "Phone: " + phone + "%0A" +
        "Pickup: " + pickup + "%0A" +
        "Drop: " + drop + "%0A" +
        "Trip Type: " + trip + "%0A" +
        "Requirement: " + message;

      window.open(
        "https://wa.me/919960703982?text=" + text,
        "_blank"
      );
    }
  </script>

</body>
</html>
