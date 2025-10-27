<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Adarsh Agrawal – CA Finalist</title>

  <!-- Meta Info -->
  <link rel="icon" href="profile.jpg" type="image/jpeg">
  <meta name="description" content="Adarsh Agrawal – CA Finalist specializing in taxation, GST, and auditing.">
  <meta property="og:title" content="Adarsh Agrawal – CA Finalist">
  <meta property="og:description" content="CA Finalist with a strong interest in taxation, auditing, and business advisory.">
  <meta property="og:image" content="https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPO_NAME/profile.jpg">
  <meta name="theme-color" content="#C0C0C0">

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600&display=swap" rel="stylesheet">

  <style>
    @keyframes fadeInUp {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #f2f2f2, #e9e9e9);
      color: #333;
    }

    .container {
      max-width: 520px;
      margin: 50px auto;
      background: #ffffff;
      border-radius: 20px;
      box-shadow: 0 8px 25px rgba(0,0,0,0.1);
      padding: 35px;
      animation: fadeInUp 0.8s ease-out both;
      border: 1px solid #dcdcdc;
    }

    .profile {
      display: flex;
      justify-content: center;
      margin-bottom: 16px;
    }

    .profile img {
      width: 180px;
      height: 180px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid transparent;
      background: linear-gradient(145deg, #dcdcdc, #f7f7f7) border-box;
      box-shadow: 0 0 25px rgba(160, 160, 160, 0.5);
    }

    h1 {
      text-align: center;
      font-size: 2rem;
      margin: 12px 0 4px;
      font-weight: 600;
      color: #2f2f2f; /* Charcoal */
    }

    p.subtitle {
      text-align: center;
      color: #666;
      margin-top: 0;
      font-weight: 500;
      font-size: 1.05rem;
    }

    /* Typewriter Tagline */
    .tagline {
      text-align: center;
      font-size: 0.95rem;
      color: #444;
      margin-top: 8px;
      height: 22px;
      font-weight: 500;
      white-space: nowrap;
      overflow: hidden;
      border-right: 2px solid #C0C0C0;
      width: 0;
      animation: typing 5s steps(60, end) forwards, blink 0.75s step-end infinite;
      font-style: italic;
    }

    @keyframes typing {
      from { width: 0; }
      to { width: 100%; }
    }

    @keyframes blink {
      50% { border-color: transparent; }
    }

    hr {
      width: 65%;
      margin: 18px auto;
      border: 0;
      border-top: 2px solid #C0C0C0;
    }

    .section {
      margin-top: 30px;
      opacity: 0;
      transform: translateY(20px);
      animation: fadeInUp 1s ease forwards;
    }

    h2 {
      text-align: center;
      color: #2f2f2f;
      font-weight: 600;
      letter-spacing: 0.5px;
      position: relative;
      margin-bottom: 12px;
    }

    h2::after {
      content: "";
      display: block;
      width: 50px;
      height: 3px;
      margin: 6px auto 0;
      border-radius: 3px;
      background: linear-gradient(90deg, #dcdcdc, #b0b0b0, #f2f2f2);
    }

    a {
      color: #505050;
      text-decoration: none;
      font-weight: 500;
    }

    a:hover {
      text-decoration: underline;
    }

    .btn {
      display: inline-block;
      padding: 10px 18px;
      text-decoration: none;
      color: #fff;
      background: linear-gradient(90deg, #b0b0b0, #c0c0c0, #a9a9a9);
      border-radius: 6px;
      font-size: 0.95rem;
      transition: all 0.3s ease;
      font-weight: 500;
      box-shadow: 0 3px 10px rgba(150, 150, 150, 0.3);
    }

    .btn:hover {
      background: linear-gradient(90deg, #a9a9a9, #bfbfbf, #999);
      transform: scale(1.05);
      box-shadow: 0 4px 14px rgba(130, 130, 130, 0.4);
    }

    .btn-whatsapp { background: #25D366; box-shadow: 0 3px 10px rgba(37,211,102,0.4); }
    .btn-instagram { background: #E1306C; box-shadow: 0 3px 10px rgba(225,48,108,0.4); }
    .btn-share { background: #0F9D58; box-shadow: 0 3px 10px rgba(15,157,88,0.4); }

    .btn-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 10px;
      margin-top: 10px;
    }

    .icon-services {
      display: flex;
      justify-content: space-around;
      margin-top: 15px;
      text-align: center;
      font-size: 0.9rem;
      flex-wrap: wrap;
      gap: 10px;
    }

    .icon-box {
      width: 100px;
      padding: 10px;
      border-radius: 10px;
      background: linear-gradient(145deg, #f8f8f8, #e6e6e6);
      box-shadow: 0 3px 10px rgba(0,0,0,0.05);
      color: #2f2f2f;
      font-weight: 500;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .icon-box:hover {
      transform: translateY(-6px);
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    }

    .qr-section {
      text-align: center;
      margin-top: 28px;
    }

    .qr-section img {
      width: 160px;
      border-radius: 12px;
      margin-top: 10px;
      box-shadow: 0 3px 12px rgba(0,0,0,0.1);
    }

    footer {
      text-align: center;
      color: #555;
      font-size: 0.85rem;
      margin-top: 35px;
      padding-top: 10px;
      border-top: 1px solid #d0d0d0;
    }

  </style>
</head>
<body>
  <div class="container">
    <div class="profile">
      <img src="PROFILE.JPG" alt="Adarsh Agrawal">
    </div>

    <h1>Adarsh Agrawal</h1>
    <p class="subtitle">CA Finalist | Vaada & Associates</p>
    <p class="tagline">Vaada means Promise and when we promise, we deliver on time.</p>
    <hr>

    <div class="section">
      <h2>Contact</h2>
      <p style="text-align:center;">
        📞 <a href="tel:+917327809032">+91 73278 09032</a><br>
        ✉️ <a href="mailto:vaadaandassociatesgst@gmail.com">vaadaandassociatesgst@gmail.com</a><br>
        🏠 Home: Balangir, Odisha<br>
        🏢 Office: Raipur, C.G.
      </p>

      <div class="btn-container">
        <a href="https://wa.me/917327809032?text=Hello%20Adarsh%20Agrawal" class="btn btn-whatsapp">WhatsApp</a>
        <a href="https://instagram.com/iamadarsh_agrawal" class="btn btn-instagram">Instagram</a>
        <a href="https://wa.me/?text=Check%20out%20Adarsh%20Agrawal’s%20profile:%20YOUR_GITHUB_PAGES_LINK" class="btn btn-share">Share My Card</a>
      </div>
    </div>

    <div class="section">
      <h2>About Me</h2>
      <p>
        I am a <strong>CA Finalist</strong> working at <strong>Vaada & Associates</strong>, where I specialize in taxation, auditing, and GST compliance.  
        I aim to assist individuals and businesses in achieving financial transparency, regulatory accuracy, and sustainable growth through professional and ethical advisory.
      </p>
      <p><strong>Birthdate:</strong> 12th June 2000</p>
    </div>

    <div class="section">
      <h2>Professional Services</h2>
      <div class="icon-services">
        <div class="icon-box">📄 ITR Filing</div>
        <div class="icon-box">💰 GST Returns</div>
        <div class="icon-box">📊 Audit</div>
        <div class="icon-box">🏢 Consultancy</div>
      </div>
    </div>

    <div class="qr-section">
      <h2>Scan for UPI Payment</h2>
      <img src="PHONEPAYQR.JPG" alt="PhonePe UPI QR Code">
      <p style="color:#555; font-size:0.9rem;">Scan using any UPI app (PhonePe, GPay, Paytm)</p>
    </div>

    <footer>
      Designed by Nitish Agrawal | © 2025 All Rights Reserved
    </footer>
  </div>
</body>
</html>