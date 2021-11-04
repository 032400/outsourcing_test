<template>
  <div class="poferter_head">
      <div class="poferter_top">
          <div class='contents'>
            <h2 style="font-size: .24rem;text-align:center">出国留学热门专题</h2>
          </div>
      </div>
      <div class="line-box">
          <span></span>
      </div>
      <div class="tiel">
          <ul class="poferter_ul">
            <li v-for="(item,index) of list" :key='index'>
                <img :src="item" alt="">
            </li>
          </ul>
      </div>
      
  </div>
</template>

<script>
export default {
    data(){
        return {
            list:[
                'http://cg.yuloo.com/images/special1.jpg',
                'http://cg.yuloo.com/images/special2.jpg',
                'http://cg.yuloo.com/images/special3.jpg',
                'http://cg.yuloo.com/images/special4.jpg',
                'http://cg.yuloo.com/images/special5.jpg',
                'http://cg.yuloo.com/images/special6.jpg',
                'http://cg.yuloo.com/images/special7.jpg',
                'http://cg.yuloo.com/images/special8.jpg',
                'http://cg.yuloo.com/images/special9.jpg',
                'http://cg.yuloo.com/images/special10.jpg'
            ]
        }
    }
}
</script>

<style lang='scss' scoped>
.poferter_head{
    padding: 5% 0;
    margin: .2rem 0;
    width: 100%;
    height: 80vh;
}
img{
    width: 100%;
    height: 100%;
}

.poferter_top{
    display: flex;
    justify-content: space-around;
}
.contents{

}
.poferter_ul>li{
    width: 48%;
    float: left;
    margin: .035rem;
}
.poferter_ul>li>img{
    border-radius: .04rem;
}
.line-box {
    padding-top: 3%;
    padding-bottom: .2rem;
}
.line-box span {
    display: inline-block;
    width: 45px;
    height: 4px;
    background: #cc8b59;
    border-radius: 4px;
}
</style>