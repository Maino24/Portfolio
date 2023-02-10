<template>
    <div class="backgroundC">
        <a href="" name="contacts"></a>
    </div>
</template>

<script>
export default {
    name: 'ContactsComp'
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.backgroundC{
  border-top: 2px solid black;
  background-color: blue;
  //width: 100vw;
  height: 100vh;
  .containerAM{
    padding-top: 2%;
    width: 70%;
    margin: auto;
    color: white;
  }
}
</style>