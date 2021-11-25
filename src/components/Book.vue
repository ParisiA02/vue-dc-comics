<template>
  <div class="book-container">
    <div class="book-img">
      <img :src="details.thumb" :alt="details.type">
      {{details.series.toUpperCase()}}
    </div>
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
    width: 15%;
    min-width: 180px;
    margin: 20px 0 40px 0;

    .book-img{
      width: 180px;
      height: 180px;
      margin: auto;
      padding: 0 10px;
      color: white;
      font-size: 10px;

      img{
        width: 100%;
        height: 100%;
        object-position: top;
        object-fit: cover;
        margin-bottom: 10px;
      }
    }
  }
</style>