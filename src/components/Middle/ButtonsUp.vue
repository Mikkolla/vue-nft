<template>
    <div class="buttons">
        <div class="buttonblue">
            <a class="blue-link" href="/">Sign in </a>
        </div>

      <div class="buttonwhite">
        <a class="white-link" href="/">Sign in with Google</a>
      </div>

      <div class="qust">
        Don’t have an account?  <a class="qust-link" href="/">Sign up</a>
        
      </div>
        
        
      
  
    </div>

    <div class="end">@CreatedbyNAMDesign</div>

  </template>
  
  <script>
  export default {
    name: 'ButtonsUp',
    props: {
      msg: String
    }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>

  .buttons{
    display: inline-flex;
    flex-direction: column;
    gap: 16px;
    margin-top: 32px;
  }
 .white-link{
    color: var(--secondary-color, #344054);
font-family: Inter;
font-size: 16px;
font-style: normal;
font-weight: 500;
line-height: 20px; /* 125% */
text-decoration: none;


display: inline-flex;
align-items: center;
justify-content: center;

text-align: center;
margin-left: 140px;

border-radius: 8px;
border: 1px solid var(--accent-1, #D0D5DD);

margin-left: 140px;

width: 380px;
height: 44px;
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

.qust{
    color: var(--secondary-color, #344054);

font-family: Inter;
font-size: 14px;

font-weight: 400;
margin-left: 200px;

}

.qust-link{
    color: var(--primary-color, #5429FF);

font-family: Inter;
font-size: 14px;

font-weight: 600;
text-decoration: none;
}

.end{
    color: var(--accent-2, #667085);
font-family: Inter;
font-size: 16px;
font-style: italic;
font-weight: 400;
margin-top: 160px;
}
  
  </style>
  