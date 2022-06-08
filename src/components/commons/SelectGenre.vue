<template>
   <div>
        <label for="genre">Fascia d'età</label>
        <select id="genre" v-model="dataSelect.genreSelected">
            <option value="Rocks">Rocks</option>
            <option value="Pop">Pop</option>
            <option value="Jazz">Jazz</option>
            <option value="Metal">Metal</option>
        </select>
    </div>
</template>

<script>
import dataSelect from '../../shared/dataSelect'
export default {
    name: 'SelectGenre',
    data(){
        return{
            dataSelect,
        }
    }

}
</script>

<style>

</style>