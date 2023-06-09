<template>
  <h1>
    <datos nombre="Antonio" edad="69" fecha="04-09-1988"/> 
  </h1>
  <h1>
    <datos nombre="Julian" edad="12" fecha="03-04-2020"/>
  </h1>
  <h1>
    <datos nombre="Jessica" edad="50" fecha="04-09-1972"/>  
  </h1>
</template>

<script>

import datos from "@/components/newComponent.vue"
export default {
  name: 'App',
  components: {
   datos,
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
