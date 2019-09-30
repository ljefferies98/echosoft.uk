<template>
  <b-container class="about">
    <b-row>
      <b-col>
         <h2>About Me</h2>
      </b-col>
    </b-row>
    <b-row>
      <b-col>
         <p>Hi, I'm Lewis Jefferies, a freelance software engineer with expertise in Web Application Development.</p>
         <p>I entered the industry through a less common route in that I didn't graduate from University, however, I was offered an apprenticeship with Ian Williams which gave me the jump start I needed to pursue my passion in the realm of technology where I gained valuable hands on knowledge as well as gaining industry recognised qualifications.</p>
         <p>In my spare time I like to investigate and play with new technologies and gadgets as well as hiking and taking part in various sports!</p>
         <p>I am currently available to consult or for fixed price work.</p>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
export default {
  name: 'Home'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style type="scss" scoped>
@media screen and (max-width: 767px) {
  h2 {
    text-align: center;
  }
}
</style>
