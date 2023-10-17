<template>
  <div class="hero" id="about">
    <section>
      <img src="/masks.svg" alt="masks"/>
      <article>
        <h2>Unravel your creative potential</h2>
        <p>
          We are a studio leveraging web 3.0 technology
          to empower creatives in africa to harness
          their creative potential
        </p>
      </article>
    </section>
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
    display: flex;
  }

  article {
    max-width: 35rem;
    display: flex;
    flex-direction: column;
    justify-content: center;
    margin-left: 10rem;
    font-size: larger;
  }

  article h2 {
    font-family: 'Fredoka', sans-serif;
    font-weight: 400px;
    font-size: 64px;
    line-height: 64px;
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