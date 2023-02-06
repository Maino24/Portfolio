<template>
    <div class="background">
        <div class="containerNP">
            <h1 class="name animated bounceInDown">I am Gabriele Mainetti</h1>
        <h1 class="profession animated bounceInDown">Junior Full Stack Web Developer</h1>
        </div>
        
        <!-- <ul>
            <li><button>About Me</button></li>
            <li><button>Skills</button></li>
            <li><button>Projects</button></li>
            <li><button>Resume</button></li>
            <li><button>Contacts</button></li>
        
        </ul>-->
        
    </div>
</template>

<script>
export default {
    name: 'HeaderComp',
}
</script>

<style lang="scss">
.background{
  background-color: #202123;
  width: 100vw;
  height: 100vh;
}
.containerNP{
    padding-top: 15%;
    width: 70%;
    margin: auto;
    
    .name{
    color: white;
    }

    .profession{
        color: white;
        
        }
}   

nav{
    display: flex;
   /* ul{
        display: flex;
        
        li{
        list-style: none;
        margin: auto;
        justify-content: space-around;
        }
    }*/
    
}

</style>