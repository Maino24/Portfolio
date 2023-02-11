<template>
    <div class="backgroundAM">
        <a href=""  name="AboutMe"></a>
        <div class="containerAM">   
            <h1 class="titleAM">Chi sono</h1>
            <div class="containerDown">
                <div class="containerImg">
                </div>
                <div class="containerParag">
                    <p>Sono molto appassionato di programmazione e mi
                        sono avvicinato ad essa durante il
                        miei studi superiori.
                        Dopo aver lavorato per un anno nel
                        settore economico, ho deciso di
                        riprendere gli studi con il corso da
                        Full Stack Web Developer di
                        Boolean.
                        Oggi sono uno sviluppatore web full
                        stack con molta voglia di lavorare e
                        imparare.
                    </p>
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
  border-top: 2px solid black;
  background-color: rgb(13, 13, 207);
  //width: 100vw;
  height: 100vh;
  .containerAM{
    padding-top: 2%;
    width: 70%;
    margin: auto;
    color: white;
    .titleAM{
        font-size: 4rem;
    }
    .containerDown{
        padding: 15% 0;
        display: flex;
        justify-content: space-between;
            .containerImg{
                width: calc(100% /2);
                height: 40vh;
                background-image: url("../assets/imgProfilo2Portfolio.png");
                background-size: contain,  cover;
                background-repeat: no-repeat;
            }    
            .containerParag{
                width: calc(100% / 2);
                p{
                    padding-top: 5%;
                    font-size: 150%;
                }
            }
        }
    }
  
}
</style>