<template>
  <!-- Navbar-->
  <nav class="navbar navbar-expand-lg navbar-light shadow-sm mb-3" style="background-color: #57f0d9">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">
        <img src="../components/Logo_Quran-removebg-preview.png" alt="" width="30" height="24" class="d-inline-block align-text-top" />
        Al-Qur'an Digital
      </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <router-link :to="{ name: 'page.home' }" class="nav-link" href="#Home">Home Qur'an</router-link>
          </li>
          <li class="nav-item">
            <router-link :to="{ name: 'page.about' }" class="nav-link active" aria-current="page" href="#about">About Qur'an</router-link>
          </li>
          <li class="nav-item">
            <router-link :to="{ name: 'page.contact' }" class="nav-link" href="#contact">Contact Author</router-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <!-- Akhir Navbar-->

  <!-- Jumbotron-->
  <section class="jumbotron text-center mb-5  p-3" style="">
    <img src="../components/Logo_Quran-removebg-preview.png" alt="Logo Quran" width="200" class="rounded-circle img-thumbnail" />
    <h1 class="display-4">Al-Qur'an</h1>
    <hr>
  </section>
  <!-- Akhir Jumbotron-->

  <!-- About-->
  <section id="about">
    <div class="container">
      <div class="row text-center mt-5">
        <div class="col">
          <h2 class="display-7">About Qur'an</h2>
        </div>
      </div>
      <div class="col justify-content-center fs-5 text-center">
        <div class=" fs-6">
          <p>“Al-Qur'an ini di buat secara digital agar mempermudah audiens jika di saat tidak membawa Al-Qur'an, jadi audiens tinggal menggunakan Al-Qur'an digital berbasis website. Adapun maksud kenapa Al-Qur'an ini di buat atas pengalaman author sendiri yang mana merasakan di saat dalam perjalanan lupa membawa Al-Qur'an.”</p>
        </div>


      </div>
    </div>
  </section>
  <!-- Akhir About-->



  <!-- Footer -->
  <footer class="text-dark text-center fixed-bottom " style="background-color: #57f0d9">
    <p>Created by <a href="https://www.instagram.com/m.rival_kurniawan/" class="text-dark fw-bold">M. Rival Kurniawan</a></p>
  </footer>
  <!-- Akhir Footer -->
</template>

<script>
export default {};
</script>