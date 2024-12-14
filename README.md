<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Samarth Raj Acharya - Futuristic with Neon</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Roboto', sans-serif;
            background: linear-gradient(135deg, #1e2a3a, #3f4b67);
            color: #ecf0f1;
            line-height: 1.6;
            overflow-x: hidden;
            transition: all 0.3s ease;
        }

        header {
            background: linear-gradient(135deg, #e74c3c, #ff4081);
            padding: 80px 0;
            text-align: center;
            box-shadow: 0px 4px 20px rgba(0, 0, 0, 0.5);
            animation: fadeInHeader 1.5s ease-out;
            text-shadow: 0 0 10px #e74c3c, 0 0 20px #ff4081, 0 0 30px #ff4081;
        }

        header h1 {
            font-size: 5rem;
            color: #fff;
            margin: 0;
            text-transform: uppercase;
            letter-spacing: 4px;
            text-shadow: 0 0 10px #e74c3c, 0 0 20px #ff4081, 0 0 30px #ff4081;
            animation: slideIn 1s ease-out;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #2c3e50;
            padding: 15px 0;
            box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.2);
        }

        nav a {
            color: #fff;
            text-decoration: none;
            padding: 15px 30px;
            font-size: 1.2rem;
            text-transform: uppercase;
            letter-spacing: 2px;
            transition: background-color 0.3s ease, transform 0.2s ease;
            position: relative;
            text-shadow: 0 0 10px #e74c3c;
        }

        nav a::after {
            content: '';
            position: absolute;
            width: 100%;
            height: 2px;
            background-color: #e74c3c;
            bottom: -10px;
            left: 0;
            transform: scaleX(0);
            transform-origin: bottom right;
            transition: transform 0.3s ease-out;
        }

        nav a:hover::after {
            transform: scaleX(1);
            transform-origin: bottom left;
        }

        nav a:hover {
            background-color: #e74c3c;
            transform: scale(1.05);
            color: #fff;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
        }

        .main-content {
            padding: 60px 20px;
            text-align: center;
            max-width: 1200px;
            margin: auto;
            animation: fadeIn 1.5s ease-in-out;
        }

        .main-content h2 {
            font-size: 3.2rem;
            color: #e74c3c;
            margin-bottom: 20px;
            animation: slideInUp 1s ease-out;
            text-shadow: 0 0 10px #e74c3c;
        }

        .main-content p {
            font-size: 1.3rem;
            color: #bdc3c7;
            margin-bottom: 30px;
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
            animation: fadeInUp 1.5s ease-in-out 0.5s forwards;
        }

        .main-content img {
            width: 250px;
            height: 250px;
            border-radius: 50%;
            object-fit: cover;
            margin-top: 30px;
            animation: rotateIn 1.5s ease-out;
            transition: transform 0.3s ease;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5), 0 0 20px #e74c3c;
        }

        .main-content img:hover {
            transform: scale(1.1);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2), 0 0 30px #ff4081;
        }

        .main-content button {
            padding: 15px 40px;
            font-size: 1.5rem;
            background-color: #3498db;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease, transform 0.2s ease;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.2);
        }

        .main-content button:hover {
            background-color: #2980b9;
            transform: scale(1.05);
            box-shadow: 0px 6px 15px rgba(0, 0, 0, 0.3);
        }

        footer {
            background-color: #2c3e50;
            text-align: center;
            padding: 20px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
            font-size: 1.2rem;
        }

        footer p {
            color: #e74c3c;
        }

        /* Animations */
        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }

        @keyframes fadeInHeader {
            0% { opacity: 0; transform: translateY(-50px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        @keyframes slideIn {
            0% { transform: translateX(-100%); }
            100% { transform: translateX(0); }
        }

        @keyframes slideInUp {
            0% { transform: translateY(50px); opacity: 0; }
            100% { transform: translateY(0); opacity: 1; }
        }

        @keyframes fadeInUp {
            0% { transform: translateY(50px); opacity: 0; }
            100% { transform: translateY(0); opacity: 1; }
        }

        @keyframes rotateIn {
            0% { transform: rotate(-200deg); opacity: 0; }
            100% { transform: rotate(0deg); opacity: 1; }
        }

        /* Responsive design */
        @media (max-width: 768px) {
            header h1 {
                font-size: 3rem;
            }

            .main-content h2 {
                font-size: 2.5rem;
            }

            .main-content p {
                font-size: 1.2rem;
            }

            nav {
                flex-direction: column;
            }

            nav a {
                padding: 12px 25px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Samarth Raj Acharya</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#hobbies">Hobbies</a>
        <a href="#achievements">Achievements</a>
        <a href="#friends">Friends</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- Home Section -->
    <div id="home" class="main-content">
        <h2>Welcome to Samarth's Digital World!</h2>
        <p>Explore the futuristic world of Samarth Raj Acharya.</p>
    </div>

    <!-- About Section -->
    <div id="about" class="main-content">
        <h2>About Samarth</h2>
        <p>Samarth Raj Acharya is an innovative mind with a love for gaming, tech, and all things creative. He loves creating in the world of Minecraft and exploring new frontiers of gaming.</p>
        <img src="https://i.imgur.com/pP3mL3k.jpeg" alt="Samarth's Photo">
    </div>

    <!-- Hobbies Section -->
    <div id="hobbies" class="main-content">
        <h2>Samarth's Hobbies</h2>
        <ul>
            <li><strong>Gaming:</strong> Building futuristic worlds in Minecraft.</li>
            <li><strong>Technology:</strong> Staying updated with the latest in tech and gadgets.</li>
            <li><strong>Music:</strong> Listening to electronic music that fuels creativity.</li>
        </ul>
    </div>

    <!-- Achievements Section -->
    <div id="achievements" class="main-content">
        <h2>Achievements</h2>
        <ul>
            <li>Built numerous futuristic Minecraft cities with cutting-edge designs.</li>
            <li>Created a unique gaming channel on YouTube, exploring and streaming Minecraft.</li>
            <li>Mastered various gaming strategies, showcasing skills on his YouTube channel.</li>
        </ul>
    </div>

    <!-- Friends Section -->
    <div id="friends" class="main-content">
        <h2>Samarth's Friends</h2>
        <p>Samarth is supported by a creative and tech-savvy group of friends.</p>
    </div>

    <!-- Contact Section -->
    <div id="contact" class="main-content">
        <h2>Contact Samarth</h2>
        <p>Get in touch with Samarth via his social media accounts:</p>
        <ul>
            <li><a href="https://www.facebook.com/samarthraj.acharya.7" target="_blank">Facebook</a></li>
            <li><a href="https://www.youtube.com/@samarthsplaying735" target="_blank">YouTube</a></li>
        </ul>
    </div>

    <footer>
        <p>&copy; 2024 Samarth Raj Acharya | All Rights Reserved</p>
    </footer>

    <script>
        // Add interactivity if needed, such as animations or interactions
    </script>
</body>
</html>
