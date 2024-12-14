<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About My Best Friend</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Roboto', sans-serif;
            background-color: #111;
            color: #fff;
            line-height: 1.6;
            overflow-x: hidden;
        }

        header {
            text-align: center;
            padding: 100px 20px;
            background: linear-gradient(45deg, #e63946, #f1faee);
            color: white;
            animation: fadeInHeader 1.5s ease-in-out;
        }

        header h1 {
            font-size: 4.8em;
            font-weight: bold;
            text-transform: uppercase;
            margin-bottom: 20px;
            letter-spacing: 5px;
            text-shadow: 3px 3px 10px rgba(0, 0, 0, 0.6);
            animation: slideIn 1s ease-out;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: rgba(0, 0, 0, 0.8);
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.4);
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 20px 30px;
            font-size: 1.3em;
            text-transform: uppercase;
            letter-spacing: 1px;
            font-weight: 500;
            transition: all 0.3s ease;
            text-align: center;
            animation: fadeInUp 1s ease-in-out;
        }

        nav a:hover {
            background-color: #e63946;
            color: #111;
            transform: scale(1.1);
            box-shadow: 0 8px 16px rgba(255, 0, 0, 0.7);
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.5);
        }

        .main-content {
            padding: 80px 20px;
            text-align: center;
            background-color: #222;
            margin: 40px auto;
            border-radius: 20px;
            max-width: 900px;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.6);
            animation: fadeIn 1.5s ease-in-out 0.5s forwards;
        }

        .main-content h2 {
            font-size: 3.8em;
            margin-bottom: 20px;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 3px;
            text-shadow: 3px 3px 15px rgba(0, 0, 0, 0.8);
            color: #e63946;
            animation: slideInUp 1.2s ease-out;
        }

        .main-content p {
            font-size: 1.4em;
            color: #ccc;
            margin-bottom: 30px;
            animation: fadeInUp 1.2s ease-in-out 1s forwards;
        }

        .main-content img {
            width: 250px;
            height: 250px;
            border-radius: 50%;
            object-fit: cover;
            margin-top: 30px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.6);
            transition: transform 0.4s ease, box-shadow 0.4s ease;
            animation: rotateIn 1.5s ease-in-out;
        }

        .main-content img:hover {
            transform: scale(1.1);
            box-shadow: 0 8px 20px rgba(255, 0, 0, 0.7);
        }

        .main-content ul {
            list-style: none;
            margin-top: 30px;
            text-align: left;
            font-size: 1.4em;
            padding: 0;
            color: #ddd;
            animation: fadeInUp 1.2s ease-in-out 1.5s forwards;
        }

        .main-content li {
            margin-bottom: 20px;
            animation: fadeInLeft 1s ease-out;
        }

        footer {
            background-color: #111;
            color: white;
            text-align: center;
            padding: 30px;
            margin-top: 50px;
            font-size: 1.2em;
            box-shadow: 0 -4px 8px rgba(0, 0, 0, 0.5);
            animation: fadeIn 1.5s ease-in-out 2s forwards;
        }

        footer p {
            font-weight: bold;
            color: #e63946;
        }

        /* Animations */
        @keyframes fadeIn {
            0% {
                opacity: 0;
            }
            100% {
                opacity: 1;
            }
        }

        @keyframes fadeInHeader {
            0% {
                opacity: 0;
                transform: translateY(-50px);
            }
            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes slideIn {
            0% {
                transform: translateX(-100%);
            }
            100% {
                transform: translateX(0);
            }
        }

        @keyframes slideInUp {
            0% {
                transform: translateY(50px);
                opacity: 0;
            }
            100% {
                transform: translateY(0);
                opacity: 1;
            }
        }

        @keyframes fadeInUp {
            0% {
                transform: translateY(50px);
                opacity: 0;
            }
            100% {
                transform: translateY(0);
                opacity: 1;
            }
        }

        @keyframes bounceIn {
            0% {
                transform: scale(0);
            }
            60% {
                transform: scale(1.1);
            }
            100% {
                transform: scale(1);
            }
        }

        @keyframes rotateIn {
            0% {
                transform: rotate(-200deg);
                opacity: 0;
            }
            100% {
                transform: rotate(0deg);
                opacity: 1;
            }
        }

        @keyframes fadeInLeft {
            0% {
                transform: translateX(-50px);
                opacity: 0;
            }
            100% {
                transform: translateX(0);
                opacity: 1;
            }
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            header h1 {
                font-size: 3.5em;
            }

            nav a {
                font-size: 1.2em;
            }

            .main-content h2 {
                font-size: 2.5em;
            }

            .main-content p {
                font-size: 1.2em;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Meet Samarth Raj Acharya</h1>
    </header>
    
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#hobbies">Hobbies</a>
        <a href="#contact">Contact</a>
    </nav>

    <div id="home" class="main-content">
        <h2>Welcome to My Best Friend's World!</h2>
        <p>Discover the journey and story of Samarth Raj Acharya, a person full of life, passion, and creativity!</p>
    </div>

    <div id="about" class="main-content">
        <h2>About Samarth</h2>
        <p>Samarth is a creative and inspiring individual who loves to explore new things, whether it be in technology, music, or art. His passion for life and positive energy is contagious!</p>
        <img src="https://i.imgur.com/pP3mL3k.jpeg" alt="Samarth's Photo">
    </div>

    <div id="hobbies" class="main-content">
        <h2>Hobbies and Interests</h2>
        <ul>
               <li><strong>Minecraft:</strong> Samarth enjoys building, exploring, and creating in the world of Minecraft, where his creativity truly shines!</li>
            <li><strong>Traveling:</strong> Exploring new places and cultures is a big part of his life.</li>
            <li><strong>Tech Enthusiast:</strong> He's fascinated by the latest trends in technology.</li>
        </ul>
    </div>

    <div id="contact" class="main-content">
        <h2>Contact Samarth</h2>
        <p>Want to get in touch with Samarth? Follow him on his social media account:</p>
        <ul>
            <li><a href="https://www.facebook.com/samarthraj.acharya.7" target="_blank">Facebook</a></li>
        </ul>
    </div>

    <footer>
        <p>&copy; 2024 Best Friend Tribute | Created with Love</p>
    </footer>
</body>
</html>
