<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>خدمة شحن الألعاب - ببجي</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f9;
      margin: 0;
      padding: 0;
      direction: rtl;
      color: #333;
    }

    header {
      background-color: #2c3e50;
      color: #fff;
      text-align: center;
      padding: 20px;
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }

    .container {
      padding: 20px;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }

    .package {
      background-color: #fff;
      border: 1px solid #ddd;
      margin: 15px;
      padding: 20px;
      text-align: center;
      border-radius: 8px;
      width: 250px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease;
    }

    .package:hover {
      transform: scale(1.05);
    }

    .package h2 {
      color: #2c3e50;
      font-size: 1.8rem;
    }

    .package p {
      font-size: 1.2rem;
      color: #7f8c8d;
      margin: 10px 0;
    }

    .package .price {
      font-size: 1.5rem;
      color: #e74c3c;
      font-weight: bold;
    }

    .package .btn {
      display: inline-block;
      margin-top: 15px;
      padding: 10px 20px;
      background-color: #3498db;
      color: #fff;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
    }

    .package .btn:hover {
      background-color: #2980b9;
    }

    .payment-form {
      background-color: #fff;
      padding: 20px;
      margin-top: 30px;
      border-radius: 8px;
      width: 100%;
      max-width: 400px;
      margin-left: auto;
      margin-right: auto;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }

    .payment-form input {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    .payment-form button {
      background-color: #2ecc71;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      font-size: 1.2rem;
      width: 100%;
      cursor: pointer;
    }

    .payment-form button:hover {
      background-color: #27ae60;
    }

    footer {
      background-color: #2c3e50;
      color: #fff;
      text-align: center;
      padding: 10px;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>خدمة شحن الألعاب - ببجي</h1>
    <p>قم بشحن حسابك بباقات مختلفة وبأسعار مميزة!</p>
  </header>

  <!-- Packages Section -->
  <div class="container">
    <!-- Package 325 UC -->
    <div class="package">
      <h2>باقة 325 UC</h2>
      <p>شحن 325 UC للعبة ببجي</p>
      <p class="price">45,000 ليرة سورية</p>
      <a href="https://example.com/325uc" class="btn" target="_blank">اشترِ الآن</a>
    </div>
    <!-- Package 600 UC -->
    <div class="package">
      <h2>باقة 600 UC</h2>
      <p>شحن 600 UC للعبة ببجي</p>
      <p class="price">90,000 ليرة سورية</p>
      <a href="https://example.com/600uc" class="btn" target="_blank">اشترِ الآن</a>
    </div>
  </div>

  <!-- Payment Form -->
  <div class="payment-form">
    <h2>إتمام الدفع عبر سيريتل</h2>
    <form action="your_payment_processing_script.php" method="POST">
      <label for="seritel-number">رقم سيريتل</label>
      <input type="text" id="seritel-number" name="seritel_number" value="96854275" readonly>
      
      <label for="customer-id">ID العميل</label>
      <input type="text" id="customer-id" name="customer_id" placeholder="أدخل ID العميل" required>

      <button type="submit">إتمام الدفع</button>
    </form>
  </div>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 جميع الحقوق محفوظة</p>
  </footer>

</body>
</html>
