html, body {
    margin: 0; padding: 0; width: 100%; height: 100%;
    background: linear-gradient(to bottom, #050510 0%, #1a1a2e 100%);
    overflow: hidden;
    font-family: 'Hiragino Kaku Gothic ProN', sans-serif;
}

#game-container {
    width: 100%; height: 100%; position: relative; cursor: pointer;
}

/* UI */
#ui {
    position: absolute; top: 20px; left: 20px; color: white; z-index: 1000;
    pointer-events: none;
}
#clock { font-size: 32px; font-weight: bold; letter-spacing: 2px; }
#gauge-container {
    width: 220px; height: 14px; background: rgba(255,255,255,0.1);
    border: 2px solid white; margin-top: 10px; border-radius: 10px; overflow: hidden;
}
#gauge { width: 0%; height: 100%; background: #fff; box-shadow: 0 0 10px #fff; transition: 0.1s; }
.hint { font-size: 12px; margin-top: 8px; opacity: 0.8; }

/* ステージと建物 */
.stage {
    position: absolute; bottom: 40px; width: 100%; height: 400px;
    display: flex; justify-content: space-around; align-items: flex-end;
    z-index: 10;
}
.building { position: relative; background: #333; box-shadow: inset -10px 0 20px rgba(0,0,0,0.3); }
.windows { display: grid; padding: 40px 10px 10px; gap: 10px; }
.win { height: 15px; background: #fff176; opacity: 0.3; border-radius: 2px; }

/* 各建物の詳細 */
.school { width: 350px; height: 200px; background: #607d8b; }
.school-tag {
    position: absolute; top: 10px; width: 100%; text-align: center;
    color: #fff; font-weight: bold; font-size: 18px; text-shadow: 1px 1px 2px #000;
}
.school .windows { grid-template-columns: repeat(6, 1fr); }

.office { width: 90px; height: 320px; background: #263238; }
.office .windows { grid-template-columns: repeat(2, 1fr); gap: 15px; }

.house { width: 120px; height: 100px; background: #795548; }
.roof {
    position: absolute; top: -50px; left: 0; width: 120px; height: 50px;
    background: #5d4037; clip-path: polygon(50% 0%, 0% 100%, 100% 100%);
}
.house-windows { padding-top: 20px; grid-template-columns: repeat(2, 1fr); }
.door { width: 25px; height: 35px; background: #3e2723; position: absolute; bottom: 0; left: 20px; }

/* 雪の積雪表現 */
.roof-snow {
    position: absolute; bottom: 0; left: 0; width: 100%; background: #fff;
    height: 0%; transition: 0.3s;
}
.flat-roof-snow {
    position: absolute; bottom: 100%; left: 0; width: 100%;
    background: #fff; height: 0px; transition: 0.3s; border-radius: 5px 5px 0 0;
}
#ground-base {
    position: absolute; bottom: 0; width: 100%; height: 40px; background: #3e2723; z-index: 5;
}
#ground-snow {
    position: absolute; bottom: 0; width: 100%; background: #fff;
    height: 0px; z-index: 100; transition: 0.3s;
    box-shadow: 0 -8px 20px rgba(255,255,255,0.4);
}

/* 通知・リザルト */
#mail {
    position: absolute; top: -150px; left: 50%; transform: translateX(-50%);
    width: 90%; max-width: 420px; background: #fff; padding: 15px;
    border-radius: 15px; box-shadow: 0 10px 40px rgba(0,0,0,0.6);
    display: flex; align-items: center; z-index: 2000;
    transition: 0.6s cubic-bezier(0.175, 0.885, 0.32, 1.275);
}
#mail.active { top: 20px; }
.mail-icon { font-size: 35px; margin-right: 15px; }
.mail-content b { display: block; font-size: 16px; color: #333; }
.mail-content p { margin: 5px 0 0; font-size: 14px; color: #444; line-height: 1.4; }

#overlay {
    position: fixed; inset: 0; background: rgba(0,0,0,0.85);
    display: none; flex-direction: column; justify-content: center; align-items: center;
    color: white; z-index: 3000; text-align: center;
}
button {
    padding: 12px 30px; font-size: 18px; border-radius: 30px; border: none;
    background: #fff; color: #333; cursor: pointer; font-weight: bold; margin-top: 20px;
}

/* 降る雪の粒 */
.snowflake-particle {
    position: absolute; background: white; border-radius: 50%;
    pointer-events: none; z-index: 150;
}