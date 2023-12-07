<script>
export default {
  name: "AppBlueComponent",
};
</script>

<template>
  <div class="blue-component">
    <ul>
      <li>prova</li>
      <li>prova</li>
      <li>prova</li>
      <li>prova</li>
    </ul>
  </div>
</template>

<style lang="scss" scoped>
@use "../styles/general.scss" as *;

.blue-component {
  background-color: #0282f9;

  ul {
    @include container;
    display: flex;
    list-style: none;
    color: white;
    justify-content: space-around;
    padding: 50px 0;
  }
}
</style>
