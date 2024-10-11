<template>
  <div class="card goal-orientation">
    <h3>Goal Orientation</h3>
    <div class="rating">
      <span class="stars">★★★☆☆</span>
      <span class="progress">60%</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'GoalOrientationCard',
};
</script>

<style scoped>
.card {
  background-color: #fdba74;
  color: white;
  padding: 16px;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  height: 100%;
}
</style>
