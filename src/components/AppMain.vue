<script>
import AppBlueComponent from "./AppBlueComponent.vue";
import AppMainContent from "./AppMainContent.vue";

export default {
  name: "AppMain",
  components: {
    AppBlueComponent,
    AppMainContent,
  },
};
</script>

<template>
  <main>
    <AppMainContent />
    <AppBlueComponent />
  </main>
</template>

<style lang="scss">
main {
  background-color: black;
}
</style>
