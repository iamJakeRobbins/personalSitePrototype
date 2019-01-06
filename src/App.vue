<!-- This is the main template, you can pull in other components here -->
<template>
  <div id="app">
		<MainHeader />
		<Tools />
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
		<MainFooter />
  </div>
</template>

<script>
import MainHeader from './components/MainHeader.vue'
import MainFooter from './components/MainFooter.vue'
import Tools from './components/Tools.vue'

export default {
  name: 'app',
  components: {
		MainHeader,
		MainFooter,
		Tools
  }
}
</script>

<style>
#app {
  text-align: center;
}
</style>
