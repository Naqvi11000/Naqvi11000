<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Personal Website</title>
    <style>
        /* Basic styling */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f2f2f2;
            color: #333;
        }

        header {
            background-color: #cc0000;
            color: white;
            padding: 20px;
            text-align: center;
        }

        .container {
            max-width: 800px;
            margin: auto;
            padding: 20px;
        }

        h1,
        h2,
        h3 {
            color: #cc0000;
        }

        p {
            margin-bottom: 20px;
        }

        /* Product grid */
        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .product {
            background-color: white;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .product h3 {
            margin-top: 0;
        }

        /* Footer */
        footer {
            background-color: #cc0000;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>

<body>
    <header>
        <h1>Your Name</h1>
        <p>Sales Executive</p>
    </header>

    <div class="container">
        <section>
            <h2>About Me</h2>
            <p>Hi, I'm [Your Name], a passionate sales executive with expertise in technology products such as laptops, desktops, toner cartridges, HDMI cables, and security cameras. With years of experience in the industry, I strive to provide the best solutions to meet your needs.</p>
        </section>

        <section>
            <h2>Products</h2>
            <div class="product-grid">
                <!-- Product 1 -->
                <div class="product">
                    <h3>Laptops</h3>
                    <p>Description: [Add laptop description here]</p>
                </div>
                <!-- Product 2 -->
                <div class="product">
                    <h3>Desktops</h3>
                    <p>Description: [Add desktop description here]</p>
                </div>
                <!-- Product 3 -->
                <div class="product">
                    <h3>Toner Cartridges</h3>
                    <p>Description: [Add toner cartridge description here]</p>
                </div>
                <!-- Product 4 -->
                <div class="product">
                    <h3>HDMI Cables</h3>
                    <p>Description: [Add HDMI cable description here]</p>
                </div>
                <!-- Product 5 -->
                <div class="product">
                    <h3>Security Cameras</h3>
                    <p>Description: [Add security camera description here]</p>
                </div>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Your Name. All rights reserved.</p>
    </footer>
</body>

</html>
