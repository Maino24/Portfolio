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
        
            <h1 class="name animated bounceInDown">I'm Gabriele Mainetti</h1>
            <h1 class="profession animated bounceInDown">Junior Full Stack Web Developer</h1>
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
}

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

    .name{
        padding-top: 15%;
        color: white;
        font-size: 5rem;
        box-shadow: 10px;
    }

    .profession{
        color: white;
        font-size: 4rem;
        }
   
}


</style>