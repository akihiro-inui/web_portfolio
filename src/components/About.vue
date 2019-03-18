<template>
<div id="about"><!-- about -->
    <h2 id="about_title" data-aos="fade-up-left" data-aos-duration="1000">ABOUT</h2>
        <div class = "about_sentence" data-aos="fade-up-left" data-aos-duration="1000" data-aos-delay="1500" data-aos-anchor="#about_title">
            <p>I am a Jedi master</p>
            <p>I hate Darth Vader and tomato</p>
            <p>May the force be with you</p>
        </div>
</div><!-- End about-->
</template>

<script>
export default {
}
</script>

<style lang="scss" scoped>
#about{
  height: 130vh;
  background-color: #7a7a7a;
}
#about_title{
  padding-top: 25vh;
  font-size: 5vw;
  color: #ffffff;
}
.about_sentence{
  float: center;
  font-size:1.5em;
  padding-top: 10vh;
  line-height: 10vh;
}
</style>
