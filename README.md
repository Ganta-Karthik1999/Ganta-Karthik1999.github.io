<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Karthik Ganta's Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1rem;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 1rem;
        }
        .section {
            margin-bottom: 2rem;
        }
        .section h2 {
            background-color: #333;
            color: #fff;
            padding: 0.5rem;
        }
        .project, .skill {
            background-color: #fff;
            padding: 1rem;
            margin-bottom: 1rem;
            border-radius: 5px;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        a {
            color: #333;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Karthik Ganta's Portfolio</h1>
    </header>
    <div class="container">
        <section class="section" id="about">
            <h2>About Me</h2>
            <p>Hello! I am Karthik Ganta, a graduate student at Northeastern University majoring in Cyber-Physical Systems with a focus on IoT. I am passionate about embedded systems and firmware development.</p>
        </section>
        <section class="section" id="projects">
            <h2>Projects</h2>
            <div class="project">
                <h3>IOT Based Agriculture Monitoring System</h3>
                <p>This project involves developing an IoT-based agriculture monitoring system that helps farmers monitor their fields remotely. The system uses various sensors to measure humidity, soil moisture, and water levels, transmitting data in real-time to a cloud platform.</p>
                <p><a href="https://github.com/Ganta-Karthik1999/IOT-Based-Agriculture-Monitoring-system" target="_blank">View on GitHub</a></p>
            </div>
            <!-- Add more projects as needed -->
        </section>
        <section class="section" id="skills">
            <h2>Skills</h2>
            <div class="skill">
                <h3>Programming Languages</h3>
                <p>C, C++, Python, C#</p>
            </div>
            <div class="skill">
                <h3>Technologies</h3>
                <p>Embedded Systems, IoT, ROS, SLAM, Blynk</p>
            </div>
            <!-- Add more skills as needed -->
        </section>
        <section class="section" id="contact">
            <h2>Contact</h2>
            <p>Email: <a href="mailto:ganta.k@northeastern.edu">ganta.k@northeastern.edu</a></p>
            <p>LinkedIn: <a href="https://www.linkedin.com/in/karthik-ganta" target="_blank">Karthik Ganta</a></p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Karthik Ganta</p>
    </footer>
</body>
</html>
