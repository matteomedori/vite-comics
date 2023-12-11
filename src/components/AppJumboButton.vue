<script>
export default {
  name: "JumboBtn",
};
</script>

<template>
  <button>current series</button>
</template>

<style lang="scss" scoped>
@use "../styles/partials/variables" as *;

button {
  all: unset;
  padding: 15px 30px;
  background-color: $primary-blue;
  color: white;
  text-transform: uppercase;
  font-weight: 600;
  font-size: 22px;
}
</style>
