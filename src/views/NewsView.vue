<template>
  <div class="about">
    <Images link="https://picsum.photos/300/200/?random=10"/>
    <Images link="https://picsum.photos/300/200/?random=10"/>
    <h1>新聞</h1>
  </div>
</template>
<script>
import Images from '@/components/Images.vue'

export default {
  name: 'HomeView',
  components: {
    Images
  }
}
</script>