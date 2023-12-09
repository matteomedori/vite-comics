<script>
export default {
  name: "AppBlueComponent",
  data() {
    return {
      links: [
        {
          url: "../../public/img/buy-comics-digital-comics.png",
          name: "digital comics",
        },
        {
          url: "../../public/img/buy-comics-merchandise.png",
          name: "dc merchandise",
        },
        {
          url: "../../public/img/buy-comics-subscriptions.png",
          name: "subscription",
        },
        {
          url: "../../public/img/buy-comics-shop-locator.png",
          name: "comic shop locator",
        },
        {
          url: "../../public/img/buy-dc-power-visa.svg",
          name: "dc power visa",
        },
      ],
    };
  },
};
</script>

<template>
  <div class="blue-component">
    <ul>
      <li v-for="link in links">
        <img :src="link.url" alt="" />
        <a href="#">{{ link.name }}</a>
      </li>
    </ul>
  </div>
</template>

<style lang="scss" scoped>
@use "../styles/general.scss" as *;
@use "../styles/partials/variables" as *;

.blue-component {
  background-color: $primary-blue;
  position: relative;
  z-index: 1;

  ul {
    @include container;
    display: flex;
    list-style: none;
    color: white;
    justify-content: space-around;
    padding: 50px 45px;

    li {
      display: flex;
      align-items: center;
      gap: 15px;

      a {
        text-transform: uppercase;
        text-decoration: none;
        color: white;
        font-size: 14px;
      }

      img {
        height: 55px;
      }
    }

    li:last-of-type img {
      height: 35px;
    }
  }
}
</style>
