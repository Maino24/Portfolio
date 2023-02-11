<template>
    <div class="backgroundS">
      <div class="containerS">
        <h1 class="title">Skills</h1>

      </div>
    </div>
</template>

<script>
export default {
    name: 'SkillsComp'
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.backgroundS{
  border-top: 2px solid black;
  background-color: rgb(13, 13, 207);
  //width: 100vw;
  height: 100vh;
  .containerS{
    padding-top: 2%;
    width: 70%;
    margin: auto;
    color: white;
    .title{
      font-size: 4rem;
    }
  }
}
</style>