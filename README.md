# B-S-servises-<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>B&S Services</title>
    <style>
        /* Global Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
        }

        nav {
            background-color: #444;
            color: #fff;
            text-align: center;
            padding: 10px;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav li {
            display: inline;
            margin-right: 20px;
        }

        nav a {
            text-decoration: none;
            color: #fff;
            font-weight: bold;
        }

        nav a:hover {
            color: #ff5733;
        }

        .content {
            padding: 20px;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
        }

        /* Dropdown Menu Styles */
        .dropdown {
            position: relative;
            display: inline-block;
        }

        .dropdown-content {
            display: none;
            position: absolute;
            background-color: #444;
            min-width: 160px;
            z-index: 1;
        }

        .dropdown:hover .dropdown-content {
            display: block;
        }

        /* Text Box Styles */
        .textbox {
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>B&S Services</h1>
    </header>
    <nav>
        <ul>
            <li class="dropdown">
                <a href="#">Our Options & Pricing</a>
                <div class="dropdown-content">
                    <a href="#">Pricing</a>
                    <a href="#">Cleaning Options</a>
                </div>
            </li>
        </ul>
    </nav>
    <div class="content">
        <div class="textbox">
            <h2>Our Story</h2>
            <p>We are two teenagers that have had a dream to own our own business with the intentions to deliver high quality work to our customers.</p>
        </div>
    </div>
    <footer>
        &copy; 2023 B&S Services
    </footer>
</body>
</html>
