<template>
  <div class="nav">
    <img src="/pmlogo.svg">
    <nav>
      <li><a href=''>About</a></li>
      <li><a href=''>Story</a></li>
      <li><a href=''>NFTs</a></li>
      <li><a href=''>Gaming</a></li>
      <li class="marketplace">
        <a href=''>Marketplace</a>
        <p>Coming Soon</p>
      </li>
    </nav>
  </div>
</template>

<style scoped>
.nav {
    list-style: none;
    display: flex;
    justify-content: space-around;
    align-items: center;
    font-family: 'Fredoka', sans-serif;
    font-weight: bold;
    font-size: large;
    background-color: #000;
    padding: 2.5rem;
  }

  nav {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    column-gap: 0.5rem;
  }

  nav li a {
    color: rgba(228, 126, 48, 1);
  }

  nav li .marketplace {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  nav .marketplace a {
    background-color: rgba(228, 126, 48, 1);
    color: #000;
    border: 3px solid rgba(228, 126, 48, 1);
    border-radius: 0.5rem;
    padding: 0.4rem;
  }

  nav .marketplace p {
    color: #fff;
    font-size: 0.7rem;
    font-weight: normal;
  }

  @media (max-width: 768px) {
    .nav {
        flex-direction: column;
        padding-top: 1rem;
    }

    nav {
        column-gap: 1rem;
    }
  }
</style>