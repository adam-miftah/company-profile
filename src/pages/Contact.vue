<template>
  <div class="container py-5">
    <div class="row align-items-center">
      <!-- Info Kontak -->
      <div class="col-md-6 mb-4" data-aos="fade-right">
        <h2 class="fw-bold mb-3">Hubungi Kami</h2>
        <p class="text-muted">Silakan tinggalkan pesan, tim kami akan segera menghubungi Anda dengan senang hati.</p>
        <ul class="list-unstyled mt-4">
          <li class="mb-3 d-flex align-items-center">
            <i class="bi bi-geo-alt text-primary fs-4 me-3"></i>
            <span>Jl. Sudirman No. 123, Jakarta</span>
          </li>
          <li class="mb-3 d-flex align-items-center">
            <i class="bi bi-telephone text-primary fs-4 me-3"></i>
            <span>+62 812 3456 7890</span>
          </li>
          <li class="mb-3 d-flex align-items-center">
            <i class="bi bi-envelope text-primary fs-4 me-3"></i>
            <span>info@propertiku.com</span>
          </li>
        </ul>
      </div>

      <!-- Form Kontak -->
      <div class="col-md-6" data-aos="fade-left">
        <form class="shadow-lg p-4 bg-white rounded-4">
          <div class="mb-3">
            <label class="form-label fw-semibold">Nama</label>
            <input type="text" class="form-control form-control-lg rounded-pill" placeholder="Nama lengkap">
          </div>
          <div class="mb-3">
            <label class="form-label fw-semibold">Email</label>
            <input type="email" class="form-control form-control-lg rounded-pill" placeholder="Alamat email">
          </div>
          <div class="mb-3">
            <label class="form-label fw-semibold">Pesan</label>
            <textarea class="form-control rounded-4" rows="4" placeholder="Tulis pesan Anda"></textarea>
          </div>
          <button type="submit" class="btn btn-primary w-100 btn-lg rounded-pill shadow-sm">
            <i class="bi bi-send me-2"></i> Kirim Pesan
          </button>
        </form>
      </div>
    </div>
  </div>
</template>
