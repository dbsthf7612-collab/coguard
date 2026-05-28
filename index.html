<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CoGuard 실시간 모니터</title>
  <script src="https://www.gstatic.com/firebasejs/9.x.x/firebase-app-compat.js"></script>
  <script src="https://www.gstatic.com/firebasejs/9.x.x/firebase-database-compat.js"></script>
  <style>
    /* 기존 CoGuard 스타일 그대로 */
    body { font-family: sans-serif; text-align: center; padding: 20px; }
    .good { background: #e8f5e9; }
    .caution { background: #fff3e0; }
    .danger { background: #ffebee; }
    .value { font-size: 3rem; font-weight: bold; }
  </style>
</head>
<body>
  <h1>코가드 CoGuard</h1>
  <p id="updated">로딩 중...</p>
  <div id="co-box"><span class="value" id="co">--</span> ppm (CO)</div>
  <div id="co2-box"><span class="value" id="co2">--</span> ppm (CO₂)</div>
  <div><span id="temp">--</span>°C / <span id="hum">--</span>%</div>

  <script>
    const firebaseConfig = {
      databaseURL: "https://coguard-xxxxx-default-rtdb.firebaseio.com"
      // ↑ 본인 URL로 교체
    };
    firebase.initializeApp(firebaseConfig);
    const db = firebase.database();

    db.ref("/coguard").on("value", (snap) => {
      const d = snap.val();
      if (!d) return;
      
      document.getElementById("co").textContent = d.co?.toFixed(1) ?? "--";
      document.getElementById("co2").textContent = d.co2 ?? "--";
      document.getElementById("temp").textContent = d.temp?.toFixed(1) ?? "--";
      document.getElementById("hum").textContent = d.humidity ?? "--";
      document.getElementById("updated").textContent = "최근 업데이트: " + new Date().toLocaleTimeString();
      
      // 상태에 따라 배경색 변경
      const status = d.status;
      document.body.className = status; // good / caution / danger
    });
  </script>
</body>
</html>d
