<template>
  <div class="flex justify-center items-center min-h-screen bg-gray-100 p-4">
    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
      <div class="flex flex-col space-y-6">
        <div class="flex space-x-6">
          <ResilienceCard />
          <GrowthCard />
        </div>
        <EngagementCard />
      </div>

      <div class="flex flex-col space-y-6">
        <GoalOrientationCard />
        <div class="flex space-x-6">
          <SelfBeliefCard />
          <VisioningCard />
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import ResilienceCard from './components/ResilienceCard.vue';
import GrowthCard from './components/GrowthCard.vue';
import EngagementCard from './components/EngagementCard.vue';
import VisioningCard from './components/VisioningCard.vue';
import GoalOrientationCard from './components/GoalOrientationCard.vue';
import SelfBeliefCard from './components/SelfBeliefCard.vue';

</script>
