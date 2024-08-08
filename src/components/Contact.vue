<template>
  <div class="contact-form">
   
 <div class="txt-center title-port">
    <img src="../assets/contact-text.svg" class="">
 </div>
    <div class="form-bind">
      <form>
      <div>
        <label for="subject">Subject:</label>
        <input type="text" id="subject"  required>
      </div>
      <div class="flex">
<div class="w-50">
        <label for="firstName">First Name:</label>
        <input type="text" id="firstName"  required>
      </div>
      <div class="w-50">
        <label for="lastName">Last Name:</label>
        <input type="text" id="lastName"required>
      </div>
      </div>
      
      <div>
        <label for="email">Email:</label>
        <input type="email" id="email"  required>
      </div>
      <div>
        <label for="message">Message:</label>
        <textarea id="message"  required></textarea>
      </div>
      <button type="submit">Submit</button>
    </form>
    </div>
    
  </div>
</template>

  <script>
  export default {
    name: 'Contact',
  };
  </script>
  
  <style scoped>
  </style>
  
  