<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Community Hub</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: #0a0a0a;
            color: #ffffff;
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 20px;
            position: relative;
            overflow-x: hidden;
        }

        /* Animated background */
        body::before {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: 
                radial-gradient(circle at 20% 50%, rgba(255, 255, 255, 0.1) 0%, transparent 50%),
                radial-gradient(circle at 80% 80%, rgba(255, 255, 255, 0.05) 0%, transparent 50%),
                linear-gradient(135deg, #0a0a0a 0%, #1a1a1a 100%);
            animation: backgroundShift 15s ease-in-out infinite;
            z-index: -2;
        }

        @keyframes backgroundShift {
            0% {
                background: 
                    radial-gradient(circle at 20% 50%, rgba(255, 255, 255, 0.1) 0%, transparent 50%),
                    radial-gradient(circle at 80% 80%, rgba(255, 255, 255, 0.05) 0%, transparent 50%),
                    linear-gradient(135deg, #0a0a0a 0%, #1a1a1a 100%);
            }
            50% {
                background: 
                    radial-gradient(circle at 80% 50%, rgba(255, 255, 255, 0.15) 0%, transparent 50%),
                    radial-gradient(circle at 20% 80%, rgba(255, 255, 255, 0.08) 0%, transparent 50%),
                    linear-gradient(135deg, #1a1a1a 0%, #0a0a0a 100%);
            }
            100% {
                background: 
                    radial-gradient(circle at 20% 50%, rgba(255, 255, 255, 0.1) 0%, transparent 50%),
                    radial-gradient(circle at 80% 80%, rgba(255, 255, 255, 0.05) 0%, transparent 50%),
                    linear-gradient(135deg, #0a0a0a 0%, #1a1a1a 100%);
            }
        }

        /* Animated particles */
        .particles {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            pointer-events: none;
        }

        .particle {
            position: absolute;
            width: 2px;
            height: 2px;
            background: rgba(255, 255, 255, 0.5);
            border-radius: 50%;
            animation: float 20s infinite;
        }

        @keyframes float {
            0% {
                transform: translateY(100vh) translateX(0);
                opacity: 0;
            }
            10% {
                opacity: 1;
            }
            90% {
                opacity: 1;
            }
            100% {
                transform: translateY(-100vh) translateX(100px);
                opacity: 0;
            }
        }

        /* Main wrapper */
        .wrapper {
            width: 100%;
            max-width: 1200px;
            display: grid;
            grid-template-columns: auto 1fr;
            gap: 50px;
            align-items: start;
        }

        /* Left section - Square buttons (vertical stack) */
        .menu-section {
            display: flex;
            flex-direction: column;
            gap: 20px;
            animation: slideInLeft 0.8s ease-out;
            align-self: center;
        }

        @keyframes slideInLeft {
            from {
                opacity: 0;
                transform: translateX(-30px);
            }
            to {
                opacity: 1;
                transform: translateX(0);
            }
        }

        .square-btn {
            width: 180px;
            height: 70px;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 15px;
            padding: 0;
            font-size: 1em;
            font-weight: 700;
            border: 1px solid #666;
            border-radius: 10px;
            text-decoration: none;
            cursor: pointer;
            transition: all 0.35s cubic-bezier(0.25, 0.46, 0.45, 0.94);
            text-transform: uppercase;
            letter-spacing: 1px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
            position: relative;
            overflow: hidden;
            animation: fadeInUp 1s ease-out;
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .square-btn::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: rgba(255, 255, 255, 0.1);
            transition: left 0.35s ease;
            z-index: 0;
        }

        .square-btn:hover::before {
            left: 100%;
        }

        .square-btn > * {
            position: relative;
            z-index: 1;
        }

        .square-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 25px rgba(0, 0, 0, 0.4);
        }

        .square-btn:active {
            transform: translateY(-1px);
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.3);
        }

        .btn-discord {
            background: linear-gradient(135deg, #5865F2 0%, #4752C4 100%);
            border-color: #7289DA;
            color: #ffffff;
        }

        .btn-discord:hover {
            background: linear-gradient(135deg, #7289DA 0%, #5865F2 100%);
            border-color: #99AAF2;
            box-shadow: 0 6px 25px rgba(88, 101, 242, 0.4);
        }

        .btn-donate {
            background: linear-gradient(135deg, #2d2d2d 0%, #1a1a1a 100%);
            border-color: #555;
            color: #ffffff;
        }

        .btn-donate:hover {
            background: linear-gradient(135deg, #444 0%, #2d2d2d 100%);
            border-color: #777;
            box-shadow: 0 6px 25px rgba(255, 255, 255, 0.2);
        }

        .icon {
            font-size: 1.6em;
            display: inline-block;
            transition: transform 0.3s ease;
        }

        .square-btn:hover .icon {
            transform: scale(1.2) rotate(10deg);
        }

        .btn-text {
            font-size: 0.9em;
        }

        /* Right section - Welcome message */
        .intro-section {
            animation: slideInRight 0.8s ease-out;
            display: flex;
            align-items: center;
        }

        @keyframes slideInRight {
            from {
                opacity: 0;
                transform: translateX(30px);
            }
            to {
                opacity: 1;
                transform: translateX(0);
            }
        }

        .intro-container {
            background: linear-gradient(135deg, rgba(26, 26, 26, 0.95) 0%, rgba(45, 45, 45, 0.95) 100%);
            border: 1px solid #444;
            border-radius: 16px;
            padding: 50px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.8), inset 0 1px 0 rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            width: 100%;
        }

        .intro-container h1 {
            font-size: 2.8em;
            margin-bottom: 30px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
            letter-spacing: 1.5px;
            font-weight: 700;
            animation: fadeInDown 1s ease-out;
        }

        @keyframes fadeInDown {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .intro-container p {
            font-size: 1.05em;
            color: #ddd;
            line-height: 2;
            margin-bottom: 22px;
            animation: fadeIn 1.2s ease-out;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        .highlight {
            color: #fff;
            font-weight: 700;
        }

        .intro-container .footer {
            margin-top: 35px;
            padding-top: 30px;
            border-top: 1px solid #444;
            color: #999;
            font-size: 0.95em;
            letter-spacing: 0.5px;
            animation: fadeIn 1.4s ease-out;
        }

        /* Page transition effect */
        body.fade-out {
            animation: fadeOut 0.6s ease-out forwards;
        }

        @keyframes fadeOut {
            from {
                opacity: 1;
            }
            to {
                opacity: 0;
            }
        }

        /* Responsive */
        @media (max-width: 1024px) {
            .wrapper {
                grid-template-columns: 1fr;
                gap: 40px;
            }

            .menu-section {
                flex-direction: row;
                gap: 20px;
                justify-content: center;
            }

            .square-btn {
                width: 150px;
                height: 60px;
                font-size: 0.9em;
            }

            .intro-container {
                padding: 40px;
            }

            .intro-container h1 {
                font-size: 2em;
                margin-bottom: 20px;
            }

            .intro-container p {
                font-size: 1em;
                line-height: 1.8;
            }
        }

        @media (max-width: 768px) {
            .wrapper {
                gap: 25px;
            }

            .menu-section {
                flex-direction: row;
                gap: 15px;
            }

            .square-btn {
                width: 140px;
                height: 55px;
                gap: 10px;
                font-size: 0.8em;
            }

            .intro-container {
                padding: 30px;
            }

            .intro-container h1 {
                font-size: 1.6em;
                margin-bottom: 15px;
            }

            .intro-container p {
                font-size: 0.95em;
                line-height: 1.6;
                margin-bottom: 15px;
            }

            .icon {
                font-size: 1.3em;
            }

            .btn-text {
                font-size: 0.75em;
            }
        }
    </style>
</head>
<body>
    <div class="particles" id="particles"></div>

    <div class="wrapper">
        <!-- Left section - Square buttons (vertical) -->
        <div class="menu-section">
            <a href="https://discord.gg/8j4zMgWJK3" class="square-btn btn-discord" target="_blank">
                <span class="icon">💫</span>
                <span class="btn-text">DISCORD</span>
            </a>
            <a href="https://ezdn.app/id1309927191" class="square-btn btn-donate" target="_blank">
                <span class="icon">✅</span>
                <span class="btn-text">DONATE</span>
            </a>
        </div>

        <!-- Right section - Welcome message -->
        <div class="intro-section">
            <div class="intro-container">
                <h1>ยินดีตอนรับ</h1>
                <p>
                    สวัสดี ยินดีต้อนรับ <span class="highlight">Community เมนู</span> ผมเป็นเด็ก12ที่ทำเองหมด
                </p>
                <p>
                    อย่าลังเลที่จะเข้าร่วม <span class="highlight">Discord </span> ของฉัน เพื่อคุ่ยได้
                </p>
                <p>
                    หากคุณต้องการสนับสนุนเราต่อไป สามารถเลือก <span class="highlight">โดเนให้ผมไม่เนื่อก</span> เพื่อช่วยให้เราพัฒนาต่อไป
                </p>
                <div class="footer">
                    <p>Thank you ที่เข้ามาดู! 🖤</p>
                </div>
            </div>
        </div>
    </div>

    <script>
        // Create animated particles
        function createParticles() {
            const particlesContainer = document.getElementById('particles');
            const particleCount = 50;

            for (let i = 0; i < particleCount; i++) {
                const particle = document.createElement('div');
                particle.className = 'particle';
                particle.style.left = Math.random() * 100 + '%';
                particle.style.animationDelay = Math.random() * 20 + 's';
                particle.style.animationDuration = (15 + Math.random() * 20) + 's';
                particlesContainer.appendChild(particle);
            }
        }

        createParticles();

        // Smooth page transition
        document.querySelectorAll('a[target="_blank"]').forEach(link => {
            link.addEventListener('click', function(e) {
                document.body.classList.add('fade-out');
                setTimeout(() => {
                    window.open(this.href, '_blank');
                    document.body.classList.remove('fade-out');
                }, 600);
            });
        });

        document.documentElement.style.scrollBehavior = 'smooth';
    </script>
</body>
</html>
