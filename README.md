<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projret</title>
    <link rel="stylesheet" href="Projet.css">
</head>
<body>
    <header>
        <div class="Principale">
        </div>
        <ul>
            <li class="active">
                <a href="#">Accueil</a>
            </li>
            <li>
                <a href="#">Service</a>
            </li>
            <li>
                <a href="#">Blog</a>
            </li>
            <li>
                <a href="#">A propos de nous</a>
            </li>
            <li>
                <a href="#">Contact</a>
            </li>
        </ul>
    </header>
    <video src="WhatsApp Vidéo 2024-02-17 à 13.12.51_d62bb7e3.mp4" controls> welcome</video>
    
</body>
</html>
*{
    padding: 0%;
    margin: 0%;
    box-sizing: border-box;
    font-family: century;
}
header{
    background-image: url(NY.img.jpg);
    height: 100%;
    background-size: cover;
    background-position: center;
}
ul{
    list-style: none;
    float: right;
    display: flex;
    margin-top: 20px;
}
ul li a {
    text-decoration: none;
    color: #ffff;
    padding: 10px 20px;
    text-transform: uppercase;
    border: 1px solid #ffff;
    margin: 10px;
    font-weight: 500;
    transition: 0.6s ease;
}
ul li a:hover{
    background-color: #ffff;
    color: #000;
}
ul li.active a{
    background:#ffff;
    color: #000;
}
.Principale{
    max-width: 114rem;
    margin: 0 auto;
}
