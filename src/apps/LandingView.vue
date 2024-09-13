<template>
  <div id="app">
    <nav class="navbar">
      <h1>Assured Harvest</h1>
    </nav>
    <main>
      <!-- Your main content goes here -->
    </main>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style scoped>
/* Styles for the navbar */
.navbar {
  background-color: #4CAF50; /* Green background */
  color: white; /* White text color */
  padding: 15px; /* Padding around the content */
  text-align: center; /* Center the text */
  position: fixed; /* Fixed position at the top */
  width: 100%; /* Full width */
  top: 0; /* Align to the top */
  left: 0; /* Align to the left */
  z-index: 1000; /* Ensure it stays on top */
}

h1 {
  margin: 0;
  font-size: 24px; /* Adjust font size as needed */
}

/* Ensure main content starts below the navbar */
main {
  padding-top: 60px; /* Adjust based on the height of your navbar */
}
</style>
