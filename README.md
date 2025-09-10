<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>アイドルプロフィールカード</title>
  <style>
    .idol-card {
      width: 240px;
      border: 1px solid #ccc;
      border-radius: 12px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.07);
      padding: 16px;
      text-align: center;
      background: #fff;
      margin: 20px auto;
    }
    .idol-photo {
      width: 120px;
      height: 120px;
      object-fit: cover;
      border-radius: 50%;
      margin-bottom: 12px;
      border: 2px solid #e3e3e3;
    }
    .idol-name {
      font-size: 1.2em;
      font-weight: bold;
      margin-bottom: 8px;
    }
    .idol-size {
      font-size: 0.95em;
      margin-bottom: 4px;
    }
    .idol-cup {
      font-size: 0.95em;
      color: #555;
    }
  </style>
</head>
<body>
  <div class="idol-card">
    <img class="idol-photo" src="https://example.com/photos/hanako.jpg" alt="山田 花子">
    <div class="idol-name">山田 花子</div>
    <div class="idol-size">B:88 W:58 H:85</div>
    <div class="idol-cup">Cup: F</div>
  </div>
</body>
</html>
