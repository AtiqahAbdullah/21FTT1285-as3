<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>

<div class="card">
  <img src="img.jpeg" alt="Atiqah Abdullah">
  <div class="container">
    <h4><b>PROFILE</b></h4>
    <p>Name: Nur Atiqah Abdullah</p>
    <p>Course: Level 5 Diploma in Web Development</p>
    <p>GroupCode: DWDT07</p>
    <p>School: School of SICT</p>
  </div>
</div>

</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}

.card {
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  transition: 0.3s;
  border-radius: 5px; /* 5px rounded corners */
}

/* Add rounded corners to the top left and the top right corner of the image */
img {
  border-radius: 5px 5px 0 0;
  height: 10cm;
  width: 100%;
  
}

</style>
