<script setup lang="ts">
import Wrapper from './components/Wrapper.vue';
</script>

<template>
  <div class="wrapper-placeholder">
    <Wrapper></Wrapper>
  </div>
</template>

<style scoped lang="scss">
// Shared lib styleguide v3
@import '../node_modules/@ironsource/shared-ui/styleguide.scss';

.wrapper-placeholder {
  padding: 2rem;
  margin: auto;
}
</style>
