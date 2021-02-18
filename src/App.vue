<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
@import "../assets/css/common.css";

#app {
  font-family: "Noto Sans KR";;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  /*color: #2c3e50;*/
  color: rgba(35,35,35,1);
  /*overflow-x: hidden;*/
}

body {
  margin: 0;
  padding: 0;
}

h1, p, div {
  margin: 0;
  padding: 0;
}

h2, h3 {
  font-weight: normal;
  margin: 0;
}

</style>
