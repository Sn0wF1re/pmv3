<template>
  <div class="story" id="story">
    <h2>Morans Origins</h2>
  </div>
</template>

<style scoped>
  .story {
    background-image: url('/origins.png');
    background-repeat: no-repeat;
    height: 43.75rem;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  h2 {
    text-transform: uppercase;
    /* font-size: 2.5rem;
    font-family: 'Fredoka', sans-serif;
    font-weight: 400px; */
    background: linear-gradient(180deg, #000 0%, #A004FF 211.31%);
    background-clip: text;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
  }

  @media (max-width: 850px) {
    .story {
      height: 25rem;
    }
  }
</style>