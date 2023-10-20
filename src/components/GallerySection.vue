<template>
  <div class="gallery" id="nfts">
    <section class="collage">
      <img src="/collage/Group15.png">
      <img src="/collage/Bg9.png">
      <img src="/collage/Group20.png">
      <img src="/collage/Bg8.png">
      <img src="/collage/Bg7.png">
      <img src="/collage/Bg6.png">
      <img src="/collage/Bg5.png">
      <img src="/collage/Group17.png">
      <img src="/collage/Bg4.png">
      <img src="/collage/Bg.png">
      <img src="/collage/Group18.png">
      <img src="/collage/Rectangle8.png">
      <img src="/collage/Bg3.png">
      <img src="/collage/Group19.png">
      <img src="/collage/Bg1.png">
      <img src="/collage/Bg2.png" class="hidden">
    </section>
    <article>
      <h2>
        Masks Of Urim are more than regular NFTs
      </h2>
      <p>
        Tales were told that certain lands
        within planet wakawaka possessed masks
        deemed to have mystical powers.
        These masks were highly sought after
        by the merchants as they believed
        that it would grant them power
        to rule over all Wakawaka.
      </p>
      <a href="https://magiceden.io/marketplace/pixel_moran_legendary_masks" target="_blank">Buy a mask</a>
    </article>
  </div>
</template>

<style scoped>
  .gallery {
    display: flex;
    justify-content: space-around;
    background-color: #000;
    padding-left: 12rem;
    padding-right: 12rem;
  }

  .gallery p {
    min-width: 1fr;
  }

  .gallery .collage {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 0.5rem;
  }

  .gallery .collage img {
    width: 100px;
    height: 100px;
  }

  .gallery article {
    display: flex;
    flex-direction: column;
    max-width: 20rem;
  }

  article h2, article p {
    background: linear-gradient(180deg, #E8A12C 0.13%, #A004FF 171.84%);
    background-clip: text;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
  }

  article h2 {
    padding-bottom: 0.3rem;
  }

  article p {
    font-family: 'Comic Sans MS', sans-serif;
    color: #ff9e00;
    padding-top: 0;
    font-size: 1rem;
  }

  article a {
    color: rgba(228, 126, 48, 1);
    border: solid 3px rgba(228, 126, 48, 1);
    border-radius: 0.5rem;
    padding: 1rem;
    text-transform: uppercase;
    margin-bottom: 4rem;
    font-family: 'Fredoka', sans-serif;
  }

  @media (max-width: 850px) {
    .gallery {
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding-right: 0;
      padding-left: 0;
    }

    .gallery .collage {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
    }
    
    .gallery .collage img {
      width: 90px;
      height: 90px;
    }
    .hidden {
      display: none;
    }
  }
</style>