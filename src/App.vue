<template>
  <div>
    <HeaderComp/>
    <AboutMe/>
    <ProjectsComp/>
    <ResumeComp/>
  </div>
</template>

<script>

import HeaderComp from './components/HeaderComp.vue';
import AboutMe from './components/AboutMe.vue';
import ProjectsComp from './components/ProjectsComp.vue';
import ResumeComp from './components/ResumeComp.vue';

export default {
  name: 'App',

  components: {
     HeaderComp,
     AboutMe,
     ProjectsComp,
     ResumeComp
  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

</style>
