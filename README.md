<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday Mama</title>
    <style>
        body {
    font-family: 'Georgia', serif;
    background: linear-gradient(to bottom right, #ffcccc, #ffe6e6);
    text-align: center;
    margin: 0;
    padding: 20px;
    color: #333;
    overflow: auto;
}


        h3 {
            color: #e74c3c;
            text-shadow: 3px 3px #f1948a;
            font-size: 36px;
        }

        img {
            border: 8px solid #f5b7b1;
            border-radius: 50%;
            box-shadow: 0px 10px 30px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease, box-shadow 0.3s ease, border-color 0.3s ease;
        }

        img:hover {
            transform: scale(1.1);
            box-shadow: 0px 15px 35px rgba(0, 0, 0, 0.5);
            border-color: #e74c3c;
        }

        p {
            font-size: 18px;
            line-height: 1.8;
            background: rgba(255, 255, 255, 0.9);
            padding: 20px;
            margin: 20px auto;
            border-radius: 15px;
            max-width: 700px;
            box-shadow: 0px 10px 20px rgba(0, 0, 0, 0.2);
            position: relative;
        }

        p span {
            color: #e74c3c;
            font-weight: bold;
        }

        p:before {
            content: "❤️";
            font-size: 50px;
            position: absolute;
            top: -30px;
            left: 50%;
            transform: translateX(-50%);
            animation: bounce 1.5s infinite;
        }

        @keyframes bounce {
            0%, 100% {
                transform: translate(-50%, -10px);
            }
            50% {
                transform: translate(-50%, 10px);
            }
        }

        .hearts {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            overflow: hidden;
        }

        .hearts div {
            width: 20px;
            height: 20px;
            background: #e74c3c;
            position: absolute;
            animation: float 7s infinite ease-in-out;
            clip-path: polygon(50% 0%, 61% 35%, 98% 35%, 68% 57%, 79% 91%, 50% 70%, 21% 91%, 32% 57%, 2% 35%, 39% 35%);
            opacity: 0.8;
        }

        @keyframes float {
            0% {
                transform: translateY(100vh) translateX(0);
                opacity: 0;
            }
            50% {
                opacity: 1;
            }
            100% {
                transform: translateY(-100vh) translateX(calc(50vw - 10vw));
                opacity: 0;
            }
        }

        p:after {
            content: '';
            position: absolute;
            top: -5px;
            left: -5px;
            right: -5px;
            bottom: -5px;
            background: linear-gradient(to right, #ffcccc, #e74c3c, #ffe6e6);
            z-index: -1;
            filter: blur(8px);
            border-radius: 20px;
            opacity: 0.7;
            animation: glow 3s infinite alternate;
        }

        @keyframes glow {
            0% {
                opacity: 0.7;
            }
            100% {
                opacity: 1;
            }
        }

        footer {
            margin-top: 20px;
            font-size: 16px;
            color: #e74c3c;
        }

    </style>
</head>
<body>
    <h3>To My Dearest Love</h3>
    <div class="image-grid">
        <img src="c:\Users\Divine Uduma\OneDrive\Pictures\WhatsApp Image 2025-01-22 at 19.43.51_b5f7c538.jpg"  width="200px" alt="Stella 1">
        <img src="c:\Users\Divine Uduma\OneDrive\Pictures\WhatsApp Image 2025-01-22 at 20.36.45_11f54759.jpg"  width="200px" alt="Stella 2">
        <img src="c:\Users\Divine Uduma\OneDrive\Pictures\WhatsApp Image 2025-01-22 at 20.36.43_4c4b6e9a.jpg"  width="200px" alt="Stella 3">
        <img src="c:\Users\Divine Uduma\OneDrive\Pictures\WhatsApp Image 2025-01-22 at 20.36.45_40490d39.jpg"  width="200px" alt="Stella 4">
        <img src="c:\Users\Divine Uduma\OneDrive\Pictures\WhatsApp Image 2025-01-22 at 20.36.46_97dc773f.jpg"  width="200px" alt="Stella 4">

    </div>
        <p>
        To be honest, I don't know exactly what to start with, but regardless, I have to start somewhere. 
        I must say you have been <span>a lot to me</span>, you know—a friend, a close friend, my best friend, my love, 
        one who corrects me whenever I make wrong decisions, who accepts me regardless of how hurtful 
        my words may be, a support, a motivation to keep going and pushing through. Smile... 
        should I talk about your care or that of your love? I really appreciate all you do, Mama.<br><br>
        
        Today marks <span>a new year for you</span> which will be filled with both highs and lows, of course. In all, I will always 
        be by your side to support and cheer you up when needed. In advance, forgive me for days when I won't 
        be of much help, but trust me, I would have loved to be of much help. So Mama, have a year as beautiful as you are 
        and don't stop smiling because those smiles of yours never run out of beauty, which is also a catalyst to 
        make others smile—me in particular.<br><br>

        My love, I'm glad for the day we started this journey together and to 
        have you by my side. <br><br>
        <span>Happy Birthday</span> my love, I wish you the very best, dear, and I pray God continues to grant your heart's desire, 
        answer both your secret and open prayers, and also turn your tears to joy and your challenges to victory.
        We keep walking through together and trust God till the very end. That day which we both want will surely come.<br><br> 
        Daddy loves you so so much, Mama, and I miss you every day. <br><br>
        Olawale Stella Opeyemi Ifeoluwa Abosede Idunuoluwa Iyanuoluwa Abigail Ajike... I Love You, Mama. Words can't 
        express it, though, but a kiss will, for sure. Unluckily, you are yet to be in Lagos. Well, soon, soon, Pookie.<br>
        Have a great day. I love you.
    </p>

    <!-- Heart Decorations -->
    <div class="hearts">
        <div style="animation-delay: 0s; left: 10%;"></div>
        <div style="animation-delay: 1s; left: 30%;"></div>
        <div style="animation-delay: 2s; left: 50%;"></div>
        <div style="animation-delay: 3s; left: 70%;"></div>
        <div style="animation-delay: 4s; left: 90%;"></div>
    </div>

    <footer>
        Made with ❤️ for my one and only.
    </footer>
</body>
</html>
