# Ex01 Portfolio
## Date:

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
<!DOCTYPE html>
<html>
<head>
    <title>Portfolio</title>
    <style>
        body {
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            margin: 0;
            padding: 0;
            background-color: #020136;
            color: #000000;
            line-height: 1.5;
        }
        header {
            background: linear-gradient(90deg, #020136, #9490ee,#020136);
            color: #fbf5f5;
            padding: 1.5rem 0;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
        }
        header h1 {
            margin: 0;
            font-size: 2.8rem;
            letter-spacing: 2px;
        }
        nav {
            margin: 1rem 0;
        }
        nav a {
            color: #f3f2f2;
            text-decoration: none;
            margin: 0 1rem;
            font-weight: bold;
            transition: color 0.3s ease;
        }
        nav a:hover {
            color: #c2c5f2;
        }
        .container {
            max-width: 1100px;
            margin: 2rem auto;
            background: #ffffff;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .section {
            margin-bottom: 3rem;
        }
        .section h2 {
            margin-bottom: 1rem;
            color: #333;
            font-size: 2rem;
            border-bottom: 3px solid #333;
            display: inline-block;
            padding-bottom: 0.5rem;
        }
        .section p, .section ul {
            font-size: 1.1rem;
        }
        .section ul {
            list-style: none;
            padding: 0;
        }
        .section ul li {
            background: #f8f6ba;
            margin: 0.5rem 0;
            padding: 0.8rem;
            border-left: 15px solid #333;
            border-radius: 30px;
            transition: background 0.3s ease;
        }
        .section ul li:hover {
            background: #bcbb9f;
        }
        img {
            width: 300px;
            height: 300px;
            border-radius: 50%;
            display:block;
            margin: 1.5rem auto;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            margin-top: 1rem;
        }
        .skills div {
            flex: 1 1 calc(33.333% - 1rem);
            background: #f8f6ba;
            padding: 1rem;
            border-radius: 108px;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .skills div:hover {
            background: #bcbb9f;
        }
        footer {
            text-align: center;
            padding: 1.5rem 0;
            background: #020136;
            color: #fff;
            margin-top: 2rem;
        }
        footer p {
            margin: 0;
            font-size: 0.9rem;
        }
        footer a {
            color: #f2e74a;
            text-decoration:underline;
            font-weight: bold;
        }
        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>My Portfolio</h1>
        <nav>
            <a href="#about">About</a>
            <a href="#projects">Projects</a>
            <a href="#skills">Skills</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>
    <div class="container">
        <section id="about" class="section">
            <h2>About Me</h2>
            <img src="sachin.jpg" alt="Profile Picture">
            <p><strong>Name:</strong> Gokul sachin k V</p>
            <p>Hello! I am a web developer passionate about creating beautiful and functional websites. I enjoy learning new technologies and improving my skills. I specialize in front-end development and have experience working with modern frameworks and tools.</p>
        </section>
        <section id="projects" class="section">
            <h2>Projects</h2>
            <ul>
                <li><strong>Project 1:</strong> A responsive website for a local business, built with HTML, CSS, and JavaScript.</li>
                <li><strong>Project 2:</strong> A personal blog using modern web technologies like React and Node.js.</li>
                <li><strong>Project 3:</strong> A portfolio showcasing my work and skills, designed with a focus on user experience.</li>
            </ul>
        </section>
        <section id="skills" class="section">
            <h2>Skills</h2>
            <div class="skills">
                <div><strong>HTML5</strong></div>
                <div><strong>CSS</strong></div>
                <div><strong>JavaScript</strong></div>
                <div><strong>React</strong></div>
                <div><strong>Node.js</strong></div>
                <div><strong>Git & GitHub</strong></div>
            </div>
        </section>
        <section id="contact" class="section">
            <h2>Contact</h2>
            <p>Email: <a href="mailto:me@gmail.com">me@gmail.com</a></p>
            <p>Phone: <a href="tel:+912345678901">+91 2345678901</a></p>
            <p>LinkedIn: <a href="https://linkedin.com/in/yourprofile" target="_blank">linkedin.com/in/yourprofile</a></p>
        </section>
    </div>
    <footer>
        <p>&copy; 2025 My Portfolio | <a href="#about">Back to Top</a></p>
    </footer>
</body>
</html>

```


## OUTPUT
![Screenshot 2025-04-29 153530](https://github.com/user-attachments/assets/17e22a25-44df-4e0c-8a8d-5c2c1f3fa3ae)
![Screenshot 2025-04-29 153622](https://github.com/user-attachments/assets/ebb6b5a4-b5a5-48c2-845f-2eca5246fb8a)
![Screenshot 2025-04-29 153645](https://github.com/user-attachments/assets/5a5a06bd-4896-4019-b3f8-075bfa882077)


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
