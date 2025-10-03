<template>
  <div>

    <!-- HERO -->
    <section class="hero d-flex align-items-center text-center text-white">
      <div class="container" data-aos="fade-up">
        <h1 class="fw-bold display-4">Selamat Datang di PropertiKu</h1>
        <p class="lead">Partner terpercaya Anda dalam investasi & hunian modern</p>
        <router-link to="/projects" class="btn btn-primary btn-lg mt-3">Lihat Proyek</router-link>
      </div>
    </section>

    <!-- ABOUT -->
    <section id="about" class="py-5 bg-light">
      <div class="container text-center">
        <h2 class="fw-bold">Tentang Kami</h2>
        <p class="mt-3">
          PropertiKu adalah perusahaan properti yang fokus pada pengembangan hunian modern, investasi
          bernilai tinggi, serta solusi properti yang berkelanjutan. Sejak berdiri, kami terus berkomitmen
          menghadirkan layanan yang profesional, transparan, dan inovatif demi memberikan pengalaman terbaik
          bagi setiap klien. Dengan dukungan tim ahli dan jaringan mitra yang luas, kami tidak hanya membangun
          properti, tetapi juga menciptakan lingkungan hidup yang nyaman, aman, dan memiliki nilai tambah jangka panjang.
        </p>
        <p>
          Visi kami adalah menjadi partner terpercaya masyarakat dalam mewujudkan impian memiliki hunian
          ideal sekaligus membuka peluang investasi yang menguntungkan. PropertiKu percaya bahwa setiap
          hunian bukan hanya tempat tinggal, melainkan juga aset berharga untuk masa depan. Oleh karena itu,
          kami senantiasa menghadirkan proyek-proyek berkualitas dengan lokasi strategis, desain modern,
          dan fasilitas lengkap yang mendukung gaya hidup Anda.
        </p>
      </div>
    </section>
<hr>
    <!-- SERVICES -->
    <section id="services" class="py-5">
      <div class="container text-center">
        <h2 class="fw-bold">Layanan Kami</h2>
        <p class="text-muted mb-5">Kami menyediakan layanan profesional di bidang properti.</p>
        <div class="row g-4">
          
          <!-- Card 1 -->
          <div class="col-md-4">
            <div class="card h-100 shadow-sm">
              <div class="card-body">
                <i class="bi bi-building display-4 text-primary"></i>
                <h5 class="mt-3 fw-bold">Pengembangan Properti</h5>
                <p>Kami membangun hunian dan investasi bernilai tinggi dengan kualitas premium.</p>
              </div>
            </div>
          </div>

          <!-- Card 2 -->
          <div class="col-md-4">
            <div class="card h-100 shadow-sm">
              <div class="card-body">
                <i class="bi bi-people display-4 text-primary"></i>
                <h5 class="mt-3 fw-bold">Konsultasi</h5>
                <p>Konsultasikan kebutuhan properti Anda dengan tim profesional kami.</p>
              </div>
            </div>
          </div>

          <!-- Card 3 -->
          <div class="col-md-4">
            <div class="card h-100 shadow-sm">
              <div class="card-body">
                <i class="bi bi-cash-stack display-4 text-primary"></i>
                <h5 class="mt-3 fw-bold">Investasi</h5>
                <p>Solusi investasi properti terpercaya dengan keuntungan jangka panjang.</p>
              </div>
            </div>
          </div>

          <!-- Card 4 -->
          <div class="col-md-4">
            <div class="card h-100 shadow-sm">
              <div class="card-body">
                <i class="bi bi-house-heart display-4 text-primary"></i>
                <h5 class="mt-3 fw-bold">Manajemen Properti</h5>
                <p>Kami membantu mengelola aset properti Anda agar tetap terawat dan produktif.</p>
              </div>
            </div>
          </div>

          <!-- Card 5 -->
          <div class="col-md-4">
            <div class="card h-100 shadow-sm">
              <div class="card-body">
                <i class="bi bi-briefcase display-4 text-primary"></i>
                <h5 class="mt-3 fw-bold">Kemitraan Bisnis</h5>
                <p>Membuka peluang kerjasama dengan investor dan mitra strategis di bidang properti.</p>
              </div>
            </div>
          </div>

          <!-- Card 6 -->
          <div class="col-md-4">
            <div class="card h-100 shadow-sm">
              <div class="card-body">
                <i class="bi bi-globe2 display-4 text-primary"></i>
                <h5 class="mt-3 fw-bold">Riset & Inovasi</h5>
                <p>Menghadirkan solusi properti berbasis teknologi modern dan ramah lingkungan.</p>
              </div>
            </div>
          </div>

        </div>
      </div>
    </section>
