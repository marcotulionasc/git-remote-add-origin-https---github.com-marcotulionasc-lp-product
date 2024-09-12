<template>
  <div>
    <HighlightBar />
    <Tutorial class="text-blue-600" />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import HighlightBar from '~/components/HighlightBar.vue'

export default Vue.extend({
  name: 'IndexPage',
  components: {
    HighlightBar,
  },
})
</script>
