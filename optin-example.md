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

    .wrapper {
      display: flex;
      gap: 40px;
      max-width: 1100px;
      margin: auto;
    }

    .form-box {
      flex: 1;
      border: 1px solid #ddd;
      padding: 30px;
      border-radius: 8px;
    }

    .side-notes {
      width: 300px;
      border-left: 4px solid #f4c400;
      padding-left: 20px;
    }

    h1 {
      margin: 0;
      font-size: 28px;
    }

    h2 {
      margin-top: 8px;
      font-size: 14px;
      font-weight: normal;
      color: #555;
      line-height: 1.4;
    }

    label {
      display: block;
      margin-top: 25px;
      margin-bottom: 8px;
      font-weight: bold;
    }

    input[type="text"] {
      width: 100%;
      padding: 12px;
      border: 1px solid #ccc;
      border-radius: 6px;
      font-size: 15px;
      margin-bottom: 20px;
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
      font-size: 14px;
      color: #555;
      line-height: 1.5;
    }

    .side-notes h3 {
      margin-top: 0;
      font-size: 18px;
    }

    .side-notes ul {
      padding-left: 20px;
      margin-top: 10px;
    }

    .side-notes li {
      margin-bottom: 8px;
      font-size: 14px;
      color: #444;
    }

    .transactional {
      margin-top: 20px;
      color: #c00;
      font-weight: bold;
    }
  </style>
</head>

<body>
  <div class="wrapper">

    <!-- LEFT SIDE: FORM -->
    <div class="form-box">
      <h1>SISuite</h1>
      <h2>
        Service Intake Suite — a reusable, AI-powered automation platform for service
        businesses (HVAC, plumbing, home services, etc.) that handles the full customer
        lifecycle: lead intake, AI-driven enrichment/qualification, scheduling and
        reminders, technician dispatch, CRM integration, and invoicing/payments.
      </h2>

      <label for="phone">Phone Number (Optional)</label>
      <input type="text" id="phone" placeholder="Enter your phone number" />

      <p class="small">
        By adding your number above, you accept the SISuite
        <a href="https://techj82.github.io/sisuite-legal/terms.html">Terms of Service</a>
        &amp;
        <a href="https://techj82.github.io/sisuite-legal/privacy.html">Privacy Policy</a>
        and you are allowing SISuite to send transactional SMS authentication messages
        such as login verification codes, password reset confirmations, and security alerts.
        Message frequency may vary. Message and data rates may apply. Reply HELP for help or STOP to opt-out.
      </p>

      <button class="button">Continue</button>
    </div>

    <!-- RIGHT SIDE: COMPLIANCE NOTES -->
    <div class="side-notes">
      <h3>Compliance requirements:</h3>
      <ul>
        <li>Brand/Business name must match the campaign</li>
        <li>Phone number collection box must be optional</li>
        <li>Opt-in language must match the Authentication/OTP use case</li>
      </ul>

      <div class="transactional">Transactional — No checkbox</div>
    </div>

  </div>
</body>
</html>
