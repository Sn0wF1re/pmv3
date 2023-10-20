<template>
  <div class="game" id="gaming">
    <article>
      <h2>
        Take a Quest with Koko for the Adventure of a Lifetime!
      </h2>
      <p>
        In the heart of Sizwe, one of the most prosperous nations
        in the magical land of Wakawaka, lies an immense
        and breathtaking forest.
        This lush woodland is not just any forest -
        it's the sacred home of a rare and remarkable kingdom
        of silverback gorillas.
      </p>
      <article class="btn">
        <a href="#">Play Koko</a>
        <p>Coming soon</p>
      </article>
    </article>
    <img src="/koko.png" alt="koko">
  </div>
</template>

<style scoped>
  .game {
    background-color: rgba(228, 126, 48, 1);
    display: flex;
    justify-content: space-around;
    align-items: center;
  }

  .game article h2, .btn a, .game article .btn p {
    font-family: 'Fredoka', sans-serif;
  }

  .game article p {
    font-family: 'Comic Sans MS', sans-serif;
    margin-bottom: 0.5rem;
  }
  .game article {
    max-width: 20rem;
    padding-bottom: 0;
    color: #000;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .game article .btn {
    border: solid 3px #000;
    border-radius: 0.5rem;
    padding: 1rem;
    width: 20rem;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }

  .game img {
    width: 40%;
    height: 40%;
  }

  .btn a {
    color: #000;
    text-transform: uppercase;
    pointer-events: none;
  }

  .game article .btn p {
    margin-top: 0;
    margin-bottom: 0;
    color: #fff;
    font-size: 0.5rem;
  }

  @media (max-width: 850px) {
    .game {
      flex-direction: column;
    }

    .game article .btn {
      width: 15rem;
    }
    .game article {
      margin-top: 2rem;
      text-align: center;
    }

    .game img {
      width: 100%;
      height: 100%;
    }
  }
</style>
