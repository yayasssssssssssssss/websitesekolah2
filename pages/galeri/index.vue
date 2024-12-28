<template>
    <div class="container py-4">
      <h2 class="text-center mb-4">Galeri Sekolah</h2>
      <div class="row g-3">
        <!-- Kartu Galeri 1 -->
        <div class="col-6 col-md-4" data-bs-toggle="modal" data-bs-target="#lightbox1">
          <div class="card">
            <img src="~assets/img/guru.jpeg" class="card-img-top" alt="Kegiatan 1" />
            <div class="card-body text-center">
              <p class="card-text">Upacara Hari Guru</p>
            </div>
          </div>
        </div>
        
        <!-- Kartu Galeri 2 -->
        <div class="col-6 col-md-4" data-bs-toggle="modal" data-bs-target="#lightbox2">
          <div class="card">
            <img src="~assets/img/guru.jpeg" class="card-img-top" alt="Prestasi 1" />
            <div class="card-body text-center">
              <p class="card-text">Upacara Hari Guru</p>
            </div>
          </div>
        </div>
        
        <!-- Kartu Galeri 3 -->
        <div class="col-6 col-md-4" data-bs-toggle="modal" data-bs-target="#lightbox3">
          <div class="card">
            <img src="~assets/img/guru.jpeg" class="card-img-top" alt="Fasilitas Baru" />
            <div class="card-body text-center">
              <p class="card-text">Fasilitas Baru</p>
            </div>
          </div>
        </div>
      </div>
  
      <!-- Modal Galeri 1 -->
      <div class="modal fade" id="lightbox1" tabindex="-1" aria-hidden="true">
        <div class="modal-dialog modal-dialog-centered">
          <div class="modal-content">
            <div class="modal-body">
              <img src="~assets/img/guru.jpeg" class="img-fluid" alt="Kegiatan 1" />
              <p class="mt-2 text-center">Kegiatan 1</p>
            </div>
          </div>
        </div>
      </div>
  
      <!-- Modal Galeri 2 -->
      <div class="modal fade" id="lightbox2" tabindex="-1" aria-hidden="true">
        <div class="modal-dialog modal-dialog-centered">
          <div class="modal-content">
            <div class="modal-body">
              <img src="~assets/img/guru.jpeg" class="img-fluid" alt="Prestasi 1" />
              <p class="mt-2 text-center">Prestasi 1</p>
            </div>
          </div>
        </div>
      </div>
  
      <!-- Modal Galeri 3 -->
      <div class="modal fade" id="lightbox3" tabindex="-1" aria-hidden="true">
        <div class="modal-dialog modal-dialog-centered">
          <div class="modal-content">
            <div class="modal-body">
              <img src="~assets/img/guru.jpeg" class="img-fluid" alt="Fasilitas Baru" />
              <p class="mt-2 text-center">Fasilitas Baru</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: "Gallery",
  };
  </script>
  
  <style scoped>
  .card-img-top {
    transition: transform 0.3s;
  }
  
  .card-img-top:hover {
    transform: scale(1.05);
  }
  </style>