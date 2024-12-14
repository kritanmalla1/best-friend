<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Samarth Raj Acharya</title>
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
       
