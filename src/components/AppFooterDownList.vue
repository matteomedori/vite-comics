<script>
export default {
  name: "AppFooterDownList",
  data() {
    return {
      imagesUrl: [
        "/img/footer-facebook.png",
        "/img/footer-twitter.png",
        "/img/footer-youtube.png",
        "/img/footer-pinterest.png",
        "/img/footer-periscope.png",
      ],
    };
  },
};
</script>

<template>
  <ul>
    <li>Follow us</li>
    <li v-for="item in imagesUrl">
      <img :src="item" alt="" />
    </li>
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
