# Ex01 Portfolio
## Date: 13.08.2025

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
index.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <nav class="navbar">
            <center>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
            </center>
        </nav>
    </header>


    <section id="home" class="hero">
        <div class="hero-text">
            <h1>Hi, I'm <span>Balasuriya</span></h1>
            <p>Aspiring Web Developer & Designer</p>
        </div>
    </section>


    <section id="about" class="about">
        <div class="about-text">
            <h2>About Me</h2>
            <p>
                I’m a passionate designer and aspiring web developer who loves turning creative ideas into functional digital experiences.
With a focus on minimal and modern design, I enjoy building clean, responsive websites that work seamlessly across devices.
My skills range from crafting eye-catching visuals to writing efficient, well-structured code.
I believe in constant learning and exploring new tools to bring fresh perspectives to every project.
Beyond coding, I find inspiration in photography, editing, and design work that tells a compelling story.
            </p>
        </div>
        <div class="about-img">
            <img src="org.jpg" alt="Profile">
        </div>
    </section>

    <section id="contact" class="contact">
        <h1>Contact Me</h1>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit" class="btn">Send</button>
        </form>
    </section>

    <footer>
        <p>© 2025 Balasuriya. All rights reserved.</p>
    </footer>

</body>
</html>
```

style.css
```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    line-height: 1.6;
}


.navbar {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 15px 30px;
    background: #222;
    position: fixed;   
    top: 0;           
    left: 0;
    width: 100%;       
    z-index: 1000;
}



.nav-links {
    list-style: none;
    display: flex;
}

.nav-links li {
    margin-left: 20px;
}

.nav-links a {
    color: white;
    text-decoration: none;
}

.nav-links a:hover {
    color: #f39c12;
}

.hero {
    height: 100vh;
    background-image: url('bg-image.jpg');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    /*background: linear-gradient(rgba(0, 0, 0, 0), rgba(0,0,0,0.5)), url('bg.jpg') center/cover no-repeat; */
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    text-align: center;
}

.hero p {
    margin-top: 1px;
    font-size: 28px;
}

.hero h1 {
    font-size: 80px;
}

.hero span {
    color: #f39c12;
}

.about {
    height: 80vh;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 50px 80px;
    background: rgba(129, 133, 138, 0.5);
}

.about-text {
    font-size: 25px;
    flex: 1;
    padding: 5px 80px 5px 5px;
}

.about-img img {
    width: 250px;
    border-radius: 20px;
}

.contact {
    height: 90vh;
    padding: 100px 100px 100px 100px;
    text-align: center;
    background: #222;
    color: white;
}

.contact form {
    padding: 5px 1px 1px 10px;
    max-width: 400px;
    margin: auto;
    display: flex;
    flex-direction: column;
}

.contact input,
.contact textarea {
    margin: 10px 0;
    padding: 10px;
    border: none;
    border-radius: 10px;
}

.contact button {
    padding: 10px;
    background: #f39c12;
    color: white;
    border: none;
    cursor: pointer;
    border-radius: 10px;
}

.contact button:hover {
    background: #d35400;
}

footer {
    background: #111;
    color: white;
    padding: 10px;
    text-align: center;
}


@media (max-width: 768px) {
    .about {
        flex-direction: column;
        text-align: center;
    }
}
```


## OUTPUT
<img width="1920" height="1200" alt="Screenshot (174)" src="https://github.com/user-attachments/assets/d59cf7c9-8f6b-4433-9408-a717ac2d4b1d" />
<img width="1920" height="1200" alt="Screenshot (175)" src="https://github.com/user-attachments/assets/27224e9a-3814-4da6-b8e9-2d92c3888f43" />
<img width="1920" height="1200" alt="Screenshot (176)" src="https://github.com/user-attachments/assets/5e7c0dbf-c6ab-4161-9206-169926be3348" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
