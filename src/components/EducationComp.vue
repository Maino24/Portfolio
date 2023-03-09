<template>
    <div class="backgroundEducation">
      <a href="" name="formazione"></a>
      <div class="containerEducation">
        <h1 class="title">Formazione</h1>
        <div class="firstExperience">
          <div class="title2 d-flex">
            <h3>Boolean Careers</h3>
            <img src="../assets/logoBoolean.png" alt="">
          </div>
          <h4>Master Sviluppatore Web Full Stack</h4>
          <h5 class="period">Settembre 2022 - Marzo 2023 | 6 mesi</h5>
          <p class="parag">Corso completo e intensivo di 700 ore, pratiche e teoriche, sullo
              sviluppo web lato Front-End e Back-End.
              <br>
              Le tecnologie studiate e utilizzate sono: Html, Css, Sass, Bootstrap,
              Javascript, VueJS, Axios, MySQL, PHP, Laravel.
          </p>
        </div>
        <div class="secondExperience">
          <div class="">
            <h3>IS Saraceno-Romegialli</h3>
          </div>
          <h4>Istituto tecnico settore economico - Indirizzo
              "Amministrazione, Finanza e Marketing" - Articolazione
              "Sistemi Informativi Aziendali"
          </h4>
          <h5 class="period">Settembre 2018 - Giugno 2021</h5>
          <p class="parag">
            Tecnologie studiate ed utilizzate: Html, Css, Visual Basic
          </p>
        </div>
      </div>
    </div>
</template>

<script>
export default {
    name: 'EducationComp'
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.backgroundEducation{
  padding: 3% 0;
  //border-top: 2px solid black;
  background-color: rgb(5, 5, 124);
  width: 100%;
  //height: 100vh;
  .containerEducation{
    padding-top: 2%;
    width: 70%;
    margin: auto;
    color: white;
    .title{
      font-size: 4rem;
    }
   .firstExperience{
      border-bottom: 2px solid white;
      padding: 5% 0;
      div{
        img{
        width: 60px;
        padding-left: 10px;
        }
      }      
    }
    .secondExperience{
        //border-bottom: 2px solid white;
        padding-top: 5%;
      }
  }
}























// Media-query mobile
@media screen and (max-width:480px){
.backgroundEducation{
  padding: 5% 0;
  //border-top: 2px solid black;
  background-color: rgb(5, 5, 124);
  width: 100%;
  //height: 100vh;
  .containerEducation{
    padding-top: 2%;
    width: 80%;
    margin: auto;
    color: white;
    text-align: center;
    .title{
      font-size: 3rem;
    }
    .title2{
      display: block;
      text-align: center;
      justify-content: center;
    }
    .period{
      font-size: 15px;
    }
   .firstExperience{
      border-bottom: 2px solid white;
      padding: 5% 0;
      div{
        img{
          display: none;
        }
      }      
    }
    .secondExperience{
        //border-bottom: 2px solid white;
        padding-top: 5%;
      }
  }
}
}















// Media-query tablet
@media screen and (min-width:481px) and (max-width:850px){
.backgroundEducation{
  padding: 3% 0;
  //border-top: 2px solid black;
  background-color: rgb(5, 5, 124);
  width: 100%;
  //height: 100vh;
  .containerEducation{
    padding-top: 2%;
    width: 80%;
    margin: auto;
    color: white;
    .title{
      font-size: 4rem;
    }
   .firstExperience{
      border-bottom: 2px solid white;
      padding: 5% 0;
      div{
        img{
        width: 60px;
        padding-left: 10px;
        }
      }      
    }
    .secondExperience{
        //border-bottom: 2px solid white;
        padding-top: 5%;
      }
  }
}
}
</style>