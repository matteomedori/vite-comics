<script>
export default {
  name: "JumboBtn",
};
</script>

<template>
  <button>current series</button>
</template>

<style lang="scss" scoped>
@use "../assets/scss/partials/variables" as *;

button {
  padding: 15px 30px;
  background-color: $primary-blue;
  color: white;
  font-weight: 700;
  font-size: 28px;
}
</style>
