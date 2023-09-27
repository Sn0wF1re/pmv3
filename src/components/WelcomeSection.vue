<template>
    <div class="welcome">
      <img src="/pmlogo.svg" alt="PM logo">
      <article>
        <h2>
            Unravel your true creative potential
        </h2>
        <p>
            We are a studio that leverages
            blockchain technology to empower you
            to harness your true creative potential.
        </p>
      </article>
    </div>
</template>

<style scoped>
  .welcome {
    width: auto;
    height: auto;
    margin: 0;
    display: flex;
    justify-content: space-around;
    align-items: center;
    background-color: #000;
  }

  article {
    max-width: 17rem;
  }
  
  h2 {
    color: #ff5400;
    font-family: 'Unbounded', sans-serif;
    font-weight: bold;
  }

  p {
    color: #ff9e00;
    font-family: 'Archivo', sans-serif;
  }

  @media (max-width: 768px) {
    .welcome {
      flex-direction: column;
    }
  }
</style>