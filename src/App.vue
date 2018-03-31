<template>
  <div class="container" >
    <p v-text="msg"></p>
  </div>   
</template>

<script lang="ts">

export default {
  name: 'app',
  data () {
    return {
      msg: 'Hello world!'
    };
  }
};
</script>

<style scoped>
  html {
    overflow-x: hidden;
  }
  html, body, div, ul, li, p {
    margin: 0;
    padding: 0;
  }
  body {
    font-family: Helvetica Neue, Helvetica, PingFang SC, Hiragino Sans GB, Microsoft YaHei, SimSun, sans-serif;
    background-color: #DEECF9;;
  }
  a {
    text-decoration: none;
    -webkit-tap-heighlight-color: transparent;
  }
</style>

