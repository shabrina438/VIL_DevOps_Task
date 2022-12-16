<template>
<Header_v/>
<router-view />
</template>

<script>
import Header_v from './components/Header_v.vue'
export default {
  name: 'App',
  components:{
    Header_v,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

body{
  padding: 0;
  margin: 0;
}
</style>
