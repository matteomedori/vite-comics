<script>
import AppBlueComponent from "./AppBlueComponent.vue";
import AppMainContent from "./AppMainContent.vue";
import AppJumbotron from "./AppJumbotron.vue";

export default {
  name: "AppMain",
  components: {
    AppBlueComponent,
    AppMainContent,
    AppJumbotron,
  },
};
</script>

<template>
  <main>
    <AppJumbotron />
    <AppMainContent />
    <AppBlueComponent />
  </main>
</template>

<style lang="scss">
main {
  background-color: black;
}
</style>
