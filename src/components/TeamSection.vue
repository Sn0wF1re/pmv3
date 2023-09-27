<template>
  <div class="team" id="team">
    <p>Img 1</p>
    <p>Img 2</p>
    <p>Img 3</p>
    <p>Img 4</p>
    <p>Img 5</p>
    <p>Img 6</p>
  </div>
</template>

<style scoped>
  .team {
    background-color: black;
    display: grid;
    grid-template-columns: repeat(3, 1rem);
    width: auto;
    height: auto;
    justify-content: space-around;
  }
</style>
