<template>
  <div class="hero" id="home">
    <section>
      <img src="/masks.svg" alt="masks"/>
      <article>
        <h2>Welcome!</h2>
        <p>
          We tell authentic stories
          that explore infinite possibilities...
        </p>
      </article>
    </section>
  </div>
</template>

<style scoped>
  .hero {
    background-color: #ff7900;
    min-height: 30rem;
    width: auto;
    height: auto;
    color: #000;
  }

  section {
    display: flex;
  }

  article {
    max-width: 20rem;
    display: flex;
    flex-direction: column;
    justify-content: center;
    margin-left: 10rem;
    font-size: larger;
  }

  article h2 {
    font-family: 'Fredoka', sans-serif;
  }

  article p {
    font-family: 'Comic Sans MS', sans-serif;
  }

  a {
    color: #000;
  }

  @media (max-width: 768px) {
    .hero {
      min-height: 25rem;
    }
    .hero section {
      flex-direction: column;
    }
    article {
      align-items: center;
      justify-content: center;
      margin-right: 20rem;
    }
  }
</style>