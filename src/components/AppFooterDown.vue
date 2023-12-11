<script>
import AppButtonFooter from "./AppButtonFooter.vue";
import AppFooterDownList from "./AppFooterDownList.vue";

export default {
  name: "AppFooterDown",
  components: {
    AppButtonFooter,
    AppFooterDownList,
  },
};
</script>

<template>
  <div class="footer-down">
    <div class="container">
      <AppButtonFooter />
      <AppFooterDownList />
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use "../styles/general.scss" as *;
@use "../styles/partials/variables" as *;

.footer-down {
  background-color: $footer-bg;
  padding: 30px 0;
  position: relative;

  .container {
    @include container;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
}
</style>
