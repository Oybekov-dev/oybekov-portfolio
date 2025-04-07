<template>
  <header class="navbar">
    <div class="container">
      <h1 class="logo">My Portfolio</h1>
      <nav>
        <ul>
          <li><a href="#about">About</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="#skills">Skills</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script setup>
// Import any necessary logic for the navbar
</script>

<style scoped>
.navbar {
  background-color: #222;
  color: white;
  padding: 10px 0;
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  z-index: 1000;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.navbar .container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-size: 24px;
  font-weight: 600;
  color: #ffcc00;
}

.navbar nav ul {
  list-style: none;
  display: flex;
  gap: 25px;
}

.navbar nav ul li a {
  color: white;
  font-size: 16px;
  text-transform: uppercase;
  padding: 6px 12px;
  transition: color 0.3s ease, transform 0.3s ease;
  text-decoration: none;
}

.navbar nav ul li a:hover {
  color: #ffcc00;
  transform: scale(1.1);
}
</style>
