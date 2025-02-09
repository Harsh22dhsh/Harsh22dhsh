<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sorry Tanisha Baby 😢</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            text-align: center;
            color: white;
            overflow: hidden;
        }
        #video-bg {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover;
            z-index: -1;
        }
        #container {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            text-align: center;
            background: rgba(0, 0, 0, 0.6);
            padding: 20px;
            border-radius: 10px;
        }
        h1 {
            font-size: 32px;
            text-shadow: 2px 2px 5px black;
        }
        #openCardBtn {
            padding: 10px 20px;
            font-size: 18px;
            border: none;
            background: red;
            color: white;
            cursor: pointer;
            border-radius: 5px;
            transition: 0.3s;
        }
        #openCardBtn:hover {
            background: darkred;
        }
        #card {
            display: none;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 300px;
            height: 200px;
            background: pink;
            border-radius: 10px;
            text-align: center;
            padding: 20px;
            box-shadow: 0px 0px 10px black;
        }
    </style>
</head>
<body>

    <!-- Background Video (Online Link) -->
    <video id="video-bg" autoplay muted loop>
        <source src="https://samplelib.com/lib/preview/mp4/sample-5s.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>

    <div id="container">
        <h1>Sorry, Tanisha Baby 😢</h1>
        <p>Mujhe maaf kar do, mujhe bohot afsos hai! 💔</p>
        <button id="openCardBtn">Open Card</button>
    </div>

    <div id="card">
        <h2>Dear Tanisha Baby,</h2>
        <p>Sorry mat bolo, main gussa nahi hoon! Bas ek baat yaad rakhna, 
           tum mere liye hamesha special ho ❤️</p>
    </div>

    <script>
        document.getElementById("openCardBtn").addEventListener("click", function() {
            document.getElementById("card").style.display = "block";
        });
    </script>

</body>
</html>
