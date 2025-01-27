# rene-birthday
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday Rene!</title>
    <style>
        /* General Page Styling */
        body {
            background: #000 url('https://upload.wikimedia.org/wikipedia/commons/e/ea/The_Starry_Night.JPG') no-repeat center center fixed;
            background-size: cover;
            color: #ccc;
            font-family: 'Arial', sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        h1 {
            font-size: 4em;
            margin-top: 50px;
            color: #fff;
            text-shadow: 2px 2px 6px #000;
        }
        .message {
            font-size: 1.5em;
            margin: 20px 0;
            color: #ddd;
            text-shadow: 1px 1px 3px #000;
        }
        .quote {
            font-size: 1.3em;
            margin: 30px 0;
            color: #ccc;
            font-style: italic;
            text-shadow: 1px 1px 3px #000;
        }
        .birthday-message {
            font-size: 2em;
            margin: 40px 0;
            color: #ffcc00;
            text-shadow: 2px 2px 6px #000;
        }
        .button {
            display: inline-block;
            margin-top: 40px;
            padding: 15px 30px;
            font-size: 1.2em;
            color: #fff;
            background: #444;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            text-shadow: 1px 1px 3px #000;
            transition: background 0.3s ease, color 0.3s ease;
        }
        .button:hover {
            background: #ffcc00;
            color: #000;
        }
        .footer {
            margin-top: 50px;
            color: #aaa;
            font-size: 0.9em;
            text-shadow: 1px 1px 2px #000;
        }
        a {
            color: #aaa;
            text-decoration: none;
            font-weight: bold;
        }
        a:hover {
            color: #fff;
        }
    </style>
</head>
<body>
    <!-- Main Header -->
    <h1>Happy Birthday Rene!</h1>
    
    <!-- Birthday Message -->
    <p class="message">Wishing you a day filled with love, joy, and unforgettable memories!</p>
    
    <!-- Highlighted Birthday Wish -->
    <p class="birthday-message">May your starry nights outshine the darkest days. 🌌</p>
    
    <!-- Favorite Quote -->
    <p class="quote">"Some days I'm Van Gogh's *Starry Night*,<br> other days I'm his suicide letter."</p>
    
    <!-- Interactive Button -->
    <button class="button" onclick="alert('You are the star of the night, Rene! 🌟')">Celebrate Rene</button>
    
    <!-- Footer -->
    <div class="footer">
        <p>Created with love by your friends! | <a href="https://en.wikipedia.org/wiki/The_Starry_Night" target="_blank">Learn about Van Gogh</a></p>
    </div>
</body>
</html>
