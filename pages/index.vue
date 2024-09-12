<template>
  <div>
    <HighlightBar />
    <HeaderPage />
    <!-- <Tutorial class="text-blue-600" /> -->
    <Product />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import HighlightBar from '~/components/HighlightBar.vue'
import HeaderPage from '~/components/HeaderPage.vue'
<<<<<<< Updated upstream
=======
import Product from '~/components/Product.vue'
>>>>>>> Stashed changes

export default Vue.extend({
  name: 'IndexPage',
  components: {
    HighlightBar,
    HeaderPage,
    Product,
  },
})
</script>
