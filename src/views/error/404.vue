<template>
  <el-result
        icon="warning"
        title="404"
        sub-title="页面走丢了"
      >
        <template #extra>
          <el-button type="primary" @click="$event => $router.push('/home')">返回首页</el-button>
        </template>
      </el-result>
</template>

<script setup lang='ts'>

</script>

<style scoped>

</style>