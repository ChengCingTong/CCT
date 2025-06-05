<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Make a Donation</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }
    .container {
      max-width: 700px;
      margin: 40px auto;
      background-color: white;
      padding: 40px;
      border-radius: 10px;
      box-shadow: 0 0 15px rgba(0, 0, 0, 0.05);
    }
    h1 {
      text-align: center;
      font-size: 28px;
      color: #333;
      margin-bottom: 30px;
    }
    .form-group {
      margin-bottom: 20px;
    }
    label {
      font-weight: bold;
      display: block;
      margin-bottom: 8px;
      color: #222;
    }
    input, select {
      width: 100%;
      padding: 12px;
      border: 1px solid #ccc;
      border-radius: 6px;
      font-size: 15px;
    }
    button {
      width: 100%;
      padding: 14px;
      background-color: #0066cc;
      border: none;
      border-radius: 6px;
      color: white;
      font-size: 16px;
      font-weight: bold;
      cursor: pointer;
    }
    button:hover {
      background-color: #004c99;
    }
    .payment-info {
      margin-top: 30px;
      font-size: 15px;
      color: #444;
      line-height: 1.6;
    }
    .payment-info strong {
      display: block;
      margin-top: 15px;
      color: #000;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Make a Donation</h1>
    <form action="#" method="POST">
      <div class="form-group">
        <label for="name">Full Name</label>
        <input type="text" id="name" name="name" required>
      </div>
      <div class="form-group">
        <label for="email">Email Address</label>
        <input type="email" id="email" name="email" required>
      </div>
      <div class="form-group">
        <label for="amount">Donation Amount (USD)</label>
        <input type="number" id="amount" name="amount" required>
      </div>
      <div class="form-group">
        <label for="purpose">Donation Purpose</label>
        <select id="purpose" name="purpose">
          <option value="general">General Support</option>
          <option value="temple">Temple Fund</option>
          <option value="charity">Charity Project</option>
        </select>
      </div>
      <button type="submit">Donate</button>
    </form>

    <div class="payment-info">
      <strong>PayPal</strong>
      Send donations to: <a href="mailto:yourpaypal@email.com">yourpaypal@email.com</a>

      <strong>Wise</strong>
      Account Name: Your Name<br>
      Currency: USD / GBP / MYR<br>
      Email: yourwise@email.com

      <strong>Bank Transfer</strong>
      Bank Name: Your Bank Name<br>
      Account Number: 12345678<br>
      SWIFT Code: ABCDGB2L<br>
      Country: United Kingdom
    </div>
  </div>
</body>
</html>
