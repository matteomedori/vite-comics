<script>
export default {
  name: "AppFooterUp",
};
</script>

<template>
  <div class="footer-up">
    <div class="container">
      <div class="left">
        <div class="col">
          <h4>DC Comics</h4>
          <ul>
            <li>prova</li>
            <li>prova</li>
            <li>prova</li>
            <li>prova</li>
            <li>prova</li>
            <li>prova</li>
            <li>prova</li>
          </ul>
          <h4>Shop</h4>
          <ul>
            <li>prova</li>
            <li>prova</li>
          </ul>
        </div>
        <div class="col">
          <h4>DC</h4>
          <ul>
            <li>prova</li>
            <li>prova</li>
            <li>prova</li>
            <li>prova</li>
            <li>prova</li>
            <li>prova</li>
            <li>prova</li>
            <li>prova</li>
            <li>prova</li>
            <li>prova</li>
            <li>prova</li>
          </ul>
        </div>
        <div class="col">
          <h4>Sites</h4>
          <ul>
            <li>prova</li>
            <li>prova</li>
            <li>prova</li>
            <li>prova</li>
            <li>prova</li>
          </ul>
        </div>
      </div>

      <img src="../../public/img/dc-logo-bg.png" alt="" />
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use "../styles/general.scss" as *;

.footer-up {
  background-image: url(../../public/img/footer-bg.jpg);
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
      h4 {
        text-transform: uppercase;
        font-size: 21px;
      }

      ul {
        list-style-type: none;
        color: gray;
        margin: 15px 0;

        li {
          margin-bottom: 4px;
          font-size: 12px;
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
