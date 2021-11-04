<template>
  <div class="home">
    <Top />
    <two/>
    <Four/>
    <seven/>
  </div>
</template>

<script>
// @ is an alias to /src
import Top from '@/components/Top_test.vue'
import Four from '@/components/four.vue'
import two from '../components/two.vue'
import seven from '../components/seven.vue'
export default {
  name: 'Home',
  components: {
    Top,
    Four,
    two,
    seven
  }
}
</script>
