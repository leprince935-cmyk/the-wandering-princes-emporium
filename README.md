# the-wandering-princes-emporium
The official storefront for the Wandering Prince's Emporium. Here you will find enchanting interactive e-books and magical adventures for young wanderers, all based on the Wandering Prince series.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Inter:wght@400;500&display=swap" rel="stylesheet">
    <title>The Wandering Prince's Emporium</title>
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background: linear-gradient(135deg, #1d0033 0%, #3a0050 100%);
            color: #d8c3ff;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 2rem;
        }
        .container {
            max-width: 900px;
            width: 100%;
            background: rgba(43, 0, 70, 0.6);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            padding: 2.5rem;
            border: 2px solid rgba(255, 255, 255, 0.1);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.4);
            animation: fadeIn 1s ease-in-out;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .header {
            text-align: center;
            margin-bottom: 2rem;
        }
        .brand-title {
            font-family: 'Playfair Display', serif;
            font-size: 3.5rem;
            font-weight: 700;
            color: #ffcc00;
            text-shadow: 0 0 15px rgba(255, 204, 0, 0.8);
            margin-bottom: 0.5rem;
            animation: pulse 2s infinite ease-in-out;
        }
        @keyframes pulse {
            0%, 100% { text-shadow: 0 0 10px rgba(255, 204, 0, 0.6); }
            50% { text-shadow: 0 0 25px rgba(255, 204, 0, 1); }
        }
        .brand-subtitle {
            font-size: 1.125rem;
            color: #b898d9;
            font-style: italic;
        }
        .book-section {
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
            margin-bottom: 2rem;
        }
        .book-cover {
            width: 100%;
            max-width: 300px;
            height: auto;
            border-radius: 12px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            margin-bottom: 1.5rem;
            border: 2px solid #ffcc00;
        }
        .book-cover:hover {
            transform: translateY(-5px) scale(1.02);
            box-shadow: 0 12px 25px rgba(0, 0, 0, 0.5);
        }
        .book-title {
            font-size: 2rem;
            font-weight: 700;
            color: #ffcc00;
            margin-bottom: 0.5rem;
        }
        .book-subtitle {
            font-size: 1rem;
            color: #b898d9;
            font-style: italic;
            margin-bottom: 1rem;
        }
        .buy-button {
            background-color: #ffcc00;
            color: #3a0050;
            font-weight: 700;
            padding: 0.75rem 2rem;
            border-radius: 9999px;
            transition: all 0.3s ease;
            box-shadow: 0 5px 15px rgba(255, 204, 0, 0.3);
            text-decoration: none;
            display: inline-block;
        }
        .buy-button:hover {
            background-color: #ffd633;
            transform: translateY(-2px) scale(1.05);
            box-shadow: 0 8px 20px rgba(255, 204, 0, 0.5);
        }
        .footer {
            text-align: center;
            margin-top: 2rem;
            font-size: 0.875rem;
            color: #b898d9;
        }
    </style>
</head>
<body>
<!-- This is the storefront for The Wandering Prince's Emporium, a publishing company for children's books. -->
    <div class="container">
        <div class="header">
            <h1 class="brand-title">The Wandering Prince's Emporium</h1>
            <p class="brand-subtitle">Curiosity, Enchantment, and Whimsy in Every Tale</p>
        </div>

        <div class="book-section">
            <img src="https://placehold.co/300x450/3a0050/ffcc00?text=The+Wandering+Prince%0AChronicles" alt="Book Cover" class="book-cover">
            <h2 class="book-title">The Halloween Heist</h2>
            <p class="book-subtitle">A Wandering Prince's Adventure</p>
            <p class="text-center text-lg mb-4">
                Join Prince Peregrine on his very first adventure!
                When a mischievous creature steals all the Halloween candy, it's up to him and his new friends to save the day.
                This is a story about friendship, teamwork, and finding your place in the world.
            </p>
            <!-- The link below is the URL for the interactive story file. -->
            <a href="the-halloween-heist/en-6-8/index.html" class="buy-button">BUY NOW</a>
        </div>
        
        <div class="footer">
            &copy; 2024 Wandering Crown Press. All rights reserved.
        </div>
    </div>
</body>
</html>
