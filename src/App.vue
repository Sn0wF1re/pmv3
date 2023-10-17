<template>
  <NavSection />
  <HeroSection />
  <TextSection />
  <WelcomeSection />
  <GallerySection />
  <GameSection />
  <!-- <StorySection /> -->
  <SocialsSection />
  <FooterSection />
</template>

<script>
import NavSection from './components/NavSection.vue'
import HeroSection from './components/HeroSection.vue'
import TextSection from './components/TextSection.vue'
import WelcomeSection from './components/WelcomeSection.vue'
import GameSection from './components/GameSection.vue'
// import StorySection from './components/StorySection.vue'
import GallerySection from './components/GallerySection.vue'
import SocialsSection from './components/SocialsSection.vue'
import FooterSection from './components/FooterSection.vue'


export default {
  name: 'App',
  components: {
    NavSection,
    HeroSection,
    WelcomeSection,
    GameSection,
    TextSection,
    // StorySection,
    GallerySection,
    SocialsSection,
    FooterSection
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: gray;
  margin: 0;
}

a {
  text-decoration: none;
}

.socials, .welcome, .text, .footer
.game, .story, .hero, .gallery {
  padding: 100px;
}

@media (max-width: 768px) {
  .socials, .welcome, .text,
  .footer, .story, .hero,
  .game, .gallery {
    padding: 50px;
  }
}
</style>
