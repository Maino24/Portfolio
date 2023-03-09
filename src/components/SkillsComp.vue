<template>
    <div class="backgroundS">
      <a href="" name="skills"></a>
      <div class="containerS">
        <h1 class="title">Skills</h1>
        <div class="containerTot">
          <div class="containerFront">
            <h2 class="text-center">Front-end</h2>
            <div class="d-flex flex-wrap pt-5">
              <img class="logo" src="../assets/HTML.png" alt="logo">
              <img class="logo" src="../assets/CSS.png" alt="logo">
              <img class="logo" src="../assets/SASS.png" alt="logo">
              <img class="logo" src="../assets/JS.png" alt="logo">
              <img class="logo" src="../assets/VUEJS.png" alt="logo"> 
              <img class="logo" src="../assets/nodejs.png" alt="logo"> 
              <img class="logo" src="../assets/BOOT.png" alt="logo">
            </div>
          </div>
          <div class="containerBack">
            <h2 class="text-center">Back-end</h2>
            <div class="d-flex flex-wrap pt-5">
              <img class="logo" src="../assets/PHP.png" alt="logo">
              <img class="logo" src="../assets/MYSQL.png" alt="logo">
              <img class="logo" src="../assets/phpMy.png" alt="logo"> 
              <img class="logo" src="../assets/laravel.png" alt="logo">
            </div>
          </div>
        </div>
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
  //border-top: 2px solid black;
  background-color: rgb(5, 5, 124);
  //width: 100vw;
  //height: 100vh;
  .containerS{
    padding-top: 2%;
    width: 70%;
    margin: auto;
    color: white;
    .title{
      font-size: 4rem;
    }
    .containerTot{
      width: 100%;
      display: flex;
      padding-top: 5%;
      .containerFront{
        width: calc(100%/2);
        height: 60vh;
        border-right: 1px solid white;
        padding-right: 5%;
        .logo{
          width: 10%;
          margin: 7% 7%;
        }
      }
      .containerBack{
        width: calc(100%/2);
        //border: 1px solid white;
        padding-left: 5%;
        .logo{
          width: 15%;
          margin: 7% 7%;
          //border: 1px solid white;
        }
      }
    }
  }
}

















// Media-query mobile
@media screen and (max-width:480px){
  .backgroundS{
    //border-top: 2px solid black;
    background-color: rgb(5, 5, 124);
    width: 100%;
    //height: 100vh;
    .containerS{
      padding-top: 2%;
      width: 80%;
      margin: auto;
      color: white;
      .title{
        font-size: 3rem;
        text-align: center;
      }
    .containerTot{
      width: 100%;
      display: block;
      padding-top: 5%;
      .containerFront{
        width: 100%;
        height: 35vh;
        border-right: 0;
        padding-right: 0;
        .logo{
          width: 10%;
          margin: 7% 7%;
        }
      }
      .containerBack{
        width: 100%;
        //border: 1px solid white;
        padding-left: 0;
        .logo{
          width: 15%;
          margin: 7% 7%;
          //border: 1px solid white;
        }
      }
    }
  }
}
}















// Media-query tablet
@media screen and (min-width:481px) and (max-width:850px){
  .backgroundS{
    //border-top: 2px solid black;
    background-color: rgb(5, 5, 124);
    width: 100%;
    //height: 100vh;
    .containerS{
      padding-top: 2%;
      width: 80%;
      margin: auto;
      color: white;
      .title{
        font-size: 4rem;
        text-align: left;
      }
    .containerTot{
      width: 100%;
      display: block;
      padding-top: 5%;
      .containerFront{
        width: 100%;
        height: 35vh;
        border-right: 0;
        padding-right: 0;
        .logo{
          width: 10%;
          margin: 7% 7%;
        }
      }
      .containerBack{
        width: 100%;
        //border: 1px solid white;
        padding-left: 0;
        padding-top: 15%;
        .logo{
          width: 15%;
          margin: 7% 7%;
          //border: 1px solid white;
        }
      }
    }
  }
}
}
</style>