<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style lang="scss">
@import "./assets/style/reset.scss";
#app {
  text-align: center;
  color: #2c3e50;
}

a {
  font-weight: bold;
  color: #2c3e50;
  line-height: 50px;
  font-size: 16px;

  &.router-link-exact-active {
    color: #42b983;
  }
}
</style>
