<template>
  <div id="app">
    <page-header></page-header>
    <page-body></page-body>
    <page-footer></page-footer>
  </div>
</template>

<script>
import PageFooter from './components/PageFooter.vue';
import PageHeader from './components/PageHeader.vue'
import PageBody from './components/PageBody.vue'

export default {
  name: 'App',
  components: {
    PageFooter,
    PageHeader,
    PageBody
  },
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
