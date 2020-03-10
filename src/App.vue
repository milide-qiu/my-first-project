<template>
  <div id="app">
    <el-container style="height: 500px">
      <el-header>header</el-header>
      <el-container>
        <el-aside width="200px">aside</el-aside>
        <el-main>
          <HelloWorld></HelloWorld>
        </el-main>
      </el-container>
    </el-container>
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
.el-header{
  background-color: green;
}
.el-aside{
  background-color: blue;
}
</style>
