# adrita<!DOCTYPE html>
<html>
<head>
  <title>For You</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      background: linear-gradient(to right, #ff9a9e, #fad0c4);
      font-family: Arial;
    }

    h1 {
      font-size: 40px;
      color: white;
      margin-bottom: 30px;
    }

    .btn {
      font-size: 30px;
      background: white;
      border: none;
      border-radius: 50%;
      padding: 15px 20px;
      cursor: pointer;
      transition: 0.3s;
    }

    .btn:hover {
      background: #ff4d6d;
      color: white;
    }
  </style>
</head>

<body>
  <h1>This is for you 💖</h1>

  <button class="btn" onclick="nextPage()">➡️</button>

  <script>
    function nextPage() {
      window.location.href = "page2.html";
    }
  </script>
</body>
</html>
