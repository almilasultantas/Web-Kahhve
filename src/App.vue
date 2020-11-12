<template>
  <div >
    <Navbar/>
    <Sidebar/>
    <Login/>
    <Cart/>
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue"
import Sidebar from "./components/Sidebar.vue"
import Login from  "./components/Login.vue"
import Cart from "./components/Cart.vue"

export default {
  components: {
    Navbar,
    Sidebar,
    Login,
    Cart
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
  margin-top: 60px;
}
</style>
