<template>
  <div>
    <HighlightBar />
    <HeaderPage class="md:block hidden" /> <!-- Versão Desktop -->
    <!-- <HeaderMobile class="md:hidden"/> Versão Mobile -->
    <!-- <Tutorial class="text-blue-600" /> -->
    <Product />
    <TechnicalSheet />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import HighlightBar from '~/components/desktop/HighlightBarDesktop.vue'
import HeaderPage from '~/components/desktop/HeaderPageDesktop.vue'
import Product from '~/components/desktop/ProductDesktop.vue'
import TechnicalSheet from '~/components/desktop/TechnicalSheetDesktop.vue'




export default Vue.extend({
  name: 'IndexPage',
  components: {
    HighlightBar,
    HeaderPage,
    Product,
    TechnicalSheet,
  },
})
</script>
