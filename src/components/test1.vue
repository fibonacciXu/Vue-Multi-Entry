<template>
  <div>
    <h2>
      in test1.vue
    </h2>

    <p>{{ count }}</p>
    <p>
      <button @click="$store.dispatch('increment')">+</button>
      <button @click="$store.dispatch('decrement')">-</button>
    </p>
  </div>
</template>

<script type="text/javascript">
export default {
  name: "test1",
  computed: {
    count() {
      return this.$store.state.count;
    }
  }
};
</script>

<style rel="stylesheet/scss" lang="scss" scoped></style>
