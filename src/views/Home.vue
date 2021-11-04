<template>
  <div class="home">
    <Top />
    <Two/>
    <ext/>
    <About/>
    <Four/>
    <Seven/>
  </div>
</template>


<script>
// @ is an alias to /src
import Top from '@/components/Top_test.vue'
import Four from '@/components/four.vue'
import Two from '../components/two.vue'
import Seven from '../components/seven.vue'
import ext from '../components/ext.vue'
import enter from '../components/enter.vue'
import About from './About.vue'
export default {
  name: 'Home',
  components: {
    Top,
    Two,
    ext,
    Four,
    About,
    Seven,
    enter,
  }
}
</script>
