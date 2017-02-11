<template>
  <div id="app">
    <app-nav></app-nav>
    <app-stage></app-stage>
    <app-feature></app-feature>
    <appMiddleHero :img="'/src/assets/yoga-placeholder.jpg'"></appMiddleHero>
    <app-info></app-info>
    <app-classes></app-classes>
    <appMiddleHero :img="'/src/assets/yoga-mat.jpg'"></appMiddleHero>
    <app-footer></app-footer>
  </div>
</template>

<script>
import appNav from './components/Nav.vue';
import appStage from './components/Stage.vue';
import appFeature from './components/Feature.vue';
import appFooter from './components/Footer.vue';
import appMiddleHero from './components/MiddleHero.vue';
import appInfo from './components/Info.vue';
import appClasses from './components/Classes.vue';
export default {
    components: {
      appNav: appNav,
      appFooter: appFooter,
      appStage: appStage,
      appFeature: appFeature,
      appMiddleHero: appMiddleHero,
      appInfo: appInfo,
      appClasses: appClasses
    }
  }
</script>
  
<style>
#app {
  height: 100%;
}
</style>
