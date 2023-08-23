<template>
  <div class="login-container">
    <el-form class="login-form" ref="form" :model="form" label-width="80px">
      <div class="title-container">
        <h3>系统登录</h3>
      </div>

      <!-- user -->
      <span class="svg-container">
        111
        <svg-icon icon-class="user" />
      </span>
    </el-form>
  </div>
</template>
``
<script>
export default {
  components: {},
  props: {},
  data() {
    return {
      form: {},
    }
  },
  //计算属性 类似于 data 概念
  computed: {},
  //监控 data 中的数据变化
  watch: {},
  //方法集合
  methods: {},
  //生命周期 - 创建完成（可以访问当前 this 实例）
  created() {},
  //生命周期 - 挂载完成（可以访问 DOM 元素）
  mounted() {},
  beforeCreate() {}, //生命周期 - 创建之前
  beforeMount() {}, //生命周期 - 挂载之前
  beforeUpdate() {}, //生命周期 - 更新之前
  updated() {}, //生命周期 - 更新之后
  beforeDestroy() {}, //生命周期 - 销毁之前
  destroyed() {}, //生命周期 - 销毁完成
  activated() {}, //如果页面有 keep-alive 缓存功能，这个函数会触发
}
</script>
<style scoped>
.login-form {
  border: 1px solid red;
}
</style>
