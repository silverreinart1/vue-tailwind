<template>
  <div class="card self-belief">
    <h3>Self-Belief</h3>
    <div class="rating">
      <span class="stars">★★★☆☆</span>
      <span class="progress">60%</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'SelfBeliefCard',
};
</script>

<style scoped>
.card {
  background-color: #ec4899;
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
