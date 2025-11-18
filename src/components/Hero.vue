<template>
  <section class="hero" id="hero">
    <!-- Abstract Background Shapes -->
    <div class="hero-bg">
      <!-- Laravel 3D Logo -->
      <div class="logo-3d laravel-logo">
        <svg viewBox="0 0 50 52" xmlns="http://www.w3.org/2000/svg">
          <g fill="var(--laravel-red)" opacity="0.15">
            <path d="M49.626 11.564a.809.809 0 0 1 .028.209v10.972a.8.8 0 0 1-.402.694l-9.209 5.302V39.25c0 .286-.152.55-.4.694L20.42 51.01c-.044.025-.092.041-.14.058-.018.006-.035.017-.054.022a.805.805 0 0 1-.41 0c-.022-.006-.042-.018-.063-.026-.044-.016-.09-.03-.132-.054L.402 39.944A.801.801 0 0 1 0 39.25V6.334c0-.072.01-.142.028-.21.006-.023.02-.044.028-.067.015-.042.029-.085.051-.124.015-.026.037-.047.055-.071.023-.032.044-.065.071-.093.023-.023.053-.04.079-.06.029-.024.055-.05.088-.069h.001l9.61-5.533a.802.802 0 0 1 .8 0l9.61 5.533h.002c.032.02.059.045.088.068.026.02.055.038.078.06.028.029.048.062.072.094.017.024.04.045.054.071.023.04.036.082.052.124.008.023.022.044.028.068a.809.809 0 0 1 .028.209v20.559l8.008-4.611v-10.51c0-.07.01-.141.028-.208.007-.024.02-.045.028-.068.016-.042.03-.085.052-.124.015-.026.037-.047.054-.071.024-.032.044-.065.072-.093.023-.023.052-.04.078-.06.03-.024.056-.05.088-.069h.001l9.611-5.533a.801.801 0 0 1 .8 0l9.61 5.533c.034.02.06.045.09.068.025.02.054.038.077.06.028.029.048.062.072.094.018.024.04.045.054.071.023.039.036.082.052.124.009.023.022.044.028.068zm-1.574 10.718v-9.124l-3.363 1.936-4.646 2.675v9.124l8.01-4.611zm-9.61 16.505v-9.13l-4.57 2.61-13.05 7.448v9.216l17.62-10.144zM1.602 7.719v31.068L19.22 48.93v-9.214l-9.204-5.209-.003-.002-.004-.002c-.031-.018-.057-.044-.086-.066-.025-.02-.054-.036-.076-.058l-.002-.003c-.026-.025-.044-.056-.066-.084-.02-.027-.044-.05-.06-.078l-.001-.003c-.018-.03-.029-.066-.042-.1-.013-.03-.03-.058-.038-.09v-.001c-.01-.038-.012-.078-.016-.117-.004-.03-.012-.06-.012-.09v-.002-21.481L4.965 9.654 1.602 7.72zm8.81-5.994L2.405 6.334l8.005 4.609 8.006-4.61-8.006-4.608zm4.164 28.764l4.645-2.674V7.719l-3.363 1.936-4.646 2.675v20.096l3.364-1.937zM39.243 7.164l-8.006 4.609 8.006 4.609 8.005-4.61-8.005-4.608zm-.801 10.605l-4.646-2.675-3.363-1.936v9.124l4.645 2.674 3.364 1.937v-9.124zM20.02 38.33l11.743-6.704 5.87-3.35-8-4.606-9.211 5.303-8.395 4.833 7.993 4.524z"/>
          </g>
        </svg>
      </div>

      <!-- Vue 3D Logo -->
      <div class="logo-3d vue-logo">
        <svg viewBox="0 0 261.76 226.69" xmlns="http://www.w3.org/2000/svg">
          <g fill="var(--vue-green)" opacity="0.15">
            <path d="M161.096.001l-30.224 52.35L100.647.002H-.005L130.872 226.69 261.749 0z" fill="#41b883"/>
            <path d="M161.096.001l-30.224 52.35L100.647.002H52.346l78.526 136.01L209.398.001z" fill="#34495e"/>
          </g>
        </svg>
      </div>

      <!-- Abstract Blob Shapes - Laravel focused -->
      <svg class="abstract-shape blob-1 laravel-blob" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
        <path fill="var(--laravel-red)" d="M44.7,-76.4C58.8,-69.2,71.8,-59.1,79.6,-45.8C87.4,-32.6,90,-16.3,88.5,-0.9C87,14.6,81.4,29.2,73.1,42.8C64.8,56.4,53.8,69,40.2,75.8C26.6,82.6,10.4,83.6,-5.3,81.3C-21,79,-42,73.4,-56.8,62.3C-71.6,51.2,-80.2,34.6,-83.8,16.8C-87.4,-1,-86,-20,-78.2,-36.4C-70.4,-52.8,-56.2,-66.6,-40.8,-73.3C-25.4,-80,-12.7,-79.5,1.3,-81.7C15.3,-83.9,30.6,-83.6,44.7,-76.4Z" transform="translate(100 100)" />
      </svg>

      <svg class="abstract-shape blob-3 vue-blob" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
        <path fill="var(--vue-green)" d="M47.1,-81.7C59.9,-72.3,68.5,-57.5,74.5,-42.1C80.5,-26.7,83.9,-10.7,83.1,5.1C82.3,20.9,77.3,36.5,68.4,49.9C59.5,63.3,46.7,74.5,32.1,79.8C17.5,85.1,1.1,84.5,-15.5,81.5C-32.1,78.5,-48.9,73.1,-62.3,63.1C-75.7,53.1,-85.7,38.5,-88.8,22.8C-91.9,7.1,-88.1,-9.7,-80.6,-24.3C-73.1,-38.9,-61.9,-51.3,-48.3,-60.3C-34.7,-69.3,-18.3,-74.9,-1.2,-72.9C15.9,-70.9,34.3,-91.1,47.1,-81.7Z" transform="translate(100 100)" />
      </svg>

      <!-- Dot Grid Pattern -->
      <div class="dot-grid"></div>
    </div>

    <div class="hero-content">
      <h1 class="hero-intro fade-in-up delay-1">Hi, my name is</h1>
      <h2 class="hero-name big-heading fade-in-up delay-2">MANSOUR SALEEM AL-DADAH</h2>
      <h3 class="hero-subtitle medium-heading fade-in-up delay-3">
        LARAVEL DEVELOPER <span class="tech-stack">(WITH VUE.JS)</span>
      </h3>

      <div class="hero-contact fade-in-up delay-4">
        <a href="mailto:m.aldadah24@gmail.com" class="contact-item" target="_blank" rel="noopener noreferrer">
          <svg class="icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
            <path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"></path>
            <polyline points="22,6 12,13 2,6"></polyline>
          </svg>
          <span>m.aldadah24@gmail.com</span>
        </a>

        <a href="https://wa.me/970595152274" class="contact-item" target="_blank" rel="noopener noreferrer">
          <svg class="icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
            <path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"></path>
          </svg>
          <span>+970595152274</span>
        </a>

        <a href="https://linkedin.com/in/mansour-aldadah" class="contact-item" target="_blank" rel="noopener noreferrer">
          <svg class="icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
            <path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"></path>
            <rect x="2" y="9" width="4" height="12"></rect>
            <circle cx="4" cy="4" r="2"></circle>
          </svg>
          <span>in/mansour-aldadah</span>
        </a>

        <a href="https://github.com/mansour-aldadah" class="contact-item" target="_blank" rel="noopener noreferrer">
          <svg class="icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
            <path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"></path>
          </svg>
          <span>github.com/mansour-aldadah</span>
        </a>
      </div>

      <p class="hero-description fade-in-up delay-5">
        I'm a Laravel Developer specializing in building robust backend systems and scalable web applications.
        With expertise in <span class="highlight laravel-highlight">Laravel</span> framework and modern
        <span class="highlight vue-highlight">Vue.js</span> for interactive frontends, I create efficient
        solutions that deliver exceptional performance and user experiences.
      </p>

      <div class="hero-cta fade-in-up delay-6">
        <a href="#contact" class="big-button">Get In Touch</a>
        <a href="/Mansour Al-Dadah CV.pdf" class="big-button secondary" download>Download CV</a>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Hero'
}
</script>

