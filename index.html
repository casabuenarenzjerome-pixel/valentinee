<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>For My Favorite Person ❤️</title>
    <style>
        body {
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: #000; /* Dark background to make the photo pop */
            font-family: 'Arial', sans-serif;
            overflow: hidden;
        }

        .container {
            text-align: center;
            z-index: 10;
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            padding: 30px;
            border-radius: 25px;
            border: 1px solid rgba(255, 255, 255, 0.2);
            width: 85%;
            max-width: 400px;
        }

        /* The Twist: Her Photo as Background */
        #herPhoto {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover;
            filter: blur(20px) grayscale(100%); /* Starts blurry and grey */
            opacity: 0.5;
            transition: all 0.5s ease;
            z-index: 1;
        }

        h1 { color: white; text-shadow: 2px 2px 10px rgba(0,0,0,0.5); font-size: 1.8rem; }
        
        .btn-box {
            margin-top: 40px;
            height: 120px;
            position: relative;
        }

        button {
            padding: 15px 35px;
            font-size: 1.2rem;
            border-radius: 50px;
            border: none;
            font-weight: bold;
            cursor: pointer;
            transition: 0.2s;
        }

        #yesBtn {
            background: #ff4d6d;
            color: white;
            box-shadow: 0 0 20px rgba(255, 77, 109, 0.6);
        }

        #noBtn {
            background: white;
            color: #ff4d6d;
            position: absolute;
            white-space: nowrap;
        }

        .success-screen {
            display: none;
            position: fixed;
            top: 0; left: 0; width: 100%; height: 100%;
            background: rgba(255, 77, 109, 0.9);
            z-index: 100;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            color: white;
            animation: fadeIn 1s;
        }

        @keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } }
    </style>
</head>
<body>

    <img id="herPhoto" src="ADD_IMAGE_URL_HERE" alt="Her Photo">

    <div id="main-ui" class="container">
        <h1>[HER NAME],<br>Will you be my Valentine? ❤️</h1>
        <p style="color: #eee;">(I'll give you a hint: look at the background...)</p>
        
        <div class="btn-box">
            <button id="yesBtn">YES</button>
            <button id="noBtn">No</button>
        </div>
    </div>

    <div id="success" class="success-screen">
        <h1 style="font-size: 4rem;">YES! ❤️</h1>
        <p style="font-size: 1.5rem;">You just made me the happiest person, [HER NAME]!</p>
    </div>

    <script>
        const noBtn = document.getElementById('noBtn');
        const yesBtn = document.getElementById('yesBtn');
        const photo = document.getElementById('herPhoto');
        
        let blurValue = 20;
        let grayValue = 100;
        let opacityValue = 0.5;

        function runAway() {
            // Move No Button
            const x = Math.random() * (window.innerWidth - noBtn.offsetWidth);
            const y = Math.random() * (window.innerHeight - noBtn.offsetHeight);
            noBtn.style.left = `${x}px`;
            noBtn.style.top = `${y}px`;

            // THE TWIST: Every "No" attempt makes her photo clearer
            if (blurValue > 0) blurValue -= 2;
            if (grayValue > 0) grayValue -= 10;
            if (opacityValue < 1) opacityValue += 0.05;

            photo.style.filter = `blur(${blurValue}px) grayscale(${grayValue}%)`;
            photo.style.opacity = opacityValue;

            // Change button text to tease her
            const messages = ["Wait!", "Look!", "Getting clearer...", "Is that you?", "So pretty!", "Just click YES!"];
            noBtn.innerText = messages[Math.floor(Math.random() * messages.length)];
        }

        noBtn.addEventListener('mouseover', runAway);
        noBtn.addEventListener('touchstart', (e) => { e.preventDefault(); runAway(); });

        yesBtn.addEventListener('click', () => {
            document.getElementById('success').style.display = 'flex';
            photo.style.filter = "blur(0px) grayscale(0%)";
            photo.style.opacity = "1";
        });
    </script>
</body>
</html>
