<template>
  <div class="home">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <tip position="left" message="11111111111111111111111"></tip>
    <tip position="right" message="11111111111111111111111"></tip>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import Tip from '../components/tip'

export default {
  name: 'home',
  components: {
    Tip,
    HelloWorld
  },
  methods: {
    x () {
      console.log()
    }
  }
}
</script>
