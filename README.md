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
            color: #333;
        }

        .header-container {
            display: flex;
            align-items: center;
            justify-content: flex-start;
            background-color: #1626af;
            padding: 10px;
            border-radius: 20px 20px 0 0;
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
            padding: 10px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            text-align: justify;
        }

        #about {
            background-color: #e0f7fa;
        }

        #education-experience,
        #teaching-experience,
        #contact {
            background-color: #fff3e0;
        }

        #publications {
            background-color: #c8e6c9;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #1626af;
            color: white;
        }

        .read-more {
            color: #1626af;
            cursor: pointer;
            text-decoration: underline;
            margin-top: 10px;
        }

        .content {
            display: none; /* Hidden by default */
            padding-left: 20px; /* Indent the content */
        }

        /* Responsive styles */
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
            }
        }
    </style>
</head>

<body>

    <div class="header-container">
        <img src="Photo.jpg" alt="Getachew Ambaye" class="profile-pic" style="border-radius: 50%; width: 150px; height: 150px; object-fit: cover; margin-right: 10px;">
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
        <p>
            <a href="Resume.pdf" target="_blank">Download Resume</a> | 
            <a href="CV.pdf" target="_blank">Download CV</a>
        </p>
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
            <li>
                <strong>Wichita State University (WSU)</strong> - Direct Graduate Teaching Assistant (2022-)
            </li>
            <li>
                <strong>Hesston College</strong> - Engineering Professor (2024-)
            </li>
            <li>
                <strong>Bahir Dar Institute of Technology (BiT)</strong> - Lecturer (2020-2022)
            </li>
            <li>
                <strong>Jimma Institute of Technology (JiT)</strong> - Lecturer (2016-2020)
            </li>
        </ul>
        
        <div class="read-more" onclick="toggleDetails(this)">Read More</div>
        <div class="content">
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
            <li>
                <strong style="font-size: 1.1em;">Soft Robot Design, Manufacturing, and Operation Challenges: A Review.</strong>
                                <i>J. Manuf. Mater. Process.</i> 8(2), 79, 2024. 
                                <a href="https://doi.org/10.3390/jmmp8020079" target="_blank">DOI</a>
                                
          <div class="read-more" onclick="toggleDetails(this)">Read More</div>
                <div class="content">
            <p> <em>Advancements in smart manufacturing have embraced the adoption of soft robots for improved productivity, flexibility, and automation as well as safety in smart factories. Hence, soft robotics is seeing a significant surge in popularity by garnering considerable attention from researchers and practitioners. Bionic soft robots, which are composed of compliant materials like silicones, offer compelling solutions to manipulating delicate objects, operating in unstructured environments, and facilitating safe human–robot interactions. However, despite their numerous advantages, there are some fundamental challenges to overcome, which particularly concern motion precision and stiffness compliance in performing physical tasks that involve external forces. In this regard, enhancing the operation performance of soft robots necessitates intricate, complex structural designs, compliant multifunctional materials, and proper manufacturing methods. The objective of this literature review is to chronicle a comprehensive overview of soft robot design, manufacturing, and operation challenges in conjunction with recent advancements and future research directions for addressing these technical challenges.</em>
                                </p>
                </div>




    
                <strong>Soft Robot Design, Manufacturing, and Operation Challenges: A Review.</strong>
                <i>J. Manuf. Mater. Process.</i> 8(2), 79, 2024.
            </li>
            <li>
                <strong>Mechanical System Design with a focus on Renewable Energy Sources.</strong>
                <i>Renewable Energy</i> 56(4), 167-175, 2023.
            </li>
            <li>
                <strong>Machine Learning in Engineering: Applications and Future Directions.</strong>
                <i>Journal of Engineering</i> 12(1), 34-45, 2022.
            </li>
        </ul>
        
        <div class="read-more" onclick="toggleDetails(this)">Read More</div>
        <div class="content">
            <p><strong>2024</strong> Getachew Ambaye, "Soft Robot Design, Manufacturing, and Operation Challenges: A Review," <i>Journal of Manufacturing Materials and Processing</i>, vol. 8, no. 2, 79.</p>
            <p><strong>2023</strong> Getachew Ambaye, "Mechanical System Design with a focus on Renewable Energy Sources," <i>Renewable Energy</i>, vol. 56, pp. 167-175.</p>
            <p><strong>2022</strong> Getachew Ambaye, "Machine Learning in Engineering: Applications and Future Directions," <i>Journal of Engineering</i>, vol. 12, no. 1, pp. 34-45.</p>
        </div>
    </section>

    <section id="contact">
        <h1>Contact</h1>
        <p>Email: <a href="mailto:getachew.ambaye@example.com">getachew.ambaye@example.com</a></p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/getachew-ambaye" target="_blank">LinkedIn Profile</a></p>
    </section>

    <footer>
        <p>&copy; 2024 Getachew Ambaye. All rights reserved.</p>
    </footer>

    <script>
        function toggleDetails(element) {
            const content = element.nextElementSibling;
            if (content.style.display === "block") {
                content.style.display = "none";
                element.textContent = "Read More";
            } else {
                content.style.display = "block";
                element.textContent = "Read Less";
            }
        }
    </script>
</body>

</html>
