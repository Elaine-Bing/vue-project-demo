<template>
  <div id="app">
    <h1>app</h1>
    <P class="p"></P>
    <van-button type="info">信息按钮</van-button>
  </div>
</template>

<script>
export default {
  name: "App"
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.p{
  width: 100px;
  height: 100px;
  background-color: blueviolet;
}
</style>
