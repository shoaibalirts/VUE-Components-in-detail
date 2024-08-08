<template>
  <ul>
    <li v-for="goal in goals" key="goal">
      {{ goal }}
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
