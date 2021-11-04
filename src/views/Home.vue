<template>
  <div class="home">
    <Top />
    <Four/>
    <About/>
  </div>
</template>


<script>
// @ is an alias to /src
import Top from '@/components/Top_test.vue'
import Four from '@/components/four.vue'
import About from './About.vue'
export default {
  name: 'Home',
  components: {
    Top,
    Four,
    About
  }
}
</script>
