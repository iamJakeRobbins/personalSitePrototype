<!-- This is the main template, you can pull in other components here -->
<template>
  <div id="app">
		<MainHeader />
    <img alt="Vue logo" src="./assets/logo.png">
		<MainFooter />
  </div>
</template>

<script>
import MainHeader from './components/MainHeader.vue'
import MainFooter from './components/MainFooter.vue'

export default {
  name: 'app',
  components: {
		MainHeader,
		MainFooter
  }
}
</script>

<style>
#app {
  text-align: center;
}
</style>
