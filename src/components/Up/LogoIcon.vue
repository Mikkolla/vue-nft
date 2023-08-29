<template>
  <div class="wrapper"> 
    <div class="wrapper__title">
      NFT Access
    </div>
    <div class="wrapper__decs">
      Please fill your detail to access your account.
    </div>
   
  </div>  

</template>

<script>
export default {
  name: 'LogoIcon',
  props: {
    msg: String
  }
}
</script>


<style scoped lang="scss">

.wrapper {
 display: flex;
 
 justify-content: start;
 
 flex-direction: column;

 margin-top: 180px;

 margin-left: 140px;

&__title {
  color: #344054;

/* Headline */
font-family: Inter;
font-size: 40px;
font-style: normal;
font-weight: 700;
line-height: normal;
letter-spacing: 0.4px;
text-transform: capitalize;
}

&__decs {
  color: #667085;

/* Text 1 */
font-family: Inter;
font-size: 16px;
font-style: normal;
font-weight: 400;
line-height: 24px; /* 150% */
}
}

</style>
