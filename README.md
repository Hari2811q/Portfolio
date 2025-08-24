# MDAP-EX_01-Portfolio
## Date: 24/08/2025

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
HTML CODE:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My CSE Portfolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="container">
    <header class="hero">
      <img src="profile.jpg" alt="My Profile" class="profile-pic" />
      <h1>Hariprasath R</h1>
      <p>CSE Student | Web Developer | Tech Enthusiast</p>
      <nav class="navbar">
        <a href="#about">About</a>
        <a href="#education">Education</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#certifications">Certifications</a>
        <a href="#achievements">Achievements</a>
        <a href="#internships">Internships</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <section id="about">
      <h2>About Me</h2>
      <p>I am a Computer Science student passionate about building scalable web apps and solving real-world problems.</p>
    </section>

    <section id="education">
      <h2>Education</h2>
      <p><strong>B.E in Computer Science and Engineering</strong></p>
      <p>Saveetha Engineering College, 2023 - 2027</p>
    </section>

    <section id="skills">
      <h2>Skills</h2>
      <ul>
        <li>C, Python, JavaScript</li>
        <li>HTML, CSS</li>
        <li>Git, GitHub, MySQL</li>
      </ul>
    </section>

    <section id="projects">
      <h2>Projects</h2>
      <ul>
        <li>Portfolio Website</li>
        <li>Student Result System </li>
        <li>ASD Detection Model </li>
      </ul>
    </section>

    <section id="certifications">
      <h2>Certifications</h2>
      <ul>
        <li>Python for Everybody – Coursera</li>
        <li>Frontend Development – Great Learning</li>
        <li>Git & GitHub – Udemy</li>
      </ul>
    </section>

    <section id="achievements">
      <h2>Achievements</h2>
      <ul>
        <li>Cloud computing - NPTEL</li>
        <li>300+ problems on LeetCode</li>
        <li>Introduction to ML</li>
      </ul>
    </section>

    <section id="internships">
      <h2>Internships</h2>
      <ul>
        <li>Machine Learning-Towards Tecnology private Limited</li>
      </ul>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>Email: harishraju123321@gmail.com</p>
      <p>GitHub: <a href="#">https://github.com/Hari2811q</a></p>
    </section>

    <footer>
      <p>&copy; 2025 Hariprasath R. All rights reserved.</p>
    </footer>
  </div>
</body>
</html>

```
CSS CODE:
```
body {
    font-family: Arial, sans-serif;
    background: #f5f5f5;
    color: #333;
    margin: 0;
    padding: 0;
  }
  
  .container {
    max-width: 900px;
    margin: auto;
    padding: 2rem;
  }
  
  .hero {
    text-align: center;
    background: #0077b6;
    color: white;
    padding: 2rem;
    border-radius: 10px;
  }
  
  .profile-pic {
  width: 150px;         
  height: 150px;        
  border-radius: 50%;   
  object-fit: cover;    
  border: 3px solid #333; 
  box-shadow: 0 4px 8px rgba(0,0,0,0.3);
}

  
  .navbar {
    margin-top: 1rem;
  }
  
  .navbar a {
    color: white;
    margin: 0 0.5rem;
    text-decoration: none;
    font-weight: bold;
  }
  
  h2 {
    color: #0077b6;
    margin-top: 2rem;
  }
  
  ul {
    list-style-type: square;
    padding-left: 1.5rem;
  }
  
  a {
    color: #0077b6;
    text-decoration: none;
  }
  
  footer {
    text-align: center;
    margin-top: 2rem;
    color: #777;
  }

```



## OUTPUT:

<img width="1917" height="1014" alt="image" src="https://github.com/user-attachments/assets/346f3e8d-31b0-4e33-9c7f-37a2f0407a9b" />

<img width="1919" height="1019" alt="image" src="https://github.com/user-attachments/assets/da9214e6-ff56-4877-be92-fad3e5de55f1" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
