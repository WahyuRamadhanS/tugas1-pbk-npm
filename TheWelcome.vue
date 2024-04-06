<script setup>
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
    <template #heading>Biodata</template>
    hallo perkenalkan saya
    <a>Wahyu Ramadhan.S</a>. Saya lahir di Pekanbaru, sedari kecil sudah besar di Pekanbaru. Saya
    Mahasiswa UIR angkatan 22. Saya seorang mahasiswa Teknik Informatika yang dimana sekarang sudah
    semester 4.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pendidikan</template>
    Pendidikan saya SMA berada pada SMAS Muhammadiyah 1 Pekanbaru dari 2019-2022. sampai saat ini
    saya masih melanjutkan pendidikan pada universitas UIR, sebagai seorang mahasiswa Teknik
    Informatika.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Pengalaman</template>
    Saya pernah menjadi panitia pada sebuah acara yang di selenggarakan himpunan mahasiswa Teknik
    Informatika (Himatif), yaitu seperti menjadi panitia divisi acara pada TI funday, panitia
    sporsorship TI Milad, dan sekarang saya menjadi salah satu anggota himatif uir sebagai anggota
    divisi Kominfo.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Organisasi</template>

    <a>IPM</a>awalan saya memasuki oraganisasi ialah IPM, IPM itu sendiri ialah Ikatan pelajar
    muhammadiyah. Saya memasuki IPM ini ketika saya berada di bangku Sma, selanjutnya saya memasuki
    <a>Himatif</a> saya memasuki Himatif sendiri karena saya merasa bergabung dalam himpunan bisa
    membuat saya lebih baik.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>FOllowing me</template>
    Bisa mengikuti saya disini :
    <br />
    <img
      src="file:///C:/Users/LENOVO/Downloads/pngwing.com.png"
      width="25px"
      height="25px"
      style="vertical-align: middle"
    />,
    <a href="https://www.instagram.com/wagyuuu_/" target="_blank" rel="noopener">wagyuuu_ . </a>
    <img
      src="file:///C:/Users/LENOVO/Downloads/pngwing.com%20(1).png"
      width="25px"
      height="25px"
      style="vertical-align: middle"
    />, <a>081218182212 . </a>
    <br />
    <img
      src="file:///C:/Users/LENOVO/Downloads/pngwing.com%20(2).png"
      width="25px"
      height="25px"
      style="vertical-align: middle"
    />, <a>wahyuramadhan.s31@student.uir.ac.id . </a>
  </WelcomeItem>
</template>
