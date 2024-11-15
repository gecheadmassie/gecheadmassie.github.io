
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Official website of Getachew Ambaye, a researcher in Engineering. Explore my teaching experience, publications, and contact information.">
    <meta name="keywords" content="Getachew Ambaye, Engineering, Teaching, Research, Publications">
    <title>Getachew Ambaye - PhD Candidate and Researcher</title>
    <style>
        body {
            margin: 20px;
            font-family: Arial, sans-serif;
            color: #333;
        }

p {
    margin: 15px 0; /* Margin for paragraphs */
    padding-left: 20px; /* Optional: Padding for list indentation */
    padding-right: 20px; /* Optional: Padding for list indentation */
}

ul, ol {
    margin: 15px 0; /* Margin for unordered and ordered lists */
    padding-left: 20px; /* Optional: Padding for list indentation */
    padding-right: 20px; /* Optional: Padding for list indentation */
}

        .header-container {
            display: flex;
            align-items: center;
            justify-content: flex-start;
            background-color: #1626af;
            padding: 1px;
            border-radius: 750px 0px  0px  0px;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
            display: flex;
            margin: 10px; for the discription 
            color: white;
        }

        nav ul li {
            margin: 5px 5px;
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
    padding: 5px 10px;  /* Adds padding to the text */
    border: 2px solid #1626af;  /* Creates a border around the text */
    border-radius: 5px;  /* Optional: gives the box rounded corners */
    background-color: #f0f8ff;  /* Optional: gives a light background to the box */
    display: inline-block;  /* Ensures the padding and border don't break the flow */
    transition: background-color 0.3s ease, border-color 0.3s ease;  /* Adds smooth transition effects */
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
            padding-right: 20px; /* Indent the content */
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
                margin: 20px;
            }
        }
    </style>
    <script>
        function toggleDetails(element) {
            const content = element.nextElementSibling;
            if (content.style.display === "block") {
                content.style.display = "none";
            } else {
                content.style.display = "block";
            }
        }
    </script>



    <script>
        function toggleDetails(element) {
            const content = element.nextElementSibling;
            if (content.style.display === "none" || content.style.display === "") {
                content.style.display = "block"; // Show the content
                element.textContent = "Show Less"; // Change text to "Less"
            } else {
                content.style.display = "none"; // Hide the content
                element.textContent = "Read More"; // Change text to "Read More"
            }
        }
    </script>
    <style>
            /* Style for the toggle button */
            .toggle-btn {
                background-color: #1E90FF;
                color: white;
                padding: 10px 20px;
                cursor: pointer;
                border: none;
                border-radius: 5px;
                font-size: 16px;
                margin: 10px 0;
            }
    
            /* Initially hide the PDF content */
            .pdf-container {
                display: none;
                margin-top: 20px;
            }
    
            /* Embed styles for better control */
            .pdf-container iframe {
                width: 100%;
                height: 600px;
                border: none;
                border-radius: 8px;
                box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            }
        </style>

        <script>
        function togglePDF() {
            const pdfContainer = document.getElementById("pdf-container");
            const toggleButton = document.querySelector(".toggle-btn");

            // Toggle the visibility of the PDF container
            if (pdfContainer.style.display === "none" || pdfContainer.style.display === "") {
                pdfContainer.style.display = "block";
                toggleButton.textContent = "Show Less";
            } else {
                pdfContainer.style.display = "none";
                toggleButton.textContent = "Read More";
            }
        }
    </script>


    
</head>

<body>

    <div class="header-container">
        <img src="Photo.jpg" alt="Getachew Ambaye" class="profile-pic" style="border-radius: 100%; width: 75px; height: 75px; object-fit: cover; margin-right: 5px;">
        <nav>
            <ul>
                
                <li><a href="#about">About</a></li>
                <li><a href="#education-experience">Education</a></li>
                <li><a href="#teaching-experience">Teaching Experience</a></li>
                <li><a href="#company-community-service-projects">Projects & Community Service</a></li>
                <li><a href="#publications">Publications</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </div>


<style>
    .header-container nav ul li a {
        font-size: 1.05em; /* Increase font size */
        font-weight: bold; /* Optional: Make text bold */
        color: white; /* Ensure text color is white */
    }

    /* Other existing styles */
