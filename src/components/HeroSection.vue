<template>
  <div class="hero" id="home">
    <nav>
        <li><a href='#home'>Home</a></li>
        <li><a href='#team'>Team</a></li>
        <li><a href='#socials'>Socials</a></li>
    </nav>
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
  
  nav {
    list-style: none;
    display: flex;
    justify-content: space-around;
    font-family: 'Unbounded', sans-serif;
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
    font-family: 'Unbounded', sans-serif;
  }

  article p {
    font-family: 'Archivo', sans-serif;
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