<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/> -->
    <navbar />
    <jumbotron /><br><br>
    <hr>
    <cardsection />
    <hr>
    <videosection />
    <hr>
  </div>
</template>

<script>
import navbar from "./components/Navbar"
import jumbotron from "./components/jumbotron"
import cardsection from "./components/cardsection"
import videosection from "./components/videosection"
export default {
    name: "app",
    components:{
        navbar,
        jumbotron,
        cardsection,
        videosection
    }
}
</script>

<style>
*{
    padding: 0;
    margin: 0;
}
#app {
  font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  color: #2c3e50;
}

/* // #nav {
//   padding: 30px;

//   a {
//     font-weight: bold;
//     color: #2c3e50;

//     &.router-link-exact-active {
//       color: #42b983;
//     }
//   }
// } */
</style>
