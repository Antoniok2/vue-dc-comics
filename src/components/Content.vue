<template>
  <div class="contents">
      <h1>
          >---- Content goes here ---<
      </h1>
  </div>
</template>

<script>
export default {
  name: 'Content'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .contents {
    display: flex;
    align-items: center;
    height: 100px;
    background-color: black;

    h1 {
        margin-left: 10% ;
        color: white;
    }
  }
</style>