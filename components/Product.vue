<template>
  <div>
    <div v-for="image in images" :key="image.src">
      <img :src="image.src" alt="" />
    </div>
  </div>
</template>

<script setup>
import img1 from '~/assets/images/product/Rectangle64.png'
import img2 from '~/assets/images/product/Rectangle65.png'
import img3 from '~/assets/images/product/Rectangle66.png'
import img4 from '~/assets/images/product/Rectangle67.png'
import img5 from '~/assets/images/product/Rectangle68.png'

const images = [
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
]
</script>
