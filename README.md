<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Modern Stylish Website</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f7f7f7;
            color: #333;
            line-height: 1.6;
        }

        header {
            background-color: #e60000; /* Red color */
            color: white;
            text-align: center;
            padding: 50px 20px;
            animation: fadeIn 1s ease-in-out;
        }

        header h1 {
            font-size: 3em;
            letter-spacing: 2px;
            text-transform: uppercase;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #ff3333;
            animation: slideIn 1s ease-in-out;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 15px 25px;
            font-size: 1.2em;
            text-transform: uppercase;
            transition: background-color 0.3s ease, transform 0.3s ease;
        }

        nav a:hover {
            background-color: #e60000;
            transform: scale(1.1);
        }

        .main-content {
            padding: 50px 20px;
            text-align: center;
            animation: fadeIn 1s ease-in-out 0.5s forwards;
        }

        .main-content h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        .main-content p {
            font-size: 1.2em;
            color: #666;
            margin-bottom: 30px;
        }

        footer {
            background-color: #e60000;
            color: white;
            text-align: center;
            padding: 15px 20px;
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

        @keyframes slideIn {
            0% {
                transform: translateX(-100%);
            }
            100% {
                transform: translateX(0);
            }
        }

    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Modern Website</h1>
    </header>
    
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="main-content">
        <h2>About This Website</h2>
        <p>This website has a modern, clean, and stylish design with smooth animations and a red theme. You can easily customize it to fit your needs.</p>
    </div>

    <footer>
        <p>&copy; 2024 Modern Stylish Website</p>
    </footer>
</body>
</html>
