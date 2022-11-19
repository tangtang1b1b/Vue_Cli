<template>
    <Carousel v-model="value" loop>
        <CarouselItem v-for="magg in 4" :key="magg">
            <div class="demo-carousel">
              <img :src="require(`@/assets/${magg+1}.jpg`)"/>
            </div>
        </CarouselItem>
        <!-- <CarouselItem>
            <div class="demo-carousel">2</div>
        </CarouselItem>
        <CarouselItem>
            <div class="demo-carousel">3</div>
        </CarouselItem>
        <CarouselItem>
            <div class="demo-carousel">4</div>
        </CarouselItem> -->
    </Carousel>
</template>
<script>
    export default {
        data () {
            return {
                value: 0
            }
        }
    }
</script>
<style>
img{
  width: 20%;
}
</style>