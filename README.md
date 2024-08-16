<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Syed Huzair's Portfolio</title>
    <style>
        /* Base Styles */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: #f4f4f4;
            overflow-x: hidden;
        }
        .container {
            width: 90%;
            margin: auto;
            overflow: hidden;
            padding: 20px 0;
        }
        header {
            background: linear-gradient(45deg, #00aaff, #0072ff);
            color: #fff;
            padding-top: 50px;
            padding-bottom: 50px;
            min-height: 70px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
            position: relative;
        }
        header h1 {
            margin: 0;
            font-size: 50px;
            font-weight: bold;
            animation: fadeIn 2s ease-in-out;
        }
        header p {
            font-size: 24px;
            margin-top: 10px;
            color: #f0f0f0;
            animation: fadeIn 3s ease-in-out;
        }
        header .blob {
            position: absolute;
            top: -50px;
            right: -50px;
            width: 200px;
            height: 200px;
            background: radial-gradient(circle at center, #00aaff, #0072ff);
            border-radius: 50%;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
            animation: blobMove 10s infinite;
        }

        section {
            padding: 40px 0;
            border-bottom: 1px solid #333;
        }
        h2 {
            color: #00aaff;
            font-size: 36px;
            margin-bottom: 20px;
            position: relative;
            display: inline-block;
            animation: fadeInUp 2s ease-in-out;
        }
        h2::after {
            content: '';
            display: block;
            width: 50px;
            height: 5px;
            background: #00aaff;
            margin-top: 10px;
            border-radius: 5px;
            animation: fadeInUp 2s ease-in-out;
        }
        p, ul {
            margin-bottom: 20px;
            font-size: 18px;
            line-height: 1.8;
            animation: fadeInUp 2s ease-in-out;
        }
        ul {
            padding-left: 20px;
        }
        ul li {
            margin-bottom: 10px;
        }
        ul li::before {
            content: '•';
            color: #00aaff;
            padding-right: 10px;
        }
        a {
            color: #00aaff;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }

        /* Footer Styles */
        .footer {
            background: #00aaff;
            color: #fff;
            text-align: center;
            padding: 20px 0;
            box-shadow: 0 -4px 8px rgba(0, 0, 0, 0.3);
        }

        /* Animations */
        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }
        @keyframes fadeInUp {
            0% { opacity: 0; transform: translateY(30px); }
            100% { opacity: 1; transform: translateY(0); }
        }
        @keyframes blobMove {
            0%, 100% { transform: translate(0, 0); }
            25% { transform: translate(20px, -10px); }
            50% { transform: translate(-20px, 10px); }
            75% { transform: translate(10px, -20px); }
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            header h1 {
                font-size: 40px;
            }
            header p {
                font-size: 20px;
            }
            h2 {
                font-size: 28px;
            }
            p, ul {
                font-size: 16px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Syed Huzair.B</h1>
        <p>Graphic Designer | LMS Administrator</p>
        <div class="blob"></div>
    </header>

    <section class="container">
        <h2>Profile</h2>
        <p>Passionate Web Developer with a strong background in developing and delivering high-quality web-based learning materials. Adept at collaborating with cross-functional teams to analyze requirements and deliver effective web solutions. Committed to incorporating innovative technologies and best practices to enhance the overall user experience.</p>
    </section>

    <section class="container">
        <h2>Contact Information</h2>
        <ul>
            <li>Email: huzair1999@gmail.com</li>
            <li>Phone: +91-7550191114</li>
            <li>Location: Chennai, India</li>
            <li>LinkedIn: <a href="https://linkedin.com/in/syed-huzair" target="_blank">linkedin.com/in/syed-huzair</a></li>
        </ul>
    </section>

    <section class="container">
        <h2>Work Experience</h2>
        <h3>Graphic Designer & LMS Administrator - HCLTech</h3>
        <p>Nov 2023 - Till date, Chennai, India</p>
        <ul>
            <li>Developed web-based learning interactive L1, L2, Gamification simple and complex e-learning materials using Articulate 360, Adobe tools, HTML, SSML.</li>
            <li>Built standard templates for different stakeholders, accelerating the content creation process.</li>
            <li>Managed LMS front-end activities and handled SSD queries, testing, and access enabling for compliance courses.</li>
        </ul>

        <h3>Graphic Designer - Juniper Networks</h3>
        <p>Aug 2022 - Nov 2023, Chennai, India</p>
        <ul>
            <li>Developed engaging and interactive web-based learning materials using Storyline, Camtasia, HTML, and JavaScript.</li>
            <li>Created Nano, Micro learning & On Demand Laboratory Courses in various standard approaches on Visual Story Board (VSB).</li>
            <li>Collaborated with cross-functional teams to deliver quality e-learning content on time.</li>
        </ul>
    </section>

    <section class="container">
        <h2>Education</h2>
        <h3>B.Tech. Biotechnology - Anna University (SVCE)</h3>
        <p>Jun 2018 - May 2022, Chennai, India (CGPA: 8.13)</p>
    </section>

    <section class="container">
        <h2>Skills</h2>
        <ul>
            <li>Figma / Adobe XD</li>
            <li>Adobe Captivate, Photoshop, After Effects</li>
            <li>SAP Success Factors (LMS), Articulate Storyline 360</li>
            <li>HTML, CSS, JavaScript, PERL, Python</li>
            <li>Audacity, Adobe Firefly, TechSmith Camtasia</li>
            <li>FileZilla, Xampp</li>
        </ul>
    </section>

    <section class="container">
        <h2>Certifications</h2>
        <ul>
            <li>Programming for Everybody (Getting Started with Python) - Coursera, University of Michigan (Sep-2020)</li>
            <li>Innovation, Business Model, and Entrepreneurship - NPTEL, IIT Roorkee (Dec-2020)</li>
            <li>Machine & Deep Learning Algorithms: Introduction - Percipio, Skillsoft (Dec-2023)</li>
            <li>UI/UX Design and Web Design (Basics) - Percipio, Skillsoft (2024)</li>
        </ul>
    </section>

    <section class="container">
        <h2>Languages</h2>
        <ul>
            <li>English (Full Professional Proficiency)</li>
            <li>Tamil (Native or Bilingual Proficiency)</li>
            <li>French (Elementary Proficiency)</li>
            <li>Arabic (Elementary Proficiency)</li>
        </ul>
    </section>

    <section class="container">
        <h2>Portfolio</h2>
        <p><a href="https://rb.gy/7tnpi9" target="_blank">https://rb.gy/7tnpi9</a></p>
    </section>

    <footer class="footer">
        <p>&copy; 2024 Syed Huzair. All Rights Reserved.</p>
    </footer>
</body>
</html>
