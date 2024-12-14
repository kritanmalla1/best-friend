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
            font-family: 'Arial', sans-serif;
            background-color: #111; /* Dark background for a modern look */
            color: #fff;
            line-height: 1.6;
            overflow-x: hidden;
        }

        header {
            text-align: center;
            padding: 80px 20px;
            background: linear-gradient(45deg, #ff4b2b, #ff416c); /* Gradient background */
            color: white;
            animation: fadeInHeader 1.5s ease-in-out;
        }

        header h1 {
            font-size: 4.5em;
            letter-spacing: 4px;
            text-transform: uppercase;
            margin-bottom: 20px;
            font-weight: bold;
            text-shadow: 3px 3px 10px rgba(0, 0, 0, 0.7);
            animation: slideIn 1s ease-out;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: rgba(255, 255, 255, 0.1);
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
            position: sticky;
            top: 0;
            z-index: 100;
            transition: all 0.3s ease-in-out;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 18px 30px;
            font-size: 1.3em;
            text-transform: uppercase;
            letter-spacing: 1px;
            transition: all 0.3s ease;
        }

        nav a:hover {
            background-color: #ff4b2b;
            transform: scale(1.1);
            box-shadow: 0 5px 15px rgba(255, 0, 0, 0.5);
        }

        .main-content {
            padding: 70px 20px;
            text-align: center;
            background-color: #222;
            margin: 40px auto;
            border-radius: 15px;
            max-width: 900px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
            animation: fadeIn 1.5s ease-in-out 0.5s forwards;
        }

        .main-content h2 {
            font-size: 3.5em;
            margin-bottom: 20px;
            font-weight: bold;
            text-shadow: 3px 3px 10px rgba(0, 0, 0, 0.6);
            animation: slideIn 1s ease-out;
        }

        .main-content p {
            font-size: 1.4em;
            color: #ddd;
            margin-bottom: 25px;
            animation: fadeIn 1s ease-in-out 1s forwards;
        }

        .main-content img {
            width: 250px;
            height: 250px;
            border-radius: 50%;
            object-fit: cover;
            margin-top: 25px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.6);
            transition: transform 0.4s ease, box-shadow 0.4s ease;
        }

        .main-content img:hover {
            transform: scale(1.1);
            box-shadow: 0 8px 20px rgba(255, 0, 0, 0.7);
        }

        .main-content ul {
            list-style: none;
            margin-top: 30px;
            text-align: left;
            font-size: 1.3em;
            padding: 0;
            color: #eee;
            animation: fadeIn 1s ease-in-out 1.5s forwards;
        }

        .main-content li {
            margin-bottom: 15px;
        }

        .card {
            background-color: #333;
            margin: 20px;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.5);
            transition: all 0.3s ease;
        }

        .card:hover {
            background-color: #ff4b2b;
            transform: translateY(-10px);
            box-shadow: 0 12px 25px rgba(0, 0, 0, 0.7);
        }

        footer {
            background-color: #111;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
            animation: fadeIn 1.5s ease-in-out 2s forwards;
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

        /* Responsive Design */
        @media (max-width: 768px) {
            header h1 {
                font-size: 3.5em;
            }

            nav a {
                font-size: 1.1em;
            }

            .main-content h2 {
                font-size: 2.5em;
            }

            .main-content p {
                font-size: 1.2em;
            }

            .card {
                padding: 15px;
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

    <div class="main-content">
        <h2>About Samarth Raj Acharya</h2>
        <p>Samarth Raj Acharya is not only a close friend but a true inspiration. We've shared unforgettable moments, and his positive energy is contagious!</p>
        
        <!-- Image with the provided URL -->
        <img src="https://i.imgur.com/pP3mL3k.jpeg" alt="Samarth's Photo">
        
        <h3>Fun Facts About Samarth</h3>
        <ul>
            <li><strong>Favorite Color:</strong> Red</li>
            <li><strong>Hobby:</strong> Playing MINECRAFT</li>
            <li><strong>Favorite Movie:</strong> idk</li>
            <li><strong>Dream Vacation:</strong> idk</li>
        </ul>
        
        <h3>Our Best Memories</h3>
        <div class="card">
            <p>We’ve had countless adventures together, late-night deep talks. Here's to many more!</p>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 Best Friend Tribute | Created with Love</p>
    </footer>
</body>
</html>
