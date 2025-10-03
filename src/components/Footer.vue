<template>
  <footer class="footer text-white pt-5 pb-3 mt-5">
    <div class="container">
      <div class="row gy-5 align-items-start">

        <!-- Brand -->
        <div class="col-lg-4 col-md-6 text-center text-md-start">
          <h4 class="fw-bold text-warning d-flex align-items-center justify-content-center justify-content-md-start mb-3">
            <i class="bi bi-building me-2"></i> PropertiKu
          </h4>
          <p class="small text-light opacity-75">
            Solusi hunian modern & investasi terpercaya sejak 2025.<br/>
            Memberikan pelayanan terbaik untuk kebutuhan properti Anda.
          </p>
        </div>

        <!-- Quick Links -->
        <div class="col-lg-4 col-md-6 text-center">
          <h6 class="fw-bold text-uppercase mb-3 text-warning">Navigasi</h6>
          <ul class="list-unstyled d-inline-block text-start">
            <li><router-link class="footer-link" to="/">Home</router-link></li>
            <li><router-link class="footer-link" to="/about">Tentang Kami</router-link></li>
            <li><router-link class="footer-link" to="/services">Layanan</router-link></li>
            <li><router-link class="footer-link" to="/projects">Proyek</router-link></li>
            <li><router-link class="footer-link" to="/contact">Kontak</router-link></li>
          </ul>
        </div>

        <!-- Social Media -->
        <div class="col-lg-4 col-md-12 text-center text-lg-end">
          <h6 class="fw-bold text-uppercase mb-3 text-warning">Ikuti Kami</h6>
          <div class="d-flex justify-content-center justify-content-lg-end gap-3 flex-wrap">
            <a href="https://facebook.com" target="_blank" class="social-link"><i class="bi bi-facebook"></i></a>
            <a href="https://instagram.com" target="_blank" class="social-link"><i class="bi bi-instagram"></i></a>
            <a href="https://twitter.com" target="_blank" class="social-link"><i class="bi bi-twitter"></i></a>
            <a href="https://linkedin.com" target="_blank" class="social-link"><i class="bi bi-linkedin"></i></a>
          </div>
        </div>
      </div>

      <!-- Divider -->
      <hr class="border-light my-4 opacity-25" />

      <!-- Copyright -->
      <div class="text-center small opacity-75">
        &copy; 2025 <span class="fw-bold text-warning">PropertiKu</span>. Published by 
        <a class="link-porto" href="https://adammiftah.com" target="_blank">adammiftah.com</a>
      </div>
    </div>
  </footer>
</template>

<style scoped>
.footer {
  background: linear-gradient(135deg, #0f0f0f, #1c1c1c, #2a2a2a);
  backdrop-filter: blur(10px);
  border-top: 1px solid rgba(255, 255, 255, 0.08);
  font-size: 0.95rem;
}

/* Footer links */
.footer-link {
  display: block;
  color: #bbb;
  text-decoration: none;
  margin-bottom: 8px;
  transition: all 0.3s ease;
}
.footer-link:hover {
  color: #0d6efd;
  transform: translateX(6px);
}

/* Social media */
.social-link {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 45px;
  height: 45px;
  border-radius: 50%;
  background: rgba(255, 255, 255, 0.08);
  color: #ddd;
  font-size: 1.2rem;
  transition: all 0.3s ease;
}
.social-link:hover {
  background: #0d6efd;
  color: #fff;
  transform: scale(1.15) rotate(5deg);
}

/* Portfolio link */
.link-porto {
  text-decoration: none;
  color: #bbb;
  font-weight: 500;
  transition: all 0.3s ease;
}
.link-porto:hover {
  text-decoration: underline;
  color: #0d6efd;
}

/* Responsive tweaks */
@media (max-width: 768px) {
  .footer {
    text-align: center;
  }
  .footer h4, 
  .footer h6 {
    justify-content: center;
  }
}
</style>
