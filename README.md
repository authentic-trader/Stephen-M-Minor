<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Authentic Constructors</title>
  <style>
    :root {
      --primary: #00553A;
      --accent: #F9A825;
      --bg: #f4f6f8;
      --text: #333;
    }

    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: var(--bg);
      color: var(--text);
    }

    .banner {
      width: 100%;
      height: auto;
      display: block;
    }

    .section {
      max-width: 1000px;
      margin: 60px auto;
      padding: 0 30px;
      text-align: center;
    }

    .section h2, .section h3 {
      color: var(--primary);
      font-size: 2em;
      margin-bottom: 20px;
    }

    .section p {
      color: #555;
      font-size: 1.1em;
      line-height: 1.6;
      margin-bottom: 30px;
    }

    .pdf-container {
      display: flex;
      justify-content: center;
      margin-bottom: 30px;
    }

    iframe {
      max-width: 900px;
      width: 100%;
      height: 600px;
      border: 1px solid #ccc;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }

    .download a {
      display: inline-block;
      margin-top: 10px;
      padding: 12px 25px;
      background-color: var(--accent);
      color: white;
      font-weight: bold;
      text-decoration: none;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }

    .download a:hover {
      background-color: #e3a700;
    }
  </style>
</head>
<body>

  <!-- Full-width banner image as header -->
  <img src="attachments/WkBiBHiYZBYtwtUkeURVx.png" alt="Authentic Constructors Banner" class="banner" />

  <!-- Welcome introduction -->
  <section class="section">
    <h2>Welcome to Authentic Constructors Kenya</h2>
    <p>We specialize in precision-driven building consultation and construction services. From architectural planning to technical execution, our team combines innovation, engineering, and craftsmanship to shape bold environments that last.</p>
  </section>

  <!-- Embedded Presentation PDF -->
  <section class="section">
    <h3>Project Gallery Overview</h3>
    <p>Browse our official presentation showcasing building layouts, design phases, materials, and workmanship across all service areas.</p>

    <div class="pdf-container">
      <iframe src="attachments/Presentation 5.pdf"></iframe>
    </div>

    <div class="download">
      <a href="attachments/Presentation 5.pdf" target="_blank">📄 Download Full Presentation</a>
    </div>
  </section>

</body>
</html>
