<template>
  <DashboardContainer/>
  <MainTemplate/>
</template>

<script>
import DashboardContainer from './components/DashboardContainer.vue'
import MainTemplate from './components/MainTemplate.vue'

export default {
  name: 'App',
  components: {
    DashboardContainer,
    MainTemplate,
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
}
</style>
