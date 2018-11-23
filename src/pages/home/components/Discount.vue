    <template>
        <div class="lv-module2">
            <div class="col-1">
                <h2></h2>
                <p class="sale-time">还剩&emsp;<span class="frame">00</span><i>:</i><span class="frame">39</span><i>:</i><span class="frame">09</span></p>
                <a class="sale-pro" href="#">
                    <div class="pic">
                        <img src="//pic4.40017.cn/zzy/rimage/2016/10/27/15/OSBVgt.jpg">
                        <span>限量100份</span>
                    </div>
                    <div class="intro">
                        <h3>【周末推荐】理县毕棚沟世纪温泉酒店雪山观景双床房1晚+双人温泉</h3>
                        <div class="price"><em>¥</em><i>471.00</i>起<span>更多抢购<b></b></span></div>
                    </div>
                </a>
            </div>
            <div class="col-2">
                <ul>
                    <li>
                        <a href="#">
                            <div class="title">
                                <h3>1元玩景点</h3>
                                <p>PLUS会员</p>
                            </div>
                            <img src="//pic5.40017.cn/02/000/64/5c/rBLkCFqp0MaAXcDOAAASHzYoUEI450.png">
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <div class="title">
                                <h3>出境特卖</h3>
                                <p style="color:#ff7e60;border-color: #ff7e60">每日上新</p>
                            </div>
                            <img src="//pic5.40017.cn/01/001/d2/88/rBLkBlrz5OGARo6VAAAZQDF46aE442.png">
                        </a>
                    </li>
                </ul>
            </div>
        </div>
       
    </template>
      
      <script>
      export default{
        name: 'HomeDiscount',
        props: {
          list: Array
        },
        
      }
      </script>
      
      <style scoped>

        .lv-module2{
           background: #fff;
           margin-top: .26rem;
           
        }
        .col-1 h2{
            height: .6rem;
            background-position: -.32rem -.32rem;
            background: url(//pic5.40017.cn/01/000/5f/b5/rBLkBlqo1SmAXKh2AAATQxd5x9Q718.png) no-repeat;
            background-size: 3.9rem 2.8rem;
        }
        .col-1{
            padding: .2rem .4rem 0 .4rem;
            position: relative;
            border-bottom: 0.01rem solid #f5f3f3;
        }

        .col-1 h2{
            height:.6rem;
            background-position: -.32rem -.32rem;
        }
       
        .sale-time{
            position: absolute;
            top: .5rem;
            right: .4rem;
            color: #666;
            font-size:.16rem;
        }

        .frame{
            background-color:#555;
            border-radius:.08rem;
            padding:.04rem .08rem;
            color:#fff;
            font-size:.24rem;
            margin-left:.05rem;
            margin-right: .05rem;
        }

        .sale-pro{
            height:2.4rem;
            display:block;
            margin-top:.46rem;
            text-decoration:none;
            color:#333;
            border:0;
        }

        .pic{
            width:38%;
            height:80%;
            float: left;
            position: relative;
        }
        .pic img{
            width:100%;
            height:100%;
            border:0;
        }

        .pic span{
            height: .42rem;
            line-height:.42rem;
            color:#fff;
            font-size:.1rem;
            background-color: #ff5f5f;
            padding:0 .13rem;
            position: absolute;
            top:0;
            left: 0;
        }

        .intro{
            width: 58%;
            height: 80%;
            float: right;
            position: relative;
        }

        .intro h3{
            max-height:1rem;
            color:#404040;
            font-size:.28rem;
            line-height:.4rem;
            text-overflow:ellipsis;
            display: -webkit-box;
            -webkit-line-clamp:2;
            -webkit-box-orient: vertical;
            overflow: hidden;
            font-weight:bold;
        }

        .price{
            width:100%;
            font-size:.1rem;
            color:#666;
            position: absolute;
            left:0;
            bottom: 0;
        }

        .price em{
            color: #ff5346;
            font-size:.28rem;
            font-style:normal;
            font-weight:500;
            margin-right:.05rem;
        }

        .price i{
            color:#ff5346;
            font-size:.32rem;
            margin-right:.06rem;
            font-weight:normal;
            font-style: normal;
        }

        .price span{
            float: right;
            margin-top:.02rem;
            font-size:.1rem;
        }

        .price span b{
            width: .13rem;
            height:.24rem;
            background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAoAAAASCAYAAABit09LAAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAAyZpVFh0WE1MOmNvbS5hZG9iZS54bXAAAAAAADw/eHBhY2tldCBiZWdpbj0i77u/IiBpZD0iVzVNME1wQ2VoaUh6cmVTek5UY3prYzlkIj8+IDx4OnhtcG1ldGEgeG1sbnM6eD0iYWRvYmU6bnM6bWV0YS8iIHg6eG1wdGs9IkFkb2JlIFhNUCBDb3JlIDUuNi1jMDY3IDc5LjE1Nzc0NywgMjAxNS8wMy8zMC0yMzo0MDo0MiAgICAgICAgIj4gPHJkZjpSREYgeG1sbnM6cmRmPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5LzAyLzIyLXJkZi1zeW50YXgtbnMjIj4gPHJkZjpEZXNjcmlwdGlvbiByZGY6YWJvdXQ9IiIgeG1sbnM6eG1wPSJodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvIiB4bWxuczp4bXBNTT0iaHR0cDovL25zLmFkb2JlLmNvbS94YXAvMS4wL21tLyIgeG1sbnM6c3RSZWY9Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC9zVHlwZS9SZXNvdXJjZVJlZiMiIHhtcDpDcmVhdG9yVG9vbD0iQWRvYmUgUGhvdG9zaG9wIENDIDIwMTUgKFdpbmRvd3MpIiB4bXBNTTpJbnN0YW5jZUlEPSJ4bXAuaWlkOjc1NUZGQTczMjc2MzExRThCODUwQzYxNDNBODE0NTVBIiB4bXBNTTpEb2N1bWVudElEPSJ4bXAuZGlkOjc1NUZGQTc0Mjc2MzExRThCODUwQzYxNDNBODE0NTVBIj4gPHhtcE1NOkRlcml2ZWRGcm9tIHN0UmVmOmluc3RhbmNlSUQ9InhtcC5paWQ6NzU1RkZBNzEyNzYzMTFFOEI4NTBDNjE0M0E4MTQ1NUEiIHN0UmVmOmRvY3VtZW50SUQ9InhtcC5kaWQ6NzU1RkZBNzIyNzYzMTFFOEI4NTBDNjE0M0E4MTQ1NUEiLz4gPC9yZGY6RGVzY3JpcHRpb24+IDwvcmRmOlJERj4gPC94OnhtcG1ldGE+IDw/eHBhY2tldCBlbmQ9InIiPz5tlP5rAAAA1ElEQVR42mJMS0tjIAYwQWkHIMargwVK2wGxKRB/BeKl+EzsBOKbQBwBxL74FP4E4nogfgDEqVCnYFXIALUWpPgFEBcCsTkuhSDwDqr4AxCXArEeLoUg8Byq+A8QVwGxCi6FDFC31kNDpQGIpZjwBB0oFNYAMT8QF+FTqA7EIUD8EYh7cSlUAOJGqDtBTniOTaEkVBHIfa1AfBebZ4ShikDu6gbiy9iChwfqQwkgngDEJ7EFODtUEchts4H4AK4oLIf6cjkQb8aXzA5C43gZrrACCDAABW0nWxL2AKoAAAAASUVORK5CYII=) no-repeat center center;
            background-size:contain;
            display: inline-block;
            margin-left:.1rem;
        }

       .col-2 ul{
            display: flex;
            box-sizing: border-box;
            list-style: none;
            overflow: hidden;
            border-bottom: .01rem solid #f5f3f3;
        }
       .col-2 ul li{
            width:50%;
            max-width: 50%;
            box-sizing: border-box;
            display: block;
            height: 1.5rem;
            float: left;
            text-align: -webkit-match-parent;
            
        }
        
        .col-2 ul li:first-child a{
            border-left: none;
        }

        .col-2 ul li a{
            height: 1.4rem;
            padding: .2rem .4rem;
            display: block;
            position: relative;
            -webkit-tap-highlight-color: rgba(0,0,0,0);
            text-decoration: none;
            color: #333;
            border-left: .01rem solid #f5f3f3;
        }

        
        .col-2 .title h3{
            line-height: .28rem;
            font-size: .28rem;
            margin-top: .2rem;
            position: relative;
            font-weight:bold;
        }
        .col-2 .title p{
            color: #ebb73f;
            height: .24rem;
            font-size: .24rem;
            border-width: .01rem;
            border-color: #ebb73f;
            border-style: solid;
            padding: 0.08rem .08rem;
            display: inline-block;
            border-radius: .1rem;
            margin-top:.14rem;
        }

        .col-2 ul li a>img{
            width: 1.2rem;
            height: 1.2rem;
            position: absolute;
            right: .4rem;
            top: .2rem;
        }
      </style>
      