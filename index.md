---
layout: default
title: Student Blog
---

<html>
<head>
    <title>Geoguessr Game</title>
    <style>
        /* Add your CSS styles here */
    </style>
</head>
<body>
    <h1>Welcome to the Geoguessr Game</h1>
    <p id="location">Loading location...</p>
    <button onclick="getRandomLocation()">Get Random Location</button>

    <script>
        async function getRandomLocation() {
            const response = await fetch('YOUR_BACKEND_ENDPOINT_URL/random-location');
            const data = await response.json();
            const locationElement = document.getElementById('location');
            locationElement.innerText = `Location: ${data.name}, Latitude: ${data.latitude}, Longitude: ${data.longitude}`;
        }
    </script>
</body>
</html>
