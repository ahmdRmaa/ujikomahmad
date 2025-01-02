<template>
    <header class="bg-blue-600 text-white py-4">
      <div class="container mx-auto flex justify-between items-center">
        <h1 class="text-3xl font-bold">Website SMK NEGERI 4 TASIKMALAYA</h1>
        <img src="~/assets/LOGO-SMK4.png" alt="logo sekolah" widht="90" height="70" class="me-2">
        <div style="color: black">SMK NEGERI 4 TASIKMALAYA</div>
        <nav>
          <nuxt-link to="/" class="mx-10">Home</nuxt-link>

          <nuxt-link to="/contact" class="mr-20">Jurusan</nuxt-link>

          <nuxt-link to="/about" class="mr-30">Ekstrakulikuler</nuxt-link>

          <nuxt-link to="/galeri" class="mx-40">galeri</nuxt-link>
        </nav>
      </div>
    </header>

    <div class="contact">
    <h1>Kontak Kami</h1>
    <p>Email: info@smkn4-tsm.sch.id </p>
    <p>Telepon: +62265312059 </p>
    </div>

    <div>
    <header class="bg-blue-600 text-white py-4">
      <div class="container mx-auto text-center">
        <img src="~/assets/kepsek.png" alt="logo sekolah" widht="400" height="400" class="me-2">
        <h1 class="text-3xl font-bold">Sambutan Kepala Sekolah</h1>
      </div>
    </header>

    <main class="py-10 container mx-auto">
      <section class="bg-gray-100 p-6 rounded shadow-lg">
        <h2 class="text-2xl font-semibold mb-3">Salam Hangat</h2>
        <p class="text-lg">
          Assalamu'alaikum Warahmatullahi Wabarakatuh, <br><br>
          Selamat datang di website resmi sekolah kami. Kami berkomitmen untuk memberikan
          pendidikan terbaik kepada siswa-siswi kami, serta menyediakan lingkungan belajar
          yang nyaman dan mendukung.
        </p>
        <p class="mt-4">
          Kami percaya bahwa pendidikan adalah kunci kesuksesan, dan kami bangga menjadi
          bagian dari perjalanan pendidikan siswa-siswi kami. Semoga website ini menjadi
          jembatan informasi yang bermanfaat bagi orang tua, siswa, dan masyarakat luas.
        </p>
        <p class="mt-4 font-bold">Hormat kami,</p>
        <p class="mt-2 text-lg font-semibold">Kurniawan spd.mpd</p>
        <p>Kepala Sekolah</p>
      </section>
    </main>

  

    <main class="py-10 container mx-auto">
      <nuxt />
    </main>

    <footer class="bg-gray-800 text-white py-4">
      <div class="container mx-auto text-center">
        <p>&copy; 2025 Website Sekolah. Hak cipta dilindungi.</p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'DefaultLayout',
};
</script>