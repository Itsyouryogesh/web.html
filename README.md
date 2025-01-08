<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #77B300 3px solid;
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
            text-align: center;
        }
        header li {
            display: inline;
            padding: 0 20px 0 20px;
        }
        .showcase {
            min-height: 400px;
            background: url('"C:\Users\Student\Desktop\channels4_profile.jpg"') no-repeat center center/cover;
            text-align: center;
            color: #fff;
        }
        .showcase h1 {
            font-size: 55px;
            margin-top: 100px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>My Portfolio</h1>
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Projects</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <section class="showcase">
        <div class="container">
            <h1>Welcome to My Portfolio</h1>
            <p>Your tagline or description goes here.</p>
        </div>
    </section>
</body>
</html>
