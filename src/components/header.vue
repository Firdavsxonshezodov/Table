<template>
  <div class="card">
    <!-- Image and text -->
    <nav class="navbar navbar-light bg-secondary">
      <router-link to="/">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">
          <!-- src="https://mdbcdn.b-cdn.net/img/logo/mdb-transaprent-noshadows.webp" -->
          <img
            src="../../image/photo_2023-10-29_00-30-09 (1).png"
            class="me-2"
            height="50"
            alt="MDB Logo"
            loading="lazy"
          />

          <small class="smal" style="color: #ffffff">Turon IT academy</small>
        </a>
      </div>
    </router-link>

    <form class="d-flex input-group w-auto">
      <input
        type="search"
        class="form-control rounded-5"
        placeholder="Search"
        aria-label="Search"
        aria-describedby="search-addon"
        :v-model="input1"
      />
      <span class="input-group-text border-0" id="search-addon">
        <i class="fas fa-search text-white fs-5"></i>
      </span>
    </form> 
    </nav>
  </div>
</template>

<script setup>

</script>

<style scoped>
.smal {
  font-weight: 600 !important;
  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
}
</style>
