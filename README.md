<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Homburger Hutsalon</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>Homburger Hutsalon</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Startseite</a></li>
                <li><a href="#about">Über uns</a></li>
                <li><a href="#products">Produkte</a></li>
                <li><a href="#contact">Kontakt</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="home">
            <h2>Willkommen im Homburger Hutsalon</h2>
            <p>Elegante Hüte für jeden Anlass – Qualität und Stil vereint.</p>
        </section>
        <section id="about">
            <h2>Über uns</h2>
            <p>Seit über 50 Jahren steht der Homburger Hutsalon für handgefertigte Hüte, ausgezeichnete Beratung und ein unvergessliches Einkaufserlebnis.</p>
        </section>
        <section id="products">
            <h2>Unsere Produkte</h2>
            <p>Entdecken Sie eine Auswahl an klassischen und modernen Hüten, maßgeschneidert für Ihren Stil.</p>
        </section>
        <section id="contact">
            <h2>Kontakt</h2>
            <p>Adresse: Hauptstraße 123, Bad Homburg<br>E-Mail: info@homburger-hutsalon.de<br>Telefon: 06172-123456</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Homburger Hutsalon. Alle Rechte vorbehalten.</p>
    </footer>
</body>
</html>
body {
    font-family: 'Georgia', serif;
    margin: 0;
    color: #4B1C1C;
    background-color: #F5E5DA;
}

header {
    background-color: #8B0000;
    color: #F5E5DA;
    padding: 10px 20px;
    text-align: center;
}

header .logo h1 {
    margin: 0;
    font-size: 2.5rem;
}

nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: center;
    gap: 15px;
    margin: 10px 0 0 0;
}

nav ul li {
    display: inline;
}

nav ul li a {
    text-decoration: none;
    color: #F5E5DA;
    font-size: 1.2rem;
}

nav ul li a:hover {
    text-decoration: underline;
}

main {
    padding: 20px;
    text-align: center;
}

main section {
    margin: 20px 0;
}

footer {
    background-color: #8B0000;
    color: #F5E5DA;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}
