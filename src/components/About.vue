<template>
  <section class="about" id="about">
    <!-- Abstract Background -->
    <div class="about-bg">
      <!-- Laravel 3D Logo -->
      <div class="tech-icon laravel-icon">
        <svg viewBox="0 0 50 52" xmlns="http://www.w3.org/2000/svg">
          <g fill="var(--laravel-red)" opacity="0.15">
            <path
              d="M49.626 11.564a.809.809 0 0 1 .028.209v10.972a.8.8 0 0 1-.402.694l-9.209 5.302V39.25c0 .286-.152.55-.4.694L20.42 51.01c-.044.025-.092.041-.14.058-.018.006-.035.017-.054.022a.805.805 0 0 1-.41 0c-.022-.006-.042-.018-.063-.026-.044-.016-.09-.03-.132-.054L.402 39.944A.801.801 0 0 1 0 39.25V6.334c0-.072.01-.142.028-.21.006-.023.02-.044.028-.067.015-.042.029-.085.051-.124.015-.026.037-.047.055-.071.023-.032.044-.065.071-.093.023-.023.053-.04.079-.06.029-.024.055-.05.088-.069h.001l9.61-5.533a.802.802 0 0 1 .8 0l9.61 5.533h.002c.032.02.059.045.088.068.026.02.055.038.078.06.028.029.048.062.072.094.017.024.04.045.054.071.023.04.036.082.052.124.008.023.022.044.028.068a.809.809 0 0 1 .028.209v20.559l8.008-4.611v-10.51c0-.07.01-.141.028-.208.007-.024.02-.045.028-.068.016-.042.03-.085.052-.124.015-.026.037-.047.054-.071.024-.032.044-.065.072-.093.023-.023.052-.04.078-.06.03-.024.056-.05.088-.069h.001l9.611-5.533a.801.801 0 0 1 .8 0l9.61 5.533c.034.02.06.045.09.068.025.02.054.038.077.06.028.029.048.062.072.094.018.024.04.045.054.071.023.039.036.082.052.124.009.023.022.044.028.068zm-1.574 10.718v-9.124l-3.363 1.936-4.646 2.675v9.124l8.01-4.611zm-9.61 16.505v-9.13l-4.57 2.61-13.05 7.448v9.216l17.62-10.144zM1.602 7.719v31.068L19.22 48.93v-9.214l-9.204-5.209-.003-.002-.004-.002c-.031-.018-.057-.044-.086-.066-.025-.02-.054-.036-.076-.058l-.002-.003c-.026-.025-.044-.056-.066-.084-.02-.027-.044-.05-.06-.078l-.001-.003c-.018-.03-.029-.066-.042-.1-.013-.03-.03-.058-.038-.09v-.001c-.01-.038-.012-.078-.016-.117-.004-.03-.012-.06-.012-.09v-.002-21.481L1.602 7.72zm8.81-5.994L2.405 6.334l8.005 4.609 8.006-4.61-8.006-4.608zm4.164 28.764l4.645-2.674V7.719l-3.363 1.936-4.646 2.675v20.096l3.364-1.937zM39.243 7.164l-8.006 4.609 8.006 4.609 8.005-4.61-8.005-4.608zm-.801 10.605l-4.646-2.675-3.363-1.936v9.124l4.645 2.674 3.364 1.937v-9.124zM20.02 38.33l11.743-6.704 5.87-3.35-8-4.606-9.211 5.303-8.395 4.833 7.993 4.524z"
            />
          </g>
        </svg>
      </div>

      <!-- Vue 3D Logo -->
      <div class="tech-icon vue-icon">
        <svg viewBox="0 0 261.76 226.69" xmlns="http://www.w3.org/2000/svg">
          <g fill="var(--vue-green)" opacity="0.15">
            <path d="M161.096.001l-30.224 52.35L100.647.002H-.005L130.872 226.69 261.749 0z" fill="#41b883"/>
            <path d="M161.096.001l-30.224 52.35L100.647.002H52.346l78.526 136.01L209.398.001z" fill="#34495e"/>
          </g>
        </svg>
      </div>

      <!-- Abstract Blob Shapes -->
      <svg
        class="abstract-shape blob-1"
        viewBox="0 0 200 200"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          fill="var(--laravel-red)"
          d="M44.7,-76.4C58.8,-69.2,71.8,-59.1,79.6,-45.8C87.4,-32.6,90,-16.3,88.5,-0.9C87,14.6,81.4,29.2,73.1,42.8C64.8,56.4,53.8,69,40.2,75.8C26.6,82.6,10.4,83.6,-5.3,81.3C-21,79,-42,73.4,-56.8,62.3C-71.6,51.2,-80.2,34.6,-83.8,16.8C-87.4,-1,-86,-20,-78.2,-36.4C-70.4,-52.8,-56.2,-66.6,-40.8,-73.3C-25.4,-80,-12.7,-79.5,1.3,-81.7C15.3,-83.9,30.6,-83.6,44.7,-76.4Z"
          transform="translate(100 100)"
        />
      </svg>

      <svg
        class="abstract-shape blob-2"
        viewBox="0 0 200 200"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          fill="var(--vue-green)"
          d="M39.5,-65.6C51.4,-58.1,61.3,-47.3,68.1,-34.8C74.9,-22.3,78.6,-8.1,78.3,6.2C78,20.5,73.7,35,65.8,47.2C57.9,59.4,46.4,69.3,33.3,74.8C20.2,80.3,5.5,81.4,-9.8,78.9C-25.1,76.4,-41,70.3,-54.3,60.5C-67.6,50.7,-78.3,37.2,-82.4,21.8C-86.5,6.4,-84,-10.9,-76.8,-25.5C-69.6,-40.1,-57.7,-52,-44.2,-59.8C-30.7,-67.6,-15.4,-71.3,-0.3,-70.8C14.8,-70.3,27.6,-73.1,39.5,-65.6Z"
          transform="translate(100 100)"
        />
      </svg>
    </div>

    <h2 class="section-heading">About Me</h2>

    <div class="about-content">
      <div class="about-text">
        <div>
          <p>
            Hello! I'm Mansour, a Full Stack Web Developer based in Gaza,
            Palestine. I enjoy creating things that live on the internet,
            whether that be websites, applications, or anything in between.
          </p>

          <p>
            My main focus these days is building scalable SaaS and SPA
            applications using
            <a
              href="https://laravel.com/"
              class="inline-link"
              target="_blank"
              rel="noopener noreferrer"
              >Laravel</a
            >
            and
            <a
              href="https://vuejs.org/"
              class="inline-link"
              target="_blank"
              rel="noopener noreferrer"
              >Vue.js</a
            >. I have over 2+ years of experience in full-stack development,
            having delivered 5+ Laravel-based applications for clients across
            healthcare, retail, and internal business tools sectors.
          </p>

          <p>
            I recently contributed to
            <a href="#" class="inline-link">Kamal Edwan Hospital</a>
            by developing a custom Fuel Management System that digitizes and
            streamlines internal operations, showcasing my ability to create
            impactful solutions for real-world problems.
          </p>

          <p>Here are a few technologies I've been working with recently:</p>

          <ul class="skills-list">
            <li>PHP & Laravel</li>
            <li>JavaScript (ES6+)</li>
            <li>Vue.js & Inertia.js</li>
            <li>React.js</li>
            <li>MySQL & RESTful APIs</li>
            <li>Tailwind CSS</li>
          </ul>
        </div>
      </div>

      <div class="about-pic">
        <div class="wrapper">
          <div class="img-placeholder">
            <div class="placeholder-content">
              <img
                src="../assets/images/Personal image.jpg"
                alt="Mansour Al-Dadah"
              />
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "About"
};
</script>

