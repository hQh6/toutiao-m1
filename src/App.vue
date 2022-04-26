<template>
  <div id="app">
    <h1>黑马头条</h1>
    
    <!-- 路由的出口  不能删 -->
    <router-view/>
  </div>
</template>
<script>
export default {
  // 项目的根组件，给每个组件起个名字，做组件缓存会用到name
    name:"App"
  }

</script>

<style lang="less">

</style>
