<template>
  <div id="app">
    <navbar/>
    <router-view/>
  </div>
</template>

<script>
import navbar from './components/navbar'

export default {
  name: 'App',
  components: {
    navbar
  }
}
</script>

<style>
  #app{
    background: rgb(237,232,239);
    background: linear-gradient(29deg, rgba(237,232,239,1) 0%, rgba(89,97,97,1) 93%);
  }
</style>
