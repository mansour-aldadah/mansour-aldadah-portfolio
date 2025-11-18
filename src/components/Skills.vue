<template>
  <section class="skills" id="skills">
    <!-- Abstract Background -->
    <div class="skills-bg">
      <svg class="abstract-shape blob-1" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
        <path fill="var(--laravel-red)" d="M47.1,-81.7C59.9,-72.3,68.5,-57.5,74.5,-42.1C80.5,-26.7,83.9,-10.7,83.1,5.1C82.3,20.9,77.3,36.5,68.4,49.9C59.5,63.3,46.7,74.5,32.1,79.8C17.5,85.1,1.1,84.5,-15.5,81.5C-32.1,78.5,-48.9,73.1,-62.3,63.1C-75.7,53.1,-85.7,38.5,-88.8,22.8C-91.9,7.1,-88.1,-9.7,-80.6,-24.3C-73.1,-38.9,-61.9,-51.3,-48.3,-60.3C-34.7,-69.3,-18.3,-74.9,-1.2,-72.9C15.9,-70.9,34.3,-91.1,47.1,-81.7Z" transform="translate(100 100)" />
      </svg>

      <svg class="abstract-shape blob-2" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
        <path fill="var(--vue-green)" d="M44.7,-76.4C58.8,-69.2,71.8,-59.1,79.6,-45.8C87.4,-32.6,90,-16.3,88.5,-0.9C87,14.6,81.4,29.2,73.1,42.8C64.8,56.4,53.8,69,40.2,75.8C26.6,82.6,10.4,83.6,-5.3,81.3C-21,79,-42,73.4,-56.8,62.3C-71.6,51.2,-80.2,34.6,-83.8,16.8C-87.4,-1,-86,-20,-78.2,-36.4C-70.4,-52.8,-56.2,-66.6,-40.8,-73.3C-25.4,-80,-12.7,-79.5,1.3,-81.7C15.3,-83.9,30.6,-83.6,44.7,-76.4Z" transform="translate(100 100)" />
      </svg>
    </div>

    <h2 class="section-heading">Skills & Experience</h2>

    <div class="skills-content">
      <div class="experience-section">
        <h3 class="subsection-title">Professional Experience</h3>
        
        <div class="experience-item">
          <div class="experience-header">
            <h4 class="job-title">
              Volunteer Laravel Developer 
              <span class="company">@ Kamal Edwan Hospital</span>
            </h4>
            <p class="job-dates">January 2024 - October 2024</p>
          </div>
          <ul class="job-details">
            <li>Developed a custom Laravel-based Fuel Management System to digitize and streamline internal hospital operations</li>
            <li>Applied RESTful APIs and MySQL to manage real-time fuel tracking</li>
            <li>Ensured system scalability, data integrity, and user role-based access</li>
          </ul>
        </div>

        <div class="experience-item">
          <div class="experience-header">
            <h4 class="job-title">
              Freelance Laravel Developer 
              <span class="company">@ Remote</span>
            </h4>
            <p class="job-dates">September 2023 - Present</p>
          </div>
          <ul class="job-details">
            <li>Delivered 5+ Laravel-based SaaS and SPA applications for clients in healthcare, retail, and internal business tools sectors</li>
            <li>Developed full-stack solutions using Laravel, Vue.js, Inertia.js, REST APIs, and MySQL from database design to deployment</li>
            <li>Built responsive admin dashboards with real-time analytics, role-based access, and secure authentication</li>
            <li>Continuously optimized application performance and database queries to ensure scalability under high load</li>
          </ul>
        </div>
      </div>

      <div class="skills-section">
        <h3 class="subsection-title">Technical Skills</h3>
        
        <div class="skills-grid">
          <div class="skill-category">
            <h4 class="category-title">Frontend</h4>
            <div class="skill-tags">
              <span class="skill-tag">HTML5</span>
              <span class="skill-tag">CSS3</span>
              <span class="skill-tag">SASS</span>
              <span class="skill-tag">JavaScript (ES6+)</span>
              <span class="skill-tag">Vue.js</span>
              <span class="skill-tag">React.js</span>
              <span class="skill-tag">Inertia.js</span>
              <span class="skill-tag">Bootstrap</span>
              <span class="skill-tag">Tailwind CSS</span>
            </div>
          </div>

          <div class="skill-category">
            <h4 class="category-title">Backend</h4>
            <div class="skill-tags">
              <span class="skill-tag">PHP</span>
              <span class="skill-tag">Laravel</span>
              <span class="skill-tag">MySQL</span>
              <span class="skill-tag">RESTful APIs</span>
              <span class="skill-tag">Sanctum</span>
              <span class="skill-tag">SPA Architecture</span>
              <span class="skill-tag">SaaS Systems</span>
            </div>
          </div>

          <div class="skill-category">
            <h4 class="category-title">Tools & Others</h4>
            <div class="skill-tags">
              <span class="skill-tag">Git</span>
              <span class="skill-tag">GitHub</span>
              <span class="skill-tag">VS Code</span>
              <span class="skill-tag">Figma</span>
              <span class="skill-tag">Adobe XD</span>
              <span class="skill-tag">Postman</span>
            </div>
          </div>
        </div>

        <div class="education-section">
          <h3 class="subsection-title">Education</h3>
          <div class="education-item">
            <h4 class="degree">Bachelor's degree in Computer Systems Engineering</h4>
            <p class="school">Palestinian Technical College</p>
            <p class="education-dates">September 2020 - January 2026</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Skills'
}
</script>

