<template>
  <section id="about" class="section about-section">
    <div class="container">
      <div class="about-content">
        <img src="/ozim.jpg" alt="Asilbek Photo" class="about-img" />
        <div class="about-text">
          <h2>Men haqimda</h2>
          <div class="about-groups">
            <div class="about-group1">
              <div class="about-box">
                <h3>👤 Shaxsiy Ma’lumot</h3>
                <p>
                  Men <strong>Asilbek Oybekov</strong>, 2008-yilda
                  tug‘ilganman. O‘zbekiston Respublikasi,
                  <a
                    href="https://maps.app.goo.gl/zzFXpNrUSpTF1Wqo9"
                    target="_blank"
                    >Andijon</a
                  >
                  viloyatida yashayman.
                </p>
              </div>
              <div class="about-box">
                <h3>🎓 Ta’lim</h3>
                <p>
                  2023–2024-yillarda <strong>Unique</strong> o‘quv markazida
                  <strong>Frontend</strong> yo‘nalishi bo‘yicha tahsil oldim.
                  Web texnologiyalarni chuqur o‘rgandim.
                </p>
              </div>
            </div>
            <div class="about-group2">
              <div class="about-box">
                <h3>💼 Ish tajribasi</h3>
                <p>
                  2025-yildan boshlab
                  <a href="https://ongila.uz" target="_blank">Ongila MCHJ</a>
                  Frontend jamoasiga qo‘shildim. Hozirda zamonaviy web
                  interfeyslar ustida ishlayapman.
                </p>
              </div>
              <div class="about-box">
                <h3>🚀 Maqsadlar</h3>
                <p>
                  Yangi texnologiyalarni o‘rganishga qiziqaman.
                  Mening maqsadim qobiliyatli dasturchilardan iborat jamoa tuzish.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
// Import any necessary logic for the about section
</script>

<style scoped>
.about-section {
  background-color: #f0f4f8;
}

.about-content {
  display: flex;
  gap: 40px;
  align-items: center;
  flex-wrap: wrap;
  justify-content: center;
}

.about-img {
  width: 220px;
  height: 220px;
  border-radius: 50%;
  object-fit: cover;
  border: 5px solid #ffcc00;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
  transition: transform 0.3s ease;
}

.about-img:hover {
  transform: rotate(2deg) scale(1.05);
}

.about-text {
  flex: 1;
  display: flex;
  flex-direction: column;
  gap: 20px;
}

.about-groups {
  display: flex;
  gap: 40px;
  justify-content: space-between;
  flex-wrap: wrap;
  animation: fadeInUp 1s ease;
}
</style>
