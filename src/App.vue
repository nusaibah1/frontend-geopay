<template>
  <nav>
    <navbar-comp/>
    <!-- <home-view/> -->
  </nav>
  <footer>
    
    <router-view/>
    <!-- <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> -->
  </footer>
  <footer-comp/>
</template>
<script>
import NavbarComp from './components/NavbarComp.vue'
import FooterComp from './components/FooterComp.vue'
// import HomeView from './views/HomeView.vue'

export default{
  components:{
    NavbarComp,
    FooterComp
    // HomeView
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
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