<style scoped>
.hero {
  display: flex;
  justify-content: center;
  align-items: flex-start;
  flex-direction: column;
  min-height: 100vh;
  padding: 0;
  position: relative;
  overflow: hidden;
  background-color: #1a1a1a;
}

.hero-bg {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 0;
  pointer-events: none;
  overflow: hidden;
  opacity: 0;
  animation: fadeIn 1s ease-out forwards;
}

/* 3D Logos */
.logo-3d {
  position: absolute;
  width: 350px;
  height: 350px;
  opacity: 0;
  animation: logoFadeIn 2s ease-out 0.5s forwards, float3d 25s ease-in-out 2.5s infinite;
}

.logo-3d img {
  width: 100%;
  height: 100%;
  object-fit: contain;
  opacity: 0.4;
}

@keyframes logoFadeIn {
  to {
    opacity: 1;
  }
}

.laravel-logo {
  top: 10%;
  left: 0;
  animation-delay: 0s;
}

.vue-logo {
  bottom: 10%;
  right: 0;
  animation-delay: 3s;
}

@keyframes float3d {
  0%, 100% {
    transform: translateY(0) translateX(0) rotate(0deg);
  }
  33% {
    transform: translateY(-40px) translateX(20px) rotate(3deg);
  }
  66% {
    transform: translateY(-20px) translateX(-15px) rotate(-3deg);
  }
}

