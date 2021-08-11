<template>
  <div id="app">
    <VueHeader></VueHeader>
    <VueBody></VueBody>
    <VueFooter></VueFooter>
  </div>
</template>

<script>
import VueHeader from './components/VueHeader.vue'
import VueBody from './components/VueBody.vue'
import VueFooter from './components/VueFooter.vue'


export default {
  name: 'App',
  components: {
    VueHeader,
    VueBody,
    VueFooter
  }
}
</script>

<style>
*{
  padding: 0;
  margin: 0;
}
#app {
  display: grid;
  grid-template-rows: 50px 1fr 50px;
  height: 100vh;
  justify-items: center;
  align-items: center;
  background-color: rgb(117, 173, 155);
}
</style>
