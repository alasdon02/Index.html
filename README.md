<!DOCTYPE html><html lang="en">

<head>

  <meta charset="UTF-8" />

  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <title>Aladson Global Services (AGS)</title>

  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">

  <style>

    * {

      box-sizing: border-box;

    }

    body {

      font-family: 'Inter', sans-serif;

      margin: 0;

      background-color: #f0f2f5;

      color: #333;

    }

    header {

      background-color: #003366;

      color: white;

      padding: 1rem 2rem;

      display: flex;

      align-items: center;

      justify-content: space-between;

      box-shadow: 0 2px 4px rgba(0,0,0,0.1);

    }

    header img {

      height: 60px;

    }

    header h1 {

      font-size: 1.8rem;

      margin: 0;

    }

    main {

      max-width: 1200px;

      margin: auto;

      padding: 3rem 2rem;

    }

    .intro {

      text-align: center;

      margin-bottom: 3rem;

    }

    .intro h2 {

      font-size: 2.2rem;

      color: #003366;

    }

    .services {

      display: grid;

      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));

      gap: 2rem;

    }

    .card {

      background: white;

      padding: 2rem;

      border-radius: 12px;

      box-shadow: 0 6px 15px rgba(0, 0, 0, 0.1);

      text-align: center;

      transition: transform 0.3s ease, box-shadow 0.3s ease;

    }

    .card:hover {

      transform: translateY(-5px);

      box-shadow: 0 10px 20px rgba(0, 0, 0, 0.15);

    }

    .card img {

      height: 80px;

      margin-bottom: 1.5rem;

    }

    .card h3 {

      font-size: 1.5rem;

      color: #003366;

      margin-bottom: 1rem;

    }

    .card p {

      font-size: 1rem;

      color: #555;

    }

    .card a {

      display: inline-block;

      margin-top: 1.5rem;

      padding: 0.6rem 1.4rem;

      background-color: #003366;

      color: white;

      text-decoration: none;

      border-radius: 8px;

      transition: background-color 0.2s ease;

    }

    .card a:hover {

      background-color: #001f4d;

    }

    footer {

      text-align: center;

      padding: 2rem;

      background: #003366;

      color: white;

      margin-top: 3rem;

    }

  </style>

</head>
