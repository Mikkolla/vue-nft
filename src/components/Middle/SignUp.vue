<template>
   <div></div>
      <!-- ICON -->
        <!-- <a class="blue-link" href="/">Sign in </a> -->
  
    
  </template>
  
  <script>
  export default {
    name: 'SignUp',
    props: {
      msg: String
    }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
  .blue {

    border-radius: 8px;
background: var(--primary-color, #5429FF);


}

.blue-link{


  border-radius: 8px;
background: var(--primary-color, #5429FF); 
color: #FFF;
font-family: Inter;
font-size: 16px;
font-style: normal;
font-weight: 500;
line-height: 20px; /* 125% */
text-decoration: none;

text-align: center;
margin-left: 140px;



width: 380px;
height: 44px;

display: inline-flex;
align-items: center;
justify-content: center;



}


  </style>
  