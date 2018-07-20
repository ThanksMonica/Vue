<template>
  <div id="app">
    <Hello/>
    <HelloWorld/>
  </div>
</template>

<script>
import Hello from './components/Hello.vue'
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    Hello,
    HelloWorld
  }
}
</script>

<style>
#app {
 
}
</style>
