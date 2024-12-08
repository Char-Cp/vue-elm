<template>
  <div id="app">
    <!-- 使用 Element UI 组件的示例 -->
    <el-container>
      <el-header>
        <h1>Vue + Element UI 项目</h1>
      </el-header>
      
      <el-main>
        <el-row>
          <el-button type="primary">主要按钮</el-button>
          <el-button type="success">成功按钮</el-button>
        </el-row>
      </el-main>
    </el-container>
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      // 这里可以添加数据
    }
  }
}
</script>

<style>
#app {
  font-family: Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
</style> 