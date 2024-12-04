
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Youmna Abden</h1>
    <p>A seasoned Information Specialist with over six years of experience in data and information services, skilled in creating and managing data. Proficient in data analysis and report preparation using advanced tools such as Excel and Power BI. Possesses proven expertise in developing comprehensive data analysis dashboards and preparing monthly analytical reports. Experienced in handling various types of data, analyzing them, and preparing appropriate reports using Python, SQL, and tools such as Excel, Power BI, and Tableau Data Analyst | Freelancer</p>
    <a href="#projects" class="btn">View My Work</a>
  </header>
  <section id="projects">
    <h2>Projects</h2>
    <div class="project-grid">
      <div class="project-card">
        <img src="project 1" alt="Project 1">
        <h3>Etisalat Dashboard</h3>
        <p>Etisalat Regression Dashboard analyzing the efficiency of companies. The findings revealed that factors such as service quality, pricing, and customer experience play a crucial role in customers' decisions to stay or leave. Based on these insights, suggestions were made to enhance performance efficiency and improve customer retention rates.</p>
        <video width="320" height="240" controls>
          <source src="Dash Bord Churn - Power BI and 2 more pages - Work - Microsoft​ Edge 2024-08-26 17-08-06.mp4" type="video/mp4">
          Your browser does not support the video tag.
        </video>
      </div>

      <div class="project-card">
        <img src="project 3" alt="Project 3">
        <h3>HR Dashboard</h3>
        <p>This project analyzes employee retention trends on Power BI. The goal was to uncover factors that influence retention and suggest improvements to the work environment.</p>
        <video width="320" height="240" controls>
          <source src="Employes_Dash board_Youmna alaa - Power BI and 1 more page - Work - Microsoft​ Edge 2024-10-29 01-25-21.mp4" type="video/mp4">
          Your browser does not support the video tag.
        </video>
      </div>

      <div class="project-card">
        <img src="project 4" alt="Project 4">
        <h3>Hotel Dashboard</h3>
        <p>This dashboard provides a comprehensive overview of the hotel's performance, understanding visit details, and guest preferences. Dropdown lists summarize the data using specific formulas to help improve management and guest experiences.</p>
        <video width="320" height="240" controls>
          <source src="Practice test - Excel 2024-08-14 07-19-27.mp4" type="video/mp4">
          Your browser does not support the video tag.
        </video>
      </div>
    </div>
  </section>
  <footer>
    <p>© 2024 Yomna Aben. All rights reserved.</p>
  </footer>
</body>
</html>
/* Reset */
body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Arial', sans-serif;
  background-color: #101010;
  color: #fff;
}

header {
  text-align: center;
  padding: 4rem 2rem;
  background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
}

header h1 {
  font-size: 3rem;
  margin-bottom: 0.5rem;
}

header p {
  font-size: 1.5rem;
  margin-bottom: 1rem;
}

header .btn {
  padding: 0.8rem 2rem;
  background: #ff6f61;
  color: #fff;
  text-decoration: none;
  border-radius: 5px;
  transition: background 0.3s;
}

header .btn:hover {
  background: #ff4a34;
}

#projects {
  padding: 4rem 2rem;
}

#projects h2 {
  text-align: center;
  margin-bottom: 2rem;
  color: #ff6f61;
}

.project-grid {
  display: flex;
  gap: 2rem;
  justify-content: center;
  flex-wrap: wrap;
}

.project-card {
  background: #2c5364;
  padding: 1rem;
  border-radius: 10px;
  text-align: center;
  width: 300px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
}

.project-card img {
  width: 100%;
  border-radius: 10px;
  margin-bottom: 1rem;
}

.project-card h3 {
  margin-bottom: 0.5rem;
}

.project-card a {
  color: #ff6f61;
  text-decoration: none;
}

footer {
  text-align: center;
  padding: 1rem;
  background: #0f2027;
}
