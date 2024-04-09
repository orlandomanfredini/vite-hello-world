<script>
import AppTitle from './components/AppTitle.vue'
import AppJumbo from './components/AppJumbo.vue';

export default {
  components: {
    AppTitle,
    AppJumbo,

  }
}
</script>


<template>
  <h1>Titolo App.vue</h1>
  <div>
    <AppTitle/>
  </div>
  <section>
    <div>
      <AppTitle/>
    </div>

    <div>
      <AppJumbo/>
      
    </div>
  </section>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}

.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
