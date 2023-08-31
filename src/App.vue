<script setup lang="ts">
import Wrapper from './components/Wrapper.vue';
</script>

<template>
  <div class="wrapper-placeholder">
    <Wrapper></Wrapper>
  </div>
</template>

<style scoped lang="scss">
@import '../node_modules/@ironsource/shared-ui/styleguide.scss';

.wrapper-placeholder {
  text-align: initial;
  padding: 2rem;
  margin: auto;
  border: $border;
  width: calc(100wh - 100px);
}
</style>
