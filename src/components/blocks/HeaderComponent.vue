<template>
  <header>
    <div class="container-fluid py-2">
        <LogoSpotifyVue/> 
    </div>
  </header>
</template>
 
 

<script>

import LogoSpotifyVue from '../commons/LogoSpotify.vue'
export default {
 name: 'HeaderComponent',
 components: {
     LogoSpotifyVue
    }
}
</script>

<style lang="scss" scoped>


.container-fluid{
    background-color: #2e3a46;
    height:70px;
    display: flex;
}



</style>