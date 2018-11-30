<template>
    <div class="advantage-module">
        <ul>
            <li class="price-justice">
                <i></i>
                <p>价格公正</p>
                <span>价格公开透明，请安心购买</span>
            </li>
            <li class="rich-product">
                <i></i>
                <p>产品丰富</p>
                <span>出行产品，全品类覆盖，一站式服务</span>
            </li>
            <li class="good-quality">
                <i></i>
                <p>品质保证</p>
                <span><em>精挑</em>细选，产品优选，放心出行</span>
            </li>
            <li class="goood-advisor">
                <i></i>
                <p>专业顾问</p>
                <span>24小时专业客服，一对一服务</span>
            </li>
        </ul>
    </div>   
</template>
      
<script>
      export default{
        name: 'HomeService',
        props: {
          list: Array
        },
        
      }
</script>
      
<style scoped>
    .advantage-module {
        background: #fff;
    }

    .advantage-module ul {
        padding: .3rem 0 .66667rem .8rem;
    }

    .advantage-module ul li:first-child {
        margin-top: 0;
    }

    .advantage-module ul li {
        color: #9f8a70;
        position: relative;
        padding-left: 1.33333rem;
        margin-top: .73333rem;
        text-align: -webkit-match-parent;
    }

    .advantage-module ul li.price-justice i {
        background-position: -.13333rem -1.86667rem;
    }

    .advantage-module ul li.rich-product i {
        background-position: -1.09333rem -1.86667rem;
    }

    .advantage-module ul li.good-quality i {
        background-position: -2.05333rem -1.86667rem;
    }

    .advantage-module ul li.goood-advisor i {
        background-position: -3.01333rem -1.86667rem;
    }

    .advantage-module ul li i {
        width: .84rem;
        height: .84rem;
        position: absolute;
        left: 0;
        font-weight: normal;
        font-style: normal;
    }

    .advantage-module ul li i{
        background: url(//pic5.40017.cn/01/000/5f/b5/rBLkBlqo1SmAXKh2AAATQxd5x9Q718.png) no-repeat 0 0;
        background-size: 3.97333rem 2.82667rem;
    }

    .advantage-module ul li p {
        font-size: .28rem;
        display: block;
        margin-block-start: .8em;
        margin-block-end: .8em;
        margin-inline-start: 0px;
        margin-inline-end: 0px;
    }
    .advantage-module ul li span {
        font-size: .24rem;
    }


</style>
      