<template>
  <div>
      <Carousel/>
      <Content/>
  </div>
</template>

<script>
import Carousel from '@/components/Carousel/index.vue'
import Content from '@/components/Content/index.vue'

export default {
  name: 'Home',
  components: {
    Carousel,
    Content,
  }
}
</script>
