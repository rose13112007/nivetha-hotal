# nivetha-hotal<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Royal Stay Hotel</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: linear-gradient(to right, #f8ede3, #dfd3c3);
      color: #333;
    }

    header {
      background: linear-gradient(to right, #2c3e50, #4ca1af);
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav {
      background: #1f2a38;
      padding: 12px;
      text-align: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-size: 18px;
      font-weight: bold;
    }

    nav a:hover {
      color: #ffd369;
    }

    .hero {
      height: 90vh;
      background: url('https://images.unsplash.com/photo-1566073771259-6a8506099945?auto=format&fit=crop&w=1400&q=80') no-repeat center center/cover;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      color: white;
    }

    .hero-content {
      background: rgba(0, 0, 0, 0.5);
      padding: 30px;
      border-radius: 15px;
    }

    .hero h1 {
      font-size: 48px;
      margin-bottom: 15px;
    }

    .hero p {
      font-size: 20px;
      margin-bottom: 20px;
    }

    .btn {
      background: #ffd369;
      color: #222;
      padding: 12px 25px;
      border: none;
      border-radius: 25px;
      text-decoration: none;
      font-size: 18px;
      cursor: pointer;
      font-weight: bold;
    }

    .btn:hover {
      background: #ffb703;
    }

    section {
      padding: 50px 20px;
      text-align: center;
    }

    .rooms, .services {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
      margin-top: 20px;
    }

    .card {
      background: white;
      width: 280px;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
      overflow: hidden;
      transition: 0.3s;
    }

    .card:hover {
      transform: scale(1.05);
    }

    .card img {
      width: 100%;
      height: 180px;
      object-fit: cover;
    }

    .card h3 {
      margin: 15px 0 10px;
      color: #2c3e50;
    }

    .card p {
      padding: 0 15px 20px;
    }

    .booking-form {
      max-width: 500px;
      margin: auto;
      background: white;
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }

    .booking-form input, .booking-form select {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 8px;
    }

    footer {
      background: #1f2a38;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Royal Stay Hotel</h1>
    <p>Luxury, Comfort, and Elegance</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#rooms">Rooms</a>
    <a href="#services">Services</a>
    <a href="#booking">Booking</a>
    <a
