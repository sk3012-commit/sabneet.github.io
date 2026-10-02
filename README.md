```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Sabneet Kaur | Finance Portfolio</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            line-height: 1.6;
            color: #222;
            background-color: #f7f8fa;
        }

        nav {
            background-color: #172b4d;
            padding: 18px 8%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        nav .logo {
            color: white;
            font-size: 22px;
            font-weight: bold;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 30px;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-size: 15px;
        }

        nav a:hover {
            color: #9fc5e8;
        }

        .hero {
            background-color: #eaf0f7;
            padding: 100px 8%;
            text-align: center;
        }

        .hero h1 {
            font-size: 48px;
            color: #172b4d;
            margin-bottom: 15px;
        }

        .hero p {
            max-width: 750px;
            margin: 0 auto;
            font-size: 20px;
            color: #444;
        }

        .section {
            max-width: 1100px;
            margin: auto;
            padding: 70px 8%;
        }

        .section h2 {
            text-align: center;
            color: #172b4d;
            font-size: 32px;
            margin-bottom: 40px;
        }

        .skills {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
        }

        .skill {
            background: white;
            padding: 20px;
            text-align: center;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.08);
            font-weight: bold;
        }

        .projects {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 25px;
        }

        .project {
            background: white;
            padding: 25px;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.08);
        }

        .project h3 {
            color: #172b4d;
            margin-bottom: 12px;
        }

        .project p {
            color: #555;
            margin-bottom: 18px;
        }

        .project a {
            display: inline-block;
            background-color: #172b4d;
            color: white;
            text-decoration: none;
            padding: 9px 15px;
            border-radius: 5px;
            font-size: 14px;
        }

        .project a:hover {
            background-color: #284b7a;
        }

        .contact {
            text-align: center;
            background-color: #172b4d;
            color: white;
            padding: 60px 8%;
        }

        .contact h2 {
            margin-bottom: 15px;
        }

        .contact a {
            color: #9fc5e8;
            text-decoration: none;
        }

        footer {
            background-color: #101d33;
            color: #ccc;
            text-align: center;
            padding: 20px;
            font-size: 14px;
        }

        @media (max-width: 800px) {
            .skills,
            .projects {
                grid-template-columns: 1fr;
            }

            nav {
                flex-direction: column;
                gap: 10px;
            }

            nav ul {
                gap: 15px;
            }

            .hero h1 {
                font-size: 36px;
            }
        }
    </style>
</head>

<body>

    <!-- Navigation -->
    <nav>
        <div class="logo">Sabneet Kaur</div>

        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>


    <!-- Personal Statement -->
    <section class="hero" id="about">
        <h1>Sabneet Kaur</h1>

        <p>
            I am a finance student interested in pursuing a career in banking
            and financial services, with strong skills in communication,
            problem-solving, leadership, and teamwork.
        </p>
    </section>


    <!-- Skills -->
    <section class="section" id="skills">
        <h2>Skills</h2>

        <div class="skills">
            <div class="skill">Financial Analysis</div>
            <div class="skill">Microsoft Excel</div>
            <div class="skill">Problem-Solving</div>
            <div class="skill">Communication</div>
            <div class="skill">Leadership</div>
            <div class="skill">Teamwork</div>
            <div class="skill">Customer Service</div>
            <div class="skill">Data Analysis</div>
            <div class="skill">Attention to Detail</div>
        </div>
    </section>


    <!-- Projects -->
    <section class="section" id="projects">
        <h2>Projects</h2>

        <div class="projects">

            <div class="project">
                <h3>PNC Financial Services Job Simulation</h3>

                <p>
                    Completed a banking-focused job simulation involving
                    financial decision-making, customer service, problem-solving,
                    communication, and working with financial information.
                </p>

                <a href="#" target="_blank">Project Details</a>
            </div>


            <div class="project">
                <h3>Business Statistics Analysis</h3>

                <p>
                    Applied statistical concepts including sampling,
                    descriptive statistics, data analysis, standard deviation,
                    and data visualization to solve business-related problems.
                </p>

                <a href="#" target="_blank">Project Details</a>
            </div>


            <div class="project">
                <h3>Business Ethics Analysis</h3>

                <p>
                    Analyzed real-world business ethics cases involving
                    corporate responsibility, ethical decision-making,
                    stakeholders, and the financial effects of business decisions.
                </p>

                <a href="#" target="_blank">Project Details</a>
            </div>

        </div>
    </section>


    <!-- Contact -->
    <section class="contact" id="contact">
        <h2>Let's Connect</h2>

        <p>
            I am interested in opportunities in finance, banking,
            and financial services.
        </p>

        <p style="margin-top: 15px;">
            <a href="https://www.linkedin.com/in/sabneet-kaur/"
               target="_blank">
                LinkedIn
            </a>
        </p>

        <p style="margin-top: 10px;">
            <a href="https://github.com/sk3012-commit"
               target="_blank">
                GitHub
            </a>
        </p>
    </section>


    <!-- Footer -->
    <footer>
        <p>© 2026 Sabneet Kaur | Finance Portfolio</p>
    </footer>

</body>
</html>
```
