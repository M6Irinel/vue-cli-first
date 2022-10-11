<template>
  <div id="app" class="container">
    <title-vue />
    <hero-vue />
  </div>
</template>

<script>
import TitleVue from './components/TitleVue.vue';
import HeroVue from './components/HeroVue.vue';

export default {
  name: 'App',
  
  components: {
    TitleVue,
    HeroVue
  }
}
</script>
