<script>
import headerApp from './components/headerApp.vue';

export default {
    data() {
        return { text:"Vite Hello Wordl"}
    },
    components:{
      headerApp
    }
};
</script>

<template>
  <div>
    <headerApp/>
    <h1>{{ text }}</h1>
  </div>
</template>

<style scoped>
  h1{
    margin:20px auto;
    text-align: center;
  }
</style>
