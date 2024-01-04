<template>
  <div class="main-container">
    <h1>Gerenciar pedidos:</h1>

    <DashBoard />
  </div>
</template>

<script>
import DashBoard from "@/components/DashBoard.vue"

export default {
  components: {
    DashBoard
  },
  
  name: 'PedidosView'
}
</script>