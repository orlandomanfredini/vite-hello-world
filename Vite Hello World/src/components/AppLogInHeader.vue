<script>
export default {
    data(){
        return{
            log: 'LOG IN'
        }
    }
}
</script>


<template>
    <div class="log-in">
         <span>{{ log }}</span>
    </div>
</template>

<style scoped>
.log-in{
    text-align: right;
    color: black;
    margin-right: 10px;
}
</style>