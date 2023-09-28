<template>
  <div class="nav">
    <img src="/pmlogo.svg">
    <nav>
      <li><a href='#home'>Home</a></li>
      <li><a href='#team'>Team</a></li>
      <li><a href='#socials'>Socials</a></li>
    </nav>
  </div>
</template>

<style scoped>
.nav {
    list-style: none;
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-family: 'Fredoka', sans-serif;
    font-weight: bold;
    font-size: large;
    background-color: #000;
    padding: 2.5rem;
  }

  nav {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    column-gap: 10rem;
  }

  nav li a {
    color: #ff5400;
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