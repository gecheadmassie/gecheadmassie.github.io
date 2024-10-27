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
            margin: 5px;
            padding: 10px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            width: calc(100% - 5px);
            text-align: justify;
        }

        /* Fancy title styles */
        h1 {
            font-family: 'Georgia', serif;
            font-size: 2em;
            color: #fff;
            text-align: center;
            background-color: #1626af;
            padding: 10px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
        }

        #about {
            background-color: #e0f7fa;
        }

        #education-experience {
            background-color: #ffe0b2;
        }

        #teaching-experience {
            background-color: #fff3e0;
        }

        #publications {
            background-color: #c8e6c9;
        }

        #contact {
            background-color: #fff3e0;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #1626af;
            color: white;
        }

        .social-media a {
            color: white;
            text-decoration: none;
            margin: 0 10px;
            transition: color 0.3s;
        }

        .social-media a:hover {
            color: #ffeb3b;
        }

        form {
            display: flex;
            flex-direction: column;
            max-width: 400px;
            margin: 0 auto;
        }

        input[type="text"],
        input[type="email"] {
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        input[type="submit"] {
            padding: 10px;
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
                padding: 5px;
            }
        }

        /* Expandable section styles */
        .section {
            margin: 10px 0;
        }

        .content {
            display: none; /* Hidden by default */
            padding-left: 20px; /* Indent the content */
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
                <li><a href="#projects-community-service">Projects & Community Service</a></li>
                <li><a href="#publications">Publications</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </div>

    <section id="home">
        <h1>Welcome</h1>
        <p>Welcome to the official website of Getachew Ambaye, where you can delve into my work and connect with me professionally. I am passionate about advancing knowledge in the field of engineering.</p>
    </section>

    <section id="about">
        <h1>About Me</h1>
        <p>I am a dedicated PhD candidate specializing in Industrial and Manufacturing Engineering at Wichita State University. With a background in mechanical design, my focus is on innovative solutions in engineering, machine learning, and robotics.</p>
    </section>

    <section id="education-experience">
        <h1>Education</h1>
        <p>I hold a PhD in Industrial Systems and Manufacturing Engineering from Wichita State University (2024), a Master's in Mechanical Design Engineering (2020), and a Bachelor's in Mechanical Engineering (2016), both from Jimma University.</p>
    </section>

    <section id="teaching-experience">
        <h1>Teaching Experience</h1>
        <div class="section">
            <h3 class="toggle">Wichita State University (WSU) - Direct Graduate Teaching Assistant (2022-)</h3>
            <div class="content">
                <p>As a Direct Graduate Teaching Assistant at WSU, I engage students in practical engineering problems, facilitating hands-on learning and guiding them through complex concepts.</p>
            </div>
        </div>
        <div class="section">
            <h3 class="toggle">Hesston College - Engineering Professor (2024-)</h3>
            <div class="content">
                <p>At Hesston College, I teach various engineering courses, encouraging students to apply theoretical knowledge to real-world challenges in engineering design.</p>
            </div>
        </div>
        <div class="section">
            <h3 class="toggle">Bahir Dar Institute of Technology (BiT) - Lecturer (2020-2022)</h3>
            <div class="content">
                <p>During my time at BiT, I delivered lectures on critical engineering principles, focusing on student engagement and practical applications.</p>
            </div>
        </div>
        <div class="section">
            <h3 class="toggle">Jimma Institute of Technology (JiT) - Lecturer (2016-2020)</h3>
            <div class="content">
                <p>As a lecturer at JiT, I designed and taught engineering courses, mentoring students in their academic pursuits and research projects.</p>
            </div>
        </div>

        <div class="read-more" onclick="toggleDetails()">Read More</div>
        <div class="additional-details content">
            <p><strong>2022–Present Direct Graduate Teaching Assistance (GTA) and GRA, WSU, Wichita, KS, USA</strong></p>
            <ul>
                <li>IME 222, Engineering Graphics (3 Semesters)</li>
                <li>IME 222L, Engineering Graphics Lab (3DX & CATIA V5) (for 2 semesters)</li>
                <li>IME 425, Kinematics and Dynamics Design (as GTA) (1 Semester)</li>
            </ul>
            <p><strong>2024–Present Engineering Professor, Hesston College, Hesston, KS, USA</strong></p>
            <ul>
                <li>ENGR 422, Design of Machines (1 Semester)</li>
                <li>ENGR 477, Senior Design Capstone Project I (1 Semester)</li>
                <li>ENGR 372, Mechatronic System Design</li>
                <li>ENGR 371, Fundamentals of Mechatronics</li>
                <li>ENGR 478, Senior Design Capstone Project II</li>
            </ul>
            <p><strong>2021–2023 Engineering Lecturer, Bahir Dar Institute of Technology, Bahir Dar, Ethiopia</strong></p>
            <ul>
                <li>Introduction to Engineering, Fluid Mechanics, Thermal Engineering</li>
                <li>Mechanics of Materials</li>
            </ul>
            <p><strong>2016–2020 Engineering Lecturer, Jimma Institute of Technology, Jimma, Ethiopia</strong></p>
            <ul>
                <li>Introduction to Engineering Design</li>
                <li>Engineering Mathematics</li>
                <li>Machine Design</li>
            </ul>
        </div>
    </section>

    <section id="projects-community-service">
        <h1>Projects & Community Service</h1>
        <p>Throughout my career, I have actively engaged in various projects and community service initiatives aimed at enhancing educational resources and promoting STEM fields among underrepresented groups.</p>
    </section>

    <section id="publications">
        <h1>Publications</h1>
        <p>My research has been published in various esteemed journals, contributing to advancements in engineering methodologies and practices.</p>
    </section>

    <section id="contact">
        <h1>Contact Me</h1>
        <form action="#" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="4" required></textarea>

            <input type="submit" value="Send Message">
        </form>
    </section>

    <footer>
        <p>Connect with me on:</p>
        <div class="social-media">
            <a href="https://www.linkedin.com/in/getachew-ambaye/">LinkedIn</a>
            <a href="https://github.com/getachew-ambaye">GitHub</a>
            <a href="https://twitter.com/getachew_ambaye">Twitter</a>
        </div>
    </footer>

    <script>
        // JavaScript for toggle functionality
        const toggles = document.querySelectorAll('.toggle');
        toggles.forEach(toggle => {
            toggle.addEventListener('click', () => {
                const content = toggle.nextElementSibling;
                content.style.display = content.style.display === 'none' || content.style.display === '' ? 'block' : 'none';
            });
        });

        function toggleDetails() {
            const details = document.querySelector('.additional-details');
            details.style.display = details.style.display === 'none' || details.style.display === '' ? 'block' : 'none';
        }
    </script>
</body>

</html>
