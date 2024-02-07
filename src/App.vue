<script>
  import AppTitle from './components/AppTitle.vue';

  export default {
    data() {
      return {
        title: 'La mia prima app con Vite!',
      };
    },
   
    components: { AppTitle },
  };
</script>

<template>
  <div class="container">
    <h1 class="red"> {{ title }} </h1>

    <AppTitle />
  </div>
</template>

<style>
@import url('./assets/style.css');
</style>