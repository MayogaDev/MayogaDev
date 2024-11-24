<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Welcome to the GitHub Portfolio of Jharold Mayorga. Explore innovative projects in AI, Game Development, and impactful technology solutions.">
  <title>Jharold Mayorga | GitHub Portfolio</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <style>
    body {
      font-family: 'Arial', sans-serif;
      line-height: 1.6;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
      color: #333;
    }

    header {
      background: linear-gradient(45deg, #0066cc, #00ccff);
      color: white;
      padding: 2rem 0;
      text-align: center;
      animation: fadeInHeader 2s ease-in-out;
    }

    header h1 {
      font-size: 3rem;
      margin-bottom: 0.5rem;
    }

    header p {
      font-size: 1.3rem;
      margin: 0;
    }

    .container {
      max-width: 1200px;
      margin: auto;
      overflow: hidden;
      padding: 1rem 2rem;
    }

    section {
      margin: 2rem 0;
      padding: 1.5rem;
      border-radius: 10px;
      background: white;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }

    h2 {
      color: #0066cc;
      text-align: center;
      margin-bottom: 1.5rem;
    }

    .badge {
      display: inline-block;
      background-color: #0066cc;
      color: white;
      padding: 0.4rem 0.7rem;
      font-size: 0.9rem;
      border-radius: 5px;
      margin-right: 0.5rem;
    }

    .project {
      display: flex;
      gap: 2rem;
      margin-bottom: 2rem;
      align-items: center;
      animation: slideIn 1s ease-in-out;
    }

    .project img {
      max-width: 300px;
      border-radius: 10px;
    }

    .project-details {
      flex-grow: 1;
      text-align: justify;
    }

    .project-details h3 {
      color: #333;
      margin-bottom: 0.5rem;
    }

    .project-details a {
      display: inline-block;
      margin-top: 1rem;
      padding: 0.5rem 1rem;
      background: #00ccff;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      transition: 0.3s;
    }

    .project-details a:hover {
      background: #0066cc;
    }

    .skills ul {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 1rem;
      list-style: none;
      padding: 0;
    }

    .skills li {
      background: #0066cc;
      color: white;
      padding: 0.8rem;
      text-align: center;
      border-radius: 10px;
      font-size: 0.9rem;
    }

    .contact-icons a {
      margin: 0 1rem;
      color: #0066cc;
      font-size: 2rem;
      text-decoration: none;
      transition: 0.3s;
    }

    .contact-icons a:hover {
      color: #00ccff;
    }

    footer {
      text-align: center;
      padding: 1rem 0;
      background: #333;
      color: white;
    }

    .animation-hover:hover {
      transform: scale(1.05);
      transition: transform 0.3s ease-in-out;
    }

    @keyframes fadeInHeader {
      0% { opacity: 0; transform: translateY(-30px); }
      100% { opacity: 1; transform: translateY(0); }
    }

    @keyframes slideIn {
      0% { opacity: 0; transform: translateX(-50px); }
      100% { opacity: 1; transform: translateX(0); }
    }
  </style>
</head>
<body>

<header>
  <h1>🌟 Welcome to My GitHub Portfolio! 🌟</h1>
  <p>Hello! I'm <strong>Jharold Mayorga</strong>, a passionate software developer creating solutions that combine innovation and impact.</p>
</header>

<div class="container">

  <!-- About Section -->
  <section>
    <h2>🧑‍💻 About Me</h2>
    <p>
      🎓 Specialist in Artificial Intelligence, Game Development, and Scalable Software Architectures.  
      🌐 I aim to build technological solutions that foster inclusion, accessibility, and innovation.  
      🛠️ Every project here is a reflection of my dedication to using technology for positive social change.
    </p>
  </section>

  <!-- Projects Section -->
  <section>
    <h2>🏆 Featured Projects</h2>
    <div class="project">
      <img src="https://via.placeholder.com/300x200" alt="Tourist Routes">
      <div class="project-details">
        <h3>📍 Recommendation System for Tourist Routes</h3>
        <span class="badge">C++</span>
        <span class="badge">Fuzzy Logic</span>
        <p>Personalized tourist routes for Arequipa City using fuzzy logic and user preferences. Published in IEEE.</p>
        <a href="https://doi.org/10.1109/Colcom56784.2022.10107831" target="_blank">View Paper</a>
      </div>
    </div>

    <div class="project">
      <img src="https://via.placeholder.com/300x200" alt="GalaxyVenture">
      <div class="project-details">
        <h3>🚀 GalaxyVenture</h3>
        <span class="badge">Three.js</span>
        <span class="badge">WebGL</span>
        <p>An interactive 3D planetary exploration game presented at NASA International Space Apps Challenge 2023.</p>
        <a href="https://mayogadev.github.io/GalaxyVenture/" target="_blank">Explore Now</a>
      </div>
    </div>
    <!-- Add more projects -->
  </section>

  <!-- Skills Section -->
  <section class="skills">
    <h2>💻 Skills</h2>
    <ul>
      <li>Python</li>
      <li>JavaScript</li>
      <li>C#</li>
      <li>Unity</li>
      <li>React.js</li>
      <li>TensorFlow</li>
      <li>Three.js</li>
      <li>MongoDB</li>
    </ul>
  </section>

  <!-- Contact Section -->
  <section>
    <h2>🔗 Connect with Me</h2>
    <div class="contact-icons">
      <a href="https://www.linkedin.com/in/jharold-mayorga" target="_blank"><i class="fab fa-linkedin"></i></a>
      <a href="mailto:jmayorgav@unsa.edu.pe" target="_blank"><i class="fas fa-envelope"></i></a>
      <a href="https://github.com/mayogadev" target="_blank"><i class="fab fa-github"></i></a>
    </div>
  </section>
</div>

<footer>
  <p>✨ "Technology is only limited by our imagination." ✨</p>
</footer>

</body>
</html>
