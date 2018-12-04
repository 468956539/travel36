<template>
    <div class="tickets">
      <div class="ticket" v-for="item of list" :key="item.id">
            <div class="ticket_img">
              <img class="ticket_img_style" :src="item.imgUrl" alt="">
            </div>
            <p class="ticket_desc">{{item.desc}}</p>
       </div>
    </div>
</template>
  
<script>
  export default{
    name: 'HomeTicket',
    props: {
      list: Array
    },
    
  }
</script>  
<style scoped>
    .tickets{
      overflow: hidden;
      width: 100%;
      padding-top:.47rem;
      padding-bottom: .24rem;
      border-bottom: .01rem solid #f5f3f3;
    }
    .ticket{
      position: relative;
      overflow: hidden;
      float: left;
      width: 25%;
      padding-bottom:20%;
    }
    .ticket_img{
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      bottom: .44rem;
    }
    .ticket_img_style{
      display: block;
      height: 100%;
      margin: 0 auto;
      width: 1rem;
      height:1rem;
    }
    .ticket_desc{
      position: absolute;
      bottom: 0;left: 0;right: 0;
      height: .44rem;
      line-height: .44rem;
      text-align: center;
      color: #333;
    }
    </style>