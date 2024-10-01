<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Apple Vision Pro Website Clone built using HTML, CSS, JavaScript, GSAP, and ScrollTrigger.">
    <meta name="keywords" content="HTML, CSS, JavaScript, GSAP, ScrollTrigger, Apple Vision Pro, Frontend Development">
    <meta name="author" content="Sainath Medpalli">
    <title>Apple Vision Pro Website Clone</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Basic reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
        }
        header {
            background: #000;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            font-size: 2.5rem;
     }
        .content {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

  .content h2 {
            font-size: 2rem;
            margin-bottom: 10px;
            color: #333;
        }
        .content p {
            font-size: 1.2rem;
            margin-bottom: 20px;
            line-height: 1.8;
        }
        .project-image {
            text-align: center;
        }
        .project-image img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
        }
        .features {
            margin-top: 20px;
        }
        .features h3 {
            font-size: 1.8rem;
            color: #000;
        }
        .features ul {
            list-style-type: none;
        }
        .features li {
            font-size: 1.2rem;
            margin: 10px 0;
            padding-left: 20px;
            position: relative;
        }
        .features li::before {
            content: '✓';
            color: #4CAF50;
            position: absolute;
            left: 0;
            top: 0;
        }
        .cta-button {
            display: inline-block;
            padding: 10px 20px;
            font-size: 1.2rem;
            color: #fff;
            background-color: #007bff;
            border: none;
            border-radius: 5px;
            text-decoration: none;
            transition: background-color 0.3s ease;
        }
        .cta-button:hover {
            background-color: #0056b3;
        }
       footer {
            text-align: center;
            padding: 20px;
            background-color: #000;
            color: #fff;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Apple Vision Pro Website Clone</h1>
    </header>
    <div class="content">
        <h2>🚀 Excited to Share My Latest Project!</h2>
        <p>
            I’m thrilled to announce the completion of my latest web development project: 
            <strong>an Apple Vision Pro website clone</strong>! This project was an incredible learning journey, and I’m proud of the result.
        </p>     
        <div class="project-image">
            <img src="https://github.com/Sainath0009/Apple-Vision-Website-Clone/assets/161853073/98d72acf-e680-4c6e-b413-8d4e91bc4ef6" alt="Apple Vision Pro Clone">
      </div>
        <h2>🔑 Key Features</h2>
        <div class="features">
            <h3>What I've Built:</h3>
            <ul>
                <li><strong>Smooth Animations:</strong> Leveraging GSAP for fluid animations, enhancing user experience.</li>
                <li><strong>Interactive Scrolling Effects:</strong> Powered by ScrollTrigger, creating dynamic, immersive scrolling.</li>
                <li><strong>Responsive Design:</strong> Fully responsive, providing a seamless experience across all devices.</li>
            </ul>
        </div>
        <p>
            Check out the project in action! Click the button below to explore the live site:
        </p>
        <p>
            <a href="https://sainath0009.github.io/Apple-Vision-Website-Clone/" class="cta-button">View Live Project</a>
        </p>
    </div>
    <footer>
        <p>Developed by Sainath Medpalli | 2024</p>
    </footer>
</body>
</html>
