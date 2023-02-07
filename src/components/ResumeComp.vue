<template>
    <div class="backgroundR">
        <div class="containerR">        
            <h1 class="title">Resu<span class="underline">me</span></h1>
            <div class="containerBottomR">
                <div class="singoleCard">
                    <div class="containerText1">
                        <h3>Experience</h3>  
                    </div>
                </div>
                <div class="singoleCard2">
                    <div class="containerText2">
                        <h3>Education</h3>
                    </div>
                </div>
                <div class="singoleCard3">
                    <div class="containerText3">
                        <h3>Equipment</h3>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>


export default {
    name: 'ResumeComp'
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.backgroundR{
  border-top: 10px solid white;
  background-color: #202123;
  width: 100vw;
  height: 100vh;
  .containerR{
    width: 70%;
    margin: auto;
    padding: 10% 0;
    .title{
        font-size: 4rem;
        color: white;
        .underline{
            border-bottom: 5px solid blue;
        }
    }
    .containerBottomR{
        margin-top: 5vh;
        width: 100%;
        display: flex;
        justify-content: space-between;
        .singoleCard{
            flex-basis: 30%;
            //border: 1px solid white;
            border-bottom: 1px solid black;
            border-right: 1px solid black;
            border-left: 1px solid black;
            height: 50vh;
            .containerText1{
                padding: 20% 15%;
                border-top: 4px solid rgb(0, 255, 145);
                    h3{
                    color: white;
                    }
            }
            
        }
        .singoleCard2{
            flex-basis: 30%;
            margin-top: 5vh;
            //border: 1px solid white;
            border-top: 4px solid rgb(255, 153, 0);
            border-bottom: 1px solid black;
            border-right: 1px solid black;
            border-left: 1px solid black;
            height: 50vh;
            .containerText2{
                padding: 20% 15%;
                    h3{
                    color: white;
                    }
            }
        }
        .singoleCard3{
            flex-basis: 30%;
            border-top: 4px solid blue;
            border-bottom: 1px solid black;
            border-right: 1px solid black;
            border-left: 1px solid black;
            height: 50vh;
            .containerText3{
                padding: 20% 15%;
                    h3{
                    color: white;
                    }
            }
        }
    }
  }
  
}
</style>