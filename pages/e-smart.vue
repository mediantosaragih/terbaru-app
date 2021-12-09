<template>
<div>
  <Navbar />
  <div class="container-fluid">
    <div class="row">
      <div class="col-md-12">
        <h1 style="text-align: center;margin-top: 40px;padding: 70px;color: #737373;">
          LITERASIA E-SMART
        </h1>
      </div>
      <div class="col-md-7" style="padding-left: 200px; text-align: justify">
        <h4 style="color: #737373">
          Literasia E-Smart adalah salah satu produk dari PT.Literasia Edutekno Digital.
          Literasia merupakan Perpustakaan Digital dan Media Pembelajaran Digital,
          dimana sebuah aplikasi yang dapat meningkatkan minat baca dan membantu mempermudah proses
          belajar mengajar di sekolah mulai dari jenjang SD, SMP, SMA sampai perguruan tinggi.
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
          FITUR LITERASIA E-Smart
        </h1>
      </div>
    </div>
    <div class="row" style="margin-top: 20px">
        <nuxt-link to = "/perpustakaan">
          <img
          src="../assets/img/perpustakaan.png"
          title="Media Perpustakaan Digital"
          style="width: 200px; height: 200px; margin-left: 200px">
        </nuxt-link>
        <nuxt-link to = "/pembelajaran_digital">
          <img
          src="../assets/img/pembelajaran_digital.jpg"
          title="Media Pembelajaran Digital"
          style="width: 200px; height: 200px; margin-left: 200px">
        </nuxt-link>
        <nuxt-link to = "/manajemen_sekolah">
          <img
          src="../assets/img/manajemensekolah.jpg"
          title="Sistem Manajemen Sekolah"
          style="width: 200px; height: 200px; margin-left: 200px">
        </nuxt-link>
    </div>
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
