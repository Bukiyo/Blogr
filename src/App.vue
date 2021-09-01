<template>
  <the-header></the-header>
  <intro-design></intro-design>
  <mid-design></mid-design>
  <end-design></end-design>
  <the-footer></the-footer>

</template>

<script>
import TheHeader from './components/layouts/TheHeader.vue';
import IntroDesign from './components/design-resources/IntroDesign.vue';
import MidDesign from './components/design-resources/MidDesign.vue';
import EndDesign from './components/design-resources/EndDesign.vue';
import TheFooter from './components/layouts/TheFooter.vue';

export default {
  components: {
    TheHeader,
    IntroDesign,
    MidDesign,
    EndDesign,
    TheFooter
  }
}
</script>

<style>
  #app {
    overflow-x: hidden;
    background-color: #f8f7f7 !important;
  }
  .navbar-collapse > form {
    justify-content: center !important;
  }
</style>
