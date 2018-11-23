<template>
<div class="header">
    <router-link to="/city">
      <div class="header_left">
        成都
        <span class="iconfont drop-down_icon">&#58901;</span>
      </div>
    </router-link>
    <div class="header_input">
      <span class="iconfont search_icon">&#58919;</span>
      目的地/酒店/景点/关键字
    </div>
    <div class="header_right">
        <div class="iconfont user_icon">&#58954;</div>
    </div>

</div>
</template>

<script>
export default{
  name: 'HomeHeader'
}
</script>

<style scoped>
  .header{
    line-height: .86rem;
    display: flex;
    color: #fff;
  }
  .header_left{
    width: 1rem;
    color:#23beae;
    float: left;
    margin-left: .2rem;
    margin-right: .12rem;
    text-align: center;
  }
  .drop-down_icon{
    font-size:.20rem;
  }
  .header_input{
    flex: 1;
    padding-left: .2rem;
    background: #eaedf1;
    border-radius: .5rem;
    height: .64rem;
    line-height: .64rem;
    margin-top: .12rem;
    color: #93989f;
    text-align: center;
  }
  .search_icon{
    font-size:.20rem;
  }
 
  .header_right{
    width: .48rem;
    float: right;
    color:#23beae;
    margin-right: .2rem;
    margin-left: .12rem;
    text-align: center;
  }

   .user_icon{
    font-size:.42rem;
  }
</style>
