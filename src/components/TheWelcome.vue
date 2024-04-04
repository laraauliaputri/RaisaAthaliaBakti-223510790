<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Tentang</template>
    Perkenalkan saya Raisa, saya dilahirkan di Bangkinang, sebuah kota kecil yang terletak di Riau, Indonesia, pada tanggal 09 April 2004. Sekarang saya tinggal di Jalan Arifin Ahmad Pekanbaru Dan Berkuliah di Universitas Islam Riau prodi Teknik Informatika
</WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pendidikan</template>
    <li>TK Aisyah</li>
      <li><a href="https://dapo.kemdikbud.go.id/sekolah/C99C9805F75009DD8B63" target="_blank" rel="noopener">SDN Muhammadiyah</a></li>
      <li><a href="https://dapo.kemdikbud.go.id/sekolah/B7ED95A3C0B2E288319F" target="_blank" rel="noopener">SMPN 1 Bangkinang kota</a></li>
      <li><a href="https://sman1bangkinangkota.sch.id/" target="_blank" rel="noopener">SMAN 1 Bangkinang Kota</a></li>
      <li><a href="https://uir.ac.id/" target="_blank" rel="noopener">Universitas Islam Riau</a></li>

  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Hobi</template>
    <ul>
      <li>Badminton</li>
      <li>Olahraga</li>
      <li>Jogging</li>
    </ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Pengalaman & skill</template>
    Saya memiliki pengalaman dan soft skill:
    <ul>
    <li>Anggota Paskibraka</li>
      <li>Anggota pik-r</li>
      <li>Badminton</li>
      <li>Web developer</li>
      <li>mengikuti seminar Cyber Security</li>
</ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Sosial Media</template>
Saya hanya aktif di satu Social Media yaitu Instagram, disana saya mencari informasi serta mengupdate kegiatan sehari-hari saya ataupun momen bersama teman. Instagram
   :<a href="https://www.instagram.com/raisa_athaliaa" target="_blank">raisa_athaliaa</a>
  </WelcomeItem>
</template>