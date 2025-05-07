<template>
  <section id="projects" class="section">
    <div class="container">
      <h2>Projects</h2>
      <div class="projects-list">
        <a href="https://sinov-admin.ongila.uz/">
          <div class="project-item">
          <img src="/ongila.jpg" alt="Project 1 Image" class="project-img" />
          <h3>OngIla Admin panel</h3>
          <p>OngIla MCHJning admin paneli</p>
        </div>
        </a>
        <a href="https://clockstream.netlify.app/">
          <div class="project-item">
          <img src="/clockstream.jpg" alt="Project 2 Image" class="project-img" />
          <h3>Clockstream</h3>
          <p>Vaqt va sanani ko'rsatuvchi sayt</p>
        </div>
        </a>
      </div>
    </div>
  </section>
</template>

<script setup>
// Import any necessary logic for the projects section
</script>

<style scoped>
.projects-list {
  display: flex;
  gap: 30px;
  justify-content: center;
  flex-wrap: wrap;
  animation: fadeInUp 1s ease;
}

.project-item {
  background-color: #fff;
  border: 2px solid #ffcc00;
  border-radius: 10px;
  overflow: hidden;
  width: 300px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  text-align: center;
}

.project-item:hover {
  transform: scale(1.05);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
}

.project-img {
  width: 100%;
  height: 180px;
  object-fit: cover;
}

.project-item h3 {
  margin: 10px 0;
  color: #222;
}

.project-item p {
  color: #666;
  padding-bottom: 15px;
}
</style>
