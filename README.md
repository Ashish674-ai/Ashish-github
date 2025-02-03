<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ashish Logical Adviser</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Ashish Logical Adviser</h1>
            <p>Your guide to making logical and impactful decisions</p>
        </div>
    </header>

    <section class="advice-section">
        <div class="container">
            <h2>Daily Impactful Advice</h2>
            <div class="advice-card">
                <p>"Success is not final, failure is not fatal: It is the courage to continue that counts." – Winston Churchill</p>
            </div>
            <div class="advice-card">
                <p>"The only way to do great work is to love what you do." – Steve Jobs</p>
            </div>
            <div class="advice-card">
                <p>"In the middle of every difficulty lies opportunity." – Albert Einstein</p>
            </div>
            <div class="advice-card">
                <p>"The best time to plant a tree was 20 years ago. The second best time is now." – Chinese Proverb</p>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2023 Ashish Logical Adviser. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

.container {
    width: 80%;
    margin: 0 auto;
    padding: 20px;
}

/* Header Styles */
header {
    background-color: #4CAF50;
    color: white;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 2.5em;
}

header p {
    margin: 5px 0 0;
    font-size: 1.2em;
}

/* Advice Section Styles */
.advice-section {
    padding: 40px 0;
}

.advice-section h2 {
    text-align: center;
    font-size: 2em;
    margin-bottom: 20px;
}

.advice-card {
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    padding: 20px;
    margin: 20px 0;
    transition: transform 0.3s ease;
}

.advice-card:hover {
    transform: translateY(-5px);
}

.advice-card p {
    font-size: 1.1em;
    line-height: 1.6;
    margin: 0;
}

/* Footer Styles */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}

footer p {
    margin: 0;
    font-size: 0.9em;
}
