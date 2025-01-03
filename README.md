<!DOCTYPE html>
<html>
  <head>
    <title>Choose Your Perfect Plan</title>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Sono:wght@400;700&display=swap"
      rel="stylesheet"
    />
    <style>
      body {
        font-family: "Sono", sans-serif;
        background-color: whitesmoke;
        margin: 0;
        padding: 0;
      }
      h1 {
        text-align: center;
        font-size: 36px;
        color: #333;
        font-weight: bold;
        margin-top: 40px;
        margin-bottom: 20px;
      }

      .pricing-container {
        display: flex;
        justify-content: space-between;
        gap: 20px;
        padding: 40px;
        max-width: 1200px;
        margin: 0 auto;
      }

      .pricing-plan {
        background-color: #fff;
        border-radius: 10px;
        box-shadow: 0 4px 10px rgba(16, 17, 16, 0.1);
        padding: 25px;
        text-align: center;
        transition: transform 0.3s ease;
        flex: 1;
      }

      .pricing-plan:hover {
        transform: scale(1.05);
        background-color: aliceblue;
      }

      .plan-title {
        color: #333;
        font-size: 28px;
        font-weight: bold;
        margin-bottom: 15px;
      }

      .plan-price {
        font-size: 48px;
        color: #2d82b7;
        font-weight: bold;
        margin-bottom: 15px;
      }

      .plan-features {
        list-style: none;
        padding: 0;
        margin: 0;
      }

      .plan-features li {
        margin-bottom: 20px;
      }

      .plan-button {
        padding: 15px 20px;
        background-color: #2d82b7;
        color: #fff;
        border-radius: 5px;
        border: none;
        cursor: pointer;
        transition: background-color 0.3s ease;
      }

      .plan-button:hover {
        background-color: #1a5f80;
      }

      @media (max-width: 768px) {
        .pricing-container {
          flex-direction: column;
          padding: 20px;
        }

        .pricing-plan {
          max-width: 100%;
        }
      }
    </style>
  </head>

  <body>
    <h1>Pricing Plans to Suit Your Lifestyle!</h1>
    <div class="pricing-container">
      <div class="pricing-plan">
        <div class="plan-title">Basic</div>
        <div class="plan-price">$9.99/month</div>
        <ul class="plan-features">
          <li>✅ 10GB Storage</li>
          <li>✅ 1 User</li>
          <li>🚫 No Support</li>
        </ul>
        <button class="plan-button">Sign Up</button>
      </div>
      <div class="pricing-plan">
        <div class="plan-title">Standard</div>
        <div class="plan-price">$19.99/month</div>
        <ul class="plan-features">
          <li>✅ 50GB Storage</li>
          <li>✅ 5 Users</li>
          <li>✅ Phone & Email Support</li>
        </ul>
        <button class="plan-button">Sign Up</button>
      </div>
      <div class="pricing-plan">
        <div class="plan-title">Premium</div>
        <div class="plan-price">$49.99/month</div>
        <ul class="plan-features">
          <li>✅ 100GB Storage</li>
          <li>✅ 10 Users</li>
          <li>✅ 24/7 Support</li>
        </ul>
        <button class="plan-button">Sign Up</button>
      </div>
    </div>
  </body>
</html>
