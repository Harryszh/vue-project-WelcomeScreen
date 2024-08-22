<template>
    <div id="app">
      <WelcomeScreen />
      <ScreenFooter />
    </div>
  </template>
  
  <script>
  import WelcomeScreen from '@/components/WelcomeScren.vue';
  import ScreenFooter from '@/components/ScreenFooter.vue'; 
  
  export default {
    name: 'App',
    components: {
      WelcomeScreen,
      ScreenFooter
    }
  }
  </script>
  
  <style>
  
  #app {
    display: flex;
    flex-direction: column;
    min-height: 100vh; 
  }
  </style>
  