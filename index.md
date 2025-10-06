<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bharat Shewale | Data Scientist</title>
  <style>
        :root {
      --primary: #2563eb;
      --secondary: #1e3a8a;
      --bg: #f8fafc;
      --text: #1f2937;
      --white: #fff;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }

    header {
      background: linear-gradient(135deg, var(--secondary), var(--primary));
      color: var(--white);
      text-align: center;
      padding: 80px 20px;
      border-bottom-left-radius: 60px;
      border-bottom-right-radius: 60px;
    }

    header h1 {
      font-size: 2.8rem;
      margin-bottom: 8px;
    }

    header p {
      font-size: 1.2rem;
    }

    nav {
      background: var(--white);
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
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
    }

    nav a:hover {
      color: var(--primary);
    }

    section {
      max-width: 1100px;
      margin: 60px auto;
      padding: 0 20px;
    }

    h2 {
      text-align: center;
      color: var(--secondary);
      font-size: 1.8rem;
      margin-bottom: 30px;
      position: relative;
    }

    h2::after {
      content: "";
      width: 60px;
      height: 4px;
      background: var(--primary);
      display: block;
      margin: 8px auto 0;
      border-radius: 5px;
    }

    /* About Section */
    .about p {
      font-size: 1.05rem;
      text-align: center;
      max-width: 800px;
      margin: auto;
    }

    /* Skills Section */
    .skills {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 15px;
    }

    .skill {
      background: var(--white);
      border: 2px solid #e5e7eb;
      border-radius: 10px;
      padding: 10px 20px;
      font-weight: 600;
      box-shadow: 0 2px 5px rgba(0,0,0,0.05);
      transition: transform 0.2s;
    }

    .skill:hover {
      transform: scale(1.05);
      border-color: var(--primary);
    }

    /* Projects Section */
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 25px;
    }

    .project-card {
      background: var(--white);
      border-radius: 15px;
      padding: 25px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.08);
      transition: transform 0.3s;
    }

    .project-card:hover {
      transform: translateY(-8px);
    }

    .project-card h3 {
      color: var(--primary);
      margin-bottom: 10px;
    }

    .btn {
      display: inline-block;
      margin-top: 10px;
      padding: 8px 14px;
      background: var(--primary);
      color: white;
      text-decoration: none;
      border-radius: 8px;
      font-size: 0.9rem;
      transition: background 0.3s;
    }

    .btn:hover {
      background: var(--secondary);
    }

    /* Resume Section */
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
    }

    .resume-btn:hover {
      background: #059669;
    }

    /* Contact Section */
    .contact {
      text-align: center;
    }

    .contact a {
      color: var(--primary);
      text-decoration: none;
      font-weight: 500;
      display: block;
      margin: 6px 0;
    }

    .contact a:hover {
      text-decoration: underline;
    }

    footer {
      background: var(--secondary);
      color: white;
      text-align: center;
      padding: 25px;
      margin-top: 60px;
      border-top-left-radius: 40px;
      border-top-right-radius: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Bharat Shewale</h1>
    <p>Data Scientist | Machine Learning & Deep Learning Enthusiast | Transforming data into Insights</p>
  </header>

  <section>
    <h2>About Me</h2>
    <p>
      Data Scientist with 3 years of experience in machine learning, data analysis, and process optimization across logistics, entrepreneurial, and academic projects. Skilled in Python, SQL, Power BI, and predictive modeling.
    </p>
  </section>

  <section>
    <h2>Projects</h2>
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
      <h3>Onlineb Retail Customer Segmentation</h3>
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
  </section>

  <section>
    <h2>Resume</h2>
    <p><a href="resume.pdf" target="_blank">Download My Resume</a></p>
  </section>

  <section>
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
