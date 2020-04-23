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
    <carouselsection />
    <hr>
    <gallary />
    <hr>
    <minicarousel />
    <hr>
  </div>
</template>

<script>
import navbar from "./components/Navbar"
import jumbotron from "./components/jumbotron"
import cardsection from "./components/cardsection"
import videosection from "./components/videosection"
import carouselsection from "./components/carousel"
import gallary from "./components/gallary"
import minicarousel from "./components/minicarousel"
export default {
    name: "app",
    components:{
        navbar,
        jumbotron,
        cardsection,
        videosection,
        carouselsection,
        gallary,
        minicarousel
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
