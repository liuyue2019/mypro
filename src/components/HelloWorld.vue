<template>
    <div class="service">
        <el-button type="primary">确定1</el-button>
        <el-button>取消1</el-button>
    </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="less">
  .service{
    width: 100%;
    height: 30px;
    /*.el-button{*/
      /*width: 20px;*/
      /*height: 20px;*/
    /*}*/
  }
</style>
