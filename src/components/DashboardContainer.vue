<template>
    <div class="background"></div>
  </template>
  
  <script>
  export default {
    name: 'DashboardContainer',
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
  .background {
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    /* background-image: url('../assets/bg.jpg'); */
    /* background-size: cover;
    background-position: 0 30%;
    background-repeat: no-repeat; */
    background-color: bisque;
  }

  /* .background::after {
    content: '';
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    background-color: rgba(255, 255, 255, 0.85);
    background-color: rgba(0, 0, 0, 0.85);
  } */
  </style>
  