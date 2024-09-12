<template>
  <div>
    <div v-for="image in images" :key="image.src">
      <img :src="image.src" alt="" />
    </div>
  </div>
</template>

<script setup>
import img0 from '~/assets/images/product/Rectangle63.svg'
import img1 from '~/assets/images/product/Rectangle64.svg'
import img2 from '~/assets/images/product/Rectangle65.svg'
import img3 from '~/assets/images/product/Rectangle66.svg'
import img4 from '~/assets/images/product/Rectangle67.svg'
import img5 from '~/assets/images/product/Rectangle68.svg'
import img6 from '~/assets/images/product/Rectangle69.svg'

const images = [
  {
    src: img0,
  },
  {
    src: img1,
  },
  {
    src: img2,
  },
  {
    src: img3,
  },
  {
    src: img4,
  },
  {
    src: img5,
  },
  {
    src: img6,
  }
]
</script>
