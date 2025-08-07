# index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>VIVEK ANILKUMAR - BCA Graduate Portfolio</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
      color: #333;
    }
    header {
      background-color: #292b2c;
      color: #fff;
      padding: 1rem;
      text-align: center;
      animation: fadeInDown 1.5s ease-out;
    }
    header img.logo {
      width: 80px;
      border-radius: 50%;
      margin-bottom: 10px;
    }
    .profile-pic {
      display: block;
      margin: 1rem auto;
      border-radius: 10px;
      width: 200px;
      height: auto;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
      animation: fadeInUp 1.5s ease-out;
    }
    section {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
      background-color: #fff;
      margin-bottom: 1rem;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      animation: fadeIn 1s ease-in;
    }
    h2 {
      color: #007bff;
    }
    ul {
      padding-left: 1.2rem;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background-color: #292b2c;
      color: #fff;
    }
    a {
      color: #007bff;
      text-decoration: none;
    }
    @keyframes fadeIn {
      from {opacity: 0; transform: translateY(10px);}
      to {opacity: 1; transform: translateY(0);}
    }
    @keyframes fadeInDown {
      from {opacity: 0; transform: translateY(-20px);}
      to {opacity: 1; transform: translateY(0);}
    }
    @keyframes fadeInUp {
      from {opacity: 0; transform: translateY(20px);}
      to {opacity: 1; transform: translateY(0);}
    }
  </style>
</head>
<body>
  <header>
    <img src="https://via.placeholder.com/80" alt="Logo" class="logo" />
    <h1>VIVI</h1>
    <p>BCA Graduate | Tech Enthusiast | Quick Learner</p>
  </header>

  <img src="https://via.placeholder.com/200x250" alt="Profile Picture" class="profile-pic" />

  <section>
    <h2>Career Objective</h2>
    <p>Motivated and hardworking BCA graduate seeking an entry-level position in the tech industry. Passionate about learning new technologies and solving real-world problems. Committed to continuous growth and adding value through dedication and adaptability.</p>
  </section>

  <section>
    <h2>Technical Skills</h2>
    <ul>
      <li><strong>Languages:</strong> HTML, CSS, JavaScript, Python, C</li>
      <li><strong>Web Dev:</strong> Responsive design, hosting basics</li>
      <li><strong>Databases:</strong> MySQL (Basics)</li>
      <li><strong>Tools:</strong> VS Code, GitHub, Canva, MS Office</li>
    </ul>
  </section>

  <section>
    <h2>Academic Project</h2>
    <p><strong>Project Name:</strong> Smart Price Compare – A Price Comparison Website</p>
    <p><strong>Role:</strong> Front-end Designer & Data Integrator</p>
    <p><strong>Description:</strong> Developed a basic price comparison platform that allows users to compare product prices across multiple e-commerce platforms. Implemented UI and filters using dummy data.</p>
    <p><strong>Technologies Used:</strong> HTML, CSS, JavaScript</p>
  </section>

  <section>
    <h2>Achievements</h2>
    <ul>
      <li>Top 7% in TANCET 2025 (15,000+ candidates)</li>
      <li>Top 15% in NIMCET 2025 (30,000+ candidates)</li>
    </ul>
  </section>

  <section>
    <h2>College Activities</h2>
    <ul>
      <li><strong>Hindi Literary Committee Secretary:</strong> Organized events, ramp walks, and participated in drama/cosplay.</li>
      <li><strong>English Literary Committee Member:</strong> Participated in debates, speeches, and dance programs.</li>
      <li><strong>NCC Volunteer:</strong> Conducted seminars and food stalls during college fests.</li>
    </ul>
  </section>

  <section>
    <h2>Contact</h2>
    <p><strong>Email:</strong> your.email@example.com</p>
    <p><strong>Phone:</strong> +91-XXXXXXXXXX</p>
    <p><strong>GitHub / LinkedIn / Portfolio:</strong> <a href="#">Add your links here</a></p>
  </section>

  <footer>
    <p>&copy; 2025 VIVI. All rights reserved.</p>
  </footer>
</body>
</html>
