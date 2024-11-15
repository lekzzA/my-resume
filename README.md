<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Google Search - Tanuj Bhatt</title>
    <!-- Favicon for Browser Tab -->
    <link rel="icon" href="https://www.google.com/favicon.ico" />
    <style>
      body {
        font-family: Arial, sans-serif;
        background-color: #f8f9fa;
        margin: 0;
        padding: 0;
        color: #202124;
      }
      .container {
        max-width: 1000px;
        margin: 20px auto;
        display: flex;
        flex-direction: column;
        gap: 20px;
      }
      /* Search bar */
      .search-bar-container {
        display: flex;
        justify-content: flex-start; /* Align search bar to the left */
        padding: 20px 0;
        padding-left: 10%;
      }
      .search-bar {
        display: flex;
        align-items: center;
        width: 100%;
        max-width: 600px;
        padding: 10px;
        border: 1px solid #ddd;
        border-radius: 24px;
        background-color: white;
      }
      .search-bar img {
        height: 20px;
        width: auto;
        margin-right: 10px;
      }
      .search-bar input {
        border: none;
        outline: none;
        font-size: 18px;
        width: 100%;
      }
      /* Layout for search results */
      .main-content {
        display: flex;
        gap: 20px;
      }
      /* Sidebar */
      .sidebar {
        width: 300px;
        padding: 20px;
        background-color: #f1f3f4;
        border-radius: 8px;
      }
      .sidebar h2 {
        font-size: 20px;
        margin: 0 0 10px 0;
      }
      .sidebar p,
      .sidebar-list li {
        margin: 10px 0;
        font-size: 14px;
        color: #5f6368;
      }
      /* Search Results */
      .search-results {
        flex: 1;
      }
      .result {
        margin-bottom: 20px;
      }
      .result h3 {
        font-size: 18px;
        color: #1a0dab;
      }
      .result a {
        color: #1a0dab;
        text-decoration: none;
        font-size: 16px;
      }
      .result a:hover {
        text-decoration: underline;
      }
      .result p {
        color: #4d5156;
        font-size: 14px;
        margin: 5px 0;
      }
      /* People also searched */
      .accordion {
        margin-top: 30px;
      }
      .accordion h3 {
        font-size: 18px;
        color: #202124;
        margin-bottom: 10px;
      }
      .accordion-item {
        background-color: #fff;
        border: 1px solid #ddd;
        border-radius: 8px;
        margin-bottom: 10px;
      }
      .accordion-title {
        font-size: 16px;
        padding: 15px;
        cursor: pointer;
        color: #1a0dab;
        display: flex;
        justify-content: space-between;
        align-items: center;
      }
      .accordion-title:hover {
        background-color: #f1f3f4;
      }
      .accordion-content {
        padding: 15px;
        font-size: 14px;
        color: #4d5156;
        display: none;
      }
    </style>
    <script>
      function toggleAccordionContent(element) {
        const content = element.nextElementSibling;
        content.style.display =
          content.style.display === "block" ? "none" : "block";
      }
    </script>
  </head>
  <body>
    <div class="container">
      <!-- Search Bar -->
      <div class="search-bar-container">
        <div class="search-bar">
          <!-- Google Logo Image in Search Bar -->
          <img src="https://www.google.com/favicon.ico" alt="Google Logo" />
          <input type="text" value="Tanuj Bhatt" readonly />
        </div>
      </div>

      <div class="main-content">
        <!-- Search Results -->
        <div class="search-results">
          <div class="result">
            <a href="#"><h3>Tanuj Bhatt - LinkedIn Profile</h3></a>
            <p>
              linkedin.com/in/tanujbhatt - Connect with Tanuj Bhatt on LinkedIn
              to learn more about his experience and skills in business
              analytics and data science.
            </p>
          </div>
          <div class="result">
            <a href="#"><h3>Portfolio Website of Tanuj Bhatt</h3></a>
            <p>
              tanujbhatt.com - Explore Tanuj's portfolio, showcasing his
              projects, achievements, and professional journey.
            </p>
          </div>
          <div class="result">
            <a href="#"><h3>Tanuj Bhatt's GitHub</h3></a>
            <p>
              github.com/tanujbhatt - Discover Tanuj's code repositories,
              open-source projects, and contributions to the tech community.
            </p>
          </div>
          <div class="result">
            <a href="#"
              ><h3>Introduction to Business Analytics by Tanuj Bhatt</h3></a
            >
            <p>
              medium.com - Read Tanuj's articles on business analytics, covering
              essential concepts, industry insights, and real-world
              applications.
            </p>
          </div>

          <!-- People Also Searched Section -->
          <div class="accordion">
            <h3>People also searched</h3>
            <div class="accordion-item">
              <div
                class="accordion-title"
                onclick="toggleAccordionContent(this)"
              >
                What is Tanuj Bhatt known for?
              </div>
              <div class="accordion-content">
                Tanuj Bhatt is recognized for his expertise in business
                analytics and data science, with a focus on leveraging data for
                actionable insights.
              </div>
            </div>
            <div class="accordion-item">
              <div
                class="accordion-title"
                onclick="toggleAccordionContent(this)"
              >
                What are Tanuj Bhatt's key skills?
              </div>
              <div class="accordion-content">
                Tanuj specializes in Python, data analysis, business
                intelligence, and machine learning, having applied these skills
                in various projects.
              </div>
            </div>
            <div class="accordion-item">
              <div
                class="accordion-title"
                onclick="toggleAccordionContent(this)"
              >
                Where did Tanuj Bhatt study?
              </div>
              <div class="accordion-content">
                Tanuj Bhatt completed an Introduction to Business Analytics
                course and holds multiple certifications in data science and
                analytics.
              </div>
            </div>
          </div>
        </div>

        <!-- Sidebar (Wikipedia-style info) -->
        <div class="sidebar">
          <h2>Tanuj Bhatt</h2>
          <p>
            <strong>Occupation:</strong> Associate Software Engineer, Veritas
            Technologies LLC
          </p>
          <p>
            <strong>Most recent Education:</strong> Army Institute of Technology, Bachelor
            of Engineering </br>
            Computer Engineering</br>
            CGPA 8.64
          </p>
          <p>
            <strong>Skills:</strong> <ul class="sidebar-list">
                <li>Development experience in C++, Java, Python and Typescript</li>
                <li>Work in collaborative environment</li>
                <li>Versatile and quick learner</li>
                <li>Familiar with concepts of OOP, DSA, STL in C++</li>
                <li>Playing instruments like Guitar, Harmonium, Dholak</li>
                <li>Singing</li>
                <li>Playing Football, Table tennis, Badminton (Inter-college and regional level)</li>
                <li>Efficient communication and solves problem</li>
            </ul>
          </p>
          <p>
            <strong>Known For:</strong> Expertise in data processing, analytics
            projects, and instructional content
          </p>
        </div>
      </div>
    </div>
  </body>
</html>
 
