# sagar.github.io


<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>My Portfolio</title>
    <style>
    @import url("https://fonts.googleapis.com/css2?family=Vazirmatn:wght@400;500;600;700;800&display=swap");

body {
  font-family: "Vazirmatn", sans-serif;
  background-color: rgba(228, 230, 252, 0.85);
  color: #1c2042;
  margin: 0;
  padding: 0;
}

a {
  text-decoration: none;
}

li {
  list-style: none;
}

h1 {
  font-size: 32px;
}

h2 {
  font-size: 24px;
}

h3 {
  font-size: 18px;
}

p {
  font-size: 16px;
}

img {
  width: 100%;
  height: auto;
}

section {
  width: 80%;
  margin: 50px auto;
}

.btn {
  background-color: #1c2042;
  border: none;
  padding: 10px 14px;
  font-size: 16px;
  color: white;
  border-radius: 8px;
  display: inline-block;
  margin: 25px auto;
}

.navbar {
  background-color: #1c2042;
  color: #ffffff;
  padding: 10px 24px;
  height: 52px;
}

.navbar-logo {
  font-size: 30px;
  font-weight: 800;
  float: left;
}

.navbar__list {
  float: right;
}

.navbar__list-item {
  display: inline;
  font-size: 18px;
  margin: auto 8px;
}

.header {
  text-align: center;
  margin: 50px auto;
}

.about {
  width: 80%;
  margin: 50px auto;
  display: flex;
  align-items: center;
  justify-content: space-around;
  gap: 20px;
}

.about__description {
  width: 60%;
}

.about__image-container {
  width: 40%;
}

.project {
  text-align: center;
  width: 80%;
  margin: 50px auto;
}

.project-heading {
  margin-bottom: 32px;
}

.projects__container {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 20px;
}

.project-card {
  width: 32%;
  padding: 10px;
  border: 2px solid #1c2042;
  border-radius: 8px;
}

.project-card img {
  height: 320px;
}

.footer {
  text-align: center;
}

.footer__form {
  height: 64px;
}

.footer__form-input {
  font-size: 20px;
  padding: 8px 16px;
  display: inline-block;
  margin-right: 0;
}

.footer__form-btn {
  background-color: #1c2042;
  border: none;
  padding: 10px 20px;
  font-size: 20px;
  color: white;
  display: inline-block;
  margin-left: 0;
}

.footer-contact {
  display: inline-block;
  margin: 20px auto;
}

    </style>
  </head>
  <body>
    <!-- Navabar -->
    <nav class="navbar">
      <span class="navbar-logo">Kishore</span>
      <ul class="navbar__list">
        <li class="navbar__list-item">Home</li>
        <li class="navbar__list-item">About</li>
        <li class="navbar__list-item">Projects</li>
      </ul>
    </nav>
    <!-- Navabar -->
    <!-- Header -->
    <header class="header">
      <div class="header__data">
        <h1 style="margin: 20px auto;">Kishore Babu</h1>
        <p>Front End Web Developer</p>
      </div style="margin: 20px auto;">
      <a href="./images/brouchermin.pdf" download="" class="btn"
        >Download Resume</a
      >
    </header>
    <!-- Header -->
    <hr />
    <!-- About -->
    <section class="about">
      <div class="about__description">
        <h2>About Me</h2>
        <p>
          Hello. My name is Kishore Babu, I am a Front End Web Developer
          specialised in ReactJs
        </p>
      </div>
      <div class="about__image-container">
        <img
          src="https://images.unsplash.com/photo-1536104968055-4d61aa56f46a"
          alt="A Develope working on a Laptop"
          width="100px"
        />
      </div>
    </section>
    <!-- About -->
    <hr/>
    <!-- Projects -->
    <section class="project">
      <h2 class="project-heading">Projects</h2>
      <div class="projects__container">
        <div class="project-card">
          <img
            src="https://images.unsplash.com/photo-1608306448197-e83633f1261c"
            alt="A Black screen with HTML Code"
            width="100px"
          />
          <h3>Project One</h3>
          <p>This is my project developed using HTML & CSS</p>
          <a href="#" class="btn">View Project</a>
        </div>
        <div class="project-card">
          <img
            src="https://images.unsplash.com/photo-1608306448197-e83633f1261c"
            alt="A Black screen with HTML Code"
            width="100px"
          />
          <h3>Project Two</h3>
          <p>This is my project developed using HTML & CSS</p>
          <a href="#" class="btn">View Project</a>
        </div>
        <div class="project-card">
          <img
            src="./images/project.png"
            alt="A Black screen with HTML Code"
            width="100px"
          />
          <h3>Project Three</h3>
          <p>This is my project developed using HTML & CSS</p>
          <a href="#" class="btn">View Project</a>
        </div>
      </div>
    </section>
    <!-- Projects -->
    <hr/>
    <!-- Footer -->
    <footer class="footer">
      <h2>Subscribe to My Newsletter</h2>
        <form action="" class="footer__form">
          <input type="email" class="footer__form-input" placeholder="Email Address" />
          <button type="submit" class="footer__form-btn">Subscribe</button>
        </form>
        <span class="footer-contact">
            Contact Me at
            <a href="mailto:kishore@skilsafari.in" target="_blank">Email</a>
        </span>
    </footer>
    <!-- Footer -->
  </body>
</html>

<!-- <html> </html> -->
