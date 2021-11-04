<template>
  <div class="top_test">
      <div class="top_test_header">
          育路出国留学网-专注出国留学提供高质量的留学规划服务
      </div>
      <div class="content">
          <div class="content_left">
                  <a class="Top_a" href="http://cg.yuloo.com/">
                <img  src="http://cg.yuloo.com/images/yuloo-logo.png">
              </a>
                  <h1>出国留学</h1>
          </div>
            <button type="button" class="degger" data-target="#bs-example-navbar-collapse-1" aria-expanded="false">
                <div class="span">
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </div>
            </button>
      </div>
      <div class="swiper_test">
          <van-swipe :autoplay="3000">
            <van-swipe-item  v-for="(image, index) in images" :key="index">
                <img :src="image" />  
            </van-swipe-item>
          </van-swipe>
      </div>
  </div>
</template>

<script>
export default {
     data() {
        return {
            images: [
                'http://cg.yuloo.com/images/banner1.jpg',
                'http://cg.yuloo.com/images/banner2.jpg',
                'http://cg.yuloo.com/images/banner3.jpg'
            ],
        };
    },
    methods: {
        
    },
}
</script>

<style lang='scss' scoped>
.Top_a{
    width: .84rem;
    height: .23rem;
    display: flex;
    margin-top: .15rem;
}
img{
    width: 100%;
    height: 100%;
}
.top_test_header{
    color: #838c94;
    background-color: #eeeeee;
    height: 40px;
    line-height: 40px;
    text-align: left;
    padding-left: .1rem;
}
.content{
    padding: 10px 0;
    display: flex;
    justify-content: space-between;
}
h1{
    background: url('http://cg.yuloo.com/images/public/jb.jpg') no-repeat center center;
    color: white;
    margin-left: -.35rem;
    padding: 0 .15rem;
    font-size: .1rem;
    line-height: .3rem;    background-size: cover;
    border-radius: .03rem;
    overflow: hidden;
    height: .3rem;
    margin-top: .1rem;
}
.content_left{
    display: flex;
    justify-content: space-between;
    width: 1.6rem;
    line-height: .6rem;
    margin-top: .05rem;
    margin-left: .1rem;
}
.degger{
    position: relative;
    padding: .09ren .1rem;
    margin-top: .1rem;
    margin-right: .15rem;
    margin-bottom: .08rem;
    background-color: transparent;
    background-image: none;
    border: 1px solid #ccc;
    height: .35rem;
    width: .44rem;
    border-radius: .04rem;
    text-align: -webkit-center
}
.span{
    margin-top: -.05rem;
}
.icon-bar{
    display: block;
    width: .22rem;
    height: .02rem;
    border-radius: .01rem;
    background-color: #888888;
    line-height: .34rem;
    margin-top: .05rem;
}
</style>