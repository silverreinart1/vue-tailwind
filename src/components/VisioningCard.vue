<template>
  <div class="card visioning">
    <h3>Visioning</h3>
    <p>Learn how to strategize and formulate your own goals...</p>
    <div class="rating">
      <span class="stars">★★★★★</span>
      <span class="progress">100%</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'VisioningCard',
};
</script>

<style scoped>
.card {
  background-color: #9333ea;
  color: white;
  padding: 16px;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  height: 100%;
}
.large {
  grid-column: span 2;
}
</style>
