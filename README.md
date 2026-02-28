<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>website test| Official Website</title>

    <style>
        /* RESET */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, sans-serif;
            background: #0a0a0a;
            color: white;
        }

        /* HEADER */
        header {
            text-align: center;
            padding: 45px 20px;
            background: #111;
            box-shadow: 0 0 15px #00ffee;
        }

        header h1 {
            font-size: 45px;
            color: #00ffee;
            text-shadow: 0 0 15px #00ffee;
        }

        header p {
            color: #ccc;
            font-size: 18px;
            margin-top: 10px;
        }

        /* NAV BAR */
        nav {
            background: #141414;
            text-align: center;
            padding: 15px 0;
            position: sticky;
            top: 0;
            z-index: 10;
        }

        nav a {
            color: #00ffee;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
            padding: 8px 14px;
            border-radius: 6px;
            transition: 0.3s;
        }

        nav a:hover {
            background: #00ffee;
            color: #000;
            box-shadow: 0 0 15px #00ffee;
        }

        /* SECTIONS */
        section {
            padding: 70px 25px;
            text-align: center;
        }

        h2 {
            font-size: 36px;
            color: #00ffee;
            text-shadow: 0 0 10px #00ffee;
            margin-bottom: 15px;
        }

        p {
            color: #ccc;
            font-size: 18px;
            max-width: 750px;
            margin: 0 auto;
        }

        /* BUTTONS */
        .btn {
            display: inline-block;
            margin-top: 30px;
            padding: 12px 28px;
            background: #00ffee;
            color: #000;
            font-weight: bold;
            border-radius: 10px;
            text-decoration: none;
            box-shadow: 0 0 15px #00ffee;
            transition: 0.3s;
        }

        .btn:hover {
            transform: scale(1.07);
            background: #00c4b8;
            box-shadow: 0 0 25px #00ffee;
        }

        /* FOOTER */
        footer {
            text-align: center;
            background: #111;
            padding: 20px;
            font-size: 14px;
            color: #777;
            margin-top: 40px;
        }
    </style>
</head>

<body>

    <!-- HEADER -->
    <header>
        <h1>Welcome to j9vr</h1>
        <p>The official GitHub Pages website</p>
    </header>

    <!-- NAVIGATION -->
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- HOME -->
    <section id="home">
        <h2>Home</h2>
        <p>This is your new website hosted completely for free on GitHub Pages.  
           You can customize anything — text, colors, buttons, sections, images, and more.</p>

        <a class="btn" href="#about">Learn More</a>
    </section>

    <!-- ABOUT -->
    <section id="about">
        <h2>About</h2>
        <p>Your website is now live on <strong>j9vr.github.io</strong>.  
           You can add more pages, features, animations, or even a full gaming/clan website.</p>
    </section>

    <!-- CONTACT -->
    <section id="contact">
        <h2>Contact</h2>
        <p>Want me to build more pages or a full advanced design?  
           Just ask and I’ll generate the full code for you.</p>

        <a class="btn" href="#home">Back to Top</a>
    </section>

    <!-- FOOTER -->
    <footer>
        © 2026 • j9vr | All rights reserved
    </footer>

</body>
</html>
