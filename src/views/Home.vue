<template>
  <div class="home">
    <Top />
    <Four/>
    <Poferfer/>
    <America/>
  </div>
</template>

<script>
// @ is an alias to /src
import Top from '@/components/Top_test.vue'
import Four from '@/components/four.vue'
import Poferfer from '@/components/poferter.vue'
import America from '@/components/America.vue'
export default {
  name: 'Home',
  components: {
    Top,
    Four,
    Poferfer,
    America
  }
}
</script>
