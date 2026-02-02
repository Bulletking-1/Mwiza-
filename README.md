<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DESTRUCTION NOTICE</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Courier New', monospace;
            background: #000;
            color: #ff0000;
            min-height: 100vh;
            overflow: hidden;
            position: relative;
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 40px 20px;
            position: relative;
            z-index: 1;
        }
        
        .destruction-header {
            text-align: center;
            border: 3px solid #ff0000;
            padding: 30px;
            margin-bottom: 50px;
            background: rgba(0, 0, 0, 0.8);
            box-shadow: 0 0 50px #ff0000;
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0% { box-shadow: 0 0 20px #ff0000; }
            50% { box-shadow: 0 0 60px #ff0000; }
            100% { box-shadow: 0 0 20px #ff0000; }
        }
        
        h1 {
            font-size: 3.5rem;
            text-transform: uppercase;
            letter-spacing: 5px;
            margin-bottom: 20px;
            text-shadow: 0 0 20px #ff0000;
        }
        
        .subtitle {
            font-size: 1.5rem;
            color: #ff4444;
            margin-bottom: 30px;
        }
        
        .cross-out {
            text-decoration: line-through;
            color: #666;
            font-size: 1.2rem;
            padding: 20px;
            border: 1px dashed #ff0000;
            margin: 30px 0;
            background: rgba(255, 0, 0, 0.1);
        }
        
        .destroyer {
            text-align: center;
            font-size: 2rem;
            color: #ff9900;
            margin: 40px 0;
            padding: 20px;
            border: 2px solid #ff9900;
            text-shadow: 0 0 10px #ff9900;
        }
        
        .invalid-stamp {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%) rotate(-15deg);
            font-size: 8rem;
            color: rgba(255, 0, 0, 0.3);
            z-index: 0;
            pointer-events: none;
            user-select: none;
        }
        
        .message {
            background: rgba(255, 0, 0, 0.05);
            padding: 30px;
            margin: 40px 0;
            border-left: 5px solid #ff0000;
        }
        
        .signature {
            text-align: right;
            margin-top: 50px;
            padding-top: 20px;
            border-top: 1px solid #ff0000;
            font-size: 1.3rem;
            color: #ff9900;
        }
        
        .bullet {
            position: fixed;
            font-size: 2rem;
            opacity: 0;
            animation: shoot 1s linear;
        }
        
        @keyframes shoot {
            0% {
                left: -50px;
                top: 50%;
                opacity: 1;
                transform: rotate(0deg);
            }
            100% {
                left: 100%;
                top: 30%;
                opacity: 0;
                transform: rotate(720deg);
            }
        }
        
        .glitch {
            position: relative;
            animation: glitch 5s infinite;
        }
        
        @keyframes glitch {
            0% { transform: translate(0); }
            20% { transform: translate(-2px, 2px); }
            40% { transform: translate(-2px, -2px); }
            60% { transform: translate(2px, 2px); }
            80% { transform: translate(2px, -2px); }
            100% { transform: translate(0); }
        }
        
        .fire {
            position: fixed;
            bottom: 0;
            left: 0;
            width: 100%;
            height: 100px;
            background: linear-gradient(to top, #ff0000, #ff9900, #000);
            opacity: 0.7;
            z-index: -1;
            animation: burn 3s infinite;
        }
        
        @keyframes burn {
            0% { height: 100px; opacity: 0.7; }
            50% { height: 150px; opacity: 0.9; }
            100% { height: 100px; opacity: 0.7; }
        }
        
        .forex-badge {
            display: inline-block;
            background: linear-gradient(45deg, #ff9900, #ff0000);
            color: #000;
            padding: 10px 20px;
            border-radius: 5px;
            font-weight: bold;
            margin: 0 10px;
            transform: rotate(5deg);
        }
    </style>
</head>
<body>
    <div class="invalid-stamp">INVALID</div>
    
    <div class="container">
        <div class="destruction-header glitch">
            <h1>APOLOGY DESTROYED</h1>
            <div class="subtitle">ALL PREVIOUS SENTIMENTS NULLIFIED</div>
            <div class="forex-badge">BULLET FOREX KING</div>
        </div>
        
        <div class="cross-out">
            <p>"My dearest Mwiza Beyonce Mwiya, I am writing this with a heart full of regret and love..."</p>
            <p><strong>STATUS: TERMINATED</strong></p>
        </div>
        
        <div class="message">
            <h2>DECLARATION OF INVALIDITY</h2>
            <p>The previous apology website addressed to <strong>Mwiza Beyonce Mwiya</strong> has been officially decommissioned.</p>
            <p>All emotional content, promises, and sentimental expressions contained within are hereby declared:</p>
            <ul style="margin: 20px; color: #ff4444;">
                <li>NULL AND VOID</li>
                <li>EMOTIONALLY INVALID</li>
                <li>STRATEGICALLY RETRACTED</li>
                <li>PERMANENTLY ARCHIVED</li>
            </ul>
            <p>The creator, <strong>Lifasi Malumo Lucky</strong>, has upgraded to a new paradigm.</p>
        </div>
        
        <div class="destroyer">
            DESTROYED BY: <span class="forex-badge">BULLET FOREX KING</span>
        </div>
        
        <div class="message">
            <h2>NEW REALITY PROTOCOL</h2>
            <p>Sentimental apologies have been replaced with strategic forward movement.</p>
            <p>The energy previously allocated to emotional appeals has been redirected to:</p>
            <ul style="margin: 20px; color: #ff9900;">
                <li>MARKET ANALYSIS</li>
                <li>FINANCIAL GROWTH</li>
                <li>PERSONAL DEVELOPMENT</li>
                <li>STRATEGIC POSITIONING</li>
            </ul>
            <p><strong>Law 7 of Power:</strong> Get others to do the work for you, but always take the credit.</p>
            <p><strong>New Principle:</strong> Own the stage, don't build it. Control the narrative, don't follow it.</p>
        </div>
        
        <div class="signature">
            <p>Signed,</p>
            <p><strong>LIFASI MALUMO LUCKY</strong></p>
            <p>AKA: <span class="forex-badge">BULLET FOREX KING</span></p>
            <p>DATE: [REDACTED FOR SECURITY]</p>
        </div>
    </div>
    
    <div class="fire"></div>
    
    <script>
        // Create bullet animations
        function createBullet() {
            const bullet = document.createElement('div');
            bullet.className = 'bullet';
            bullet.innerHTML = '💥';
            bullet.style.left = '-50px';
            bullet.style.top = Math.random() * 80 + 10 + '%';
            document.body.appendChild(bullet);
            
            setTimeout(() => {
                document.body.removeChild(bullet);
            }, 1000);
        }
        
        // Shoot bullets periodically
        setInterval(createBullet, 500);
        
        // Glitch effect
        const glitchElements = document.querySelectorAll('.glitch');
        setInterval(() => {
            glitchElements.forEach(el => {
                el.style.transform = `translate(${Math.random() * 10 - 5}px, ${Math.random() * 10 - 5}px)`;
            });
        }, 100);
        
        // Terminal-style typing effect for a message
        const messages = [
            "APOLOGY TERMINATED",
            "SENTIMENTS DELETED",
            "EMOTIONAL BAGGAGE PURGED",
            "BULLET FOREX KING ACTIVE",
            "ALL PREVIOUS COMMS NULLIFIED"
        ];
        
        let messageIndex = 0;
        const terminal = document.createElement('div');
        terminal.style.position = 'fixed';
        terminal.style.bottom = '10px';
        terminal.style.right = '10px';
        terminal.style.color = '#00ff00';
        terminal.style.fontSize = '0.9rem';
        terminal.style.fontFamily = 'Courier New';
        terminal.style.background = 'rgba(0,0,0,0.7)';
        terminal.style.padding = '10px';
        terminal.style.border = '1px solid #00ff00';
        document.body.appendChild(terminal);
        
        function updateTerminal() {
            terminal.textContent = `> ${messages[messageIndex]}`;
            messageIndex = (messageIndex + 1) % messages.length;
        }
        
        updateTerminal();
        setInterval(updateTerminal, 3000);
        
        // Add some random sparks
        setInterval(() => {
            const spark = document.createElement('div');
            spark.style.position = 'fixed';
            spark.style.width = '3px';
            spark.style.height = '3px';
            spark.style.background = '#ff9900';
            spark.style.borderRadius = '50%';
            spark.style.left = Math.random() * 100 + '%';
            spark.style.top = Math.random() * 100 + '%';
            spark.style.boxShadow = '0 0 10px #ff9900';
            document.body.appendChild(spark);
            
            setTimeout(() => {
                if (spark.parentNode) {
                    document.body.removeChild(spark);
                }
            }, 1000);
        }, 100);
    </script>
</body>
</html>
