<template>
  <div class="hero" id="about">
    <section>
      <img src="/masks.svg" alt="masks"/>
      <article>
        <h1>Unravel your<br> creative potential</h1>
        <p>
          We are a studio leveraging web 3.0 technology
          to empower creatives in Africa to harness
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
    max-width: 100%;
  }

  article {
    display: flex;
    flex-direction: column;
    justify-content: center;
    margin-left: 10rem;
  }

  article h1 {
    font-family: 'Fredoka', sans-serif;
    font-weight: 400px;
    font-size: 2.5rem;
    margin-bottom: 1rem;
  }

  article p {
    font-family: 'Comic Sans MS', sans-serif;
    margin-top: 0;
  }

  a {
    color: #000;
  }

  img {
    width: 37rem;
    height: 35rem;
  }

  @media (max-width: 768px) {
    .hero {
      min-height: 25rem;
    }
    .hero section {
      flex-direction: column;
      align-items: center;
    }
    article {
      margin-left: 0;
      margin-top: 0;
      text-align: center;
    }

    img {
      width: 75%;
      height: 75%;
      margin-bottom: 2rem;
    }
  }
</style>