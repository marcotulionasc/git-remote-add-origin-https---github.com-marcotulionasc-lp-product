<template>
  <div>
    <HighlightBarDesktop class="md:block hidden"/> <!-- Versão Desktop -->
    <HighlightBarMobile class="md:hidden"/> <!-- Versão Mobile -->
    <HeaderPageDesktop class="md:block hidden" /> <!-- Versão Desktop -->
    <HeaderMobile class="md:hidden"/> <!-- Versão Mobile -->   
    <ProductDesktop class="md:block hidden"/> <!-- Versão Desktop -->
    <ProductMobile class="md:hidden"/> <!-- Versão Mobile -->
    <TechnicalSheetDesktop class="md:block hidden"/> <!-- Versão Desktop -->
    <TechnicalSheetMobile class="md:hidden"/> <!-- Versão Mobile -->
    
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

/* Imports of Desktop Pages */

import HighlightBarDesktop from '~/components/desktop/HighlightBarDesktop.vue'
import HeaderPageDesktop from '~/components/desktop/HeaderPageDesktop.vue'
import ProductDesktop from '~/components/desktop/ProductDesktop.vue'
import TechnicalSheetDesktop from '~/components/desktop/TechnicalSheetDesktop.vue'

/* Imports of Mobile Pages */

import HighlightBarMobile from '~/components/mobile/HighlightBarMobile.vue'
import HeaderPageMobile from '~/components/mobile/HeaderPageMobile.vue'
import ProductMobile from '~/components/mobile/ProductMobile.vue'
import TechnicalSheetMobile from '~/components/mobile/TechnicalSheetMobile.vue'



export default Vue.extend({
  name: 'IndexPage',
  components: {
    HighlightBarDesktop,
    HeaderPageDesktop,
    ProductDesktop,
    TechnicalSheetDesktop,
  },
})
</script>
