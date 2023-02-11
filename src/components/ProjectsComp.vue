<template>
    <div class="backgroundP">
        <a href="" name="projects"></a>
        <div class="containerP">
           <h1 class="title">My Projects</h1>
           
            
                  <!--      <img src="../assets/Zalando.png" class="d-block w-100" alt="...">
                    </div>
                    <div class="carousel-item">
                        <img src="../assets/Netflix.png" class="d-block w-100" alt="...">
                    </div>
                    <div class="carousel-item">
                        <img src="../assets/Whatsapp.png" class="d-block w-100" alt="...">
                    </div>
                    <div class="carousel-item">
                        <img src="../assets/Dropbox.png" class="d-block w-100" alt="...">
                    </div>
                    <div class="carousel-item">
                        <img src="../assets/discord.png" class="d-block w-100" alt="...">-->
                <div id="carouselExampleDark" class="carousel carousel-dark slide">
                <div class="carousel-indicators">
                    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1" aria-label="Slide 2"></button>
                    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="2" aria-label="Slide 3"></button>
                    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="3" aria-label="Slide 4"></button>
                    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="4" aria-label="Slide 5"></button>
                </div>
                <div class="carousel-inner">
                    <div class="carousel-item active" data-bs-interval="10000">
                        <img src="../assets/Zalando.png" class="imgZ d-block w-100" alt="...">
                        <div class="carousel-caption d-none d-md-block"></div>
                    </div>
                    <div class="carousel-item" data-bs-interval="2000">
                        <img src="../assets/Netflix.png" class="imgN d-block w-100" alt="...">
                        <div class="carousel-caption d-none d-md-block"></div>
                    </div>
                    <div class="carousel-item">
                        <img src="../assets/Whatsapp.png" class="imgW d-block w-100" alt="...">
                        <div class="carousel-caption d-none d-md-block"></div>
                    </div>
                    <div class="carousel-item">
                        <img src="../assets/discord.png" class="imgD d-block w-100" alt="...">
                        <div class="carousel-caption d-none d-md-block"></div>
                    </div>
                    <div class="carousel-item">
                        <img src="../assets/Dropbox.png" class="imgDrop d-block w-100" alt="...">
                        <div class="carousel-caption d-none d-md-block"></div>
                    </div>
                </div>
                <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Previous</span>
                </button>
                <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Next</span>
                </button>
                </div>
        </div>
    </div>


</template>

<script>


export default {
    name: 'ProjectsComp',
    
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.backgroundP{
  border-top: 2px solid black;
  background-color: rgb(13, 13, 207);
  //width: 100vw;
  height: 100vh;
  .containerP{
    width: 70%;
    margin: auto;
    padding: 2% 0;
    
    .title{
        font-size: 4rem;
        color: white;
        padding-bottom: 5%;
    }
        
    
  }
}
</style>