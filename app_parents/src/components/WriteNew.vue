<template>
  <!--匿名动态-->
  <mt-header class="WriteNew-header" title="匿名动态">
    <router-link to="/Work" slot="left">
      <mt-button icon="back">返回</mt-button>
    </router-link>
    <mt-button icon="more" slot="right"></mt-button>
  </mt-header>
</template>

<script>
  import { Header } from 'mint-ui';
  export default {
    name: "WriteNew"
  }
</script>

<style scoped>
  .WriteNew-header {
    background-color: #B3C0D1;
    font-size: 1.6rem;
    width: 100%;
    height: 50px;
  }
  *{
    -webkit-tap-highlight-color: rgba(255,0,0,0);
    -webkit-appearance:none;
  }
</style>
