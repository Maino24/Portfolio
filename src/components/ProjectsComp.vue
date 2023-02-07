<template>
    <div class="backgroundP">
        <div class="containerP">
           <h1 class="title">My Projects</h1>
           <div class="grid">
                <div class="square">
                    <!--<video width="320" height="240" controls>
                        <source src="../assets/.....mp4" type="video/mp4">
                    </video>-->
                </div>
                <div class="square"></div>
                <div class="square"></div>
                <div class="square"></div>
           </div>
        </div>
    </div>
</template>

<script>


export default {
    name: 'ProjectsComp'
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.backgroundP{
  //border-top: 10px solid white;
  background-color: #202123;
  width: 100vw;
  height: 100vh;
  .containerP{
    width: 70%;
    margin: auto;
    padding: 2% 0;
    .title{
        font-size: 4rem;
        color: white;
    }
    .grid{
        padding-top: 5%;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-wrap: wrap;
        width: 100%;
        margin: 0 auto;
        .square{
            border: 1px solid white;
            width: calc(100% / 2);
            aspect-ratio: 1/0.4;
        }
    }
  }
}
</style>