<template>
  <div class="home">
    <div class="container-fluid">
      <div class="row my-5">
        <div class="col-lg-6">

          <selection class="hero-selection text-center text-white py-5 ">
            <h1 class="display-4 mb-4">Selamat Datang Di Website Smkn4</h1>
            <p class="lead mb-4">Informasi Smkn4</p>
            <div class="container">
            </div>
          </selection>
              <nuxt-link to="/about">Tentang Sekolah</nuxt-link>
              <footer class="bg-gray-800 text-white py-4">
      <div class="container mx-auto text-center">
        <p>&copy; 2025 Website Sekolah. Hak cipta dilindungi.</p>
      </div>
    </footer>
            </div>
          </div>
        </div>
      </div>
    
</template>

<script>
export default {
  head() {
    return {
      title: 'Beranda - Website Sekolah'
    };
  }
};
</script>

<style scoped>
.home {
  text-align: center;
  margin-top: 50px;
}
</style>
