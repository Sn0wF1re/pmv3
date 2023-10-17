<template>
  <div class="game" id="koko">
    <article>
      <h1>
        Take a Quest<br> with Koko for the<br> Adventure of a<br> Lifetime!
      </h1>
      <p>
        In the heart of Sizwe, one of the most prosperous nations
        in the magical land of Wakawaka, lies an immense
        and breathtaking forest.
        This lush woodland is not just any forest -
        it's the sacred home of a rare and remarkable kingdom
        of silverback gorillas.
      </p>
      <article class="btn">
        <a href="">Play Koko</a>
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
    padding: 100px;
  }

  .game article h1, .btn a, .game article .btn p {
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
  }

  .game article .btn {
    border: solid 3px #000;
    border-radius: 0.5rem;
    width: 18.4rem;
    height: 5.1rem;
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
    font-size: 1.7rem;
    font-weight: 400;
  }

  .game article .btn p {
    margin-top: 0;
    margin-bottom: 0;
    color: #fff;
    font-size: 0.7rem;
  }
</style>
