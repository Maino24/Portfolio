<template>
  <div>
    <HeaderComp/>
    <AboutMe/>
    <ProjectsComp/>
    <ExperienceComp/>
    <EducationComp/>
    <SkillsComp/>
    <ContactsComp/>
  </div>
</template>

<script>

import HeaderComp from './components/HeaderComp.vue';
import AboutMe from './components/AboutMe.vue';
import ProjectsComp from './components/ProjectsComp.vue';
import ContactsComp from './components/ContactsComp.vue';
import ExperienceComp from './components/ExperienceComp.vue';
import EducationComp from './components/EducationComp.vue';
import SkillsComp from './components/SkillsComp.vue';

export default {
  name: 'App',

  components: {
     HeaderComp,
     AboutMe,
     ProjectsComp,
     ContactsComp,
     ExperienceComp,
     EducationComp,
     SkillsComp
  },

  

}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

</style>