<hr>
    <!-- PROJECTS -->
    <section id="projects" class="py-5 bg-light">
      <div class="container text-center">
        <h2 class="fw-bold mb-5">Proyek Kami</h2>

        <div id="projectsCarousel" class="carousel slide" data-bs-ride="carousel">
          <div class="carousel-inner p-4">

            <!-- Slide 1 -->
            <div class="carousel-item active">
              <div class="row g-4">
                <div class="col-md-4">
                  <div class="project-card">
                    <img src="/project1.jpg" class="img-fluid" alt="Proyek 1">
                    <div class="overlay">
                      <h5>Proyek 1</h5>
                      <p>Deskripsi singkat proyek ini...</p>
                    </div>
                  </div>
                </div>

                <div class="col-md-4">
                  <div class="project-card">
                    <img src="/project2.jpg" class="img-fluid" alt="Proyek 2">
                    <div class="overlay">
                      <h5>Proyek 2</h5>
                      <p>Deskripsi singkat proyek ini...</p>
                    </div>
                  </div>
                </div>

                <div class="col-md-4">
                  <div class="project-card">
                    <img src="/project3.jpg" class="img-fluid" alt="Proyek 3">
                    <div class="overlay">
                      <h5>Proyek 3</h5>
                      <p>Deskripsi singkat proyek ini...</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <!-- Slide 2 -->
            <div class="carousel-item">
              <div class="row g-4">
                <div class="col-md-4">
                  <div class="project-card">
                    <img src="/project1.jpg" class="img-fluid" alt="Proyek 4">
                    <div class="overlay">
                      <h5>Proyek 4</h5>
                      <p>Deskripsi proyek lainnya...</p>
                    </div>
                  </div>
                </div>

                <div class="col-md-4">
                  <div class="project-card">
                    <img src="/project2.jpg" class="img-fluid" alt="Proyek 5">
                    <div class="overlay">
                      <h5>Proyek 5</h5>
                      <p>Deskripsi proyek lainnya...</p>
                    </div>
                  </div>
                </div>

                <div class="col-md-4">
                  <div class="project-card">
                    <img src="/project3.jpg" class="img-fluid" alt="Proyek 6">
                    <div class="overlay">
                      <h5>Proyek 6</h5>
                      <p>Deskripsi proyek lainnya...</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- Control Button -->
          <button class="carousel-control-prev" type="button" data-bs-target="#projectsCarousel" data-bs-slide="prev">
            <span class="carousel-control-prev-icon"></span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#projectsCarousel" data-bs-slide="next">
            <span class="carousel-control-next-icon"></span>
          </button>

          <!-- Indicator -->
          <div class="carousel-indicators">
            <button type="button" data-bs-target="#projectsCarousel" data-bs-slide-to="0" class="active"></button>
            <button type="button" data-bs-target="#projectsCarousel" data-bs-slide-to="1"></button>
          </div>
        </div>
      </div>
    </section>
