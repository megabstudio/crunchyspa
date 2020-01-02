<template>
  <div class="home main-content">
    <div class="left-content">

      <div>
      <img id="mainlogo" class="responsive" src="../assets/logo.png">
    </div>
      <h1>40% off - Subscribe now</h1>

      <p class="subtxt">Don't miss this opportunity, become premium now.</p>
      <input type="text" size="15" maxlength="30" placeholder="your e-mail" name="nombre" id="caja">
      <br />
      <br />
      <button id="suscribete"><router-link to="/subscription">Subscribe</router-link></button>
    
    </div>

    <div class="right-content img1">
      
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>

<style scoped>

  .img1 {
    background: url('../assets/home.jpg');
  }

</style>