<template>
  <div class="login-card">
    <div>
      <el-input v-model="input" placeholder="用户名"/>
    </div>

    <br>
    <div>
      <el-input v-model="input" placeholder="密码"/>
    </div>

    <br>
    <div style="width: 50%; margin: 0 auto">
      <el-button type="primary">登录</el-button>
      <el-button>注册</el-button>
    </div>


  </div>

</template>

<script>
export default {
  name: "Login"
}
</script>

<style scoped>
.login-card {
  width: 50%;
  margin: 0 auto;
}
</style>