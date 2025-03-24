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
  text-align: center;
}

body {
  display: grid;
  place-items: center; /* Center the header both vertically and horizontally */
  height: 100vh; /* Full viewport height */
  margin: 0; /* Remove default margins */
}

.logo {
  max-width: 200px; /* Adjust logo size */
  margin-right: 2rem; /* Add spacing between logo and text */
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