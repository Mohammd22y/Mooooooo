<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>الرفيق معلمك</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      overflow: hidden;
      background-color: black;
      color: #FFD700;
      font-family: 'Arial', sans-serif;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      direction: rtl;
      position: relative;
    }

    .container {
      z-index: 2;
      text-align: center;
    }

    h1 {
      font-size: 4rem;
      text-shadow: 0 0 10px #FFD700, 0 0 20px #FFD700;
      animation: glow 2s ease-in-out infinite alternate;
    }

    @keyframes glow {
      from {
        text-shadow: 0 0 10px #FFD700, 0 0 20px #FFD700;
      }
      to {
        text-shadow: 0 0 20px #FFA500, 0 0 40px #FFD700;
      }
    }

    .stars {
      width: 100%;
      height: 100%;
      position: absolute;
      top: 0; left: 0;
      background: transparent;
      z-index: 1;
    }

    .stars::after {
      content: "✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨✨";
      font-size: 2rem;
      color: #fffacd;
      position: absolute;
      animation: twinkle 3s linear infinite;
      white-space: nowrap;
      left: 50%;
      top: 10%;
      transform: translateX(-50%);
      pointer-events: none;
    }

    @keyframes twinkle {
      0%, 100% { opacity: 0.5; transform: translateX(-50%) translateY(0); }
      50% { opacity: 1; transform: translateX(-50%) translateY(10px); }
    }
  </style>
</head>
<body>
  <div class="stars"></div>
  <div class="container">
    <h1>الرفيق معلمك</h1>
  </div>
</body>
</html>
