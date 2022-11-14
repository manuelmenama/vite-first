<script>

import NewComponentTitleVue from './components/NewComponentTitle.vue';

export default {
  name: 'App',
  components: {
    NewComponentTitleVue
  }
}
</script>

<template>

  <div class="container">

    <NewComponentTitleVue />

  </div>
  
</template>

<style>
  .container{
    width: 50%;
    margin: 100px auto;
  }
</style>