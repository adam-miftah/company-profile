<template>
  <div class="container py-5">
    <!-- Judul Section -->
    <div class="text-center mb-5" data-aos="fade-up">
      <h2 class="fw-bold">Tim Kami</h2>
      <p class="text-muted">Dipimpin oleh profesional berpengalaman di industri properti.</p>
    </div>

    <!-- Card Team -->
    <div class="row g-4">
      <div 
        class="col-12 col-sm-6 col-md-4 col-lg-3" 
        v-for="(member, index) in team" 
        :key="member.id"
        :data-aos="'fade-up'" 
        :data-aos-delay="100 * (index+1)"
      >
        <div class="card border-0 shadow team-card h-100 text-center">
          <div class="image-wrapper mx-auto">
            <img :src="member.image" class="rounded-circle team-img" alt="Team Member" />
          </div>
          <div class="card-body">
            <h5 class="fw-bold mb-1">{{ member.name }}</h5>
            <p class="text-muted mb-0">{{ member.role }}</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      team: [
        { id: 1, name: 'Andi Setiawan', role: 'CEO', image: '/team1.jpg' },
        { id: 2, name: 'Budi Hartono', role: 'CTO', image: '/team2.jpg' },
        { id: 3, name: 'Citra Dewi', role: 'Marketing Manager', image: '/team3.jpg' },
        { id: 4, name: 'Dian Putri', role: 'Finance Manager', image: '/team4.jpg' }
      ]
    }
  }
}
</script>

<style scoped>
.team-card {
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  border-radius: 20px;
  padding-top: 20px;
}

.team-card:hover {
  transform: translateY(-8px);
  box-shadow: 0px 10px 20px rgba(0,0,0,0.15);
}

.image-wrapper {
  width: 150px;
  height: 150px;
  overflow: hidden;
  border-radius: 50%;
  margin-bottom: 15px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.15);
}

.team-img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  transition: transform 0.4s ease;
}

.team-card:hover .team-img {
  transform: scale(1.1);
}
</style>
