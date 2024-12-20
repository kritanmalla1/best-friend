<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Samarth Raj Acharya - The Ultimate Website</title>
    <style>
        /* General Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Roboto', sans-serif;
            background: linear-gradient(135deg, #ff416c, #ff4b2b);
            color: #fff;
            overflow-x: hidden;
            transition: background 0.5s ease;
        }

        header {
            text-align: center;
            padding: 80px 20px;
            background-color: transparent;
            animation: fadeInHeader 1.5s ease-out;
        }

        header h1 {
            font-size: 3.5rem;
            color: white;
            font-weight: 700;
            letter-spacing: 3px;
            text-transform: uppercase;
            text-shadow: 0px 0px 10px rgba(255, 0, 0, 0.8), 0px 0px 20px rgba(255, 0, 0, 0.6), 0px 0px 30px rgba(255, 0, 0, 0.4);
            margin-bottom: 20px;
            animation: fadeIn 1s ease-out;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: transparent;
            padding: 15px 0;
            margin-top: 20px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 12px 25px;
            font-size: 1.1rem;
            font-weight: 500;
            text-transform: uppercase;
            letter-spacing: 1.5px;
            margin: 0 15px;
            transition: color 0.3s ease, transform 0.3s ease, text-shadow 0.3s ease;
            animation: glowingText 1.5s infinite alternate;
        }

        nav a:hover {
            color: #ff4b2b;
            transform: translateY(-5px);
            text-shadow: 0px 0px 10px rgba(255, 0, 0, 0.8), 0px 0px 20px rgba(255, 0, 0, 0.6), 0px 0px 30px rgba(255, 0, 0, 0.4);
        }

        .main-content {
            text-align: center;
            padding: 60px 20px;
            max-width: 1100px;
            margin: auto;
            animation: fadeIn 1.5s ease-out;
        }

        .main-content h2 {
            font-size: 3rem;
            color: white;
            margin-bottom: 30px;
            text-transform: uppercase;
            letter-spacing: 2px;
            animation: fadeInContent 2s ease-out;
            text-shadow: 0px 0px 10px rgba(255, 0, 0, 0.8), 0px 0px 20px rgba(255, 0, 0, 0.6), 0px 0px 30px rgba(255, 0, 0, 0.4);
        }

        .main-content p {
            font-size: 1.1rem;
            line-height: 1.6;
            color: #f1f1f1;
            margin-bottom: 30px;
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
            animation: fadeInText 2s ease-out;
        }

        .main-content img {
            width: 250px;
            height: 250px;
            border-radius: 50%;
            object-fit: cover;
            margin-top: 20px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            animation: bounceIn 1s ease-out;
        }

        .main-content img:hover {
            transform: scale(1.1);
            box-shadow: 0px 10px 20px rgba(0, 0, 0, 0.1), 0px 0px 15px rgba(255, 255, 255, 0.7);
        }

        .main-content button {
            padding: 15px 40px;
            font-size: 1.2rem;
            background-color: #ff4b2b;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease, transform 0.2s ease;
            animation: slideUp 2s ease-out;
        }

        .main-content button:hover {
            background-color: #e04326;
            transform: scale(1.05);
        }

        footer {
            background-color: #2c3e50;
            text-align: center;
            padding: 20px 0;
            color: white;
            font-size: 1rem;
        }

        footer p {
            margin: 0;
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

        @keyframes fadeInContent {
            0% { opacity: 0; transform: translateY(30px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        @keyframes fadeInText {
            0% { opacity: 0; transform: translateX(-20px); }
            100% { opacity: 1; transform: translateX(0); }
        }

        @keyframes bounceIn {
            0% { transform: scale(0.5); opacity: 0; }
            60% { transform: scale(1.2); opacity: 1; }
            100% { transform: scale(1); }
        }

        @keyframes slideUp {
            0% { transform: translateY(50px); opacity: 0; }
            100% { transform: translateY(0); opacity: 1; }
        }

        @keyframes glowingText {
            0% { text-shadow: 0 0 5px #ff4b2b, 0 0 10px #ff4b2b, 0 0 15px #ff4b2b, 0 0 20px #ff4b2b; }
            50% { text-shadow: 0 0 10px #ff4b2b, 0 0 20px #ff4b2b, 0 0 30px #ff4b2b, 0 0 40px #ff4b2b; }
            100% { text-shadow: 0 0 5px #ff4b2b, 0 0 10px #ff4b2b, 0 0 15px #ff4b2b, 0 0 20px #ff4b2b; }
        }

        /* Additional Animations */
        @keyframes pulseEffect {
            0% { transform: scale(1); opacity: 0.8; }
            50% { transform: scale(1.05); opacity: 1; }
            100% { transform: scale(1); opacity: 0.8; }
        }

        @keyframes rotateEffect {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2.5rem;
            }

            .main-content h2 {
                font-size: 2rem;
            }

            .main-content p {
                font-size: 1rem;
            }

            nav {
                flex-direction: column;
                padding: 10px 0;
            }

            nav a {
                margin: 10px 0;
            }

            .main-content img {
                width: 200px;
                height: 200px;
            }

            .main-content button {
                padding: 12px 35px;
                font-size: 1.1rem;
            }
        }

    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Samarth Raj Acharya</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#hobbies">Hobbies</a>
            <a href="#skills">Skills</a>
            <a href="#funfacts">Fun Facts</a>
            <a href="#dreamvacation">Dream Vacation</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- Home Section -->
    <div id="home" class="main-content">
        <h2>Welcome to Samarth's Digital World</h2>
        <p>Explore the fascinating world of Samarth Raj Acharya. Gamer, Creator, Innovator.</p>
        <img src="https://i.imgur.com/pP3mL3k.jpeg" alt="Samarth's Photo" style="animation: pulseEffect 3s infinite;">
        <button onclick="window.location.href='#contact'" style="animation: pulseEffect 3s infinite;">Get in Touch</button>
    </div>

    <!-- About Section -->
    <div id="about" class="main-content">
        <h2>About Samarth</h2>
        <p>Samarth is a tech enthusiast, a creative Minecraft builder, and a passionate gamer. He loves to explore new challenges and build futuristic worlds in Minecraft. Apart from gaming, Samarth is highly involved in technology and video creation.</p>
    </div>

    <!-- Hobbies Section -->
    <div id="hobbies" class="main-content">
        <h2>Samarth's Hobbies</h2>
        <ul style="list-style-type: none; padding: 0;">
            <li><strong>Gaming:</strong> Building and surviving in Minecraft</li>
            <li><strong>Tech:</strong> Experimenting with gadgets and new software</li>
            <li><strong>Music:</strong> Enjoying and creating electronic music</li>
        </ul>
    </div>

    <!-- Skills Section -->
    <div id="skills" class="main-content">
        <h2>Samarth's Skills</h2>
        <ul style="list-style-type: none; padding: 0;">
            <li><strong>Minecraft Building:</strong> Master of creating complex structures</li>
            <li><strong>Coding:</strong> Proficient in JavaScript, Python, HTML/CSS</li>
            <li><strong>Video Editing:</strong> Excellent in editing and content creation</li>
        </ul>
    </div>

    <!-- Fun Facts Section -->
    <div id="funfacts" class="main-content">
        <h2>Fun Facts</h2>
        <ul style="list-style-type: none; padding: 0;">
            <li><strong>Favorite Color:</strong> Red</li>
            <li><strong>Favorite Food:</strong> Pizza</li>
            <li><strong>Dream Vacation:</strong> Bora Bora (Paradise Island)</li>
        </ul>
    </div>

    <!-- Dream Vacation Section -->
    <div id="dreamvacation" class="main-content">
        <h2>Samarth's Dream Vacation</h2>
        <p>Samarth dreams of a tropical paradise, Bora Bora, where he can relax and explore beautiful beaches and crystal-clear waters. It's the ultimate vacation destination!</p>
    </div>

    <!-- Contact Section -->
    <div id="contact" class="main-content">
        <h2>Contact Samarth</h2>
        <p>Want to collaborate with Samarth? Reach out to him on his social media:</p>
        <ul style="list-style-type: none; padding: 0;">
            <li><a href="https://www.facebook.com/samarthraj.acharya.7" target="_blank">Facebook</a></li>
            <li><a href="https://www.youtube.com/@samarthsplaying735" target="_blank">YouTube</a></li>
        </ul>
    </div>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 kritanmalla1. All Rights Reserved.</p>
    </footer>

</body>
</html>
