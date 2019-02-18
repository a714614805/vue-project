<template>
  <div id="app">
    <img src="./assets/logo.png">
    <div id="kuai"></div>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
#kuai {
  height:5999px;
  width:100%;
}
::-webkit-scrollbar {
width:12px;
}
/* 滚动槽 */
::-webkit-scrollbar-track {
-webkit-box-shadow:inset006pxrgba(0,255,0,0.3);
border-radius:10px;
}
::-webkit-scrollbar-track-piece{
  -webkit-box-shadow:2px 2px 2px 2px;
  background : rgba(0,0,255,0.5);
}
/* 滚动条滑块 */
::-webkit-scrollbar-thumb {
border-radius:10px;
background:rgba(255, 0, 0, 1);
-webkit-box-shadow:inset006pxrgba(0,0,0,0.5);
}
::-webkit-scrollbar-thumb:window-inactive {
background:rgba(0, 0, 0, 0);
}
</style>
