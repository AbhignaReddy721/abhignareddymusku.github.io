---
layout: page
title: Work and School
permalink: /timeline/
nav: true
nav_order: 2
---

<style>
/* Hide the page title */
.post-title {
  display: none !important;
}

/* Reduce top padding when title is hidden */
.post-content {
  padding-top: 0 !important;
  margin-top: -4rem !important;
}

.timeline-container {
  max-width: 900px;
  margin: 0 auto;
  padding: 2rem 1rem;
}

.timeline-item {
  display: flex;
  gap: 2rem;
  margin-bottom: 2.5rem;
  position: relative;
  padding-left: 140px;
}

.timeline-date {
  position: absolute;
  left: 0;
  top: 0;
  width: 120px;
  text-align: right;
  font-size: 0.9rem;
  color: #888;
  font-weight: 500;
  padding-right: 1rem;
}

.timeline-logo {
  flex-shrink: 0;
  width: 60px;
  height: 60px;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #f8f9fa;
  border-radius: 8px;
  overflow: hidden;
  position: relative;
  margin-top: -5px;
}

.timeline-logo img {
  width: 100%;
  height: 100%;
  object-fit: contain;
  padding: 8px;
}

.timeline-logo.no-image {
  background: linear-gradient(135deg, #667eea, #764ba2);
  color: white;
  font-size: 1.5rem;
  font-weight: bold;
}

.timeline-content {
  flex: 1;
  padding-top: 0;
}

.timeline-content p {
  margin: 0 0 1rem 0;
  line-height: 1.6;
  color: #333;
}

.timeline-content ul {
  margin: 0.5rem 0;
  padding-left: 1.2rem;
  list-style: none;
}

.timeline-content ul li {
  position: relative;
  margin-bottom: 0.5rem;
  padding-left: 1rem;
  color: #555;
  line-height: 1.5;
}

.timeline-content ul li:before {
  content: "•";
  position: absolute;
  left: 0;
  color: #667eea;
  font-weight: bold;
}

.timeline-title {
  font-size: 1.1rem;
  font-weight: 600;
  color: #222;
  margin-bottom: 0.2rem;
}

.timeline-subtitle {
  font-size: 0.95rem;
  color: #666;
  margin-bottom: 0.8rem;
}

.timeline-link {
  color: #667eea;
  text-decoration: none;
  border-bottom: 1px solid transparent;
  transition: border-color 0.2s;
}

.timeline-link:hover {
  border-bottom-color: #667eea;
}

/* Vertical line connecting items */
.timeline-item:not(:last-child)::before {
  content: "";
  position: absolute;
  left: 170px;
  top: 60px;
  bottom: -2.5rem;
  width: 1px;
  background: linear-gradient(to bottom, #e0e0e0 0%, #e0e0e0 90%, transparent 100%);
}

/* Remove line from last experience item */
.timeline-item.last-experience::before {
  display: none !important;
}

/* Section divider */
.timeline-section {
  margin: -3rem 0 2rem 0;
  padding-left: 0px;
  font-size: 1.5rem;
  font-weight: 700;
  color: #111;
  border-bottom: 2px solid #f0f0f0;
  padding-bottom: 0.5rem;
}

/* Responsive design */
@media (max-width: 768px) {
  .timeline-item {
    padding-left: 0;
    flex-direction: column;
    gap: 1rem;
  }
  
  .timeline-date {
    position: relative;
    text-align: left;
    width: auto;
    padding-right: 0;
    margin-bottom: 0.5rem;
    color: #667eea;
    font-weight: 600;
  }
  
  .timeline-logo {
    width: 50px;
    height: 50px;
  }
  
  .timeline-item:not(:last-child)::before {
    display: none;
  }
  
  .timeline-section {
    padding-left: 0;
  }
}

/* Dark mode support */
@media (prefers-color-scheme: dark) {
  .timeline-content p {
    color: #ddd;
  }
  
  .timeline-content ul li {
    color: #bbb;
  }
  
  .timeline-title {
    color: #eee;
  }
  
  .timeline-subtitle {
    color: #aaa;
  }
  
  .timeline-logo {
    background-color: #2a2a2a;
  }
  
  .timeline-section {
    color: #eee;
    border-bottom-color: #444;
  }
}
</style>

<div class="timeline-container">

  <!-- Work Experience Section -->
  <div class="timeline-section">Experience</div>

  <div class="timeline-item">
    <div class="timeline-date">2025 - Present</div>
    <div class="timeline-logo">
      <img src="{{ '/assets/img/logo/ip.png' | relative_url }}" alt="IP" onerror="this.parentElement.classList.add('no-image'); this.parentElement.innerHTML='IP';">
    </div>
    <div class="timeline-content">
      <div class="timeline-title">Analytics Developer ( Health, Safety and Environmental )</div>
      <div class="timeline-subtitle">International Paper • Memphis, TN</div>
      <p> Objective is to reduce safety incidents and improve safety culture across manufacturing facilities. I work on leveraging data science, machine learning, and analytics to optimize reporting systems, enhance data infrastructure, and develop predictive insights that facilitate these efforts.</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">2024</div>
    <div class="timeline-logo">
      <img src="{{ '/assets/img/logo/damore.png' | relative_url }}" alt="NEU" onerror="this.parentElement.classList.add('no-image'); this.parentElement.innerHTML='N';">
    </div>
    <div class="timeline-content">
      <div class="timeline-title">Machine Learning Research Assistant</div>
      <div class="timeline-subtitle">D'Amore-McKim School of Business, Northeastern University • Boston, MA</div>
      <p>Leveraged large language models to perform sentiment analysis on accounting data.</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">2023 - 2024</div>
    <div class="timeline-logo">
      <img src="{{ '/assets/img/logo/tesla.png' | relative_url }}" alt="Tesla" onerror="this.parentElement.classList.add('no-image'); this.parentElement.innerHTML='T';">
    </div>
    <div class="timeline-content">
      <div class="timeline-title">Intern - Environmental, Health, Safety, and Security </div>
      <div class="timeline-subtitle">Tesla • Austin, TX</div>
      <p>Analyzed safety event data, created visualizations and presented findings to business stakeholders to support safety improvement intiatives across Giga Factory, Texas. Conducted Job Hazard Analysis for Body and General Assembly Lines of Cybertruck.</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">2021 - 2022</div>
    <div class="timeline-logo">
      <img src="{{ '/assets/img/logo/kagool.jpg' | relative_url }}" alt="Kagool" onerror="this.parentElement.classList.add('no-image'); this.parentElement.innerHTML='K';">
    </div>
    <div class="timeline-content">
      <div class="timeline-title">SAP Functional Consultant/Analyst ( Materials Management )</div>
      <div class="timeline-subtitle">Kagool • Hyderabad, India</div>
      <p>Worked on ensuring successful data migration and integration between client's legacy systems and SAP. Created master data, conducted unit testing, system integration testing, brainstormed exception handling scenarios and collaborated with stakeholders to gather business requirements and convert them to technical solutions.</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">2021</div>
    <div class="timeline-logo">
      <img src="{{ '/assets/img/logo/won.jpg' | relative_url }}" alt="WON" onerror="this.parentElement.classList.add('no-image'); this.parentElement.innerHTML='W';">
    </div>
    <div class="timeline-content">
      <div class="timeline-title">Data Analyst Intern</div>
      <div class="timeline-subtitle">William O'Neil Co. • Bengaluru, India ( was mostly remote due to covid )</div>
      <p>Researched and collected data from online financial sources for MarketSmith India. Developed design documentation and visualization structures to guide the product's data presentation.</p>
    </div>
  </div>

  <div class="timeline-item last-experience">
    <div class="timeline-date">2019</div>
    <div class="timeline-logo">
      <img src="{{ '/assets/img/logo/cumi.jpeg' | relative_url }}" alt="CUMI" onerror="this.parentElement.classList.add('no-image'); this.parentElement.innerHTML='C';">
    </div>
    <div class="timeline-content">
      <div class="timeline-title">Summer Intern - Manufacturing</div>
      <div class="timeline-subtitle">Carborundum Universal Ltd • Chennai, India</div>
      <p>Worked on process optimization and quality improvement initiatives for manufacturing operations.</p>
    </div>
  </div>

  <!-- Education Section -->
  <div class="timeline-section">Education</div>

  <div class="timeline-item">
    <div class="timeline-date">2022 - 2024</div>
    <div class="timeline-logo">
      <img src="{{ '/assets/img/logo/neu.png' | relative_url }}" alt="NEU" onerror="this.parentElement.classList.add('no-image'); this.parentElement.innerHTML='N';">
    </div>
    <div class="timeline-content">
      <div class="timeline-title">Master of Science in Industrial Engineering ( Data Science and Analytics Focus )</div>
      <div class="timeline-subtitle">Northeastern University • Boston, MA</div>
      <p><strong>GPA: 3.8/4.0</strong> • Graduate Student Representative, INFORMS Chapter, Northeastern University</p>
      <p>Coursework: Product Development, Project Management, Machine Learning, Machine Learning Operations, Database Design and Database Management, Operations Research, Probability and Statistics</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">2017 - 2021</div>
    <div class="timeline-logo">
      <img src="{{ '/assets/img/logo/bits.jpeg' | relative_url }}" alt="University" onerror="this.parentElement.classList.add('no-image'); this.parentElement.innerHTML='B';">
    </div>
    <div class="timeline-content">
      <div class="timeline-title">Bachelor of Engineering in Mechanical Engineering</div>
      <div class="timeline-subtitle">BITS Pilani • Hyderabad, India</div>
      <p><strong>GPA: 6.34/10.0</strong> • Member, Department of Controlz ( Event Management and Operations ) </p>
      <p>Coursework: Engineering Optimization, Energy Management, Business Analysis and Valuation, Supply Chain Management, Behavioral Economics, Principles of Management </p>
    </div>
  </div>

</div>