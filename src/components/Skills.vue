<template>
  <section id="skills" class="section">
    <div class="container">
      <h2>Skills</h2>
      <ul class="skills-list">
        <li>
          <a href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="_blank">HTML</a>
        </li>
        <li>
          <a href="https://developer.mozilla.org/en-US/docs/Web/CSS" target="_blank">CSS</a>
        </li>
        <li>
          <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank">JavaScript</a>
        </li>
        <li>
          <a href="https://vuejs.org/" target="_blank">Vue.js</a>
        </li>
        <li>
          <a href="https://tailwindcss.com/" target="_blank">Tailwind</a>
        </li>
        <li>
          <a href="https://vuex.vuejs.org/" target="_blank">Vuex</a>
        </li>
        <li>
          <a href="https://www.primefaces.org/primevue/" target="_blank">Prime vue</a>
        </li>
        <li>
          <a href="https://github.com/" target="_blank">GitHub</a>
        </li>
        <li>
          <a href="https://www.figma.com/" target="_blank">Figma</a>
        </li>
      </ul>
    </div>
  </section>
</template>

<script setup>
// Import any necessary logic for the skills section
</script>

<style scoped>
.skills-list {
  list-style: none;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 20px;
  padding: 0;
  margin: 0;
}

.skills-list li a {
  display: inline-block;
  background-color: #333;
  color: white;
  text-decoration: none;
  padding: 12px 25px;
  border-radius: 25px;
  font-weight: 600;
  font-size: 16px;
  transition: background-color 0.3s ease, transform 0.3s ease;
}

.skills-list li a:hover {
  background-color: #ffcc00;
  color: #222;
  transform: scale(1.1);
}
</style>
