<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Date Invitation</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 50px;
        }

        h1 {
            color: #333;
        }

        button {
            padding: 10px 20px;
            font-size: 16px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <h1>Hey there!</h1>
    <p>I've been thinking it would be awesome to spend some time together. What do you say?</p>

    <button onclick="sendResponse('yes')">Yes, let's do it!</button>
    <button onclick="sendResponse('no')">Sorry, not this time.</button>

    <script>
        function sendResponse(response) {
            if (response === 'yes') {
                alert('Fantastic! Looking forward to it.');
            } else {
                alert('No worries, maybe another time.');
            }
        }
    </script>

</body>
</html>
