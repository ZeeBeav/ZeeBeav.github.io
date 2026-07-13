<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ZeeBeavs Blinky Shows</title>
  <style>
    body, html {
      margin: 0;
      padding: 0;
      background-color: #000000;     /* This is the key */
      height: 100%;
      overflow: hidden;
    }

   @import url('https://fonts.googleapis.com/css2?family=Impact:wght@400;700&family=Arial:wght@400;700&display=swap');
* {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    .video-bg {
      position: fixed;          /* Stays in background */
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      object-fit: cover;        /* Keeps aspect ratio, fills screen */
      z-index: -1;              /* Behind everything */
      filter: brightness(0.75); /* Optional: darken a bit for text readability */
    }

    .content {
      position: relative;
      z-index: 1;
      color: white;
      text-align: center;
      padding: 100px 20px;
    }
    body {
      margin: 0;
      padding: 0;background-color: #0a0a0a;
      background: #0a0a0a;
      color: #000000;
      font-family: 'Arial', sans-serif;
      text-align: center;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
    }

    .container {
      max-width: 820px;
      padding: 40px 20px;
    }

    h1 {
      font-family: 'Impact', sans-serif;
      font-size: 5.2rem;
      margin: 0 0 8px 0;
      letter-spacing: 8px;background-color: #0a0a0a;
      color: #00F0FF;
      text-shadow: 0 0 30px rgba(0, 240, 255, 0.7);
    }

    .tagline {
      font-size: 1.75rem;
      margin-bottom: 25px;
      opacity: 0.95;
    }

    img {
      max-width: 100%;
      width: 440px;
      height: auto;
      border-radius: 16px;
      box-shadow: 0 25px 50px rgba(0, 240, 255, 0.3);
      margin: 35px 0 25px;
      border: none;
    }

    .subtitle {
      font-size: 1.4rem;
      margin: 15px 0 40px;
      line-height: 1.6;
    }

    .cta {
      background: #00F0FF;
      color: #000;
      padding: 18px 48px;
      font-size: 1.5rem;
      font-weight: bold;
      border-radius: 50px;
      text-decoration: none;
      display: inline-block;
      margin-top: 10px;
      transition: all 0.3s;
      box-shadow: 0 10px 30px rgba(0, 240, 255, 0.4);
    }

    .cta:hover {
      transform: scale(1.08);
      background: #00ffff;
    }

    footer {
      margin-top: 80px;
      opacity: 0.65;
      font-size: 1rem;
    }
  </style>
</head>
<body>
  <!-- Background Video -->
  <video class="video-bg" autoplay loop muted playsinline>
    <source src="https://zeebeav.github.io/Sequence 01_2.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>

  <!-- Your actual website content on top -->
  <div class="container">
    <h1><img src="https://zeebeav.github.io/ZeeBeav_BlinkyShows (1).png">
    <br>
    <img src="https://zeebeav.github.io/ZeeBeav_BlinkyShows.png"></h1>
    <p class="tagline">We do Electric. Bold. Unforgettable. Tesla Light Shows.</p>

    <img src="https://zeebeav.github.io/ZeeBeavLogoPatriotic.png" alt="Zeebeev Helmet & License Plate">

    <p class="subtitle">
      Catch the ZeeBeev license plate on the streets</p><br>

    <a href="mailto:Zeebeav@gmail.com?subject=Dude, put me on the email list pls!" target="_blank" class="cta">JOIN THE EMAIL LIST</a>

    <p class="subtitle">
      FREE DOWNLOAD SITES:<br>

       <a href="https://www.toybox.lol/zeebeav" target="_blank" class="cta">The ToyBox</a>
       <a href="https://xlightshows.io/light-shows/" target="_blank" class="cta">Xlights</a>
       <a href="https://teslalightshare.io/4247/light-shows" target="_blank" class="cta">TeslaShare</a>
       <a href="https://www.patreon.com/zeebeav" target="_blank" class="cta">Patreon</a>
       
       

      </p>
  <p class="tagline"><br>We even have Tshirts!<br>
  <img src="https://zeebeav.github.io/zeebeavTshirt.png" alt="Zeebeev shirt"><br>
  <a href="https://smokehbearsden.com/products/zeebeav-blinky-shows-tee?variant=48170385080558" target="_blank" class="cta"> $40 T's</a>
    <footer>
      zeebeav.com &amp; zeebeev.com
    </footer>
