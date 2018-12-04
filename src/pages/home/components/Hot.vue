<template>
    <div class="hot-module1">
        <h2><em></em>热门推荐</h2>
        <div class="col-1">
            <ul>
                <li v-for="item of list" :key="item.id">                    
                    <a :href="item.url" :title="item.title">{{item.title}}</a>
                </li>
            </ul>
            <ul class="more">
                <li>
                    <a href="https://m.ly.com/public/destination" title="更多"><i></i><i></i><i></i></a>
                </li>
            </ul>
        </div>
    </div>
</template>
  
<script>
  export default{
    name: 'HomeHot',
    props: {
      list: Array,
    },
    
  }
</script>
  
<style scoped>
    .hot-module1{
        margin-top: .2rem;
        background: #fff;
        padding: .1rem 0 0 0;
    }

    .hot-module1 h2{
        text-align: center;
        color: #fb5300;
        font-size: .32rem;
        font-weight: 500;
    }

    .hot-module1 h2 em {
        width: .42667rem;
        height: .49333rem;
        display: inline-block;
        vertical-align: -.08rem;
        margin-right: .1rem;
    }

    .hot-module1 h2 em{
        background: url(//pic5.40017.cn/01/000/5f/b5/rBLkBlqo1SmAXKh2AAATQxd5x9Q718.png) no-repeat 0 0;
        background-size: 3.9rem 2.8rem;
        background-position: -.32rem -1.10667rem;
    }

    .hot-module1 .col-1 {
        padding: .53333rem .13333rem .26667rem .4rem;
        border-bottom: .01333rem solid #f5f5f5;
        overflow: hidden;
    }

    .hot-module1 .col-1 .more li i{
        width: .1rem;
        height: .1rem;
        background: #979797;
        display: inline-block;
        margin-left: .13333rem;
        border-radius: 100%;
        vertical-align: middle;
        
    }

    .hot-module1 .col-1 ul li {
        width: 25%;
        float: left;
        display: block;
        background: #fff!important;
    }

    .hot-module1 .col-1 ul li a {
        height: .6rem;
        line-height: .6rem;
        text-align: center;
        display: block;
        background: #f4f4f4;
        border-radius: .4rem;
        margin-right: .26667rem;
        margin-bottom: .26667rem;
        text-decoration: none;
        color: #333;
        font-size:.24rem;
    }

    .hot-module1 .col-2 {
        padding: .4rem .13333rem .53333rem .4rem;
        border-bottom: .01333rem solid #f5f5f5;
        overflow: hidden;
    }

    .hot-module1 .col-2 ul{
        display: table;
       
    }

    .hot-module1 .col-2 ul li {
        width: 50%;
        height: 2.2rem;
        float: left;
        display: block;
        margin-bottom: .26667rem;
        text-align: -webkit-match-parent;
    }

    .hot-module1 .col-2 ul li a {
        height: 100%;
        display: block;
        position: relative;
        margin-right: .26667rem;
    }

    .hot-module1 .col-2 ul li a img {
        width: 100%;
        height: 100%;
        border-radius: .10667rem;
    }

    .hot-module1 .col-2 ul li span {
        position: absolute;
        top: 0;
        left: 0;
        padding-right: .4rem;
    }

    .hot-module1 .col-2 ul li span b {
        height: .4rem;
        line-height: .4rem;
        font-size: .24rem;
        padding-left: .10667rem;
        background: #fc5446;
        color: #fff;
        display: block;
        border-top-left-radius: .10667rem;
    }

    .hot-module1 .col-2 ul li span i {
        position: absolute;
        display: inline-block;
        width: 0;
        height: 0;
        right: .01333rem;
        top: 0;
        border-top: .4rem solid #fc5446;
        border-right: .4rem solid transparent;
        z-index: 3;
    }

    .hot-module1 .col-2 ul li p {
        height: .36rem;
        line-height: .36rem;
        font-size: .24rem;
        padding: .13333rem .26667rem;
        position: absolute;
        bottom: 0;
        left: 0;
        color: #fff;
        overflow: hidden;
        text-overflow: ellipsis;
        -o-text-overflow: ellipsis;
        white-space: nowrap;
    }

    .hot-module1 .col-2>a {
        color: #00a0ff;
        font-size: .28rem;
        text-align: center;
        display: block;
        margin-top: .26667rem;
        -webkit-tap-highlight-color: rgba(0,0,0,0);
        text-decoration: none;
    }

</style>
  