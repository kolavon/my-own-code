<!DOCTYPE html>
<html lang="en">
<head>
  <title>My Personal Website</title>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <!-- Bootstrap CDN -->
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/5.0.0-alpha1/css/bootstrap.min.css">
  <!-- Custom CSS -->
  <style>
    /* Add your custom CSS here */
    .jumbotron {
      background-image: url("https://1drv.ms/i/s!AoQycDe3PqNQgVNtcSa0Nwhxq0tq?e=k3mDXc");
      background-size: cover;
      color: rgb(255, 255, 255);
    }

    .navbar {
      background-color: transparent;
    }

    .navbar-brand {
      font-weight: bold;
      font-size: 24px;
    }

    .navbar-nav li a {
      color: rgb(0, 0, 0);
    }

    .card {
      margin: 20px;
    }

    .card-img-top {
      height: 200px;
      object-fit: cover;
    }

    .card-body {
      text-align: center;
    }

    .card-title {
      font-weight: bold;
    }

    .card-text {
      font-style: italic;
    }

    .contact-form {
      margin: 20px;
    }

    .contact-form input, .contact-form textarea {
      width: 100%;
    }

    .contact-form button {
      margin-top: 10px;
    }

    .footer {
      background-color: #333;
      color: rgb(248, 82, 82);
      padding: 20px;
      text-align: center;
    }

    .footer a {
      color: white;
    }
  </style>
</head>
<body>
  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg fixed-top">
    <div class="container">
      <a class="navbar-brand" href="#">My Name</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item active">
            <a class="nav-link" href="#home">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#about">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#portfolio">Portfolio</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <!-- Hero Header -->
  <div class="jumbotron" id="home">
    <div class="container">
      <h1 class="display-4">Hello, world!</h1>
      <p class="lead">I am a web developer and a web designer.</p>
      <p class="lead">I create beautiful and responsive websites using HTML, CSS, JavaScript, and Bootstrap.</p>
      <p class="lead">I am passionate about learning new technologies and creating awesome web experiences.</p>
      <a class="btn btn-primary btn-lg" href="#contact" role="button">Hire Me</a>
    </div>
  </div>
  <!-- About Section -->
  <div class="container" id="about">
    <h2 class="text-center">About Me</h2>
    <p class="text-center">I am a self-taught web developer and a web designer based in Sharjah, UAE. I have been developing websites for over two years and I love what I do. I have a bachelor's degree in computer science and a master's degree in software engineering. I have worked on various projects, ranging from personal blogs to e-commerce websites. I am proficient in HTML, CSS, JavaScript, jQuery, Bootstrap, PHP, MySQL, WordPress, and more. I am always eager to learn new skills and explore new challenges.</p>
    <p class="text-center">When I am not coding, I enjoy reading books, playing games, and traveling. I am also interested in photography, music, and art. I am a friendly and easy-going person who likes to work in a team and communicate with clients. I am always open to feedback and suggestions to improve my work and deliver the best results.</p>
  </div>
  <!-- Portfolio Section -->
  <div class="container" id="portfolio">
    <h2 class="text-center">My Portfolio</h2>
    <p class="text-center">Here are some of the websites that I have created or contributed to. You can click on the images to visit the live websites.</p>
    <div class="row">
      <!-- Portfolio Item 1 -->
      <div class="col-md-4">
        <div class="card">
          <img src="https://thumbs.dreamstime.com/b/macho-concentrated-face-reading-book-scandalous-bestseller-concept-guy-reading-book-attention-man-beard-mustache-142321448.jpg" class="card-img-top" alt="Portfolio 1">
          <div class="card-body">
            <h5 class="card-title">Portfolio 1</h5>
            <p class="card-text">personal Website for a storyteler.</p>
            <a href="file:///C:/Users/jmeke/New%20folder/my%20own%20code.html" class="btn btn-primary">Visit Website</a>
          </div>
        </div>
      </div>
      <!-- Portfolio Item 2 -->
      <div class="col-md-4">
        <div class="card">
          <img src="https://www.kasandbox.org/programming-images/landscapes/lava.png" class="card-img-top" alt="Portfolio 2">
          <div class="card-body">
            <h5 class="card-title">Portfolio 2</h5>
            <p class="card-text">A landing page for a travel agency.</p>
            <a href="file:///C:/Users/jmeke/New%20folder/land%20of%20doooooooooooooooooooom.html" class="btn btn-primary">Visit Website</a>
          </div>

        </div>
      </div>
      <!-- Portfolio Item 3 -->
      <div class="col-md-4">
        <div class="card">
          <img src=" https://p.im9.eu/you-dont-say-meme-face.jpg" class="card-img-top" alt="Portfolio 3">
          <div class="card-body">
            <h5 class="card-title">Portfolio 3</h5>
            <p class="card-text">An online store for a fashion brand.</p>
            <a href="https://www.youtube.com/watch?v=7WGTRMl0G-o" class="btn btn-primary">Visit Website</a>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- Contact Section -->
  <form action="mailto:yourname@example.com" method="post" enctype="text/plain">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required><br>
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required><br>
    <label for="subject">Subject:</label>
    <input type="text" id="subject" name="subject" required><br>
    <label for="message">Message:</label>
    <textarea id="message" name="message" rows="4" cols="40" required></textarea><br>
    <input type="submit" value="Send">
    <input type="reset" value="Reset">
  </form>
  
