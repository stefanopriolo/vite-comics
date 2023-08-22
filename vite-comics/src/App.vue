<script>
import TheHeader from "./components/TheHeader.vue"
import Banner from "./components/Banner.vue"
import TheFooter from "./components/TheFooter.vue"

export default {
components: {
  TheHeader,
  Banner,
  TheFooter
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
      <h2>Content goes here</h2>
    </div>
    
  </main>
  <Banner></Banner>
  <TheFooter></TheFooter>
</template>

<style>
main {
  background-color: black;
}

main h2 {
  padding: 3rem;
  margin-left: 3rem;
  margin-bottom: 0;
  color: white;
}
</style>
