<template>
 
  <li>
    <img :src="cardSingle.thumb" :alt="cardSingle.type">
    <h4><a href="">{{cardSingle.series}}</a></h4>
  </li>
  
</template>

<script>
export default {
 name:'CardComp',
 props:{
   cardSingle:Object
 }
}
</script>

<style lang ="scss" scoped>
li{
  flex-basis: calc(100% / 6);
  margin-bottom: 28px;
  text-align: left;
  height: 25vh;
  
  img{
    width: 80%;
    height:20vh;
    margin: 0 10%;
  };
  h4{
    color: #FFFFFF;
    font-size: 12px;
    text-transform: uppercase;
    margin-top: 16px;
    padding: 0 16px;
    
    
  };
  a{
    color: white;
    &:hover{
      color:#FFFFFF;
      text-shadow: 1px 1px 10px #469beb
    }
  }
};
</style>