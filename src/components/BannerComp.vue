<template>
  <div id="main-banner">
    <h1>
      Make your Burger
    </h1>
  </div>
</template>

<script>
export default {
  name: 'BannerComp'
}
</script>

<style scoped>

  #main-banner {
    background-image: url('/public/images/burger.jpg');
    background-position: center center;
    background-size: cover;
    height: 500px;
    display: flex;
    align-content: center;
  }

  h1 {
    color: #FFF;
    font-size: 60px;
    background: #222;
    padding: 20px 40px;
    width: max-content;
  }
</style>