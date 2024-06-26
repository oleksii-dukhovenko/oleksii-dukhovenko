<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Profile</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Noto Sans', Helvetica, Arial, sans-serif;
            background-color: #0d1117;
            color: #c9d1d9;
            line-height: 1.5;
            padding: 20px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
        }
        .stats-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            gap: 20px;
            margin-bottom: 20px;
        }
        .stats-item {
            flex: 1;
            min-width: 300px;
        }
        img {
            max-width: 100%;
            height: auto;
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
        <div>
            <img src="https://github-readme-streak-stats.herokuapp.com/?user=oleksii-dukhovenko&" alt="GitHub Streak" />
        </div>
    </div>
</body>
</html>