</style>



    <section id="home">
        <h1>Welcome</h1>
        <p>This is the official website of Getachew Ambaye,  a PhD candidate and Reserecher in Industrial Systems and Manufacturing Engineering. Feel free to explore my work and connect with me.</p>
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
            <p><strong>2021–2022 Guest Lecturer/Trainer, Ethio Engineering Group (EEG), Addis Ababa, Ethiopia</strong></p>
            <ul>
                <li>Product Design and Development: Module 1</li>
                <li>Stress Analysis and Product Modelling: Module 2</li>
            </ul>
            <p><strong>2020–2022 Lecturer, Bahir Dar Institute of Technology (BiT), Bahir Dar, Ethiopia</strong></p>
            <ul>
                <li>Material Handling Equipment Design (3 Semesters)</li>
                <li>Strength of Materials I (1 Semester)</li>
                <li>Strength of Materials II (1 Semester)</li>
                <li>AutoCAD (2 Semesters)</li>
                <li>Engineering Drawing (1 Semester)</li>
            </ul>
            <p><strong>2016-2020 Assistant Lecturer - Lecturer, Jimma Institute of Technology (JiT), Jimma, Ethiopia</strong></p>
            <ul>
                <li>Mechanism of Machinery (1 Semester)</li>
                <li>Design of Machine Elements (1 Semester)</li>
                <li>Maintenance of Machinery (1 Semester)</li>
                <li>Material Handling Equipment (1 Semester)</li>
                <li>Strength of Materials II (2 Semesters)</li>
                <li>AutoCAD (2 Semesters)</li>
                <li>Dynamics (1 Semester)</li>
            </ul>
        </div>
    </section>






    <style>
        /* Flex container for image-text pairing */
        .content-row {
            display: flex;
            align-items: flex-start; /* Align images and text at the top */
            margin-bottom: 100px; /* Spacing between rows */
            gap: 20px; /* Space between image and text columns */
        }

        /* Column for image */
        .image-column {
            flex: 2; /* The image takes up more space (increased from 1 to 2) */
            max-width: 100%; /* Ensure the image container doesn't overflow */
        }

        /* Column for text */
        .text-column {
            flex: 1; /* The text takes up less space (increased from 2 to 1) */
            font-size: 14px; /* Standard font size for the text */
            line-height: 1.5; /* Spacing between lines of text */
            color: #333; /* Dark gray text for better contrast */
            max-width: 300px; /* Limit the width of the text container */
        }

        /* Make the images more flexible */
        .image-column img {
            height: auto; /* Keep aspect ratio */
            border-radius: 8px; /* Slightly rounded corners */
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1); /* Subtle shadow for depth */
        }

        /* Small blue text styling */
        .small-blue-text {
            color: #1E90FF; /* Blue color for descriptions */
            font-size: 14px; /* Font size for description */
            line-height: 1.4; /* Tighter line height */
            margin-top: 10px; /* Space between image and text */
        }

        /* Custom classes for image sizes */
        .image-small {
            width: 200px; /* Example small image */
        }

        .image-medium {
            width: 500px; /* Example medium image */
        }

        .image-large {
            width: 800px; /* Example large image */
        }
    </style>

    
       <section id="company-community-service-projects">
        <h1>Professional Experience and Projects</h1>
        <ul>
            <li> <strong>Industry 4.0 Lab, WSU, Wichita, KS (2022-present)</strong></li>
            <p><em>Graduate Research Assistant </em></p>
            <ul>
                <li> Predicting the Working Space of a Pneumatic Soft Actuator Using Deep Learning.</li>

            <li> 
                Soft Robot Design, Manufacturing, and Operation Challenges: A Review
                <div class="read-more" onclick="toggleDetails(this)">Read More</div>
                <div class="extra-content" style="display:none;">
                <!-- Content Row with Image and Text -->
                    <div class="content-row">
                        <div class="text-column">
                            <span class="small-blue-text">Key technical challenges in soft robotics.</span>
                        </div>
                        <div class="image-column">
                            <img src="Review/Picture6.png" width="850" alt="Image 1">
                        </div>
                    </div>

                    <div class="content-row">
                        <div class="text-column">
                            <span class="small-blue-text">The figure below presents FEA simulation models of a pneumatic soft actuator design that is inspired by an elephant trunk.</span>
                        </div>
                        <div class="image-column">
                            <img src="Review/Picture1.png" width="850" alt="Image 1">
                        </div>
                    </div>

                    <div class="content-row">
                        <div class="text-column">
                            <span class="small-blue-text">The pie chart of soft material usages documented in the selected literature. These materials are mostly used as structural elements, but soft materials with electromagnetic properties may also facilitate sensing and control.</span>
                        </div>
                        <div class="image-column">
                            <img src="Review/Picture2.png" width="850" alt="Image 2">
                        </div>
                    </div>

                    <div class="content-row">
                        <div class="text-column">
                            <span class="small-blue-text">The figure below shows an illustration of multi-material 3D printing that uses restricting and actuating materials along with certain design parameter settings, such as A, B, C, D, and E, to fabricate bio-inspired flexible parts with self-shaping properties.</span>
                        </div>
                        <div class="image-column">
                            <img src="Review/Picture4.png" width="850" alt="Image 4">
                        </div>
                    </div>

                    <div class="content-row">
                        <div class="text-column">
                            <span class="small-blue-text">The figure below presents the illustrations of common soft actuator functions and their stimuli.</span>
                        </div>
                        <div class="image-column">
                            <img src="Review/Picture5.png" width="850" alt="Image 5">
                        </div>
                    </div>

                    <div class="content-row">
                        <div class="text-column">
                            <span class="small-blue-text">The figure below presents the movements of a soft actuator with two asymmetric pneumatic chambers. The soft actuator design, left, is inspired by an elephant trunk. The end trajectories of soft actuator movements are illustrated in a reference frame, right. The bending movements are planar.</span>
                        </div>
                        <div class="image-column">
                            <img src="Review/Picture3.png" width="850" alt="Image 3">
                        </div>
                    </div>

                </div>
            </li>

            <li> Detecting Misalignments of Drilled Holes Using Machine Vision.</li>
            
            <li> Robot Arm Damage Detection Using Vibration Data and Deep Learning.</li>
            <div class="read-more" onclick="toggleDetails(this)">Read More</div>
                <div class="extra-content" style="display:none;">
                <!-- Content Row with Image and Text -->
                    <div class="content-row">
                        <div class="text-column">
                            <span class=" Baseline robot link with an open vertical crack</span>
                        </div>
                        <div class="image-column">
                            <img src="Robot_Link/Figure_2.png" width="150" alt="Figure 1">
                        </div>
                    </div>



                        <div class="content-row">
                        <div class="text-column">
                            <span class=" Simulation setup.</span>
                        </div>
                        <div class="image-column">
                            <img src="Robot_Link/Figure_3.png" width="150" alt="Image 1">
                        </div>
                    </div>

                    
                        <div class="content-row">
                        <div class="text-column">
                            <span class=" Planar model with quadrilateral elements.</span>
                        </div>
                        <div class="image-column">
                            <img src="Robot_Link/Figure_4.png" width="150" alt="Image 1">
                        </div>
                    </div>

                            <div class="content-row">
                        <div class="text-column">
                            <span class=" Mesh density convergence.</span>
                        </div>
                        <div class="image-column">
                            <img src="Robot_Link/Figure_5.png" width="150" alt="Image 1">
                        </div>
                    </div>

                            <div class="content-row">
                        <div class="text-column">
                            <span class=" Accelerations of Node 8 and Node 851 in the vertical direction.</span>
                        </div>
                        <div class="image-column">
                            <img src="Robot_Link/Figure_6.png" width="150" alt="Image 1">
                        </div>
                    </div>


                            <div class="content-row">
                        <div class="text-column">
                            <span class=" Feature extraction: a) Raw time series data; b) Polar representation of raw data; c) 2D image data.</span>
                        </div>
                        <div class="image-column">
                            <img src="Robot_Link/Figure_7a.png" width="150" alt="Image 1">
                            <img src="Robot_Link/Figure_7b.png" width="150" alt="Image 1">
                            <img src="Robot_Link/Figure_7c.png" width="150" alt="Image 1">
                        </div>
                    </div>

                     
                            <div class="content-row">
                        <div class="text-column">
                            <span class=" Neural network architecture. Note: ReLU is a rectified linear unit used as an activation function.</span>
                        </div>
                        <div class="image-column">
                            <img src="Robot_Link/Figure_8.png" width="150" alt="Image 1">
                        </div>
                    </div>

                   
                            <div class="content-row">
                        <div class="text-column">
                            <span class="  Vibration mode shapes due to free vibration of intact robot link with one fixed eyelet end.</span>
                        </div>
                        <div class="image-column">
                            <img src="Robot_Link/Figure_9MS1_2.png" width="150" alt="Image 1">
                            <img src="Robot_Link/Figure_9MS3_4.png" width="150" alt="Image 1">
                            <img src="Robot_Link/Figure_9MS5_6.png" width="150" alt="Image 1">
                        </div>
                    </div>

                        <div class="content-row">
                        <div class="text-column">
                            <span class="  Mode shapes, natural frequencies, and cases for robot link crack geometries.</span>
                        </div>
                        <div class="image-column">
                            <img src="Robot_Link/Figure_10a.png" width="150" alt="Image 1">
                            <img src="Robot_Link/Figure_10b.png" width="150" alt="Image 1">
                            <img src="Robot_Link/Figure_10c.png" width="150" alt="Image 1">
                            <img src="Robot_Link/Figure_10d.png" width="150" alt="Image 1">
                            <img src="Robot_Link/Figure_10e.png" width="150" alt="Image 1">
                            <img src="Robot_Link/Figure_10f.png" width="150" alt="Image 1">
                        </div>
                    </div>

                        <div class="content-row">
                        <div class="text-column">
                            <span class=" Confusion matrix for robot link with cracks at different locations. Note: Cr means Crack.</span>
                        </div>
                        <div class="image-column">
                            <img src="Robot_Link/Figure_14.png" width="150" alt="Image 1">
                        </div>
                    </div>

                        <div class="content-row">
                        <div class="text-column">
                            <span class=" Confusion matrix for robot link with different crack sizes.</span>
                        </div>
                        <div class="image-column">
                            <img src="Robot_Link/Figure_16.png" width="150" alt="Image 1">
                        </div>
                    </div>
                    </div></li>


                    
                    
            <li> Detection of Small Screws Using Machine Learning.</li>
        </ul>

        <li> <strong>Wichita State University, Wichita, KS (2022–Present) </strong></li>
        <p><em>Engineering Graphics Instructor</em></p>
        <ul>
            <li> IME 222L (Engineering Graphics lab) using CATIAV5 and 3DX software.</li>
            <li> IME 222(Engineering Graphics lecture) principles of drawings and GD&T</li>
        </ul>

        <li> <strong>Hesston College, Hesston, KS (2024–Present)</strong></li>
        <p><em>Engineering Professor</em></p>
        <ul>
            <li> Design of Machines (ENGR 422) and Senior Design Capstone Project (ENGR 477), Fundamentals of mechatronics, and Mechatronics system design.</li>
        </ul>

        <li> <strong>Advanced Manufacturing Processes Lab, Wichita, KS (2022-2023, 5 months)</strong></li>
        <p><em>Mechanical Design of Machine Tools</em></p>
        <ul>
            <li> 3-axis milling machine stiffness improvement </li> 
            <li> Finite element (FE) stress & deformation analysis using 3DX SIMULIA </li>
            <li> Natural and forced frequencies for different mode-shapes using 3DX SIMULIA </li>
        </ul>

         <!-- Button to trigger the toggle -->
        <button class="toggle-btn" onclick="togglePDF()">Read More</button>

        <!-- Hidden PDF container that will be toggled -->
        <div class="pdf-container" id="pdf-container">
            <iframe src="3XM/Project_1.pdf" alt="PDF File"></iframe>
            <iframe src="3XM/Project_2.pdf" alt="PDF File"></iframe>
            <iframe src="3XM/Project_3.pdf" alt="PDF File"></iframe>
        </div>
                    


        <li><strong>Ethio Engineering Group, Ethiopia (2020–2022, 6 months) </strong></li>
        <p><em>Engineering Product design, and analysis Trainer</em></p>
        <ul>
            <li> Bench grinding machine design and analysis </li> 
            <li> Delivered specialized training modules on product design and stress analysis.</li> 
        </ul>
        <div class="read-more" onclick="toggleDetails(this)">Read More</div>
                <div class="extra-content" style="display:none;">
                  <img src="EEG/Picture73.png" width="850" alt="Image 1">
                    <!-- Content Row with Image and Text -->
                    
                    <div class="content-row">
                        <div class="text-column">
                            <span class="small-blue-text">Static analysis of manual bench gridning machine transmission components</span>
                        </div>
                        <div class="image-column">
                            <img src="EEG/Picture24.png" width="450" alt="Image 1">
                            <img src="EEG/Picture25.png" width="450" alt="Image 1">
                            <img src="EEG/Picture28.png" width="450" alt="Image 1">
                            <img src="EEG/Picture29.png" width="450" alt="Image 1">
                        </div>
                    </div>

                     <div class="content-row">
                        <div class="text-column">
                            <span class="small-blue-text">Dynamic analysis of manual bench griding machine transmission components</span>
                        </div>
                        <div class="image-column">
                            <img src="EEG/Picture32.png" width="350" alt="Image 1">
                            <img src="EEG/Picture31.png" width="150" alt="Image 1">
                            <img src="EEG/Picture32.png" width="150" alt="Image 1">
                            <img src="EEG/Picture33.png" width="150" alt="Image 1">
                            <img src="EEG/Picture34.png" width="150" alt="Image 1">
                            <img src="EEG/Picture35.png" width="150" alt="Image 1">
                            <img src="EEG/Picture36.png" width="150" alt="Image 1">
                            <img src="EEG/Picture37.png" width="150" alt="Image 1">
                        </div>
                    </div>

                           <div class="content-row">
                        <div class="text-column">
                            <span class="small-blue-text">Basics of Manufacturing Process Modelling and Simulation: 1.	Sheet Metal Forming Modeling</span>
                        </div>
                        <div class="image-column">
                            <img src="EEG/Picture38.png" width="350" alt="Image 1">
                            <img src="EEG/Picture39.png" width="150" alt="Image 1">
                            <img src="EEG/Picture40.png" width="150" alt="Image 1">
                            <img src="EEG/Picture41.png" width="150" alt="Image 1">
                            <img src="EEG/Picture42.png" width="150" alt="Image 1">
                            <img src="EEG/Picture43.png" width="150" alt="Image 1">
                            <img src="EEG/Picture44.png" width="150" alt="Image 1">
                            <img src="EEG/Picture45.png" width="150" alt="Image 1">
                        </div>
                    </div>

                           <div class="content-row">
                        <div class="text-column">
                            <span class="small-blue-text">Basics of Manufacturing Process Modelling and Simulation: 2.	Extrusion Modeling</span>
                        </div>
                        <div class="image-column">
                            <img src="EEG/Picture46.png" width="350" alt="Image 1">
                            <img src="EEG/Picture49.png" width="150" alt="Image 1">
                            <img src="EEG/Picture40.png" width="150" alt="Image 1">
                            <img src="EEG/Picture50.png" width="150" alt="Image 1">
                            <img src="EEG/Picture51.png" width="150" alt="Image 1">
                            <img src="EEG/Picture52.png" width="150" alt="Image 1">
                            <img src="EEG/Picture53.png" width="150" alt="Image 1">
                            <img src="EEG/Picture54.png" width="150" alt="Image 1">
                            <img src="EEG/Picture55.png" width="150" alt="Image 1">
                            <img src="EEG/Picture56.png" width="150" alt="Image 1">
                        </div>
                    </div>


                           <div class="content-row">
                        <div class="text-column">
                            <span class="small-blue-text">Basics of Manufacturing Process Modelling and Simulation: 3.	Deep Drawing Modeling</span>
                        </div>
                        <div class="image-column">
                            <img src="EEG/Picture57.png" width="350" alt="Image 1">
                            <img src="EEG/Picture58.png" width="150" alt="Image 1">
                            <img src="EEG/Picture59.png" width="150" alt="Image 1">
                            <img src="EEG/Picture60.png" width="150" alt="Image 1">
                            <img src="EEG/Picture61.png" width="150" alt="Image 1">
                            <img src="EEG/Picture62.png" width="150" alt="Image 1">
                            <img src="EEG/Picture63.png" width="150" alt="Image 1">
                            <img src="EEG/Picture64.png" width="150" alt="Image 1">
                          </div>
                    </div>

                        <div class="content-row">
                        <div class="text-column">
                            <span class="small-blue-text">Basics of Manufacturing Process Modelling and Simulation: 4.	Rolling Modeling</span>
                        </div>
                        <div class="image-column">
                            <img src="EEG/Picture65.png" width="350" alt="Image 1">
                            <img src="EEG/Picture66.png" width="150" alt="Image 1">
                            <img src="EEG/Picture67.png" width="150" alt="Image 1">
                            <img src="EEG/Picture68.png" width="150" alt="Image 1">
                            <img src="EEG/Picture69.png" width="150" alt="Image 1">
                            <img src="EEG/Picture70.png" width="150" alt="Image 1">
                            <img src="EEG/Picture71.png" width="150" alt="Image 1">
                            <img src="EEG/Picture72.png" width="150" alt="Image 1">
                            </div>
                    </div>           
                    
                    </div>

        <li><strong>Potato Processing Plant Facility Planning & Design, BiT, Ethiopia (2021-2022)</strong></li>
        <p><em>Plant layout designer</em></p>
        <ul>
            <li> Potato processing plant layout design using Autodesk Inventor software.</li> 
        </ul>

        <li><strong>Amhara Pipe Factory, Ethiopia (2020-2021)</strong></li>
        <p><em>Machine designer</em></p>
        <ul>
            <li> Design of HDPE and PVC pipe pulling machine</li> 
            <li> Performed analysis to determine the load required to pull pipes from the extrusion process to the final cutter machine, taking into account the load imposed by vacuum tank seals.</li> 
        </ul>

        <li><strong>Micro-Dairy Equipment Design for the Amhara Dairy Platform, Ethiopia (2020-2021, 6 months)</strong></li>
        <p><em>Machine designer</em></p>
        <ul>
            <li> Designed processing equipment to enhance local dairy production.</li> 
        </ul>

        <li><strong>Textile industry (internship) 2015-2016</strong></li>
        <ul>
            <li> Design of machine components</li>
        </ul>
    </ul>
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
                    <p><em>Advancements in smart manufacturing have embraced the adoption of soft robots for improved productivity, flexibility, and automation as well as safety in smart factories. Hence, soft robotics is seeing a significant surge in popularity by garnering considerable attention from researchers and practitioners. Bionic soft robots, which are composed of compliant materials like silicones, offer compelling solutions to manipulating delicate objects, operating in unstructured environments, and facilitating safe human–robot interactions. However, despite their numerous advantages, there are some fundamental challenges to overcome, which particularly concern motion precision and stiffness compliance in performing physical tasks that involve external forces. In this regard, enhancing the operation performance of soft robots necessitates intricate, complex structural designs, compliant multifunctional materials, and proper manufacturing methods. The objective of this literature review is to chronicle a comprehensive overview of soft robot design, manufacturing, and operation challenges in conjunction with recent advancements and future research directions for addressing these technical challenges.</em></p>
                </div>
            </li>
            <li>
                <strong style="font-size: 1.1em;">Robot arm damage detection using vibration data and deep learning.</strong>
                <i>Neural Comput & Applic.</i> 36 (pp. 1727-1739) 2024. 
                <a href="https://doi.org/10.1007/s00521-023-09150-3" target="_blank">DOI</a>
                <div class="read-more" onclick="toggleDetails(this)">Read More</div>
                <div class="content">
                    <p><em>During robot operation, robot components like links and joints may experience collisions or excess loads that can lead to structural damages or cracks. A crack in a structural component can degrade the overall performance of the structure. This study examines the influence of cracks on the vibration characteristics of a baseline robot link. The approach uses the finite element method to simulate the dynamics of planar robot link models with and without artificial cracks with different sizes, locations, and orientations in the ABAQUS software. The robot link models include one intact model and five defective models with cracks. A rectangular crack with a fixed length of 1 mm and a varying width from 0.001 to 0.1 mm is applied to a specific location along the robot link. Finite element analysis and machine learning are used to simulate and characterize the vibration of each robot link with one fixed end and one free end. The vibration responses are measured at the free end. The measured vibration data are then transformed into two-dimensional (2D) image data using the Gramian Angular Summation Field method. A convolutional neural network is then trained with the image data for crack detection and analysis. The results indicate that the proposed method demonstrates 98.25% accuracy on the data generated by the simulation experiments.</em></p>
                </div>
            </li>


    <li>
    <strong style="font-size: 1.1em;">Detection of Small Screws Using Machine Learning.</strong> 
    <i>2023 International Conference on Information and Communication Technology for Development for Africa (ICT4DA)</i> (pp. 13-18). IEEE. 
    <a href="https://doi.org/10.1109/ICT4DA59526.2023.10302258" target="_blank">DOI</a> 
     <div class="read-more" onclick="toggleDetails(this)">Read More</div>
                <div class="content">
            <p> <em> Small screws are commonly employed in assenrbling similar or dissimilar components of various industrial or consumer products. In automated assembly lines, detecting and sorting small targets like screws require accurate sensing and machine learning. Identifying the size of the screw is crucial for assembling and disassembling. This study focuses on the detection of small screws captured in images using a recent machine learning platform named You Only Look Once (YOLO) Version 8. This algorithmic platform offers powerful supervised machine-learning engines with highly competitive accuracy and speed. The data set from this study consists of images of small black carbon steel flat head screws. The dataset is divided into training, development, and testing subsets. There are 24 classes of screws with extremely small difference in attributes in their sizes. The dataset is annotated using the Make Sense open-source annotating tool. The results indicate that the machine learning method demonstrates 99.3% mean average precision (mAP). This detection performance is promising in comparison to the results documented by previous studies.</em></p> 
        </div> </li>
             
    
             
        <li>
            <strong style="font-size: 1.1em;">Contact temperature analysis of the classical Geneva mechanism through numerical methods.</strong> 
            <i>Materials Today: Proceedings</i>, 57, pp. 545-552. 
            <a href="https://doi.org/10.1016/j.matpr.2022.01.420" target="_blank">DOI</a> 
                 <div class="read-more" onclick="toggleDetails(this)">Read More</div>
                <div class="content">
            <p> <em> In this study, the flash temperature of the classical Geneva mechanism has been studied using the numerical method. An excessive sliding motion between the wheel and pin leads to the generation of heat at the contact surfaces, which raises the surface temperature of the two contacting bodies. The flash temperature has been anticipated for different loading cases and coefficients of friction. The analytical Blok equation results are compared with the finite element results, and the results are satisfactory for maximum temperature. Based on the simulation results, the maximum contact temperature occurred in the driving crankpin within 10-15° and 70–75° of the angular position, and as the load increased the contact temperature also increases. In addition, the angular velocity increment produced higher temperatures than the torque load increments.</em></p>
        </div> </li>

              
            <li>
             <strong style="font-size: 1.1em;">Numerical Stress Analysis and Fatigue Life Prediction of the Classical External Geneva Mechanism.</strong> 
             <i>International Workshop of Advanced Manufacturing and Automation (pp. 176-186).</i> Singapore: Springer Singapore. 
             <a href="https://doi.org/10.1007/978-981-19-0572-8_23" target="_blank">DOI</a>
              <div class="read-more" onclick="toggleDetails(this)">Read More</div>
                <div class="content">
            <p> <em>  This study examined the stress distribution and predicting the fatigue life of the classical external Geneva mechanism using analytical and finite element methods for three loading cases. The life cycles were analyzed using FE SAFE software by using the stress output database of ABAQUS software, which has been used for stress analysis of the Geneva wheel mechanism. The maximum stress is found at 45∘ of the angular position of the driving crank located at the bottom part of the end of the wheel slot and pin. Doubling the angular speed of the driving crank and doubling the torque that applied on the wheel yields almost equal contact pressure and von Mises stress. The wheel has a lower fatigue life cycle compared to the pin. </em></p> 
        </div></li>

    
            
            <li>
            <strong style="font-size: 1.1em;">The performance of gear with backlash: A review.</strong>  
            <i>Journal of Applied Mechanical Engineering</i>, 10(9), p. 389.
              <div class="read-more" onclick="toggleDetails(this)">Read More</div>
                <div class="content">
            <p> <em>  As the service time of the gear increases, its tooth profile could be deviated from its initial design shape and size as a result of time-varying load, overheating, wear, friction, and other working environmental impacts. Gear backlash is one of the non-linear parameters of the gear that adversely affects the performance of the transmission system. Backlash can be introduced deliberately for lubrication and free paly purposes or due to the gear tooth wear (reduction of the gear tooth thickness). The objective of this paper is to review and encapsulate this literature to provide a wide and good reference for scholars to be utilized. Assessing the effect of backlash on the dynamics and flash temperature of the gear is the main target of this review paper.</em></p> 
        </div></li>


            
            <li>
            <strong style="font-size: 1.1em;">Numerical comparative modal analysis of connecting rod between fixed crankpin and fixed piston pin.</strong>  
            <i>The 8th International Conference on Innovation in Science and Technology</i>, July 23–25, 2021, in Stockholm, Sweden.
             <div class="read-more" onclick="toggleDetails(this)">Read More</div>
                            <div class="content">
                        <p> <em> Connecting rods are subjected to a tensile (inertial force), compressive (gas pressure), and bending (eccentricity) loadings. The boundary conditions used for the determination of its natural frequency depends on the loading type. For free vibration analysis, when the piston moves upward the crankpin needs to be fixed and free piston pin, while when it moves down the piston pin should be considered as a fixed and free crankpin. This paper presents a numerical (ABAQUS software) comparison of the first six dominant mode shapes and natural frequencies of the connecting rod when it is fixed at the crankpin and free at the piston pin (case 1) and fixed at the piston pin and free at the crankpin (case 2) of an optimized geometry that found from literature. The mode shapes and natural frequencies of the two cases are compared, and it shows that the natural frequency of case 2 is lower than case 1. Therefore, for design purpose, the loading frequency should be less than the natural frequency of the connecting rod when it is fixed at the piston pin.</em></p> 
                    </div></li>


            
            <li>
            <strong style="font-size: 1.1em;">Determination of Important Contact Parameters for Spur Gear Design.</strong>   
            <i>TechHub Journal</i>, 1(1), pp. 28-38.
             <div class="read-more" onclick="toggleDetails(this)">Read More</div>
                            <div class="content">
                        <p> <em> This study focused on the determination of the important contact pa-rameters of spur gear design for the investigation of different parametric studies such as the maximum pressure, contact width, contact film thickness, sliding velocities, and others. The single and double tooth contact region has been de-termined for the given gear parameters along with their contact lengths. The contact width and pressure can be determined by considering the engaged spur tooth as a cylindrical object. The film thickness will vary from the mesh ap-proach (minimum) to the mesh recesses (maximum). The film thickness is de-creased in a single tooth contact region a maximum value at the mesh termina-tion.</em> </p> 
                    </div></li>
                    
            
            <li>
            <strong style="font-size: 1.1em;">Effect of backlash on transmission error and time varying mesh stiffness.</strong>   
            <i>International Workshop of Advanced Manufacturing and Automation</i> (pp. 18-28). Singapore: Springer Singapore. 
            <a href="https://doi.org/10.1007/978-981-33-6318-2_3" target="_blank">DOI</a> 
             <div class="read-more" onclick="toggleDetails(this)">Read More</div>
                            <div class="content">
                        <p> <em> Gears suffer by unavoidable time-varying mesh stiffness. Noise and vibrations amplitudes show the transmission error occurred within the components of power transmission error. The Gear Trax software has been used to model the gear with different amounts of backlash (from 0 mm to 1 mm by 0.2 mm increments) so that this gives a backlash due to the reduction of the thickness of the gear tooth. A plane strain analysis is used to predict the static transmission error, dynamic transmission error and time-varying mesh stiffness of spur gear with different backlash at different coefficients of friction using ABAQUS software. For finite element analysis, the mesh convergence has been done for maximum contact pressure and von Mises stress. The analytical mesh stiffness and the finite element mesh stiffness for gear without backlash have been compared, based on this the prediction time-varying mesh stiffness and transmission errors are continued to predict for the spur gear with different backlashes and coefficient of friction.</em> </p> 
                    </div></li>

        
            
            <li>
            <strong style="font-size: 1.1em;">Numerical study of the effect of backlash on flash temperature of spur gear.</strong>   
            <i>International Review of Mechanical Engineering (IREME)</i> 14, no. 11 (2020). 
            <a href="http://dx.doi.org/10.15866/ireme.v14i11.19763" target="_blank">DOI</a> 
            <div class="read-more" onclick="toggleDetails(this)">Read More</div>
                        <div class="content">
                        <p> <em> This article presents the effect of backlash on flash temperature of spur gears. Backlash in gears is one of the nonlinear parameters that can act as internal excitation and highly influence the life of gear teeth. To investigate the influence of friction coefficient on the flash temperature of the gear, a spur gear with a backlash from 0 mm to 1 mm, with 0.2 mm increment, is modelled by considering a pinion and gear in contact where the pinion is subjected to a constant angular velocity. The results of finite element analysis in ABAQUS with plane strain assumption and analytical results are compared with the experimental results from the literature. The results obtained in this study show that the flash temperature is maximum on the gear without backlash and the finite element and analytical results are in good agreement specifically within a single tooth contact region.</em></p> 
                    </div></li>
            
            
            <li>
             <strong style="font-size: 1.1em;">Dynamic analysis of spur gear with backlash using ADAMS.</strong>   
             <i>Materials Today: Proceedings</i>, 38, pp. 2959-2967. 
             <a href="https://doi.org/10.1016/j.matpr.2020.09.309" target="_blank">DOI</a> 
             <div class="read-more" onclick="toggleDetails(this)">Read More</div>
                     <div class="content">
                    <p> <em> Gear tooth profile can deviate from its initial design shape and size as a result of increasing service time under time-varying load, introducing external agents like debris, overheating due to friction, wear, and in generally due to other nonlinear factors such as backlash. As a result, the dynamics of the gear will also vary depending on the resulting gear tooth profile. In this study, the worn-out gear tooth is modelled as a backlash by assuming a uniformly distributed worn out surface and the effect on the dynamic performance is investigated. By changing the amount of backlash of the gear tooth from 0 mm to 1 mm by 0.2 mm increment, the gear is modelled and analysed for three loading cases using MSC ADAMS software. This paper discusses the effect of backlash or uniformly worn out spur gear tooth faces on the dynamics specifically the contact and angular accelerations of the gear.</em></p> 
                    </div></li>
            
            <li>
                <strong>Short Descriptions of Measurements and Instrumentation.</strong> <i>Int J Eng Res Technol</i>, 9 (12).
            </li>
            <li>
                <strong>Time and frequency domain analysis of signals: a review.</strong> <i>Int J Eng Res Technol</i> 9: 271–276.
            </li>
        </ul>
    </section>





    



