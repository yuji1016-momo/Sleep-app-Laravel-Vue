<template>
  <div id="main">
    <!-- <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> -->
    <Header/>
    <router-view/>
    <Footer/>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  min-height: 100vh;
  /* color: #2c3e50; */
}
footer{
    position: absolute;
    bottom: 0;
    width: 100%;
}

/* #nav {
  padding: 30px;
} */

/* #nav a {
  font-weight: bold;
  color: #2c3e50;
} */

/* #nav a.router-link-exact-active {
  color: #42b983;
} */
</style>

<script>
import Header from '@/app/components/Header.vue'
import Footer from '@/app/components/Footer.vue'

export default {
  // name: 'Home',
  components: {
    Header,
    Footer,
  }
}
</script>