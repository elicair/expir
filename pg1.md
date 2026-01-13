<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image and Table Page</title>
    <style>
        body {
            font-family: sans-serif;
            text-align: center;
            margin: 20px;
        }
        img {
            max-width: 100%;
            height: auto;
            border: 2px solid #333;
            margin-bottom: 20px;
        }
        table {
            width: 50%;
            margin: 0 auto 20px auto;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
        .home-button {
            padding: 10px 20px;
            background-color: #007BFF;
            color: white;
            border: none;
            cursor: pointer;
            text-decoration: none;
            border-radius: 5px;
        }
    </style>
</head>
<body>

    <h1>Welcome to the Sample Page</h1>

    <!-- Image Section -->
    <h2>Our Image</h2>
    <!-- Replace 'path/to/your/image.jpg' with the actual path to your image file -->
    <img src="path/to/your/image.jpg" alt="A sample image">

    <!-- Table Section -->
    <h2>Data Table</h2>
    <table>
        <thead>
            <tr>
                <th>Header 1</th>
                <th>Header 2</th>
                <th>Header 3</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Row 1, Cell 1</td>
                <td>Row 1, Cell 2</td>
                <td>Row 1, Cell 3</td>
            </tr>
            <tr>
                <td>Row 2, Cell 1</td>
                <td>Row 2, Cell 2</td>
                <td>Row 2, Cell 3</td>
            </tr>
            <tr>
                <td>Row 3, Cell 1</td>
                <td>Row 3, Cell 2</td>
                <td>Row 3, Cell 3</td>
            </tr>
        </tbody>
    </table>

    <!-- Redirect Button Section -->
    <!-- The anchor tag acts as a link. The class is for styling as a button. -->
    <a href="README.md" class="home-button">Go to Home Page</a>

</body>
</html>
