<template>
     <h1>Send me a message, I'd love to hear from you!</h1>
    <form ref="form" @submit.prevent="sendEmail">
      <input placeholder="Your Name" type="text" name="user_name"> <br />
      <input placeholder="Your Email" type="email" name="user_email"> <br />
      <textarea placeholder="Your Message" name="message"></textarea> <br />
      <input type="submit" value="Send">
    </form>
  </template>


<style>
form {
    color: white;
    font-family: 'Righteous', cursive;
    text-align: center;
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