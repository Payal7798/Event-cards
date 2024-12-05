<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Event Cards</title>
    <link rel="stylesheet" href="styles.css">
<style>
 body {
    font-family: Arial, sans-serif;
    background-color: #121212;
    color: white;
    margin: 0;
    padding: 0;
}

.event-card-container {
    display: flex;
    justify-content: center;
    gap: 20px;
    padding: 20px;
}

.event-card {
    background-color: #1e1e1e;
    border-radius: 8px;
    text-align: center;
    transition: transform 0.2s ease-in-out;
}




.event-card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.event-card h3 {
    font-size: 1.5em;
    margin: 15px 0;
    color: #00bcd4;
}

.event-card p {
    padding: 0 15px 15px;
    font-size: 0.9em;
    color: #b0b0b0;
}

.buttons {
    display: flex;
    justify-content: space-around;
    padding: 10px;
}

.btn {
     background-color: #00bcd4;
    color: white;
    padding: 10px 20px;
    border-radius: 5px;
    transition: background-color 0.3s ease;
}

.btn:hover {
    background-color: #0097a7;
}
</style>
</head>
<body>
    <div class="event-card-container">
        <div class="event-card">
            <img src="path_blazer.jpg" alt="Path Blazer">
            <h3>PATH BLAZER</h3>
            <p>Encounter the realm of 'Path Blazer'. A RoboRace competition...</p>
            <div class="buttons">
                <a href="#" class="btn">Rule Book</a>
                <a href="#" class="btn">Register</a>
            </div>
        </div>
        
        <div class="event-card">
            <img src="dread_showdown.jpg" alt="Dread Showdown">
            <h3>DREAD SHOWDOWN</h3>
            <p>Test your strength in this intense robotic showdown...</p>
            <div class="buttons">
                <a href="#" class="btn">Rule Book</a>
                <a href="#" class="btn">Register</a>
            </div>
        </div>

        <!-- Add more event cards here -->

    </div>
</body>
</html>

