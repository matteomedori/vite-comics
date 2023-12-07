<script>
export default {
  name: "AppMain",
};
</script>

<template>
  <main>
    <div>&rarr;Content goes here&larr;</div>
  </main>
</template>

<style lang="scss">
@use "../styles/general.scss" as *;

main {
  background-color: black;
  color: white;
  padding: 50px 0;

  div {
    @include container;
  }
}
</style>
