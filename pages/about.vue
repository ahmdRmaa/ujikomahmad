<template>
  <div class="about">
    <h1>ekstrakulikuler</h1>
    <p>Ini adalah halaman yang berisi informasi tentang ektrakulikuler yang ada di smk negeri 4.</p>
    <nuxt-link to="/">Kembali ke Beranda</nuxt-link>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: 'Tentang Sekolah - Website Sekolah'
    };
  }
};
</script>

<style scoped>
.about {
  text-align: center;
  margin-top: 50px;
}
</style>
