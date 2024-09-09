
<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';
// my-component.js
export default {
  data() {
    return { 
      count: 0 
    }
  },
  components:{
    AppTitle, AppHero
  }
}
</script>

<template>
  <AppTitle />
  <AppHero />
</template>

<style scoped>

</style>

