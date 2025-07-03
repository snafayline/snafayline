<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>IXL - Personalized Learning</title>
  <link href="https://fonts.googleapis.com/css2?family=Open+Sans&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Open Sans', sans-serif;
      background: #f3fdfc;
    }
    header {
      background: #4caf50;
      color: white;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 10px 30px;
    }
    header .logo {
      font-size: 24px;
      font-weight: bold;
    }
    header nav a {
      margin: 0 15px;
      color: white;
      text-decoration: none;
      font-weight: 600;
    }
    .auth {
      display: flex;
      gap: 10px;
      align-items: center;
    }
    .auth input {
      padding: 5px;
    }
    .hero {
      text-align: center;
      padding: 60px 20px;
      background: linear-gradient(to right, #c8f5e4, #bde8f7);
    }
    .hero h1 {
      color: #1e8e3e;
      margin-bottom: 20px;
    }
    .hero p {
      font-size: 18px;
      margin: 10px 0;
    }
    .btn {
      background-color: #4caf50;
      color: white;
      padding: 10px 20px;
      border: none;
      cursor: pointer;
      margin-top: 20px;
      font-size: 16px;
      border-radius: 4px;
    }
    .features {
      display: flex;
      justify-content: center;
      gap: 40px;
      padding: 40px 20px;
      background-color: #e3f9f6;
    }
    .feature-box {
      background: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      width: 250px;
      text-align: center;
    }
    .bottom-boxes {
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 30px;
      background-color: #fdfdfd;
    }
    .bottom-boxes .box {
      background: #e5f4fb;
      padding: 20px;
      border-radius: 8px;
      width: 300px;
      text-align: center;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">IXL</div>
    <nav>
      <a href="#">Learning</a>
      <a href="#">Assessment</a>
      <a href="#">Analytics</a>
      <a href="#">Takeoff</a>
      <a href="#">Inspiration</a>
      <a href="#">MEMBERSHIP</a>
    </nav>
    <div class="auth">
      <input type="text" placeholder="Username">
      <input type="password" placeholder="Password">
      <button class="btn">Sign in</button>
    </div>
  </header>

  <section class="hero">
    <h1>IXL is personalized learning</h1>
    <p>Comprehensive K–12 curriculum</p>
    <p>Trusted by educators and parents</p>
    <p>Immersive learning experience</p>
    <button class="btn">Become a member</button>
  </section>

  <section class="features">
    <div class="feature-box">
      <h3>Comprehensive K–12 curriculum</h3>
      <p>Math, Language arts, Science, Social studies, Spanish</p>
    </div>
    <div class="feature-box">
      <h3>Trusted by educators and parents</h3>
      <p>Over 160 billion questions answered, 17M+ students use IXL</p>
    </div>
    <div class="feature-box">
      <h3>Immersive learning experience</h3>
      <p>Analytics, Recommendations, Real-Time Diagnostic, Awards</p>
    </div>
  </section>

  <section class="bottom-boxes">
    <div class="box">
      <h3>IXL for high school</h3>
      <p>Helps high schoolers create their own path to success.</p>
      <a href="#">Take a look</a>
    </div>
    <div class="box">
      <h3>IXL for independent learners</h3>
      <p>Yes, IXL is for adults too!</p>
      <a href="#">Take a look</a>
    </div>
  </section>
</body>
</html>
