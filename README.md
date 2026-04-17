<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>THE GHOST TECH MD | Matrix</title>
    <style>
        body {
            background-color: #000;
            color: #00ff00;
            font-family: 'Courier New', Courier, monospace;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        .matrix-bg {
            background: linear-gradient(rgba(0, 0, 0, 0.8), rgba(0, 0, 0, 0.8)), url('https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExNHJwamZ3Y2V3bm96ZzRycXp4eHh4eHh4eHh4eHh4eHh4eHh4JnBvcz1jJm9uPXNoYXJlX2lkJmN0PWc/o0vwzuFwCGAFO/giphy.gif');
            padding: 60px 20px;
            background-size: cover;
        }
        .ghost-logo {
            font-size: 100px;
            text-shadow: 0 0 20px #00ff00;
            animation: float 3s ease-in-out infinite;
        }
        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-20px); }
        }
        h1 { font-size: 2.2em; text-shadow: 0 0 15px #00ff00; letter-spacing: 5px; }
        .menu-card {
            border: 2px solid #00ff00;
            background: rgba(0, 30, 0, 0.6);
            border-radius: 15px;
            max-width: 380px;
            margin: 20px auto;
            padding: 25px;
            box-shadow: 0 0 30px rgba(0, 255, 0, 0.3);
        }
        .btn {
            display: block;
            border: 2px solid #00ff00;
            color: #00ff00;
            padding: 15px;
            margin: 15px 0;
            text-decoration: none;
            text-transform: uppercase;
            font-weight: bold;
            transition: 0.4s;
        }
        .btn:hover { background: #00ff00; color: #000; box-shadow: 0 0 40px #00ff00; }
        .footer { margin-top: 50px; font-size: 12px; color: #00ff00; opacity: 0.5; }
    </style>
</head>
<body>

    <div class="matrix-bg">
        <div class="ghost-logo">👻</div>
        <h1>THE GHOST TECH MD</h1>
        <p>[ ACCESS GRANTED ]</p>
    </div>

    <div class="container">
        <div class="menu-card">
            <p>"The Ghost is not a myth, it's a code."</p>
            <a href="https://keith-v2-pairing.onrender.com/" class="btn">PAIRING CODE 📱</a>
            <a href="https://dashboard.heroku.com/new?template=https://github.com/bbyderrick99-gif/Theghost-" class="btn">DEPLOY TO HEROKU 🚀</a>
            <a href="https://github.com/bbyderrick99-gif/Theghost-" class="btn">SOURCE CODE 🍴</a>
        </div>
    </div>

    <div class="footer">
        © 2026 GHOST TECH SYSTEM | USER: bbyderrick99-gif
    </div>

</body>
</html>
