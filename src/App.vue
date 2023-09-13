<script setup lang="ts">
import Wrapper from './components/Wrapper.vue';
</script>

<template>
  <div class="wrapper-placeholder">
    <Wrapper></Wrapper>
  </div>
</template>

<style scoped lang="scss">
@import 'shared-ui-andyk/styles/scss/fonts';

.wrapper-placeholder {
  @extend %font-body-1;
  padding: 2rem;
  margin: auto;
}
</style>
