<template>
  <Banner/>
  <img src="" alt="">
  <div class="main-container">
    <h1>Monte seu burger:</h1>
    <burger-form/>
  </div>
  
</template>

<script>
import burgerForm from '../components/BurgerForm.vue'
import Banner from '../components/Banner.vue'
export default {
  name:"Home",
  components:{
    Banner,
    burgerForm
  }

}
</script>

<style>

</style>