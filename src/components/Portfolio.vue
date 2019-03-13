<template>
  <div class="portfolio">
      <!-- Top image -->
      <div class="top_image">
        <!--Menu bar-->
        <div class="menu">
          <p class="title">Portfolio of Akihiro Inui</p>
          <ul>
            <li>
              <a href="" class="menu_button">ABOUT</a>
            </li>
            <li>
              <a href="" class="menu_button">EDUCATION</a>
            </li>
            <li>
              <a href="" class="menu_button">PROJECTS</a>
            </li>
            <li>
              <a href="" class="menu_button">SKILLS</a>
            </li>
            <li>
              <a href="" class="menu_button">CONTACT</a>
            </li>
          </ul>
        </div>
        <!--End Menu bar-->
        <!-- Name -->
        <h1>Akihiro Inui</h1>
        <a href="AkihiroInuiCV.pdf" class="download_cv_button" download="AkihiroInuiCV.pdf">Download Resume</a>
      </div>
      <!-- End Top image -->
      <div class="about"></div>
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

<style scoped lang="scss">
// Download Resume Button
@import "../styles/button/square_move_button";
.download_cv_button{
    // Import button
    @extend .square_move_button;
    // Overwrite
    padding: 1vh 1vw;
}
// Name
h1{
  font-size: 3.2vw;
  letter-spacing: 0.2vw;
  font-weight: normal;
  text-align: center;
  padding-top: 35vh;
}
// Menu Bar
@import "../styles/menu/menu_bar";
</style>
