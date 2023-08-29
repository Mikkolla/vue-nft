<template>
    <div class="inpt">
      <div class="main-email">

        <div class="chk-title">Email</div>
        <input class="email" type="email" name="email" id="chk" placeholder="Your email.." > 
        <div class="email-icon"><HideIcon /></div>  
      </div>
      
      <div class="main-password">

        <div class="chk-password">Password</div>
        <input class="password" type="password" name="password" id="chk" placeholder="Your password..">
        <div class="password-icon"><CloseIcon /></div>
      </div>
        
       
   
      
    </div>
   
  </template>
  
  <script>
    import HideIcon from './Icons/HideIcon.vue'
    import CloseIcon from './Icons/CloseIcon.vue'
  export default {
    name: 'InPut',
    components:{
      HideIcon,
      CloseIcon,
    }
    

   
  }
  </script>
  
 
  <style scoped lang="scss">
  
  .inpt{
    display: flex;
    flex-direction: column;
    gap: 20px;
    margin-top: 90px;
    margin-left: 140px;



}

.chk-password{
  color: var(--secondary-color, #344054);

/* Text 2 */
font-family: Inter;
font-size: 14px;
font-style: normal;
font-weight: 500;
line-height: 20px; /* 142.857% */
margin-bottom: 8px;
}
.email {
  border-radius: 8px;
border: 1px solid var(--accent-1, #D0D5DD);
padding: 10px 14px;
position: relative;
width: 360px;
}

.chk-title{
  color: var(--secondary-color, #344054);

/* Text 2 */
font-family: Inter;
font-size: 14px;
font-style: normal;
font-weight: 500;
line-height: 20px; /* 142.857% */
margin-bottom: 8px;
}
.password {
  border-radius: 8px;
border: 1px solid var(--accent-1, #D0D5DD);
padding: 10px 14px;
width: 360px;

}
.email-icon{
position: absolute;
left: 33%;
bottom: 40%;
}

.password-icon{
  position: absolute;
left: 33.2%;
bottom: 28.7%;
}

  </style>
  