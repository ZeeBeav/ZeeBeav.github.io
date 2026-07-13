<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ZeeBeav - Tesla Light Shows</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    
    body, html {
      height: 100%;
      background: #000;
      overflow: hidden;
      font-family: Arial, sans-serif;
    }

    .video-bg {
      position: fixed;
      top: 0; left: 0;
      width: 100%;
      height: 100%;
      object-fit: cover;
      z-index: -1;
    }

    .content {
      position: relative;
      z-index: 2;
      color: white;
      text-align: center;
      padding-top: 18%;
    }

    h1 {
      font-size: 5.5rem;
      margin-bottom: 10px;
      letter-spacing: 4px;
    }

    p {
      font-size: 1.6rem;
      margin-bottom: 50px;
      opacity: 0.95;
    }

    .btn {
      background: rgba(255, 255, 255, 0.18);
      color: white;
      padding: 18px 48px;
      border-radius: 50px;
      font-size: 1.35rem;
      text-decoration: none;
      backdrop-filter: blur(12px);
      display: inline-block;
      transition: 0.3s;
    }

    .btn:hover {
      background: rgba(255, 255, 255, 0.3);
      transform: scale(1.05);
    }

    .logo {
      position: absolute;
      top: 40px;
      left: 50px;
      width: 200px;
      z-index: 3;
      filter: drop-shadow(0 0 20px rgba(0,0,0,0.9));
    }
  </style>
</head>
<body>

  <!-- ================== CHANGE THESE TWO LINES ================== -->
  <video class="video-bg" autoplay loop muted playsinline>
    <source src="your-video.mp4" type="video/mp4">   <!-- ← CHANGE THIS -->
  </video>

  <img src="your-logo.png" class="logo" alt="ZeeBeav">   <!-- ← CHANGE THIS (or delete the whole line if no logo) -->
  <!-- ============================================================ -->

  <div class="content">
    <h1>ZEEBEEV</h1>
    <p>Electric. Bold. Unforgettable.<br>Tesla Light Shows</p>
    <a href="mailto:your@email.com?subject=ZeeBeav%20Inquiry" target="_blank" class="btn">
      JOIN THE WAITLIST
    </a>
  </div>

</body>
</html>
