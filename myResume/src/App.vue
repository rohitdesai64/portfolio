<template>
  <div id="app">
    <header>
      <span>Rohit Desai</span>
    </header>
    <main style="position: relative;">
      <div class="bann_txt">UI Developer <br> with 2+ year Experience</div>
      <img src="./assets/banner-1.jpg" alt="Vue.js PWA">
      <router-view></router-view>
    </main>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
body {
  margin: 0;
}
.bann_txt {
  position: absolute;
  font-size: 40px;
  color: #fff;
  text-align: center;
  right: 0;
  left: 0;
  top: 20%;
  text-shadow: 8px 6px 6px #ccc;
}

header {
  margin: 0;
  height: 56px;
  padding: 0 16px 0 24px;
  background-color: #35495E;
  color: #ffffff;
}

header span {
  display: block;
  position: relative;
  font-size: 20px;
  line-height: 1;
  letter-spacing: .02em;
  font-weight: 400;
  box-sizing: border-box;
  padding-top: 16px;
}
</style>
