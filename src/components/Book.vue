<template>
  <div class="book-container">
    <div class="book-img">
      <img :src="details.thumb" :alt="details.type">
    </div>
    {{details.series}}
  </div>
</template>

<script>
export default {
  name: 'Book',
  props:{
      details: Object,
  }
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .book-container{
    width: calc(100% / 4);
  }
</style>