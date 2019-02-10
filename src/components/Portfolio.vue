<template>
  <div class="portfolio">
      <!-- Top image -->
      <div class="top_image">
        <!-- Name -->
        <h1>Akihiro Inui</h1> 
      </div>
      <!-- Top image end -->
  </div>
</template>

<script>
export default {
  name: 'Portfolio',
  data () {
    return {
      text: 'Akihiro Inui',
      showText: true,
    }
  },

  // Define custom functions here
  methods: { 
  }
}
</script>

<style scoped>
/* Style for name */
h1{
  font-size: 3.2vw;
  letter-spacing: 0.2vw;
  color: white;
  font-weight: normal;
  text-align: center;
  padding-top: 35vh;
}
</style>
