<template>
  <div id="app">
    <img src="./assets/logo.png">
    <HelloWorld :msg="msg" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
    data() {
        return {
            msg:'Welcome to Your Vue.js App'
        }
    },
}
</script>

<style>
@import './style/globalStyle.less'
</style>
