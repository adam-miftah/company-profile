<template>
  <div class="container py-5">
    <div class="text-center mb-5" data-aos="fade-up">
      <h2 class="fw-bold">Proyek Kami</h2>
      <p class="text-muted">Beberapa proyek unggulan yang telah kami kerjakan, mencerminkan komitmen kami dalam menghadirkan hunian modern dan investasi bernilai tinggi.</p>
    </div>

    <div class="row g-4">
      <div class="col-md-4" v-for="(project, index) in projects" :key="index">
        <div class="card shadow-sm h-100">
          <img :src="project.image" class="card-img-top fixed-img" alt="project image" />
          <div class="card-body text-center">
            <h5 class="fw-bold">{{ project.title }}</h5>
            <p class="text-muted">{{ project.description }}</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script setup>
const projects = [
  {
    image: '/project1.jpg',
    title: 'Perumahan Green Valley',
    description: 'Hunian modern dengan lingkungan hijau yang asri dan nyaman.'
  },
  {
    image: '/project2.jpg',
    title: 'Apartemen Skyline',
    description: 'Apartemen mewah dengan pemandangan kota metropolitan.'
  },
  {
    image: '/project3.jpg',
    title: 'Villa Ocean View',
    description: 'Villa eksklusif dengan panorama laut yang menakjubkan.'
  }
]
</script>

<style scoped>
.project-card {
  border-radius: 15px;
  overflow: hidden;
  transition: transform 0.3s ease-in-out;
}
.project-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 8px 20px rgba(0,0,0,0.15);
}
.project-img-wrapper {
  position: relative;
  overflow: hidden;
}
.project-img-wrapper img {
  transition: transform 0.4s ease;
}
.project-img-wrapper:hover img {
  transform: scale(1.1);
}
.overlay {
  position: absolute;
  inset: 0;
  background: rgba(0,0,0,0.5);
  opacity: 0;
  transition: opacity 0.4s ease;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 20px;
}
.project-img-wrapper:hover .overlay {
  opacity: 1;
}
.fixed-img {
  height: 220px;      /* atur sesuai kebutuhan */
  object-fit: cover;  /* biar proporsional */
  border-top-left-radius: 12px;
  border-top-right-radius: 12px;
}
</style>
