<template>
  <div class="scheda">
      <img :src="details.thumb" :alt="details.type">
      <span>{{details.series}}</span>
  </div>
</template>

<script>
export default {
  name: 'Content',
  props: {
    details: Object
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    .scheda {
        width: calc((100% / 6) - 56px);
        height: 40%;
        margin: 28px;
        text-align: center;

        img {
            width: 80%;
            height: 80%;
            margin: 15px;
        }

        span {
            color: white;
        }

        &:hover {
          transform: scale(1.1);
        }
    }
</style>
