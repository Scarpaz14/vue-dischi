<template>
<div class="row">
    <div class="col d-flex justify-content-center py-5">
        <i class="ex-10-icon fas fa-circle-notch"></i>
    </div>
</div>
</template>

<script >
export default {
    name:'LoginIcon',
}
</script >

<style lang="scss" scoped>
.ex-10-icon{
    animation: power 1s linear infinite;
    color:white;
    font-size: 50px;
}
 @keyframes power {
    0% {
        transform: rotate(1turn);
    }
}

</style>