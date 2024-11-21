<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Circle and Rectangle</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
        }
        .rectangle {
            width: 200px;
            height: 200px;
            background-color: blue;
            position: relative;
        }
        .circle {
            width: 150px;
            height: 150px;
            background-color: yellow;
            border: 5px solid red;
            border-radius: 50%;
            position: absolute;
            top: 25%;
            right: -25%;
        }
    </style>
</head>
<body>
    <div class="rectangle">
        <div class="circle"></div>
    </div>
</body>
</html>
