<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page 1</title>
    <style>
        /* Reusing the same simple CSS from index.html for consistency */
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            overflow: hidden;
            background-color: #333;
        }
        nav li {
            float: left;
        }
        nav li a {
            display: block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }
        nav li a:hover {
            background-color: #111;
        }
        .active {
            background-color: #04AA6D;
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to Page 1</h1>
    </header>

    <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a class="active" href="page1.html">Page 1</a></li>
            <li><a href="page2.html">Page 2</a></li>
            <li><a href="page3.html">Page 3</a></li>
            <li><a href="page4.html">Page 4</a></li>
            <li><a href="page5.html">Page 5</a></li>
        </ul>
    </nav>

    <main>
        <p>This is the content for Page 1. Each page uses the same navigation structure.</p>
    </main>

    <footer>
        <p>&copy; 2025 My Website</p>
    </footer>

</body>
</html>
