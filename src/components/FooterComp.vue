<template>
  <footer id="footer">
    <p>Make your Burger &copy; 2021</p>
  </footer>
</template>

<script>
export default {
  name:"FooterComp"
}
</script>

<style scoped>
  #footer {
    height: 200px;
    background-color: #222;
    border-top: 4px solid #111;
    color: #FCBA03;
    display: flex;
    align-content: center;
    justify-content: center;
    width: 100%;
  }

  p {
    display: flex;
    align-content: center;
    flex-wrap: wrap;
  }
</style>