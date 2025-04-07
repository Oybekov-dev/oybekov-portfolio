<template>
  <section id="contact" class="section contact-section">
    <div class="container">
      <h2>Contact Me</h2>
      <form id="contact-form">
        <input type="text" id="name" placeholder="Your Name" required />
        <input type="email" id="email" placeholder="Your Email" required />
        <textarea id="message" placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
      </form>
      <p>Follow me on social media:</p>
      <div class="social-media">
        <a href="https://t.me/Asilbek_0419" target="_blank" class="social-icon">Telegram</a>
        <a href="https://github.com/Oybekov-dev" target="_blank" class="social-icon">GitHub</a>
        <a href="https://www.instagram.com/as1lbek_7067" target="_blank" class="social-icon">Instagram</a>
      </div>
    </div>
  </section>
</template>

<script setup>
// Import any necessary logic for the contact section
</script>

<style scoped>
.contact-section {
  background-color: #eef2f5;
  text-align: center;
}

#contact-form {
  display: flex;
  flex-direction: column;
  gap: 15px;
  margin-top: 20px;
  max-width: 500px;
  margin-inline: auto;
}

#contact-form input,
#contact-form textarea {
  padding: 12px;
  border-radius: 5px;
  border: 1px solid #ccc;
  font-size: 16px;
  width: 100%;
}

#contact-form textarea {
  resize: vertical;
  min-height: 100px;
}

#contact-form button {
  padding: 12px;
  background-color: #222;
  color: white;
  border: none;
  border-radius: 5px;
  font-size: 16px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

#contact-form button:hover {
  background-color: #ffcc00;
  color: #222;
}

.social-media {
  display: flex;
  justify-content: center;
  gap: 20px;
  margin-top: 20px;
}

.social-icon {
  background-color: #ffcc00;
  color: #222;
  padding: 10px 20px;
  border-radius: 8px;
  text-decoration: none;
  font-weight: bold;
  transition: background-color 0.3s ease;
}

.social-icon:hover {
  background-color: #222;
  color: white;
}
</style>
