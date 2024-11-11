<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Agent Jay Demo Game</title>
    <style>
        /* Darker theme */
        body {
            background-color: #212121;
            font-family: Arial, sans-serif;
            color: #fff;
        }
        
        .container {
            max-width: 800px;
            margin: 40px auto;
            padding: 20px;
            background-color: #333;
            border: 1px solid #444;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
        }
        
        .header {
            background-color: #444;
            padding: 10px;
            border-radius: 10px 10px 0 0;
        }
        
        .content {
            padding: 20px;
        }
        
        .steps {
            list-style: none;
            padding: 0;
            margin: 0;
        }
        
        .steps li {
            margin-bottom: 10px;
        }
        
        .steps li::before {
            content: "\2022";
            font-weight: bold;
            font-size: 1.5em;
            color: #666;
            margin-right: 5px;
        }
        
        .button {
            background-color: #4CAF50;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        
        .button:hover {
            background-color: #3e8e41;
        }
        
        /* Moving text */
        .developer {
            font-size: 16px;
            font-weight: bold;
            white-space: nowrap;
            animation: move 20s linear infinite;
        }
        
        @keyframes move {
            from {
                transform: translateX(100%);
            }
            to {
                transform: translateX(-100%);
            }
        }
        
        /* Star button */
        .star-btn {
            background-color: #FFD700;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        
        .star-btn:hover {
            background-color: #FFC400;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Agent Jay Demo Game 🎮</h1>
            <div class="developer">Developed by Manolo from Hatchers College 📚</div>
        </div>
        <div class="content">
            <p>Hi all, playtest our demo game! 🚀</p>
            <h3>How to run the game:</h3>
            <ul class="steps">
                <li>After downloading it from the URL, extract it. 💻</li>
                <li>Open the folder you extracted to. 📁</li>
                <li>Run the "RTS.exe" file. ▶️</li>
                <li>Enjoy! 😄</li>
            </ul>
            <p>Remember, it's just a demo and we need your feedback. 💬</p>
            <p>Thank you! 🤜🤛</p>
            <button class="button"><a href="https://github.com/TA-wiah/Agent-Jay" style="color: #fff;">Play Now! 🎮</a></button>
            <button class="star-btn"><a href="https://github.com/TA-wiah/Agent-Jay/stargazers" style="color: #fff;">Give us a Star! ⭐️</a></button>
        </div>
    </div>
</body>
</html>