<hr>
    <!-- TEAM -->
    <section id="team" class="py-5 bg-light">
      <div class="container text-center">
        <h2 class="fw-bold mb-5">Tim Kami</h2>
        <div class="row g-4">
          <div class="col-md-3 col-sm-6" v-for="i in 4" :key="i">
            <div class="card border-0 shadow-lg h-100 team-card">
              <div class="position-relative">
                <img :src="'https://randomuser.me/api/portraits/men/' + (30+i) + '.jpg'" class="rounded-circle mx-auto d-block mt-4 team-img" alt="team">
                <div class="overlay">
                  <a href="#" class="btn btn-primary btn-sm rounded-circle"><i class="bi bi-facebook"></i></a>
                  <a href="#" class="btn btn-info btn-sm rounded-circle"><i class="bi bi-twitter"></i></a>
                  <a href="#" class="btn btn-danger btn-sm rounded-circle"><i class="bi bi-instagram"></i></a>
                </div>
              </div>
              <div class="card-body">
                <h5 class="fw-bold">Nama {{ i }}</h5>
                <p class="text-muted">Posisi</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
<hr>
    <!-- TESTIMONIAL -->
    <section id="testimonials" class="py-5 bg-light">
      <div class="container text-center">
        <h2 class="fw-bold mb-5">Testimoni</h2>

        <div class="position-relative">
          <!-- Wrapper -->
          <div class="overflow-hidden p-3">
            <div class="d-flex testimonial-track" id="testimonialTrack">
              <!-- 12 Card -->
              <div class="card p-3 mx-2 shadow-sm" style="min-width: 300px;">
                <p>"Pelayanan PropertiKu sangat memuaskan, proses cepat dan profesional."</p>
                <h6 class="fw-bold mt-2">Klien 1</h6>
              </div>
              <div class="card p-3 mx-2 shadow-sm" style="min-width: 300px;">
                <p>"PropertiKu membantu saya menemukan hunian impian dengan harga terbaik."</p>
                <h6 class="fw-bold mt-2">Klien 2</h6>
              </div>
              <div class="card p-3 mx-2 shadow-sm" style="min-width: 300px;">
                <p>"Tim yang sangat profesional dan komunikatif. Sangat direkomendasikan!"</p>
                <h6 class="fw-bold mt-2">Klien 3</h6>
              </div>
              <div class="card p-3 mx-2 shadow-sm" style="min-width: 300px;">
                <p>"Proses transaksi berjalan lancar, semua transparan dan jelas."</p>
                <h6 class="fw-bold mt-2">Klien 4</h6>
              </div>
              <div class="card p-3 mx-2 shadow-sm" style="min-width: 300px;">
                <p>"Hunian yang saya beli kualitasnya premium sesuai dengan janji PropertiKu."</p>
                <h6 class="fw-bold mt-2">Klien 5</h6>
              </div>
              <div class="card p-3 mx-2 shadow-sm" style="min-width: 300px;">
                <p>"Layanan konsultasi sangat membantu untuk perencanaan investasi saya."</p>
                <h6 class="fw-bold mt-2">Klien 6</h6>
              </div>
              <div class="card p-3 mx-2 shadow-sm" style="min-width: 300px;">
                <p>"PropertiKu selalu memberikan solusi terbaik sesuai kebutuhan keluarga."</p>
                <h6 class="fw-bold mt-2">Klien 7</h6>
              </div>
              <div class="card p-3 mx-2 shadow-sm" style="min-width: 300px;">
                <p>"Tim marketing ramah dan fast response, membuat proses lebih nyaman."</p>
                <h6 class="fw-bold mt-2">Klien 8</h6>
              </div>
              <div class="card p-3 mx-2 shadow-sm" style="min-width: 300px;">
                <p>"Sangat puas dengan hasil akhir rumah saya, sesuai ekspektasi."</p>
                <h6 class="fw-bold mt-2">Klien 9</h6>
              </div>
              <div class="card p-3 mx-2 shadow-sm" style="min-width: 300px;">
                <p>"Proses cepat dan aman, semua dokumen diurus dengan baik."</p>
                <h6 class="fw-bold mt-2">Klien 10</h6>
              </div>
              <div class="card p-3 mx-2 shadow-sm" style="min-width: 300px;">
                <p>"Investasi saya berkembang pesat berkat PropertiKu."</p>
                <h6 class="fw-bold mt-2">Klien 11</h6>
              </div>
              <div class="card p-3 mx-2 shadow-sm" style="min-width: 300px;">
                <p>"Layanan after-sales luar biasa, tetap dibantu meskipun transaksi selesai."</p>
                <h6 class="fw-bold mt-2">Klien 12</h6>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
