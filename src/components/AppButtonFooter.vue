<script>
export default {
  name: "AppButtonFooter",
};
</script>

<template>
  <button>Sign up now!</button>
</template>

<style lang="scss" scoped>
@use "../assets/scss/partials/variables" as *;

button {
  all: unset;
  padding: 15px;
  border: 2px solid $primary-blue;
  text-transform: uppercase;
  color: white;
  font-weight: 600;
}
</style>
