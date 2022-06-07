<template>
  <section>
      <div class="container">
          <div class="row">
              <SongCard class="col-12 col-sm-6 col-lg-2" v-for="song in songs" :key="song.title" :song="song"/>
          </div>
      </div>
  </section>
</template>

<script>
import axios from 'axios';
import SongCard from '../commons/SongCard.vue'
export default {
    name: 'SectionSongCard',
    data() {
        return {
            songs: [],
        };
    },
    components: {
        SongCard
    },
     created() {
        axios.get('https://flynn.boolean.careers/exercises/api/array/music')
        .then((response) => {
            // handle success
            this.songs =response.data.response;
            console.log(response.data.response)
        })
        .catch((error) => {
            // handle error
            console.log(error);
        });
    }

}
</script>

<style lang="scss" scoped>
</style>