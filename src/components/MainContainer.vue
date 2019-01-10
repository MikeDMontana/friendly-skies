<template>
  <div class="mainContainer">
    <InfoDrawer />
    <ForeCastContainer />
    <Footer />
  </div>
</template>

<script>
import Footer from './Footer.vue'
import ForeCastContainer from './ForeCastContainer.vue'
import InfoDrawer from './InfoDrawer.vue'

export default {
  name: 'MainContainer',
components: {
  InfoDrawer,
  ForeCastContainer,
  Footer
}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
