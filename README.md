<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Photo Download Site</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Free Photo Downloads</h1>
    </header>

    <section class="gallery">
        <div class="photo">
            <img src="https://source.unsplash.com/300x200/?nature" alt="Nature Photo">
            <a href="https://source.unsplash.com/300x200/?nature" download="nature.jpg" class="download-btn">Download</a>
        </div>

        <div class="photo">
            <img src="https://source.unsplash.com/300x200/?city" alt="City Photo">
            <a href="https://source.unsplash.com/300x200/?city" download="city.jpg" class="download-btn">Download</a>
        </div>

        <div class="photo">
            <img src="https://source.unsplash.com/300x200/?technology" alt="Technology Photo">
            <a href="https://source.unsplash.com/300x200/?technology" download="tech.jpg" class="download-btn">Download</a>
        </div>
    </section>

    <script src="script.js"></script>
</body>
</html>
