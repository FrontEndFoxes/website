<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <img alt="Vue Vixens logo" class="logo" src="./assets/logo.png" />

    <div class="wrapper">
      <HelloWorld msg="Thank you!" />
    </div>


  </header>
</template>

<style scoped>
header {
  display: flex;
  flex-direction: row; /* Arrange items side by side */
  align-items: center; /* Vertically center items */
  justify-content: center; /* Horizontally center items */
  height: 100vh; /* Full viewport height */
  width: 100%; /* Full width */
  text-align: center;
  margin: 0; /* Remove default margins */
}

.logo {
  max-width: 200px; /* Adjust logo size */
  margin-right: 2rem; /* Add spacing between logo and text */
}

.wrapper {
  display: flex;
  flex-direction: column; /* Stack text vertically */
  align-items: flex-start; /* Align text to the left */
}

/* Mobile styles */
@media (max-width: 768px) {
  header {
    flex-direction: column; /* Stack logo and text vertically */
  }

  .logo {
    margin-right: 0; /* Remove right margin */
    margin-bottom: 1rem; /* Add spacing below the logo */
  }

  .wrapper {
    align-items: center; /* Center text on mobile */
  }
}
</style>