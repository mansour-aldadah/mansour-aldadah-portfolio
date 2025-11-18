<template>
  <div class="email-sidebar">
    <div class="email-link">
      <a href="mailto:m.aldadah24@gmail.com">m.aldadah24@gmail.com</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'EmailSidebar'
}
</script>

<style scoped>
.email-sidebar {
  position: fixed;
  bottom: 0;
  right: 40px;
  left: auto;
  z-index: 10;
  color: var(--light-slate);
}

.email-link {
  display: flex;
  flex-direction: column;
  align-items: center;
  position: relative;
}

.email-link:after {
  content: '';
  display: block;
  width: 1px;
  height: 90px;
  margin: 0 auto;
  background-color: var(--light-slate);
}

.email-link a {
  margin: 20px auto;
  padding: 10px;
  font-family: var(--font-mono);
  font-size: var(--fz-xxs);
  line-height: var(--fz-lg);
  letter-spacing: 0.1em;
  writing-mode: vertical-rl;
  color: var(--light-slate);
  transition: var(--transition);
}

.email-link a:hover,
.email-link a:focus {
  color: var(--green);
  transform: translateY(-3px);
}

@media (max-width: 1080px) {
  .email-sidebar {
    right: 20px;
  }
}

@media (max-width: 768px) {
  .email-sidebar {
    display: none;
  }
}
</style>