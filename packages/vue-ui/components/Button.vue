<template>
    <button class="button" @click="handleClick">Click Me</button>
  </template>
  
  <script lang="ts">
  import Vue from "vue";
  
  export default Vue.extend({
    methods: {
      handleClick: () => {
        alert("Woooha!");
      },
    },
  });
  </script>
  
  <style scoped>
  .button {
    background-color: #3498db;
    color: #fff;
    border: none;
    padding: 10px 20px;
    font-size: 16px;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s ease-in-out;
  }
  
  .button:hover {
    background-color: #2980b9;
  }
  </style>
  