# Valentine-s-day-gift-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Valentine's Day Card</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="card">
    <div class="card-header">
      <h1>Happy Valentine's Day!</h1>
    </div>
    <div class="card-body">
      <p>To my dearest,</p>
      <p>You are the light of my life and the love in my heart. I cherish every moment with you. Here's to many more wonderful days together!</p>
      <p class="heart">❤️</p>
    </div>
    <div class="card-footer">
      <p>With all my love,</p>
      <p>Your Valentine</p>
    </div>
  </div>
</body>
</html>
body {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  margin: 0;
  background-color: #f9f9f9;
}

.card {
  width: 400px;
  padding: 20px;
  background-color: #ffb6c1;
  border-radius: 15px;
  box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
  text-align: center;
  font-family: 'Arial', sans-serif;
}

.card-header h1 {
  color: #d6336c;
  font-size: 2.5em;
}

.card-body p {
  font-size: 1.2em;
  color: #333;
  margin: 10px 0;
}

.heart {
  font-size: 3em;
  margin-top: 20px;
}

.card-footer p {
  font-size: 1em;
  color: #333;
  margin-top: 20px;
  font-style: italic;
}
