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
@import '../node_modules/@ironsource/shared-ui/styles/levelplay/fonts';

.wrapper-placeholder {
  @extend %font-body-1;
  padding: 2rem;
  margin: auto;
  //border: $border;
}
</style>
