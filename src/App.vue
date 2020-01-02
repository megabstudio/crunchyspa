<template>
  <div id="app">
    <div class="container">
      <div class="inner">
        
          <ul>
            <li><router-link to="/Show">The show</router-link></li>
            <li><router-link to="/">Home</router-link></li>
            <li><router-link to="/About">Crunchyroll</router-link></li>
          </ul>
        

        <transition name="fade" mode="out-in">
          <router-view />
        </transition>

      </div>
    </div>

  </div>
</template>


<style lang="scss" src="./global.scss">

</style>
