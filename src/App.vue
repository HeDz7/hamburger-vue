<template>
  <NavBar :logo="logo_src" :alt="app_name" />
  <router-view/>
  <FooterComp />
</template>

<script>
import NavBar from './components/NavBar.vue'
import FooterComp from './components/FooterComp.vue'

export default {
  components: {
    NavBar,
    FooterComp
  },

  data() {
    return {
      logo_src: "/images/logo.png",
      app_name: "Make your Burger"
    }
  }
}
</script>

<style>
  * {
    font-family: Helvetica, Arial, sans-serif;
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    flex-wrap: wrap;
  }

  .main-container {
    margin: 50px;
    min-height: 250px;
  }

  h1 {
    text-align: center;
    font-size: 42px;
    margin-bottom: 30px;
    color: #222;
  }

  p {
    flex-wrap: unset;
  }
</style>
