<template>
  <section>
    <div class="jumbotron">
      <button>CURRENT SERIES</button>
    </div>
  </section>
</template>

<script>
export default {
  name: 'JumbotronComp'

}
</script>

<style lang="scss" scoped>
@import '../assets/style/mixin.scss';
.jumbotron{
  height: 43vh;
  background-image: url(../assets/img/jumbotron.jpg);
  background-size: cover;
  position: relative;
  button{
    @include button-blue; 
    font-size: 18px;
    position: absolute;
    left: 16.5%;
    bottom: -2vh;
    &:hover{
      color:#FFFFFF;
        box-shadow: 1px 1px 10px #469beb
    }
    };

}


</style>