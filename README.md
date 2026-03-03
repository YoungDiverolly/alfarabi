<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Study Kingdom</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
<style>

body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background: linear-gradient(135deg, #1a1a2e, #16213e);
    color: white;
}

header {
    background: linear-gradient(90deg, #6a00ff, #b300ff);
    padding: 15px;
    text-align: center;
    font-size: 24px;
    font-weight: 600;
}

.telegram-btn {
    display: inline-block;
    margin-top: 10px;
    padding: 8px 20px;
    background: gold;
    color: black;
    border-radius: 20px;
    text-decoration: none;
    font-weight: 600;
}

.container {
    max-width: 1000px;
    margin: auto;
    padding: 20px;
}

.card {
    background: rgba(255,255,255,0.05);
    padding: 20px;
    border-radius: 20px;
    margin-bottom: 20px;
    backdrop-filter: blur(10px);
}

.progress-bar {
    background: #333;
    border-radius: 20px;
    overflow: hidden;
    height: 20px;
}

.progress {
    height: 100%;
    width: 40%;
    background: linear-gradient(90deg, gold, orange);
}

.shop-item {
    background: rgba(255,255,255,0.08);
    padding: 15px;
    border-radius: 15px;
    margin: 10px 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

button {
    background: gold;
    border: none;
    padding: 8px 15px;
    border-radius: 15px;
    font-weight: 600;
    cursor: pointer;
}

button:hover {
    opacity: 0.8;
}

</style>
</head>
<body>

<header>
    👑 Study Kingdom
    <br>
    <a class="telegram-btn" href="https://t.me/study_kingdomBOT" target="_blank">
        📲 Наш Telegram бот
    </a>
</header>

<div class="container">

    <div class="card">
        <h2>👤 Профиль</h2>
        <p><b>Имя:</b> Student_01</p>
        <p><b>Роль:</b> Ученик</p>
        <p><b>Уровень:</b> 3</p>
        <p><b>XP:</b> 240 / 500</p>
        <p><b>🔥 Стрик:</b> 5 дней</p>

        <div class="progress-bar">
            <div class="progress"></div>
        </div>
    </div>

    <div class="card">
        <h2>📚 Задания</h2>
        <p>Математика (Easy) — +50 XP</p>
        <button onclick="alert('Задание выполнено! +50 XP')">Выполнить</button>
    </div>

    <div class="card">
        <h2>🛒 Магазин</h2>

        <div class="shop-item">
            🎨 Кастомный аватар — 200 XP
            <button>Купить</button>
        </div>

        <div class="shop-item">
            📐 Калькулятор PRO — 300 XP
            <button>Купить</button>
        </div>

        <div class="shop-item">
            💎 Буст XP — 150 XP
            <button>Купить</button>
        </div>

    </div>

</div>

</body>
</html>
