<template>
  <div class="two_hea">
    <div>
      <van-icon name="youzan-shield" /><span style="font-size: 30px"
        ><b>出国留学规划</b></span
      >
    </div>
    <div class="xue">
      <span>出国留学人群</span>
    </div>
    <div class="annv">
      <van-button type="default">我要读高中</van-button>
      <van-button type="default">我要读本科</van-button>
      <van-button type="default">我要读硕士</van-button>
    </div>
    <div class="xue">
      <span>出国留学途径</span>
    </div>
    <div class="annv">
      <van-button type="default">留学预科</van-button>
      <van-button type="default">2+2留学</van-button>
      <van-button type="default">3+2留学</van-button>
    </div>
    <div class="xue">
      <span>出国留学国家</span>
    </div>
    <div class="annv-img">
      <van-button type="default">
        <span>
          <img
            src="../assets/yg.jpg"
            alt=""
            style="width: 34px; height: 17px"
          />
        </span>
        <span>英国</span>
      </van-button>
      <van-button type="default">
        <span>
          <img
            src="../assets/mg.jpg"
            alt=""
            style="width: 34px; height: 17px"
          />
        </span>
        <span>美国</span>
      </van-button>
      <van-button type="default">
        <span>
          <img
            src="../assets/az.jpg"
            alt=""
            style="width: 34px; height: 17px"
          />
        </span>
        <span>澳洲</span>
      </van-button>
    </div>
    <div class="annv-img" style="margin-top: 0.125rem">
      <van-button type="default">
        <span>
          <img
            src="../assets/jnd.jpg"
            alt=""
            style="width: 34px; height: 17px"
          />
        </span>
        <span>加拿大</span>
      </van-button>
      <van-button type="default">
        <span>
          <img
            src="../assets/hg.jpg"
            alt=""
            style="width: 34px; height: 17px"
          />
        </span>
        <span>韩国</span>
      </van-button>
      <van-button type="default">
        <span>
          <img
            src="../assets/rb.jpg"
            alt=""
            style="width: 34px; height: 17px"
          />
        </span>
        <span>日本</span>
      </van-button>
    </div>
    <div class="da">
      <span>出国留学有问必答</span>
      <div class="kuang">
        <input type="text" placeholder="学生姓名" />
        <input type="text" placeholder="手机号码" />
      </div>
      <div class="kuang">
        <input type="text" placeholder="出生年月" />
        <input type="text" placeholder="请选择学校" />
      </div>
      <div class="kuang">
        <input type="text" placeholder="请选择学历" />
        <input type="text" placeholder="您的疑问" />
      </div>
      <div class="jiao">
        <van-button type="default">立即提交</van-button>
        <span>《隐私保障》</span>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style lang='scss' scoped>
* {
  margin: 0 auto;
}
.two_hea {
  width: 100%;
  padding: 0.1rem 0;
  //   height: 0.4rem;
}
.van-icon-youzan-shield:before {
  font-size: 40px;
}
.xue {
  width: 200px;
  height: 40px;
  margin-top: 10px;
  font-size: 20px;
}
.annv > button + button {
  margin-left: 0.25rem;
}
.annv > button {
  width: 1.07rem;
  height: 0.35rem;
  border: 1 solid rgb(192, 201, 228);
  color: rgb(54, 71, 122);
}

.annv-img > button + button {
  margin-left: 0.25rem;
}
.annv-img > button {
  width: 1.08rem;
  height: 0.35rem;
  border: 1 solid rgb(192, 201, 228);
  color: rgb(54, 71, 122);
}

.da {
  width: 100%;
  background: rgb(244, 244, 244);
  margin-top: 0.125rem;
}
.da > span {
  font-size: 20px;
  padding-top: .2rem;
  display: inline-block;
}
.kuang {
  width: 3.6875rem;
  height: 40px;
  /* background: red; */
  margin-top: 0.2rem;
}
.kuang > input {
  width: 1.7rem;
  height: 0.3rem;
  margin-left: 0.08rem;
  border: 1px solid #ccc;
  text-align: center;
  /* margin: 0 auto; */
}

.jiao {
  width: 3.6875rem;
  text-align: center;
  margin-top: .2rem;
  display: flex;
  /* height: 50px; */
  padding-bottom: 0.2rem;
  flex-direction: column;
}
.jiao > button {
  margin-top: 0.15rem;
  background: #cc8b59;
  color: white;
  margin: 0 auto;
}
.jiao > span {
  margin-top: 15px;
  color: #ccc;
  outline: none;
  border: none;
  margin-bottom: 0.15rem;
}

.van-button__text {
  display: flex;
  align-items: center;
}
</style>
