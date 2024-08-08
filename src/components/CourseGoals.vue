<template>
  <ul>
    <li v-for="goal in goals" :key="goal">
      <!-- {{ goal }} we want to send the goal to app component-->
      <slot :item="goal" anotherProp="..."></slot>
    </li>
  </ul>
</template>

<script>
export default {
  data() {
    return {
      goals: ["finish the course", "Learn Vue"],
    };
  },
};
</script>
<style scoped></style>