<hr>
    <!-- FAQ -->
    <section id="faq" class="py-5">
      <div class="container">
        <h2 class="fw-bold text-center mb-5">Pertanyaan Umum</h2>
        <div class="accordion shadow-sm rounded" id="faqAccordion">
          <div class="accordion-item" v-for="(q, i) in faqList" :key="i">
            <h2 class="accordion-header">
              <button 
                class="accordion-button collapsed fw-semibold" 
                type="button" 
                data-bs-toggle="collapse" 
                :data-bs-target="'#faq'+i">
                {{ q.question }}
              </button>
            </h2>
            <div :id="'faq'+i" class="accordion-collapse collapse" data-bs-parent="#faqAccordion">
              <div class="accordion-body">{{ q.answer }}</div>
            </div>
          </div>
        </div>
      </div>
    </section>
<hr>
    <!-- CONTACT -->
    <section id="contact" class="py-5 bg-light">
      <div class="container">
        <h2 class="fw-bold text-center mb-4">Hubungi Kami</h2>
        <p class="text-center text-muted mb-5">Ada pertanyaan atau butuh bantuan? Silakan kirim pesan kepada kami.</p>
        
        <div class="row justify-content-center">
          <div class="col-lg-8">
            <div class="card shadow-lg border-0 rounded-4">
              <div class="card-body p-4 p-md-5">
                <form class="row g-4">
                  <div class="col-md-6">
                    <div class="input-group">
                      <span class="input-group-text bg-primary text-white"><i class="bi bi-person"></i></span>
                      <input type="text" class="form-control" placeholder="Nama Anda">
                    </div>
                  </div>
                  <div class="col-md-6">
                    <div class="input-group">
                      <span class="input-group-text bg-primary text-white"><i class="bi bi-envelope"></i></span>
                      <input type="email" class="form-control" placeholder="Email Anda">
                    </div>
                  </div>
                  <div class="col-12">
                    <div class="input-group">
                      <span class="input-group-text bg-primary text-white"><i class="bi bi-chat-text"></i></span>
                      <textarea class="form-control" rows="5" placeholder="Pesan Anda"></textarea>
                    </div>
                  </div>
                  <div class="col-12 text-center">
                    <button class="btn btn-primary btn-lg px-5 shadow-sm">
                      <i class="bi bi-send"></i> Kirim Pesan
                    </button>
                  </div>
                </form>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

  </div>
</template>

<script setup>
import { ref } from "vue";

const faqList = ref([
  {
    question: "Apa itu PropertiKu?",
    answer: "PropertiKu adalah perusahaan properti yang fokus pada hunian modern dan investasi bernilai tinggi, memberikan layanan profesional untuk klien individu maupun korporasi."
  },
  {
    question: "Apakah PropertiKu hanya menjual rumah?",
    answer: "Tidak. Kami menyediakan berbagai jenis properti seperti rumah, apartemen, ruko, hingga lahan investasi."
  },
  {
    question: "Bagaimana cara membeli properti melalui PropertiKu?",
    answer: "Cukup hubungi tim sales kami, lakukan konsultasi kebutuhan Anda, lalu kami akan membantu dari proses pemilihan hingga transaksi selesai."
  },
  {
    question: "Apakah tersedia layanan KPR?",
    answer: "Ya, kami bekerja sama dengan berbagai bank nasional untuk menyediakan layanan KPR dengan bunga kompetitif."
  },
  {
    question: "Apakah PropertiKu menyediakan layanan investasi?",
    answer: "Benar. Kami memberikan rekomendasi properti dengan nilai investasi tinggi serta analisis keuntungan jangka panjang."
  },
  {
    question: "Bagaimana cara mengikuti promo yang sedang berjalan?",
    answer: "Promo dan penawaran spesial dapat dilihat pada halaman proyek kami atau melalui newsletter dan media sosial PropertiKu."
  },
  {
    question: "Apakah PropertiKu memiliki layanan manajemen properti?",
    answer: "Ya, kami menyediakan jasa pengelolaan properti seperti penyewaan, perawatan, hingga administrasi dokumen legal."
  },
  {
    question: "Bagaimana saya bisa menghubungi tim PropertiKu?",
    answer: "Anda bisa menghubungi kami melalui halaman Kontak di website, email resmi, atau nomor telepon yang tersedia di footer website."
  }
]);
document.addEventListener("DOMContentLoaded", function () {
  const track = document.getElementById("testimonialTrack");
  const prevBtn = document.getElementById("prevBtn");
  const nextBtn = document.getElementById("nextBtn");

  let scrollAmount = 0;

  prevBtn.addEventListener("click", () => {
    track.scrollBy({ left: -300, behavior: "smooth" });
  });

  nextBtn.addEventListener("click", () => {
    track.scrollBy({ left: 300, behavior: "smooth" });
  });
});
</script>

