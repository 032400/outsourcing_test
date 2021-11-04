<template>
  <div class="two_hea">
      <div class="two_tit">
          <div class="two-icon">
              <van-icon name="notes-o" />
          </div>
          <div class="two_wz">
             出国留学最新资讯
          </div>
      </div>
      <!-- 第二部分 -->
      <div class="er">
          <div class="er_rig">出国留学动态</div>
          <div class="er_left">中外合作留学动态</div>
      </div>
      <!-- 第三部分 -->
      <div class="three">
          <div class="san">
          <!-- 图片 -->
          <div class="three_img">
              <img width="100%" src="../assets/ys.jpg" alt="" srcset="">
          </div>
          <!-- 文字 -->
          <div class="three_wz">
            <!-- <span>哪个国家留学可以免雅思申请</span> -->
            <div class="three_one">哪个国家留学可以免雅思申请学籍</div>
            <div class="three_two">雅思成绩不好的学生出国留学，希望能去免雅思成绩的国家...</div>
          </div>
          </div>
      </div>
      <!-- 第四部分 -->
      <div class="four">
          <div class="four_one">
              <div class="four_left">.北京出国留学院校哪些办的比较好？</div>
              <div class="four_rig">11-04</div>
          </div>
          <div class="four_one">
              <div class="four_left">.留学预算低，可以去哪些国家留学？</div>
              <div class="four_rig">11-04</div>
          </div>
          <div class="four_one">
              <div class="four_left">.2022QS亚洲地区大学排名重磅发布？</div>
              <div class="four_rig">11-04</div>
          </div>
          <div class="four_one">
              <div class="four_left">.雅思分数低的学生出国留学有哪些方案？</div>
              <div class="four_rig">11-04</div>
          </div>
          <div class="four_one">
              <div class="four_left">.日本TOP10院校硕士留学申请条件详解？</div>
              <div class="four_rig">11-04</div>
          </div>
          <div class="four_one">
              <div class="four_left">.出国留学什么专业最值得读？</div>
              <div class="four_rig">11-04</div>
          </div>
          <div class="four_one">
              <div class="four_left">.留学预算低，可以去哪些国家留学？</div>
              <div class="four_rig">11-04</div>
          </div>
          <div class="four_one">
              <div class="four_left">.2022QS亚洲地区大学排名重磅发布？</div>
              <div class="four_rig">11-04</div>
          </div>
          <!-- <div class="four_one">
              <div class="four_left">.雅思分数低的学生出国留学有哪些方案？</div>
              <div class="four_rig">11-04</div>
          </div> -->
      </div>
      <!-- 第五部分 -->
      <div class="five">
          <div class="five_wz">查看更多出国留学动态>></div>
      </div>
  </div>
</template>
<script>
export default {
//   props: ["msg"],
};
</script>
<style lang="scss" scoped>
.two_hea {
  width: 100%;
  height: auto;
  /* background: #ccc; */
}
.two_tit{
    width: 100%;
    height: .5rem;
    /* background: rebeccapurple; */
    display: flex;
}
.two-icon{
    width: 20%;
    height: .5rem;
    // background: rgb(247, 245, 247);
    display: flex;
    /* flex-direction: column; */
    align-items: center;
    justify-content: center;
}
.van-icon-notes-o:before {
    content: '\e6dd';
    font-size: .38rem;
} 
.two_wz{
    width: 70%;
    height: .5rem;
    /* background: gainsboro; */
    font-size: .2rem;
    display: flex;
    align-items: center;
    font-weight: 700;
}
/* 第二部分 */
.er{
    width: 100%;
    height: .45rem;
    /* background: cornsilk; */
    display: flex;
    justify-content: space-around;
}
.er_rig{
    width: 48%;
    height: .45rem;
    background: #cc8b59;
    border-radius: .1rem;
    font-size: .24rem;
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
}
.er_left{
    width: 48%;
    height: .45rem;
    /* background: #b4eeee; */
    border-radius: .1rem;
    font-size: .20rem;
    display: flex;
    align-items: center;
    justify-content: center;
    border: 1px solid #ccc;
}
.san{
    display: flex;
    flex-wrap: wrap;
}
/* 第三部分 */
.three{
    width: 100%;
    height: 1.4rem;
    /* background: wheat; */
    display: flex;
    align-items: center;
    justify-content: space-around;
}
.three_img{
    width: 40%;
    height: 1rem;
    /* background: violet; */
}
.three_wz{
    width: 55%;
    height: 1rem;
    /* background: coral; */
}
.three_one{
    width: 100%;
    height: .5rem;
    /* background: cornsilk; */
    font-size: .16rem;
    font-weight: 700;
}
.three_two{
    width: 100%;
    height: .5rem;
    /* background: rgb(202, 179, 84); */
    font-size: .14rem;
}
/* 第四部分 */
.four{
    width: 100%;
    height: 3.6rem;
    /* background: lightcyan; */
    margin-top: .2rem;
    // text-align: -webkit-left;
}
.four_one{
    width: 100%;
    height: .45rem;
    /* background: lightgoldenrodyellow; */
    display: flex;
    justify-content: center;
}
.four_left{
    width: 80%;
    height: .45rem;
    /* background: lightgray; */
    font-size: .14rem;
    display: flex;
    align-items: center;
    justify-content: center;
}
.four_rig{
    width: 30%;
    height: .45rem;
    /* background: rgb(159, 209, 224); */
    font-size: .16rem;
    display: flex;
    align-items: center;
    justify-content: center;
    color: #bdbdc2;
}
/* 第五部分 */
.five{
    width: 100%;
    height: .6rem;
    /* background: coral; */
    display: flex;
    justify-content: center;
    align-items: center;
}
.five_wz{
    width: 98%;
    height: .4rem;
    border-radius: .1rem;
    font-size: .16rem;
    border: 1px solid #cc8b59;
    color: #cc8b59;
    display: flex;
    align-items: center;
    justify-content: center;
}
</style>
