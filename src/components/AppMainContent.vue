<script>
export default {
  name: "AppMainContent",
};
</script>

<template>
  <div class="content">&rarr;Content goes here&larr;</div>
</template>

<style lang="scss" scoped>
@use "../styles/general.scss" as *;

.content {
  @include container;
  padding: 50px 0;
  color: white;
}
</style>
