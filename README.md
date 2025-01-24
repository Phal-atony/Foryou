<html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Code Love to My Crush</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f0f8ff;
            color: #333;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            text-align: center;
        }
        h1 {
            font-size: 3em;
            color: #ff69b4;
            margin-bottom: 0.5em;
        }
        p {
            font-size: 1.2em;
            color: #4b0082;
        }
        .heart {
            font-size: 4em;
            color: #ff1493;
            animation: beat 1.5s infinite;
        }
        @keyframes beat {
            0% { transform: scale(1); }
            50% { transform: scale(1.2); }
            100% { transform: scale(1); }
        }
        button {
            background-color: #ff1493;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 1em;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        button:hover {
            background-color: #ff69b4;
        }
    </style>
</head>
<body>

    <div>
        <h1>អូនស្រលាញ់បងទេ?</h1>
        <div class="heart">❤️</div>
        <p>អូនស្អាតជាងគេលើលោកនេះ❤️អូនមានដឹងអត់បងតែងតែលួចមើលអូនគ្រប់ពេលវេលា😘 បងមិនថាបងអាចក្លាយជាប្ដីរបស់អូនទេ🥺</p>
        <button onclick="showMessage()">Yes!</button>
        <p id="love-message" style="display: none; font-size: 1.5em; color: #ff6347; margin-top: 20px;">បងក៏ស្រលាញ់អូនដែរ😘❤️</p>
    </div>

    <script>
        function showMessage() {
            document.getElementById('love-message').style.display = 'block';
        }
    </script>

</body>
</html>
