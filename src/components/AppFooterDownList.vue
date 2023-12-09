<script>
export default {
  name: "AppFooterDownList",
};
</script>

<template>
  <ul>
    <li>Follow us</li>
    <li><img src="../../public/img/footer-facebook.png" alt="" /></li>
    <li><img src="../../public/img/footer-twitter.png" alt="" /></li>
    <li><img src="../../public/img/footer-youtube.png" alt="" /></li>
    <li><img src="../../public/img/footer-pinterest.png" alt="" /></li>
    <li><img src="../../public/img/footer-periscope.png" alt="" /></li>
  </ul>
</template>

<style lang="scss" scoped>
ul {
  list-style-type: none;
  display: flex;
  align-items: center;
  gap: 20px;

  li:first-child {
    color: #0282f9;
    text-transform: uppercase;
  }
}
</style>
