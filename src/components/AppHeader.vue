<script>
import AppLogo from "./AppLogo.vue";
import AppHeaderList from "./appheaderlist.vue";

export default {
  name: "AppHeader",
  components: {
    AppLogo,
    AppHeaderList,
  },
};
</script>

<template>
  <header>
    <div class="navbar">
      <AppLogo />
      <AppHeaderList />
    </div>
  </header>
</template>

<style lang="scss">
@use "../assets/scss/partials/mixins" as *;

header {
  .navbar {
    @include container;
    height: 120px;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
}
</style>
