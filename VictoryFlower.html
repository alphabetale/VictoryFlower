<!DOCTYPE html>
<html lang="zh">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>抗战胜利花</title>
  <style>
    body {
      margin: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background: #fffaf0;
      position: relative;
      font-family: sans-serif;
    }
    canvas {
      display: block;
    }
    #qrcode {
      position: absolute;
      right: 20px;
      bottom: 20px;
      padding: 8px;
      background: white;
      border: 1px solid #ccc;
      border-radius: 8px;
    }
    #qrcode p {
      margin: 0;
      font-size: 12px;
      text-align: center;
    }
  </style>
</head>
<body>
  <canvas id="flower" width="300" height="300"></canvas>
  <div id="qrcode"></div>

  <!-- 引入二维码生成库 -->
  <script src="https://cdn.jsdelivr.net/npm/qrcodejs@1.0.0/qrcode.min.js"></script>
  <script>
    const canvas = document.getElementById("flower");
    const ctx = canvas.getContext("2d");
    const w = canvas.width;
    const h = canvas.height;
    const cx = w / 2;
    const cy = h / 2;
    let angle = 0;

    const petalCount = 4;
    const petalRadius = 80;

    function drawStar(x, y, r, n, inset) {
      ctx.beginPath();
      ctx.save();
      ctx.translate(x, y);
      ctx.moveTo(0, 0 - r);
      for (let i = 0; i < n; i++) {
        ctx.rotate(Math.PI / n);
        ctx.lineTo(0, 0 - r * inset);
        ctx.rotate(Math.PI / n);
        ctx.lineTo(0, 0 - r);
      }
      ctx.closePath();
      ctx.fillStyle = "#ffd700"; // 金黄色
      ctx.fill();
      ctx.restore();
    }

    function render() {
      ctx.clearRect(0, 0, w, h);

      ctx.save();
      ctx.translate(cx, cy);
      ctx.rotate(angle);

      // 花瓣
      for (let i = 0; i < petalCount; i++) {
        const a = (i * Math.PI * 2) / petalCount;
        ctx.save();
        ctx.rotate(a);
        ctx.beginPath();
        ctx.moveTo(0, 0);
        ctx.bezierCurveTo(
          petalRadius, -petalRadius / 2,
          petalRadius, petalRadius / 2,
          0, petalRadius
        );
        ctx.closePath();
        ctx.fillStyle = "#e63946"; // 红色花瓣
        ctx.fill();
        ctx.restore();
      }

      ctx.restore();

      // 中间五角星
      drawStar(cx, cy, 30, 5, 0.5);

      angle += 0.01;
      requestAnimationFrame(render);
    }

    render();

    // 生成二维码（默认指向当前页面 URL）
    const url = window.location.href;
    new QRCode(document.getElementById("qrcode"), {
      text: url,
      width: 100,
      height: 100,
    });
  </script>
</body>
</html>
