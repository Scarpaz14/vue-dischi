<template>
  <div class="card-song my-5 mx-3 py-4">
      <img class="img-fluid" :src="song.poster" :alt="song.author">
      <h3>{{song.title}}</h3>
      <p>{{song.author}}</p>
      <p>{{song.genre}}</p>
      <small>{{song.year}}</small>
  </div>
</template>

<script>
export default {
    name: 'SongCard',
    props:{
        song: Object,
    }

}
</script>

<style lang="scss" scoped>

.card-song{
    color: white;
    background-color: #2e3a46 ;

}

</style>