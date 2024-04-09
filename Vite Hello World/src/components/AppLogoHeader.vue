<script>
export default {
    data(){
        return{
            msg: 'Ciao',
            logo: 'https://static-00.iconduck.com/assets.00/react-icon-512x512-u6e60ayf.png'
        }
    }
}
</script>

<template>
    <div class="col-3">
        <img :src="logo" alt="">
    </div>
            
</template>

<style scoped>
.col-3{
    width: calc(4 * (100% / 12));
    padding: 5px;
}

img{
    max-width: 50px;
}

</style>