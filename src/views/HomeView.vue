<template>
  <HelloWorld/><br><br><br>
  <div  class="home">
    <div class="home1">
      <img alt="Vue logo" src="https://ntandomabuto.github.io/images/geo2.jpg">
      <h5>{Organisation name}</h5><p>miles away</p>
      <button>View</button>
    </div>
    <div class="home1">
      <img alt="Vue logo" src="https://ntandomabuto.github.io/images/geo2.jpg">
      <h5>{Organisation name}</h5><p>miles away</p>
      <button>View</button>
    </div>
    <div class="home1">
      <img alt="Vue logo" src="https://ntandomabuto.github.io/images/geo2.jpg">
      <h5>{Organisation name}</h5><p>miles away</p>
      <button>View</button>
    </div>

  </div><br><br>
  <div class="badge"><p class="p"></p></div>
  <h3>Recently viewed</h3>

</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
<style scoped>
.home1{
  border: solid black 2px;
  border-radius: 1rem;
  width: 350px;
  margin-left: 70px;
  padding: 10px;
}
.home{
  display: flex;
  justify-content: center;
  align-content: center;
}
button{
  padding: 10px;
  width: 90px;
  border-radius: 1rex;
}
.badge{
  position: absolute;
  padding: 0 3px;
  background-color: #BFDE11;
  left: 50px;
  height: 50px;
  text-align: center;
}
h3{
  position: absolute;
  left: 80px;
}
</style>
