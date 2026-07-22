# Money
<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minimalist Vocabulary</title>
    <style>
        body {
            background-color: #f7f7f8;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            color: #1a1a1a;
        }
        .card {
            background: #ffffff;
            width: 320px;
            padding: 40px 30px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.05);
            text-align: center;
            transition: transform 0.2s ease;
        }
        .card:hover {
            transform: translateY(-4px);
        }
        .tag {
            font-size: 12px;
            letter-spacing: 2px;
            color: #8e8e93;
            text-transform: uppercase;
            margin-bottom: 20px;
        }
        .word {
            font-size: 36px;
            font-weight: 700;
            margin: 0 0 8px 0;
            letter-spacing: -0.5px;
        }
        .phonetic {
            font-size: 16px;
            color: #8e8e93;
            margin-bottom: 24px;
        }
        .definition {
            font-size: 18px;
            font-weight: 600;
            color: #2c2c2e;
            padding: 12px 0;
            border-top: 1px solid #f0f0f2;
            border-bottom: 1px solid #f0f0f2;
            margin-bottom: 24px;
        }
        .example-en {
            font-size: 14px;
            line-height: 1.5;
            color: #3a3a3c;
            margin-bottom: 8px;
            font-style: italic;
        }
        .example-zh {
            font-size: 13px;
            color: #8e8e93;
        }
    </style>
</head>
<body>

    <div class="card">
        <div class="tag">IELTS / 學測必考</div>
        <div class="word" id="word">Abandon</div>
        <div class="phonetic" id="phonetic">/əˈbæn.dən/</div>
        <div class="definition" id="definition">放棄；拋棄</div>
        <div class="example-en" id="example_en">"Never abandon your dreams, no matter how tough the journey gets."</div>
        <div class="example-zh" id="example_zh">即使旅途再艱難，也絕不放棄你的夢想。</div>
    </div>

</body>
</html>
