<template>
  <div class="about">
    <div class="about-one">
      <h1 class="about-tit"><span>中外合作留学</span></h1>
      <div class="about-type">
        <ul class="about-ul">
          <li class="about-ul-li1">留学预科</li>
          <li class="about-ul-li">2+2留学</li>
          <li class="about-ul-li">3+2留学</li>
        </ul>
      </div>
      <One/>
      <router-view/>
    </div>
  </div>
</template>
<script>
import One from '@/components/one.vue'


export default {
  name: 'About',
  components: {
    One,
  }
}
</script>


<style scoped>
.about{
  width: 100%;
}
.about-one{
  margin: 0 .1rem 0 .1rem;
  border: 1px solid #ccc;
  box-sizing: content-box;
}
.about-tit{
  height: .55rem;
  text-align: left !important;
}
.about-tit span{
  display: block;
  background: #36477a;
  color: #fff;
  font-size: 26px;
  width: 1.6rem;
  height: .55rem;
  line-height: .5rem;
  font-weight: bold;
}
.about-ul{
  display: flex;
  padding: .15rem .05rem .1rem .05rem;
  border: 1px solid #ccc;
}
.about-ul-li{
  width: 33.333%;
  height: .32rem;
  line-height: .32rem;
  border: 1px solid #cc8b59;
}
.about-ul-li1{
  width: 33.333%;
  height: .32rem;
  line-height: .32rem;
  border: 1px solid #cc8b59;
  background-color: #cc8b59;
}
</style>
