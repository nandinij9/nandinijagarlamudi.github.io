<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nandini Jagarlamudi Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet" />
  <style>
    * {
      margin: 0;
      padding: 0;
      font-family: 'Poppins', sans-serif;
      box-sizing: border-box;
    }

    body {
      background: #f9f9f9;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(90deg, #6a11cb, #2575fc);
      color: white;
      padding: 2rem;
      text-align: center;
    }

    section {
      padding: 2rem;
      margin: 1rem auto;
      max-width: 1000px;
      background-color: white;
      border-radius: 8px;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    }

    h2 {
      color: #2575fc;
      margin-bottom: 1rem;
      border-bottom: 2px solid #eee;
      padding-bottom: 0.5rem;
    }

    ul {
      padding-left: 1.2rem;
    }

    li {
      margin-bottom: 0.5rem;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 1rem;
    }

    .project-card {
      border: 1px solid #ddd;
      border-radius: 8px;
      padding: 1rem;
      background-color: #f0f8ff;
      transition: transform 0.2s ease-in-out;
    }

    .project-card:hover {
      transform: scale(1.02);
    }

    footer {
      text-align: center;
      padding: 1rem;
      background-color: #eee;
      margin-top: 2rem;
    }
  </style>
</head>

<body>
  <header>
    <h1>Nandini Jagarlamudi</h1>
    <p>🔗 <a href="https://linkedin.com/in/nandinijagarlamudi" style="color: #fff; text-decoration: underline;">LinkedIn</a> |
      ✉ nandinij1029@gmail.com |
      ✆ +1 (984)-278-0803</p>
  </header>

  <section>
    <h2>Career Objective</h2>
    <p>Motivated and adaptable graduate student with 5+ years of experience in application development, now transitioning into a data-focused role...</p>
  </section>

  <section>
    <h2>Skills</h2>
    <ul>
      <li><strong>Programming:</strong> Python, R, SQL, Bash, Java, JavaScript</li>
      <li><strong>Data Analysis:</strong> EDA, Hypothesis Testing, Regression, Forecasting</li>
      <li><strong>Visualization:</strong> Tableau, Power BI, Looker, Matplotlib</li>
      <li><strong>ML & AI:</strong> Supervised & Unsupervised, SHAP, Gradient Boosting</li>
      <li><strong>Tools:</strong> Jupyter, Git, VS Code, Scikit-learn, Pandas</li>
      <li><strong>Cloud & DB:</strong> MySQL, BigQuery, AWS, GCP</li>
    </ul>
  </section>

  <section>
    <h2>Work Experience</h2>
    <h3>Accenture Pvt Ltd (Oct 2017 – Dec 2022)</h3>
    <p>Application Development Associate – QA lead, agile contributor, automation specialist</p>
    <h3>Supraja Technologies (Dec 2020 – Feb 2021)</h3>
    <p>Student Intern – Penetration Testing, Red-Team Simulations, Cybersecurity Analysis</p>
  </section>

  <section>
    <h2>Academic Projects</h2>
    <div class="grid">
      <div class="project-card">
        <h4>ML & Kidney Exchange</h4>
        <p>Built ML models to predict CPRA from HLA data. Applied SHAP, stacking, and donor frequencies.</p>
      </div>
      <div class="project-card">
        <h4>Heart Failure Prediction</h4>
        <p>Trained classification models to predict near-term mortality. Focused on model metrics and class imbalance.</p>
      </div>
      <div class="project-card">
        <h4>Heart Failure Analysis</h4>
        <p>Used decision trees and random forest to identify clinical risk factors. Achieved 75% accuracy.</p>
      </div>
      <div class="project-card">
        <h4>Worldwide Blockbusters</h4>
        <p>Explored top-grossing films using SQL + R visualizations. Analyzed budget, ratings, and profitability.</p>
      </div>
    </div>
  </section>

  <section>
    <h2>Research Experience</h2>
    <p>Parallel Processing for Autonomous Vehicles – Sensor fusion, real-time ML, and UI design.</p>
  </section>

  <section>
    <h2>Education</h2>
    <ul>
      <li>M.S. Data Science – Bowling Green State University, OH (2023 – 2025) – GPA: 3.3</li>
      <li>B.Tech. CSE – NRI Institute of Technology, Guntur – GPA: 3.2</li>
    </ul>
  </section>

  <section>
    <h2>Certifications</h2>
    <ul>
      <li>Generative AI Fundamentals</li>
      <li>Data Visualization in Tableau</li>
    </ul>
  </section>

  <footer>
    <p>© 2025 Nandini Jagarlamudi • Built with ❤️ using HTML & CSS</p>
  </footer>
</body>

</html>
