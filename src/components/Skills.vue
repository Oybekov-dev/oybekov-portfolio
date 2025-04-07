<template>
  <section id="skills" class="section">
    <div class="container">
      <h2>Skills</h2>
      <ul class="skills-list">
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
        <li>Vue.js</li>
        <li>Tailwind</li>
        <li>Vuex</li>
        <li>Prime vue</li>
        <li>GitHub</li>
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
}

.skills-list li {
  background-color: #333;
  color: white;
  padding: 12px 25px;
  border-radius: 25px;
  font-weight: 600;
  font-size: 16px;
  transition: background-color 0.3s ease, transform 0.3s ease;
}

.skills-list li:hover {
  background-color: #ffcc00;
  color: #222;
  transform: scale(1.1);
}
</style>
