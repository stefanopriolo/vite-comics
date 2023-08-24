<script>
import TheHeader from "./components/TheHeader.vue"
import Banner from "./components/Banner.vue"
import TheMain from "./components/TheMain.vue"
import TheFooter from "./components/TheFooter.vue"
import Array from "./components/Array.vue"

export default {
components: {
  TheHeader,
  Banner,
  TheMain,
  TheFooter,
  Array
},
data() {
  return {}
}

}
</script>

<template>
  <TheHeader></TheHeader>
  <main>
    <div class="container">
      <div v-for="cards in cards"> 
        <img :src="thumb.cards" alt="">
      {{ cards.series }}
      </div>
      
    </div>
    
  </main>
  <Banner></Banner>
  <TheMain></TheMain>
  <TheFooter></TheFooter>
</template>

<style lang="scss">
main {
  background-color: black;


 h2 {
  padding: 3rem;
  margin-left: 3rem;
  margin-bottom: 0;
  color: white;
}
}
</style>
