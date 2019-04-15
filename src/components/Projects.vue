<template>
<div id="projects">
    <h2 id="projects_title">PROJECTS</h2>
            <!-- <div id="root_isotope" class="isoDefault">
                <div v-isotope-for="element in data"  @click="selected=element">
                    {{element.name}}
                <br> {{element.id}}
                </div>
            </div> -->
</div>
</template>

<script>
// Import variables from global.js
import project_data from "../global.js"
export default {
}
</script>

<style lang="scss" scoped>
#projects{
    height: 100vh;
    background-color: #7a7a7a;
}
#projects_title{
  padding-top: 25vh;
  font-size: 5vw;
  color: #ffffff;
}
</style>
