---
layout: page
title: So Far
permalink: /education and experience/
# description: My professional and academic journey
nav: false
published: false
nav_order: 2
---

<style>
.experience-container {
  max-width: 100%;
}

.experience-item {
  margin-bottom: 2.5rem;
  padding-bottom: 2rem;
  border-bottom: 1px solid #e0e0e0;
  display: flex;
  gap: 1.5rem;
  align-items: flex-start;
}

.experience-item:last-child {
  border-bottom: none;
}

.experience-logo {
  flex-shrink: 0;
  width: 60px;
  height: 60px;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #f5f5f5;
  border-radius: 8px;
  overflow: hidden;
}

.experience-logo img {
  width: 100%;
  height: 100%;
  object-fit: contain;
  padding: 8px;
}

/* Fallback for missing logos - displays first letter */
.experience-logo.no-image {
  background: linear-gradient(135deg, var(--global-theme-color), #667eea);
  color: white;
  font-size: 1.5rem;
  font-weight: bold;
}

.experience-details {
  flex: 1;
}

.experience-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  flex-wrap: wrap;
  gap: 1rem;
  margin-bottom: 0.5rem;
}

.experience-title-section {
  flex: 1;
}

.experience-company {
  font-size: 1.3rem;
  font-weight: 600;
  color: var(--global-text-color);
  margin-bottom: 0.2rem;
}

.experience-role {
  font-size: 1.1rem;
  color: #666;
  margin-bottom: 0.3rem;
}

.experience-date {
  font-size: 0.95rem;
  color: var(--global-theme-color);
  font-weight: 500;
}

.experience-location {
  font-size: 0.9rem;
  color: #888;
  margin-top: 0.2rem;
}

.experience-content {
  margin-top: 0.8rem;
  line-height: 1.6;
  color: #555;
}

.experience-content ul {
  margin-top: 0.5rem;
  padding-left: 1.2rem;
}

.experience-content li {
  margin-bottom: 0.3rem;
}

.experience-content a {
  color: var(--global-theme-color);
  text-decoration: none;
}

.experience-content a:hover {
  text-decoration: underline;
}

/* Responsive design */
@media (max-width: 768px) {
  .experience-item {
    flex-direction: column;
    gap: 1rem;
  }
  
  .experience-logo {
    width: 50px;
    height: 50px;
  }
  
  .experience-header {
    flex-direction: column;
    gap: 0.5rem;
  }
}

/* Dark mode support */
@media (prefers-color-scheme: dark) {
  .experience-logo {
    background-color: #2a2a2a;
  }
  
  .experience-content {
    color: #ccc;
  }
  
  .experience-role {
    color: #aaa;
  }
  
  .experience-location {
    color: #999;
  }
}
</style>

