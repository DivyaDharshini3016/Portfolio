# Ex01 Portfolio
## Date: 29/04/2026

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

## PROGRAM:

### Index.html
```
<!DOCTYPE html>
<html>
<head>
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <nav>
        <h2 class="logo">Divya Dharshini S</h2>
        <ul>
            <li><a href="#" onclick="showPage('home')">Home</a></li>
            <li><a href="#" onclick="showPage('about')">About</a></li>
            <li><a href="#" onclick="showPage('skills')">Skills</a></li>
            <li><a href="#" onclick="showPage('contact')">Contact</a></li>
        </ul>
    </nav>
</header>

<!-- HOME -->
<section id="home" class="page active">
    <h1>Welcome to My Portfolio</h1><br>
    <h2>Hello,I'm Divya Dharshini S</h2>
    <p>aspiring web developer with a passion for web design and development.<br><br>
I have basic knowledge of HTML, CSS, and JavaScript, and I am continuously learning new technologies to improve my skills.</p>
</section>

<!-- ABOUT -->
<section id="about" class="page">
    <h1>About Me</h1>
    <p>I am Divya Dharshini S, a B.Tech student in the Artificial Intelligence and Machine Learning (AIML) department at Saveetha Engineering College.<br><br>
 I am passionate about web design and development and enjoy creating modern, responsive, and user-friendly websites.<br><br> 
I have basic knowledge of HTML, CSS, and JavaScript, and I am continuously learning new technologies to improve my skills and build creative projects.<br><br>
I like turning creative ideas into real-world projects and aim to become a skilled web developer in the future.</p>
</section>

<!-- Skills Section -->
<section id="skills" class="page">
    <h2 style="text-align: center;">My Skills</h2>

    <div class="skills-container">
        <div class="skill-card">
            <h3>HTML</h3>
            <p>Skilled in structuring to create a web pages using HTML.</p>
        </div>

        <div class="skill-card">
            <h3>SQL (Database)</h3>
            <p>Able to work with databases using SQL, including basic queries, data insertion, and table management..</p>
        </div>

        <div class="skill-card">
            <h3>Language</h3>
            <h4>Python,C & Java</h4>
            <p>Basic programming knowledge and problem solving.</p>
        </div>

        <div class="skill-card">
            <h3>CSS</h3>
            <p>Experienced in styling web pages using CSS.</p>
        </div>
    </div>
</section>


<!-- CONTACT -->
<section id="contact" class="page">
    <h1>Contact Me</h1>
    <p>Email: divyadharshini1827@email.com</p>
    <p>Phone: +91 8056750716</p>
</section>



<script>
function showPage(pageId) {
    let pages = document.querySelectorAll('.page');
    pages.forEach(page => page.classList.remove('active'));
    document.getElementById(pageId).classList.add('active');
}
</script>

</body>
</html>
```

### Style.CSS
```
body {
    font-family: Arial;
    margin: 0;
}

/* Navbar */
header {
    background: #333;
    color: white;
    padding: 10px 0;
}
#home {
    background-color: #f7cac9;
}

#about {
    background-color: #b8a9c9;
}

#skills {
    background-color: #f1e3dd;
}

#contact {
    background-color: #f9d5e5;
}


nav {
    display: flex;
    justify-content: space-between;
    width: 80%;
    margin: auto;
    padding: 10px;
}

nav ul {
    display: flex;
    list-style: none;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    cursor: pointer;
}

nav ul li a:hover {
    color: cyan;
}

/* Pages */
.page {
    display: none;
    padding: 60px;
    text-align: center;
    min-height: calc(100vh - 120px);
}

.active {
    display: block;
}

/* Skills Section */

.skills-container {
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
}

/* Skill Card */
.skill-card {
    background: pink;
    padding: 20px;
    width: 260px;
    border-radius: 10px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}

.skill-card:hover {
    transform: scale(1.05);
}

/* Skill Title */
.skill-card h3 {
    margin-bottom: 10px;
}
```

## OUTPUT

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/41ed342c-87ea-4ad3-b533-16d7faca0db2" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/133d87ab-a9e4-4587-b2ca-5462cf2f43fb" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/381654e7-730e-42f1-ad0f-2ec2f93bb5fb" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c4000037-f2bd-4fa5-ac76-48043a66ec94" />

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
