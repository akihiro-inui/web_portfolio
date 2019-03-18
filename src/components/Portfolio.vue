<template>
  <div class="portfolio">
      <div class="menu"><!--Menu bar-->
        <p class="title">Badass Portfolio of Obi-Wan Kenobi</p>
        <ul>
          <li>
            <a href="#about" class="menu_button">ABOUT</a>
          </li>
          <li>
            <a href="#education" class="menu_button">EDUCATION</a>
          </li>
          <li>
            <a href="#projects" class="menu_button">PROJECTS</a>
          </li>
          <li>
            <a href="#skills" class="menu_button">SKILLS</a>
          </li>
          <li>
            <a href="#contact" class="menu_button">CONTACT</a>
          </li>
        </ul>
      </div><!--End Menu bar-->
      <div class="top_image"><!-- Top image -->
        <h1>Obi-Wan</h1>
          <button href="AkihiroInuiCV.pdf" class="download_cv_button" download="AkihiroInuiCV.pdf">Download Resume</button>
      </div><!-- End Top image -->
      <!-- End Top image -->
      <About></About><!-- ABOUT -->
      <Education></Education><!-- EDUCATION -->
      <Projects></Projects><!-- PROJECTS -->
      <Skills></Skills><!-- SKILLS -->
      <Contact></Contact><!-- CONTACT -->
  </div>
</template>

<script>
// Import vue file
import About from './About.vue'
import Education from './Education.vue'
import Projects from './Projects.vue'
import Skills from './Skills.vue'
import Contact from './Contact.vue'

export default {
  name: 'Portfolio',
  components: {
    About,
    Education,
    Projects,
    Skills,
    Contact
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
</style>
