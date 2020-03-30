<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <WhButton text="按钮"></WhButton>
  </div>
</template>

<script>
import WhButton from '@/components/WhButton'

export default {
  name: 'App',
  components: {
    WhButton
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
