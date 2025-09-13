<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Monarch Air</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Inter', sans-serif; }
    body { color: #333; }

    /* Navbar */
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem 2rem;
      background: white;
      position: fixed;
      width: 100%;
      top: 0;
      box-shadow: 0 2px 5px rgba(0,0,0,.1);
      z-index: 10;
    }
    nav ul { display: flex; gap: 2rem; list-style: none; }
    nav ul li a {
      text-decoration: none;
      font-weight: 600;
      color: #333;
    }
    nav ul li a.active, nav ul li a:hover { color: goldenrod; }
    .login-btn {
      background: #5865F2;
      color: white;
      padding: 0.5rem 1rem;
      border-radius: 6px;
      text-decoration: none;
      font-weight: 600;
    }

    /* Hero section */
    .hero {
      height: 100vh;
      background: url("your-airplane.jpg") no-repeat center center/cover;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      flex-direction: column;
      color: white;
      padding: 0 1rem;
    }
    .hero h1 {
      font-size: 3rem;
      font-weight: 700;
    }
    .hero h1 span {
      color: gold;
    }
    .hero p {
      margin-top: 1rem;
      font-size: 1.2rem;
      max-width: 700px;
    }
    .btn-group {
      margin-top: 2rem;
    }
    .btn {
      display: inline-block;
      padding: 0.8rem 1.5rem;
      margin: 0.5rem;
      border-radius: 6px;
      text-decoration: none;
      font-weight: 600;
      transition: 0.2s;
    }
    .btn.primary { background: goldenrod; color: white; }
    .btn.secondary { border: 2px solid goldenrod; color: goldenrod; background: white; }
    .btn:hover { opacity: 0.85; }
  </style>
</head>
<body>
  <nav>
    <div class="logo"><strong>Monarch Air</strong></div>
    <ul>
      <li><a href="#" class="active">Home</a></li>
      <li><a href="#">Destinations</a></li>
      <li><a href="#">Fleet</a></li>
      <li><a href="#">Fly with Us</a></li>
    </ul>
    <a href="#" class="login-btn">Login with Discord</a>
  </nav>

  <section class="hero">
    <h1>Going Places <span>Together</span></h1>
    <p>Discover the world with Monarch Air. Premium destinations, exceptional service, and unforgettable journeys await.</p>
    <div class="btn-group">
      <a href="#" class="btn primary">Join Us Now</a>
      <a href="#" class="btn secondary">Fly with Us</a>
    </div>
  </section>
</body>
</html>
