<template>
  <div>
    <nav-bar />
    <b-container>
      <b-row class="text-center logo-block" v-bind:style="{ marginTop: '55vh' }">
        <b-col>
          <h1 class="logo"><a href="mailto:info@volrix.co.uk">Volrix</a></h1>
          <h5 class="slogan"><strong>Manufacturing software that is out of this world.</strong></h5>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
import NavBar from './NavBar.vue'

export default {
  name: 'Home',
  components: {
    NavBar
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@media screen and (max-width: 767px) {
  h1.logo {
      font-size: 3rem;
  }
  h5 {
      font-size: 0.9rem;
  }
  .logo-block{
    margin-top: 49vh !important;
  }
}
h1, h2, h3, h4, h5, h6 {
  font-family: 'Poiret One','Helvetica Neue', Helvetica, Arial, sans-serif, cursive !important;
}
.logo {
  font-size: 4rem;
  opacity: 0.6;
}
.logo > a {
  color: white;
}
.slogan {
  color: white;
  opacity: 0.6;
}
.logo-block{
  margin-top: 55vh;
}
</style>
