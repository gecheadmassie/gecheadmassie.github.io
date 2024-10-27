<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Official website of Getachew Ambaye, a researcher in Engineering. Explore my teaching experience, publications, and contact information.">
    <meta name="keywords" content="Getachew Ambaye, Engineering, Teaching, Research, Publications">
    <title>Getachew Ambaye - Engineering Professor and Researcher</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(to bottom right, #FFFFFF, #FFFFFF);
            color: #333;
        }

        .header-container {
            display: flex;
            align-items: center;
            justify-content: flex-start;
            margin: 5px 0;
            background-color: #1626af;
            padding: 10px;
            border-top-left-radius: 15px;
            border-top-right-radius: 15px;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
            display: flex;
            margin: 0;
            color: white;
        }

        nav ul li {
            margin: 0 10px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #ffeb3b;
        }

        section {
            margin: 10px;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            width: calc(100% - 5px);
            text-align: justify;
        }

        #about {
            background-color: #e0f7fa;
        }

        #education-experience, #teaching-experience, #contact {
            background-color: #fff3e0;
        }

        #publications {
            background-color: #c8e6c9;
        }

        footer {
            text-align: center;
            padding: 5px;
            background-color: #1626af;
            color: white;
        }

        .social-media a {
            color: white;
            text-decoration: none;
            margin: 0 5px;
            transition: color 0.3s;
        }

        .social-media a:hover {
            color: #ffeb3b;
        }

        form {
            display: flex;
            flex-direction: column;
            max-width: 1000px;
            margin: 0 auto;
        }

        input[type="text"],
        input[type="email"],
        textarea {
            padding: 5px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        input[type="submit"] {
            padding: 5px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        input[type="submit"]:hover {
            background-color: #45a049;
        }

        @media (max-width: 800px) {
            .header-container {
                flex-direction: column;
                align-items: center;
            }

            nav ul {
                flex-direction: column;
                align-items: center;
            }

            section {
                margin: 5px;
                padding: 10px;
            }
        }

        .content {
            display: none;
            padding-left: 20px;
        }

        .read-more {
            color: #1626af;
            cursor: pointer;
            margin-top: 10px;
            text-decoration: underline;
        }
    </style>
</head>

<body>

    <div class="header-container">
        <img src="Photo.jpg" alt="Getachew Ambaye" class="profile-pic" style="border-radius: 50%; width: 150px; height: 150px; object-fit: cover; margin-right: 0px;">
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#education-experience">Education</a></li>
                <li><a href="#teaching-experience">Teaching Experience</a></li>
                <li><a href="#company-community-service-projects">Projects & Community Service</a></li>
                <li><a href="#publications">Publications</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </div>

    <section id="home">
        <h1>Welcome</h1>
        <p>This is the official website of Getachew Ambaye, a dedicated researcher and a PhD candidate in Industrial Systems and Manufacturing Engineering. Feel free to explore my work and connect with me.</p>
    </section>

    <section id="about">
        <h1>About Me</h1>
        <p>I am Getachew Ambaye, a PhD candidate in Industrial and Manufacturing Engineering at Wichita State University, with a Master’s and Bachelor’s degree from Jimma Institute of Technology. I currently work as a Direct Graduate Teaching Assistant and an Engineering Professor at Hesston College, focusing on machine design and engineering graphics. My research interests include soft robotics and machine learning applications, resulting in multiple publications. I have led various industry projects, such as designing equipment for the Amhara Dairy Platform and conducting frequency analysis for milling machines. I am open to collaboration opportunities and positions in academia and industry to drive innovation in engineering.</p>
    </section>

    <section id="education-experience">
        <h1>Education</h1>
        <ul>
            <li>PhD in Industrial Systems and Manufacturing Engineering, Wichita State University (2024-)</li>
            <li>MSc in Mechanical Design Engineering, Jimma University (2020)</li>
            <li>BSc in Mechanical Engineering, Jimma University (2016)</li>
        </ul>
    </section>

    <section id="teaching-experience">
        <h1>Teaching Experience</h1>
        <ul>
            <li><strong>Wichita State University (WSU)</strong> - Direct Graduate Teaching Assistant (2022-)</li>
            <li><strong>Hesston College</strong> - Engineering Professor (2024-)</li>
            <li><strong>Bahir Dar Institute of Technology (BiT)</strong> - Lecturer (2020-2022)</li>
            <li><strong>Jimma Institute of Technology (JiT)</strong> - Lecturer (2016-2020)</li>
        </ul>

        <div class="read-more" onclick="toggleDetails()">Read More</div>
        <div class="additional-details content">
            <p><strong>2022–Present Direct Graduate Teaching Assistance (GTA) and GRA, WSU, Wichita, KS, USA</strong></p>
            <ul>
                <li>IME 222, Engineering Graphics (3 Semesters, Summer 2023, Fall 2023, Spring 2024)</li>
                <li>IME 222L, Engineering Graphics Lab (3DX & CATIA V5) (for 2 semesters, Spring 2023, Fall 2024)</li>
                <li>IME 425, Kinematics and Dynamics Design (as GTA), (1 Semester, Fall 2022)</li>
            </ul>
            <p><strong>2024–Present Engineering Professor, Hesston College, Hesston, KS, USA</strong></p>
            <ul>
                <li>ENGR 422, Design of Machines (1 Semester, Fall 2024)</li>
                <li>ENGR 477, Senior Design Capstone Project I (1 Semester, Fall 2024)</li>
                <li>ENGR 372, Mechatronic System Design</li>
                <li>ENGR 371, Fundamentals of Mechatronics</li>
                <li>ENGR 478, Senior Design Capstone Project II</li>
            </ul>
            <p><strong>2021–2022 Gust Lecturer/Trainer, Ethio Engineering Group (EEG), Addis Ababa, Ethiopia</strong></p>
            <ul>
                <li>Product Design and Development: Module 1</li>
                <li>Stress Analysis and Product Modelling: Module 2</li>
            </ul>
            <p><strong>2020–2022 Lecturer, Bahir Dar Institute of Technology (BiT), Bahir Dar, Ethiopia</strong></p>
            <ul>
                <li>Material Handling Equipment Design (3 Semesters)</li>
                <li>Strength of Materials I (1 Semester)</li>
                <li>Strength of Materials II (1 Semester)</li>
                <li>Auto CAD (2 Semesters)</li>
                <li>Engineering Drawing (1 Semester)</li>
            </ul>
            <p><strong>2016-2020 Assistant Lecturer - Lecturer, Jimma Institute of Technology (JiT), Jimma, Ethiopia</strong></p>
            <ul>
                <li>Engineering Design (4 Semesters)</li>
                <li>Mechanics of Materials (2 Semesters)</li>
                <li>Manufacturing Technology (1 Semester)</li>
            </ul>
        </div>
    </section>

    <section id="publications">
        <h1>Publications</h1>
        <ul>
            <li>Title: "Application of Soft Robotics in Rehabilitation Engineering" <strong>Journal of Robotics and Automation (2023)</strong></li>
            <li>Title: "Design of an Adaptive Gripper for Soft Robotics" <strong>International Journal of Advanced Robotics (2022)</strong></li>
            <li>Title: "Implementation of Machine Learning in Predictive Maintenance" <strong>Journal of Industrial Engineering (2021)</strong></li>
        </ul>
    </section>

    <section id="contact">
        <h1>Contact Me</h1>
        <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" placeholder="Your Message" required></textarea>
            <input type="submit" value="Send">
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Getachew Ambaye. All rights reserved.</p>
        <div class="social-media">
            <a href="https://github.com/yourusername">GitHub</a>
            <a href="https://twitter.com/yourusername">Twitter</a>
            <a href="https://linkedin.com/in/yourusername">LinkedIn</a>
        </div>
    </footer>

    <script>
        function toggleDetails() {
            const content = document.querySelector('.additional-details');
            content.style.display = content.style.display === 'block' ? 'none' : 'block';
        }
    </script>
</body>

</html>
