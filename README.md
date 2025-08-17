 <!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Orchere Tumurekeyisoni — Portfolio</title>
  <style>
    /* Base styles */
    body {font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; margin: 0; background: #f0f4f8; color: #333;}
    a {color: #1a73e8; text-decoration: none;}
    a:hover {text-decoration: underline;}
    
    /* Header & nav */
    header {background: #1f2937; color: #fff; padding: 1.5rem; text-align: center;}
    header h1 {margin: 0.2rem 0;}
    header p {margin: 0.5rem 0 1rem 0; font-size: 1.1rem;}
    nav a {margin: 0 12px; color: #fff; font-weight: bold;}
    
    /* Main container */
    .container {max-width: 900px; margin: 2rem auto; padding: 1rem;}
    section {margin-bottom: 2.5rem;}
    h2 {color: #1f2937; border-bottom: 2px solid #1a73e8; padding-bottom: 0.3rem;}
    
    /* Cards */
    .card {background: #fff; padding: 1.5rem; border-radius: 10px; box-shadow: 0 4px 10px rgba(0,0,0,0.08); margin-top: 1rem;}
    
    /* Footer */
    footer {background: #1f2937; color: #fff; text-align: center; padding: 1rem; margin-top: 2rem;}
  </style>
</head>
<body>
  <header>
    <h1>Orchere Tumurekeyisoni</h1>
    <p>Aspiring Software Engineer • ALX Rwanda Pathway</p>
    <nav>
      <a href="#bio">Bio</a>
      <a href="#portfolio">Portfolio</a>
      <a href="#elevator">Elevator Pitch</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main class="container">
    <section id="bio">
      <h2>Bio</h2>
      <div class="card">
        <p>My name is Orchere Tumurekeyisoni, an ALX Rwanda Pathway student focusing on software engineering and entrepreneurship. I am passionate about using technology to solve real-world problems and improve community life. With experience in teamwork, problem-solving, and project development, I aim to create practical and innovative solutions. I am dedicated to continuous learning and applying my skills to projects that make a meaningful impact.</p>
      </div>
    </section>

    <section id="portfolio">
      <h2>Portfolio</h2>
      <div class="card">
        <p><strong>Phase 2 Project Video:</strong> <a href="https://youtu.be/2Whi0xpohVQ" target="_blank">Watch Here</a></p>
        <p><strong>Phase 2 Project Slides (PDF/Google Slides):</strong> <a href="https://docs.google.com/presentation/d/155eu4e8yNDUDhT9Kv7xCil77qA19wPNNFCUl5puY7J4/edit?usp=sharing" target="_blank">View Slides</a></p>
      </div>
    </section>

    <section id="elevator">
      <h2>Elevator Pitch</h2>
      <div class="card">
        <p>Hello, my name is Orchere Tumurekeyisoni, and I am currently an ALX Rwanda student in the Pathway Program, focusing on software engineering and entrepreneurship. I have experience in problem-solving, teamwork, and leveraging technology to create simple but impactful solutions. What makes me stand out is my passion for connecting technology to real-life community needs, such as improving access to healthcare and supporting local innovation. I can help organizations solve problems efficiently and create solutions that make life easier for their users. I am seeking opportunities to contribute to technology-driven projects where I can apply my skills, deliver value, and continue to grow professionally. Thank you for considering me, and I look forward to connecting with you.</p>
      </div>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <div class="card">
        <p>Email: <a href="mailto:orcheretumurekeyisoni@gmail.com">orcheretumurekeyisoni@gmail.com</a></p>
        <p>LinkedIn: <a href="#" target="_blank">Add Link</a></p>
      </div>
    </section>
  </main>

  <footer>
    <p>© <span id="year"></span> Orchere Tumurekeyisoni</p>
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
