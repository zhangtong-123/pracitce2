<template>
  <div>
    {{msg}}
    {{list}}
    {{list1}}
    <div>123</div>
    <div>123</div>
    <div>890</div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App',
      list:'change first',
      list1:'change second'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
