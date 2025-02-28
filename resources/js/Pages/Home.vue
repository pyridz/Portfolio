<template>
    <div class="home">
      <h1>Hi, I’m [Your Name], a web developer specializing in Laravel and Vue.js.</h1>
      <a href="/projects" class="cta-button">View My Work</a>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Home',
  };
  </script>
  
  <style scoped>
  .home {
    text-align: center;
    padding: 2rem;
  }
  .cta-button {
    display: inline-block;
    margin-top: 1rem;
    padding: 0.5rem 1rem;
    background-color: #3b82f6;
    color: white;
    text-decoration: none;
    border-radius: 0.25rem;
  }
  </style>