<section id="contact">
    <h1>Contact Me</h1>
    <form action="https://formspree.io/f/mkgnobej" method="POST">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <textarea name="message" placeholder="Your Message" required style="height: 150px;"></textarea>
        <input type="submit" value="Send">
    </form>
</section>

<style>
    /* Additional styles for the contact form */
    section#contact form {
        display: flex;
        flex-direction: column;
        gap: 10px; /* Space between form elements */
    }

    input[type="text"],
    input[type="email"],
    textarea {
        padding: 10px;
        font-size: 1em; /* Adjust font size for better readability */
        border: 1px solid #ccc; /* Add a border */
        border-radius: 5px; /* Rounded corners */
        width: 100%; /* Full width */
        box-sizing: border-box; /* Include padding and border in the element's total width */
    }

    textarea {
        resize: none; /* Disable resizing */
    }

    input[type="submit"] {
        background-color: #1626af;
        color: white;
        border: none;
        padding: 10px;
        border-radius: 5px;
        cursor: pointer;
        transition: background-color 0.3s;
    }

    input[type="submit"]:hover {
        background-color: #0e1a7b; /* Darker shade on hover */
    }
</style>

 




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
            <a href="https://www.webofscience.com/wos/author/record/AAO-1275-2021" target="_blank" style="color: white; text-decoration: none;">PubLons</a>
        </p>
    </div>
    </footer>
    
</body>
</html>
