<template>
   <div>
        <label for="genre">Scegli un genere musicale tra:</label>
        <select id="genre" v-model="dataSelect.genreSelected">
            <option value="all">All</option>
            <option value="Rock">Rock</option>
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
    },

    

}
</script>

<style lang="scss" scoped>

label{
    color: white;
}

select{
    width: 50%;
    margin: 10px;
}
</style>