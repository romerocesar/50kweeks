<template>
  <div class="grid-container">
    <div v-for="row in 100" :key="row" class="grid-row">
      <div v-for="col in 52" :key="col" class="grid-card">
        <!-- Your card content here -->
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'GridComponent',
  // Any data, methods, etc.
}
</script>

<style scoped>
.grid-container {
  display: flex;
  flex-direction: column;
}
.grid-row {
  display: flex;
}
.grid-card {
  width: 20px; /* Adjust as per your requirement */
  height: 20px; /* Adjust as per your requirement */
  border: 1px solid #ccc;
  /* Additional styling */
}
</style>
