<template>
  <footer>

    <div class="footer-top container">
      <div class="list-box">
        <div class="list-footer">
          <ul>
            <li><h2>dc comics</h2></li>
            <li><a href="#">Characters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">News</a></li>
          </ul>

          <ul>
            <li><h2>shop</h2></li>
            <li><a href="#">Shop DC</a></li>
            <li><a href="#">Shop DC Collectibles</a></li>
          </ul>
        </div>

        <div class="list-footer">
          <ul>
            <li><h2>dc</h2></li>
            <li><a href="#">Terms Of Use</a></li>
            <li><a href="#">Privacy policy (New)</a></li>
            <li><a href="#">Ad Choices</a></li>
            <li><a href="#">Advertising</a></li>
            <li><a href="#">Jobs</a></li>
            <li><a href="#">Subscriptions</a></li>
            <li><a href="#">Talent Workshops</a></li>
            <li><a href="#">CPSC Certificates</a></li>
            <li><a href="#">Ratings</a></li>
            <li><a href="#">Shop Help</a></li>
            <li><a href="#">Contact Us</a></li>
          </ul>
        </div>

        <div class="list-footer">
          <ul>
            <li><h2>sites</h2></li>
            <li><a href="#">DC</a></li>
            <li><a href="#">MAD Magazine</a></li>
            <li><a href="#">DC Kids</a></li>
            <li><a href="#">DC Universe</a></li>
            <li><a href="#">DC Power Visa</a></li>
          </ul>
        </div>
      </div>

      <div class="logo-background">
        <img src="../assets/img/dc-logo-bg.png" alt="logo-background">
      </div>
    </div>
    <div class="footer-bottom container">
      <div class="sign-up">
        <a href="#">SIGN-UP NOW!</a>
      </div>

      <div class="box-follow">
        <ul>
          <li><a href="#">follow us</a></li>
          <li><a href="#"><img src="../assets/img/footer-facebook.png" alt=""></a></li>
          <li><a href="#"><img src="../assets/img/footer-twitter.png" alt=""></a></li>
          <li><a href="#"><img src="../assets/img/footer-youtube.png" alt=""></a></li>
          <li><a href="#"><img src="../assets/img/footer-pinterest.png" alt=""></a></li>
          <li><a href="#"><img src="../assets/img/footer-periscope.png" alt=""></a></li>
        </ul>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'FooterComp'

}
</script>

<style lang='scss' scoped>
@import '../assets/style/vars.scss';

footer{
  background-image: url(../assets/img/footer-bg.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  .footer-top{
    display: flex;
    justify-content: space-between;
  }
  .list-box{
    display: flex;
  }
  .list-footer{
    padding: 10px 10px 50px;
  }
  ul{
    margin-top: 20px;
  }
  li{
    h2{
      color: #FFFFFF;
      font-size: 15px;
      margin-bottom:10px;
      text-transform: uppercase;
    };
    a{
      color: #687E7B;
      font-size: 12px;
      font-weight: normal;
      &:hover{
        color:#FFFFFF;
        text-shadow: 1px 1px 10px #469beb

      }
    };
  };
  .logo-background{
    height: 360px;
    overflow: hidden;
    text-align: right;
    img{
      margin-top: -75px;
      width: 85%;
    }
  }

/* -------------------------------------------- */

  .footer-bottom{
    height: 80px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #303030;
    .sign-up{
      a{
        color: #FFFFFF;
        text-transform: uppercase;
        border: 1px solid $color-blue;
        font-size:15px;
        padding: 10px;
        margin-left:15px;
        animation: neon .08s ease-in-out infinite alternate;
        &:hover{
          color: $color-blue;
          background-color: #FFFFFF;
          box-shadow: 1px 1px 10px #469beb;
          /* text-shadow: 1px 1px 15px #469beb */

        }
      };

    };
    .box-follow{
      ul{
        display: flex;
        align-items: center;
        li{
          text-transform: uppercase;
          a{
            color: $color-blue;
            margin: 0 10px;
            font-size: 18px;
            display: flex;
            align-items: center;
            &:hover{
              color: #FFFFFF;
              text-shadow: 1px 1px 15px #469beb

            }
            img{
              width: 25px;
              border-radius: 50%;
              &:hover{
                box-shadow: 1px 1px 20px #469beb
              }
            }
          };
        }
      }
    }
    @keyframes neon {
  from {
    text-shadow:
    0 0 6px rgba(202,228,225,0.92),
    0 0 30px rgba(202,228,225,0.34),
    0 0 12px rgba(30,132,242,0.52),
    0 0 21px rgba(30,132,242,0.92),
    0 0 34px rgba(30,132,242,0.78),
    0 0 54px rgba(30,132,242,0.92);
  }
  to {
    text-shadow:
    0 0 6px rgba(202,228,225,0.98),
    0 0 30px rgba(202,228,225,0.42),
    0 0 12px rgba(30,132,242,0.58),
    0 0 22px rgba(30,132,242,0.84),
    0 0 38px rgba(30,132,242,0.88),
    0 0 60px rgba(30,132,242,1);
  }
}
  }
}

</style>