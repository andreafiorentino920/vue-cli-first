<template>
  <div id="app">
    <Title/>
    <Img/>
  </div>

</template>

<script>
import Title from './components/Title.vue';
import Img from './components/Hero.vue';

export default {
  name: 'App',
  components: {
    Title,
    Img
  }
}
</script>

<style>
</style>
