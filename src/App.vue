<script setup lang="ts">
// import Typography from '@ironsource/shared-ui/typography';
/*import HelloWorld from './components/HelloWorld.vue'*/
import Wrapper from './components/Wrapper.vue'

// import Banner from '@ironsource/shared-ui/banner';

</script>

<template>
  <div class="wrapper-placeholder">
<!--    <Banner>This is a banner!</Banner>-->

    <Wrapper></Wrapper>

<!--
    <br>
    <Typography variant="chart1">SharedUI Typography component variant - chart1</Typography>
    <br><br>
    <div class="font-title">CSS class font-title</div>
    <br>
    <HelloWorld msg="Vite + Vue" />
-->
  </div>
</template>

<style scoped lang="scss">
@import '../node_modules/@ironsource/shared-ui/styleguide.scss';

.wrapper-placeholder{
  text-align: initial;
  padding: 2rem;
  margin: auto;
  border: $border;
  width: 978px;
}
</style>
