<script>
import AppFooterUp from "./AppFooterUp.vue";
import AppFooterDown from "./AppFooterDown.vue";

export default {
  name: "AppFooter",
  components: {
    AppFooterUp,
    AppFooterDown,
  },
};
</script>

<template>
  <footer>
    <AppFooterUp />
    <AppFooterDown />
  </footer>
</template>

<style></style>
