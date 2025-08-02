# Maryam-s-birthday
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>🎉 Happy Birthday 🎂</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Arial', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background: linear-gradient(135deg, #ff9a9e 0%, #fad0c4 100%);
      color: #fff;
    }

    .card {
      background: rgba(0, 0, 0, 0.7);
      padding: 40px;
      border-radius: 15px;
      text-align: center;
      box-shadow: 0 10px 20px rgba(0,0,0,0.3);
      animation: pop 1s ease forwards;
    }

    .card h1 {
      font-size: 36px;
      margin-bottom: 20px;
    }

    .card p {
      font-size: 18px;
      margin-bottom: 10px;
    }

    .card button {
      padding: 10px 20px;
      font-size: 16px;
      background-color: #ff6b6b;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    .card button:hover {
      background-color: #ff4757;
    }

    @keyframes pop {
      0% {
        transform: scale(0);
      }
      100% {
        transform: scale(1);
      }
    }
  </style>
</head>

<body>
  <div class="card">
    <h1>🎈 Happy Birthday! 🎂</h1>
    <p>كل سنة وانت طيب 🎉</p>
    <p>يوم جميل وسعيد عليك 🎁</p>
    <button onclick="alert('🎉🎉🎉 كل سنة وانت طيب! 🎉🎉🎉')">اضغط هنا 🎊</button>
  </div>

  <script>
    console.log('Happy Birthday 🎉');
  </script>
</body>
</html>
