<template>
  <div id="app" class="container">
    <Title />
    <Hero />
  </div>
</template>

<script>
import Title from './components/Title.vue';
import Hero from './components/Hero.vue';

export default {
  name: 'App',
  components: {
    Title,
    Hero
  }
}
</script>
