<template>
  <div class="nav" id="nav">
    <a href="#nav"><img src="/pmlogo.svg"></a>
    <nav class="desktop-nav" v-show="!mobileMenuVisible">
      <li><a href='#about'>About</a></li>
      <li><a href='#story'>Story</a></li>
      <li><a href='#nfts'>NFTs</a></li>
      <li><a href='#gaming'>Gaming</a></li>
      <li class="marketplace">
        <a href=''>Marketplace</a>
        <p>Coming Soon</p>
      </li>
    </nav>

    <div class="mobile-toggle" @click="toggleMobileMenu">
      <span class="line"></span>
      <span class="line"></span>
      <span class="line"></span>
    </div>

    <nav class="mobile-nav" v-show="mobileMenuVisible">
      <li><a href='#about'>About</a></li>
      <li><a href='#story'>Story</a></li>
      <li><a href='#nfts'>NFTs</a></li>
      <li><a href='#gaming'>Gaming</a></li>
      <li class="marketplace">
        <a href=''>Marketplace</a>
        <p>Coming Soon</p>
      </li>
    </nav>
  </div>
</template>

<script setup>
import { ref } from 'vue';

const mobileMenuVisible = ref(false);

const toggleMobileMenu = () => {
  mobileMenuVisible.value = !mobileMenuVisible.value;
  // set class
  const mobileToggle = document.querySelector('.mobile-toggle');
  mobileToggle.classList.toggle('mobile-toggle-active');
};
</script>

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
    padding-bottom: 1rem;
  }

  .desktop-nav {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    column-gap: 0.5rem;
  }

  .desktop-nav li a {
    color: rgba(228, 126, 48, 1);
  }

  .desktop-nav li .marketplace {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .desktop-nav .marketplace a {
    background-color: rgba(228, 126, 48, 1);
    color: #000;
    border: 3px solid rgba(228, 126, 48, 1);
    border-radius: 0.5rem;
    padding: 0.4rem;
  }

  .desktop-nav .marketplace p {
    color: #fff;
    font-size: 0.7rem;
    font-weight: normal;
  }

  img {
    padding-left: 7rem;
  }
  /* Show the mobile menu when the button is clicked */
  .mobile-nav {
    display: none;
  }

  @media (min-width: 900px) {
    .nav {
      height: 2rem;
    }
  }

  @media (max-width: 850px) {
    .line {
      width: 30px;
      height: 3px;
      background: rgba(228, 126, 48, 1);
      margin: 6px 0;
      transition: transform 0.2s, opacity 0.2s;
    }
    
    /* Mobile Navigation Menu Styles */
    .mobile-toggle-active .line:nth-child(1) {
      transform: rotate(-45deg) translate(-9px, 12px);
    }
    
    .mobile-toggle-active .line:nth-child(2) {
      opacity: 0;
    }
    
    .mobile-toggle-active .line:nth-child(3) {
      transform: rotate(45deg) translate(-9px, -12px);
    }
  
    .mobile-nav {
      display: flex;
      background: #000;
      padding: 1rem;
      flex-direction: column;
    }
    .nav {
      flex-direction: column;
    }

    .mobile-nav li a {
      color: rgba(228, 126, 48, 1);
      font-size: 1rem;
    }

    .mobile-nav li .marketplace {
      display: flex;
      flex-direction: column;
      align-items: center;
    }
  
    .mobile-nav .marketplace a {
      background-color: rgba(228, 126, 48, 1);
      color: #000;
      border: 3px solid rgba(228, 126, 48, 1);
      border-radius: 0.5rem;
      padding: 0.1rem;
      font-size: 0.9rem;
    }
  
    .mobile-nav .marketplace p {
      color: #fff;
      font-size: 0.5rem;
      font-weight: normal;
    }
    .mobile-toggle {
      display: flex;
      flex-direction: column;
      background-color: #000;
      cursor: pointer;
    }

    img {
      padding-left: 0;
    }
    .desktop-nav {
      display: none;
    }
  }
</style>