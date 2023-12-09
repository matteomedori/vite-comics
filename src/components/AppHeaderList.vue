<script>
export default {
  name: "AppHeaderList",
  data() {
    return {
      headerList: [
        "Characters",
        "Comics",
        "Movies",
        "Tv",
        "Games",
        "Collectibles",
        "Videos",
        "Fans",
        "News",
        "Shop",
      ],
    };
  },
};
</script>

<template>
  <ul>
    <li v-for="elem in headerList">
      <a href="#">{{ elem }}</a>
    </li>
  </ul>
</template>

<style lang="scss" scoped>
ul {
  display: flex;
  align-items: center;
  list-style-type: none;
  gap: 30px;
  height: 100%;

  li {
    height: 100%;
    display: flex;
    align-items: center;
    cursor: pointer;
    border-bottom: 5px solid white;
  }

  a {
    text-decoration: none;
    color: black;
    text-transform: uppercase;
    font-weight: 600;
    letter-spacing: -1px;
    font-size: 12px;
  }

  li:hover a {
    color: #0282f9;
  }

  li:hover {
    border-color: #0282f9;
  }
}
</style>
