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
      <a href="#">
        <img :src="item" alt="" />
      </a>
    </li>
  </ul>
</template>

<style lang="scss" scoped>
@use "../assets/scss/partials/variables" as *;

ul {
  display: flex;
  align-items: center;
  gap: 20px;

  li:first-child {
    color: $primary-blue;
    text-transform: uppercase;
    font-weight: 700;
    font-size: 21px;
    letter-spacing: -2px;
  }
}
</style>
