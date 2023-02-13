<template>
    <div class="backgroundC">
      <div class="containerC">
        <h1 class="title">Contatti</h1>
        <ul>
          <li>
            <i class="fa-solid fa-house"></i><span>Sondrio, Lombardia Italia</span>
          </li>
          <li>
            <i class="fa-solid fa-envelope"></i><span>mg02.gabriele@gmail.com</span>
          </li>
          <li>
            <a href="https://www.linkedin.com/in/gabriele-mainetti/"><i class="fa-brands fa-linkedin"></i>https://www.linkedin.com/in/gabriele-mainetti</a>
          </li>
          <li>
            <a href="https://github.com/Maino24"><i class="fa-brands fa-github"></i>https://github.com/Maino24</a>
          </li>
        </ul>
      </div>
    </div>
</template>

<script>
export default {
    name: 'ContactsComp'
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.backgroundC{
  border-top: 2px solid black;
  background-color: rgb(13, 13, 207);
  //width: 100vw;
  height: 100vh;
  .containerC{
    padding-top: 2%;
    width: 70%;
    margin: auto;
    color: white;
    .title{
      font-size: 4rem;
    }
    li{
      list-style: none;
      padding-top: 5%;
      font-size: 2rem;
      
      i{
        padding-right: 3%;
        color: white;
      }

      a{
        color: white;
        text-decoration: none;
      }
    }
  }
}
</style>