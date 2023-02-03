<template>
  <div id="app">
  <HelloWorld msg="123456xinyuetoutiao"/>
  git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/seover/-.git
git push -u origin main
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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
