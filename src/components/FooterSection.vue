<template>
  <div class="footer">
    <ul>
      <a href="https://twitter.com/pixelmorans" target="_blank"><font-awesome-icon icon="fa-brands fa-x-twitter" /></a>
      <a href="https://instagram.com/pixelmorans" target="_blank"><font-awesome-icon icon="fa-brands fa-instagram" /></a>
      <a href="https://t.me/pixelmorans" target="_blank"><font-awesome-icon icon="fa-brands fa-telegram" /></a>
      <a href="https://medium.com/@pixelmorans" target="_blank"><font-awesome-icon icon="fa-brands fa-medium" /></a>
      <a href="https://discord.gg/BZEqhguD2e" target="_blank"><font-awesome-icon icon="fa-brands fa-discord" /></a>
    </ul>
    <footer>
      &copy {{ year }}/ Pixel Morans Studios. All rights reserved.
    </footer>
  </div>
</template>

<script setup>
import { ref } from 'vue';

const year = ref(null);
year.value = new Date().getFullYear();
</script>

<style scoped>
  .footer {
    background-color: #000;
    color: #fff;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    font-family: 'Fredoka', sans-serif;
    padding-bottom: 2.5rem;
    padding-top: 0;
  }

  .footer ul {
    display: flex;
  }
  .footer a {
    display: block;
    margin-right: 1rem;
    color: #000;
  }

  .footer footer {
    font-weight: bold;
  }

  .footer footer a {
    color: #000;
    display: inline;
    margin-right: 0;
  }
</style>