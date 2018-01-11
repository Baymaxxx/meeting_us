<template>
  <div>
    <h1>Welcome to {{message}}</h1>
    <p>Let's Go</p>
  </div>
</template>

<script>
  export default {
    name: 'index',
    data () {
      return {
        message: '带我去约会吧!'
      }
    }
  }
</script>

<style lang='scss' scoped  type="text/css">
  $base-color:#888;
  h1{color:$base-color;}
  // p{background:$base_bgcolor}
</style>