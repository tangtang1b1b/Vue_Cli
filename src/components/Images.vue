<template>
    <div class="img">
      <img :src="link" alt="">
      <h1>bang</h1>
    </div>
</template>
<script>
// @ is an alias to /src

export default {
props:{
  link: String,
  title: String
}
}
</script>