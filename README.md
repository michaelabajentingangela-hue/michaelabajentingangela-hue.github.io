<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>VisionWeb - Visualize Your Dream Website</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- ===== CSS STYLE ===== -->
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, Helvetica, sans-serif;
        }

        body {
            background-color: #f4f6f9;
            color: #333;
        }

        /* ===== NAVIGATION ===== */
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 40px;
            background: #ffffff;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
        }

        .logo {
            font-size: 1.5rem;
            font-weight: bold;
            color: #4f46e5;
        }

        .nav-links a {
            margin-left: 20px;
            text-decoration: none;
            color: #333;
            font-weight: 500;
        }

        .nav-links a:hover {
            color: #4f46e5;
        }

        /* ===== HERO SECTION ===== */
        .hero {
            text-align: center;
            padding: 80px 20px;
            background: linear-gradient(135deg, #4f46e5, #7c3aed);
            color: white;
        }

        .hero h1 {
            font-size: 2.8rem;
        }

        .hero p {
            margin-top: 15px;
            font-size: 1.2rem;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }

        .btn {
            display: inline-block;
            margin-top: 25px;
            padding: 12px 25px;
            background: white;
            color: #4f46e5;
            text-decoration: none;
            border-radius: 30px;
            font-weight: bold;
            transition: 0.3s;
        }

        .btn:hover {
            background: #e0e7ff;
        }

        /* ===== SECTION GENERAL ===== */
        section {
            padding: 60px 20px;
            max-width: 1100px;
            margin: auto;
        }

        section h2 {
            text-align: center;
            margin-bottom: 30px;
            color: #4f46e5;
        }

        /* ===== FEATURES ===== */
        .features-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .feature-card {
            background: white;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.08);
            transition: 0.3s;
        }

        .feature-card:hover {
            transform: translateY(-5px);
        }

        /* ===== ABOUT ===== */
        .about {
            text-align: center;
            max-width: 700px;
            margin: auto;
        }

        /* ===== FOOTER ===== */
        footer {
            background: #1f2937;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
    </style>
</head>

<body>

<!-- ===== NAVIGATION BAR ===== -->
<nav>
    <div class="logo">VisionWeb</div>
    <div class="nav-links">
        <a href="#">Home</a>
        <a href="#features">Features</a>
        <a href="#about">About</a>
    </div>
</nav>

<!-- ===== HERO SECTION ===== -->
<div class="hero">
    <h1>Visualize Your Dream Website</h1>
    <p>
        Plan layouts, explore designs, and choose the perfect color combinations —
        all before building your website.
    </p>
    <a href="#features" class="btn">Get Started</a>
</div>

<!-- ===== FEATURES SECTION ===== -->
<section id="features">
    <h2>What We Help You With</h2>
    <div class="features-container">
        <div class="feature-card">
            <h3>Website Visualization</h3>
            <p>Turn your ideas into clear visual concepts before development begins.</p>
        </div>

        <div class="feature-card">
            <h3>Layout Selection</h3>
            <p>Explore different structures and page layouts that fit your goals.</p>
        </div>

        <div class="feature-card">
            <h3>Design & Color Matching</h3>
            <p>Find color combinations and design themes that best represent your brand.</p>
        </div>
    </div>
</section>

<!-- ===== ABOUT SECTION ===== -->
<section id="about">
    <h2>Who Is VisionWeb For?</h2>
    <div class="about">
        <p>
            VisionWeb is designed for everyone interested in creating websites —
            beginners, students, business owners, and aspiring designers.
            If you can imagine it, we help you visualize it.
        </p>
    </div>
</section>

<!-- ===== FOOTER ===== -->
<footer>
    <p>© 2026 VisionWeb | Helping You Design With Confidence</p>
</footer>

</body>
</html>
