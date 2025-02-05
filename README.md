<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nexa Art - Alanove Jenny Bazil</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <div class="profile-header">
            <img src="profile.jpg" alt="Alanove Jenny Bazil" class="profile-pic">
            <h1>Alanove Jenny Bazil</h1>
            <p>Portrait Artist | Acrylic Painter</p>
            <p>Kozhikode, Kerala, India</p>
        </div>
    </header>

    <section class="bio">
        <h2>About Me</h2>
        <p>Hi! I'm Alanove, the artist behind <strong>Nexa Art</strong>. I specialize in portrait art and acrylic painting, bringing emotions to life through my artwork.</p>
    </section>

    <section class="buttons">
        <a href="https://wa.me/6282925877" class="btn contact">WhatsApp Me</a>
        <a href="https://www.instagram.com/nexa.art_" class="btn hire">Follow on Instagram</a>
    </section>

    <section class="social-links">
        <h2>Find Me Online</h2>
        <a href="https://www.instagram.com/nexa.art_" class="social-btn">Instagram</a>
        <a href="https://youtube.com/@nexaartdesigns" class="social-btn">YouTube</a>
    </section>

    <section class="gallery">
        <h2>Gallery</h2>
        <div class="gallery-container">
            <img src="gallery1.jpg" alt="Artwork 1">
            <img src="gallery2.jpg" alt="Artwork 2">
            <img src="gallery3.jpg" alt="Artwork 3">
        </div>
    </section>

    <footer>
        <p>© 2025 Nexa Art | Alanove Jenny Bazil</p>
    </footer>

</body>
</html>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    text-align: center;
    background-color: #f4f4f4;
}

header {
    background-color: #222;
    color: white;
    padding: 20px;
}

.profile-header {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.profile-pic {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    border: 3px solid white;
}

h1 {
    margin: 10px 0 5px;
}

.bio, .social-links, .gallery {
    padding: 20px;
    background: white;
    margin: 10px;
    border-radius: 8px;
}

.btn {
    display: inline-block;
    padding: 10px 20px;
    margin: 10px;
    border-radius: 5px;
    text-decoration: none;
    color: white;
    font-weight: bold;
}

.contact {
    background-color: green;
}

.hire {
    background-color: blue;
}

.social-links a, .gallery img {
    margin: 10px;
    display: inline-block;
}

.gallery-container img {
    width: 100px;
    height: 100px;
    border-radius: 5px;
}

footer {
    background: #222;
    color: white;
    padding: 10px;
}
