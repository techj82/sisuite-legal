<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SISuite Opt-In Example</title>

  <style>
    body {
      font-family: Arial, sans-serif;
      background: #ffffff;
      margin: 0;
      padding: 40px;
      color: #333;
    }

    .container {
      max-width: 600px;
      margin: auto;
      text-align: center;
    }

    h1 {
      font-size: 32px;
      margin-bottom: 5px;
    }

    .description {
      font-size: 13px;
      color: #555;
      line-height: 1.4;
      margin-bottom: 30px;
    }

    label {
      display: block;
      text-align: left;
      margin-top: 20px;
      margin-bottom: 6px;
      font-weight: bold;
    }

    input[type="text"],
    input[type="email"] {
      width: 100%;
      padding: 12px;
      border: 1px solid #ccc;
      border-radius: 6px;
      font-size: 15px;
      margin-bottom: 15px;
    }

    .button {
      background: #f4c400;
      color: #000;
      padding: 14px 20px;
      border: none;
      border-radius: 6px;
      font-size: 16px;
      cursor: pointer;
      width: 100%;
      font-weight: bold;
      margin-top: 10px;
    }

    .button:hover {
      background: #e0b200;
    }

    .small {
      font-size: 13px;
      color: #555;
      line-height: 1.5;
      margin-top: 20px;
      text-align: left;
    }
  </style>
</head>

<body>
  <div class="container">

    <h1>SISuite</h1>

    <p class="description">
      Service Intake Suite — a reusable, AI-powered automation platform for service businesses
      (HVAC, plumbing, home services, etc.) that handles the full customer lifecycle: lead intake,
      AI-driven enrichment/qualification, scheduling and reminders, technician dispatch, CRM
      integration, and invoicing/payments.
    </p>

    <!-- FORM FIELDS -->
    <label for="firstname">First Name</label>
    <input type="text" id="firstname" placeholder="Enter your first name" />

    <label for="lastname">Last Name</label>
    <input type="text" id="lastname" placeholder="Enter your last name" />

    <label for="email">Email</label>
    <input type="email" id="email" placeholder="Enter your email" />

    <label for="phone">Phone Number (Optional)</label>
    <input type="text" id="phone" placeholder="Enter your phone number" />

    <!-- REQUIRED TWILIO COMPLIANCE TEXT -->
    <p class="small">
      By adding your number above, you accept the SISuite
      <a href="https://techj82.github.io/sisuite-legal/terms.html">Terms of Service</a> &
      <a href="https://techj82.github.io/sisuite-legal/privacy.html">Privacy Policy</a> and you are
      allowing SISuite to send transactional/informational SMS communications regarding account
      notifications, authentication, and customer care. Message frequency may vary. Message and data
      rates may apply. Reply HELP for help or STOP to opt-out.
    </p>

    <button class="button">Continue</button>

  </div>
</body>
</html>
