# floodmgmtsystem.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rohit's Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        /* General Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
        }
        /* Header Section */
        header {
            background: linear-gradient(135deg, #6a1b9a, #d32f2f);
            color: #fff;
            text-align: center;
            padding: 50px 20px;
            position: relative;
        }
        header h1 {
            font-size: 3rem;
            margin-bottom: 10px;
        }
        header p {
            font-size: 1.2rem;
        }
        header .profile-photo {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 4px solid #fff;
            margin: 20px auto;
            display: block;
            object-fit: cover;
        }

        /* Hamburger Menu Styles */
        .hamburger {
            display: none;
            flex-direction: column;
            cursor: pointer;
            position: absolute;
            top: 20px;
            right: 20px;
        }
        .hamburger div {
            width: 30px;
            height: 4px;
            background-color: #fff;
            margin: 4px 0;
            transition: all 0.3s ease;
        }

        /* Navigation Menu */
        nav {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            background: #6a1b9a;
            padding: 10px 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            padding: 10px 20px;
            font-weight: bold;
            font-size: 1rem;
            transition: background 0.3s ease;
        }
        nav a:hover {
            background: #d32f2f;
            border-radius: 5px;
        }

        /* Responsive Navigation */
        @media (max-width: 768px) {
            .hamburger {
                display: flex;
            }
            nav {
                display: none;
                flex-direction: column;
                align-items: center;
                background: #6a1b9a;
                position: absolute;
                top: 70px;
                right: 10px;
                width: 200px;
                border-radius: 8px;
                box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            }
            nav.active {
                display: flex;
            }
            nav a {
                margin: 10px 0;
            }
        }

        /* Main Content Styling */
        .container {
            max-width: 1100px;
            margin: 40px auto;
            padding: 20px;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #6a1b9a;
            border-bottom: 2px solid #6a1b9a;
            padding-bottom: 5px;
            margin-bottom: 20px;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        ul li {
            margin-bottom: 10px;
            font-size: 1rem;
        }
        ul li strong {
            color: #d32f2f;
        }
        dl dt {
            font-weight: bold;
            color: #333;
            margin-top: 10px;
        }
        dl dd {
            margin-left: 20px;
            margin-bottom: 10px;
            color: #555;
        }
        blockquote {
            font-style: italic;
            margin: 20px 0;
            padding: 20px;
            background: #f1f1f1;
            border-left: 4px solid #6a1b9a;
            color: #444;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <!-- Profile Photo -->
        <img src="your-photo.jpg" alt="Profile Photo" class="profile-photo">
        <h1>Hello, I'm Rohit👋</h1>
        <p>A passionate problem-solver & tech enthusiast</p>

        <!-- Hamburger Menu -->
        <div class="hamburger" id="hamburger">
            <div></div>
            <div></div>
            <div></div>
        </div>

        <!-- Navigation Menu -->
        <nav id="nav-menu">
            <a href="desc.html">Description</a>
            <a href="Flood Prediction.html">Flood Prediction</a>
            <a href="Flood Evacuation.html">Flood Evacuation</a>
            <a href="Flood Risk Mapping.html">Flood Risk Mapping</a>
            <a href="Flood drainage nerwork optimization.html">Flood drainage nerwork optimization</a>
            <a href="Program.html">Code</a>
        </nav>
    </header>

    <!-- Main Content -->
    <div class="container">
        <h2>Academic Details</h2>
        <dl>
            <dt>Course Name</dt>
            <dd>Algorithmic Problem Solving</dd>
            <dt>Course Code</dt>
            <dd>24ECSC205</dd>
            <dt>Name</dt>
            <dd>Rohit</dd>
            <dt>SRN</dt>
            <dd>02FE23BCS074</dd>
            <dt>University</dt>
            <dd>KLE Technological University</dd>
        </dl>
        <blockquote>“The only way to do great work is to love what you do.” – Steve Jobs</blockquote>

        <!-- Project Section -->
        <h2>Projects</h2>
        <ul>
            <li><strong>Flood Management System</strong></li>
        </ul>

        <!-- Skills Section -->
        <h2>Skills</h2>
        <ul>
            <li>Programming Languages: C++, Python, C</li>
            <li>Core Concepts: Data Structures and Algorithms</li>
        </ul>
    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Vaibhav | <a href="#contact">Contact Me</a></p>
    </footer>

    <script>
        // JavaScript for Hamburger Toggle
        const hamburger = document.getElementById('hamburger');
        const navMenu = document.getElementById('nav-menu');

        hamburger.addEventListener('click', () => {
            navMenu.classList.toggle('active');
        });
    </script>
</body>
</html>
