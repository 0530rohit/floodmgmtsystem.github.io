<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Rohit - GitHub Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
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
            padding-top: 40px;
        }

        header {
            text-align: center;
            padding: 20px;
            background-color: #6a1b9a;
            color: #fff;
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.2rem;
        }

        section {
            padding: 40px 20px;
            margin: 20px 0;
        }

        section h2 {
            color: #6a1b9a;
            font-size: 2rem;
            margin-bottom: 20px;
        }

        .projects ul {
            list-style: none;
            padding: 0;
        }

        .projects ul li {
            background-color: #fff;
            margin: 10px 0;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        .projects strong {
            color: #d32f2f;
        }

        .skills ul {
            list-style: none;
            padding: 0;
        }

        .skills ul li {
            font-size: 1.1rem;
            margin-bottom: 8px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #6a1b9a;
            color: #fff;
        }

        footer a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }

        footer a:hover {
            text-decoration: underline;
        }

        blockquote {
            font-style: italic;
            margin: 20px 0;
            padding: 20px;
            background: #f1f1f1;
            border-left: 4px solid #6a1b9a;
            color: #444;
        }

        .contact-info {
            margin-top: 30px;
            font-size: 1.2rem;
        }

        .contact-info span {
            font-weight: bold;
        }
    </style>
</head>

<body>
    <!-- Header Section -->
    <header>
        <h1>Hello, Rohit 👋</h1>
        <p>I am passionate about technology and problem-solving. Here's a glimpse of my work:</p>
    </header>

    <!-- Projects Section -->
    <section class="projects">
        <h2>🛠 Projects</h2>
        <ul>
            <li>
                <strong>Project 1: Flood Monitoring and Management System</strong>
                <p>
                    The Flood Monitoring and Management System is a comprehensive tool designed to enhance disaster preparedness and response.
                    It intelligently processes vague or unclear environmental data inputs, narrows down risk zones through targeted analyses,
                    ensures quick access to emergency facilities, and provides personalized evacuation and safety recommendations.
                    With these four integrated modules, the system aims to provide timely and accurate guidance, empowering communities to make
                    informed decisions while mitigating flood-related risks.
                </p>

                <h3>Modules:</h3>
                <ul>
                    <li><strong>1st Module: Flood Prediction:</strong> Uses environmental data (rainfall, river levels, soil moisture) with advanced algorithms like time-series analysis or machine learning models to predict the likelihood of flooding in specific areas.</li>
                    <li><strong>2nd Module: Flood Evacuation:</strong> Based on real-time predictions, identifies at-risk populations and suggests evacuation plans using decision analysis techniques like decision trees.</li>
                    <li><strong>3rd Module: Flood Risk Mapping:</strong> Generates detailed flood risk maps using topographical data and historical patterns to highlight high-risk areas using GIS (Geographic Information Systems).</li>
                    <li><strong>4th Module: Flood Drainage Network Optimization:</strong> Optimizes the flood drainage network using graph-based algorithms like Dijkstra's algorithm to ensure efficient water flow and reduce flood impact.</li>
                </ul>
            </li>
        </ul>
    </section>

    <!-- Skills Section -->
    <section class="skills">
        <h2>🚀 Skills</h2>
        <ul>
            <li>C++, Python, C</li>
            <li>Data Structures and Algorithms</li>
        </ul>
    </section>

    <!-- Academic Details Section -->
    <section class="academic">
        <h2>📚 Academic Details</h2>
        <div>
            <p><span>Course Name:</span> Algorithmic Lab</p>
            <p><span>Course Code:</span> 24ECSP205</p>
            <p><span>Name:</span> Rohit </p>
            <p><span>SRN:</span> 02FE23BCS074</p>
            <p><span>Course Instructor:</span> Prof. Vaishali Parab</p>
            <p><span>University:</span> KLE Technological University</p>
            <p><span>Course Topic:</span> Flood Management System (Computer Science)</p>
        </div>
    </section>

    <!-- Quote Section -->
    <section>
        <blockquote>
            “When something is important enough, you do it even if the odds are not in your favor.” – Elon Musk
        </blockquote>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2025 Rohit | <a href="https://github.com/your-username" target="_blank">GitHub</a> | <a href="#contact">Contact Me</a></p>
    </footer>

    <!-- Contact Info (Optional) -->
    <div id="contact" class="contact-info">
        <h3>Contact Info</h3>
        <p><span>Email:</span> your-email@example.com</p>
        <p><span>LinkedIn:</span> <a href="https://www.linkedin.com/in/your-profile/" target="_blank">LinkedIn Profile</a></p>
    </div>
</body>

</html>
