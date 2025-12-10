<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Official server website for our Geopolitical Minecraft community.">
  <title>Geopolitical Minecraft Server</title>
  
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  
  <!-- Styles -->
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Inter', sans-serif;
    }

    body {
      background: linear-gradient(135deg, #1f1c2c, #928dab);
      color: #fff;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    header {
      padding: 2rem;
      text-align: center;
      background: rgba(0,0,0,0.5);
      backdrop-filter: blur(10px);
    }

    header h1 {
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
      color: #f0d67b;
    }

    header p {
      font-size: 1.2rem;
      color: #e0e0e0;
    }

    main {
      flex: 1;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: 2rem;
      text-align: center;
    }

    main h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
      color: #f8b400;
    }

    main a.button {
      display: inline-block;
      padding: 1rem 2rem;
      margin-top: 1rem;
      background: #f8b400;
      color: #1f1c2c;
      font-weight: 600;
      text-decoration: none;
      border-radius: 8px;
      transition: background 0.3s, transform 0.3s;
    }

    main a.button:hover {
      background: #ffd15c;
      transform: scale(1.05);
    }

    footer {
      padding: 1rem 2rem;
      text-align: center;
      font-size: 0.9rem;
      background: rgba(0,0,0,0.4);
      backdrop-filter: blur(10px);
    }

    @media (max-width: 600px) {
      header h1 { font-size: 2rem; }
      main h2 { font-size: 1.5rem; }
      main a.button { padding: 0.8rem 1.5rem; }
    }
  </style>
</head>
<body>

  <header>
    <h1>Geopolitical Minecraft Server</h1>
    <p>Welcome to our official community website</p>
  </header>

  <main>
    <h2>Join Our Server Today!</h2>
    <p>IP Address: <strong>play.yourserver.com</strong></p>
    <a class="button" href="https://discord.gg/YOURSERVERLINK" target="_blank">Join Discord</a>
    <a class="button" href="https://docs.google.com/document/d/1HYHfjA6p3PQEadXiR0ExEz6emdcRSdyWFVcYeZwYDRc/edit?usp=sharing" target="_blank">View Server Rules</a>
  </main>

  <footer>
    &copy; 2025 Geopolitical Minecraft Server. All rights reserved.
  </footer>

</body>
</html>