<style scoped>
.about {
  max-width: 900px;
  margin: 0 auto;
  padding: 100px 0;
  position: relative;
}

.about-bg {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 0;
  pointer-events: none;
  overflow: hidden;
}

/* 3D Logos */
.tech-icon {
  position: absolute;
  width: 300px;
  height: 300px;
  opacity: 0.8;
  animation: float 20s ease-in-out infinite;
}

.tech-icon img {
  width: 100%;
  height: 100%;
  object-fit: contain;
  opacity: 0.3;
}

.laravel-icon {
  top: 10%;
  right: -50px;
  animation-delay: 0s;
}

.vue-icon {
  bottom: 5%;
  left: -60px;
  animation-delay: 2s;
}

@keyframes float {
  0%,
  100% {
    transform: translateY(0) translateX(0) rotate(0deg);
  }
  33% {
    transform: translateY(-30px) translateX(15px) rotate(3deg);
  }
  66% {
    transform: translateY(-15px) translateX(-10px) rotate(-3deg);
  }
}

.abstract-shape {
  position: absolute;
  width: 300px;
  height: 300px;
  animation: morphing 20s ease-in-out infinite;
  filter: blur(50px);
  opacity: 0.15;
}

.blob-1 {
  top: 15%;
  right: 5%;
  animation-delay: 1s;
}

