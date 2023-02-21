# sagar.github.io

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>My Portfolio</title>
    <!-- Custom CSS -->
    <link href="./style.css" rel="stylesheet" />
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