<style scoped>
.skills {
  max-width: 1000px;
  margin: 0 auto;
  padding: 100px 0;
  position: relative;
  overflow: hidden;
}

.skills-bg {
  position: absolute;
  top: -20%;
  left: -20%;
  width: 140%;
  height: 140%;
  z-index: 0;
  pointer-events: none;
  overflow: visible;
}

.abstract-shape {
  position: absolute;
  width: 500px;
  height: 500px;
  animation: morphing 25s ease-in-out infinite;
  filter: blur(70px);
  opacity: 0.15;
}

.blob-1 {
  top: 15%;
  left: -10%;
  animation-delay: 0s;
}

.blob-2 {
  bottom: 10%;
  right: -15%;
  animation-delay: 2s;
}

@keyframes morphing {
  0%, 100% {
    transform: translate(0, 0) scale(1) rotate(0deg);
  }
  33% {
    transform: translate(40px, -60px) scale(1.15) rotate(120deg);
  }
  66% {
    transform: translate(-30px, 40px) scale(0.9) rotate(240deg);
  }
}

.skills-content {
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-gap: 50px;
  position: relative;
  z-index: 1;
}

.subsection-title {
  color: var(--lightest-slate);
  font-size: var(--fz-xxl);
  font-weight: 600;
  margin-bottom: 30px;
}

.experience-item {
  margin-bottom: 40px;
  padding: 20px;
  background-color: var(--light-navy);
  border-radius: var(--border-radius);
  border-left: 3px solid var(--laravel-red);
}

.experience-header {
  margin-bottom: 15px;
}

.job-title {
  color: var(--lightest-slate);
  font-size: var(--fz-lg);
  font-weight: 600;
  margin-bottom: 5px;
}

.company {
  color: var(--green);
  font-family: var(--font-mono);
  font-size: var(--fz-md);
  font-weight: 400;
}

.job-dates {
  color: var(--light-slate);
  font-family: var(--font-mono);
  font-size: var(--fz-xs);
  margin-bottom: 15px;
}

.job-details {
  list-style: none;
  padding: 0;
  margin: 0;
}

.job-details li {
  position: relative;
  padding-left: 20px;
  margin-bottom: 10px;
  color: var(--slate);
  font-size: var(--fz-sm);
  line-height: 1.5;
}

.job-details li:before {
  content: '▹';
  position: absolute;
  left: 0;
  color: var(--green);
}

.skills-grid {
  margin-bottom: 40px;
}

.skill-category {
  margin-bottom: 30px;
}

.category-title {
  color: var(--lightest-slate);
  font-size: var(--fz-lg);
  font-weight: 600;
  margin-bottom: 15px;
}

.skill-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
}

.skill-tag {
  background-color: var(--light-navy);
  color: var(--green);
  font-family: var(--font-mono);
  font-size: var(--fz-xs);
  padding: 8px 12px;
  border-radius: var(--border-radius);
  border: 1px solid var(--green);
  transition: var(--transition);
}

.skill-tag:hover {
  background-color: var(--green-tint);
  transform: translateY(-2px);
}

.education-item {
  background-color: var(--light-navy);
  padding: 20px;
  border-radius: var(--border-radius);
  border-left: 3px solid var(--laravel-red);
}

.degree {
  color: var(--lightest-slate);
  font-size: var(--fz-lg);
  font-weight: 600;
  margin-bottom: 5px;
}

.school {
  color: var(--green);
  font-family: var(--font-mono);
  font-size: var(--fz-md);
  margin-bottom: 5px;
}

.education-dates {
  color: var(--light-slate);
  font-family: var(--font-mono);
  font-size: var(--fz-xs);
}

@media (max-width: 768px) {
  .skills-content {
    display: block;
  }

  .experience-section {
    margin-bottom: 50px;
  }
}

@media (max-width: 480px) {
  .skills {
    padding: 60px 0;
  }

  .experience-item,
  .education-item {
    padding: 15px;
  }
}
</style>