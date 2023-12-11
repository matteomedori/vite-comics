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
@use "../styles/partials/variables" as *;

button {
  all: unset;
  background-color: $primary-blue;
  padding: 10px 60px;
  margin-bottom: 20px;
  text-transform: uppercase;
  font-weight: 600;
  letter-spacing: -1px;
}
</style>
