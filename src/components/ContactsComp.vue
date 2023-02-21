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
      <form ref="form" @submit.prevent="sendEmail">
        <label>Name</label>
        <input type="text" name="user_name">
        <label>Email</label>
        <input type="email" name="user_email">
        <label>Message</label>
        <textarea name="message"></textarea>
        <input type="submit" value="Send">
    </form>
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
  border-top: 2px solid black;
  background-color: rgb(5, 5, 124);
  //width: 100vw;
  //height: 100vh;
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