<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Shree Sarbajanik Secondary School</title>
  <style>
    /* ===== GENERAL STYLES ===== */
    body {
      margin: 0;
      font-family: "Poppins", sans-serif;
      scroll-behavior: smooth;
      color: #333;
    }
    header {
      background-color: #0056b3;
      color: white;
      padding: 20px 0;
      position: fixed;
      top: 0;
      width: 100%;
      z-index: 1000;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 30px;
      flex-wrap: wrap;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: 500;
      transition: 0.3s;
    }
    nav a:hover {
      color: #ffd700;
    }

    section {
      padding: 100px 20px;
      max-width: 1000px;
      margin: auto;
    }

    h1, h2 {
      color: #0056b3;
      text-align: center;
    }

    .hero {
      background: linear-gradient(rgba(0, 86, 179, 0.7), rgba(0, 86, 179, 0.7)),
                  url('https://images.unsplash.com/photo-1596495577886-d920f1fb7238?auto=format&fit=crop&w=1950&q=80')
                  center/cover;
      color: white;
      height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 0 20px;
    }

    .hero h1 {
      font-size: 2.5rem;
      margin-bottom: 15px;
    }
    .hero p {
      font-size: 1.2rem;
      max-width: 600px;
    }

    .academics, .staff, .news {
      background-color: #f5f8ff;
      border-radius: 10px;
      padding: 40px 30px;
      margin-top: 30px;
    }

    .contact {
      text-align: center;
    }
    .contact a {
      color: #0056b3;
      text-decoration: none;
      font-weight: bold;
    }

    footer {
      background-color: #003f88;
      color: white;
      text-align: center;
      padding: 15px 10px;
      margin-top: 40px;
    }

    @media (max-width: 768px) {
      nav {
        flex-direction: column;
        gap: 10px;
      }
      .hero h1 {
        font-size: 2rem;
      }
    }
  </style>
</head>
<body>

  <!-- ===== HEADER ===== -->
  <header>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About Us</a>
      <a href="#academics">Academics</a>
      <a href="#staff">Staff</a>
      <a href="#news">News / Events</a>
      <a href="#contact">Contact Us</a>
    </nav>
  </header>

  <!-- ===== HERO / HOME SECTION ===== -->
  <section id="home" class="hero">
    <h1>Welcome to Shree Sarbajanik Secondary School</h1>
    <p>Empowering students through quality education and holistic development in the heart of Lumbini, Nepal.</p>
  </section>

  <!-- ===== ABOUT US ===== -->
  <section id="about">
    <h2>About Us</h2>
    <p>
      Shree Sarbajanik Secondary School, located in Chhatradev-5, Arghakhanchi, has been providing quality education 
      to the community for decades. Our mission is to inspire lifelong learning, moral values, and excellence 
      among our students.
    </p>
  </section>

  <!-- ===== ACADEMICS ===== -->
  <section id="academics" class="academics">
    <h2>Academics</h2>
    <p>
      Our academic programs include primary to secondary levels, with a strong focus on science, mathematics, 
      social studies, and language education. We also emphasize extracurricular activities to ensure 
      balanced development.
    </p>
  </section>

  <!-- ===== STAFF ===== -->
  <section id="staff" class="staff">
    <h2>Our Dedicated Staff</h2>
    <p>
      Our team consists of experienced, passionate, and caring teachers who work tirelessly to support 
      students in their educational journey. Each teacher brings unique expertise and commitment to excellence.
    </p>
  </section>

  <!-- ===== NEWS / EVENTS ===== -->
  <section id="news" class="news">
    <h2>News & Events</h2>
    <p>
      Stay tuned for updates on school events, examination schedules, and special programs.
      <br>📅 Upcoming: Annual Sports Week & Cultural Day!
    </p>
  </section>

  <!-- ===== CONTACT US ===== -->
  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p><strong>Address:</strong> Chhatradev-5, Arghakhanchi, Lumbini, Nepal</p>
    <p><strong>Phone:</strong> 9847493238</p>
    <p><strong>Email:</strong> <a href="mailto:contact@ssss.edu.np">contact@ssss.edu.np</a></p>
  </section>

  <!-- ===== FOOTER ===== -->
  <footer>
    &copy; 2025 Shree Sarbajanik Secondary School. All Rights Reserved.
  </footer>

</body>
</html>
