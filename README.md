# all-or-nothing

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abegael | Personal Portfolio</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, sans-serif;
            background: #f5f7fb;
            color: #263238;
            line-height: 1.6;
        }

        header {
            background: #172554;
            color: white;
            padding: 20px 8%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
        }

        header h2 {
            color: #60a5fa;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
            font-weight: bold;
        }

        nav a:hover {
            color: #60a5fa;
        }

        .hero {
            min-height: 85vh;
            background: linear-gradient(135deg, #172554, #2563eb);
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 50px 20px;
        }

        .hero-content {
            max-width: 700px;
        }

        .profile {
            width: 160px;
            height: 160px;
            border-radius: 50%;
            border: 5px solid white;
            object-fit: cover;
            margin-bottom: 20px;
            background: #dbeafe;
        }

        .hero h1 {
            font-size: 45px;
            margin-bottom: 10px;
        }

        .hero h3 {
            color: #bfdbfe;
            margin-bottom: 15px;
        }

        .hero p {
            margin-bottom: 25px;
        }

        .btn {
            display: inline-block;
            background: #60a5fa;
            color: #172554;
            padding: 12px 25px;
            border-radius: 25px;
            text-decoration: none;
            font-weight: bold;
        }

        .btn:hover {
            background: white;
        }

        section {
            padding: 65px 10%;
        }

        .section-title {
            text-align: center;
            font-size: 30px;
            color: #172554;
            margin-bottom: 30px;
        }

        .about {
            text-align: center;
            max-width: 850px;
            margin: auto;
        }

        .skills-container,
        .projects-container,
        .achievements-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 20px;
        }

        .card {
            background: white;
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.08);
            text-align: center;
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-7px);
        }

        .card h3 {
            color: #2563eb;
            margin-bottom: 10px;
        }

        .skill-bar {
            background: #e5e7eb;
            height: 10px;
            border-radius: 10px;
            margin-top: 10px;
            overflow: hidden;
        }

        .skill-level {
            background: #2563eb;
            height: 100%;
            border-radius: 10px;
        }

        .contact {
            background: #172554;
            color: white;
            text-align: center;
        }

        .contact .section-title {
            color: white;
        }

        .contact p {
            margin: 12px 0;
        }

        .contact a {
            color: #93c5fd;
            text-decoration: none;
        }

        footer {
            background: #0f172a;
            color: white;
            text-align: center;
            padding: 18px;
        }

        @media (max-width: 600px) {
            header {
                justify-content: center;
                gap: 15px;
            }

            nav {
                text-align: center;
            }

            nav a {
                display: inline-block;
                margin: 5px;
                font-size: 13px;
            }

            .hero h1 {
                font-size: 32px;
            }

            section {
                padding: 45px 6%;
            }
        }
    </style>
</head>

<body>

    <!-- NAVIGATION -->
    <header>
        <h2>ABEGÆL.</h2>
        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- HOME -->
    <section class="hero" id="home">
        <div class="hero-content">

            <!-- Replace profile.jpg with your own photo -->
            <img src="profile.jpg" alt="Profile Picture" class="profile">

            <h3>Hello, Welcome to My Portfolio!</h3>
            <h1>I'm Abegael</h1>
            <h3>Future Web Developer | Student</h3>

            <p>
                I am a passionate student who loves technology,
                creativity, and learning new things.
                Welcome to my personal portfolio website!
            </p>

            <a href="#about" class="btn">Explore My Portfolio</a>
        </div>
    </section>

    <!-- ABOUT -->
    <section id="about">
        <h2 class="section-title">About Me</h2>

        <div class="about">
            <p>
                Hi! My name is Abegael. I am a student who is interested
                in computers, technology, and web development.
                I enjoy learning how to create websites and exploring
                new ideas that can improve my skills.
                My goal is to become a successful professional in
                the field of Information Technology.
            </p>
        </div>
    </section>

    <!-- SKILLS -->
    <section id="skills">
        <h2 class="section-title">My Skills</h2>

        <div class="skills-container">

            <div class="card">
                <h3>HTML</h3>
                <p>Creating website structures.</p>
                <div class="skill-bar">
                    <div class="skill-level" style="width: 85%"></div>
                </div>
            </div>

            <div class="card">
                <h3>CSS</h3>
                <p>Designing beautiful websites.</p>
                <div class="skill-bar">
                    <div class="skill-level" style="width: 75%"></div>
                </div>
            </div>

            <div class="card">
                <h3>JavaScript</h3>
                <p>Learning website programming.</p>
                <div class="skill-bar">
                    <div class="skill-level" style="width: 60%"></div>
                </div>
            </div>

            <div class="card">
                <h3>Communication</h3>
                <p>Sharing ideas and working with others.</p>
                <div class="skill-bar">
                    <div class="skill-level" style="width: 80%"></div>
                </div>
            </div>

        </div>
    </section>

    <!-- PROJECTS -->
    <section id="projects">
        <h2 class="section-title">My Projects</h2>

        <div class="projects-container">

            <div class="card">
                <h3>Personal Portfolio</h3>
                <p>
                    A personal website that introduces my profile,
                    skills, and achievements.
                </p>
            </div>

            <div class="card">
                <h3>Web Design Project</h3>
                <p>
                    A creative website made using HTML and CSS
                    with a clean and responsive design.
                </p>
            </div>

            <div class="card">
                <h3>Student Project</h3>
                <p>
                    An academic project that shows my creativity,
                    teamwork, and programming knowledge.
                </p>
            </div>

        </div>
    </section>

    <!-- ACHIEVEMENTS -->
    <section id="achievements">
        <h2 class="section-title">My Achievements</h2>

        <div class="achievements-container">

            <div class="card">
                <h3>🎓 Education</h3>
                <p>Continuously learning and improving my knowledge.</p>
            </div>

            <div class="card">
                <h3>💻 Web Development</h3>
                <p>Learning to build websites using HTML and CSS.</p>
            </div>

            <div class="card">
                <h3>🌟 Personal Growth</h3>
                <p>Developing my confidence, creativity, and skills.</p>
            </div>

        </div>
    </section>

    <!-- CONTACT -->
    <section class="contact" id="contact">
        <h2 class="section-title">Contact Me</h2>

        <p>Do you want to connect with me?</p>
        <p>Email: <a href="mailto:your@email.com">your@email.com</a></p>
        <p>Facebook: <a href="#">My Facebook Profile</a></p>
        <p>Location: Philippines</p>

        <br>
        <a href="mailto:your@email.com" class="btn">Send Me an Email</a>
    </section>

    <!-- FOOTER -->
    <footer>
        <p>© 2026 Abegael | Personal Portfolio Website</p>
        <p>Designed with HTML5 and CSS3</p>
    </footer>

</body>
</html>
