# cybersphinix.github.io
   <!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="portfolio.css">
</head>

<body>
    <header>
        <h1>Hi, I am Shristi 👋</h1>
        <p id="aboutParagraph" style="display: none;">I am a CS student currently studying at the University of Central
            Oklahoma.</p>
    </header>
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#resume">Resume</a></li>
            <li><a href="#linkedin">LinkedIn</a></li>
        </ul>
    </nav>
    <section id="about">
        <h2>About Me</h2>
        <div class="buttons">
            <a onclick="toggleParagraph()" class="btn">About</a>
            <a href="http://cybersphinix.github.io/resume.pdf" target="_blank" class="btn">Resume</a>
            <a href="https://www.linkedin.com/in/shristi-thapaliya2003" target="_blank" class="btn">LinkedIn</a>
        </div>
    </section>
    <section id="activities-container"> <!-- New container for activities and heading -->
        <h2>What I'm Doing</h2> <!-- Moved heading here -->
        <section id="activities"> <!-- Moved activities inside the new container -->
            <div class="activity">
                <h3>Web Development</h3>
                <p>Development of sites for business activities.</p>
            </div>
            <div class="activity">
                <h3>Cybersecurity Manager</h3>
                <p>Managing security threats and implementing security measures to prevent security breaches.</p>
            </div>
        </section>
    </section>
    <section id="linkedin">
        <h2>LinkedIn</h2>
        <p><a href="https://www.linkedin.com/in/shristi-thapaliya2003" target="_blank">Visit LinkedIn Profile</a></p>
    </section>
    <footer>
        <p>&copy; 2024 My Portfolio</p>
    </footer>
    <script>
        function toggleParagraph() {
            var paragraph = document.getElementById("aboutParagraph");
            var style = window.getComputedStyle(paragraph);
            if (style.display === "none") {
                paragraph.style.display = "block";
            } else {
                paragraph.style.display = "none";
            }
        }
    </script>
    <script src="portfolio.js"></script>
</body>

</html>
