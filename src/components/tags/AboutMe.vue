<template>
    <div class="backgroundAM">
        <div class="containerAM">   
            <h1 class="nameAM">About Me</h1>
            <div class="containerDown">
                <div class="containerImg">
                </div>
                <div class="containerPrag">
                    <p>Mi chiamo Gabriele Mainetti ..........</p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'AboutMe'
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.backgroundAM{
  border-top: 10px solid white;
  background-color: #202123;
  width: 100vw;
  height: 100vh;
  .containerAM{
    padding-top: 2%;
    width: 70%;
    margin: auto;
    color: white;
 
    .containerDown{
        padding-top: 5%;
        display: flex;
        justify-content: space-between;
            .containerImg{
                width: calc(100% /2);
                height: 60vh;
                background-image: url("../../assets/fototessera.jpg");
                background-size: contain,  cover;
                background-repeat: no-repeat;

            }    
            .containerParag{
                width: calc(100% /2);
            }
    }
    }
  
}
</style>