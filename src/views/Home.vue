<template>
  <div class="home">
    <Top />
    <Two/>
    <Seven/>
    <Four/>
    <About/>
  </div>
</template>


<script>
// @ is an alias to /src
import Top from '@/components/Top_test.vue'
import Four from '@/components/four.vue'
import About from './About.vue'
import Two from '../components/two.vue'
import Seven from '../components/seven.vue'
export default {
  name: 'Home',
  components: {
    Top,
    Two,
    Seven,
    Four,
    About
  }
}
</script>
