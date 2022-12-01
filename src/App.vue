<script >
import AppTitle from "./AppTitle.vue";
import AppHero from "./AppHero.vue"
export default {

  components:{AppTitle ,AppHero},
  data() {

return {
  messaggio: "Hello Vite!"

}

}


  
  }
</script>

<template>
  <h1>{{messaggio}}</h1>
    <AppTitle></AppTitle>
    <AppHero></AppHero>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
