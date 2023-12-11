<!-- sign up button  -->
<script>
export default {
  name: "FooterBtn",
};
</script>

<template>
  <button>Sign up now!</button>
</template>

<style lang="scss" scoped>
@use "../assets/scss/partials/variables" as *;

button {
  padding: 15px;
  border: 2px solid $primary-blue;
  color: white;
  font-weight: 600;
}
</style>
