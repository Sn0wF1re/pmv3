<template>
  <NavSection />
  <HeroSection />
  <TextSection />
  <UniverseSection />
  <StorySection />
  <GallerySection />
  <GameSection />
  <SocialsSection />
  <FooterSection />
</template>

<script>
import NavSection from './components/NavSection.vue'
import HeroSection from './components/HeroSection.vue'
import TextSection from './components/TextSection.vue'
import StorySection from './components/StorySection.vue'
import GameSection from './components/GameSection.vue'
import UniverseSection from './components/UniverseSection.vue'
import GallerySection from './components/GallerySection.vue'
import SocialsSection from './components/SocialsSection.vue'
import FooterSection from './components/FooterSection.vue'


export default {
  name: 'App',
  components: {
    NavSection,
    HeroSection,
    StorySection,
    GameSection,
    TextSection,
    UniverseSection,
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
  max-width: 100%;
  max-height: 100%;
}

body {
  margin: 0;
}

h2 {
  font-family: 'Fredoka', sans-serif;
  font-size: 3rem;
  margin-bottom: 1rem;
  line-height: 100%;
}

p {
  font-size: 1rem;
  font-weight: 400;
}

a {
  text-decoration: none;
}

.socials, .story, .text, .footer,
.game, .universe, .gallery {
  padding: 6.25rem 16.25rem;
}

@media (max-width: 768px) {
  .socials, .story, .text,
  .footer, .universe, .hero,
  .game, .gallery {
    padding: 50px;
  }
}
</style>
