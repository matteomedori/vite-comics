<script>
import AppLogo from "./AppLogo.vue";
import AppHeaderList from "./AppHeaderList.vue";

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
    <AppLogo />
    <AppHeaderList />
  </header>
</template>

<style lang="scss">
header {
  height: 120px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
</style>
