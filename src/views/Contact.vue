<template>
     <h1>Send me a message, I'd love to hear from you!</h1>
    <form ref="form" @submit.prevent="sendEmail">
      <label>Name</label> 
      <input type="text" name="user_name"> <br />
      <label>Email</label>
      <input type="email" name="user_email"> <br />
      <label>Message</label>
      <textarea name="message"></textarea> <br />
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