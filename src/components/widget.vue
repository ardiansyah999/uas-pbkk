<template>
    <div class="widget">
      <h2>{{ title }}</h2>
      <p>{{ message }}</p>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        title: 'Widget Title',
        message: 'Hello, Saya Muhammad Ardiansyah, 213510595. ini merupakan project sederhana saya mengenai widget',
        
      };
    },
  };
  </script>
  
  <style scoped>
  .widget {
    border: 1px solid #ccc;
    padding: 20px;
    margin-bottom: 20px;
  }
  </style>
  