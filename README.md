<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Weather App</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Weather App</h1>
        <div class="weather-search">
            <input type="text" id="city" placeholder="Enter city name">
            <button id="searchBtn">Search</button>
        </div>
        <div class="weather-info">
            <h2 id="cityName"></h2>
            <p id="temperature"></p>
            <p id="description"></p>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
