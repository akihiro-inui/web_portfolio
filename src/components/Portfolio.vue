<template>
  <div class="portfolio">
      <!-- Top image -->
      <div class="top_image">
        <!--Menu bar-->
        <div class="menu">
          <ul>
            <li>
              <a href="">ABOUT</a>
            </li>
            <li>
              <a href="">EDUCATION</a>
            </li>
            <li>
              <a href="">PROJECTS</a>
            </li>
            <li>
              <a href="">SKILLS</a>
            </li>
            <li>
              <a href="">CONTACT</a>
            </li>
          </ul>
        </div>
        <!--End Menu bar-->
        <!-- Name -->
        <h1>Akihiro Inui</h1>
      </div>
      <!-- End Top image -->
  </div>
</template>

<script>
export default {
  name: 'Portfolio',
  data () {
    return {
      text: 'Akihiro Inui',
      showText: true
    }
  },
  // Define custom functions here
  methods: {
  }
}
</script>

<style scoped>
/* Style for top name */
h1{
  font-size: 3.2vw;
  letter-spacing: 0.2vw;
  font-weight: normal;
  text-align: center;
  padding-top: 35vh;
}
/* Style for menu bar */
ul {
  list-style-type: none;
  padding: 0;
  margin: 0;
}
li {
  display: inline-block;
  padding: 0 5vh;
}
a {
  text-decoration: none;
  color: white;
}
a:hover{
  border-bottom: solid 1px;
}
</style>
