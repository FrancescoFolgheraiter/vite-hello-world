<script>
import headerApp from './components/headerApp.vue';
import AppTitle from './components/AppTitle.vue';

export default {
    data() {
        return { text:"Vite Hello Wordl"}
    },
    components:{
      headerApp,
      AppTitle
    }
};
</script>

<template>
  <div>
    <headerApp/>
    <h1>{{ text }}</h1>
    <AppTitle/>
  </div>
</template>

<style scoped>
  h1{
    margin:20px auto;
    text-align: center;
  }
</style>
