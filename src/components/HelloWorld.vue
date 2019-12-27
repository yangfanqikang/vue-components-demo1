<template>
  <div>
    <div class="block">
      <button @click="toggle">切换</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  methods: {
    toggle () {
      // this.$refs.cascader.$children[1].toggleDropDownVisible(true)
      this.showPanel = !this.showPanel
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .ecp{
    width: 600px;
  }
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
