<template>
  <BannerComp />

  <div class="main-container">
    <h1>Monte o seu burger:</h1>
    
    <BurgerForm />
  </div>
</template>

<script>
import BannerComp from '@/components/BannerComp.vue'
import BurgerForm from '@/components/BurgerForm.vue'

export default {
  name: 'HomeView',
  components: {
    BannerComp,
    BurgerForm
  }
}
</script>
