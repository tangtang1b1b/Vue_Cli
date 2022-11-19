<template>
  <div class="hello">
    <div class="img" v-for="(magg) in 4" :key="magg">
      <img :src="require(`@/assets/${magg+1}.jpg`)"/>
    </div>
    <div>
      <h1>{{ title }}</h1>
      <h1>12321321</h1>
      <button>gg</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
    title: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.hello{
  width: 100%;
  display: flex;
  color: #000;
}
.img{
  background-color: #ddd;
  margin-bottom: 10px;
  width: 100%;
  img{
    width: 100%;
  }
}
</style>
