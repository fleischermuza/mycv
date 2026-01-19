CV/
│
├── index.html
├── style.css
![photo](https://github.com/user-attachments/assets/d9bb80f2-a76c-4d7d-8bd9-56ed695c015a)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Brian | Digital Marketing Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <div class="header-content">
        <img src="profile.jpg" alt="Profile Picture" class="profile-img">
        <h1>Brian</h1>
        <p class="subtitle">Digital Marketing Assistant | Remote Work Ready</p>
    </div>
</header>

<section class="about">
    <h2>About Me</h2>
    <p>
        I am an entry-level digital marketing professional with a strong interest in online marketing,
        content creation, and social media management. I have experience supporting educational
        environments as an assistant teacher, which strengthened my communication, organization,
        and teamwork skills. I am motivated, reliable, and eager to grow in a remote digital marketing role.
    </p>
</section>

<section class="details">
    <h2>Personal Details</h2>
    <ul>
        <li><strong>Name:</strong> Brian</li>
        <li><strong>Location:</strong> South Africa</li>
        <li><strong>Availability:</strong> Remote</li>
        <li><strong>Email:</strong> yourname@email.com</li>
    </ul>
</section>

<section class="skills">
    <h2>Skills</h2>
    <ul>
        <li>Social Media Management</li>
        <li>Content Creation</li>
        <li>Basic SEO Knowledge</li>
        <li>Email Marketing Support</li>
        <li>Canva & Visual Content Design</li>
        <li>Analytics & Reporting (Basic)</li>
        <li>Remote Communication</li>
    </ul>
</section>

<section class="projects">
    <h2>Sample Projects</h2>

    <div class="project-card">
        <h3>Social Media Content Plan</h3>
        <p>
            Developed a sample Instagram content calendar including captions, hashtags,
            and posting schedules aimed at improving engagement and brand visibility.
        </p>
    </div>

    <div class="project-card">
        <h3>Email Marketing Draft</h3>
        <p>
            Created a promotional email draft focused on clear messaging,
            customer engagement, and strong call-to-action strategies.
        </p>
    </div>
</section>

<section class="contact">
    <h2>Contact</h2>
    <p>Email: yourname@email.com</p>
    <p>LinkedIn: linkedin.com/in/yourprofile</p>
    <p>GitHub: github.com/brianxovo</p>
</section>

<footer>
    <p>© 2026 Brian | Digital Marketing Portfolio</p>
</footer>

</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, Helvetica, sans-serif;
    background-color: #0f172a;
    color: #e5e7eb;
    line-height: 1.6;
}

header {
    background-color: #020617;
    padding: 40px 20px;
    text-align: center;
}

.header-content {
    max-width: 900px;
    margin: auto;
}

.profile-img {
    width: 140px;
    height: 140px;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 15px;
    border: 3px solid #38bdf8;
}

h1 {
    font-size: 2.2rem;
}

.subtitle {
    color: #94a3b8;
    margin-top: 5px;
}

section {
    max-width: 900px;
    margin: 40px auto;
    padding: 0 20px;
}

h2 {
    border-bottom: 2px solid #38bdf8;
    padding-bottom: 5px;
    margin-bottom: 15px;
    color: #38bdf8;
}

.details ul,
.skills ul {
    list-style: none;
}

.details li,
.skills li {
    padding: 6px 0;
}

.project-card {
    background-color: #020617;
    padding: 20px;
    border-radius: 8px;
    margin-bottom: 15px;
}

.contact p {
    margin: 8px 0;
}

footer {
    background-color: #020617;
    text-align: center;
    padding: 15px;
    margin-top: 50px;
    color: #94a3b8;
}

