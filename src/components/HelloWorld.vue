<template>
  <div class="hello">
    <el-button type="primary" @click="visible = true">按钮</el-button>
    <el-dialog :visible.sync="visible" title="hell-world"><p>HelloWorld111</p></el-dialog>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data() {
    return {
      visible: false
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
