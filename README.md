<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Animated Game Page</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(135deg, #1f1c2c, #928dab);
      font-family: Arial, sans-serif;
      color: white;
      text-align: center;
      overflow: hidden;
    }

    .container {
      padding: 50px 20px;
      animation: slideIn 2s ease;
    }

    h1 {
      font-size: 3em;
      margin-bottom: 10px;
      animation: fadeIn 2s ease-in-out;
    }

    p {
      font-size: 1.2em;
      margin-bottom: 30px;
      animation: fadeIn 2.5s ease-in-out;
    }

    .game-preview {
      width: 300px;
      height: 200px;
      margin: 0 auto 40px;
      background: rgba(255, 255, 255, 0.1);
      border: 2px dashed #fff;
      display: flex;
      align-items: center;
      justify-content: center;
      animation: bounceIn 2s ease;
    }

    .download-btn {
      padding: 15px 30px;
      font-size: 1.2em;
      background: #ff4e50;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      text-decoration: none;
      animation: pulse 2s infinite;
      transition: background 0.3s;
    }

    .download-btn:hover {
      background: #ff1f2c;
    }

    @keyframes slideIn {
      from { transform: translateY(-100px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    @keyframes bounceIn {
      0% { transform: scale(0.8); opacity: 0; }
      50% { transform: scale(1.1); opacity: 1; }
      100% { transform: scale(1); }
    }

    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.05); }
      100% { transform: scale(1); }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Welcome to My Game</h1>
    <p>Experience the thrill of action and adventure. Download now!</p>
    <div class="game-preview">
      <span>Game Preview</span>
    </div>
    <a href="https://e733228f3003ec552ee415ea9bd627ed.serveo.net" class="download-btn">Download Game</a>
  </div>
</body>
</html>
