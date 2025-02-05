# About-Me
Its about me!!!!
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Abdallah</title>
    <style>
        body {
            font-family: 'Press Start 2P', cursive; /* Retro gaming font */
            background: linear-gradient(135deg, #00bcd4, #ff4081); /* Cool gradient background */
            background-size: 400% 400%; /* Smooth gradient animation */
            animation: gradient 10s ease infinite;
            margin: 0;
            padding: 0;
            text-align: center;
            color: white;
            overflow-x: hidden;
        }

        @keyframes gradient {
            0% { background-position: 100% 0; }
            50% { background-position: 0 100%; }
            100% { background-position: 100% 0; }
        }

        .container {
            max-width: 1000px;
            margin: auto;
            background: rgba(0, 0, 0, 0.7); /* Semi-transparent black background */
            padding: 30px;
            border-radius: 20px;
            border: 5px solid #ff4081; /* Pink border */
            box-shadow: 0 0 20px rgba(255, 255, 255, 0.5);
            margin-top: 50px;
            transition: transform 0.3s ease;
        }

        .container:hover {
            transform: scale(1.05);
            box-shadow: 0 0 40px rgba(255, 255, 255, 0.7);
        }

        .section {
            background-color: rgba(255, 255, 255, 0.1);
            padding: 30px;
            margin: 20px 0;
            border-radius: 15px;
            box-shadow: 0 0 10px rgba(255, 255, 255, 0.2);
            transition: transform 0.3s ease;
        }

        .section:hover {
            transform: scale(1.05);
            box-shadow: 0 0 15px rgba(255, 255, 255, 0.4);
        }

        h1 {
            font-size: 3.5rem;
            color: #ff4081;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
            margin-bottom: 20px;
        }

        p {
            font-size: 1.5rem;
            line-height: 1.8;
            margin: 10px 0;
        }

        h2 {
            font-size: 2.5rem;
            margin-top: 0;
            text-shadow: 1px 1px 5px rgba(0, 0, 0, 0.5);
        }

        .links a {
            display: inline-block;
            margin: 20px 0;
            padding: 15px 30px;
            background: #ff4081;
            color: white;
            text-decoration: none;
            border-radius: 8px;
            font-size: 1.5rem;
            text-transform: uppercase;
            letter-spacing: 2px;
            box-shadow: 0 0 15px rgba(255, 255, 255, 0.4);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .links a:hover {
            background: #00bcd4;
            transform: scale(1.1);
            box-shadow: 0 0 25px rgba(255, 255, 255, 0.7);
            text-shadow: 1px 1px 5px rgba(0, 0, 0, 0.8);
        }

        /* Glowing effect on hover for the container */
        .container:hover {
            box-shadow: 0 0 30px rgba(255, 255, 255, 0.8);
            border: 5px solid #00bcd4;
        }

        /* Smooth scroll effect */
        html {
            scroll-behavior: smooth;
        }

        /* Button styling for interactivity */
        .scroll-button {
            margin-top: 30px;
            padding: 20px;
            font-size: 1.5rem;
            background-color: #00bcd4;
            border-radius: 12px;
            color: white;
            text-transform: uppercase;
            letter-spacing: 1px;
            cursor: pointer;
            border: none;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .scroll-button:hover {
            transform: scale(1.1);
            box-shadow: 0 0 20px rgba(0, 255, 255, 0.6);
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="section">
            <h1>About Abdallah</h1>
            <p>Hi! I'm Abdallah, a 9th grader from Winnipeg, Manitoba, Canada. I enjoy gaming, especially first-person shooters like *Call of Duty*, which I play often. When I'm not gaming, I enjoy spending time with my little sister Zahra and indulging in delicious meals like chicken and jollof rice. My Nigerian heritage plays a significant role in my daily life, and it’s always a good time when food brings us together. I'm also a huge fan of anime, especially *One Piece*. The adventures of Luffy and his crew are a huge source of inspiration, and I love getting lost in the world of the Grand Line, where the search for the ultimate treasure, the One Piece, never gets old. Watching anime is one of my favorite ways to unwind and dive into fantastic worlds, and *One Piece* holds a special place in my heart!</p>
        </div>

        <div class="section">
            <p>Outside of gaming, I’m passionate about learning and improving my skills in different areas. I am starting to learn PowerShell, and I'm excited to develop my knowledge in tech. I am also dedicated to my studies, and I always strive to do my best. Being Muslim is a central part of who I am, and it shapes how I approach life with discipline and faith.</p>
        </div>

        <div class="section">
            <h2>Quran</h2>
            <p>The Quran is a significant part of my life, providing spiritual guidance and helping me stay grounded. It shapes my worldview and strengthens my faith, helping me stay focused on what's truly important. I always make time to read and reflect on its teachings.</p>
        </div>

        <div class="section">
            <h2>One Piece</h2>
            <p>I absolutely love *One Piece*—it's my all-time favorite anime! Luffy and his crew's adventures on the Grand Line are an inspiration to me. The world-building, the fights, the story—it all pulls me in every time. The concept of chasing your dreams no matter the odds resonates deeply with me.</p>
        </div>

        <div class="section">
            <h2>Soccer</h2>
            <p>Soccer is one of my favorite sports. Whether it's playing with friends or watching a match, the energy, teamwork, and excitement are unmatched. I’m always up for a game, and I try to keep up with soccer leagues around the world. It’s a sport that brings people together, just like gaming and anime do for me!</p>
        </div>

        <button class="scroll-button" onclick="window.scrollTo({top: document.body.scrollHeight, behavior: 'smooth'});">Scroll to Links</button>

        <div class="section">
            <h2>Links</h2>
            <div class="links">
                <a href="https://www.callofduty.com" target="_blank">Call of Duty</a>
                <a href="https://www.roblox.com" target="_blank">Roblox</a>
                <a href="https://www.quran.com" target="_blank">Quran</a>
                <a href="https://www.onepiece.com" target="_blank">One Piece</a>
                <a href="https://www.socceracademy.com" target="_blank">Soccer Academy</a>
            </div>
        </div>
    </div>

    <script>
        // Additional JavaScript to improve interactivity can be added here.
    </script>
</body>
</html>
