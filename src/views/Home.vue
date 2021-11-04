<template>
  <div class="home">
    <Top />
    <two/>
    <Four/>
    
  </div>
</template>

<script>
// @ is an alias to /src
import Top from '@/components/Top_test.vue'
import Four from '@/components/four.vue'
import two from '../components/two.vue'
export default {
  name: 'Home',
  components: {
    Top,
    Four,
    two
  }
}
</script>
