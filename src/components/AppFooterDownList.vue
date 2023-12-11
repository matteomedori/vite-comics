<script>
export default {
  name: "AppFooterDownList",
};
</script>

<template>
  <ul>
    <li>Follow us</li>
    <li><img src="../assets/img/footer-facebook.png" alt="" /></li>
    <li><img src="../assets/img/footer-twitter.png" alt="" /></li>
    <li><img src="../assets/img/footer-youtube.png" alt="" /></li>
    <li><img src="../assets/img/footer-pinterest.png" alt="" /></li>
    <li><img src="../assets/img/footer-periscope.png" alt="" /></li>
  </ul>
</template>

<style lang="scss" scoped>
@use "../assets/scss/partials/variables" as *;

ul {
  list-style-type: none;
  display: flex;
  align-items: center;
  gap: 20px;

  li:first-child {
    color: $primary-blue;
    text-transform: uppercase;
    font-weight: 600;
    font-size: 18px;
    letter-spacing: -1px;
  }
}
</style>
