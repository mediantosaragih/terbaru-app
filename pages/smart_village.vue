<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-md-12">
        <h1 style="text-align: center;margin-top: 40px;padding: 70px;color: #737373;">
          LITERASIA SMART VILLAGE
        </h1>
      </div>
      <div class="col-md-7" style="padding-left: 200px; text-align: justify">
        <h4 style="color: #737373">
          Literasia Smart Village adalah sebuah aplikasi perpustakaan digital dan administrasi digitalisasi desa dimana manfaat aplikasi ini sangat membantu administrasi desa dengan digitalisasi dan meningkatkan minat baca masyarakat dengan adanya perpustakaan digital.
        </h4>
      </div>
      <div class="col-md-5">
        <img
          src="../assets/img/smartvillage.png"
          alt="Logo"
          style="width: 400px; height: 300px"
        />
      </div>
      <div class="col-md-12">
        <h1 style="text-align: center;margin-top: 40px;padding: 70px;color: #737373;">
          FITUR LITERASIA SMART VILLAGE
        </h1>
      </div>
    </div>
    <div class="row" style="margin-top: 100px">
        <nuxt-link to = "/perpustakaan">
          <img
          src="../assets/img/perpustakaan.png"
          title="Perpustakaan Digital"
          style="width: 400px; height: 300px">
        </nuxt-link>
        <nuxt-link to = "/administrasi">
          <img
          src="../assets/img/administrasi.jpg"
          title="Administrasi Digitalisasi Desa"
          style="width: 400px; height: 300px">
        </nuxt-link>
        <nuxt-link to = "/informasi">
          <img
          src="../assets/img/informasi.png"
          title="Informasi dan Komunikasi Desa"
          style="width: 400px; height: 300px">
        </nuxt-link>
    </div>
  </div>
</template>

<script></script>

<style>
.navbar {
  margin-top: 10px;
}
main {
  background-color: red;
}
body {
  background-image: url("../assets/img/bg-1.jpg");
  background-size: 100%;
  background-repeat: repeat-x;
}
</style>
