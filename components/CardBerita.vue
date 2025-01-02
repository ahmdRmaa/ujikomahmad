<template>
  <div class="max-w-sm mx-auto bg-white rounded-lg shadow-md">
    <img class="w-full h-48 object-cover" :src="gambar" :alt="judul">
    <div class="p-4">
      <h5 class="text-lg font-bold mb-2">{{ judul }}</h5>
      <p class="text-gray-600">{{ deskripsi }}</p>
      <NuxtLink :to="link" class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">Baca Selengkapnya</NuxtLink>
    </div>
  </div>
</template>


<script>
export default {
  props: {
    gambar: img
    judul: String,
    deskripsi: String,
    link: String,
  },
};
</script>