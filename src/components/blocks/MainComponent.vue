<template>
 <main>
     <SectionSongCard/>
 </main>
</template>

<script>
import SectionSongCard from "../sections/SectionSongCard.vue";


export default {
    name:'MainComponent',
    components: { 
        SectionSongCard 
    }
}
</script>

<style lang="scss" scoped>

main{
    background-color: #1e2d3b;
    height: calc(100vh + 200px);
    
}

</style>