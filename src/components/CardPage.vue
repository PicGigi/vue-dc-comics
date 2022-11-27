<template>
  <div class="card">
    <div class="card-info">
      <img
        :src="cardImg"
        alt=""
      >
      <span>{{ cardTitle }}</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'CardPage',
  props: {
    // eslint-disable-next-line vue/require-default-prop
    cardImg: String,
    // eslint-disable-next-line vue/require-default-prop
    cardTitle: String,
  },
};
</script>

<style lang="scss" scoped>
  .card {
    display: flex;
    flex-direction: column;
    color: white;
    font-weight: bold;
    padding: auto;
    margin-bottom: 3rem;

    .card-info{
      width: min-content;

      img{
        margin-bottom: .5rem;
      }
    }
  }
</style>
