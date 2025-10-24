# Person's Portfolio Page

This repository contains the source code for my portfolio page, showcasing my skills in web development and WordPress.

---

## 1. HTML Structure (`index.html`)

This forms the basic layout and content of the portfolio.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Person's Portfolio</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header class="jumbotron text-center">
        <h1 class="display-4 animate__fade-in">Hello, I'm **Person** 👋</h1>
        <p class="lead animate__slide-up">A Web Development student specializing in front-end technologies and WordPress solutions.</p>
        <hr class="my-4 animate__fade-in">
        <p class="animate__slide-up animate__delay-1s">Currently pursuing **WordPress Plugin & Theme Development** to build robust digital experiences.</p>
    </header>

    <section id="skills" class="container my-5">
        <h2 class="text-center mb-4 animate__slide-right">Core Competencies</h2>
        <div class="row">
            <div class="col-md-6 animate__fade-in-up">
                <h3>Front-End & CMS</h3>
                <ul>
                    <li>**HTML, CSS, Bootstrap** (Solid Foundation)</li>
                    <li>Basic **JavaScript** & **jQuery**</li>
                    <li>**PHP** Basics</li>
                    <li>**WordPress** Website Management (Elementor, Rank Math, etc.)</li>
                </ul>
            </div>
            <div class="col-md-6 animate__fade-in-up animate__delay-0_5s">
                <h3>Systems & Tools</h3>
                <ul>
                    <li>Operating Systems: Windows, Linux, Android</li>
                    <li>MS Office Basic Proficiency</li>
                    <li>Technical Research & Validation</li>
                </ul>
            </div>
        </div>
    </section>
    
    <hr>

    <section id="projects" class="container my-5">
        <h2 class="text-center mb-4 animate__slide-left">Featured Work</h2>
        <div class="card shadow-sm animate__pop-in">
            <div class="card-body">
                <h5 class="card-title">Technical Blog & Resource Site</h5>
                <p class="card-text">My personal tech resource website, built and managed using my WordPress and web skills.</p>
                <a href="https://techcoreverity.site" target="_blank" class="btn btn-primary animate__bounce-in">Visit techcoreverity.site 🚀</a>
            </div>
        </div>
        </section>

    <hr>

    <section id="ambition" class="container my-5">
        <h2 class="text-center mb-4 animate__slide-right">Education & Future Focus</h2>
        <p class="text-center animate__fade-in-up">Currently in the **last semester** of a 4-year BBIT program.</p>
        <p class="text-center animate__fade-in-up animate__delay-0_5s">My immediate learning trajectory is focused on **WordPress Plugin Development**, which will solidify my full-stack capabilities within the WordPress ecosystem, followed by advanced **Theme Development**.</p>
    </section>

    <footer id="contact" class="bg-dark text-white text-center py-4 animate__fade-in">
        <h2>Connect With Me</h2>
        <p>Email: <a href="mailto:your_email@example.com" class="text-white">your_email@example.com</a></p>
        <p><a href="https://github.com/yourusername" target="_blank" class="text-white">GitHub Profile</a></p>
    </footer>

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="script.js"></script>

</body>
</html>
