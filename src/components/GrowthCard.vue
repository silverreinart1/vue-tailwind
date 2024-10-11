<template>
  <div class="card growth">
    <h3>Growth</h3>
    <p>Expand your skills and knowledge...</p>
    <div class="rating">
      <span class="stars">★★★☆☆</span>
      <span class="progress">60%</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'GrowthCard',
};
</script>

<style scoped>
.card {
  background-color: #22c55e;
  color: white;
  padding: 16px;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  height: 100%;
}
</style>
