<template>
  <div class="flex justify-center w-screen">
    <div class="flex-col">
      <div class="flex">
        <ResilienceCard />
        <GrowthCard />
      </div>
      <EngagementCard />
    </div>
      


    <GoalOrientationCard />
    <div class="flex-col">
      <SelfBeliefCard />
      <VisioningCard /> 
    </div>
  </div>
</template>

<script setup>
import ResilienceCard from './ResilienceCard.vue';
import GrowthCard from './GrowthCard.vue';
import EngagementCard from './EngagementCard.vue';
import VisioningCard from './VisioningCard.vue';
import GoalOrientationCard from './GoalOrientationCard.vue';
import SelfBeliefCard from './SelfBeliefCard.vue';

</script>
