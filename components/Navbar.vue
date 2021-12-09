<template>
<div>
  <div class="heads">
    <b-navbar type="dark" variant="dark">
              <img
            src="../assets/img/logo.png"
            alt="Logo"
            style="width: 300px; height: 70px; padding:10px; margin-left:100px"
          />
      <b-navbar-nav style="margin-left:400px;">
        <b-nav-item-dropdown text="Produk" right>
          <b-dropdown-item to="/e-smart">Literasia E-Smart</b-dropdown-item>
          <b-dropdown-item href="/smart_village">Literasia Smart Village</b-dropdown-item>
          <b-dropdown-item href="e-pusda">Literasia E-Pusda</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item href="#">Hubungi Kami</b-nav-item>
        <b-nav-item href="#">Bantuan</b-nav-item>
        <b-nav-item href="#">Kantor Pemasaran</b-nav-item>
      </b-navbar-nav>
    </b-navbar>
  </div>
  <Nuxt />
  <div>

  </div>
</div>

</template>

<style>
.heads{
  list-style-type: none;
    background-color: rgb(206, 19, 97);
    top: 0;
    position: fixed;
    width: 100%;
    z-index: 1;
}
</style>
