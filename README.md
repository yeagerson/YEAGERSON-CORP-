# YEAGERSON-CORP-
welcome to YA services.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Y.A Services</title>
  <meta name="description" content="Design. Digital Strategy. Full-service execution by Yeagerson Services.">
  <meta property="og:title" content="Y,A Services">
  <meta property="og:description" content="Design. Digital Strategy. Execute faster with Yeagerson.">
  <meta property="og:type" content="website">
  <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * { box-sizing: border-box; scroll-behavior: smooth; }
    body {
      margin: 0;
      font-family: 'Outfit', sans-serif;
      color: #f2f2f2;
      background: radial-gradient(ellipse at bottom, #1b2735 0%, #090a0f 100%);
    }
    header {
      text-align: center;
      background: linear-gradient(135deg, #121212, #1f1f1f);
      padding: 80px 20px 60px;
      position: relative;
      overflow: hidden;
    }
    .logo {
      font-size: 48px;
      font-weight: 800;
      background: linear-gradient(90deg, #ccc, #eee, #ccc);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      position: relative;
      z-index: 1;
    }
    .shine {
      content: '';
      position: absolute;
      top: 0;
      left: -75%;
      width: 50%;
      height: 100%;
      background: linear-gradient(120deg, transparent, rgba(255,255,255,0.2), transparent);
      transform: skewX(-25deg);
      animation: shine 4s infinite;
      z-index: 0;
    }
    @keyframes shine {
      0% { left: -75%; }
      100% { left: 125%; }
    }
    .subtext {
      font-size: 20px;
      opacity: 0.9;
      margin-bottom: 30px;
    }
    .action-btn {
      display: inline-block;
      background: linear-gradient(135deg, #00acc1, #007c91);
      color: white;
      padding: 12px 24px;
      margin: 10px;
      border: none;
      border-radius: 10px;
      font-weight: 600;
      text-decoration: none;
      cursor: pointer;
      transition: all 0.3s ease;
    }
    .action-btn:hover {
      transform: scale(1.05);
    }
    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
      display: none;
    }
    section.active {
      display: block;
    }
    h2 {
      color: #00acc1;
      margin-bottom: 20px;
    }
    ul { padding-left: 20px; line-height: 1.7; }
    .card-grid {
      display: grid;
      gap: 20px;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    }
    .card {
      background: rgba(255,255,255,0.05);
      border-radius: 10px;
      padding: 20px;
      text-align: center;
      transition: 0.3s ease;
    }
    .card:hover {
      background: rgba(255,255,255,0.08);
      transform: translateY(-4px);
    }
    .card a {
      color: #00e0ff;
      font-weight: bold;
      display: block;
      margin-top: 10px;
    }
    .footer {
      text-align: center;
      padding: 40px 20px;
      font-size: 14px;
      background: #111;
      color: #aaa;
    }
    .footer-buttons {
      margin: 20px 0;
    }
    .footer-buttons button {
      margin: 0 10px;
    }
    #scrollTop {
      position: fixed;
      bottom: 30px;
      right: 20px;
      background: #00acc1;
      color: white;
      padding: 10px 14px;
      border-radius: 50%;
      cursor: pointer;
      font-size: 18px;
      display: none;
    }
  </style>
</head>
<body>

  <header>
    <div class="logo">Y.A SERVICES</div>
    <div class="shine"></div>
    <p class="subtext">Design. Digital. Weekly Drops. Built for Execution.</p>
    <div>
      <button class="action-btn" onclick="toggleSection('services')">💼 Services</button>
      <button class="action-btn" onclick="toggleSection('rate')">💸 Rate List</button>
      <button class="action-btn" onclick="toggleSection('form')">📄 Apply</button>
      <button class="action-btn" onclick="toggleSection('about')">📌 About</button>
      <button class="action-btn" onclick="toggleSection('contact')">📞 Contact</button>
    </div>
  </header> 

  <section id="services">
    <h2>What We Offer</h2>
    <ul>
      <li><strong>🎨 Design:</strong> Logo Design, Web UI/UX, Brand Packs</li>
      <li><strong>📚 Courses:</strong> Freelancing, Digital Hustle PDFs</li>
      <li><strong>📞 Strategy Calls:</strong> 1-on-1 execution sessions</li>
    </ul>
  </section>

  <section id="rate">
    <h2>Service Rate List</h2>
    <h3>🎨 DESIGN SERVICES</h3>
    <ul>
      <li>Logo Design (Basic) – ₹799</li>
      <li>Logo Design (Pro) – ₹1499</li>
      <li>Landing Page Design – ₹2499</li>
      <li>Full Website UI/UX – ₹4999</li>
    </ul>

    <h3>📚 COURSES / PDF PACKS</h3>
    <ul>
      <li>Bulking Plan – ₹499</li>
      <li>cutting Plan - ₹499</li>
      <li>full(Bulk+Cut)- ₹899</li>
    </ul>

    <h3>🧠 CONSULTING & CUSTOMS</h3>
    <ul>
      <li>Brand Strategy Call (30 min) – ₹699</li>
      <li>Custom Bundle – Starts ₹999</li>
    </ul>
    <p><strong>Note:</strong> Payment via UPI / GPay / Paytm / PhonePe. Contact to proceed.</p>
  </section>

  <section id="about">
    <h2>About Yeagerson</h2>
    <p>At Yeagerson Services, we don’t do “just enough.” We design, strategize, and execute like it’s war-time. Built by John Yeagerson — this brand was born to serve creators, startups, and solo beasts who want full control over their digital identity.</p>
    <p>From bold logos to full brand experiences. From content systems to client pitches. We blend form, function, and fire.</p>
    <p><strong>📍 Based in India – Serving Worldwide 🌍</strong></p>
  </section>

  <section id="form">
    <h2>Apply to Work With Us</h2>
    <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSeGxgOCqAzI-d8mpKss4QXefyI48pKEvjm5rFyBHxBMoZhDMw/viewform?embedded=true" width="100%" height="800" frameborder="0">Loading…</iframe>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <div class="footer-buttons">
      <button class="action-btn" onclick="openEmail()">📧 Email</button>
      <button class="action-btn" onclick="openInstagram()">📸 Instagram</button>
      <button class="action-btn" onclick="openWhatsApp()">💬 WhatsApp</button>
    </div>
  </section>

  <footer class="footer">
    <p>© Yeagerson Services. All rights reserved. No fluff, only fire made possible by sister and the lord almighty.</p>
  </footer>

  <div id="scrollTop" onclick="window.scrollTo({ top: 0, behavior: 'smooth' })">↑</div>

  <script>
    function openEmail() {
      window.open('https://mail.google.com/mail/?view=cm&to=adityacharak14@gmail.com', '_blank');
    }

    function openWhatsApp() {
      const number = "9469264220";
      window.open(`https://wa.me/91${number}`, '_blank');
    }

    function openInstagram() {
      window.open('https://www.instagram.com/ya__services', '_blank');
    }

    function toggleSection(id) {
      const all = document.querySelectorAll('section');
      all.forEach(s => {
        if (s.id !== id) s.classList.remove('active');
      });
      const el = document.getElementById(id);
      el.classList.toggle('active');
    }

    window.onscroll = () => {
      document.getElementById("scrollTop").style.display = window.scrollY > 300 ? "block" : "none";
    };
  </script>

</body>
</html>
