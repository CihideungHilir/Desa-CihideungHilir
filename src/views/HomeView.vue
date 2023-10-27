<script setup>
import Header from "../components/Header.vue";
import Banner from "../components/Banner.vue";
import Sidebar from "../components/Sidebar.vue";
</script>

<template>
  <Header />
  <Banner />

  <main class="flex">
    <Sidebar />

    <div class="flex-1 p-10">
      <p class="text-3xl font-semibold">Visi & Misi Desa</p>
      <p class="text-lg font-semibold">Visi</p>
      <p>
        1. Peningkatan Pemberdayaan Pemuda Melalui Penguatan Lembaga Karang Taruna
        2. Peningkatan Ekonomi Masyarakat Melalui Inovasi Desa dan Penguatan Kegiatan PKK dan UMKM
      </p>
      <p class="text-lg font-semibold">Misi</p>
      <ul>
        <li>
          1. Peningkatan Mental dan Akhlak Melalui MUI Desa
        </li>
        <li>
          2. Peningkatan Program Pendidikan dan Kesehatan
        </li>
        <li>
        </li>
      </ul>
    </div>
  </main>
</template>

<style>
body {
  background: #f1f1f1;
}
</style>
