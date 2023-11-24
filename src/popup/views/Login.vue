<template>
  <el-main class="page">
    <div class="page__header">
      <el-image
        class="page__logo"
        :src="logo"
      />
      <span class="page__title">EC Amazon Tool</span>
    </div>
    <el-form
      class="page__main"
      ref="form"
    >
      <el-form-item>
        <el-button
          type="success"
          :style="{ marginTop: '20px', width: '100%' }"
          @click="onSubmit"
        >
          一键登录
        </el-button>
      </el-form-item>
    </el-form>
  </el-main>
</template>

<script>
import logo from '@/assets/logo.png'
export default {
  name: 'Login',
  data () {
    return {
      logo
    }
  },
  methods: {
    onSubmit () {
    }
  }
}
</script>

<style lang="less" scoped>
.page__header {
  margin-top: 36px;
  margin-bottom: 50px;
  display: flex;
  align-items: center;
  justify-content: center;
}
.page__main {
  margin-left: 30px;
  margin-right: 30px;

  .el-form-item {
    margin-bottom: 30px;
  }
}
.page__logo {
  margin-right: 16px;
}
.page__title {
  color: #000001;
  font-size: 26px;
  font-weight: 400;
}
</style>
