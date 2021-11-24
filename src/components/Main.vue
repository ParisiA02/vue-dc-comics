<template>
    <div class="container">
        <div class="text-container">
            --> Text goes here    
        </div> 
    </div>
</template>

<script>
export default {
  name: 'Main',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    .container{
        height: 150px;
        width: 100%;
        display: flex;
        align-items: center;
        background-color: #1C1C1C;

        .text-container{
            width: 60%;
            margin: 0 auto;
            color: white;
            font-size: 30px;
        }
    }
</style>