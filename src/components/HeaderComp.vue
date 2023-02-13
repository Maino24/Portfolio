<template>
    <div class="background">
        <div class="containerNP">
            <ul class="nav animated bounceInDown">
                <li><a href="#AboutMe">About Me</a></li>
                <li><a href="">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#resume">Resume</a></li>
                <li><a href="#contacts">Contacts</a></li>
            </ul>
            <div class="nameImg animated bounceInDown">
                <div class="containerName">
                    <h1 class="name">I'm Gabriele Mainetti</h1>
                    <h1 class="profession">Junior Full Stack Web Developer</h1>
                </div>
                <div class="containerImg">
                    <img src="../assets/pc.webp" alt="">
                </div>
            </div>
        </div>
        <div class="contacts animated bounceInDown">
            <div class="contactsFirst">
                <li>
                    <span><i class="fa-solid fa-house"></i>Sondrio, Lombardia Italia</span>
                </li>
                <li>
                    <span><i class="fa-solid fa-envelope"></i>mg02.gabriele@gmail.com</span>
                </li>
            </div>
            <div class="contactsSecond">
                <li>
                    <a href="https://www.linkedin.com/in/gabriele-mainetti/"><i class="fa-brands fa-linkedin"></i>https://www.linkedin.com/in/gabriele-mainetti</a>
                </li>
                <li>
                    <a href="https://github.com/Maino24"><i class="fa-brands fa-github"></i>https://github.com/Maino24</a>
                </li>
            </div>
        </div>
        
        
        
    </div>
</template>

<script>
export default {
    name: 'HeaderComp',
}
</script>

<style lang="scss">
.background{
  background-color: rgb(13, 13, 207);
  //width: 100vw;
  height: 100vh;


.containerNP{
    width: 70%;
    margin: auto;

    .nav{
    display: flex;
    margin: auto;
    list-style: none;
    justify-content: space-between;
    padding-top: 5%;
    font-size: 2rem;
    color: white;
    a{
        text-decoration: none;
        color: white;
    }
    a:hover{
        font-size: 2.5rem;
        border-bottom: 2px solid black;
    }
    }
    .nameImg{
        display: flex;
        //margin: auto;
        justify-content: space-between;
        padding-top: 7%;
        .containerName{
            flex-basis: 70%;
            .name{
            //padding-top: 15%;
            color: white;
            font-size: 4rem;
            box-shadow: 10px;
            }

            .profession{
                color: white;
                font-size: 3rem;
            }
        }
        .containerImg{
            flex-basis: 30%;
            img{
                width: 80%
            }
        }
       
    }
    
}
    .contacts{
        width: 70%;
        margin: auto;
        //border: 1.5px solid white;
        display: flex;
        justify-content: space-between;
        margin-top: 5%;
        .contactsFirst{
            flex-basis: 50%;
            color: white;
            li{
            list-style: none;
            //padding-top: 5%;
            font-size: 1.5rem;
            padding-top: 10%;
                span{
                    text-decoration: none;
                    color: white;
                    i{
                        margin-right: 3%;
                        color: white;
                    }
                }     
            }
        }
        .contactsSecond{
            flex-basis: 50%;
            color: white;
            li{
            list-style: none;
            //padding-top: 5%;
            font-size: 1.5rem;
            padding-top: 10%;
                a{
                    text-decoration: none;
                    color: white;
                    i{
                        margin-right: 3%;
                        color: white;
                    }
                }
            }
        }
    }
}

</style>