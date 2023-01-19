<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/Apphero.vue';
export default {
  name: "App",
  data() {
  },

  components: {
    AppTitle,
    AppHero
  },
}
</script>

<template>
  <app-title></app-title>
  <app-hero></app-hero>
</template>