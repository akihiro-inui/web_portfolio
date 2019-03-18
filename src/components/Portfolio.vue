<template>
  <div class="portfolio">
      <div class="menu"><!--Menu bar-->
        <p class="title">Badass Portfolio of Obi-Wan Kenobi</p>
        <ul>
          <li>
            <a href="#about" class="menu_button">ABOUT</a>
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
      </div><!--End Menu bar-->
      <div class="top_image"><!-- Top image -->
        <h1>{{titleName}}</h1>
          <button href="AkihiroInuiCV.pdf" class="download_cv_button" download="AkihiroInuiCV.pdf">Download Resume</button>
      </div><!-- End Top image -->
      <!-- End Top image -->
      <div id="about"><!-- about -->
          <h2 class="about_title" data-aos="fade-up-left" data-aos-duration="600">ABOUT</h2>
          <div class = "about_sentence">
            <p>I am a Jedi master</p>
            <p>I hate Darth Vader and tomato</p>
            <p>May the force be with you</p>
          </div>
      </div><!-- End about-->
  </div>
</template>

<script>
export default {
  name: 'Portfolio',
  data () {
    return {
      titleName: 'Obi-Wan'
    }
  },
  // Define custom functions here
  methods: {
  }
}
</script>

<style scoped lang="scss">
// Import scss
@import "../styles/button/square_move_button";
@import "../styles/menu/menu_bar";

// Overwrite custom scss components
.download_cv_button{
    // Import button
    @extend .square_move_button;
    padding: 1.5vh 1.5vw;
    margin-top:20vh;
    text-align: center;
    float: center;
}

// Name TODO: to be scss
h1{
  font-size: 50px;
  letter-spacing: 0.2vw;
  font-weight: normal;
  text-align: center;
  padding-top: 35vh;
}
#about{
  height: 100vh;
  background-color: rgb(151, 151, 151);
}
.about_title{
  padding-top: 25vh;
  font-size: 5vw;
  color: #ffffff;
}
.about_sentence{
  float: center;
  font-size:1.5em;
  padding-top: 8vh;
  line-height: 10vh;
}
</style>
