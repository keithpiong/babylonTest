<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>BABYLON</h2>
<Scene type="gamepad">
<Box :position="[0, 0, 5]"></Box>
</Scene>
  </div>
</template>

<script>
export default {
  name: 'Babi',
  data () {
    return {
      msg: 'Welcome to BABYLON !!'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
