<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Diet To Fit | Book Consultation</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f7f9f7;
      margin: 0;
      padding: 0;
    }
    .container {
      max-width: 500px;
      margin: 40px auto;
      background: #ffffff;
      padding: 25px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
    h1 {
      text-align: center;
      color: #2e7d32;
      margin-bottom: 5px;
    }
    p {
      text-align: center;
      color: #555;
      margin-bottom: 20px;
    }
    label {
      display: block;
      margin-bottom: 5px;
      font-weight: bold;
    }
    input, select, textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      width: 100%;
      background: #f57c00;
      color: #fff;
      padding: 12px;
      border: none;
      border-radius: 5px;
      font-size: 16px;
      cursor: pointer;
    }
    button:hover {
      background: #ef6c00;
    }
    .footer {
      text-align: center;
      margin-top: 15px;
      font-size: 14px;
      color: #777;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Diet To Fit</h1>
    <p>Book Your Nutrition Consultation</p>

    <form>
      <label>Full Name</label>
      <input type="text" placeholder="Enter your name" required />

      <label>Mobile Number</label>
      <input type="tel" placeholder="Enter your mobile number" required />

      <label>Email Address</label>
      <input type="email" placeholder="Enter your email" />

      <label>Goal</label>
      <select required>
        <option value="">Select your goal</option>
        <option>Weight Loss</option>
        <option>Fat Loss</option>
        <option>Healthy Lifestyle</option>
        <option>Weight Gain</option>
      </select>

      <label>Your Message</label>
      <textarea rows="3" placeholder="Tell us about your health goal"></textarea>

      <button type="submit">Book Consultation</button>
    </form>

    <div class="footer">
      Eat Right • Get Fit 💪🥗
    </div>
  </div>
</body>
</html>