.blob-2 {
  bottom: 25%;
  left: 0%;
  animation-delay: 2.5s;
}

@keyframes morphing {
  0%,
  100% {
    transform: translate(0, 0) scale(1) rotate(0deg);
  }
  33% {
    transform: translate(30px, -50px) scale(1.2) rotate(120deg);
  }
  66% {
    transform: translate(-20px, 30px) scale(0.95) rotate(240deg);
  }
}

.about-content {
  display: grid;
  grid-template-columns: 3fr 2fr;
  grid-gap: 50px;
  position: relative;
  z-index: 1;
}

.about-text {
  color: var(--slate);
  font-size: var(--fz-lg);
}

.about-text p {
  margin: 0 0 15px 0;
}

.skills-list {
  display: grid;
  grid-template-columns: repeat(2, minmax(140px, 200px));
  grid-gap: 0px 10px;
  padding: 0;
  margin: 20px 0 0 0;
  overflow: hidden;
  list-style: none;
}

.skills-list li {
  position: relative;
  margin-bottom: 10px;
  padding-left: 20px;
  font-family: var(--font-mono);
  font-size: var(--fz-xs);
  color: var(--slate);
}

.skills-list li:before {
  content: "▹";
  position: absolute;
  left: 0;
  color: var(--green);
  font-size: var(--fz-sm);
  line-height: 12px;
}

.about-pic {
  position: relative;
  max-width: 300px;
}

.wrapper {
  position: relative;
  width: 100%;
  border-radius: var(--border-radius);
  background-color: transparent;
  transition: var(--transition);
}

.wrapper:hover .img-placeholder {
  filter: none;
  mix-blend-mode: normal;
}

.wrapper:hover .img-placeholder:before {
  background: transparent;
}

.img-placeholder {
  position: relative;
  border-radius: var(--border-radius);
  mix-blend-mode: normal;
  filter: none;
  transition: var(--transition);
  background-color: var(--light-navy);
  width: 100%;
  aspect-ratio: 1;
  display: flex;
  align-items: center;
  justify-content: center;
}

.img-placeholder:before {
  content: "";
  position: absolute;
  width: 100%;
  height: 100%;
  inset: 0;
  background-color: rgba(0, 0, 0, 0.3);
  mix-blend-mode: normal;
  border-radius: var(--border-radius);
  transition: var(--transition);
}

.placeholder-content {
  position: relative;
  z-index: 2;
  color: var(--green);
  opacity: 0.7;
}

.placeholder-content img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: var(--border-radius);
  display: block;
}

@media (max-width: 768px) {
  .about-content {
    display: block;
  }

  .about-pic {
    margin: 50px auto 0;
    width: 70%;
  }
}

@media (max-width: 480px) {
  .about {
    padding: 60px 0;
  }

  .skills-list {
    grid-template-columns: repeat(1, minmax(140px, 200px));
  }
}
</style>
