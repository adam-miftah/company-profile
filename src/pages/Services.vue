<template>
  <section id="services" class="services-section py-5">
    <div class="container">
      <!-- Judul -->
      <div class="text-center mb-5" data-aos="fade-up">
        <h2 class="fw-bold">Layanan Kami</h2>
        <p class="text-muted">
          Kami menyediakan layanan profesional di bidang properti dengan kualitas terbaik
          untuk membantu Anda mewujudkan hunian impian dan investasi bernilai tinggi.
        </p>
      </div>

      <!-- Card Services -->
      <div class="row g-4">
        <!-- Service Card -->
        <div class="col-md-6 col-lg-4" v-for="(service, i) in services" :key="i" data-aos="fade-up" :data-aos-delay="i*100">
          <div class="card h-100 shadow-sm service-card">
            <div class="card-body text-center">
              <div class="icon-wrapper mx-auto mb-3">
                <i :class="service.icon"></i>
              </div>
              <h5 class="fw-bold">{{ service.title }}</h5>
              <p class="text-muted">{{ service.desc }}</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
const services = [
  { title: 'Pengembangan Properti', desc: 'Membangun hunian modern & investasi bernilai tinggi dengan kualitas premium.', icon: 'bi bi-building' },
  { title: 'Konsultasi', desc: 'Diskusikan kebutuhan properti Anda dengan tim ahli kami.', icon: 'bi bi-people' },
  { title: 'Investasi', desc: 'Solusi investasi properti terpercaya dengan keuntungan jangka panjang.', icon: 'bi bi-cash-stack' },
  { title: 'Manajemen Properti', desc: 'Mengelola aset properti agar terawat & produktif.', icon: 'bi bi-house-heart' },
  { title: 'Kemitraan Bisnis', desc: 'Membuka peluang kerjasama dengan investor & mitra strategis.', icon: 'bi bi-briefcase' },
  { title: 'Riset & Inovasi', desc: 'Solusi properti berbasis teknologi modern & ramah lingkungan.', icon: 'bi bi-globe2' },
]
</script>

<style scoped>
.services-section {
  background: #f9f9f9;
}

/* Card Styling */
.service-card {
  border: none;
  transition: all 0.3s ease;
  border-radius: 16px;
  cursor: pointer;
}
.service-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
}

/* Icon Wrapper */
.icon-wrapper {
  width: 70px;
  height: 70px;
  background: linear-gradient(135deg, #0d6efd, #6610f2);
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  font-size: 2rem;
  transition: all 0.3s ease;
}
.service-card:hover .icon-wrapper {
  background: linear-gradient(135deg, #6610f2, #0d6efd);
  transform: rotate(10deg) scale(1.1);
}

/* Responsif Heading */
h2 {
  font-size: 2rem;
}
@media (min-width: 768px) {
  h2 {
    font-size: 2.5rem;
  }
}
</style>
