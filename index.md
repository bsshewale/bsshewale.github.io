<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bharat Shewale | Data Scientist</title>
  <style>
    :root {
      --primary: #2563eb;
      --secondary: #1e3a8a;
      --bg-gradient: linear-gradient(135deg, #e0f2fe, #f8fafc, #e0f7fa);
      --text: #1f2937;
      --white: #ffffff;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', sans-serif;
      background: var(--bg-gradient);
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
      box-shadow: 0 8px 25px rgba(0,0,0,0.2);
    }

    header h1 {
      font-size: 3rem;
      margin-bottom: 10px;
      letter-spacing: 1px;
    }

    header p {
      font-size: 1.25rem;
      opacity: 0.9;
    }

    nav {
      background: var(--white);
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
      position: sticky;
      top: 0;
      z-index: 10;
      border-bottom: 2px solid #e5e7eb;
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
      transition: 0.3s;
    }

    nav a:hover {
      color: var(--primary);
      text-shadow: 0 0 8px rgba(37,99,235,0.4);
    }

    section {
      max-width: 1100px;
      margin: 60px auto;
      padding: 0 20px;
    }

    h2 {
      text-align: center;
      color: var(--secondary);
      font-size: 1.9rem;
      margin-bottom: 30px;
      position: relative;
    }

    h2::after {
      content: "";
      width: 70px;
      height: 4px;
      background: var(--primary);
      display: block;
      margin: 10px auto 0;
      border-radius: 5px;
    }

    /* About Section */
    .about p {
      font-size: 1.1rem;
      text-align: center;
      max-width: 800px;
      margin: auto;
    }

    /* Projects Section */
    .project {
      background: var(--white);
      border-radius: 15px;
      padding: 25px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
      margin-bottom: 25px;
      transition: all 0.3s ease-in-out;
    }

    .project:hover {
      transform: translateY(-6px);
      box-shadow: 0 10px 30px rgba(37,99,235,0.2);
    }

    .project h3 {
      color: var(--primary);
      margin-bottom: 10px;
      font-size: 1.3rem;
    }

    .project p {
      font-size: 1rem;
      color: #4b5563;
      margin-bottom: 10px;
    }

    .project a {
      color: var(--white);
      background: var(--primary);
      padding: 8px 14px;
      text-decoration: none;
      border-radius: 8px;
      font-size: 0.9rem;
      font-weight: 500;
      transition: 0.3s;
    }

    .project a:hover {
      background: var(--secondary);
    }

    /* Resume Section */
    .resume-btn {
      display: inline-block;
      text-align: center;
      margin: 20px auto;
      padding: 12px 30px;
      background: #10b981;
      border-radius: 12px;
      color: white;
      font-weight: 600;
      text-decoration: none;
      font-size: 1rem;
      transition: background 0.3s ease;
    }

    .resume-btn:hover {
      background: #059669;
      transform: translateY(-2px);
    }

    /* Contact Section */
    .contact {
      text-align: center;
      font-size: 1rem;
    }

    .contact a {
      color: var(--primary);
      text-decoration: none;
      font-weight: 500;
      display: block;
      margin: 8px 0;
      transition: 0.3s;
    }

    .contact a:hover {
      text-decoration: underline;
      color: var(--secondary);
    }

    footer {
      background: var(--secondary);
      color: white;
      text-align: center;
      padding: 25px;
      margin-top: 80px;
      border-top-left-radius: 40px;
      border-top-right-radius: 40px;
      box-shadow: 0 -5px 20px rgba(0,0,0,0.2);
    }
  </style>
</head>
<body>
  <header>
    <h1>Bharat Shewale</h1>
    <p>Data Scientist | Machine Learning & Deep Learning Enthusiast | Transforming Data into Insights</p>
  </header>

  <nav>
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#resume">Resume</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <section id="about" class="about">
    <h2>About Me</h2>
    <p>
      Data Scientist with 3 years of experience in machine learning, data analysis, and process optimization across logistics, entrepreneurial, and academic projects. Skilled in Python, SQL, Power BI, and predictive modeling.
    </p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Hotel Booking Data Analysis</h3>
      <p>Exploratory analysis of hotel booking trends to identify customer behaviors and improve business strategy.</p>
      <a href="https://github.com/bsshewale/Hotel_Booking_Data_Analysis" target="_blank">View Project</a>
    </div>
    <div class="project">
      <h3>COVID Tweets Sentiment Analysis</h3>
      <p>Built ML model to classify COVID-related tweets into positive, negative, and neutral sentiments.</p>
      <a href="https://github.com/bsshewale/Coronavirus-tweet-sentiment-analysis" target="_blank">View Project</a>
    </div>
    <div class="project">
      <h3>Online Retail Customer Segmentation</h3>
      <p>Applied clustering techniques on retail data to segment customers for targeted marketing campaigns.</p>
      <a href="https://github.com/bsshewale/Online-retail-customer-segmentation" target="_blank">View Project</a>
    </div>
    <div class="project">
      <h3>Voyage Analytics Integrating MLOps in Travel Industry</h3>
      <p>Analyzed 271K+ flight and hotel records and built predictive ML pipelines to optimize travel pricing and improve decision-making.</p>
      <a href="https://github.com/bsshewale/Voyage-Analytics-Integrating-MLOps-in-Travel-Industry" target="_blank">View Project</a>
    </div>
    <div class="project">
      <h3>Automatic Movable Sprinkler System</h3>
      <p>Developed an automatic movable sprinkler system to reduce irrigation effort, improve water efficiency, and lay the groundwork for future AI/ML-based optimization.</p>
      <a href="https://drive.google.com/file/d/13hK6kNKuXBLJ30VxtsgYs6Z3jiMAq3fW/view?usp=sharing" target="_blank">View Project</a>
    </div>
  </section>

  <section id="resume">
    <h2>Resume</h2>
    <a class="resume-btn" href="resume.pdf" target="_blank">Download My Resume</a>
  </section>

  <section id="contact" class="contact">
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
