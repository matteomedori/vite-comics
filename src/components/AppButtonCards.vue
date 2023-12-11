<!-- button under cards -->
<script>
export default {
  name: "CardsBtn",
  props: ["btnText"],
};
</script>

<template>
  <button>{{ btnText }}</button>
</template>

<style lang="scss" scoped>
@use "../assets/scss/partials/variables" as *;

button {
  background-color: $primary-blue;
  padding: 10px 60px;
  margin-bottom: 20px;
  font-weight: 600;
  letter-spacing: -1px;
}
</style>
