<template>
  <div class="wrapper">
    <swiper :options="swiperOption">
      <!-- slides -->
      <swiper-slide v-for="item in list" :key="item.id">
        <img class="swiper_img" :src="item.imgUrl" alt="">
        <div class="intro">
          <span v-if="item.month"><em>{{item.month}}</em>月</span>
          <h4>{{item.address}}</h4>
          <p>{{item.desc}}</p></div>
      </swiper-slide>
      <!-- Optional controls -->
      <div class="swiper-pagination"  slot="pagination"></div>
    </swiper>
  </div>
</template>

<script>
export default{
  name: 'HomeSwiper',
  props: {
    list: Array
  },
  data: function () {
    return {
      swiperOption: {
        pagination: '.swiper-pagination',
        loop: true
      }
    }
  }
}
</script>

<style scoped>
  .intro{
    color: #fff;
    width:100%;
    position: absolute;
    top: 0;
    left: 0;
  }
  .intro span{
    width: 1rem;
    font-size:.18rem;
    display:inline-block;
    margin-top: .15rem;
    text-align: center;
    color: #fff;
  }
  .intro h4{
    width: 7.6rem;
    height: 0.74rem;
    text-align:center;
    line-height:0.74rem;
    font-size: .4rem;
    overflow: hidden;
    color:#fff;
  }
  .intro p{
    width: 7.6rem;
    height: .32rem;
    line-height:.32rem;
    text-align: center;
    font-size: .2rem;
    overflow: hidden;
    color:#fff;
  }
  .swiper_img{
    width: 100%;
  }
  .wrapper >>> .swiper-pagination-bullet-active{
    background: #fff !important;
  }
</style>
