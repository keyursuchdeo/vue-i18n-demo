<template>
  <div id="app">
    <LocaleChanger />
    <HelloI18n />
  </div>
</template>

<script>
import HelloI18n from './components/HelloI18n.vue'
import LocaleChanger from './components/LocaleChanger.vue'

export default {
  name: 'App',
  components: {
    HelloI18n,
    LocaleChanger
  }
}
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
</style>
