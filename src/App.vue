<template>
  <div>
    <HeaderComp/>
    <AboutMe/>
  </div>
</template>

<script>

import HeaderComp from './components/HeaderComp.vue';
import AboutMe from './components/tags/AboutMe.vue';

export default {
  name: 'App',

  components: {
     HeaderComp,
     AboutMe
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
