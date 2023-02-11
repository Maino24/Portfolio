<template>
    <div class="backgroundR">
        <a href="" name="resume"></a>
        <div class="containerR">        
            <h1 class="title">Resu<span class="underline">me</span></h1>
            <div class="containerBottomR">
                
                
                <div class="singoleCard3">
                    <div class="containerText3">
                        <h3 class="skills">Skills</h3>
                        <div class="containerLoghi">
                            <img class="logo" src="../assets/HTML.png" alt="logo">
                            <img class="logo" src="../assets/CSS.png" alt="logo">
                            <img class="logo" src="../assets/SASS.png" alt="logo">
                            <img class="logo" src="../assets/JS.png" alt="logo">
                            <img class="logo" src="../assets/VUEJS.png" alt="logo"> 
                            <img class="logo" src="../assets/nodejs.png" alt="logo"> 
                            <img class="logo" src="../assets/BOOT.png" alt="logo">
                            <img class="logo" src="../assets/PHP.png" alt="logo">
                            <img class="logo" src="../assets/MYSQL.png" alt="logo">
                            <img class="logo" src="../assets/phpMy.png" alt="logo"> 
                            <img class="logo" src="../assets/laravel.png" alt="logo">
                            <img class="logo" src="../assets/git.png" alt="logo">
                        </div>
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
  border-top: 2px solid black;
  background-color: rgb(13, 13, 207);
  //width: 100vw;
  height: 100vh;
  .containerR{
    width: 70%;
    margin: auto;
    .title{
        font-size: 4rem;
        color: white;
       padding: 3% 0;
        .underline{
            border-bottom: 5px solid black;
        }
    }
    .containerBottomR{
        //padding-top: 10vh;
        width: 100%;
        display: flex;
        justify-content: space-between;
        .singoleCard{
            flex-basis: 30%;
            //border: 1px solid white;
            border-bottom: 1px solid black;
            border-right: 1px solid black;
            border-left: 1px solid black;
            height: 70vh;
            .containerText1{
                padding: 5% 10%;
                border-top: 4px solid rgb(0, 255, 145);
                color: white;
                .experience{
                    padding-bottom: 5%;
                    font-size: 2rem;
                    color: rgb(204, 204, 16);  
                }
                .firstExperience{
                    border-bottom: 1px solid white;
                    //padding: 4% 0;
                    .startParag{
                        padding-top: 3%;
                    }
                }
                .secondExperience{
                    padding: 4% 0;
                    .startParag{
                        padding-top: 3%;
                    }
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
            height: 70vh;
            .containerText2{
                padding: 5% 10%;
                    .education{
                    padding-bottom: 5%;
                    font-size: 2rem;
                    color: rgb(204, 204, 16); 
                    }
                    .firstEducation{
                    color: white;
                    border-bottom: 1px solid white;
                    padding: 4% 0;
                        .startParag{
                            padding-top: 3%;
                        }
                    }
                    .secondEducation{
                        color: white;
                        padding: 4% 0;
                        .startParag{
                            padding-top: 3%;
                        }
                    }   
            }
        }

        .singoleCard3{
            flex-basis: 30%;
            border-top: 4px solid blue;
            border-bottom: 1px solid black;
            border-right: 1px solid black;
            border-left: 1px solid black;
            height: 70vh;
            .containerText3{
                padding: 5% 10%;
                    .skills{
                    padding-bottom: 5%;
                    font-size: 2rem;
                    color: rgb(204, 204, 16); 
                    }
                    .containerLoghi{
                        display: flex;
                        flex-wrap: wrap;
                        .logo{
                            width: 15%;
                            margin: 7% 7%;
                        }
                    }

                }
        }
    }
  }
  
}
</style>