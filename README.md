<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Resume of Souman Das">
    <title>Souman Das - Resume</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Open+Sans:wght@400;600&display=swap" rel="stylesheet">
    <style>
        /* General reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Body styling */
        body {
            font-family: 'Open Sans', sans-serif;
            background-color: #f5f5f5;
            color: #333;
        }

        /* Header and Navigation Bar */
        header {
            background-color: #2C3E50;
            color: white;
            padding: 30px 0;
            text-align: center;
        }

        header h1 {
            font-family: 'Roboto', sans-serif;
            font-size: 36px;
            margin-bottom: 10px;
        }

        header p {
            font-size: 18px;
            font-weight: 400;
            margin-bottom: 20px;
        }

        nav {
            background-color: #34495E;
            padding: 10px 0;
        }

        nav ul {
            list-style-type: none;
            display: flex;
            justify-content: center;
            padding: 0;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: 600;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #18BC9C;
        }

        /* Main content container */
        .container {
            width: 80%;
            margin: 30px auto;
        }

        /* Section Styling */
        section {
            margin-bottom: 40px;
        }

        section h2 {
            font-family: 'Roboto', sans-serif;
            color: #2C3E50;
            margin-bottom: 15px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .content {
            background-color: white;
            padding: 25px;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        .content p {
            margin-bottom: 15px;
            line-height: 1.6;
        }

        .content ul {
            list-style-type: none;
        }

        .content ul li {
            margin-bottom: 10px;
        }

        /* Contact Info */
        .contact-info {
            font-size: 16px;
        }

        .contact-info li {
            margin-bottom: 10px;
        }

        /* Footer Styling */
        footer {
            background-color: #2C3E50;
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 14px;
        }

        /* Responsive design */
        @media (max-width: 768px) {
            .container {
                width: 90%;
            }

            nav ul {
                flex-direction: column;
            }

            nav ul li {
                margin: 10px 0;
            }
        }

    </style>
</head>
<body>

<header>
    <h1>Souman Das</h1>
    <p>Web Developer | Designer | Tech Enthusiast</p>
</header>

<nav>
    <ul>
        <li><a href="#profile">Profile</a></li>
        <li><a href="#education">Education</a></li>
        <li><a href="#experience">Experience</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<div class="container">
    <section id="profile">
        <h2>Profile</h2>
        <div class="content">
            <p>Hello! I am Souman Das, a passionate web developer with expertise in HTML, CSS, JavaScript, and a love for building clean, functional websites. I enjoy problem-solving and working on both front-end and back-end web development projects.</p>
        </div>
    </section>

    <section id="education">
        <h2>Education</h2>
        <div class="content">
            <p>BBA in Digital Business and Entrepreneurship (DBE), Indian Institute of Management Bangalore (IIMB) - 2024 to 2027</p>
        </div>
    </section>

    <section id="experience">
        <h2>Experience</h2>
        <div class="content">
            <p>Web Developer Intern, ABC Tech Solutions - June 2023 to August 2023</p>
            <ul>
                <li>Developed and maintained front-end components for client websites using HTML, CSS, and JavaScript.</li>
                <li>Collaborated with senior developers to optimize website performance and fix bugs.</li>
                <li>Assisted in testing and deploying web applications to production environments.</li>
            </ul>
        </div>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <div class="content">
            <ul class="contact-info">
                <li>Email: souman.das@gmail.com</li>
                <li>Phone: +91 123 456 7890</li>
                <li>Location: Sribhumi, Assam, India</li>
            </ul>
        </div>
    </section>
</div>

<footer>
    <p>&copy; 2025 Souman Das</p>
</footer>

</body>
</html>
