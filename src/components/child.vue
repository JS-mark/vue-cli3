<template>
  <div class="box">
    <slot></slot>
  </div>
</template>

<style scoped>
.box {
  width: 750px;
  height: 100%;
}
</style>

<script>
export default {
  created() {
    this.ddd()
  },
  methods: {
    ddd() {
      console.log('dasdasdsad')
    }
  }
};
</script>