<script>
import AppLinkHeader from './components/AppLinkHeader.vue';
import AppLogoHeader from './components/AppLogoHeader.vue';
import AppLogInHeader from './components/AppLogInHeader.vue';

export default {
  components: {
    AppLogoHeader,
    AppLinkHeader,
    AppLogInHeader,

  }
}
</script>


<template>
  <header class="main_header">
    <div class="container">
      <div class="row">
        <div class="col-3"><AppLogoHeader/></div>
        <div class="col-6"><AppLinkHeader/></div>
        <div class="col-3"><AppLogInHeader/></div>
        
        
      </div>
    </div>
    
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
  background-color: rgb(255, 255, 255);
  border-radius: 20px;
}

.row{
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  
}

.col-3{
  width: calc(3 * (100% / 12));
}

.col-6{
  width: calc(6 * (100% / 12)) ;
}


</style>
