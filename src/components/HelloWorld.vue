<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <div class="amap-wrapper">
      <el-amap class="amap-box" :vid="'amap-vue'"></el-amap>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'vue-amap向你问好'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.amap-wrapper {
  width: 100vw;
  height: 500px;
  margin: auto;
}
</style>
