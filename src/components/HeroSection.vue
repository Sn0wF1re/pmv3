<template>
  <div class="hero" id="about">
    <section>
      <img src="/masks.svg" alt="masks" class="masks"/>
      <article>
        <h2>Unravel your creative potential</h2>
        <p>
          We are a studio leveraging web 3.0 technology
          to empower creatives in Africa to harness
          their creative potential
        </p>
      </article>
    </section>
    <img src="/vector.png" alt="stars" class="stars">
  </div>
</template>

<style scoped>
  .hero {
    background-color: rgba(228, 126, 48, 1);
    min-height: 30rem;
    width: auto;
    height: auto;
    color: #000;
  }

  section {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    column-gap: 0;
  }

  article {
    display: flex;
    flex-direction: column;
    justify-content: center;
    max-width: 25rem;
  }

  /* article h2 {
    font-family: 'Fredoka', sans-serif;
    font-size: 2.5rem;
    margin-bottom: 1rem;
    line-height: 100%;
  } */

  article p {
    font-family: 'Comic Sans MS', sans-serif;
  }

  a {
    color: #000;
  }

  .masks {
    width: 37rem;
    height: 35rem;
  }

  .stars {
    position: absolute;
    top: 18.5rem;
    right: 13rem;
  }

  @media (max-width: 850px) {
    .hero {
      min-height: 25rem;
    }
    .hero section {
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    article {
      margin-left: 0;
      margin-top: 0;
      text-align: center;
    }

    .masks {
      width: 75%;
      height: 75%;
      margin-bottom: 2rem;
    }
    .stars {
      display: none;
    }
  }
</style>