<template>
  <section class="contact" id="contact">
    <!-- Abstract Background -->
    <div class="contact-bg">
      <svg class="abstract-shape blob-1" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
        <path fill="var(--laravel-red)" d="M47.1,-81.7C59.9,-72.3,68.5,-57.5,74.5,-42.1C80.5,-26.7,83.9,-10.7,83.1,5.1C82.3,20.9,77.3,36.5,68.4,49.9C59.5,63.3,46.7,74.5,32.1,79.8C17.5,85.1,1.1,84.5,-15.5,81.5C-32.1,78.5,-48.9,73.1,-62.3,63.1C-75.7,53.1,-85.7,38.5,-88.8,22.8C-91.9,7.1,-88.1,-9.7,-80.6,-24.3C-73.1,-38.9,-61.9,-51.3,-48.3,-60.3C-34.7,-69.3,-18.3,-74.9,-1.2,-72.9C15.9,-70.9,34.3,-91.1,47.1,-81.7Z" transform="translate(100 100)" />
      </svg>

      <svg class="abstract-shape blob-2" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
        <path fill="var(--vue-green)" d="M39.5,-65.6C51.4,-58.1,61.3,-47.3,68.1,-34.8C74.9,-22.3,78.6,-8.1,78.3,6.2C78,20.5,73.7,35,65.8,47.2C57.9,59.4,46.4,69.3,33.3,74.8C20.2,80.3,5.5,81.4,-9.8,78.9C-25.1,76.4,-41,70.3,-54.3,60.5C-67.6,50.7,-78.3,37.2,-82.4,21.8C-86.5,6.4,-84,-10.9,-76.8,-25.5C-69.6,-40.1,-57.7,-52,-44.2,-59.8C-30.7,-67.6,-15.4,-71.3,-0.3,-70.8C14.8,-70.3,27.6,-73.1,39.5,-65.6Z" transform="translate(100 100)" />
      </svg>
    </div>

    <h2 class="section-heading overline">What's Next?</h2>

    <h2 class="contact-title">Get In Touch</h2>
    
    <p class="contact-description">
      I'm currently seeking new opportunities and my inbox is always open. 
      Whether you have a question, want to discuss a project, or just want to say hi, 
      I'll try my best to get back to you!
    </p>
    
    <div class="contact-cta">
      <a href="mailto:m.aldadah24@gmail.com" class="big-button contact-button">
        Say Hello
      </a>
    </div>

    <div class="contact-info">
      <div class="contact-details">
        <div class="contact-item">
          <span class="contact-label">Email:</span>
          <a href="mailto:m.aldadah24@gmail.com" class="inline-link">m.aldadah24@gmail.com</a>
        </div>
        <div class="contact-item">
          <span class="contact-label">Phone:</span>
          <a href="https://wa.me/970595152274" class="inline-link" target="_blank" rel="noopener noreferrer">+970 595 152 274</a>
        </div>
        <div class="contact-item">
          <span class="contact-label">Location:</span>
          <span>Gaza, Palestine</span>
        </div>
      </div>

      <div class="social-links">
        <a href="https://github.com/mansour-aldadah" aria-label="GitHub" target="_blank" rel="noopener noreferrer">
          <svg xmlns="http://www.w3.org/2000/svg" role="img" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-github">
            <path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"></path>
          </svg>
        </a>
        <a href="https://linkedin.com/in/mansour-aldadah" aria-label="LinkedIn" target="_blank" rel="noopener noreferrer">
          <svg xmlns="http://www.w3.org/2000/svg" role="img" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-linkedin">
            <path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"></path>
            <rect x="2" y="9" width="4" height="12"></rect>
            <circle cx="4" cy="4" r="2"></circle>
          </svg>
        </a>
      </div>
    </div>
  </section>

  <footer class="footer">
    <div class="footer-content">
      <p>
        Built by
        <a href="https://github.com/mansour-aldadah" class="inline-link" target="_blank" rel="noopener noreferrer">
          Mansour Al-Dadah
        </a>
      </p>
      <p class="footer-tech">
        Designed & Built with
        <span class="highlight">Vue.js</span>
      </p>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'Contact'
}
</script>

