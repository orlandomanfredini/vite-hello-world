<script>
import AppLogoHeader from './components/AppLogoHeader.vue';

export default {
  components: {
    AppLogoHeader,

  }
}
</script>


<template>
  <header class="main_header">
    <AppLogoHeader/>
  </header>
  
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

.main_header{
  width: 100%;
  background-color: rgb(183, 98, 98);
  border-radius: 20px;
}
</style>
