<template>
     <h1 id="contact">Send me a message. I'd love to hear from you!</h1>
    <form ref="form" @submit.prevent="sendEmail">
      <input placeholder="Your Name" type="text" name="user_name"> 
      <input placeholder="Your Email" type="email" name="user_email"> <br />
      <textarea placeholder="Your Message" name="message"></textarea> <br />
      <input id="send" type="submit" value="Send">
    </form>
  </template>


<style>
#contact {
    text-align: center;
    margin-top: 10vh;
    font-size: 5vh
}

form {
    color: white;
    font-family: 'Righteous', cursive;
    text-align: center;
}

input {
    width: 50vh;
    height: 10vh;
    text-align: center;
    font-family: 'Righteous', cursive;
    font-size: 25px;
    box-shadow: white 1px 0 30px;
    
}

textarea {
    width: 100vh;
    height: 30vh;
    border-width: 5px;
    border-color: white;
    color: white;
    background-color: black;
    font-size: larger;
    box-shadow: white 1px 0 30px;
}

#send {
    width: 102vh;
    border-width: 10px;
    border-color: #0677a1;
    background-color: #0677a1;
    color: white;
    font-size: 40px;
}
</style>
  
  <script>
  import emailjs from '@emailjs/browser';
  
  export default {
    methods: {
      sendEmail() {
        emailjs.sendForm('service_bvk1rmn', 'template_xly6jps', this.$refs.form, 'TbRiNitiwUZuV34HP')
          .then((result) => {
              console.log('SUCCESS!', result.text);
          }, (error) => {
              console.log('FAILED...', error.text);
          });
      }
    }
  }
  </script>