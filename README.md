# Amazon-clone
Code of Amazon in HTML CSS AND JS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazon Clone</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #232f3e;
            color: white;
            padding: 10px;
            text-align: center;
        }

        nav {
            background-color: #131921;
            color: white;
            padding: 10px;
            text-align: center;
        }

        section {
            padding: 20px;
        }

        .product {
            border: 1px solid #ddd;
            padding: 10px;
            margin: 10px;
            text-align: center;
            display: inline-block;
        }
    </style>
</head>
<body>
    <header>
        <h1>Amazon Clone</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">Shop</a>
        <a href="#">Contact</a>
    </nav>

    <section>
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Product Image">
            <h2>Product Name</h2>
            <p>Description of the product.</p>
            <p>20rs</p>
            <button>Add to Cart</button>
        </div>

        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Product Image">
            <h2>Another Product</h2>
            <p>Description of another product.</p>
            <p>30rs</p>
            <button>Add to Cart</button>
        </div>
    </section>

    <footer>
        <p>&copy; 2023 Amazon Clone</p>
    </footer>

    <script>
        // You can add JavaScript code for additional functionality here
    </script>
</body>
</html>
