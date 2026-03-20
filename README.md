# Site1
Info cours à domicile 
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mon Site</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #0f172a;
      color: white;
      text-align: center;
    }

    header {
      padding: 40px 20px;
      font-size: 28px;
      font-weight: bold;
      background: linear-gradient(90deg, teal, #0ea5e9);
    }

    .container {
      padding: 30px 20px;
    }

    .image-box img {
      width: 100%;
      max-width: 500px;
      border-radius: 20px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.5);
      margin: 20px 0;
    }

    .info {
      max-width: 600px;
      margin: auto;
      font-size: 18px;
      line-height: 1.6;
      opacity: 0.9;
    }

    .contact-section {
      margin-top: 50px;
      padding: 40px 20px;
      background: #020617;
      border-top: 2px solid teal;
    }

    .contact-title {
      font-size: 24px;
      margin-bottom: 20px;
    }

    .contact-btn {
      display: inline-block;
      padding: 15px 30px;
      background: teal;
      color: white;
      text-decoration: none;
      border-radius: 30px;
      font-size: 18px;
      transition: 0.3s;
    }

    .contact-btn:hover {
      background: #0ea5e9;
      transform: scale(1.05);
    }

    footer {
      margin-top: 30px;
      font-size: 14px;
      opacity: 0.6;
    }
  </style>
</head>
<body>

  <header>
    Mon Super Site
  </header>

  <div class="container">

    <div class="image-box">
      <img src="https://via.placeholder.com/500" alt="image">
    </div>

    <div class="info">
      <p>
        Bienvenue sur mon site ! Ici vous pouvez découvrir mon univers, mes services ou mon projet.
        Ce site est simple, rapide et accessible à tous.
      </p>

      <br>

      <p>
        N'hésitez pas à me contacter pour toute question, collaboration ou information.
      </p>
    </div>

  </div>

  <div class="contact-section">
    <div class="contact-title">Contact</div>

    <a class="contact-btn" href="mailto:tonemail@gmail.com">
      Me contacter
    </a>
  </div>

  <footer>
    © 2026 - Mon site
  </footer>

</body>
</html>
