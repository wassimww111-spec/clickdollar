<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ClickDollar - كليك دولار</title>
    <style>
        body { font-family: Tahoma, sans-serif; text-align: center; background: #f4f7f6; margin-top: 50px; }
        .box { background: white; padding: 30px; border-radius: 10px; display: inline-block; box-shadow: 0 4px 10px rgba(0,0,0,0.1); }
        button { background: #28a745; color: white; border: none; padding: 15px 30px; font-size: 18px; border-radius: 5px; cursor: pointer; margin-top: 20px; }
        button:active { background: #218838; }
        h1 { color: #333; }
        p { font-size: 20px; color: #555; }
    </style>
</head>
<body>
    <div class="box">
        <h1>مرحباً بك في كليك دولار</h1>
        <p>الرصيد: <span id="score">0</span> $</p>
        <button onclick="addMoney()">اضغط هنا للربح!</button>
    </div>

    <script>
        let score = 0;
        function addMoney() {
            score += 1;
            document.getElementById('score').innerText = score;
        }
    </script>
</body>
</html>
