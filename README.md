<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Stats</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        .stats-container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
            margin-bottom: 20px;
        }
        .stats-item {
            flex: 1 1 300px;
            max-width: 100%;
        }
        img {
            max-width: 100%;
            height: auto;
            display: block;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="stats-container">
            <div class="stats-item">
                <img src="https://github-readme-stats.vercel.app/api/top-langs?username=oleksii-dukhovenko&show_icons=true&locale=en&layout=compact" alt="Top Languages" />
            </div>
            <div class="stats-item">
                <img src="https://github-readme-stats.vercel.app/api?username=oleksii-dukhovenko&show_icons=true&locale=en" alt="GitHub Stats" />
            </div>
        </div>
        <div class="stats-container">
            <div class="stats-item">
                <img src="https://github-readme-streak-stats.herokuapp.com/?user=oleksii-dukhovenko&" alt="GitHub Streak" />
            </div>
        </div>
    </div>
</body>
</html>
