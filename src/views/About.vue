<template>
  <div class="home main-content">
    <div class="left-content">

      <div id="responsive">
      <img id="mainlogo" src="../assets/logo.png">
      </div>
      <h1>Crunchyroll</h1>

      <p class="subtxt">Crunchyroll is an American distributor, publisher, and licensing company focused on streaming anime, manga, and dorama. Founded in 2006 by a group of University of California, Berkeley graduates, Crunchyroll's distribution channel and partnership program delivers content to over 35 million online community members worldwide. </p>
    
    
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
    background: url('../assets/about.jpg');
  }

</style>