<template>
    <div class="backgroundR">
        <div class="containerR">        
            <h1 class="title">Resu<span class="underline">me</span></h1>
            <div class="containerBottomR">
                <div class="singoleCard">
                    <div class="containerText1">
                        <h2 class="experience">Experience</h2> 
                        <div class="firstExperience">
                            <h3>Jr Full Stack Web Developer Trainee</h3>
                            <h4>Boolean Careers</h4>
                            <h4>Settembre 2022 - Marzo 2023 | 6 mesi</h4>
                            <p class="startParag">Sviluppo di progetti ispirati a web app esistenti come: Netflix,
                                Whatsapp Web, Spotify, Zoom, Zalando ... .
                            </p>
                            <p>Tutti i progetti svolti avevano una scadenza e questo mi ha permesso
                            di avvicinarmi a ciò che avviene effettivamente nel mondo del lavoro.
                            </p>
                        </div>
                        <div class="secondExperience">
                            <h3>Impiegato Contabile</h3>
                            <h4>Midac S.r.l.</h4>
                            <h4>Agosto 2021 - Agosto 2022| 1 anno</h4>
                            <p class="startParag">Impiegato contabile presso studio commercialista. Gestione
                                contabilità, mail, chiamate per un gruppo di società.
                            </p>
                        </div> 
                    </div>
                </div>
                <div class="singoleCard2">
                    <div class="containerText2">
                        <h3 class="education">Education</h3>
                        <div class="firstEducation">
                            <h3>Boolean Careers</h3>
                            <h4>Master Sviluppatore Web Full Stack</h4>
                            <h4>Settembre 2022 - Febbraio 2023 | 6 mesi</h4>
                            <p class="startParag">Corso completo e intensivo di 700 ore, pratiche e teoriche, sullo
                                sviluppo web lato Front-End e Back-End.
                            </p>
                            <p>Le tecnologie studiate e utilizzate sono: Html, Css, Sass, Bootstrap,
                                Javascript, VueJS, Axios, MySQL, PHP, Laravel.
                            </p>
                        </div>
                        <div class="secondEducation">
                            <h3>IS Saraceno-Romegialli</h3>
                            <h4>IS Saraceno-Romegialli
                                Istituto tecnico settore economico - Indirizzo
                                "Amministrazione, Finanza e Marketing" - Articolazione
                                "Sistemi Informativi Aziendali"
                            </h4>
                            <h4>Settembre 2018 - Giugno 2021</h4>
                            <p class="startParag">Tecnologie studiate ed utilizzate: Html, Css, Visual Basic                            </p>
                        </div>
                    </div>
                </div>
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
                            <img class="logo" src="../assets/PHP.png" alt="logo">
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
  //border-top: 10px solid white;
  background-color: rgb(13, 13, 207);
  width: 100vw;
  height: 100vh;
  .containerR{
    width: 70%;
    margin: auto;
    padding: 5% 0;
    .title{
        font-size: 4rem;
        color: white;
        .underline{
            border-bottom: 5px solid black;
        }
    }
    .containerBottomR{
        padding-top: 10vh;
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
                    padding: 4% 0;
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
            height: 50vh;
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
            height: 50vh;
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
                            margin: 5% 5%;
                        }
                    }

                }
        }
    }
  }
  
}
</style>