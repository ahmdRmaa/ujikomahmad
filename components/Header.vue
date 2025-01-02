<template>
  <div>

    <nav class="navbar navbar-expland-lg bg-primary navbar-dark" style="margin-bottom: 40px;">
      <div class="container">

        <img src="~/assets/LOGO-SMK4.png" alt="logo sekolah" widht="30" height="35" class="me-2">
        <div style="color: white">SMKN4 TASIKMALAYA</div>

        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarNaw">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item">
              <nuxt-link class="nav-link" to="./">BERANDA</nuxtlink>
              </li>
            <li class="nav-item">
              <nuxt-link class="nav-link" to="./">PROFIL</nuxtlink>
              </li>
            <li class="nav-item">
              <nuxt-link class="nav-link" to="./">JURUSAN</nuxtlink>
              </li>
            </ul>
          </div>
        </div>
      </nav>

      <nuxt />
    </div>
    </template>

    <script>
    export default {
      name: 'Defaultlayout'
    }
  </script>

  <style scoped>

  .navbar{
    padding : 10px 15px;
  }
  .navbar-brand img {
    max-height: 35px;
  }
  </style>