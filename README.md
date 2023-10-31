head>
<body>
    <header>
        <div class="header-content">
            <!-- Add your profile picture here -->
            <img src="./mypic.jpg" alt>
            <h1>ABINAYA K</h1>
            <p>STUDENT </p>
        </div>
    </header>

    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#resume">Resume</a></li>
        </ul>
    </nav>

    <section id="about">
        <div class="section-content">
            <h2>About Me</h2>
            <p>I am abinaya.i am doing bca. i am become a web developer<p>
        </div>
    </section>

    <section id="education">
        <div class="section-content">
            <h2>Education</h2>
            <p>Bharathidhasan University </p>
        </div>
    </section>

    <section id="skills">
        <div class="section-content">
            <h2>Skills</h2>
            <ul>
                <li>CyberSecurity</li>
                <li>Internet of Things</li>
                <li>Cloud Computing</li>
            </ul>
        </div>
    </section>

    <section id="projects">
        <div class="section-content">
            <h2>Projects</h2>
            <ul>
                <li><a href="#">AI Based alternator control system</a></li>
                <li><a href="#">Cloud Security IBM</a></li>
                <!-- Add more project links here -->
            </ul>
        </div>
    </section>

    <section id="resume">
    
        <div class="section-content">
            <center>
            <h2>Resume</h2>
            <a href="https://drive.google.com/file/d/1Fjf9NlokC-6Cvk6CimvWKehDOOl8855V/view?usp=sharing" target="_blank" class="download-button">Download CV</a>
        </center>
        </div>
        
    </section>

    <footer>
        <p>&copy; 2023 Abinaya</p>
    </footer>

    <script>
        // Smooth scrolling to section when clicking on navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();

                const targetId = this.getAttribute('href').substring(1);
                const targetElement = document.getElementById(targetId);

                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop,
                        behavior: 'smooth'
                    });
                }
            });
        });
    </script>
</body>
</html># Profile1
