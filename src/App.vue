<template>
  <BaseNotification />
</template>


<script>
  import BaseNotification from './components/BaseNotification.vue';

  export default {
    name: "App",
    components: {
      BaseNotification
    }
  }
</script>

<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
</style>