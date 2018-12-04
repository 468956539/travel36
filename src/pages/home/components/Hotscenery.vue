<template>
    <div class="hot-module1">
        <div class="col-2">
            <ul>
                <li v-for="item of list" :key="item.id">
                    <a :href="item.url">
                        <img :src="item.imgUrl">
                        <span><b>{{item.title}}</b><i></i></span>
                        <p>{{item.desc}}</p>
                    </a>
                </li>
                <!-- <li>
                    <a href="">
                        <img src="//pic4.40017.cn/poi/2017/03/16/16/wony5c_300x200_00.jpg">
                        <span><b>古镇</b><i></i></span>
                        <p>今年最火的10大古镇</p>
                    </a>
                </li> -->
                <!-- <li>
                    <a href="https://m.ly.com/go/journeytopic/3144/2155.html?from=hotplay" rel="nofollow" onclick="_tcTraObj._tcTrackEvent('touchhome_B','img','/hot-playing','locCid=324&amp;pos=2&amp;title=适合秋冬出游的海岛&amp;date=20180319')"><img src="http://pic5.40017.cn/01/000/07/9e/rBLkBlnoZ5CAd5s8AAGoaencbUU275_300x200_00.jpg"><span><b>海岛</b><i></i></span><p>适合秋冬出游的海岛</p></a>
                </li>
                <li>
                    <a href="https://m.ly.com/go/journeytopic/210/2154.html?from=hotplay" rel="nofollow" onclick="_tcTraObj._tcTrackEvent('touchhome_B','img','/hot-playing','locCid=324&amp;pos=3&amp;title=中国8大经典自驾线路	&amp;date=20180319')"><img src="http://pic5.40017.cn/01/001/04/14/rBLkBVnnEiaADQysAAD4v4j0QKY062_300x200_00.jpg"><span><b>自驾游</b><i></i></span><p>中国8大经典自驾线路	</p></a>
                </li>
                <li>
                    <a href="https://m.ly.com/go/journeytopic/1813/1757.html?from=hotplay" rel="nofollow" onclick="_tcTraObj._tcTrackEvent('touchhome_B','img','/hot-playing','locCid=324&amp;pos=4&amp;title=10月旅行目的地推荐&amp;date=20180319')"><img src="//pic4.40017.cn/poi/2016/09/28/20/jfN5UH_300x200_00.jpg"><span><b>盘点</b><i></i></span><p>10月旅行目的地推荐</p></a>
                </li> -->
            </ul>
            <a class="more-link" href="https://m.ly.com/go/youji/view/gonglueIndex.html?fid=8" onclick="_tcTraObj._tcTrackEvent('touchhome_B','txt','/hot-more','locCid=324&amp;txt=查看更多玩法&amp;date=20180319')">查看更多玩法</a>
        </div>
    </div>
</template>
  
<script>
  export default{
    name: 'HomeHotscenery',
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
  