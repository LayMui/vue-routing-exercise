<template>
<div id="app">
 <master-component/>
<router-view/>
</div>
</template>

<script>
import MasterComponent from './components/MasterComponent.vue'


export default {
  name: 'app',
  components: {
    MasterComponent
    
   
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
  margin-top: 60px;
}
</style>
