<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Main Menu</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, rgb(8, 183, 192), rgb(157, 188, 197));
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }

    .container {
      background: rgba(255, 255, 255, 0.1);
      padding: 50px;
      border-radius: 20px;
      text-align: center;
      box-shadow: 0 8px 25px rgba(0,0,0,0.4);
      width: 400px;
      backdrop-filter: blur(10px);
      border: 1px solid rgba(255, 255, 255, 0.2);
    }

    h1 {
      margin-bottom: 30px;
      color: #fff;
      font-weight: 600;
      letter-spacing: 1px;
    }

    a.menu-btn {
      display: block;
      margin: 14px 0;
      padding: 14px;
      background: linear-gradient(135deg, white, mintcream);
      color: black;
      border-radius: 12px;
      font-weight: 600;
      text-decoration: none;
      transition: all 0.3s ease;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }

    a.menu-btn:hover {
      background: linear-gradient(135deg, #8cdce1, #8dcbdc);
      transform: scale(1.05);
      box-shadow: 0 6px 15px rgba(0,0,0,0.3);
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Main Menu</h1>
    <a href="unitconverter.html" class="menu-btn">🌡️ Temperature Converter</a>
    <a href="grading.html" class="menu-btn">📘 Grade Checker</a>
    <a href="change.html" class="menu-btn">💰 Change Calculator</a>
    <a href="geolocation.html" class="menu-btn">📍 Geolocation</a>
    <a href="hobby.html" class="menu-btn">🎨 Hobby</a>
    <a href="resume.html" class="menu-btn">📄 Resume</a>
  </div>
</body>
</html>
