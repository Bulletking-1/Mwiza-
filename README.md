<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>For Mwiza Beyonce Mwiya</title>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        body {
            background: linear-gradient(135deg, #ffafbd 0%, #ffc3a0 100%);
            color: #8a2b5e;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 20px;
            font-family: 'Poppins', sans-serif;
            overflow-x: hidden;
        }
        
        .container {
            max-width: 800px;
            width: 100%;
            background: rgba(255, 255, 255, 0.92);
            border-radius: 25px;
            padding: 40px;
            box-shadow: 0 20px 40px rgba(255, 105, 180, 0.3);
            position: relative;
            overflow: hidden;
            border: 8px solid #ff69b4;
            margin: 20px 0;
        }
        
        .container::before {
            content: "";
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(255,182,193,0.1) 1px, transparent 1px);
            background-size: 30px 30px;
            z-index: 0;
            animation: floatHearts 60s linear infinite;
        }
        
        @keyframes floatHearts {
            0% { transform: translate(0, 0) rotate(0deg); }
            100% { transform: translate(-30px, -30px) rotate(360deg); }
        }
        
        .header {
            text-align: center;
            margin-bottom: 30px;
            position: relative;
            z-index: 1;
        }
        
        .title {
            font-family: 'Dancing Script', cursive;
            font-size: 3.5rem;
            color: #ff1493;
            margin-bottom: 10px;
            text-shadow: 3px 3px 0px rgba(255, 20, 147, 0.2);
        }
        
        .name-container {
            background: linear-gradient(45deg, #ff1493, #ff69b4);
            padding: 15px 30px;
            border-radius: 50px;
            display: inline-block;
            margin: 20px 0;
            box-shadow: 0 10px 20px rgba(255, 20, 147, 0.3);
            transform: rotate(-2deg);
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0% { transform: rotate(-2deg) scale(1); }
            50% { transform: rotate(-2deg) scale(1.03); }
            100% { transform: rotate(-2deg) scale(1); }
        }
        
        .name-highlight {
            font-size: 2.8rem;
            color: white;
            font-weight: 700;
            letter-spacing: 1px;
        }
        
        .my-name {
            text-align: center;
            font-size: 1.5rem;
            color: #db7093;
            margin-top: 10px;
            font-weight: 600;
        }
        
        .heart-banner {
            display: flex;
            justify-content: center;
            gap: 10px;
            margin: 25px 0;
            flex-wrap: wrap;
        }
        
        .heart {
            font-size: 2.5rem;
            color: #ff69b4;
            animation: bounce 1.5s infinite;
        }
        
        .heart:nth-child(2) { animation-delay: 0.2s; color: #ff1493; }
        .heart:nth-child(3) { animation-delay: 0.4s; color: #db7093; }
        .heart:nth-child(4) { animation-delay: 0.6s; color: #ff69b4; }
        .heart:nth-child(5) { animation-delay: 0.8s; color: #ff1493; }
        
        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-15px); }
        }
        
        .apology-card {
            background: linear-gradient(145deg, #fff5f7, #ffeef2);
            border-radius: 20px;
            padding: 30px;
            margin: 30px 0;
            border-left: 10px solid #ff69b4;
            box-shadow: 0 10px 25px rgba(255, 105, 180, 0.15);
            position: relative;
            z-index: 1;
        }
        
        .apology-card::after {
            content: "💖";
            position: absolute;
            top: -20px;
            right: -20px;
            font-size: 3rem;
            transform: rotate(15deg);
        }
        
        .apology-text {
            font-size: 1.2rem;
            line-height: 1.8;
            margin-bottom: 20px;
        }
        
        .apology-text p {
            margin-bottom: 15px;
        }
        
        .promise-section {
            background: linear-gradient(135deg, #ff69b4, #ff1493);
            color: white;
            padding: 25px;
            border-radius: 20px;
            text-align: center;
            margin: 30px 0;
            box-shadow: 0 15px 30px rgba(255, 20, 147, 0.3);
            position: relative;
            overflow: hidden;
        }
        
        .promise-section::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 5px;
            background: linear-gradient(90deg, #ffb6c1, #fff, #ffb6c1);
        }
        
        .promise-title {
            font-family: 'Dancing Script', cursive;
            font-size: 2.5rem;
            margin-bottom: 15px;
        }
        
        .promise-text {
            font-size: 1.5rem;
            font-weight: 600;
            text-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }
        
        .music-section {
            background: rgba(255, 255, 255, 0.95);
            border-radius: 20px;
            padding: 25px;
            margin: 30px 0;
            text-align: center;
            border: 3px dashed #ff69b4;
            position: relative;
            z-index: 1;
        }
        
        .music-title {
            font-family: 'Dancing Script', cursive;
            font-size: 2.5rem;
            color: #ff1493;
            margin-bottom: 20px;
        }
        
        .song-info {
            font-size: 1.2rem;
            margin-bottom: 20px;
            color: #8a2b5e;
        }
        
        .player-container {
            background: linear-gradient(135deg, #ffb6c1, #ff69b4);
            border-radius: 15px;
            padding: 20px;
            margin: 20px auto;
            max-width: 500px;
            box-shadow: 0 10px 20px rgba(255, 105, 180, 0.2);
        }
        
        .player-controls {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 20px;
            margin-top: 20px;
        }
        
        .player-btn {
            background: white;
            border: none;
            width: 50px;
            height: 50px;
            border-radius: 50%;
            font-size: 1.5rem;
            color: #ff1493;
            cursor: pointer;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.3s ease;
        }
        
        .player-btn:hover {
            transform: scale(1.1);
            box-shadow: 0 5px 15px rgba(255, 20, 147, 0.3);
        }
        
        .love-game {
            background: rgba(255, 255, 255, 0.95);
            border-radius: 20px;
            padding: 30px;
            margin: 30px 0;
            text-align: center;
            border: 3px dashed #ff69b4;
            position: relative;
            z-index: 1;
        }
        
        .game-title {
            font-family: 'Dancing Script', cursive;
            font-size: 2.5rem;
            color: #ff1493;
            margin-bottom: 20px;
        }
        
        .game-instruction {
            font-size: 1.1rem;
            margin-bottom: 25px;
            color: #8a2b5e;
        }
        
        .love-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 15px;
            margin-bottom: 25px;
        }
        
        .love-box {
            background: linear-gradient(135deg, #ffb6c1, #ff69b4);
            height: 80px;
            border-radius: 15px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2rem;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 8px 15px rgba(255, 105, 180, 0.2);
        }
        
        .love-box:hover {
            transform: translateY(-5px);
            box-shadow: 0 12px 20px rgba(255, 105, 180, 0.4);
        }
        
        .love-box.revealed {
            background: linear-gradient(135deg, #ff1493, #c71585);
            color: white;
            transform: scale(1.05);
        }
        
        .game-message {
            font-size: 1.4rem;
            color: #ff1493;
            min-height: 40px;
            margin-top: 20px;
            font-weight: 600;
            transition: all 0.5s ease;
        }
        
        .forgiveness-btn {
            background: linear-gradient(to right, #ff1493, #ff69b4);
            border: none;
            color: white;
            padding: 18px 50px;
            font-size: 1.5rem;
            border-radius: 50px;
            cursor: pointer;
            margin: 25px auto;
            display: block;
            font-weight: 600;
            letter-spacing: 1px;
            transition: all 0.3s ease;
            box-shadow: 0 10px 20px rgba(255, 20, 147, 0.4);
            font-family: 'Poppins', sans-serif;
            position: relative;
            overflow: hidden;
        }
        
        .forgiveness-btn:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 25px rgba(255, 20, 147, 0.6);
            background: linear-gradient(to right, #ff69b4, #ff1493);
        }
        
        .forgiveness-btn:active {
            transform: translateY(0);
        }
        
        .forgiveness-btn::after {
            content: "💝";
            position: absolute;
            right: 20px;
            top: 50%;
            transform: translateY(-50%);
        }
        
        .signature {
            text-align: center;
            margin-top: 30px;
            padding-top: 20px;
            border-top: 2px dotted #ffb6c1;
            color: #8a2b5e;
            font-style: italic;
            position: relative;
            z-index: 1;
        }
        
        .footer {
            text-align: center;
            margin-top: 30px;
            color: #8a2b5e;
            font-size: 0.9rem;
            opacity: 0.8;
        }
        
        .pink-flower {
            position: absolute;
            font-size: 2rem;
            opacity: 0.7;
            z-index: 0;
        }
        
        .flower1 { top: 10%; left: 5%; transform: rotate(45deg); }
        .flower2 { top: 15%; right: 5%; transform: rotate(-20deg); }
        .flower3 { bottom: 20%; left: 8%; transform: rotate(10deg); }
        .flower4 { bottom: 15%; right: 10%; transform: rotate(-45deg); }
        
        @media (max-width: 768px) {
            .container { padding: 25px; }
            .title { font-size: 2.8rem; }
            .name-highlight { font-size: 2.2rem; }
            .love-grid { grid-template-columns: repeat(3, 1fr); }
            .love-box { height: 70px; font-size: 1.8rem; }
            .apology-text { font-size: 1.1rem; }
        }
        
        @media (max-width: 480px) {
            .container { padding: 20px; }
            .title { font-size: 2.2rem; }
            .name-highlight { font-size: 1.8rem; }
            .love-grid { grid-template-columns: repeat(2, 1fr); }
            .love-box { height: 75px; }
            .forgiveness-btn { padding: 15px 30px; font-size: 1.3rem; }
        }
    </style>
</head>
<body>
    <div class="pink-flower flower1">🌸</div>
    <div class="pink-flower flower2">🌺</div>
    <div class="pink-flower flower3">💮</div>
    <div class="pink-flower flower4">🏵️</div>
    
    <div class="container">
        <div class="header">
            <h1 class="title">My Heartfelt Apology</h1>
            
            <div class="heart-banner">
                <div class="heart">❤️</div>
                <div class="heart">💖</div>
                <div class="heart">💗</div>
                <div class="heart">💕</div>
                <div class="heart">💞</div>
            </div>
            
            <div class="name-container">
                <h2 class="name-highlight">For Mwiza Beyonce Mwiya</h2>
            </div>
            
            <div class="my-name">From Lifasi Malumo Lucky</div>
        </div>
        
        <div class="apology-card">
            <div class="apology-text">
                <p>My dearest Mwiza Beyonce Mwiya,</p>
                <p>I am writing this with a heart full of regret and love. I know I've made mistakes, and I'm truly sorry for the pain I've caused you. You mean the world to me, and seeing you upset because of me is the hardest thing to bear.</p>
                <p>Every moment with you is special, and I realize now how much I've taken that for granted. Your smile lights up my world, your laughter is my favorite melody, and your presence makes everything better. I promise to be more thoughtful, more attentive, and to cherish you the way you deserve.</p>
                <p>Please know that my love for you is genuine and deep. I'm committed to making things right and being the person you can always count on.</p>
            </div>
        </div>
        
        <div class="promise-section">
            <h3 class="promise-title">My Promise to You</h3>
            <p class="promise-text">I will always cherish and respect you, Beyonce</p>
        </div>
        
        <div class="music-section">
            <h3 class="music-title">Our Song</h3>
            <p class="song-info">This song reminds me of us - let's calm down and make up 💖</p>
            <div class="player-container">
                <h4>Rema - Calm Down</h4>
                <div class="player-controls">
                    <button class="player-btn" id="playBtn">
                        <i class="fas fa-play"></i>
                    </button>
                    <button class="player-btn" id="pauseBtn">
                        <i class="fas fa-pause"></i>
                    </button>
                    <button class="player-btn" id="stopBtn">
                        <i class="fas fa-stop"></i>
                    </button>
                </div>
                <div id="lyrics">
                    <p><i>"Baby, calm down, calm down<br>
                    Girl, this your body e put in my heart for lockdown<br>
                    For lockdown, oh, lockdown"</i></p>
                </div>
            </div>
        </div>
        
        <div class="love-game">
            <h3 class="game-title">Find Our Love Messages</h3>
            <p class="game-instruction">Click on the hearts to reveal hidden messages for you!</p>
            
            <div class="love-grid" id="loveGrid">
                <!-- Hearts will be generated by JavaScript -->
            </div>
            
            <div class="game-message" id="gameMessage">Click a heart to reveal a message!</div>
        </div>
        
        <button class="forgiveness-btn" id="forgivenessBtn">Will You Forgive Me?</button>
        
        <div class="signature">
            <p>With all my love and sincere apologies,</p>
            <p style="font-size: 1.3rem; font-weight: 600; color: #ff1493;">Lifasi Malumo Lucky</p>
        </div>
    </div>
    
    <div class="footer">
        <p>Made with 💖 for the most amazing woman in the world</p>
    </div>

    <script>
        // Music Player Simulation
        const playBtn = document.getElementById('playBtn');
        const pauseBtn = document.getElementById('pauseBtn');
        const stopBtn = document.getElementById('stopBtn');
        const lyrics = document.getElementById('lyrics');
        
        const songLyrics = [
            "Baby, calm down, calm down",
            "Girl, this your body e put in my heart for lockdown",
            "For lockdown, oh, lockdown",
            "Girl, you sweet like Fanta, ooh, Fanta, ooh",
            "If I tell you say I love you, you no dey form hanger",
            "You dey make my heart dey samba, ooh, samba, ooh",
            "Queen, you for be di queen for di carnival",
            "Your body catch my eye, na him be the original",
            "Girl, you're too fine, with you I can't settle",
            "Baby, calm down, calm down"
        ];
        
        let currentLyricIndex = 0;
        let lyricInterval;
        
        function startLyrics() {
            clearInterval(lyricInterval);
            currentLyricIndex = 0;
            updateLyric();
            lyricInterval = setInterval(updateLyric, 3000);
        }
        
        function updateLyric() {
            lyrics.innerHTML = `<p><i>"${songLyrics[currentLyricIndex]}"</i></p>`;
            currentLyricIndex = (currentLyricIndex + 1) % songLyrics.length;
        }
        
        function stopLyrics() {
            clearInterval(lyricInterval);
            lyrics.innerHTML = `<p><i>"Baby, calm down, calm down<br>
                    Girl, this your body e put in my heart for lockdown<br>
                    For lockdown, oh, lockdown"</i></p>`;
        }
        
        playBtn.addEventListener('click', function() {
            startLyrics();
            playBtn.innerHTML = '<i class="fas fa-play"></i>';
            playBtn.style.backgroundColor = '#ffebf0';
        });
        
        pauseBtn.addEventListener('click', function() {
            clearInterval(lyricInterval);
            pauseBtn.style.backgroundColor = '#ffebf0';
            setTimeout(() => {
                pauseBtn.style.backgroundColor = 'white';
            }, 300);
        });
        
        stopBtn.addEventListener('click', function() {
            stopLyrics();
            stopBtn.style.backgroundColor = '#ffebf0';
            setTimeout(() => {
                stopBtn.style.backgroundColor = 'white';
            }, 300);
        });
        
        // Love Game
        const loveGrid = document.getElementById('loveGrid');
        const gameMessage = document.getElementById('gameMessage');
        
        const loveMessages = [
            "You're amazing 💖",
            "I adore you 🌹",
            "My heart is yours ❤️",
            "Forgive me? 🙏",
            "You're my queen 👑",
            "I miss your smile 😊",
            "You complete me 💑",
            "Always yours 💘",
            "I cherish you 💕",
            "You're my dream 💭",
            "My love for you is endless 💞",
            "You're my everything 🌟"
        ];
        
        // Create heart boxes
        for (let i = 0; i < 12; i++) {
            const box = document.createElement('div');
            box.className = 'love-box';
            box.innerHTML = '💖';
            box.dataset.message = loveMessages[i];
            
            box.addEventListener('click', function() {
                if (!this.classList.contains('revealed')) {
                    this.classList.add('revealed');
                    this.innerHTML = this.dataset.message;
                    
                    // Update game message
                    const messages = [
                        "That's so true! 💖",
                        "You found one! 🌹",
                        "My feelings exactly! ❤️",
                        "Another truth revealed! 💕",
                        "Exactly how I feel! 💘",
                        "Keep going, my love! 💞"
                    ];
                    const randomMessage = messages[Math.floor(Math.random() * messages.length)];
                    gameMessage.textContent = randomMessage;
                    
                    // Check if all boxes are revealed
                    const allBoxes = document.querySelectorAll('.love-box');
                    const revealedBoxes = document.querySelectorAll('.love-box.revealed');
                    
                    if (allBoxes.length === revealedBoxes.length) {
                        gameMessage.textContent = "You found all my love messages! I'm all yours! 💘";
                        gameMessage.style.color = "#ff1493";
                        gameMessage.style.fontSize = "1.6rem";
                    }
                }
            });
            
            loveGrid.appendChild(box);
        }
        
        // Forgiveness Button
        const forgivenessBtn = document.getElementById('forgivenessBtn');
        let clickCount = 0;
        
        forgivenessBtn.addEventListener('click', function() {
            clickCount++;
            
            if (clickCount === 1) {
                this.innerHTML = 'Please? 💖';
                this.style.transform = 'scale(1.05)';
                gameMessage.textContent = "I'm really sorry Beyonce, please give me another chance!";
                
                // Create floating hearts
                createFloatingHearts(5);
            } 
            else if (clickCount === 2) {
                this.innerHTML = 'I promise to do better! 💝';
                this.style.background = 'linear-gradient(to right, #ff69b4, #ff1493)';
                gameMessage.textContent = "I'll make it up to you, I promise!";
                
                // Create more floating hearts
                createFloatingHearts(8);
            }
            else if (clickCount === 3) {
                this.innerHTML = 'Thank you, my love! 💘';
                this.style.background = 'linear-gradient(to right, #4CAF50, #45a049)';
                gameMessage.textContent = "Thank you for forgiving me! I love you so much, Mwiza Beyonce Mwiya! 💖";
                
                // Create celebration hearts
                createFloatingHearts(15);
                
                // Change all heart boxes to green
                const allBoxes = document.querySelectorAll('.love-box');
                allBoxes.forEach(box => {
                    box.style.background = 'linear-gradient(135deg, #4CAF50, #45a049)';
                });
                
                // Play celebration animation
                celebrationAnimation();
            }
            
            // Reset transform after animation
            setTimeout(() => {
                this.style.transform = '';
            }, 300);
        });
        
        function createFloatingHearts(count) {
            for (let i = 0; i < count; i++) {
                const heart = document.createElement('div');
                heart.innerHTML = '💖';
                heart.style.position = 'fixed';
                heart.style.fontSize = Math.random() * 20 + 20 + 'px';
                heart.style.left = Math.random() * 100 + 'vw';
                heart.style.top = '100vh';
                heart.style.zIndex = '9999';
                heart.style.pointerEvents = 'none';
                heart.style.opacity = '0.9';
                
                document.body.appendChild(heart);
                
                // Animate heart floating up
                const animation = heart.animate([
                    { transform: 'translateY(0) rotate(0deg)', opacity: 1 },
                    { transform: `translateY(-${window.innerHeight + 100}px) rotate(${Math.random() * 360}deg)`, opacity: 0 }
                ], {
                    duration: Math.random() * 3000 + 2000,
                    easing: 'cubic-bezier(0.215, 0.610, 0.355, 1)'
                });
                
                // Remove heart after animation completes
                animation.onfinish = () => {
                    document.body.removeChild(heart);
                };
            }
        }
        
        function celebrationAnimation() {
            // Add celebration message to the page
            const celebration = document.createElement('div');
            celebration.innerHTML = `
                <div style="position: fixed; top: 50%; left: 50%; transform: translate(-50%, -50%); 
                           background: rgba(255, 255, 255, 0.95); padding: 30px; border-radius: 20px; 
                           text-align: center; z-index: 10000; box-shadow: 0 20px 40px rgba(0,0,0,0.2);
                           border: 5px solid #ff69b4; max-width: 80%;">
                    <h2 style="color: #ff1493; font-family: 'Dancing Script', cursive; font-size: 3rem; margin-bottom: 20px;">
                        You Made My Day! 💖
                    </h2>
                    <p style="font-size: 1.5rem; color: #8a2b5e;">
                        Thank you for forgiving me, Beyonce!<br>
                        I love you more than words can express!
                    </p>
                    <button id="closeCelebration" style="margin-top: 20px; padding: 10px 30px; 
                           background: #ff69b4; color: white; border: none; border-radius: 50px; 
                           font-size: 1.2rem; cursor: pointer;">
                        Close
                    </button>
                </div>
            `;
            
            document.body.appendChild(celebration);
            
            // Close button functionality
            document.getElementById('closeCelebration').addEventListener('click', function() {
                document.body.removeChild(celebration);
            });
        }
        
        // Initialize with some floating hearts
        window.addEventListener('load', function() {
            setTimeout(() => {
                createFloatingHearts(3);
            }, 1000);
        });
    </script>
</body>
</html>
