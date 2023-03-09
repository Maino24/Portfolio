<template>
    <div class="backgroundE">
      <a href="" name="esperienza"></a>
      <div class="containerE">
        <h1 class="title">Esperienza</h1>
        <div class="firstExperience">
          <div class="d-flex">
            <h3>Jr Full Stack Web Developer Trainee</h3>
            <img src="../assets/logoBoolean.png" alt="">
          </div>
          <h4>Boolean Careers</h4>
          <h4 class="period">Settembre 2022 - Marzo 2023 | 6 mesi</h4>
          <p class="parag">Sviluppo di progetti ispirati a web app esistenti come: Netflix,
              Whatsapp Web, Spotify, Zoom, Zalando ... .
              <br>
              Tutti i progetti svolti avevano una scadenza e questo mi ha permesso
              di avvicinarmi a ciò che avviene effettivamente nel mondo del lavoro.
          </p>
        </div>
        <div class="secondExperience">
          <div >
            <h3>Impiegato Contabile</h3>
          </div>
          <h4>Midac S.r.l.</h4>
          <h4 class="period">Agosto 2022 - agosto 2023 | 1 anno</h4>
          <p class="parag">Impiegato contabile presso studio commercialista. Gestione
            contabilità, mail, chiamate per un gruppo di società
          </p>
        </div>
      </div>
    </div>
</template>

<script>
export default {
    name: 'ExperienceComp'
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.backgroundE{
  padding-top: 10%;
  padding-bottom: 2%;
  //border-top: 2px solid black;
  background-color: rgb(5, 5, 124);
  width: 100%;
  //height: 100vh;
  .containerE{
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
.backgroundE{
  padding-bottom: 5%;
  //border-top: 2px solid black;
  background-color: rgb(5, 5, 124);
  width: 100%;
  //height: 100vh;
  text-align: center;
  .containerE{
    padding-top: 2%;
    width: 70%;
    margin: auto;
    color: white;
    .title{
      font-size: 3rem;
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






























// Media-query tablet
@media screen and (min-width:481px) and (max-width:850px){
.backgroundE{
  padding-top: 10%;
  padding-bottom: 2%;
  //border-top: 2px solid black;
  background-color: rgb(5, 5, 124);
  width: 100%;
  //height: 100vh;
  .containerE{
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












