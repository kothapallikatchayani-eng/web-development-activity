<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Portfolio</title>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Alex Student</h1>
        <p>First-Year Computer Science Student & Aspiring Developer</p>
        <hr>
        <!-- Navigation Links -->
        <nav>
            <a href="#about">About Me</a> |
            <a href="#skills">Skills</a> |
            <a href="#projects">Projects</a> |
            <a href="#contact">Contact</a>
        </nav>
        <hr>
    </header>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I am a first-semester computer science student passionate about technology and web development. I am currently learning the fundamentals of HTML, CSS, and basic programming concepts.</p>
        <p>In my free time, I enjoy solving coding puzzles and exploring new technology trends.</p>
    </section>

    <hr>

    <!-- Skills Section -->
    <section id="skills">
        <h2>My Skills</h2>
        <table border="1" cellpadding="8">
            <thead>
                <tr>
                    <th>Category</th>
                    <th>Technologies / Tools</th>
                    <th>Proficiency Level</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Web Technologies</td>
                    <td>HTML5, Basic CSS</td>
                    <td>Beginner</td>
                </tr>
                <tr>
                    <td>Programming Languages</td>
                    <td>C, Python (Basics)</td>
                    <td>Beginner</td>
                </tr>
                <tr>
                    <td>Tools</td>
                    <td>Git, VS Code</td>
                    <td>Learning</td>
                </tr>
            </tbody>
        </table>
    </section>

    <hr>

    <!-- Projects Section -->
    <section id="projects">
        <h2>Projects</h2>
        
        <h3>1. Personal Portfolio Website</h3>
        <p>A simple, accessible personal website built using semantic HTML5 tags to showcase my profile and academic journey.</p>

        <h3>2. Student Grade Calculator</h3>
        <p>A simple command-line program written in C to compute student GPA and grade averages.</p>

        <h3>3. Restaurant Web Page</h3>
        <p>A single-page layout featuring menu listings, operating schedules, and a table reservation form.</p>
    </section>

    <hr>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Get in Touch</h2>
        <form action="#" method="post">
            <label for="name">Your Name:</label><br>
            <input type="text" id="name" name="name" required><br><br>

            <label for="email">Your Email:</label><br>
            <input type="email" id="email" name="email" required><br><br>

            <label for="subject">Subject:</label><br>
            <input type="text" id="subject" name="subject" required><br><br>

            <label for="message">Message:</label><br>
            <textarea id="message" name="message" rows="5" cols="30" required></textarea><br><br>

            <input type="submit" value="Send Message">
        </form>
    </section>

    <hr>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2026 Alex Student. All Rights Reserved.</p>
        <p>Connect with me on <a href="https://github.com" target="_blank">GitHub</a> or <a href="https://linkedin.com" target="_blank">LinkedIn</a>.</p>
    </footer>

</body>
</html>
