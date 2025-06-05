<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Donate to Our Mission</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Inter', sans-serif;
      background: linear-gradient(to bottom right, #f3f4f6, #e5e7eb);
      margin: 0;
      padding: 0;
    }
    .container {
      max-width: 600px;
      margin: 60px auto;
      background-color: #ffffff;
      padding: 40px;
      border-radius: 16px;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.05);
    }
    h1 {
      text-align: center;
      font-weight: 600;
      color: #1f2937;
      margin-bottom: 30px;
    }
    .form-group {
      margin-bottom: 25px;
    }
    label {
      display: block;
      margin-bottom: 8px;
      font-weight: 600;
      color: #374151;
    }
    input, select, button {
      width: 100%;
      padding: 12px;
      border: 1px solid #d1d5db;
      border-radius: 8px;
      font-size: 16px;
      box-sizing: border-box;
    }
    input:focus, select:focus {
      border-color: #2563eb;
      outline: none;
    }
    button {
      background-color: #2563eb;
      color: white;
      border: none;
      font-weight: 600;
      transition: background-color 0.3s;
      margin-top: 10px;
    }
    button:hover {
      background-color: #1d4ed8;
    }
    .note {
      font-size: 15px;
      color: #374151;
      margin-top: 30px;
      line-height: 1.6;
    }
    .note strong {
      color: #111827;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Support Our Mission</h1>
    <form action="#" method="POST">
      <div class="form-group">
        <label for="name">Full Name</label>
        <input type="text" id="name" name="name" required>
      </div>
      <div class="form-group">
        <label for="email">Email</label>
        <input type="email" id="email" name="email" required>
      </div>
      <div class="form-group">
        <label for="amount">Donation Amount (USD)</label>
        <input type="number" id="amount" name="amount" required>
      </div>
      <div class="form-group">
        <label for="purpose">Donation Purpose</label>
        <select id="purpose" name="purpose">
          <option value="general">General Fund</option>
          <option value="education">Education</option>
          <option value="health">Health</option>
        </select>
      </div>
      <button type="submit">Donate Now</button>
    </form>

    <div class="note">
      <p><strong>PayPal:</strong> <a href="mailto:yourpaypal@email.com">yourpaypal@email.com</a></p>
      <p><strong>Wise:</strong><br>
        Account name: Your Name<br>
        Currency: USD / GBP / MYR<br>
        Email: yourwise@email.com
      </p>
      <p><strong>Bank Transfer:</strong><br>
        Bank: Your Bank Name<br>
        Account Number: 12345678<br>
        SWIFT: ABCDGB2L<br>
        Country: United Kingdom
      </p>
    </div>
  </div>
</body>
</html>
