<template>
  <header>
    <div class="left-header">
      <div class="logo">
        <img src="../assets/dc-logo.png" alt="dc-logo">
      </div>
    </div>
    <div class="right-header">
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header',
}
// data() {
//   return{
//     a:10,
//   };
// }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  header{
    width: 100%;
    background-color: red;
    height: 150px;
  }
</style>
