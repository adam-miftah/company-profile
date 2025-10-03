<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-white shadow-sm fixed-top">
    <div class="container">
      <!-- Logo -->
      <router-link to="/" class="navbar-brand fw-bold fs-4">
        Properti<span class="text-primary">Ku</span>
      </router-link>

      <!-- Hamburger Button -->
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <!-- Menu Items -->
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto mb-2 mb-lg-0 align-items-lg-center">
          <li class="nav-item">
            <router-link to="/" exact class="nav-link">Home</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/about" class="nav-link">Tentang Kami</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/services" class="nav-link">Layanan</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/team" class="nav-link">Tim Kami</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/contact" class="nav-link">Kontak</router-link>
          </li>

          <!-- CTA -->
          <li class="nav-item ms-lg-3 mt-3 mt-lg-0">
            <router-link
              to="/contact"
              class="btn btn-primary px-4 rounded-pill shadow-sm cta-btn"
              :exact-active-class="''"
            >
              Get Started
            </router-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<style scoped>
/* Navbar Style */
.navbar {
  transition: all 0.3s ease;
}

.navbar-brand {
  font-weight: 700;
  letter-spacing: 0.5px;
}

.nav-link {
  position: relative;
  font-weight: 500;
  margin: 0 8px;
  transition: color 0.3s ease;
}

.nav-link:hover {
  color: #0d6efd; /* Bootstrap primary */
}

/* Garis bawah animasi */
.nav-link.router-link-exact-active::after {
  content: "";
  position: absolute;
  bottom: -4px;
  left: 0;
  width: 100%;
  height: 2px;
  background: #0d6efd;
  border-radius: 5px;
  animation: slideIn 0.3s ease forwards;
}

@keyframes slideIn {
  from {
    width: 0;
  }
  to {
    width: 100%;
  }
}

/* CTA Button */
.cta-btn {
  font-weight: 600;
  transition: all 0.3s ease;
}

.cta-btn:hover {
  background-color: #0b5ed7;
  transform: translateY(-2px);
  box-shadow: 0 6px 12px rgba(13, 110, 253, 0.3);
}

/* Responsif tambahan */
@media (max-width: 992px) {
  .nav-link {
    margin: 8px 0;
  }
  .cta-btn {
    width: 100%;
    text-align: center;
  }
}
</style>
