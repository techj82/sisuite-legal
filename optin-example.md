<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SISuite SMS Opt-In Example</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f7f7f7;
      color: #333;
      margin: 0;
      padding: 40px;
    }
    .container {
      max-width: 700px;
      margin: auto;
      background: #fff;
      padding: 30px;
      border-radius: 8px;
      border: 1px solid #ddd;
    }
    h1 {
      margin-bottom: 5px;
      color: #222;
    }
    h2 {
      font-size: 15px;
      font-weight: normal;
      color: #555;
      margin-bottom: 25px;
    }
    label {
      display: block;
      margin-bottom: 8px;
      font-weight: bold;
    }
    input[type="text"] {
      width: 100%;
      padding: 12px;
      border: 1px solid #ccc;
      border-radius: 6px;
      margin-bottom: 20px;
      font-size: 15px;
    }
    .button {
      background: #f4c400; /* SISuite yellow */
      color: #000;
      padding: 14px 20px;
      border: none;
      border-radius: 6px;
      font-size: 16px;
      cursor: pointer;
      width: 100%;
      font-weight: bold;
    }
    .button:hover {
      background: #e0b200;
    }
    .notes {
      margin-top: 30px;
      padding: 15px;
      background: #fafafa;
      border-left: 4px solid #f4c400;
    }
    .small {
      font-size: 14px;
      color: #555;
      line-height: 1.5;
    }
  </style>
</head>

<body>
  <div class="container">
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
      By adding your phone number, you accept the SISuite
      <a href="https://techj82.github.io/sisuite-legal/terms.html">Terms of Service</a>
      and
      <a href="https://techj82.github.io/sisuite-legal/privacy.html">Privacy Policy</a>
      and agree to receive transactional SMS authentication messages from SISuite.
      Message frequency varies. Reply HELP for help or STOP to opt out. Msg&Data rates may apply.
    </p>

    <button class="button">Continue</button>

    <div class="notes">
      <p><strong>Compliance Notes:</strong></p>
      <ul class="small">
        <li>Brand/business name matches the campaign</li>
        <li>Phone number collection is optional</li>
        <li>Opt-in language matches the Authentication/OTP use case</li>
        <li>Transactional — No checkbox required</li>
      </ul>
    </div>

    <h3>SMS Keyword Opt-In (Alternative Method)</h3>
    <p class="small">
      Users may also opt in by texting <strong>SISUITE</strong> to <strong>3334445555</strong>.
      By texting SISUITE, users agree to receive one-time passcodes (OTP) and login verification
      messages for authentication.
    </p>

    <h3>Opt-In Confirmation Message</h3>
    <p class="small">
      <strong>SISuite:</strong> You are now opted in to receive one-time passcodes (OTP)
      for login and identity verification. Reply HELP for assistance or STOP to opt out.
    </p>

    <h3>Opt-Out Message</h3>
    <p class="small">
      You have successfully been unsubscribed. You will not receive any more messages from
      this number. Reply START to resubscribe.
    </p>

    <h3>Help Message</h3>
    <p class="small">
      Reply STOP to unsubscribe. Msg&Data Rates May Apply.
    </p>
  </div>
</body>
</html>
