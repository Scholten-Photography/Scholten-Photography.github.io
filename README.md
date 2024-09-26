<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Photography Portfolio</title>
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
        <h1>Photography Portfolio</h1>
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
        <p>Hi, I’m Janet Scholten, a photographer with a passion for capturing the beauty of nature and exploring new perspectives. Through my lens, I strive to highlight the unique moments and details that often go unnoticed. Whether it's a sweeping landscape or a simple portrait, my goal is to inspire others to see the world in fresh and exciting ways.</p>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>If you are interested in working with me or have any questions, feel free to contact me at:</p>
        <p>Email: <a href="jscholten@hotmail.ca" style="color: #fff;">jscholten@hotmail.ca</a></p>
        <p>Phone: <a href="(604) 217-1751" style="color: #fff;">(604) 217-1751</a></p>
    </section>

    <section id="social-media">
        <h2>Follow Me</h2>
        <div class="social-media">
            <a href="https://www.instagram.com/yourprofile" target="_blank">Instagram</a> |
            <a href="https://www.facebook.com/yourprofile" target="_blank">Facebook</a> |
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Your Name. All rights reserved.</p>
    </footer>
</body>
</html>
