<template>
  <div id="app">
  <LangindHeader/>
  <LandingPromo/>
  <LandingService/>
  <LandingMap/>
  <LandingComments/>
  <LandingFooter/>
  </div>
</template>

<script>
import LangindHeader from './components/LangindHeader.vue';
import LandingPromo from './components/LandingPromo.vue';
import LandingService from './components/LandingService.vue';
import LandingMap from './components/LandingMap.vue';
import LandingComments from './components/LandingComments.vue';
import LandingFooter from './components/LandingFooter.vue';

export default {
  name: 'app',
  components: {
    LangindHeader,
    LandingPromo,
    LandingService,
    LandingMap,
    LandingComments,
    LandingFooter
  }
}
</script>

<style lang="scss">
#app {
  position: relative;
  width: 1920px;


  background: #FFFFFF;
}
</style>
