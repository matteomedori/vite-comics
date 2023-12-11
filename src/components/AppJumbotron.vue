<script>
import AppJumboButton from "./AppJumboButton.vue";
export default {
  name: "Jumbotron",
  components: {
    AppJumboButton,
  },
};
</script>

<template>
  <div class="jumbo">
    <div class="container">
      <AppJumboButton />
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use "../assets/scss/partials/variables" as *;
@use "../assets/scss/partials/mixins" as *;

.jumbo {
  height: 400px;
  background-image: url("/img/jumbotron.jpg");
  background-repeat: repeat;

  .container {
    @include container;
    position: relative;
    height: 100%;

    :deep(button) {
      position: absolute;
      bottom: -27px;
    }
  }
}
</style>
