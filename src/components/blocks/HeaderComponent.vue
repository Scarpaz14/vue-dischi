<template>
  <header>
    <div class="container-fluid py-2">
      <div class="row d-flex align-items-center">
        <div class="col"><LogoSpotify/></div>
        <div class="col"><select-genre/></div>
      </div>
    </div>
  </header>
</template>
 
 

<script>

import LogoSpotify from '../commons/LogoSpotify.vue';
import SelectGenre from '../commons/SelectGenre.vue';
export default {
 name: 'HeaderComponent',
 components: {
     LogoSpotify,
     SelectGenre,
    }
}
</script>

<style lang="scss" scoped>


.container-fluid{
    background-color: #2e3a46;
    height:70px;
}

.col{
  height: 100%;
}



</style>