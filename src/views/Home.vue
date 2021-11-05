<template>
  <div class="home">
    <Top />
    <Two/>
    <Ext/>
    <Four/>
    <Poferfer/>
    <About/>
    <Seven/>
    <America/>
    <enter/>
  </div>
</template>


<script>
// @ is an alias to /src
import Top from '@/components/Top_test.vue'
import Four from '@/components/four.vue'
import Poferfer from '@/components/poferter.vue'
import America from '@/components/America.vue'
import Two from '../components/two.vue'
import Seven from '../components/seven.vue'
import Ext from '../components/ext.vue'
import enter from '../components/enter.vue'
import About from './About.vue'
export default {
  name: 'Home',
  components: {
    Top,
    Four,
    Poferfer,
    America,
    Two,
    Ext,
    Four,
    About,
    Seven,
    enter,
  }
}
</script>
