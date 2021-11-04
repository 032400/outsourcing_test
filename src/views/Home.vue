<template>
  <div class="home">
    <Top />
    <two/>
    <Four/>
    <seven/>
    <enter/>
  </div>
</template>

<script>
// @ is an alias to /src
import Top from '@/components/Top_test.vue'
import Four from '@/components/four.vue'
import two from '../components/two.vue'
import seven from '../components/seven.vue'
import enter from '../components/enter.vue'
export default {
  name: 'Home',
  components: {
    Top,
    Four,
    two,
    seven,
    enter
  }
}
</script>
