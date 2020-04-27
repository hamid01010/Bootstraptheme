<template>
  <div id="app"> 
    <navbar />
    <router-view />
    <ribbon />
    <app-footer />
  </div>
</template>

<script>
import ribbon from "./components/Ribbon"
import Navbar from "./components/Navbar"
import AppFooter from "./components/AppFooter"
export default {
    name: "app",
    components:{
        ribbon,
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
    color: rgb(31, 158, 231) !important
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
