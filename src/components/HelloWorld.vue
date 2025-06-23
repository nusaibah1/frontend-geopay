<template>
  <div class="hello">
    <div class="badge"><p class="p"></p></div>
    <h3>Within 30m radius</h3>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style scoped>
.badge{
  position: absolute;
  padding: 0 3px;
  background-color: #BFDE11;
  top: 140px;
  left: 50px;
  height: 50px;
}

h3{
  position: absolute;
  left: 80px;
}

</style>
