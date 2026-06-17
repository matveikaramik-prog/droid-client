<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Droid Client - Oxide Client</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #1a1a2e 0%, #16213e 100%);
            color: #e0e0e0;
            line-height: 1.6;
        }

        header {
            background: rgba(0, 0, 0, 0.8);
            padding: 20px;
            text-align: center;
            border-bottom: 3px solid #00ff88;
        }

        header h1 {
            font-size: 3em;
            color: #00ff88;
            text-shadow: 0 0 20px #00ff88;
            letter-spacing: 2px;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.2em;
            color: #00ccff;
        }

        .container {
            max-width: 900px;
            margin: 40px auto;
            padding: 0 20px;
        }

        .hero {
            background: rgba(0, 255, 136, 0.1);
            border: 2px solid #00ff88;
            border-radius: 10px;
            padding: 40px;
            margin-bottom: 40px;
            text-align: center;
        }

        .hero h2 {
            font-size: 2.2em;
            color: #00ff88;
            margin-bottom: 20px;
            text-shadow: 0 0 10px #00ff88;
        }

        .hero p {
            font-size: 1.1em;
            color: #e0e0e0;
            line-height: 1.8;
        }

        .features {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin: 40px 0;
        }

        .feature-box {
            background: rgba(0, 204, 255, 0.1);
            border: 2px solid #00ccff;
            border-radius: 8px;
            padding: 20px;
        }

        .feature-box h3 {
            color: #00ff88;
            margin-bottom: 10px;
            font-size: 1.3em;
        }

        .feature-box p {
            color: #e0e0e0;
        }

        .warning {
            background: rgba(255, 100, 0, 0.1);
            border: 2px solid #ff6400;
            border-radius: 8px;
            padding: 20px;
            margin: 30px 0;
            text-align: center;
        }

        .warning h3 {
            color: #ff6400;
            margin-bottom: 10px;
            font-size: 1.3em;
        }

        .warning p {
            color: #e0e0e0;
            font-size: 1.1em;
        }

        .contacts {
            background: rgba(0, 0, 0, 0.8);
            border: 2px solid #00ff88;
            border-radius: 10px;
            padding: 40px;
            text-align: center;
            margin-top: 40px;
        }

        .contacts h2 {
            color: #00ff88;
            margin-bottom: 30px;
            font-size: 2em;
            text-shadow: 0 0 10px #00ff88;
        }

        .contact-link {
            display: inline-block;
            background: #00ff88;
            color: #1a1a2e;
            padding: 15px 40px;
            border-radius: 8px;
            text-decoration: none;
            font-size: 1.2em;
            font-weight: bold;
            margin: 10px;
            transition: all 0.3s ease;
            box-shadow: 0 0 20px #00ff88;
        }

        .contact-link:hover {
            background: #00ccff;
            box-shadow: 0 0 30px #00ccff;
            transform: scale(1.05);
        }

        footer {
            text-align: center;
            padding: 20px;
            background: rgba(0, 0, 0, 0.8);
            border-top: 2px solid #00ff88;
            margin-top: 40px;
            color: #00ff88;
        }

        @media (max-width: 600px) {
            header h1 {
                font-size: 2em;
            }

            .hero h2 {
                font-size: 1.5em;
            }

            .features {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>🎮 DROID CLIENT 🎮</h1>
        <p>Oxide - Профессиональный клиент для игроков</p>
    </header>

    <div class="container">
        <div class="hero">
            <h2>Плохой аим?</h2>
            <p>Если ты играешь в Oxide и ничего не получается, если твой аим оставляет желать лучшего, если враги всегда быстрее — <strong style="color: #00ff88;">Droid Client</strong> — это простое решение твоей проблемы!</p>
        </div>

        <div class="features">
            <div class="feature-box">
                <h3>⚡ Производительность</h3>
                <p>Оптимизированный клиент для максимальной скорости и отзывчивости</p>
            </div>
            <div class="feature-box">
                <h3>🎯 Точность</h3>
                <p>Улучшенные механики управления для лучшего контроля в боях</p>
            </div>
            <div class="feature-box">
                <h3>🛡️ Безопасность</h3>
                <p>Надежная защита и стабильная работа в любых условиях</p>
            </div>
            <div class="feature-box">
                <h3>⚙️ Кастомизация</h3>
                <p>Настройка всех параметров под твой стиль игры</p>
            </div>
        </div>

        <div class="warning">
            <h3>⚠️ ВАЖНО!</h3>
            <p>Droid Client — это программа исключительно для ПК (Windows)</p>
        </div>

        <div class="contacts">
            <h2>📞 КОНТАКТЫ</h2>
            <p style="margin-bottom: 20px;">Подпишись на наш Телеграмм канал для новостей и обновлений</p>
            <a href="https://t.me/DroidClient" class="contact-link" target="_blank">📱 Телеграмм Канал</a>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 Droid Client. Все права защищены.</p>
    </footer>
</body>
</html>
