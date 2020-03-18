<template>
  <div>
    <!-- 面包屑显示区域 -->
    <el-breadcrumb separator="/">
      <el-breadcrumb-item :to="{ path: '/home' }">首页</el-breadcrumb-item>
      <el-breadcrumb-item>商品管理</el-breadcrumb-item>
      <el-breadcrumb-item>参数列表</el-breadcrumb-item>
    </el-breadcrumb>
    <!-- 卡片视图 -->
    <el-card>
    <!-- 警告区域 -->
      <el-alert title="注意：只允许为第三级分类设置相关参数!" type="warning" show-icon :closable="false"></el-alert>
      <!-- 选择商品分类区域 -->
      <el-row class="cat_opt">
        <el-col>
          <span>选择商品分类:</span>
          <!-- 选择商品分类的商品级联选择框 -->
        </el-col>
      </el-row>
    </el-card>
  </div>
</template>

<script>
export default {
  data () {
    return {}
  },
  created () {},
  methods: {}
}
</script>

<style lang="less" scoped>
.cat_opt{
  margin: 15px 0;
}
</style>
