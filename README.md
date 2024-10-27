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
            padding: 2.55px;
            border-top-left-radius: 20px;
            border-bottom-left-radius: 20px;
            border-top-right-radius: 0px;
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
            padding: 5px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            width: calc(100% - 5px);
            text-align: justify;
        }

        #about {
            background-color: #e0f7fa;
        }

        #education-experience {
            background-color: #fff3e0;
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
        input[type="email"] {
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
            <li><strong>Soft Robot Design, Manufacturing, and Operation Challenges: A Review. </strong><i>Neural Comput & Applic.</i> 8(2), 79, 2024. <a                 
             href="https://doi.org/10.3390/jmmp8020079" target="_blank">DOI: 10.3390/jmmp8020079</a></li>
             <p> Advancements in smart manufacturing have embraced the adoption of soft robots for improved productivity, flexibility, and automation as well as safety in smart factories. Hence, soft robotics is seeing a significant surge in popularity by garnering considerable attention from researchers and practitioners. Bionic soft robots, which are composed of compliant materials like silicones, offer compelling solutions to manipulating delicate objects, operating in unstructured environments, and facilitating safe human–robot interactions. However, despite their numerous advantages, there are some fundamental challenges to overcome, which particularly concern motion precision and stiffness compliance in performing physical tasks that involve external forces. In this regard, enhancing the operation performance of soft robots necessitates intricate, complex structural designs, compliant multifunctional materials, and proper manufacturing methods. The objective of this literature review is to chronicle a comprehensive overview of soft robot design, manufacturing, and operation challenges in conjunction with recent advancements and future research directions for addressing these technical challenges. <p>


             
            <li>Robot arm damage detection using vibration data and deep learning. <i>Neural Comput & Applic.</i> 36 (pp. 1727-1739) 2024. <a     
             href="https://doi.org/10.1007/s00521-023-09150-3" target="_blank">DOI: 10.1007/s00521-023-09150-3</a></li>
            <li>Detection of Small Screws Using Machine Learning. In <i>2023 International Conference on Information and Communication Technology for Development for 
             Africa (ICT4DA)</i> (pp. 13-18). IEEE. <a href="https://doi.org/10.1109/ICT4DA59526.2023.10302258" target="_blank">DOI: 10.1109/ICT4DA59526.2023.10302258</a></li>
            <li>Contact temperature analysis of the classical Geneva mechanism through numerical methods. <i>Materials Today: Proceedings</i>, 57, pp. 545-552. <a 
              href="https://doi.org/10.1016/j.matpr.2022.01.420" target="_blank">DOI: 10.1016/j.matpr.2022.01.420</a></li>
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

    <section id="company-community-service-projects">
        <h1>Company & Community Service Projects</h1>
        <ul>
            <li>Design and development of a small CAM analyzer including the programming</li>
            <li>Natural and Forced Frequency Analysis for 3-Axis Milling Machine to Improve Stiffness, presented at Advanced Manufacturing Processes in WSU, 2023.</li>
            <li>Potato Processing Plant Facility Planning and Design for BiT, 2022</li>
            <li>Product design and Stress analysis using ANSYS for Ethio-Engineering Group, 2021.</li>
            <li>Micro-dairy equipment Design for the Amhara Dairy Platform, 2021</li>
            <li>Design of HDPE & PVC pipe puller machine for Amhara Pipe Factory, 2020</li>
            <li>Degradation on Energy Conversion, 2020</li>
        </ul>
    </section>

    <section id="contact">
        <h1>Contact Me</h1>
        <form action="https://formspree.io/f/mkgnobej" method="POST">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" placeholder="Your Message" required></textarea>
            <input type="submit" value="Send">
        </form>
    </section>



<footer style="background-color: #2c3e50; color: white; padding: 20px; text-align: center;">
    <p>© 2024 Getachew Ambaye. All rights reserved.</p>
    
    <div class="social-media" style="margin: 10px 0;">
        <a href="https://www.linkedin.com/in/getachew-ambaye" target="_blank" style="margin-right: 15px; color: white; text-decoration: none;">LinkedIn</a>
        <a href="https://github.com/gecheadmassie" target="_blank" style="color: white; text-decoration: none;">GitHub</a>
        <p style="display: inline; margin-left: 20px;">
            <a href="#home" style="color: white; text-decoration: underline;">Home</a>
        </p>
    </div>
    
    <div style="margin-top: 20px;">
        <p style="font-weight: bold;">Connect with me:</p>
        <p>
            <a href="https://scholar.google.com/citations?user=YOUR_PROFILE_ID" target="_blank" style="color: white; text-decoration: none;">Google Scholar</a> |
            <a href="https://www.researchgate.net/profile/Getachew-Ambaye" target="_blank" style="color: white; text-decoration: none;">ResearchGate</a> |
            <a href="https://orcid.org/0000-0003-4197-0188" target="_blank" style="color: white; text-decoration: none;">ORCID</a> |
            <a href="https://www.webofscience.com/wos/author/record/AAO-1275-2021" target="_blank" style="color: white; text-decoration: none;">PubLoons</a>
        </p>
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
