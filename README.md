<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Моя страница с видео</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul class="menu">
                <li><a href="#heroes">Герои</a></li>
                <li><a href="#movies">Фильмы</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="heroes">
            <h2>Мои любимые герои</h2>
            <div class="video-container">
                <iframe src="https://dota2.su/media/uploads/2024/08/14/dota_2_earthshaker_441741_2048x1152.jpg" frameborder="0" allowfullscreen></iframe>
                <iframe src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSZbVGPOnC-iuCFTDEnx8P5uGqvhsDrIBMXRg&s" frameborder="0" allowfullscreen></iframe>
            </div>
        </section>

 <section id="movies">
            <h2>Мои любимые фильмы</h2>
            <div class="video-container">
                <iframe src="https://upload.wikimedia.org/wikipedia/ru/1/15/Transformers_Age_of_Extinction.jpg" frameborder="0" allowfullscreen></iframe>
                <iframe src="https://upload.wikimedia.org/wikipedia/ru/6/62/Hitman_%28poster%29.jpg" frameborder="0" allowfullscreen></iframe>
            </div>
        </section>
    </main>     






    body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    padding: 10px 0;
}

.menu {
    list-style: none;
    display: flex;
    justify-content: center;
}

.menu li {
    margin: 0 15px;
}

.menu a {
    color: white;
    text-decoration: none;
    padding: 10px 15px;
    border-radius: 5px;
    transition: background-color 0.3s;
}

.menu a:hover {
    background-color: #555;
}

main {
    padding: 20px;
}

h2 {
    color: #333;
}

.video-container {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    margin: 20px 0;
}

.video-container iframe {
    width: 300px;
    height: 200px;
    margin: 10px;
    border: 2px solid #ccc;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

footer {
    text-align: center;
    padding: 10px 0;
    background-color: #333;
    color: white;
    position: relative;
    bottom: 0;
    width: 100%;
}
