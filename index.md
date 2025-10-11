<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Bharat Shewale | Data Scientist</title>

  <style>
    /* ===== Root Colors ===== */
    :root {
      --primary: #00b4d8;
      --secondary: #0077b6;
      --accent: #90e0ef;
      --bg: #0d1117;
      --card-bg: #161b22;
      --text: #e6edf3;
      --white: #ffffff;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', sans-serif;
      background: radial-gradient(circle at 20% 20%, #001219, #0a192f, #000814);
      background-attachment: fixed;
      color: var(--text);
      line-height: 1.7;
      overflow-x: hidden;
      position: relative;
    }

    /* ===== Animated Background Glow ===== */
    body::before {
      content: "";
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: radial-gradient(circle at 70% 30%, rgba(0,180,216,0.2), transparent 60%),
                  radial-gradient(circle at 30% 80%, rgba(0,119,182,0.2), transparent 60%);
      animation: moveGlow 12s ease-in-out infinite alternate;
      z-index: -1;
    }

    @keyframes moveGlow {
      0% { background-position: 0 0, 100% 100%; }
      100% { background-position: 100% 100%, 0 0; }
    }

    header {
      background: linear-gradient(135deg, var(--secondary), var(--primary));
      color: var(--white);
      text-align: center;
      padding: 80px 20px;
      border-bottom-left-radius: 60px;
      border-bottom-right-radius: 60px;
      box-shadow: 0 5px 20px rgba(0, 180, 216, 0.3);
    }

    header h1 {
      font-size: 2.8rem;
      margin-bottom: 8px;
      text-shadow: 0 0 15px rgba(0, 180, 216, 0.6);
    }

    header p {
      font-size: 1.2rem;
      opacity: 0.9;
    }

    nav {
      background: rgba(22,27,34,0.85);
      backdrop-filter: blur(10px);
      box-shadow: 0 2px 10px rgba(0,0,0,0.3);
      position: sticky;
      top: 0;
      z-index: 10;
    }

    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 15px;
    }

    nav a {
      color: var(--text);
      text-decoration: none;
      font-weight: 600;
      transition: color 0.3s ease, text-shadow 0.3s ease;
    }

    nav a:hover {
      color: var(--accent);
      text-shadow: 0 0 8px var(--primary);
    }

    section {
      max-width: 1100px;
      margin: 60px auto;
      padding: 0 20px;
    }

    h2 {
      text-align: center;
      color: var(--accent);
      font-size: 1.8rem;
      margin-bottom: 30px;
      position: relative;
      text-shadow: 0 0 10px rgba(144,224,239,0.5);
    }

    h2::after {
      content: "";
      width: 60px;
      height: 4px;
      background: var(--primary);
      display: block;
      margin: 8px auto 0;
      border-radius: 5px;
      box-shadow: 0 0 10px var(--primary);
    }

    /* ===== About Section ===== */
    .about p {
      font-size: 1.05rem;
      text-align: center;
      max-width: 800px;
      margin: auto;
      opacity: 0.9;
    }

    /* ===== Skills Section ===== */
    .skills {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 15px;
    }

    .skill {
      background: var(--card-bg);
      border: 1px solid rgba(255,255,255,0.05);
      border-radius: 10px;
      padding: 10px 20px;
      font-weight: 600;
      box-shadow: 0 0 10px rgba(0,0,0,0.2);
      transition: all 0.3s ease;
    }

    .skill:hover {
      transform: scale(1.05);
      border-color: var(--primary);
      box-shadow: 0 0 20px rgba(0,180,216,0.3);
    }

    /* ===== Projects Section ===== */
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 25px;
    }

    .project {
      background: var(--card-bg);
      border-radius: 15px;
      padding: 25px;
      box-shadow: 0 5px 20px rgba(0,0,0,0.3);
      border: 1px solid rgba(255,255,255,0.05);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .project:hover {
      transform: translateY(-8px);
      box-shadow: 0 0 25px rgba(0,180,216,0.3);
      border-color: var(--primary);
    }

    .project h3 {
      color: var(--primary);
      margin-bottom: 10px;
      text-shadow: 0 0 8px rgba(0,180,216,0.5);
    }

    .project p {
      opacity: 0.85;
      line-height: 1.6;
    }

    .project a {
      display: inline-block;
      margin-top: 10px;
      padding: 8px 14px;
      background: var(--primary);
      color: white;
      text-decoration: none;
      border-radius: 8px;
      font-size: 0.9rem;
      transition: background 0.3s, box-shadow 0.3s;
    }

    .project a:hover {
      background: var(--secondary);
      box-shadow: 0 0 15px rgba(0,119,182,0.6);
    }

    /* ===== Resume Section ===== */
    .resume-btn {
      display: block;
      width: 220px;
      text-align: center;
      margin: 30px auto;
      padding: 12px 0;
      background: #10b981;
      border-radius: 10px;
      color: white;
      font-weight: 600;
      text-decoration: none;
      box-shadow: 0 0 20px rgba(16,185,129,0.3);
      transition: all 0.3s ease;
    }

    .resume-btn:hover {
      background: #059669;
      box-shadow: 0 0 25px rgba(5,150,105,0.5);
    }

    /* ===== Contact Section ===== */
    .contact {
      text-align: center;
    }

    .contact a {
      color: var(--accent);
      text-decoration: none;
      font-weight: 500;
      display: block;
      margin: 6px 0;
      transition: color 0.3s;
    }

    .contact a:hover {
      color: var(--primary);
      text-shadow: 0 0 8px var(--primary);
    }

    footer {
      background: var(--card-bg);
      color: white;
      text-align: center;
      padding: 25px;
      margin-top: 60px;
      border-top: 1px solid rgba(255,255,255,0.1);
      box-shadow: 0 -2px 15px rgba(0,180,216,0.2);
    }
  </style>
</head>

<body>
  <header>
    <h1>Bharat Shewale</h1>
    <p>Data Scientist | Machine Learning & Deep Learning Enthusiast | Transforming Data into Insights</p>
  </header>

  <section class="about">
    <h2>About Me</h2>
    <p>
      Data Scientist with 3 years of experience in machine learning, data analysis, and process optimization across logistics, entrepreneurial, and academic projects. Skilled in Python, SQL, Power BI, and predictive modeling.
    </p>
  </section>

  <section>
    <h2>Projects</h2>
    <div class="projects">
      <div class="project">
        <h3>Hotel Booking Data Analysis</h3>
        <p>Exploratory analysis of hotel booking trends to identify customer behaviors and improve business strategy.</p>
        <a href="https://github.com/bsshewale/Hotel_Booking_Data_Analysis">View Project</a>
      </div>

      <div class="project">
        <h3>COVID Tweets Sentiment Analysis</h3>
        <p>Built ML model to classify COVID-related tweets into positive, negative, and neutral sentiments.</p>
        <a href="https://github.com/bsshewale/Coronavirus-tweet-sentiment-analysis">View Project</a>
      </div>

      <div class="project">
        <h3>Online Retail Customer Segmentation</h3>
        <p>Applied clustering techniques on retail data to segment customers for targeted marketing campaigns.</p>
        <a href="https://github.com/bsshewale/Online-retail-customer-segmentation">View Project</a>
      </div>

      <div class="project">
        <h3>Voyage Analytics Integrating MLOps in Travel Industry</h3>
        <p>Analyzed 271K+ flight and hotel records and built predictive ML pipelines to optimize travel pricing and improve decision-making.</p>
        <a href="https://github.com/bsshewale/Voyage-Analytics-Integrating-MLOps-in-Travel-Industry">View Project</a>
      </div>

      <div class="project">
        <h3>Automatic Movable Sprinkler System</h3>
        <p>Developed an automatic movable sprinkler system to reduce irrigation effort, improve water efficiency, and lay the groundwork for future AI/ML-based optimization.</p>
        <a href="https://drive.google.com/file/d/13hK6kNKuXBLJ30VxtsgYs6Z3jiMAq3fW/view?usp=sharing">View Project</a>
      </div>
    </div>
  </section>

  <section>
    <h2>Resume</h2>
    <p><a href="resume.pdf" target="_blank" class="resume-btn">Download My Resume</a></p>
  </section>

  <section class="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:bsshewale1630@gmail.com">bsshewale1630@gmail.com</a></p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/bharatshewale/" target="_blank">Welcome to my LinkedIn Profile</a></p>
    <p>GitHub: <a href="https://github.com/bsshewale" target="_blank">Welcome to my GitHub Profile</a></p>
  </section>

  <footer>
    <p>© 2025 Bharat Shewale | Data Science Portfolio</p>
  </footer>
</body>
</html>
