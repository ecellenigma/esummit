<template>

  <NavBar/>
  <LandingVue/>
  <AboutV2/>
  <CardsWrapper/>
  <FaqsWrapper/>
  <TimelineVue/>  
  <SponsorsVue/>  
  <FooterVue/>


</template>

<script>
import NavBar from './components/NavBar.vue';
import LandingVue from './components/Landing.vue';
import AboutV2 from './components/AboutV2.vue';
import TimelineVue from "./components/Timeline.vue"
import FooterVue from "./components/Footer.vue" 
import SponsorsVue from "./components/Sponsors.vue" 
import CardsWrapper from "./components/Events.vue"
import FaqsWrapper from './components/FaqsWrapper.vue';

export default {
  name: 'App',
  components: {
    NavBar,
    LandingVue,
    TimelineVue,
    SponsorsVue,
    AboutV2,
    FooterVue,
    CardsWrapper,
    FaqsWrapper
}
}
</script>

<style>

/* Root that contains variables - start */
:root{
  --logoPurple: #653390;
  --logoBlue: #222878;
  --grey: #444;
  /* --logoNeutral: #6533903f; */
  --logoNeutral: #b5aabe;
  --purpleDark: #2b1e37;
}
/* Root that contains variables - end */

html, body{
  margin: 0;
  scroll-behavior: smooth !important;
  transition: all; 
  overflow-x: hidden !important;
  height: 100vh;
}
.vh56{
  height: 56vh;
}

</style>
