<template>
  <div id="app"> 
    <navbar />
    <router-view />
    <app-footer />
  </div>
</template>

<script>
import Navbar from "./components/Navbar"
import AppFooter from "./components/AppFooter"
export default {
    name: "app",
    components:{
        Navbar,
        AppFooter
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
.navbar-nav .router-link-exact-active {
    color: red !important
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
