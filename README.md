<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Uganda Wildlife Conservation Society's mission and vision.">
    <title>UWCS - Home</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="hero-banner">
        <div class="overlay">
            <h1>Welcome to Uganda Wildlife Conservation Society</h1>
            <p>Preserving Uganda’s wildlife for future generations.</p>
        </div>
    </header>
    <nav>
        <ul>
            <li><a href="wildlife-projects.html">Wildlife</a></li>
            <li><a href="wildlife-projects.html">Projects</a></li>
            <li><a href="events-education.html">Events</a></li>
            <li><a href="support-contact.html">Support</a></li>
        </ul>
    </nav>
    <main>
        <section class="intro">
            <h2>About Uganda’s Biodiversity</h2>
            <p>Uganda is home to some of the world's most diverse wildlife. From the majestic gorillas to colorful birds, every creature plays a vital role in our ecosystem.</p>
            <a href="wildlife-projects.html" class="btn">Learn More</a>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Uganda Wildlife Conservation Society</p>
    </footer>
</body>
</html>
# uganda.wild.life<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Discover Uganda’s wildlife and ongoing conservation projects.">
    <title>UWCS - Wildlife & Projects</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="hero-banner">
        <div class="overlay">
            <h1>Explore Uganda’s Wildlife & Conservation Efforts</h1>
        </div>
    </header>
    <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="events-education.html">Events</a></li>
            <li><a href="support-contact.html">Support</a></li>
        </ul>
    </nav>
    <main>
        <section class="wildlife-gallery">
            <h2>Wildlife Gallery</h2>
            <div class="gallery">
                <div class="gallery-item">Mammals</div>
                <div class="gallery-item">Birds</div>
                <div class="gallery-item">Reptiles</div>
                <div class="gallery-item">Endangered Species</div>
            </div>
        </section>
        <section class="projects">
            <h2>Conservation Projects</h2>
            <p>Discover our projects, achievements, and how you can help.</p>
            <a href="support-contact.html" class="btn">Get Involved</a>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Uganda Wildlife Conservation Society</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f5f5f5;
    color: #333;
}

header.hero-banner {
    background-image: url('wildlife-banner.jpg');
    background-size: cover;
    background-position: center;
    color: #fff;
    text-align: center;
    padding: 50px 20px;
    position: relative;
}

header.hero-banner .overlay {
    background: rgba(0, 0, 0, 0.5);
    padding: 20px;
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 10px;
    background: #006400;
    text-align: center;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 16px;
}

main {
    padding: 20px;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
    margin-top: 20px;
}

.gallery {
    display: flex;
    gap: 20px;
    flex-wrap: wrap;
}

.gallery-item {
    background: #ddd;
    padding: 20px;
    flex: 1 1 calc(25% - 20px);
    box-sizing: border-box;
    text-align: center;
}

.btn {
    display: inline-block;
    margin-top: 10px;
    padding: 10px 20px;
    background: #006400;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
}

lets tour Uganda 
