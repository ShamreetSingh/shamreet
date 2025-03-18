DESCRIPTION-
Kissan - A One-Stop Solution for Farmers
Kissan is a dedicated online marketplace designed specifically for farmers, providing them with easy access to high-quality agricultural products. Whether you are looking for seeds, flowers, farming tools, pesticides, or insecticides, Kissan has everything you need to boost your farm’s productivity.
What We Offer:
Seeds & Plants – High-yield seeds and a variety of flowers to enhance your farming.
Farming Tools & Equipment – Essential tools for efficient farming operations.
Pesticides & Insecticides – Protect your crops from pests and diseases.
Fertilizers & Soil Enhancers – Boost soil health for better growth.
Expert Tips & Community – Get insights, guidance, and support from fellow farmers.
With a user-friendly interface, competitive prices, and reliable delivery, Kissan is here to support farmers at every step of their journey.
Grow More, Earn More – With Kissan!

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KISSAN Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        nav {
            background-color: #333;
            padding: 15px;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 18px;
        }
        h1 {
            color: #3498db;
        }
        .slider {
            width: 80%;
            margin: auto;
            overflow: hidden;
            position: relative;
            height: 100px;
        }
        .slides {
            display: flex;
            transition: transform 0.5s ease-in-out;
        }
        .slide {
            min-width: 100%;
            font-size: 30px;
            font-weight: bold;
            color: white;
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100px;
            border-radius: 10px;
        }
        .slide:nth-child(1) { background-color: #ff7f7f; }
        .slide:nth-child(2) { background-color: #77ff77; }
        .slide:nth-child(3) { background-color: #7f7fff; }
        .btn {
            background-color: #2ecc71;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            font-size: 18px;
            margin-top: 20px;
        }
        .btn:hover {
            background-color: #27ae60;
        }
        footer {
            background-color: #333;
            color: white;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Services</a>
        <a href="#">Contact</a>
    </nav>
    
    <h1>Welcome to KISSAN🚀</h1>
    
    <div class="slider">
        <div class="slides">
            <div class="slide">Vegetable Seeds</div>
            <div class="slide">Flower Seeds</div>
            <div class="slide">Pesticides</div>
        </div>
    </div>
    
    <button class="btn">Click Me!</button>
    
    <footer>
        &copy; 2025 KISSAN. All rights reserved.
    </footer>

    <script>
        let index = 0;
        function showSlides() {
            const slides = document.querySelector(".slides");
            index++;
            if (index >= slides.children.length) {
                index = 0;
            }
            slides.style.transform = `translateX(-${index * 100}%)`;
        }
        setInterval(showSlides, 3000);
    </script>
</body>
</html>



Names of all teammates-
Krishna Nautiyal,
Shamreet Singh,
Soanam Norphel Negi,
Saksham,
Shivam