<style scoped>
.hero {
  min-height: 90vh;
  background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)),
              url("https://images.unsplash.com/photo-1505691723518-36a5ac3be353?auto=format&fit=crop&w=1350&q=80")
              center/cover no-repeat;
}

.testimonial-track {
  display: flex;
  gap: 1rem;
  animation: scroll 20s linear infinite;
}

@keyframes scroll {
  from {
    transform: translateX(0);
  }
  to {
    transform: translateX(-50%);
  }
}

.card {
  transition: transform 0.3s;
  cursor: pointer;
}
.card:hover {
  transform: translateY(-5px);
}
#faq {
  background: linear-gradient(135deg, #f8f9fa, #ffffff);
}
.accordion-button {
  background: #fff;
  border: none;
  box-shadow: none;
  transition: all 0.3s ease;
}
.accordion-button:not(.collapsed) {
  color: #0d6efd;
  background: #e9f0ff;
  font-weight: 600;
}
.accordion-button:hover {
  background: #f1f5ff;
}
.accordion-body {
  background: #fff;
  border-left: 3px solid #0d6efd;
}
  #contact h2 {
    color: #0d6efd;
  }
  #contact .form-control:focus {
    border-color: #0d6efd;
    box-shadow: 0 0 6px rgba(13, 110, 253, 0.4);
  }
  #contact .btn-primary:hover {
    background-color: #084298;
    transform: scale(1.05);
    transition: 0.3s;
  }
  .team-img {
    width: 150px;
    height: 150px;
    object-fit: cover;
    border: 5px solid #fff;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    transition: transform 0.3s ease;
  }
  .team-card:hover .team-img {
    transform: scale(1.05);
  }
  .overlay {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    opacity: 0;
    transition: opacity 0.4s ease;
    display: flex;
    gap: 10px;
  }
  .team-card:hover .overlay {
    opacity: 1;
  }
  .overlay a {
    width: 35px;
    height: 35px;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .project-card {
    position: relative;
    border-radius: 15px;
    overflow: hidden;
    box-shadow: 0 5px 15px rgba(0,0,0,0.2);
    transition: transform 0.3s ease-in-out;
  }

  .project-card:hover {
    transform: translateY(-5px);
  }

  .project-card img {
    width: 100%;
    height: 250px;
    object-fit: cover;
    cursor: pointer;
  }

  .project-card .overlay {
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    padding: 20px;
    background: linear-gradient(to top, rgba(0,0,0,0.8), transparent);
    color: #fff;
    text-align: left;
  }

  .project-card .overlay h5 {
    font-weight: bold;
    margin-bottom: 5px;
  }

  .carousel-control-prev-icon,
  .carousel-control-next-icon {
    background-size: 100% 100%;
    filter: invert(1);
  }

  .carousel-indicators button {
    background-color: #007bff;
  }
</style>