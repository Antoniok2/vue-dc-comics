<template>
  <div class="jumbotron">
    <img src="../assets/img/jumbotron.jpg" alt="">
  </div>
</template>

<script>
export default {
  name: 'Jumbotron'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    .jumbotron {
        width: 100%;
        height: 300px;
        background-color: blue;

        img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
    }
</style>
