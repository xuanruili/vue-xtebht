<template>
  <div id="app">
    <!--img alt="Vue logo" src="https://vuejs.org/images/logo.png"-->
    <ReleaseSummary msg="Start to generate your email here!"/>
  </div>
</template>

<script>
import ReleaseSummary from './components/ReleaseSummary.vue'

export default {
  name: 'App',
  components: {
    ReleaseSummary
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