<style scoped>
.contact {
  max-width: 600px;
  margin: 0 auto 100px;
  text-align: center;
  padding: 100px 0;
  position: relative;
}

.contact-bg {
  position: absolute;
  top: 0;
  left: -100%;
  width: 300%;
  height: 100%;
  z-index: 0;
  pointer-events: none;
  overflow: hidden;
}

.abstract-shape {
  position: absolute;
  width: 450px;
  height: 450px;
  animation: morphing 20s ease-in-out infinite;
  filter: blur(70px);
  opacity: 0.18;
}

.blob-1 {
  top: 10%;
  left: 20%;
  animation-delay: 0s;
}

.blob-2 {
  bottom: 15%;
  right: 25%;
  animation-delay: 1.5s;
}

@keyframes morphing {
  0%, 100% {
    transform: translate(0, 0) scale(1) rotate(0deg);
  }
  33% {
    transform: translate(30px, -50px) scale(1.2) rotate(120deg);
  }
  66% {
    transform: translate(-20px, 30px) scale(0.95) rotate(240deg);
  }
}

.contact .section-heading {
  display: block;
  margin-bottom: 20px;
  color: var(--laravel-red);
  font-family: var(--font-mono);
  font-size: var(--fz-md);
  font-weight: 400;
  position: relative;
  z-index: 1;
}

.contact .section-heading:before {
  bottom: auto;
  font-size: var(--fz-sm);
}

.contact .section-heading:after {
  display: none;
}

.contact-title {
  font-size: clamp(40px, 5vw, 60px);
  color: var(--lightest-slate);
  margin-bottom: 20px;
  position: relative;
  z-index: 1;
}

.contact-description {
  color: var(--slate);
  font-size: var(--fz-xl);
  line-height: 1.3;
  margin-bottom: 50px;
  position: relative;
  z-index: 1;
}

.contact-cta {
  margin-bottom: 50px;
  position: relative;
  z-index: 1;
}

.contact-info {
  margin-top: 50px;
  position: relative;
  z-index: 1;
}

.contact-details {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-bottom: 30px;
}

.contact-item {
  display: flex;
  align-items: center;
  margin-bottom: 15px;
  color: var(--slate);
  font-family: var(--font-mono);
  font-size: var(--fz-sm);
}

.contact-label {
  margin-right: 10px;
  color: var(--light-slate);
  font-weight: 600;
  min-width: 70px;
  text-align: right;
}

.social-links {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 20px;
  margin-top: 30px;
}

.social-links a {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 40px;
  height: 40px;
  color: var(--light-slate);
  transition: var(--transition);
}

.social-links a:hover {
  color: var(--laravel-red);
  transform: translateY(-3px);
}

.social-links svg {
  width: 20px;
  height: 20px;
}

.footer {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  height: auto;
  min-height: 70px;
  padding: 15px;
  text-align: center;
}

.footer-content {
  color: var(--light-slate);
  font-family: var(--font-mono);
  font-size: var(--fz-xxs);
  line-height: 1;
}

.footer-content p {
  margin: 0;
}

.footer-tech {
  margin-top: 10px !important;
  color: var(--slate);
}

.footer-tech .highlight {
  color: var(--laravel-red);
}

@media (max-width: 768px) {
  .contact {
    padding: 80px 0;
  }

  .contact-details {
    align-items: flex-start;
  }

  .contact-item {
    justify-content: flex-start;
    flex-direction: column;
    align-items: flex-start;
  }

  .contact-label {
    margin-right: 0;
    margin-bottom: 5px;
    text-align: left;
    min-width: auto;
  }
}

@media (max-width: 480px) {
  .contact {
    padding: 60px 0;
  }

  .contact-description {
    font-size: var(--fz-lg);
  }
}
</style>