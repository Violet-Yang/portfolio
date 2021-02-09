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
#app {
  font-family: "Noto Sans KR";
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  max-width: 1366px;
}

p, div {
  margin: 0;
  padding: 0;
}

.flex-all-center {
  display: flex;
  align-items: center;
  justify-content: center;

}
</style>