<div class="experience-container">
  
  <div class="experience-item">
    <div class="experience-logo">
      <!-- Replace with actual logo path or use fallback letter -->
      <img src="/assets/img/logos/IP new logo.png" alt="Company Logo" onerror="this.parentElement.classList.add('no-image'); this.parentElement.innerHTML='C';">
    </div>
    <div class="experience-details">
      <div class="experience-header">
        <div class="experience-title-section">
          <div class="experience-company">International Paper</div>
          <div class="experience-role">Analytics Developer</div>
          <div class="experience-date">Mar 2025 - Present</div>
          <div class="experience-location">Memphis, TN</div>
        </div>
      </div>
      <div class="experience-content">
        Leading the development of cloud-native applications and microservices architecture. Working with cutting-edge technologies to build scalable solutions.
        <ul>
          <li>Architected and implemented a distributed system handling 1M+ requests/day</li>
          <li>Led a team of 5 engineers in migrating legacy systems to Kubernetes</li>
          <li>Reduced infrastructure costs by 40% through optimization initiatives</li>
        </ul>
      </div>
    </div>
  </div>
  
  <div class="experience-item">
    <div class="experience-logo">
      <img src="/assets/img/logos/D'amore_northeastern_logo.jpeg" alt="Previous Company" onerror="this.parentElement.classList.add('no-image'); this.parentElement.innerHTML='P';">
    </div>
    <div class="experience-details">
      <div class="experience-header">
        <div class="experience-title-section">
          <div class="experience-company">D'Amore-McKim School of Business, Northeastern University</div>
          <div class="experience-role">Machine Learning Research Assistant</div>
          <div class="experience-date">Mar 2024 - Aug 2024</div>
          <div class="experience-location">Boston, MA</div>
        </div>
      </div>
      <div class="experience-content">
        Developed full-stack applications using React and Node.js. Collaborated with cross-functional teams to deliver customer-facing features.
        <ul>
          <li>Built RESTful APIs serving 500K+ daily active users</li>
          <li>Implemented CI/CD pipelines reducing deployment time by 60%</li>
          <li>Mentored junior developers and conducted code reviews</li>
        </ul>
      </div>
    </div>
  </div>
  
  <div class="experience-item">
    <div class="experience-logo">
      <img src="/assets/img/logos/Tesla_logo.png" alt="Startup" onerror="this.parentElement.classList.add('no-image'); this.parentElement.innerHTML='S';">
    </div>
    <div class="experience-details">
      <div class="experience-header">
        <div class="experience-title-section">
          <div class="experience-company">Tesla</div>
          <div class="experience-role">Intern - Environmental, Health, Safety, and Security (EHS&S)</div>
          <div class="experience-date">Sep 2023 - Jan 2024</div>
          <div class="experience-location">Austin, TX</div>
        </div>
      </div>
      <div class="experience-content">
        Gained hands-on experience in agile development environments. Contributed to various projects from MVP to production launch.
        <ul>
          <li>Developed responsive web interfaces using modern JavaScript frameworks</li>
          <li>Participated in daily standups and sprint planning</li>
          <li>Contributed to open-source projects and internal tools</li>
        </ul>
      </div>
    </div>
  </div>
  
  <div class="experience-item">
    <div class="experience-logo">
      <img src="/assets/img/logos/Kagool_Logo_new.jpg" alt="Research Lab" onerror="this.parentElement.classList.add('no-image'); this.parentElement.innerHTML='R';">
    </div>
    <div class="experience-details">
      <div class="experience-header">
        <div class="experience-title-section">
          <div class="experience-company">Kagool</div>
          <div class="experience-role">SAP Functional Consultant/Analyst ( Materials Management )</div>
          <div class="experience-date">Jun 2021 - Aug 2022</div>
          <div class="experience-location">Hyderabad, India</div>
        </div>
      </div>
      <div class="experience-content">
        Conducted research in machine learning and computer vision under Prof. Smith. Published findings in peer-reviewed conferences.
        <ul>
          <li>Developed novel algorithms for object detection in low-light conditions</li>
          <li>Co-authored 2 papers published in IEEE conferences</li>
          <li>Presented research findings at international symposium</li>
        </ul>
      </div>
    </div>
  </div>

  <div class="experience-item">
    <div class="experience-logo">
      <img src="/assets/img/logos/william-o-neil-co-logo.jpg" alt="Tech Corp" onerror="this.parentElement.classList.add('no-image'); this.parentElement.innerHTML='T';">
    </div>
    <div class="experience-details">
      <div class="experience-header">
        <div class="experience-title-section">
          <div class="experience-company">William O Neil Co.</div>
          <div class="experience-role">Data Analyst Intern</div>
          <div class="experience-date">Jan 2021 - May 2021</div>
          <div class="experience-location">Bengaluru, India</div>
        </div>
      </div>
      <div class="experience-content">
        Participated in a 12-week internship program focused on cloud computing and DevOps practices.
        <ul>
          <li>Built automated testing framework improving code coverage by 30%</li>
          <li>Collaborated with senior engineers on production features</li>
          <li>Received return offer for following summer</li>
        </ul>
      </div>
    </div>
  </div>

  <div class="experience-item">
    <div class="experience-logo">
      <img src="/assets/img/logos/Carborundum logo.jpeg" alt="Tech Corp" onerror="this.parentElement.classList.add('no-image'); this.parentElement.innerHTML='T';">
    </div>
    <div class="experience-details">
      <div class="experience-header">
        <div class="experience-title-section">
          <div class="experience-company">Carborundum Universal Ltd</div>
          <div class="experience-role">Summer Intern</div>
          <div class="experience-date">May 2019 - Jul 2019</div>
          <div class="experience-location">Chennai, India</div>
        </div>
      </div>
      <div class="experience-content">
        Participated in a 12-week internship program focused on cloud computing and DevOps practices.
        <ul>
          <li>Built automated testing framework improving code coverage by 30%</li>
          <li>Collaborated with senior engineers on production features</li>
          <li>Received return offer for following summer</li>
        </ul>
      </div>
    </div>
  </div>
  
  <div class="experience-item">
    <div class="experience-logo">
      <img src="/assets/img/logos/university-logo.png" alt="University" onerror="this.parentElement.classList.add('no-image'); this.parentElement.innerHTML='U';">
    </div>
    <div class="experience-details">
      <div class="experience-header">
        <div class="experience-title-section">
          <div class="experience-company">University Name</div>
          <div class="experience-role">Bachelor of Science in Computer Science</div>
          <div class="experience-date">2014 - 2018</div>
          <div class="experience-location">Cambridge, MA</div>
        </div>
      </div>
      <div class="experience-content">
        <strong>GPA: 3.8/4.0</strong> • Dean's List • Computer Science Society President
        <br><br>
        Focused on algorithms, distributed systems, and machine learning. Completed thesis on "Optimizing Neural Network Architecture for Edge Computing." Worked as a teaching assistant for Data Structures and Algorithms course.
      </div>
    </div>
  </div>
  
</div>