/* Abstract Blob Shapes */
.abstract-shape {
  position: absolute;
  width: 600px;
  height: 600px;
  animation: blobFadeIn 1.5s ease-out forwards, morphing 20s ease-in-out 1.5s infinite;
  filter: blur(60px);
  opacity: 0;
}

@keyframes blobFadeIn {
  to {
    opacity: 0.25;
  }
}

/* Laravel Blobs - Larger and more prominent */
.laravel-blob {
  width: 450px;
  height: 450px;
}

.vue-blob {
  width: 400px;
  height: 400px;
}

.blob-1 {
  top: 10%;
  left: 5%;
  animation-delay: 0s, 0s;
}

.blob-2 {
  bottom: 15%;
  right: 10%;
  animation-delay: 0.2s, 1.7s;
}

.blob-3 {
  top: 45%;
  right: 5%;
  animation-delay: 0.4s, 1.9s;
}

.blob-4 {
  top: 60%;
  left: 15%;
  animation-delay: 0.6s, 2.1s;
}

.blob-5 {
  bottom: 30%;
  left: 25%;
  animation-delay: 0.8s, 2.3s;
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

/* Curved Lines */
.curved-line {
  position: absolute;
  width: 100%;
  height: auto;
}

.line-1 {
  top: 20%;
  animation: slide 15s linear infinite;
}

.line-2 {
  bottom: 25%;
  animation: slide 18s linear infinite reverse;
}

@keyframes slide {
  0% {
    transform: translateX(0);
  }
  100% {
    transform: translateX(-100px);
  }
}

/* Dot Grid Pattern */
.dot-grid {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-image: radial-gradient(circle, var(--lightest-navy) 1px, transparent 1px);
  background-size: 50px 50px;
  opacity: 0.15;
}

@keyframes float {
  0%, 100% {
    transform: translateY(0) rotate(0deg);
  }
  50% {
    transform: translateY(-30px) rotate(5deg);
  }
}

.hero-content {
  max-width: 1000px;
  width: 100%;
  padding: 0 25px;
  position: relative;
  z-index: 1;
}

.hero-intro {
  margin: 0 0 20px 4px;
  color: var(--green);
  font-family: var(--font-mono);
  font-size: clamp(var(--fz-sm), 5vw, var(--fz-md));
  font-weight: 400;
  opacity: 0;
  animation: fadeInUp 0.6s ease-out 0.1s forwards;
}

.hero-name {
  color: var(--lightest-slate);
  opacity: 0;
  font-weight: 700;
  letter-spacing: -1px;
  animation: fadeInUp 0.6s ease-out 0.2s forwards;
}

.hero-subtitle {
  margin-top: 15px;
  color: var(--slate);
  opacity: 0;
  font-weight: 600;
  animation: fadeInUp 0.6s ease-out 0.3s forwards;
}

.tech-stack {
  color: var(--green);
  font-family: var(--font-mono);
  font-size: clamp(var(--fz-lg), 3vw, var(--fz-xxl));
  font-weight: 400;
}

/* Hero Contact Info */
.hero-contact {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 15px;
  margin-top: 30px;
  opacity: 0;
  animation: fadeInUp 0.6s ease-out 0.4s forwards;
}

.contact-item {
  display: flex;
  align-items: center;
  gap: 12px;
  color: var(--slate);
  font-size: var(--fz-sm);
  font-family: var(--font-mono);
  transition: var(--transition);
  text-decoration: none;
  cursor: pointer;
}

.contact-item:hover {
  color: var(--green);
  transform: translateX(5px);
}

.contact-item .icon {
  width: 20px;
  height: 20px;
  min-width: 20px;
  color: var(--green);
}

.contact-item span {
  font-size: var(--fz-xs);
  word-break: break-word;
  overflow-wrap: anywhere;
}

.hero-description {
  margin: 25px 0 0 0;
  max-width: 600px;
  color: var(--slate);
  font-size: var(--fz-lg);
  line-height: 1.5;
  opacity: 0;
  animation: fadeInUp 0.6s ease-out 0.5s forwards;
}

.hero-description .highlight {
  font-family: var(--font-mono);
  font-size: var(--fz-md);
  font-weight: 600;
  transition: var(--transition);
  padding: 2px 6px;
  border-radius: 3px;
}

.hero-description .laravel-highlight {
  color: var(--laravel-red);
  background-color: rgba(255, 45, 32, 0.1);
}

.hero-description .laravel-highlight:hover {
  background-color: rgba(255, 45, 32, 0.2);
}

.hero-description .vue-highlight {
  color: var(--vue-green);
  background-color: rgba(66, 184, 131, 0.1);
}

.hero-description .vue-highlight:hover {
  background-color: rgba(66, 184, 131, 0.2);
}

.hero-cta {
  margin-top: 40px;
  opacity: 0;
  display: flex;
  gap: 20px;
  flex-wrap: wrap;
  animation: fadeInUp 0.6s ease-out 0.6s forwards;
}

.hero-cta .big-button.secondary {
  background-color: var(--lightest-navy);
  border-color: var(--lightest-navy);
  color: var(--lightest-slate);
}

.hero-cta .big-button.secondary:hover {
  background-color: var(--light-navy);
  border-color: var(--green);
  color: var(--green);
}

/* Responsive Design */
@media (max-width: 768px) {
  .hero-contact {
    grid-template-columns: 1fr;
  }

  .logo-3d {
    width: 300px;
    height: 300px;
  }

  .abstract-shape {
    width: 300px;
    height: 300px;
  }

  .hero-name {
    font-size: clamp(40px, 8vw, 60px) !important;
  }

  .hero-subtitle {
    font-size: clamp(30px, 6vw, 40px) !important;
  }

  .hero-cta {
    flex-direction: column;
  }

  .hero-cta .big-button {
    text-align: center;
  }
}

@media (max-width: 480px) {
  .hero-content {
    padding: 0 20px;
  }

  .contact-item span {
    font-size: 10px;
  }

  .contact-item .icon {
    width: 16px;
    height: 16px;
    min-width: 16px;
  }

  .logo-3d {
    width: 200px;
    height: 200px;
  }
}

@media (max-width: 480px) and (min-height: 700px) {
  .hero {
    padding-bottom: 10vh;
  }
}

@media (max-height: 700px) and (min-width: 700px) {
  .hero {
    height: auto;
    padding-top: calc(var(--nav-height) + 50px);
  }
}

@media (max-height: 700px) {
  .hero-name,
  .hero-subtitle {
    font-size: 50px;
  }
}
</style>