
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8d0d1;
            color: #333;
            text-align: center;
            padding: 50px;
        }
        /* Flower animation background */
        .flower {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('https://www.transparenttextures.com/patterns/polygons.png'); /* Use a pattern or image of flowers */
            opacity: 0.1;
            animation: flowerAnimation 10s linear infinite;
            z-index: -1;
        }
        @keyframes flowerAnimation {
            0% {
                transform: translateX(0) rotate(0deg);
            }
            50% {
                transform: translateX(100%) rotate(180deg);
            }
            100% {
                transform: translateX(0) rotate(360deg);
            }
        h1 {
            color: #003366;
            font-size: 3em;
        }
        p {
            font-size: 1.5em;
            margin-top: 20px;
        } 
        .photo-gallery {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            margin-top: 30px;
        }
        .photo-gallery img {
            border-radius: 10px;
            margin: 10px;
        }
        .button {
            background-color: #f5f5dc;
            color: black;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            font-size: 1.2em;
            cursor: pointer;
        }
        .button:hover {
            background-color: #ff1a1a;
        }
    </style>
</head>
<body>
    <h1>Happy Birthday, Nasahhara!</h1>
    <p>Wishing you all the love, joy, and happiness in the world today and always. You mean so much to me! Semoga awak sentiasa dilindungi dan diluaskan rezeki dari Allah s.w.t. Jadi anak yang baik dan solehah yaa..</p>
    <div class="photo-gallery">
        <img src="IMG-20250401-WA0002.jpg" alt="Memory 1" width="300" height="199">
        <img src="IMG-20250405-WA0008.jpg" alt="Memory 2" width="300" height="400">
    </div>
    <a href="FB_VID_3300536119473816444.mp4" class="button">Your Special Gift</a>
</body>
</html>
