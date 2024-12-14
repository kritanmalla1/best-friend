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
            background: linear-gradient(to bottom right, #e60000, #ff3333);
            color: white;
            line-height: 1.6;
        }

        header {
            text-align: center;
            padding: 80px 20px;
            animation: fadeIn 1s ease-in-out;
            background-color: rgba(0, 0, 0, 0.6);
        }

        header h1 {
            font-size: 3.5em;
            letter-spacing: 4px;
            text-transform: uppercase;
            margin-bottom: 20px;
            text-shadow: 2px 2px 10px rgba(0, 0, 0, 0.5);
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: rgba(255, 255, 255, 0.1);
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 18px 30px;
            font-size: 1.2em;
            text-transform: uppercase;
            letter-spacing: 1px;
            transition: all 0.3s ease;
        }

        nav a:hover {
            background-color: #e60000;
            transform: scale(1.1);
            box-shadow: 0 5px 15px rgba(255, 0, 0, 0.5);
        }

        .main-content {
            padding: 50px 20px;
            text-align: center;
            animation: fadeIn 1s ease-in-out 0.5s forwards;
            background-color: rgba(0, 0, 0, 0.6);
            margin: 30px auto;
            border-radius: 10px;
            max-width: 800px;
        }

        .main-content h2 {
            font-size: 2.8em;
            margin-bottom: 20px;
            text-shadow: 2px 2px 10px rgba(0, 0, 0, 0.5);
        }

        .main-content p {
            font-size: 1.2em;
            color: #ddd;
            margin-bottom: 20px;
        }

        .main-content img {
            width: 220px;
            height: 220px;
            border-radius: 50%;
            object-fit: cover;
            margin-top: 20px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.5);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .main-content img:hover {
            transform: scale(1.1);
            box-shadow: 0 8px 20px rgba(255, 0, 0, 0.5);
        }

        .main-content ul {
            list-style: none;
            margin-top: 20px;
            text-align: left;
            font-size: 1.1em;
            padding: 0;
            color: #eee;
        }

        .main-content li {
            margin-bottom: 10px;
        }

        footer {
            background-color: rgba(0, 0, 0, 0.8);
            color: white;
            text-align: center;
            padding: 20px 20px;
            position: fixed;
            width: 100%;
            bottom: 0;
            animation: fadeIn 1s ease-in-out 1s forwards;
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

    </style>
</head>
<body>
    <header>
        <h1>Meet My Best Friend</h1>
    </header>
    
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#hobbies">Hobbies</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="main-content">
        <h2>About Samarth Raj Acharya
        <p>Let me tell you about my amazing best friend, Samarth. We’ve had so many great memories together, and their personality is truly one of a kind!</p>
        
        <img src="https://www.facebook.com/photo/?fbid=104716301179966&set=a.104716331179963" alt="Best Friend's Photo">
        
        <h3>Fun Facts About Samarth</h3>
        <ul>
            <li><strong>Favorite Color:</strong> Red</li>
            <li><strong>Hobby:</strong> Playing MINECRAFT</li>
            <li><strong>Favorite Movie:</strong> idk</li>
            <li><strong>Dream Vacation:</strong> idk</li>
        </ul>
        
        <h3>Our Best Memories</h3>
        <p>From late-night conversations to epic adventures, Samarth and I share so many wonderful moments. Here are just a few of the best ones!</p>
    </div>

    <footer>
        <p>&copy; 2024 Best Friend Tribute</p>
    </footer>
</body>
</html>
