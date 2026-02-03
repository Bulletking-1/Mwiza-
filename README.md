<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Heart's Proposal</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Georgia', serif;
            background: linear-gradient(135deg, #fdf2f8 0%, #fce7f3 100%);
            color: #701a75;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
            position: relative;
        }
        
        .envelope {
            width: 100%;
            max-width: 800px;
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 60px rgba(190, 24, 93, 0.3);
            overflow: hidden;
            position: relative;
            border: 3px solid #db2777;
        }
        
        .header {
            background: linear-gradient(135deg, #db2777, #be185d);
            padding: 40px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        
        .header::before {
            content: "❤️";
            position: absolute;
            font-size: 200px;
            opacity: 0.1;
            top: -50px;
            left: -50px;
            transform: rotate(-30deg);
        }
        
        h1 {
            font-family: 'Brush Script MT', cursive;
            font-size: 4rem;
            color: white;
            text-shadow: 3px 3px 5px rgba(0, 0, 0, 0.3);
            margin-bottom: 15px;
            position: relative;
            z-index: 1;
        }
        
        .subtitle {
            font-size: 1.3rem;
            color: rgba(255, 255, 255, 0.9);
            font-style: italic;
            position: relative;
            z-index: 1;
        }
        
        .letter-content {
            padding: 50px;
            line-height: 1.8;
            font-size: 1.1rem;
            background: white;
        }
        
        .salutation {
            font-size: 1.5rem;
            margin-bottom: 30px;
            font-weight: bold;
            color: #be185d;
        }
        
        .paragraph {
            margin-bottom: 25px;
            text-align: justify;
        }
        
        .promises {
            background: #fdf2f8;
            padding: 30px;
            border-radius: 15px;
            margin: 40px 0;
            border-left: 5px solid #db2777;
        }
        
        .promises h2 {
            color: #be185d;
            margin-bottom: 20px;
            font-family: 'Georgia', serif;
        }
        
        .promises ul {
            list-style: none;
            padding-left: 20px;
        }
        
        .promises li {
            padding: 10px 0;
            padding-left: 30px;
            position: relative;
        }
        
        .promises li:before {
            content: "💖";
            position: absolute;
            left: 0;
        }
        
        .closing {
            text-align: right;
            margin-top: 50px;
            padding-top: 30px;
            border-top: 2px dashed #fbcfe8;
        }
        
        .signature {
            font-family: 'Brush Script MT', cursive;
            font-size: 2.5rem;
            color: #db2777;
            margin-top: 10px;
        }
        
        .heart-container {
            text-align: center;
            margin: 40px 0;
        }
        
        .heart {
            display: inline-block;
            font-size: 3rem;
            animation: heartbeat 1.5s infinite;
            margin: 0 10px;
            cursor: pointer;
            transition: transform 0.3s;
        }
        
        .heart:hover {
            transform: scale(1.5);
        }
        
        @keyframes heartbeat {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.2); }
        }
        
        .flowers {
            position: absolute;
            font-size: 2rem;
            opacity: 0.2;
            z-index: 0;
        }
        
        .flower1 { top: 10%; left: 5%; transform: rotate(30deg); }
        .flower2 { top: 15%; right: 5%; transform: rotate(-20deg); }
        .flower3 { bottom: 20%; left: 8%; transform: rotate(15deg); }
        .flower4 { bottom: 15%; right: 8%; transform: rotate(-40deg); }
        
        .accept-btn {
            display: block;
            width: 200px;
            margin: 30px auto;
            background: linear-gradient(to right, #db2777, #be185d);
            color: white;
            border: none;
            padding: 15px 30px;
            font-size: 1.3rem;
            border-radius: 50px;
            cursor: pointer;
            font-family: 'Georgia', serif;
            font-weight: bold;
            box-shadow: 0 10px 20px rgba(219, 39, 119, 0.4);
            transition: all 0.3s ease;
        }
        
        .accept-btn:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 30px rgba(219, 39, 119, 0.6);
            background: linear-gradient(to right, #be185d, #9d174d);
        }
        
        .footer {
            text-align: center;
            padding: 20px;
            background: #fdf2f8;
            color: #9d174d;
            font-style: italic;
        }
        
        @media (max-width: 768px) {
            .envelope {
                margin: 20px;
            }
            
            h1 {
                font-size: 3rem;
            }
            
            .letter-content {
                padding: 30px;
            }
            
            .header {
                padding: 30px 20px;
            }
        }
        
        @media (max-width: 480px) {
            h1 {
                font-size: 2.5rem;
            }
            
            .letter-content {
                padding: 20px;
            }
            
            .signature {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <div class="flowers flower1">🌹</div>
    <div class="flowers flower2">🌷</div>
    <div class="flowers flower3">🌸</div>
    <div class="flowers flower4">💐</div>
    
    <div class="envelope">
        <div class="header">
            <h1>For Martha</h1>
            <div class="subtitle">A Proposal from the Heart</div>
        </div>
        
        <div class="letter-content">
            <div class="salutation">My Dearest Martha,</div>
            
            <div class="paragraph">
                I'm writing this with a heart full of genuine admiration and affection for you. For some time now, I've been gathering the courage to express what I truly feel, and today I choose to be completely honest about my intentions.
            </div>
            
            <div class="paragraph">
                You are an incredible woman – intelligent, beautiful, kind, and with a spirit that inspires everyone around you. Every moment I spend with you feels meaningful, and I find myself constantly looking forward to our next conversation, our next laugh, our next shared moment.
            </div>
            
            <div class="paragraph">
                Today, I'm asking you something important: <strong>Will you be my girlfriend?</strong> Will you give me the honor and privilege of officially being by your side, of building something beautiful together, of creating memories that will last a lifetime?
            </div>
            
            <div class="promises">
                <h2>My Promises to You:</h2>
                <ul>
                    <li><strong>Complete Commitment:</strong> I will be fully present, loyal, and dedicated to our relationship</li>
                    <li><strong>Emotional Security:</strong> I will provide a safe space for your feelings, dreams, and vulnerabilities</li>
                    <li><strong>Growth Together:</strong> I will support your personal and professional growth every step of the way</li>
                    <li><strong>Financial Stability:</strong> I will work tirelessly to ensure we never lack anything essential</li>
                    <li><strong>Respect & Honor:</strong> I will respect your individuality, your opinions, and your boundaries</li>
                    <li><strong>Joy & Laughter:</strong> I will fill our days with happiness, adventure, and beautiful moments</li>
                    <li><strong>Future Planning:</strong> I will build a solid foundation for our shared dreams and aspirations</li>
                </ul>
            </div>
            
            <div class="paragraph">
                I want you to know that I'm not just making empty promises. I have built a stable foundation through my education, trading systems, and strategic planning. I can and <strong>will provide everything</strong> – emotional support, intellectual partnership, financial security, and unwavering commitment.
            </div>
            
            <div class="paragraph">
                With you, I see a future filled with purpose, growth, and love. I see us supporting each other's dreams, celebrating each other's successes, and building a life that exceeds our individual expectations.
            </div>
            
            <div class="heart-container">
                <span class="heart">❤️</span>
                <span class="heart">💕</span>
                <span class="heart">💖</span>
                <span class="heart">💗</span>
                <span class="heart">💘</span>
            </div>
            
            <div class="closing">
                <div class="paragraph" style="text-align: center;">
                    I await your answer with hope in my heart and certainty in my commitment.
                </div>
                
                <div>With all my love and sincerity,</div>
                <div class="signature">Lifasi Malumo Lucky</div>
            </div>
            
            <button class="accept-btn" onclick="acceptProposal()">Say Yes 💖</button>
        </div>
        
        <div class="footer">
            This proposal comes from genuine feelings and serious intentions
        </div>
    </div>
    
    <script>
        function acceptProposal() {
            // Create a beautiful acceptance animation
            const hearts = ['❤️', '💕', '💖', '💗', '💘', '💝', '💞'];
            const colors = ['#db2777', '#be185d', '#9d174d', '#831843', '#500724'];
            
            // Create floating hearts
            for (let i = 0; i < 50; i++) {
                setTimeout(() => {
                    const heart = document.createElement('div');
                    heart.innerHTML = hearts[Math.floor(Math.random() * hearts.length)];
                    heart.style.position = 'fixed';
                    heart.style.fontSize = Math.random() * 30 + 20 + 'px';
                    heart.style.color = colors[Math.floor(Math.random() * colors.length)];
                    heart.style.left = Math.random() * 100 + '%';
                    heart.style.top = '100%';
                    heart.style.zIndex = '9999';
                    heart.style.pointerEvents = 'none';
                    heart.style.opacity = '0.9';
                    
                    document.body.appendChild(heart);
                    
                    // Animate heart
                    const animation = heart.animate([
                        { transform: 'translateY(0) rotate(0deg)', opacity: 1 },
                        { transform: `translateY(-${window.innerHeight + 100}px) rotate(${Math.random() * 360}deg)`, opacity: 0 }
                    ], {
                        duration: Math.random() * 3000 + 2000,
                        easing: 'cubic-bezier(0.215, 0.610, 0.355, 1)'
                    });
                    
                    // Remove after animation
                    animation.onfinish = () => {
                        if (heart.parentNode) {
                            document.body.removeChild(heart);
                        }
                    };
                }, i * 100);
            }
            
            // Change button text
            const button = document.querySelector('.accept-btn');
            button.innerHTML = 'Thank You! 💝';
            button.style.background = 'linear-gradient(to right, #10b981, #059669)';
            button.style.transform = 'scale(1.1)';
            
            // Show message
            setTimeout(() => {
                const message = document.createElement('div');
                message.innerHTML = `
                    <div style="position: fixed; top: 50%; left: 50%; transform: translate(-50%, -50%); 
                           background: rgba(255, 255, 255, 0.95); padding: 40px; border-radius: 20px; 
                           text-align: center; z-index: 10000; box-shadow: 0 20px 40px rgba(0,0,0,0.2);
                           border: 5px solid #db2777; max-width: 80%;">
                        <h2 style="color: #db2777; font-family: cursive; font-size: 2.5rem; margin-bottom: 20px;">
                            You've Made Me So Happy! 💖
                        </h2>
                        <p style="font-size: 1.3rem; color: #701a75; margin-bottom: 30px;">
                            I promise to cherish this opportunity and be the best partner I can be.<br>
                            Let's build something beautiful together.
                        </p>
                        <button onclick="closeMessage(this)" style="padding: 10px 30px; 
                               background: #db2777; color: white; border: none; border-radius: 50px; 
                               font-size: 1.2rem; cursor: pointer;">
                            Continue
                        </button>
                    </div>
                `;
                document.body.appendChild(message);
            }, 1000);
        }
        
        function closeMessage(button) {
            const messageDiv = button.closest('div');
            if (messageDiv) {
                messageDiv.style.animation = 'fadeOut 0.5s forwards';
                setTimeout(() => {
                    if (messageDiv.parentNode) {
                        document.body.removeChild(messageDiv);
                    }
                }, 500);
            }
        }
        
        // Add some initial floating hearts
        window.addEventListener('load', function() {
            setTimeout(() => {
                const hearts = document.querySelectorAll('.heart');
                hearts.forEach(heart => {
                    heart.style.animationDelay = Math.random() + 's';
                });
            }, 500);
        });
    </script>
</body>
</html>
