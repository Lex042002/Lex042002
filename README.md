<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 50px;
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
            background: url('mopsy.jpg') center/cover no-repeat fixed;
        }

        #message-container {
            background-color: pink;
            padding: 50px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            max-width: 600px;
            width: 100%;
            margin-bottom: 50px;
            font-size:15px;
        }

#heart {
            color: red;
            font-size: 24px; /* Adjust the heart size */
        }

        #signature {
          
            margin-top: 20px;
            font-weight: bold;
            font-size: 20px; 
            color:white;/* Adjust the signature font size */
        }

        #love-button {
            background-color: #4CAF50;
            color: white;
            padding: 20px 40px; /* Adjust button padding */
            font-size: 24px; /* Adjust the button font size */
            cursor: pointer;
            border: none;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <div id="message-container">
        <p>Hi pooo, I just want to thank you for being with me on this day pooo, and I hope for more Christmases to come for us and our families poooo.</p>
        <p>We celebrate this joyous season of love and togetherness. I want to take a moment to express my feelings tonight, even though we had misunderstandings. I hope as you read my message, any discomfort from last night disappears...</p>
        <p>I know I've made mistakes, and I deeply regret all the troubles I've caused. I hope your heart is filled with love this night, cherishing all the moments we've created for months.</p>
        <p>As we start this Christmas day, let's embrace forgiveness. I want you to know how much your friendship means to me, not only as friends but as lovers. I extend my heartfelt apologies for your understanding. May this Christmas bring us closer together.</p>
        <p>Wishing you a Merry Christmas, mopsy<span id="heart">❤️</span>. Have a great and wonderful night <span id="heart">😘</span>.</p>
    </div>
    <p id="signature">Thank you for being an incredible friend, mama, tita, ante, lola char lang haha... I look forward to creating beautiful memories together in the coming year. I love you pooo<span id="heart">❤️</span>. Merry Christmasssss <span id="heart">🥳</span></p>

    <!-- Button to display "I LOVE YOU" message -->
    <button id="love-button">Click me please🥺</button>

    <script>
        document.getElementById("love-button").addEventListener("click", function() {
            alert("I LOVE YOU POOO❤️");
        });
    </script>
</body>
</html>
 
