<template>
  <section class="container">
    <ul>
      <li><a href="#">
        <img src="../assets/img/buy-comics-digital-comics.png" alt="digital-comics">
        <h4>DIGITAL COMICS</h4>
        </a>
      </li>

      <li><a href="#">
        <img src="../assets/img/buy-comics-merchandise.png" alt="merchandise">
        <h4>DC MERCHANDISE</h4>
        </a>
      </li>

            <li><a href="#">
        <img src="../assets/img/buy-comics-subscriptions.png" alt="subscription">
        <h4>SUBSCRIPTION</h4>
        </a>
      </li>

            <li><a href="#">
        <img class="special-img-shop"  src="../assets/img/buy-comics-shop-locator.png" alt="comic shop locator">
        <h4>COMIC SHOP LOCATOR</h4>
        </a>
      </li>

            <li><a href="#">
        <img src="../assets/img/buy-dc-power-visa.svg" alt="power visa">
        <h4>DC POWER VISA</h4>
        </a>
      </li>

    </ul>

  </section>
</template>

<script>
export default {
  name: 'SectionShopComp',

}
</script>

<style lang="scss" scoped>

@import '../assets/style/vars.scss';
section{
  background-color: $color-blue;
  height: 150px;
  display: flex;
  align-items: center;
  ul{
    display: flex;
    justify-content: space-evenly;
    width: 100%;
    li{
      display: flex;
      align-items: center;
      a{
        display: flex;
        align-items: center;
        img{
          width: 40px
        };
        img.special-img-shop{
          width: 30px
        };
        h4{
          font-size: 12px;
          color: #FFFFFF;
          margin-left: 10px;
        };
      };
      a:hover h4{
        color: #000000;
      
      };


    };
  };
}

</style>