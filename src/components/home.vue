<template>
    <div>
      <h1>Welcome to the Bank Account Management System</h1>
      <button @click="goToAccounts">Go to Accounts</button>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Home',
    methods: {
      goToAccounts() {
        this.$router.push('/accounts');
      }
    }
  }
  </script>
  
  <style scoped>
  /* Add your styles here if needed */
  </style>
  