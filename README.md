<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Healthy Lives</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: #121212;
            color: #f5f5f5;
        }

        header {
            background-color: rgba(0, 128, 0, 0.7);
            color: white;
            padding: 15px 20px;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #1e1e1e;
            padding: 10px 0;
        }

        nav a {
            color: #f5f5f5;
            text-decoration: none;
            padding: 10px 20px;
        }

        nav a:hover {
            background-color: #333;
        }

        main {
            padding: 20px;
            text-align: center;
        }

        footer {
            background-color: rgba(0, 128, 0, 0.7);
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .button {
            display: inline-block;
            padding: 10px 20px;
            margin: 10px;
            color: white;
            background-color: #4CAF50;
            border: none;
            border-radius: 5px;
            text-decoration: none;
            cursor: pointer;
        }

        .button:hover {
            background-color: #45a049;
        }

        .section-button {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Healthy Lives</h1>
        <p>Promoting Wellness and Healthy Living</p>
    </header>

    <nav>
        <a href="index.html">Home</a>
        <a href="nutrition.html">Nutrition</a>
        <a href="fitness.html">Fitness</a>
        <a href="mental_health.html">Mental Health</a>
        <a href="contact.html">Contact</a>
    </nav>

    <main>
        <h2>Welcome to Healthy Lives</h2>
        <p>Discover tips, resources, and guides to maintain a healthy lifestyle. Explore our sections on nutrition, fitness, and mental health.</p>
        <p>Healthy living is about making smart choices every day to improve physical, mental, and emotional well-being. Our goal is to provide you with the tools and inspiration you need to achieve your wellness goals.</p>
        <p>Start your journey towards a healthier, happier you by exploring our expertly curated articles and advice tailored to your needs.</p>

        <p>Maintaining a healthy life involves regular exercise, balanced nutrition, and sufficient rest. Learn how to balance these aspects to lead a fulfilled life.</p>
        <p>We provide insights on superfoods, workout regimes, and relaxation techniques to help you make the best choices for your health.</p>
        <p>Our mission is to inspire you with actionable tips and foster a community where wellness is a priority.</p>
        <p>Don't forget to explore our resources on mental health for a comprehensive approach to well-being.</p>
        <p>Contact us anytime for personalized advice or to share your wellness journey with us.</p>

        <div class="section-button">
            <button class="button" onclick="window.location.href='nutrition.html'">Learn About Nutrition</button>
            <button class="button" onclick="window.location.href='fitness.html'">Get Fitness Tips</button>
            <button class="button" onclick="window.location.href='mental_health.html'">Mental Health Resources</button>
            <button class="button" onclick="window.location.href='contact.html'">Contact Us</button>
        </div>
    </main>

    <footer>
        <p>&copy; 2025 Healthy Lives. All Rights Reserved.</p>
        <p>Follow us on social media: <a href="#" style="color: white; text-decoration: underline;">Facebook</a> | <a href="#" style="color: white; text-decoration: underline;">Twitter</a> | <a href="#" style="color: white; text-decoration: underline;">Instagram</a></p>
    </footer>
</body>
</html>

<!-- Contact Page -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact - Healthy Lives</title>
</head>
<body>
    <header>
        <h1>Contact Us</h1>
    </header>
    <main>
        <p>If you have any questions, feel free to reach out to us at <a href="mailto:info@healthylives.com">info@healthylives.com</a>.</p>
        <p>Contact us directly at: +91 7678199834</p>
        <p>Stay connected by following our social media channels or signing up for our newsletter.</p>
        <button class="button" onclick="window.location.href='nutrition.html'">Go to Nutrition</button>
        <button class="button" onclick="window.location.href='fitness.html'">Go to Fitness</button>
        <button class="button" onclick="window.location.href='mental_health.html'">Go to Mental Health</button>
        <button class="button" onclick="window.location.href='index.html'">Back to Home</button>
    </main>
</body>
</html>
