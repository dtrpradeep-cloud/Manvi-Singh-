<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>MANVI SINGH | VIP CRICKET PREDICTIONS</title>
    <link href="https://fonts.googleapis.com/css2?family=Syncopate:wght@700&family=Outfit:wght@300;600;900&display=swap" rel="stylesheet">
    <style>
        :root { --gold: linear-gradient(135deg, #FFD700 0%, #B8860B 100%); --neon-green: #00FF88; --bg-dark: #050505; }
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { background-color: var(--bg-dark); color: #fff; font-family: 'Outfit', sans-serif; display: flex; justify-content: center; align-items: center; min-height: 100vh; background: radial-gradient(circle at top right, #1a3a1a 0%, #050505 50%), radial-gradient(circle at bottom left, #1a1a00 0%, #050505 50%); }
        .main-card { width: 92%; max-width: 420px; background: rgba(255, 255, 255, 0.02); backdrop-filter: blur(30px); border: 1px solid rgba(255, 215, 0, 0.2); border-radius: 50px; padding: 50px 20px; text-align: center; box-shadow: 0 50px 100px rgba(0,0,0,1); position: relative; overflow: hidden; }
        .live-notif { position: absolute; top: 20px; left: 50%; transform: translateX(-50%); background: rgba(255, 255, 255, 0.1); padding: 5px 15px; border-radius: 50px; font-size: 0.65rem; border: 1px solid rgba(0, 255, 136, 0.3); color: var(--neon-green); white-space: nowrap; }
        .profile-img { width: 140px; height: 140px; border-radius: 50%; border: 4px solid #FFD700; padding: 6px; background: #000; box-shadow: 0 0 40px rgba(255, 215, 0, 0.3); margin-bottom: 20px; }
        h1 { font-family: 'Syncopate', sans-serif; font-size: 1.5rem; letter-spacing: 3px; margin-bottom: 5px; background: var(--gold); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
        .headline { font-size: 1.3rem; font-weight: 900; margin-bottom: 10px; color: #fff; }
        .sub-headline { font-size: 0.85rem; color: #aaa; margin-bottom: 25px; line-height: 1.5; }
        .counter-box { background: rgba(255, 255, 255, 0.05); margin-bottom: 25px; padding: 15px; border-radius: 25px; border: 1px dashed #FFD700; }
        .counter-box p { font-size: 0.65rem; color: #FFD700; text-transform: uppercase; margin-bottom: 5px; font-weight: 800; }
        .vvip-btn { display: flex; align-items: center; justify-content: center; padding: 22px; background: var(--gold); color: #000; text-decoration: none; border-radius: 25px; font-weight: 900; font-size: 1.2rem; box-shadow: 0 20px 50px rgba(255, 215, 0, 0.4); animation: pulse 1.8s infinite ease-in-out; }
        @keyframes pulse { 0%, 100% { transform: scale(1); } 50% { transform: scale(1.04); } }
        .feature-item { display: flex; align-items: center; gap: 8px; margin-bottom: 8px; font-size: 0.8rem; color: #ccc; justify-content: center; }
        .check { color: var(--neon-green); }
    </style>
</head>
<body>
    <div class="main-card">
        <div class="live-notif">⚡ MATCH REPORT IS LIVE NOW!</div>
        <img src="https://i.ibb.co/LDvrWxYH/IMG-20260318-235941-002.jpg" class="profile-img" alt="Manvi Singh">
        <h1>MANVI SINGH</h1>
        <div class="headline">RECOVER ALL YOUR LOSS 🏆</div>
        <p class="sub-headline">India's most accurate cricket forecaster. <br><b>95% Accuracy directly from Ground.</b></p>
        <div class="counter-box">
            <p>TODAY'S TOTAL PROFIT</p>
            <span style="font-size: 1.5rem; font-weight: 900;">₹<span id="profit">52,400</span>+</span>
        </div>
        <a href="https://t.me/+wJEWoUQtM_9jMGM1" class="vvip-btn">JOIN VVIP TELEGRAM</a>
        <div style="margin-top: 25px;">
            <div class="feature-item"><span class="check">✓</span> Back-to-Back Jackpot Pass</div>
            <div class="feature-item"><span class="check">✓</span> Daily Free Open Tips</div>
        </div>
    </div>
    <script>
        let count = 52400;
        setInterval(() => { count += Math.floor(Math.random() * 400); document.getElementById('profit').innerText = count.toLocaleString(); }, 3000);
    </script>
</body>
</html>
