<template>
  <header class="header">
    <nav class="nav">
      <div class="nav-logo">
        <a href="#" aria-label="home">
          <div class="logo">M</div>
        </a>
      </div>

      <div class="nav-links">
        <ol>
          <li><a href="#about" class="nav-link">About</a></li>
          <li><a href="#skills" class="nav-link">Skills</a></li>
          <li><a href="#projects" class="nav-link">Projects</a></li>
          <li><a href="#contact" class="nav-link">Contact</a></li>
        </ol>
        <div class="resume-link">
          <a href="/Mansour Al-Dadah CV.pdf" class="big-button" target="_blank" rel="noopener noreferrer">
            Resume
          </a>
        </div>
      </div>

      <div class="menu-btn" @click="toggleMenu">
        <div class="hamburger" :class="{ active: menuOpen }">
          <span></span>
          <span></span>
          <span></span>
        </div>
      </div>
    </nav>

    <aside class="sidebar" :class="{ open: menuOpen }">
      <nav>
        <ol>
          <li><a href="#about" @click="closeMenu">About</a></li>
          <li><a href="#skills" @click="closeMenu">Skills</a></li>
          <li><a href="#projects" @click="closeMenu">Projects</a></li>
          <li><a href="#contact" @click="closeMenu">Contact</a></li>
        </ol>
        <a href="/Mansour Al-Dadah CV.pdf" class="big-button" target="_blank" rel="noopener noreferrer">
          Resume
        </a>
      </nav>
    </aside>
  </header>
</template>

<script>
export default {
  name: 'Navigation',
  data() {
    return {
      menuOpen: false
    }
  },
  methods: {
    toggleMenu() {
      this.menuOpen = !this.menuOpen
    },
    closeMenu() {
      this.menuOpen = false
    }
  }
}
</script>

<style scoped>
.header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  position: fixed;
  top: 0;
  z-index: 11;
  padding: 0px 50px;
  width: 100%;
  height: var(--nav-height);
  background-color: rgba(26, 26, 26, 0.9);
  backdrop-filter: blur(10px);
  transition: var(--transition);
  filter: none !important;
  pointer-events: auto !important;
  user-select: auto !important;
}

.nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 100%;
  color: var(--lightest-slate);
  font-family: var(--font-mono);
  counter-reset: item 0;
  z-index: 12;
}

.logo {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 42px;
  height: 42px;
  border: 2px solid var(--green);
  border-radius: 4px;
  color: var(--green);
  font-family: var(--font-mono);
  font-size: 18px;
  font-weight: 600;
  transition: var(--transition);
}

.logo:hover {
  background-color: var(--green-tint);
}

.nav-links {
  display: flex;
  align-items: center;
}

.nav-links ol {
  display: flex;
  align-items: center;
  padding: 0;
  margin: 0;
  list-style: none;
}

.nav-links li {
  margin: 0 5px;
  position: relative;
  counter-increment: item 1;
  font-size: var(--fz-xs);
}

.nav-link {
  padding: 10px;
  color: var(--lightest-slate);
  font-family: var(--font-mono);
  font-size: var(--fz-xs);
  font-weight: 400;
}

.nav-link:before {
  content: "0" counter(item) ".";
  margin-right: 5px;
  color: var(--green);
  font-size: var(--fz-xxs);
  text-align: right;
}

.nav-link:hover {
  color: var(--green);
}

.resume-link {
  margin-left: 15px;
}

.menu-btn {
  display: none;
  justify-content: center;
  align-items: center;
  position: relative;
  z-index: 10;
  margin-right: -15px;
  padding: 15px;
  border: 0;
  background-color: transparent;
  color: inherit;
  text-transform: none;
  transition-timing-function: linear;
  transition-duration: 0.15s;
  transition-property: opacity, filter;
}

.hamburger {
  display: inline-block;
  position: relative;
  width: var(--hamburger-width);
  height: 24px;
}

.hamburger span {
  display: block;
  position: absolute;
  left: 0;
  right: 0;
  height: 2px;
  background-color: var(--green);
  border-radius: var(--border-radius);
  transition: var(--transition);
}

.hamburger span:nth-child(1) {
  top: 0px;
  transition: var(--ham-before);
}

.hamburger span:nth-child(2) {
  top: 11px;
}

.hamburger span:nth-child(3) {
  top: 22px;
  transition: var(--ham-after);
}

.hamburger.active span:nth-child(1) {
  top: 11px;
  transform: rotate(45deg);
  transition: var(--ham-before-active);
}

.hamburger.active span:nth-child(2) {
  opacity: 0;
}

.hamburger.active span:nth-child(3) {
  top: 11px;
  transform: rotate(-45deg);
  transition: var(--ham-after-active);
}

.sidebar {
  display: none;
  position: fixed;
  top: 0;
  bottom: 0;
  right: 0;
  padding: 50px 10px;
  width: min(75vw, 400px);
  height: 100vh;
  outline: 0;
  background-color: var(--light-navy);
  box-shadow: -10px 0px 30px -15px var(--navy-shadow);
  z-index: 9;
  transform: translateX(100vw);
  visibility: hidden;
  transition: var(--transition);
}

.sidebar.open {
  transform: translateX(0vw);
  visibility: visible;
}

.sidebar nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  flex-direction: column;
  color: var(--lightest-slate);
  font-family: var(--font-mono);
  text-align: center;
}

.sidebar ol {
  padding: 0;
  margin: 0;
  list-style: none;
  width: 100%;
}

.sidebar li {
  position: relative;
  margin: 0 auto 20px;
  counter-increment: item 1;
  font-size: clamp(var(--fz-sm), 4vw, var(--fz-lg));
}

.sidebar a {
  display: inline-block;
  text-decoration: none;
  text-decoration-skip-ink: auto;
  color: inherit;
  position: relative;
  transition: var(--transition);
  width: 100%;
  padding: 3px 20px 20px;
}

.sidebar a:before {
  content: "0" counter(item) ".";
  display: block;
  margin-bottom: 5px;
  color: var(--green);
  font-size: var(--fz-sm);
}

.sidebar .big-button {
  margin: 10% auto 0;
}

@media (max-width: 768px) {
  .header {
    padding: 0 40px;
  }
}

@media (max-width: 480px) {
  .header {
    padding: 0 25px;
  }
}

@media (max-width: 768px) {
  .nav-links {
    display: none;
  }

  .menu-btn {
    display: flex;
  }

  .sidebar {
    display: flex;
  }
}
</style>