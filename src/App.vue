<template>
  <img src="./assets/icon.svg" alt="logo">
  
  <div class="box">
    
  
  
  <LogoIcon />
  <BackGround />
  

  <InPut />
  
    <CheckBox />

    
    <ButtonsUp />
  </div>
  
</template>

<script>

import LogoIcon from './components/Up/LogoIcon.vue'
import BackGround from './components/Up/BackGround.vue'

import InPut from './components/InPut.vue'


import ButtonsUp from './components/Middle/ButtonsUp.vue'




import CheckBox from './components/Middle/CheckBox.vue'



export default {
  name: 'App',
  components: {
    
    LogoIcon,
    BackGround,
    InPut,
    CheckBox,
    
    ButtonsUp,
    
  }
}
</script>

<style>
.box{
  display: flex;
  flex-direction: column;
  width: 100%;
  height: 100%;
  
  
}

  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700&display=swap');


</style>
