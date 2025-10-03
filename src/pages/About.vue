<script setup>
import aboutImage from '../assets/about.jpg'
</script>

<template>
  <section id="about" class="about-section py-5 bg-light">
    <div class="container">
      <div class="row align-items-center g-1">
        <!-- Gambar -->
        <div class="col-lg-6" data-aos="fade-right">
          <img :src="aboutImage" alt="Tentang Kami" class="img-fluid w-50 h-50 rounded-4 shadow-lg" />
        </div>

        <!-- Konten -->
        <div class="col-lg-6 text-center text-lg-start" data-aos="fade-left">
          <h2 class="fw-bold mb-3">
            Tentang <span class="text-primary">PropertiKu</span>
          </h2>
          <p class="text-muted mb-3">
            Kami adalah perusahaan properti yang berfokus pada <strong>hunian modern</strong> 
            dan <strong>investasi terpercaya</strong>. Dengan pengalaman lebih dari 
            <strong>10 tahun</strong>, kami telah menyelesaikan ratusan proyek 
            perumahan, apartemen, hingga area komersial di berbagai kota besar Indonesia.
          </p>
          <p class="text-muted mb-4">
            PropertiKu hadir untuk memberikan <em>solusi lengkap</em> bagi setiap kebutuhan properti, 
            mulai dari pengembangan, pembelian, hingga konsultasi investasi. 
            Dengan dukungan tim profesional, kami selalu mengutamakan 
            <strong>kualitas, transparansi, dan kepuasan pelanggan</strong> dalam setiap proyek.
          </p>
          <router-link to="/services" class="btn btn-primary px-4 py-2 rounded-pill shadow-sm">
            Pelajari Layanan Kami <i class="bi bi-arrow-right ms-2"></i>
          </router-link>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.about-section {
  background: linear-gradient(to bottom right, #f8f9fa, #ffffff);
}

/* Judul */
.about-section h2 {
  font-size: 2rem;
}
@media (min-width: 768px) {
  .about-section h2 {
    font-size: 2.4rem;
  }
}

/* Paragraf */
.about-section p {
  font-size: 1rem;
  line-height: 1.7;
}

/* Tombol */
.btn-primary {
  background: linear-gradient(45deg, #0d6efd, #0a58ca);
  border: none;
  transition: all 0.3s ease;
}
.btn-primary:hover {
  background: linear-gradient(45deg, #0a58ca, #084298);
  transform: translateY(-2px);
}
</style>
