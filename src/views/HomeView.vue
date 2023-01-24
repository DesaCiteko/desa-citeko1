<script setup>
import Header from '../components/Header.vue'
import Banner from '../components/Banner.vue'
import Sidebar from '../components/Sidebar.vue'
</script>

<template>
  <Header/>
  <Banner/>
  <main class="flex">
    <Sidebar/>
    <div class="flex-1 p-10">


      <p class="text-3xl font-semibold">Visi & Misi Desa</p>
      <p>VISI</p>
      <p>Hadir lebih dekat Melayani Masyarakat untuk mewujudkannya Desa Citeko yang “ BERKAH “ dan sejahtera serta menjungjung tinggi nilai Budaya, Agama, Kesejahteraan Masyarakat dan Berakhlakul Karimah.</p>
      <p>Desa yang Bersih  (B)</p>
      <p>Desa yang Elok    (E)</p>
      <p>Desa yang Rukun   (R)</p>
      <p>Desa yang Kuat    (K)</p>
      <p>Desa yang Aman    (A)</p>
      <p>Desa yang Humanis (H)</p>
      <p>Yang selanjutnya dirumuskan dengan akronim “ B E R K A H “</p>
      <p>MISI</p>
      <p>1. Bekerjasama dengan Pemerintah Pusat,Provinsi dan Pemerintah Daerah dalam mewujudkan pembangunan fisik dan Non Fisik Desa Citeko</p>
      <p>2. Meningkatkan hasil produksi pertanian dan pariwisata sebagai sumber daya alam di Desa Citeko</p>
      <p>3. Melestarikan nilai seni budaya yang ada di Desa Citeko</p>
      <p>4. Meningkatkan kerukunan antar warga masyarakat serta membentuk masyarakat yang cerdas, mandiri dan berahlakul Karimah</p>
      <p>5. Memberikan rujukan terhadap kesejahteraan masyarakat dalam bidang pendidikan, kesehatan, keamanan dan kesejahteraan sosial</p>




      <p class="text-3xl font-semibold my-4">Struktur Desa</p>
      <img src="@/assets/struktur-desa-citeko.png" alt=""/>
    </div>
  </main>
</template>

<style>
  body{
    background: #f1f1f1;
  }
</style>
