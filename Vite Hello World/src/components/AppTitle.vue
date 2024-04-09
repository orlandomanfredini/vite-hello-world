<script>
export default {
    name: 'AppTitle',
    data(){
        return{
            title: 'Ciao Vite',
            counter: 0,
        }
    }

}
</script>


<template>
    <h1>{{title}} {{ counter }}</h1>
    <ul>
        <li>Roba</li>
    </ul>

    <button @click="counter++">Genera</button>
    

</template>

<style scoped>
h1 {
    color: orange;
}
</style>