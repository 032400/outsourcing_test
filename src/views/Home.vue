<template>
  <div class="home">
    <Top />
    <two/>
    <Four/>
    <seven/>
	<ext/>
  </div>
</template>

<script>
// @ is an alias to /src
import Top from '@/components/Top_test.vue'
import Four from '@/components/four.vue'
import two from '../components/two.vue'
import seven from '../components/seven.vue'
import ext from '../components/ext.vue'
export default {
  name: 'Home',
  components: {
    Top,
    Four,
    two,
    seven,
	ext
  }
}
</script>
