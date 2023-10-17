<template>
  <div class="socials" id="socials">
    <img src="/pm-main-logo.png" alt="">
    <article>
      <h3>Follow Us</h3>
      <ul>
        <a href="https://twitter.com/pixelmorans" target="_blank"><font-awesome-icon icon="fa-brands fa-x-twitter" :style="{ color: iconColor }" /></a>
        <a href="https://t.me/pixelmorans" target="_blank"><font-awesome-icon icon="fa-brands fa-telegram" :style="{ color: iconColor }" /></a>
        <a href="https://discord.gg/BZEqhguD2e" target="_blank"><font-awesome-icon icon="fa-brands fa-discord" :style="{ color: iconColor }" /></a>
        <a href="https://medium.com/@pixelmorans" target="_blank" class="middle"><font-awesome-icon icon="fa-brands fa-medium" :style="{ color: iconColor }" /></a>
        <a href="https://instagram.com/pixelmorans" target="_blank" class="middle"><font-awesome-icon icon="fa-brands fa-instagram" :style="{ color: iconColor }" /></a>
      </ul>
    </article>
  </div>
</template>

<script>
export default {
  data() {
    return {
      iconColor: 'rgba(228, 126, 48, 1)'
    };
  }
};
</script>

<style scoped>
  .socials {
    background-color: #000;
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding-bottom: 0;
  }

  .socials article {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }

  .socials img {
    width: 60px;
    height: 60px;
  }
  .socials h3 {
    font-family: 'Fredoka', sans-serif;
    font-size: 2.5rem;
    color: #fff;
    margin-bottom: 0;
  }

  .socials ul {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    grid-template-rows: auto;
    font-size: 3rem;
    column-gap: 5.5rem;
    margin-top: 0.25rem;
  }
  .socials a {
    font-family: 'Comic Sans MS', sans-serif;
    color: #fff;
    display: block;
    margin-bottom: 0.5rem;
    width: 3px;
  }

  @media (max-width: 768px) {
    .socials {
      flex-direction: column;
      padding-bottom: 0;
    }

    .socials ul {
      grid-template-columns: repeat(5, 1fr);
      margin-top: 2rem;
      column-gap: 2.5rem;
      margin-right: 5rem;
      font-size: 1.5rem;
    }

    /* .socials article {
      margin-left: 2rem;
    } */
    .socials h3 {
      font-size: 2rem;
      margin-right: 1rem;
    }
    /* .socials .middle {
      margin-left: 3.5rem;
    } */

    img {
      width: 20%;
      height: 20%;
    }
  }
</style>