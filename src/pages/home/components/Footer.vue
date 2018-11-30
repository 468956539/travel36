<template>
    <div class="bottom">
        <ul>
            <li class="service-tel" href="tel:4007-995-166">
                <a href="tel:4007-555-555" rel="nofollow" part-label="phone">
                    <img src="//pic5.40017.cn/02/000/64/7b/rBLkCVqp3pSAND1WAAACDBVkQaU993.png">
                    <p>客服电话</p>
                </a>
            </li>
            <li class="download-app">
                <a href="//m.17u.cn/client/qr/18024458" rel="nofollow" part-label="download">
                    <img src="//pic5.40017.cn/01/000/64/74/rBLkBlqp3pSAUjDFAAAAqM2yKYA236.png">
                    <p>下载客户端</p>
                </a>
            </li>
            <li>
                <a href="/member" rel="nofollow" part-label="mine">
                    <img src="//pic5.40017.cn/02/001/64/7b/rBLkCVqp3pSAItBpAAABv-mJDd4590.png">
                    <p>我的同程</p>
                </a>
            </li>
        </ul>
        <div class="bottom-sub">
            <a href="//www.ly.com/?fromwap=1" rel="nofollow" part-label="PC">电脑版</a>
            <a href="javascript:void(0)" class="bottom-language" part-label="language">
                <i></i>简体中文
                <em></em>
            </a>
            <a href="/suggestion.html" rel="nofollow" part-label="suggestion">意见反馈</a>
        </div>
        <footer>©2018同程旅游</footer>      
    </div>    
</template>
          
<script>
    export default{
        name: 'HomeFooter',
        props: {
            list: Array
        },     
    }
</script>
          
<style scoped>
    .bottom {
        background: #f0f4f5;
        padding: .46667rem 0 0 0;
    }

    .bottom ul {
        display: -webkit-box;
        display: -ms-flexbox;
        display: flex;
        box-sizing: border-box;
    }

    .bottom ul li {
        width: 100%;
        height: 1.46667rem;
        -webkit-box-flex: 0;
        -ms-flex: 0 0 33.333%;
        flex: 0 0 33.333%;
        max-width: 33.333%;
        box-sizing: border-box;
        text-align: center;
        display: list-item;
    }

    .bottom ul li a {
        height: 100%;
        display: block;
        -webkit-tap-highlight-color: rgba(0,0,0,0);
        text-decoration: none;
        color: #333;
    }

    .bottom ul li img {
        width: .5rem;
        height: .5rem;
        margin-top: .16rem;
    }

    .bottom ul li p {
        color: #666;
        font-size: .24rem;
        margin-top: .1rem;
    }
    
    .bottom .bottom-sub {
        text-align: center;
        padding-top: .4rem;
    }

    .bottom .bottom-sub a {
        display: inline-block;
        line-height: .21333rem;
        border-left: .02667rem solid #e4e4e4;
        padding: 0 .26667rem 0 .4rem;
        color: #999;
        position: relative;
        font-size:.24rem;
    }

    .bottom .bottom-sub a:first-child {
        border: none;
    }

    .bottom-language i {
        width: .26667rem;
        height: .18667rem;
        margin-right: .13333rem;
        display: inline-block;
        background: url(//pic5.40017.cn/01/001/9c/5c/rBLkBlrNwKCALGcVAAAEyPA_usE580.png) no-repeat;
        background-size: contain;
    }

    .bottom-language em {
        width: .16rem;
        height: .08rem;
        margin-right: .06667rem;
        display: inline-block;
        background: url(//pic5.40017.cn/02/001/9c/64/rBLkCVrNwfeAImtlAAAD0unXgok290.png) no-repeat;
        background-size: contain;
        vertical-align: middle;
    }

    footer {
        background: #f0f4f5;
        color: #999;
        font-size: .24rem;
        text-align: center;
        padding: .4rem 0;
    }
</style>
          