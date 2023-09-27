<template>
  <HeroSection />
  <WelcomeSection />
  <TeamSection />
  <TextSection />
  <StorySection />
  <GallerySection />
  <SocialsSection />
  <FooterSection />
</template>

<script>
import HeroSection from './components/HeroSection.vue'
import WelcomeSection from './components/WelcomeSection.vue'
import TeamSection from './components/TeamSection.vue'
import TextSection from './components/TextSection.vue'
import StorySection from './components/StorySection.vue'
import GallerySection from './components/GallerySection.vue'
import SocialsSection from './components/SocialsSection.vue'
import FooterSection from './components/FooterSection.vue'


export default {
  name: 'App',
  components: {
    HeroSection,
    WelcomeSection,
    TeamSection,
    TextSection,
    StorySection,
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
}

a {
  text-decoration: none;
}

.socials, .welcome, .text, .footer
.team, .story, .hero, .gallery {
  padding: 100px;
}

@media (max-width: 768px) {
  .socials, .welcome, .text,
  .footer, .story, .hero,
  .team, .gallery {
    padding: 50px;
  }
}
</style>
