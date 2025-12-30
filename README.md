# Vishwanath-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Animated Portfolio</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body {
            background: linear-gradient(120deg, #0f2027, #203a43, #2c5364);
            color: white;
            overflow-x: hidden;
        }

        header {
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            animation: fadeIn 2s ease;
        }

        header h1 {
            font-size: 3rem;
            animation: slideDown 1.5s ease;
        }

        header p {
            margin-top: 10px;
            font-size: 1.2rem;
            opacity: 0.8;
        }

        section {
            padding: 60px 10%;
        }

        h2 {
            text-align: center;
            margin-bottom: 40px;
            font-size: 2.5rem;
            position: relative;
        }

        h2::after {
            content: '';
            width: 80px;
            height: 4px;
            background: #00eaff;
            display: block;
            margin: 10px auto;
        }

        .about {
            text-align: center;
            animation: fadeInUp 2s ease;
        }

        .skills {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }

        .skill-box {
            background: rgba(255, 255, 255, 0.1);
            padding: 20px;
            border-radius: 10px;
            text-align: center;
            transition: transform 0.3s, background 0.3s;
        }

        .skill-box:hover {
            transform: translateY(-10px);
            background: rgba(0, 234, 255, 0.2);
        }

        footer {
            text-align: center;
            padding: 20px;
            background: rgba(0, 0, 0, 0.4);
        }

        /* Animations */
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @keyframes slideDown {
            from {
                transform: translateY(-50px);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }

        @keyframes fadeInUp {
            from {
                transform: translateY(50px);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }
    </style>
</head>
<body>

<header>
    <div>
        <h1>Hello, I'm <span style="color:#00eaff;">Vishwanath</span></h1>
        <p>Web Developer | Designer | Learner</p>
    </div>
</header>

<section>
    <h2>About Me</h2>
    <p class="about">
        I am a passionate web developer who loves creating animated and modern websites
        using HTML and CSS. I enjoy learning new technologies and building cool projects.
    </p>
</section>

<section>
    <h2>Skills</h2>
    <div class="skills">
        <div class="skill-box">HTML5</div>
        <div class="skill-box">CSS3</div>
        <div class="skill-box">JavaScript</div>
        <div class="skill-box">Responsive Design</div>
    </div>
</section>

<footer>
    <p>© 2025 Vishwanath | Animated Portfolio</p>
</footer>

</body>
</html>
