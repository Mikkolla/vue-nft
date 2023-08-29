<template>
    <div class="chk">
        <div class="chk-box">
            <input class="checkbox" type="checkbox">
            <div class="chk-title">Remember me</div>
        </div>


        <div class="chk-forgott">
            <div class="chk-title">
                <a class="link" href="/">Forgot Password?</a>
            </div>
        </div>
        
        
  
  
    </div>
  </template>
  
  <script>
  export default {
    name: 'CheckBox',
    props: {
      msg: String
    }
  }
  </script>
  
  
  <style scoped>
.chk {
    display: flex;
    gap: 100px;
    margin-left: 140px;
    margin-top: 22px;
}
.link{
    color: var(--primary-color, #5429FF);

/* Text 2 */
font-family: Inter;
font-size: 14px;
font-style: normal;
font-weight: 500;
line-height: 20px; /* 142.857% */
text-decoration: none;
margin-left: 43px;
}

.chk-box {
display: flex;
gap: 8px;
}

.chk-title 
{
    color: var(--secondary-color, #344054);

/* Text 2 */
font-family: Inter;
font-size: 14px;
font-style: normal;
font-weight: 500;
line-height: 20px; /* 142.857% */
    
}



.checkbox{
   
width: 16px;
height: 16px;
}

  
  </style>
  