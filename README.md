# FAITH-LIMO-
Personal portfolio website for Faith Chemurgor Limo — showcasing projects, resume, lab challenges, and skills in Data, AI, Python, and Virtual Assistance. Built with HTML, CSS, and Bootstrap.  
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Faith Chemurgor Limo - Portfolio</title>
  <meta name="description" content="Portfolio of Faith Chemurgor Limo - Aspiring Data & AI Specialist, Python Enthusiast, Virtual Assistant. Showcasing projects, skills, and experience.">

  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <!-- Icons -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons/font/bootstrap-icons.css">

  <style>
    body { scroll-behavior: smooth; }
    html { scroll-padding-top: 70px; }
    .hero {
      background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)),
                  url('https://source.unsplash.com/1600x900/?technology,laptop') center/cover no-repeat;
      height: 100vh;
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
    }
    .hero h1 { font-size: 3rem; font-weight: bold; }
    .section { padding: 60px 0; }
    .card:hover { transform: translateY(-5px); transition: 0.3s; box-shadow: 0 8px 20px rgba(0,0,0,0.15); }
    footer { background: #111; color: #ddd; padding: 20px 0; text-align: center; }
    footer a { color: #0d6efd; margin: 0 10px; text-decoration: none; }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
    <div class="container">
      <a class="navbar-brand" href="#">Faith Limo</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#resume">Resume</a></li>
          <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
          <li class="nav-item"><a class="nav-link" href="#labs">Lab Challenges</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="hero" id="home">
    <div class="container">
      <h1>Faith Chemurgor Limo</h1>
      <p class="lead">Aspiring Data & AI Specialist | Virtual Assistant | Lifelong Learner</p>
      <a href="#contact" class="btn btn-primary mt-3">Get in Touch</a>
    </div>
  </section>

  <!-- Resume Section -->
  <section class="section" id="resume">
    <div class="container text-center">
      <h2 class="mb-4">Resume</h2>
      <p><strong>Education:</strong> Diploma in Surgical Technology – AIC Kapsowar MTC (2024)</p>
      <p><strong>Ongoing Studies:</strong> Data & AI (Cyber Shujaa, ALX), Python Programming, Generative AI</p>
      <p><strong>Certifications:</strong> ALX Virtual Assistant, Python Essentials (Jenga Learning)</p>
      <p><strong>Skills:</strong> Data Analysis, Python, Generative AI, Virtual Assistance, Communication</p>
      <p><strong>Experience:</strong> Volunteer – Kenya Red Cross, Treasurer – Family Savings Group</p>
      <a href="Faith_Limo_Resume.pdf" class="btn btn-outline-primary mt-3" target="_blank"><i class="bi bi-download"></i> Download Resume</a>
    </div>
  </section>

  <!-- Projects Section -->
  <section class="section bg-light" id="projects">
    <div class="container">
      <h2 class="text-center mb-4">Projects</h2>
      <div class="row g-4">
        <div class="col-md-4">
          <div class="card h-100">
            <div class="card-body">
              <h5 class="card-title">Kaggle Data Analysis</h5>
              <p class="card-text">Exploratory data analysis and predictive modeling using Python and Pandas.</p>
              <a href="https://www.kaggle.com/faithchemurgorlimo" target="_blank" class="btn btn-outline-primary">View</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card h-100">
            <div class="card-body">
              <h5 class="card-title">Portfolio Website</h5>
              <p class="card-text">Personal portfolio website showcasing CV, projects, and lab challenges.</p>
              <a href="https://github.com/Faithchemurgor9" target="_blank" class="btn btn-outline-primary">View</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card h-100">
            <div class="card-body">
              <h5 class="card-title">Python Practice</h5>
              <p class="card-text">Hands-on Python exercises covering problem-solving, AI tools, and automation.</p>
              <a href="https://github.com/Faithchemurgor9" target="_blank" class="btn btn-outline-primary">View</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Lab Challenges Section -->
  <section class="section" id="labs">
    <div class="container">
      <h2 class="text-center mb-4">Lab Challenges</h2>
      <ul>
        <li><strong>Challenge 1:</strong> Data wrangling with Pandas – Learned efficient data cleaning.</li>
        <li><strong>Challenge 2:</strong> SQL Query Lab – Practiced database querying and joins.</li>
        <li><strong>Challenge 3:</strong> AI Tool Exploration – Experimented with Generative AI workflows.</li>
      </ul>
    </div>
  </section>

  <!-- Contact Section -->
  <section class="section bg-light" id="contact">
    <div class="container text-center">
      <h2 class="mb-4">Contact Me</h2>
      <p>Email: <a href="mailto:flimo9129@gmail.com">flimo9129@gmail.com</a></p>
      <p>Phone: +254 708 530 369</p>
      <p>
        <a href="https://www.linkedin.com/in/faith-limo-chemurgor" target="_blank"><i class="bi bi-linkedin"></i> LinkedIn</a> |
        <a href="https://github.com/Faithchemurgor9" target="_blank"><i class="bi bi-github"></i> GitHub</a> |
        <a href="https://www.kaggle.com/faithchemurgorlimo" target="_blank"><i class="bi bi-bar-chart"></i> Kaggle</a>
      </p>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Faith Chemurgor Limo | Built with Bootstrap</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
