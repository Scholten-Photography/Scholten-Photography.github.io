<h1>Hello</h1>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Photography Portfolio</title>
    <style>
        body {
            background-color: #000;
            color: #fff;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            text-align: center;
            padding: 50px;
        }
        section {
            max-width: 1000px;
            margin: 0 auto;
            padding: 50px;
        }
        h1, h2 {
            text-align: center;
            color: #fff;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .gallery img {
            width: 300px;
            height: 200px;
            object-fit: cover;
        }
        .social-media a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
        }
        footer {
            text-align: center;
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Your Photography Portfolio</h1>
    </header>

    <section id="my-work">
        <h2>My Work</h2>
        <div class="gallery">
            <!-- Add your photo URLs below -->
            <img src="photo1.jpg" alt="Photography 1">
            <img src="photo2.jpg" alt="Photography 2">
            <img src="photo3.jpg" alt="Photography 3">
            <img src="photo4.jpg" alt="Photography 4">
            <!-- Add more photos as needed -->
        </div>
    </section>

    <section id="about-me">
        <h2>About Me</h2>
        <p>Hello! I am a passionate photographer based in Abbotsford, BC. I love capturing moments through my lens, whether it's landscapes, portraits, or abstract photography. My work reflects my unique perspective on the world, and I'm always exploring new ways to tell a story through images. Feel free to reach out if you'd like to collaborate or inquire about my work!</p>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>If you are interested in working with me or have any questions, feel free to contact me at:</p>
        <p>Email: <a href="mailto:your-email@example.com" style="color: #fff;">your-email@example.com</a></p>
    </section>

    <section id="social-media">
        <h2>Follow Me</h2>
        <div class="social-media">
            <a href="https://www.instagram.com/yourprofile" target="_blank">Instagram</a> |
            <a href="https://www.facebook.com/yourprofile" target="_blank">Facebook</a> |
            <a href="https://twitter.com/yourprofile" target="_blank">Twitter</a>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Your Name. All rights reserved.</p>
    </footer>
</body>
</html>
