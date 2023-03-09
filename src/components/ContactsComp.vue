<template>
    <div class="backgroundC">
      <a href="" name="contatti"></a>
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
            <i class="fa-solid fa-phone"></i><span>+39 347 024 2909</span>
          </li>
          <li>
            <a href="https://www.linkedin.com/in/gabriele-mainetti/"><i class="fa-brands fa-linkedin"></i>https://www.linkedin.com</a>
          </li>
          <li>
            <a href="https://github.com/Maino24"><i class="fa-brands fa-github"></i>https://github.com/Maino24</a>
          </li>
        </ul>
      </div>
    </div>
</template>

<script>

import emailjs from '@emailjs/browser';


export default {
    name: 'ContactsComp',
    methods: {
        sendEmail() {
          emailjs.sendForm('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', this.$refs.form, 'YOUR_PUBLIC_KEY')
            .then((result) => {
                console.log('SUCCESS!', result.text);
            }, (error) => {
                console.log('FAILED...', error.text);
            });
        }
      }
  };
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.backgroundC{
  //border-top: 2px solid black;
  background-color: rgb(5, 5, 124);
  width: 100%;
  //height: 100vh;
  padding-top: 8%;
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























// Media-query mobile
@media screen and (max-width:480px){
.backgroundC{
  //border-top: 2px solid black;
  background-color: rgb(5, 5, 124);
  width: 100%;
  height: 50vh;
  .containerC{
    padding-top: 2%;
    width: 80%;
    margin: auto;
    color: white;
    .title{
      font-size: 3rem;
      text-align: center;
    }
    li{
      list-style: none;
      //padding-top: 5%;
      font-size: 0.9rem;
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
}
}






















// Media-query tablet
@media screen and (min-width:481px) and (max-width:850px){
  .backgroundC{
  //border-top: 2px solid black;
  background-color: rgb(5, 5, 124);
  width: 100%;
  height: 80vh;
  padding-top: 8%;
  .containerC{
    padding-top: 2%;
    width: 80%;
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
}
</style>