# HAPPY-9-MONTHS-ANNIVERSARY.-
<!DOCTYPE html> happy 9 months anniversary banyy ❤️💋🌹
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy 9 months Anniversary Teena Ji ❤️ - By Navu</title>
    <!-- Premium Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Fredoka:wght@400;600;700&family=Mali:wght@600;700&family=Dancing+Script:wght@700&display=swap" rel="stylesheet">
    
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            user-select: none;
            -webkit-tap-highlight-color: transparent;
        }

        body {
            font-family: 'Fredoka', sans-serif;
            background: linear-gradient(135deg, #ff9a9e 0%, #fecfef 50%, #a1c4fd 100%);
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            overflow: hidden;
            padding: 15px;
            position: relative;
        }

        /* Floating background hearts */
        .bg-heart {
            position: absolute;
            color: rgba(255, 255, 255, 0.45);
            font-size: 1.8rem;
            animation: floatBg 6s infinite linear;
            pointer-events: none;
        }

        @keyframes floatBg {
            0% { transform: translateY(100vh) rotate(0deg); opacity: 0; }
            50% { opacity: 0.8; }
            100% { transform: translateY(-10vh) rotate(360deg); opacity: 0; }
        }

        #confettiCanvas {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 9999;
        }

        /* 3D BOOK WRAPPER WITH GLOW */
        .book-wrapper {
            position: relative;
            width: 360px;
            height: 560px;
            perspective: 1800px;
            filter: drop-shadow(0 20px 30px rgba(0,0,0,0.15));
        }

        .page {
            position: absolute;
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
            border: 3px solid rgba(255, 255, 255, 0.85);
            border-radius: 28px;
            padding: 20px 18px;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            align-items: center;
            text-align: center;
            transform-origin: left center;
            transition: transform 0.8s cubic-bezier(0.645, 0.045, 0.355, 1);
            transform-style: preserve-3d;
            backface-visibility: hidden;
            box-shadow: inset 0 0 15px rgba(255, 255, 255, 0.4);
            backdrop-filter: blur(8px);
        }

        .page.flipped {
            transform: rotateY(-180deg);
        }

        /* Gradient Color Schemes */
        .p1 { z-index: 6; background: linear-gradient(135deg, #ff758c 0%, #ff7eb3 100%); color: #fff; }
        .p2 { z-index: 5; background: linear-gradient(135deg, #a1c4fd 0%, #c2e9fb 100%); color: #2d3436; }
        .p3 { z-index: 4; background: linear-gradient(135deg, #fbc2eb 0%, #a6c1ee 100%); color: #2d3436; }
        .p4 { z-index: 3; background: linear-gradient(135deg, #84fab0 0%, #8fd3f4 100%); color: #2d3436; }
        .p5 { z-index: 2; background: linear-gradient(135deg, #e0c3fc 0%, #8ec5fc 100%); color: #2d3436; }
        .p6 { z-index: 1; background: linear-gradient(135deg, #fff1eb 0%, #ace0f9 100%); color: #2d3436; }

        .spine {
            position: absolute;
            left: 0;
            top: 0;
            bottom: 0;
            width: 12px;
            background: linear-gradient(to right, rgba(0,0,0,0.18), transparent);
            border-top-left-radius: 28px;
            border-bottom-left-radius: 28px;
        }

        .badge {
            background: rgba(255, 255, 255, 0.95);
            color: #d63031;
            padding: 6px 16px;
            border-radius: 50px;
            font-size: 0.82rem;
            font-weight: 700;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            letter-spacing: 0.5px;
            text-transform: uppercase;
        }

        .speech-box {
            background: rgba(255, 255, 255, 0.95);
            color: #2d3436;
            border-radius: 22px;
            padding: 15px;
            font-family: 'Mali', cursive;
            font-size: 0.92rem;
            line-height: 1.5rem;
            box-shadow: 0 8px 22px rgba(0, 0, 0, 0.08);
            width: 100%;
        }

        .photo-frame {
            width: 118px;
            height: 118px;
            border: 4px solid #fff;
            border-radius: 50%;
            overflow: hidden;
            box-shadow: 0 8px 22px rgba(0, 0, 0, 0.18);
            background: #fff;
            transition: transform 0.3s ease;
        }

        .photo-frame:hover {
            transform: scale(1.06) rotate(3deg);
        }

        .photo-frame img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .gif-box {
            width: 110px;
            height: 110px;
            border: 3px solid #fff;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.12);
            background: #fff;
        }

        .gif-box img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .gif-row {
            display: flex;
            gap: 12px;
            justify-content: center;
        }

        .btn-cartoon {
            background: #ffffff;
            color: #ff4757;
            border: none;
            padding: 10px 24px;
            border-radius: 50px;
            font-family: 'Fredoka', sans-serif;
            font-weight: 700;
            font-size: 0.92rem;
            cursor: pointer;
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.12);
            transition: all 0.2s ease;
        }

        .btn-cartoon:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.18);
        }

        .btn-cartoon:active {
            transform: translateY(1px);
        }

        .nav-bar {
            margin-top: 18px;
            display: flex;
            gap: 15px;
            z-index: 1000;
        }

        /* GAME STYLING */
        #gameArea {
            width: 100%;
            height: 185px;
            background: rgba(255, 255, 255, 0.88);
            border-radius: 22px;
            position: relative;
            overflow: hidden;
            box-shadow: inset 0 0 12px rgba(0,0,0,0.06);
        }

        .falling-heart {
            position: absolute;
            font-size: 2.2rem;
            cursor: pointer;
            animation: fallDrop 2.2s linear forwards;
            filter: drop-shadow(0 4px 6px rgba(0,0,0,0.12));
        }

        @keyframes fallDrop {
            0% { top: -40px; transform: scale(0.8) rotate(0deg); opacity: 1; }
            50% { transform: scale(1.15) rotate(15deg); }
            100% { top: 195px; transform: scale(0.9) rotate(-15deg); opacity: 0.8; }
        }

        .court-tag {
            background: linear-gradient(135deg, #2d3436 0%, #000000 100%);
            color: #ffeaa7;
            padding: 6px 18px;
            border-radius: 50px;
            font-weight: 700;
            font-size: 0.82rem;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.18);
        }

        .handwriting {
            font-family: 'Dancing Script', cursive;
            font-size: 1.85rem;
            font-weight: 700;
            color: #d63031;
        }
    </style>
</head>
<body onclick="autoPlayMusic(event)">

    <!-- RELIABLE BACKGROUND MUSIC -->
    <audio id="bgSong" loop preload="auto">
        <source src="https://files.catbox.moe/u0q2v7.mp3" type="audio/mpeg">
    </audio>

    <!-- FLOATING BG ELEMENTS -->
    <div class="bg-heart" style="left: 8%; animation-delay: 0s;">💖</div>
    <div class="bg-heart" style="left: 28%; animation-delay: 2s;">🌸</div>
    <div class="bg-heart" style="left: 68%; animation-delay: 1s;">✨</div>
    <div class="bg-heart" style="left: 88%; animation-delay: 3s;">💕</div>

    <canvas id="confettiCanvas"></canvas>

    <div class="book-wrapper">
        
        <!-- PAGE 1: COVER -->
        <div class="page p1" id="p1">
            <div class="spine"></div>
            <span class="badge">HAPPY ANNIVERSARY 🎉🥳</span>
            
            <div class="photo-frame">
                <img src="https://i.ibb.co/ZzsZrk08/photo.jpg" alt="Teena & Navu" onerror="this.src='https://i.ibb.co/ZzsZrk08/image.jpg'">
            </div>

            <div>
                <h1 style="font-size: 1.95rem; font-weight:700; text-shadow: 0 4px 10px rgba(0,0,0,0.15);">Our Love Story 📖💖</h1>
                <p style="font-weight:600; font-size:1.05rem; margin-top: 6px; opacity: 0.95;">Teena Soni Ji & Navu 👩‍❤️‍👨</p>
            </div>
            
            <div style="font-size: 1.35rem;">🧸🎈✨🌸💘</div>
            <button class="btn-cartoon" onclick="turn(1)">Open Book 📖✨</button>
        </div>

        <!-- PAGE 2: MEMORIES -->
        <div class="page p2" id="p2">
            <div class="spine"></div>
            <span class="badge" style="background:#ff7675; color:#fff;">PAGE 02 💋🥰</span>
            
            <div class="gif-row">
                <div class="gif-box"><img src="https://media1.giphy.com/media/26BRv0ThflsHCqDrG/giphy.gif" alt="Kiss GIF"></div>
                <div class="gif-box"><img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExM3ZhcTZsN2llNWlvd2N3aXo0ZGxsMjEwaXlpYzhpOXAycWNyeWdrdCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/g01FpmEF642Onqf1nA/giphy.gif" alt="Cute Hug GIF"></div>
            </div>

            <div class="speech-box">
                Aapke sath bitaya har ek pal super special aur romantic raha hai! Aap meri zindagi ki sabse badi khushi ho Teena Ji. 💋✨
            </div>
            
            <button class="btn-cartoon" onclick="turn(2)">Next Page 🚀</button>
        </div>

        <!-- PAGE 3: SHAYARI -->
        <div class="page p3" id="p3">
            <div class="spine"></div>
            <span class="badge" style="background:#ffeaa7; color:#2d3436;">SHAYARI TIME 📜💖</span>
            
            <div class="gif-box" style="width: 95px; height: 95px;">
                <img src="https://media3.giphy.com/media/3o7abKhOpu0NwenH3O/giphy.gif" alt="Warm Hug GIF">
            </div>

            <div class="speech-box" style="font-size:0.88rem;">
                "Aapki muskurahat se chamakti hai meri har subah ☀️,<br>
                Aap sath ho toh har rasta lagta hai pyara 🛣️.<br>
                Yeh khoobsurat safar toh bas ek shuruat hai 🌱,<br>
                Aap hi toh ho Navu ka sabse pyara sahara! 🤗"<br>
                <span class="handwriting" style="display: block; margin-top: 4px;">— Navuddin</span>
            </div>
            
            <button class="btn-cartoon" onclick="turn(3)">Play Game 🎁</button>
        </div>

        <!-- PAGE 4: HEART CATCHER GAME -->
        <div class="page p4" id="p4">
            <div class="spine"></div>
            <span class="badge" style="background:#ff7675; color:#fff;">HEART CATCHER 🎮💖</span>
            
            <div style="width:100%;">
                <p style="font-weight:700; font-size:0.9rem; margin-bottom:6px;">Catch 10 Hearts! Score: <span id="score" style="color:#d63031; font-size:1.15rem;">0</span>/10</p>
                <div id="gameArea">
                    <button class="btn-cartoon" id="startBtn" onclick="startGame()" style="position:absolute; top:36%; left:20%; background:#ff7675; color:#fff;">Start Game! 🚀</button>
                </div>
            </div>
            
            <button class="btn-cartoon" onclick="turn(4)">Next Page ✨</button>
        </div>

        <!-- PAGE 5: PROMISE -->
        <div class="page p5" id="p5">
            <div class="spine"></div>
            <span class="badge" style="background:#74b9ff; color:#fff;">MY PROMISE 🤝👑</span>
            
            <div class="gif-box" style="width: 105px; height: 105px;">
                <img src="https://media2.giphy.com/media/L0SaMyy8w570P7gsia/giphy.gif" alt="Promise Couple GIF">
            </div>

            <div class="speech-box">
                Navu ka aap se waada hai ki main aapko hamesha aise hi khush rakhunga, aapki har baat sununga aur hamesha aapka sath dunga! 💏❤️
            </div>
            
            <button class="btn-cartoon" onclick="turn(5)">Final Surprise 🎉</button>
        </div>

        <!-- PAGE 6: FINAL PAGE -->
        <div class="page p6" id="p6">
            <div class="spine"></div>
            <span class="badge" style="background:#d63031; color:#fff;">FOREVER & ALWAYS ❤️👑</span>

            <div class="photo-frame" style="width: 110px; height: 110px;">
                <img src="https://i.ibb.co/ZzsZrk08/photo.jpg" alt="Teena & Navu" onerror="this.src='https://i.ibb.co/ZzsZrk08/image.jpg'">
            </div>

            <div>
                <h1 style="font-size: 1.65rem; color:#d63031; line-height: 1.7rem;">
                    I Love You Teena Ji! 😘
                </h1>
                <p style="font-weight: 700; font-size: 0.95rem; color:#2d3436; margin-top: 3px;">
                    Happy Anniversary! 🥳✨
                </p>
            </div>
            
            <div class="court-tag">
                ⚖️ MY SUPREME COURT ⚖️
            </div>
            
            <p style="font-weight: 700; color: #636e72; font-size: 0.9rem;">
                Hamesha ke liye aapka,<br>
                <span class="handwriting" style="font-size: 1.95rem; color: #2d3436;">Navuddin (Navu) 🧸❤️</span>
            </p>

            <button class="btn-cartoon" onclick="resetBook()" style="padding: 6px 18px; font-size: 0.82rem;">Reopen Book 🔄</button>
        </div>

    </div>

    <!-- NAVIGATION CONTROLS -->
    <div class="nav-bar">
        <button class="btn-cartoon" id="pBtn" onclick="prev()" style="display: none; background: rgba(255,255,255,0.95);">← Back</button>
        <button class="btn-cartoon" id="nBtn" onclick="next()" style="background: rgba(255,255,255,0.95);">Next →</button>
    </div>

    <script>
        var curr = 1;
        var max = 6;
        var score = 0;
        var gameInterval = null;
        var audioObj = document.getElementById('bgSong');
        var isPlaying = false;

        function autoPlayMusic(e) {
            if (!isPlaying && audioObj) {
                audioObj.play().then(function() {
                    isPlaying = true;
                }).catch(function(err) {});
            }
            createTapHeart(e);
        }

        /* Touch Particle Effect */
        function createTapHeart(e) {
            if (!e || !e.clientX) return;
            var heart = document.createElement('div');
            heart.innerHTML = ['💖', '✨', '🌸'][Math.floor(Math.random() * 3)];
            heart.style.position = 'fixed';
            heart.style.left = e.clientX + 'px';
            heart.style.top = e.clientY + 'px';
            heart.style.fontSize = '1.5rem';
            heart.style.pointerEvents = 'none';
            heart.style.zIndex = '10000';
            heart.style.transition = 'all 0.8s ease-out';
            document.body.appendChild(heart);

            setTimeout(function() {
                heart.style.transform = 'translateY(-55px) scale(1.3)';
                heart.style.opacity = '0';
            }, 20);

            setTimeout(function() { heart.remove(); }, 800);
        }

        function turn(i) {
            var el = document.getElementById('p' + i);
            if (el) {
                el.classList.add('flipped');
                curr = i + 1;
                checkState();
            }
        }

        function back(i) {
            var el = document.getElementById('p' + i);
            if (el) {
                el.classList.remove('flipped');
                curr = i;
                checkState();
            }
        }

        function next() {
            if (curr < max) turn(curr);
        }

        function prev() {
            if (curr > 1) back(curr - 1);
        }

        function resetBook() {
            for (var i = 5; i >= 1; i--) {
                var el = document.getElementById('p' + i);
                if (el) el.classList.remove('flipped');
            }
            curr = 1;
            checkState();
        }

        function checkState() {
            document.getElementById('pBtn').style.display = curr > 1 ? 'block' : 'none';
            document.getElementById('nBtn').style.display = curr < max ? 'block' : 'none';
            if (curr === max) triggerConfetti();
        }

        /* GAME LOGIC */
        function startGame() {
            score = 0;
            document.getElementById('score').innerText = score;
            document.getElementById('startBtn').style.display = 'none';
            if (gameInterval) clearInterval(gameInterval);

            gameInterval = setInterval(function() {
                if (score >= 10) {
                    clearInterval(gameInterval);
                    document.getElementById('gameArea').innerHTML = 
                        '<div style="padding-top:30px; color:#2d3436;">' +
                        '<h3 style="font-size:1.15rem; color:#d63031;">🎉 YOU WON TEENA JI! 🎉</h3>' +
                        '<p style="font-weight:700; margin-top:8px; font-size:0.95rem;">Navu Loves You 10000%! 💋✨</p>' +
                        '</div>';
                    triggerConfetti();
                    return;
                }
                spawnHeart();
            }, 550);
        }

        function spawnHeart() {
            var area = document.getElementById('gameArea');
            if (!area) return;
            var h = document.createElement('div');
            h.className = 'falling-heart';
            h.innerHTML = ['💖', '❤️', '💋', '🌸', '💘'][Math.floor(Math.random() * 5)];
            h.style.left = Math.random() * (area.clientWidth - 45) + 'px';
            h.onclick = function(e) {
                e.stopPropagation();
                score++;
                document.getElementById('score').innerText = score;
                h.remove();
            };
            area.appendChild(h);
            setTimeout(function() { if (h.parentNode) h.remove(); }, 2200);
        }

        /* CONFETTI ANIMATION */
        function triggerConfetti() {
            var canvas = document.getElementById('confettiCanvas');
            var ctx = canvas.getContext('2d');
            canvas.width = window.innerWidth;
            canvas.height = window.innerHeight;

            var p = [];
            for (var i = 0; i < 85; i++) {
                p.push({
                    x: Math.random() * canvas.width,
                    y: Math.random() * canvas.height - canvas.height,
                    size: Math.random() * 8 + 4,
                    color: ['#ff7675', '#fd79a8', '#74b9ff', '#55efc4', '#ffeaa7', '#a29bfe'][Math.floor(Math.random() * 6)],
                    speed: Math.random() * 4 + 2
                });
            }

            function draw() {
                ctx.clearRect(0, 0, canvas.width, canvas.height);
                p.forEach(function(item) {
                    ctx.beginPath();
                    ctx.arc(item.x, item.y, item.size, 0, Math.PI * 2);
                    ctx.fillStyle = item.color;
                    ctx.fill();
                    item.y += item.speed;
                    if (item.y > canvas.height) item.y = -10;
                });
                requestAnimationFrame(draw);
            }
            draw();
        }
    </script>
</body>
</html>
