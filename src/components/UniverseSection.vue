<template>
  <div class="universe">
  </div>
</template>

<style scoped>
  .universe {
    background-image: url('/universe.png');
    background-size: cover;
    background-repeat: no-repeat;
    height: 43.75rem;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  h2 {
    text-transform: uppercase;
    background: linear-gradient(180deg, #000 0%, #A004FF 211.31%);
    background-clip: text;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
  }

  @media (max-width: 850px) {
    .universe {
      height: 25rem;
    }
  }
</style>