<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/> -->
    <navbar />
  
  </div>
</template>

<script>
import navbar from "./components/Navbar"
export default {
    name: "app",
    components:{
        navbar
    }
}
</script>

<style lang="scss">
.marginleft{
    margin-left: 500px;
}
#app {
  font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  color: #2c3e50;
}

// #nav {
//   padding: 30px;

//   a {
//     font-weight: bold;
//     color: #2c3e50;

//     &.router-link-exact-active {
//       color: #42b983;
//     }
//   }
// }
</style>
