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
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            width: calc(100% - 5px);
            text-align: justify;
        }

        #about {
            background-color: #e0f7fa;
        }

        #education-experience {
            background-color: #ffe0b2;
        }

        #teaching-experience {
            background-color: #e1bee7;
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
                <li><a href="#education-experience">Education Experience</a></li>
                <li><a href="#teaching-experience">Teaching Experience</a></li>
                <li><a href="#projects-community-service">Projects & Community Service</a></li>
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
        <h1>Education Experience</h1>
        <p>PhD in Industrial Systems and Manufacturing Engineering at Wichita State University (2024)</p>
        <p>MSc. in Mechanical Design Engineering at Jimma University (2020)</p>
        <p>BSc. in Mechanical Engineering at Jimma University (2016)</p>
    </section>

    <section id="teaching-experience">
        <h1>Teaching Experience</h1>
        <div class="section">
            <h3 class="toggle">Wichita State University (WSU) - Direct Graduate Teaching Assistant (2022-)</h3>
            <div class="content">
                <p>Details about my role and responsibilities as a Direct Graduate Teaching Assistant...</p>
            </div>
        </div>
        <div class="section">
            <h3 class="toggle">Hesston College - Engineering Professor (2024-)</h3>
            <div class="content">
                <p>Details about my role and responsibilities as an Engineering Professor...</p>
            </div>
        </div>
        <div class="section">
            <h3 class="toggle">Bahir Dar Institute of Technology (BiT) - Lecturer (2020-2022)</h3>
            <div class="content">
                <p>Details about my role and responsibilities as a Lecturer at BiT...</p>
            </div>
        </div>
        <div class="section">
            <h3 class="toggle">Jimma Institute of Technology (JiT) - Lecturer (2016-2020)</h3>
            <div class="content">
                <p>Details about my role and responsibilities as a Lecturer at JiT...</p>
            </div>
        </div>
        
        <div class="read-more" onclick="toggleDetails()">Read More</div>
        <div class="additional-details content">
            <p> 2022–Present Direct Graduate Teaching Assistance (GTA) and GRA, WSU, Wichita, KS, USA </p>
            <ul style="padding: 0; list-style-type: disc; list-style-position: inside;">
            <li>  IME 222, Engineering Graphics (3 Semesters, (Summer 2023, Fall 2023, Spring 2024))<li> 
            <li>  IME 222L, Engineering Graphics Lab (3DX & CATIA V5) (for 2 semesters, (Spring 2023,Fall 2024))<li> 
            <li>  IME 425, Kinematics and Dynamics Design (as GTA), (1 Semester, (Fall 2022))<li> 
            <ul>
        </div>
    </section>

    <section id="projects-community-service">
        <h1>Company & Community Projects</h1>
        <ul style="padding: 0; list-style-type: disc; list-style-position: inside;">
            <li>Design and development of a small CAM analyzer including the programming.</li>
            <li>Natural and Forced Frequency Analysis for 3-Axis Milling Machine to Improve Stiffness, presented at Advanced Manufacturing Processes in WSU, 2023.</li>
            <li>Potato Processing Plant Facility Planning and Design for BiT, 2022.</li>
            <li>Product design and Stress analysis using ANSYS for Ethio-Engineering Group, 2021.</li>
            <li>Micro-dairy equipment Design for the Amhara Dairy Platform, 2021.</li>
            <li>Design of HDPE & PVC pipe puller machine for Amhara Pipe Factory, 2020.</li>
        </ul>
    </section>

    <section id="publications">
        <h1>Publications</h1>
        <ul style="padding: 0; list-style-type: disc; list-style-position: inside;">
            <li>Soft Robot Design, Fabrication, and Control. <i>IEEE/ASME Transactions on Mechatronics</i>, 28(4), 2023. <a href="https://doi.org/10.1109/TMECH.2023.3231942" target="_blank">DOI: 10.1109/TMECH.2023.3231942</a></li>
            <li>Vibration-Based Damage Detection of Robot Arm Using Machine Learning. <i>Journal of Intelligent & Robotic Systems</i>. <a href="https://doi.org/10.1007/s10846-023-01818-3" target="_blank">DOI: 10.1007/s10846-023-01818-3</a></li>
            <li>Robot arm damage detection using vibration data and deep learning. <i>Neural Comput & Applic.</i> 36 (pp. 1727-1739) 2024. <a href="https://doi.org/10.1007/s00521-023-09150-3" target="_blank">DOI: 10.1007/s00521-023-09150-3</a></li>
            <li>Detection of Small Screws Using Machine Learning. In <i>2023 International Conference on Information and Communication Technology for Development for Africa (ICT4DA)</i> (pp. 13-18). IEEE. <a href="https://doi.org/10.1109/ICT4DA59526.2023.10302258" target="_blank">DOI: 10.1109/ICT4DA59526.2023.10302258</a></li>
            <li>Contact temperature analysis of the classical Geneva mechanism through numerical methods. <i>Materials Today: Proceedings</i>, 57, pp. 545-552. <a href="https://doi.org/10.1016/j.matpr.2022.01.420" target="_blank">DOI: 10.1016/j.matpr.2022.01.420</a></li>
            <li>Numerical Stress Analysis and Fatigue Life Prediction of the Classical External Geneva Mechanism. In <i>International Workshop of Advanced Manufacturing and Automation</i> (pp. 176-186). Singapore: Springer Singapore. <a href="https://doi.org/10.1007/978-981-19-0572-8_23" target="_blank">DOI: 10.1007/978-981-19-0572-8_23</a></li>
            <li>The performance of gear with backlash: A review. <i>Journal of Applied Mechanical Engineering</i>, 10(9), p. 389.</li>
            <li>Numerical comparative modal analysis of connecting rod between fixed crankpin and fixed piston pin. The 8th International Conference on Innovation in Science and Technology, July 23–25, 2021, in Stockholm, Sweden.</li>
            <li>Determination of Important Contact Parameters for Spur Gear Design. <i>TechHub Journal</i>, 1(1), pp. 28-38.</li>
            <li>Effect of backlash on transmission error and time varying mesh stiffness. In <i>International Workshop of Advanced Manufacturing and Automation</i> (pp. 18-28). Singapore: Springer Singapore. <a href="https://doi.org/10.1007/978-981-33-6318-2_3" target="_blank">DOI: 10.1007/978-981-33-6318-2_3</a></li>
            <li>Numerical study of the effect of backlash on flash temperature of spur gear. <i>International Review of Mechanical Engineering (IREME)</i> 14, no. 11 (2020). <a href="http://dx.doi.org/10.15866/ireme.v14i11.19763" target="_blank">DOI: http://dx.doi.org/10.15866/ireme.v14i11.19763</a></li>
            <li>Dynamic analysis of spur gear with backlash using ADAMS. <i>Materials Today: Proceedings</i>, 38, pp. 2959-2967. <a href="https://doi.org/10.1016/j.matpr.2020.09.309" target="_blank">DOI: 10.1016/j.matpr.2020.09.309</a></li>
            <li>Short Descriptions of Measurements and Instrumentation. <i>Int J Eng Res Technol</i>, 9 (12).</li>
            <li>Time and frequency domain analysis of signals: a review. <i>Int J Eng Res Technol</i> 9: 271–276.</li>
        </ul>
    </section>

    <section id="contact">
        <h1>Contact Me</h1>
        <div class="contact-container">
            <form action="/contact" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <input type="submit" value="Submit">
            </form>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Getachew Ambaye</p>
        <div class="social-media">
            <a href="//linkedin.com/in/getachew-ambaye" target="_blank">LinkedIn</a>
            <a href="https://github.com/gecheadmassie" target="_blank">GitHub</a>
            <a href="mailto:gecheadmassie@gmail.com">Email</a>
        </div>
    </footer>

    <script>
        function toggleContent(element) {
            const content = element.nextElementSibling;
            if (content.style.display === "block") {
                content.style.display = "none";
            } else {
                content.style.display = "block";
            }
        }

        function toggleDetails() {
            const additionalDetails = document.querySelector('.additional-details');
            if (additionalDetails.style.display === "block") {
                additionalDetails.style.display = "none";
            } else {
                additionalDetails.style.display = "block";
            }
        }
    </script>
</body>

</html>
