<template>
  <div>
    <HighlightBar />
    <HeaderPage class="md:block hidden" /> <!-- Versão Desktop -->
    <!-- <HeaderMobile class="md:hidden"/> Versão Mobile -->
    <!-- <Tutorial class="text-blue-600" /> -->
    <!-- <Product /> -->
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import HighlightBar from '~/components/HighlightBar.vue'
import HeaderPage from '~/components/HeaderPage.vue'
import Product from '~/components/Product.vue'

export default Vue.extend({
  name: 'IndexPage',
  components: {
    HighlightBar,
    HeaderPage,
    //Product,
  },
})
</script>
