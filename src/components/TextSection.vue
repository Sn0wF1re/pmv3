<template>
  <div class="text">
    <h2>
      Welcome to Pixel Morans.<br> Where creativity knows no bounds!
    </h2>
    <p>
      Our dynamic web3 platform is a haven for artists, writers,
      gamers, engineers and designers alike.
      Immerse yourself in a universe of NFTs, games, Tokens,
      and a rich lore fuel your creativity powered by our open IP;
      the 'Morans Origins' Story. Let your masterpiece begin here!
    </p>
    <a href="https://t.me/pixelmorans" target="_blank">Join community</a>
  </div>
</template>

<style scoped>
  .text {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background-color: #000;
  }

  .text h2 {
    font-size: 2.5rem;
  }
  .text h2, .text p {
    background: linear-gradient(180deg, #E8A12C 0.13%, #A004FF 171.84%);
    background-clip: text;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    font-family: 'Fredoka', sans-serif;
    margin-bottom: 1rem;
    max-width: 30rem;
  }

  .text a {
    color: rgba(228, 126, 48, 1);
    text-transform: uppercase;
    font-family: 'Fredoka', sans-serif;
    border: solid 3px rgba(228, 126, 48, 1);
    border-radius: 0.5rem;
    padding: 1rem;
    width: 20rem;
  }

  @media (max-width: 850px) {
    .text a {
      width: 15rem;
    }
  }
</style>