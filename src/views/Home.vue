<template>
  <Banner/>
  <img src="" alt="">
  <div class="main-container">
    <h1>Monte seu burguer:</h1>
    <burguer-form/>
  </div>
  
</template>

<script>
import BurguerForm from '@/components/BurguerForm.vue'
import Banner from '../components/Banner.vue'
export default {
  name:"Home",
  components:{
    Banner,
    BurguerForm
  }

}
</script>

<style>

</style>