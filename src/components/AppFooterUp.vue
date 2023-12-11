<script>
export default {
  name: "AppFooterUp",
  data() {
    return {
      dcComics: [
        "Characters",
        "Comics",
        "Movies",
        "TV",
        "Games",
        "Videos",
        "News",
      ],
      shop: ["Shop DC", "Shop DC Collectables"],
      dc: [
        "Terms of Use",
        "Privacy policy(New)",
        "Ad Choises",
        "Advertising",
        "Jobs",
        "Subscriptons",
        "Talent Workshops",
        "CPSC Certificates",
        "Ratings",
        "Shop Help",
        "Contact Us",
      ],
      sites: ["DC", "MAD Magazine", "DC Kids", "DC Universe", "DC Power Visa"],
    };
  },
};
</script>

<template>
  <div class="footer-up">
    <div class="container">
      <div class="left">
        <div class="col">
          <h4>DC Comics</h4>
          <ul>
            <li v-for="link in dcComics">
              <a href="#">{{ link }}</a>
            </li>
          </ul>
          <h4>Shop</h4>
          <ul>
            <li v-for="link in shop">
              <a href="#">{{ link }}</a>
            </li>
          </ul>
        </div>
        <div class="col">
          <h4>DC</h4>
          <ul>
            <li v-for="link in dc">
              <a href="#">{{ link }}</a>
            </li>
          </ul>
        </div>
        <div class="col">
          <h4>Sites</h4>
          <ul>
            <li v-for="link in sites">
              <a href="#">{{ link }}</a>
            </li>
          </ul>
        </div>
      </div>

      <img src="/img/dc-logo-bg.png" alt="" />
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use "../assets/scss/partials/mixins" as *;
@use "../assets/scss/partials/variables" as *;

.footer-up {
  background-image: url(/img/footer-bg.jpg);
  color: white;
  .container {
    @include container;
    display: flex;
    justify-content: space-between;
    position: relative;

    .left {
      display: flex;
      padding: 40px 0 60px 0;

      .col {
        width: 140px;
      }

      ul {
        margin: 15px 0;

        li {
          margin-bottom: 4px;
          font-size: 12px;

          a {
            color: $links-color;
          }
        }
      }
    }

    img {
      overflow: hidden;
      position: absolute;
      right: 0;
      top: -100px;
    }
  }
}
</style>
