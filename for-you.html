<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>💕 A Special Message For You</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600;700&family=Caveat:wght@400;500;600;700&family=Quicksand:wght@300;400;500;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --rose: #e8a0b5;
            --rose-deep: #d4748f;
            --blush: #fce4ec;
            --cream: #fff8f0;
            --gold: #d4a574;
            --wine: #8b4557;
            --soft-shadow: rgba(139, 69, 87, 0.15);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Quicksand', sans-serif;
            background: linear-gradient(135deg, var(--cream) 0%, var(--blush) 50%, #ffd6e7 100%);
            min-height: 100vh;
            overflow-x: hidden;
            cursor: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='32' height='32' viewBox='0 0 32 32'%3E%3Ctext y='24' font-size='24'%3E💕%3C/text%3E%3C/svg%3E"), auto;
        }

        /* Floating Hearts Background */
        .hearts-bg {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 0;
            overflow: hidden;
        }

        .floating-heart {
            position: absolute;
            font-size: 20px;
            animation: floatUp linear infinite;
            opacity: 0.6;
        }

        @keyframes floatUp {
            0% {
                transform: translateY(100vh) rotate(0deg) scale(1);
                opacity: 0;
            }
            10% {
                opacity: 0.6;
            }
            90% {
                opacity: 0.6;
            }
            100% {
                transform: translateY(-100px) rotate(360deg) scale(0.5);
                opacity: 0;
            }
        }

        /* Sparkle Effect */
        .sparkle {
            position: fixed;
            width: 10px;
            height: 10px;
            background: radial-gradient(circle, var(--gold) 0%, transparent 70%);
            border-radius: 50%;
            pointer-events: none;
            animation: sparkle 0.8s ease-out forwards;
            z-index: 1000;
        }

        @keyframes sparkle {
            0% {
                transform: scale(0) rotate(0deg);
                opacity: 1;
            }
            50% {
                transform: scale(1.5) rotate(180deg);
                opacity: 0.8;
            }
            100% {
                transform: scale(0) rotate(360deg);
                opacity: 0;
            }
        }

        /* Screens */
        .screen {
            display: none;
            min-height: 100vh;
            position: relative;
            z-index: 1;
        }

        .screen.active {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            animation: fadeIn 1s ease-out;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* Screen 1: Envelope */
        .envelope-container {
            perspective: 1000px;
        }

        .envelope {
            width: 320px;
            height: 220px;
            position: relative;
            cursor: pointer;
            transform-style: preserve-3d;
            transition: transform 0.6s ease;
        }

        .envelope:hover {
            transform: scale(1.05);
        }

        .envelope-body {
            width: 100%;
            height: 100%;
            background: linear-gradient(145deg, #fff 0%, var(--cream) 100%);
            border-radius: 8px;
            box-shadow: 
                0 20px 60px var(--soft-shadow),
                0 10px 30px rgba(0,0,0,0.1),
                inset 0 -5px 20px rgba(232, 160, 181, 0.2);
            position: relative;
            overflow: hidden;
        }

        .envelope-body::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 100%;
            background: 
                linear-gradient(135deg, transparent 48%, var(--rose) 48%, var(--rose) 52%, transparent 52%),
                linear-gradient(-135deg, transparent 48%, var(--rose-deep) 48%, var(--rose-deep) 52%, transparent 52%);
            clip-path: polygon(0 0, 50% 60%, 100% 0);
            z-index: 2;
        }

        .envelope-flap {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 120px;
            background: linear-gradient(180deg, var(--rose) 0%, var(--rose-deep) 100%);
            clip-path: polygon(0 0, 50% 100%, 100% 0);
            transform-origin: top center;
            transition: transform 0.8s cubic-bezier(0.4, 0, 0.2, 1);
            z-index: 3;
        }

        .envelope.opened .envelope-flap {
            transform: rotateX(180deg);
        }

        .heart-seal {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 60px;
            height: 60px;
            background: linear-gradient(145deg, var(--wine) 0%, #6d3344 100%);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 28px;
            box-shadow: 0 4px 15px rgba(139, 69, 87, 0.4);
            z-index: 4;
            animation: pulse 2s ease-in-out infinite;
        }

        @keyframes pulse {
            0%, 100% { transform: translate(-50%, -50%) scale(1); }
            50% { transform: translate(-50%, -50%) scale(1.1); }
        }

        .click-hint {
            font-family: 'Caveat', cursive;
            font-size: 1.4rem;
            color: var(--wine);
            margin-top: 30px;
            animation: bounce 2s ease-in-out infinite;
        }

        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }

        /* Screen 2: Question */
        .question-container {
            text-align: center;
            padding: 40px;
        }

        .love-text {
            font-family: 'Playfair Display', serif;
            font-size: clamp(2rem, 6vw, 4rem);
            color: var(--wine);
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px var(--soft-shadow);
        }

        .love-text span {
            display: inline-block;
            animation: letterFloat 3s ease-in-out infinite;
        }

        @keyframes letterFloat {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }

        .sub-text {
            font-family: 'Caveat', cursive;
            font-size: clamp(1.5rem, 4vw, 2.5rem);
            color: var(--rose-deep);
            margin-bottom: 50px;
            line-height: 1.6;
        }

        .typewriter {
            overflow: hidden;
            white-space: nowrap;
            border-right: 3px solid var(--rose-deep);
            animation: typing 3s steps(40) forwards, blink 0.8s step-end infinite;
            max-width: fit-content;
            margin: 0 auto 50px;
        }

        @keyframes typing {
            from { width: 0; }
            to { width: 100%; }
        }

        @keyframes blink {
            50% { border-color: transparent; }
        }

        .buttons-container {
            display: flex;
            gap: 30px;
            flex-wrap: wrap;
            justify-content: center;
        }

        .btn {
            padding: 18px 50px;
            font-family: 'Quicksand', sans-serif;
            font-size: 1.2rem;
            font-weight: 600;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }

        .btn-yes {
            background: linear-gradient(145deg, var(--rose) 0%, var(--rose-deep) 100%);
            color: white;
            box-shadow: 0 10px 30px rgba(212, 116, 143, 0.4);
        }

        .btn-yes:hover {
            transform: translateY(-5px) scale(1.05);
            box-shadow: 0 15px 40px rgba(212, 116, 143, 0.5);
        }

        .btn-yes::after {
            content: '💕';
            position: absolute;
            right: 15px;
            animation: heartBeat 1s ease-in-out infinite;
        }

        @keyframes heartBeat {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.3); }
        }

        .btn-no {
            background: linear-gradient(145deg, #f0f0f0 0%, #ddd 100%);
            color: #888;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: all 0.1s ease;
        }

        /* Screen 3: Celebration */
        .celebration-container {
            text-align: center;
            padding: 40px;
        }

        .big-heart {
            font-size: clamp(80px, 20vw, 150px);
            animation: heartPump 0.8s ease-in-out infinite;
            filter: drop-shadow(0 10px 30px rgba(212, 116, 143, 0.5));
        }

        @keyframes heartPump {
            0%, 100% { transform: scale(1); }
            15% { transform: scale(1.2); }
            30% { transform: scale(1); }
            45% { transform: scale(1.15); }
            60% { transform: scale(1); }
        }

        .celebration-text {
            font-family: 'Playfair Display', serif;
            font-size: clamp(2rem, 8vw, 5rem);
            background: linear-gradient(145deg, var(--wine) 0%, var(--rose-deep) 50%, var(--gold) 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            margin: 30px 0;
            animation: glow 2s ease-in-out infinite;
        }

        @keyframes glow {
            0%, 100% { filter: drop-shadow(0 0 10px var(--rose)); }
            50% { filter: drop-shadow(0 0 30px var(--rose)); }
        }

        .love-message {
            font-family: 'Caveat', cursive;
            font-size: clamp(1.3rem, 4vw, 2rem);
            color: var(--wine);
            max-width: 600px;
            line-height: 1.8;
            margin: 20px auto;
        }

        .promise-card {
            background: rgba(255, 255, 255, 0.9);
            backdrop-filter: blur(10px);
            padding: 40px;
            border-radius: 20px;
            box-shadow: 
                0 20px 60px var(--soft-shadow),
                inset 0 0 0 2px var(--rose);
            max-width: 500px;
            margin: 40px auto;
            position: relative;
        }

        .promise-card::before {
            content: '💍';
            position: absolute;
            top: -20px;
            left: 50%;
            transform: translateX(-50%);
            font-size: 40px;
            animation: rotate 4s linear infinite;
        }

        @keyframes rotate {
            from { transform: translateX(-50%) rotate(0deg); }
            to { transform: translateX(-50%) rotate(360deg); }
        }

        .promise-text {
            font-family: 'Playfair Display', serif;
            font-size: 1.1rem;
            color: var(--wine);
            line-height: 2;
        }

        .signature {
            font-family: 'Caveat', cursive;
            font-size: 2rem;
            color: var(--rose-deep);
            margin-top: 20px;
        }

        /* Confetti */
        .confetti {
            position: fixed;
            width: 12px;
            height: 12px;
            top: -20px;
            animation: confettiFall linear forwards;
            z-index: 1000;
        }

        @keyframes confettiFall {
            to {
                transform: translateY(100vh) rotate(720deg);
            }
        }

        /* Fireworks */
        .firework {
            position: fixed;
            width: 6px;
            height: 6px;
            border-radius: 50%;
            animation: explode 1s ease-out forwards;
        }

        @keyframes explode {
            0% {
                transform: scale(1);
                opacity: 1;
            }
            100% {
                transform: scale(0);
                opacity: 0;
            }
        }

        /* Responsive */
        @media (max-width: 600px) {
            .envelope {
                width: 280px;
                height: 190px;
            }
            
            .buttons-container {
                flex-direction: column;
                gap: 20px;
            }
            
            .btn {
                width: 200px;
            }
        }

        /* Dev signature - hidden */
        .dev-love {
            position: fixed;
            bottom: 10px;
            right: 10px;
            font-family: 'Caveat', cursive;
            font-size: 0.9rem;
            color: rgba(139, 69, 87, 0.3);
            z-index: 1;
        }
    </style>
</head>
<body>
    <div class="hearts-bg" id="heartsBg"></div>

    <!-- Screen 1: Envelope -->
    <div class="screen active" id="screen1">
        <div class="envelope-container">
            <div class="envelope" id="envelope" onclick="openEnvelope()">
                <div class="envelope-body"></div>
                <div class="envelope-flap"></div>
                <div class="heart-seal">💌</div>
            </div>
        </div>
        <p class="click-hint">✨ Click to open ✨</p>
    </div>

    <!-- Screen 2: Question -->
    <div class="screen" id="screen2">
        <div class="question-container">
            <h1 class="love-text" id="loveText"></h1>
            <p class="sub-text typewriter">From the moment I saw you, my heart knew...</p>
            <p class="sub-text" style="animation-delay: 0.5s;">
                Every line of code I write,<br>
                Every bug I fix,<br>
                Every feature I ship...<br>
                <strong>It all means nothing without you by my side 💕</strong>
            </p>
            <div class="buttons-container">
                <button class="btn btn-yes" onclick="sayYes()">Yes, I love you too!</button>
                <button class="btn btn-no" id="noBtn" onmouseover="moveButton()" onclick="moveButton()">No</button>
            </div>
        </div>
    </div>

    <!-- Screen 3: Celebration -->
    <div class="screen" id="screen3">
        <div class="celebration-container">
            <div class="big-heart">💖</div>
            <h1 class="celebration-text">You Made Me The Happiest!</h1>
            <p class="love-message">
                "In a world full of algorithms, you're my favorite output.<br>
                In a sea of infinite loops, you're my perfect break.<br>
                You compiled my heart and it returned... true love."
            </p>
            <div class="promise-card">
                <p class="promise-text">
                    I promise to:<br>
                    🌹 Love you like a recursive function - endlessly<br>
                    🌹 Be your constant in every variable life throws<br>
                    🌹 Debug any problem in your life<br>
                    🌹 Never let our love throw an exception<br>
                    🌹 Keep our connection strong with 100% uptime
                </p>
                <p class="signature">Forever Yours ❤️</p>
            </div>
        </div>
    </div>

    <div class="dev-love">Made with 💕</div>

    <script>
        // Create floating hearts background
        function createFloatingHearts() {
            const heartsBg = document.getElementById('heartsBg');
            const hearts = ['💕', '💖', '💗', '💓', '💝', '🌸', '✨', '💫'];
            
            for (let i = 0; i < 30; i++) {
                setTimeout(() => {
                    const heart = document.createElement('div');
                    heart.className = 'floating-heart';
                    heart.textContent = hearts[Math.floor(Math.random() * hearts.length)];
                    heart.style.left = Math.random() * 100 + 'vw';
                    heart.style.animationDuration = (8 + Math.random() * 10) + 's';
                    heart.style.animationDelay = Math.random() * 5 + 's';
                    heart.style.fontSize = (15 + Math.random() * 20) + 'px';
                    heartsBg.appendChild(heart);
                    
                    // Remove after animation
                    setTimeout(() => heart.remove(), 20000);
                }, i * 200);
            }
            
            // Keep creating hearts
            setInterval(createFloatingHearts, 15000);
        }

        // Sparkle effect on mouse move
        document.addEventListener('mousemove', (e) => {
            if (Math.random() > 0.92) {
                createSparkle(e.clientX, e.clientY);
            }
        });

        function createSparkle(x, y) {
            const sparkle = document.createElement('div');
            sparkle.className = 'sparkle';
            sparkle.style.left = x + 'px';
            sparkle.style.top = y + 'px';
            document.body.appendChild(sparkle);
            setTimeout(() => sparkle.remove(), 800);
        }

        // Open envelope
        function openEnvelope() {
            const envelope = document.getElementById('envelope');
            envelope.classList.add('opened');
            
            // Create burst of sparkles
            for (let i = 0; i < 20; i++) {
                setTimeout(() => {
                    const rect = envelope.getBoundingClientRect();
                    createSparkle(
                        rect.left + rect.width/2 + (Math.random() - 0.5) * 100,
                        rect.top + rect.height/2 + (Math.random() - 0.5) * 100
                    );
                }, i * 50);
            }
            
            setTimeout(() => {
                document.getElementById('screen1').classList.remove('active');
                document.getElementById('screen2').classList.add('active');
                animateLoveText();
            }, 1500);
        }

        // Animate love text letter by letter
        function animateLoveText() {
            const text = "Will You Be Mine? 💕";
            const container = document.getElementById('loveText');
            container.innerHTML = '';
            
            text.split('').forEach((letter, i) => {
                const span = document.createElement('span');
                span.textContent = letter;
                span.style.animationDelay = (i * 0.1) + 's';
                span.style.opacity = '0';
                span.style.animation = `letterFloat 3s ease-in-out infinite ${i * 0.1}s, fadeIn 0.5s ease forwards ${i * 0.05}s`;
                container.appendChild(span);
            });
        }

        // Move "No" button away
        let noButtonMoves = 0;
        function moveButton() {
            const btn = document.getElementById('noBtn');
            noButtonMoves++;
            
            const messages = [
                "Think again! 🥺",
                "Are you sure? 😢",
                "Please? 🙏",
                "Pretty please? 💕",
                "One more chance? 🌹",
                "I won't give up! 💖"
            ];
            
            if (noButtonMoves <= 6) {
                btn.textContent = messages[noButtonMoves - 1] || "Nope!";
            }
            
            const maxX = window.innerWidth - btn.offsetWidth - 50;
            const maxY = window.innerHeight - btn.offsetHeight - 50;
            
            btn.style.position = 'fixed';
            btn.style.left = Math.random() * maxX + 'px';
            btn.style.top = Math.random() * maxY + 'px';
            btn.style.zIndex = '100';
        }

        // Say yes - celebration!
        function sayYes() {
            document.getElementById('screen2').classList.remove('active');
            document.getElementById('screen3').classList.add('active');
            
            // Launch confetti
            launchConfetti();
            
            // Launch fireworks
            for (let i = 0; i < 5; i++) {
                setTimeout(() => launchFirework(), i * 500);
            }
            
            // Play celebration sound (if supported)
            try {
                const audioContext = new (window.AudioContext || window.webkitAudioContext)();
                playHappyTone(audioContext);
            } catch (e) {}
        }

        function launchConfetti() {
            const colors = ['#e8a0b5', '#d4748f', '#fce4ec', '#d4a574', '#8b4557', '#ff6b9d', '#ffd700'];
            const shapes = ['❤️', '💕', '💖', '🌸', '✨', '💫', '🎉', '🎊'];
            
            for (let i = 0; i < 100; i++) {
                setTimeout(() => {
                    const confetti = document.createElement('div');
                    confetti.className = 'confetti';
                    
                    if (Math.random() > 0.5) {
                        confetti.textContent = shapes[Math.floor(Math.random() * shapes.length)];
                        confetti.style.fontSize = (15 + Math.random() * 15) + 'px';
                        confetti.style.background = 'transparent';
                    } else {
                        confetti.style.background = colors[Math.floor(Math.random() * colors.length)];
                        confetti.style.borderRadius = Math.random() > 0.5 ? '50%' : '0';
                    }
                    
                    confetti.style.left = Math.random() * 100 + 'vw';
                    confetti.style.animationDuration = (2 + Math.random() * 3) + 's';
                    document.body.appendChild(confetti);
                    
                    setTimeout(() => confetti.remove(), 5000);
                }, i * 30);
            }
        }

        function launchFirework() {
            const colors = ['#e8a0b5', '#d4748f', '#d4a574', '#ff6b9d', '#ffd700'];
            const x = Math.random() * window.innerWidth;
            const y = Math.random() * (window.innerHeight * 0.5);
            
            for (let i = 0; i < 30; i++) {
                const particle = document.createElement('div');
                particle.className = 'firework';
                particle.style.background = colors[Math.floor(Math.random() * colors.length)];
                particle.style.left = x + 'px';
                particle.style.top = y + 'px';
                particle.style.boxShadow = `0 0 10px ${colors[Math.floor(Math.random() * colors.length)]}`;
                
                const angle = (i / 30) * Math.PI * 2;
                const velocity = 50 + Math.random() * 100;
                const endX = x + Math.cos(angle) * velocity;
                const endY = y + Math.sin(angle) * velocity;
                
                particle.animate([
                    { left: x + 'px', top: y + 'px', opacity: 1 },
                    { left: endX + 'px', top: endY + 'px', opacity: 0 }
                ], {
                    duration: 1000,
                    easing: 'ease-out'
                });
                
                document.body.appendChild(particle);
                setTimeout(() => particle.remove(), 1000);
            }
        }

        function playHappyTone(audioContext) {
            const notes = [523.25, 659.25, 783.99, 1046.50]; // C5, E5, G5, C6
            notes.forEach((freq, i) => {
                setTimeout(() => {
                    const oscillator = audioContext.createOscillator();
                    const gainNode = audioContext.createGain();
                    oscillator.connect(gainNode);
                    gainNode.connect(audioContext.destination);
                    oscillator.frequency.value = freq;
                    oscillator.type = 'sine';
                    gainNode.gain.setValueAtTime(0.1, audioContext.currentTime);
                    gainNode.gain.exponentialRampToValueAtTime(0.01, audioContext.currentTime + 0.5);
                    oscillator.start();
                    oscillator.stop(audioContext.currentTime + 0.5);
                }, i * 150);
            });
        }

        // Initialize
        createFloatingHearts();
    </script>
</body>
</html>
