<template>
    <div class="story" id="story">
      <h2>
        Within the boundless expanse of Wakawaka
      </h2>
      <p>
        Dive into the heart of our universe by taking a read
        of the captivating Moran's Origin Story.
        Discover how this narrative inspires our community
        to come together and create a rich and open universe.
      </p>
      <a href="https://pixelmorans.notion.site/Morans-Origins-53a3cbadef024160836ac44672fdc8ac" target="_blank">Read More</a>
    </div>
</template>

<style scoped>
  .story {
    width: auto;
    height: auto;
    margin: 0;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    align-items: center;
    background-color: #000;
  }
  
  h2, p {
    max-width: 30rem;
    background: linear-gradient(180deg, #E8A12C 0.13%, #A004FF 171.84%);
    background-clip: text;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
  }

  p {
    color: #ff9e00;
    font-family: 'Comic Sans MS', sans-serif;
    margin-bottom: 1.5rem;
  }

  a {
    color: rgba(228, 126, 48, 1);
    font-family: 'Fredoka', sans-serif;
    text-transform: uppercase;
    border: solid 3px rgba(228, 126, 48, 1);
    border-radius: 0.5rem;
    padding: 1rem;
    width: 20rem;
  }

  @media (max-width: 850px) {
    .story {
      flex-direction: column;
    }

    a {
      width: 15rem;
    }
  }
</style>