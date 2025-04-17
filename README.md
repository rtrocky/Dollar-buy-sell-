<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Dollar Buy-Sell</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <h1>Dollar Buy & Sell</h1>
    
    <div class="rates">
      <p>Buy Rate: <span id="buyRate">110</span>৳</p>
      <p>Sell Rate: <span id="sellRate">112</span>৳</p>
    </div>

    <div class="form">
      <h2>Buy Dollar</h2>
      <input type="number" id="buyAmount" placeholder="Enter dollar amount">
      <p>Total: <span id="buyTotal">0</span> ৳</p>
      
      <h2>Sell Dollar</h2>
      <input type="number" id="sellAmount" placeholder="Enter dollar amount">
      <p>Total: <span id="sellTotal">0</span> ৳</p>
    </div>
  </div>

  <script src="script.js"></script>
</body>
</html>
