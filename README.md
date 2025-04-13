# website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Saavari - Book Your Ride</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Inter', sans-serif;
      margin: 0;
      padding: 0;
      background: #f8fafc;
      color: #1f2937;
    }
    header {
      background-color: #0f172a;
      color: white;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2rem;
    }
    .container {
      padding: 20px;
      max-width: 800px;
      margin: auto;
    }
    .booking-form {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.05);
    }
    .booking-form h2 {
      margin-bottom: 20px;
      color: #0f172a;
    }
    label {
      display: block;
      margin: 10px 0 5px;
    }
    input, select, button {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #cbd5e1;
      border-radius: 8px;
    }
    button {
      background-color: #0ea5e9;
      color: white;
      font-weight: 600;
      border: none;
      cursor: pointer;
    }
    button:hover {
      background-color: #0284c7;
    }
    footer {
      text-align: center;
      padding: 15px;
      background-color: #0f172a;
      color: white;
      margin-top: 40px;
    }
  </style>
</head>
<body>

<header>
  <h1>Saavari 🚗</h1>
  <p>Your Smart Ride Partner</p>
</header>

<div class="container">
  <div class="booking-form">
    <h2>Book a Ride</h2>
    <form>
      <label for="pickup">Pickup Location</label>
      <input type="text" id="pickup" placeholder="Enter pickup point" required />

      <label for="drop">Drop Location</label>
      <input type="text" id="drop" placeholder="Enter drop point" required />

      <label for="ride-type">Select Ride Type</label>
      <select id="ride-type">
        <option value="auto">Auto</option>
        <option value="mini">Mini</option>
        <option value="prime">Prime</option>
      </select>

      <label for="time">Pickup Time</label>
      <input type="time" id="time" />

      <button type="submit">Confirm Ride</button>
    </form>
  </div>
</div>

<footer>
  &copy; 2025 Saavari - Made for Easy Travel
</footer>

</body>
</html>
