<template>
<div>
    <home-header></home-header>
    <home-swiper :list='swiperList'></home-swiper>
    <home-ticket :list="ticketList"></home-ticket>
    <home-icons :list="iconList"></home-icons>
    <home-discount :list="discountList"></home-discount>
    <home-aboutapp :list="aboutappList"></home-aboutapp>
    <home-hot :list="hotList"></home-hot>
    <home-hotscenery :list="hotsceneryList"></home-hotscenery>
    <home-service></home-service>
    <home-footer></home-footer>
    <!-- <home-recommend :list="recommendList"></home-recommend> -->
</div>
</template>

<script>
import HomeHeader from './components/Header'
import HomeSwiper from './components/Swiper'
import HomeTicket from './components/Ticket'
import HomeIcons from './components/Icons'
import HomeRecommend from './components/Recommend'
import HomeDiscount from './components/Discount'
import HomeAboutapp from './components/Aboutapp'
import HomeHot from './components/Hot'
import HomeHotscenery from './components/Hotscenery'
import HomeService from './components/Service'
import HomeFooter from './components/Footer'
import axios from 'axios'
export default{
  name: 'Home',
  components: {
    HomeHeader,
    HomeSwiper,
    HomeTicket,
    HomeIcons,
    HomeRecommend,
    HomeDiscount,
    HomeAboutapp,
    HomeHot,
    HomeHotscenery,
    HomeService,
    HomeFooter
  },
  data: function () {
    return {
      swiperList: [],
      ticketList: [],
      iconList: [],
      discountList: [],
      downloadappList: [],
      hotList: [],
      hotsceneryList: []
    }
  },
  methods: {
    getHomeInfo: function () {
      axios.get('/api/index.json').then(this.getHomeInfoSucc)
    },
    getHomeInfoSucc: function (res) {
      res = res.data
      if (res.ret && res.data) {
        const data = res.data
        this.swiperList = data.swiperList
        this.ticketList = data.ticketList
        this.iconList = data.iconList
        this.discountList = data.recommendList
        this.downloadappList = data.downloadappList
        this.hotList = data.hotList
        this.hotsceneryList = data.hotsceneryList
      }
      console.log(res)
    }
  },
  mounted: function () {
    this.getHomeInfo()
  }
}
</script>

<style>
</style>
