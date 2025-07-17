# ilymore
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Happy Birthday, Tiny!</title>
  <style>
    body {
      background-color: #87CEFA; /* a light sky-blue */
      color: #fff;
      font-family: 'Comic Sans MS', cursive;
      text-align: center;
      padding-top: 100px;
    }
  </style>
</head>
<body>
  <h1>Happy Birthday, Tiny!</h1>
  <p>Wishing you all the joy, love, and laughter today.</p>
  <img src="balloon.png" class="balloons" alt="balloons" width="100">
  <style>
    .balloons {
      position: absolute;
      top: -100px;
      left: 50%;
      transform: translateX(-50%);
      animation: rise 10s infinite;
    }
    @keyframes rise {
      0% { top: 100%; opacity: 0; }
      50% { opacity: 1; }
      100% { top: -200px; opacity: 0; }
    }
  </style>
</body>
</html>
