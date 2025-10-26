<template>
  <BusinessCard name="John Doe" phone="1234567890" email="psjsnajjbj@gmail.com" />
</template>

<script>
import BusinessCard from './components/BusinessCard.vue'

export default {
  name: 'App',
  components: {
    BusinessCard
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
