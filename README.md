<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ZeeBeav - Tesla Light Shows</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    
    body, html {
      height: 100%;
      background-color: #000000;
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
      padding-top: 15%;
    }

    h1 {
      font-size: 4.5rem;
      margin-bottom: 10px;
    }

    p {
      font-size: 1.4rem;
      margin-bottom: 40px;
      opacity: 0.9;
    }

    .btn {
      background: rgba(255,255,255,0.15);
      color: white;
      padding: 16px 40px;
      border-radius: 50px;
      text-decoration: none;
      font-size: 1.2rem;
      backdrop-filter: blur(10px);
      display: inline-block;
    }
  </style>
</head>
<body>

  <!-- Change this to your video filename -->
  <video class="video-bg" autoplay loop muted playsinline>
    <source src="your-video.mp4" type="video/mp4">
  </video>

  <div class="content">
    <h1>ZEEBEEV</h1>
    <p>Electric. Bold. Unforgettable.<br>Tesla Light Shows</p>
    <a href="mailto:your@email.com?subject=ZeeBeav%20Inquiry" target="_blank" class="btn">
      JOIN THE WAITLIST
    </a>
  </div>

</body>
</html>
