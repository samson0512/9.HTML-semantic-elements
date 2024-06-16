# 9.HTML-semantic-elements
# program :
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Semantic Elements</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header, nav, section, article, aside, footer {
            padding: 20px;
            margin: 10px;
        }
        header {
            background-color: #333;
            color: white;
            text-align: center;
        }
        nav {
            background-color: #555;
            color: white;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        section {
            display: flex;
        }
        article {
            flex: 3;
            background-color: #f9f9f9;
        }
        aside {
            flex: 1;
            background-color: #f4f4f4;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>DAY TODAY NEWS</h1>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
</nav>

<section>
    <article>
        <h2>football Article </h2>
        <p>Football’s governing body, the Fédération Internationale de Football Association (FIFA), estimated that at the turn of the 21st century there were approximately 250 million football players and over 1.3 billion people “interested” in football; in 2010 a combined television audience of more than 26 billion watched football’s premier tournament, the quadrennial monthlong World Cup finals.</p>
        <p>Principal rules and essential equipment, the sport can be played almost anywhere, from official football playing fields (pitches) to gymnasiums, streets, school playgrounds, parks, or beaches.</p>
    </article>

    <aside>
        <h3>Related Content</h3>
        <ul>
            <li><a href="#link1">Related Link 1</a></li>
            <li><a href="#link2">Related Link 2</a></li>
            <li><a href="#link3">Related Link 3</a></li>
        </ul>
    </aside>
</section>

<footer>
    <p>&copy; 2024 Sam Pvt.Ltd</p>
</footer>

</body>
</html>
# output:
![image](https://github.com/samson0512/9.HTML-semantic-elements/assets/172907275/86650c52-6846-4ce7-82c0-f803410f0af5)
