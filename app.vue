<script setup lang='ts'>
</script>
<template>
  <div class="header">
    <div class="header-nav">
      <NuxtLink to="/">首頁</NuxtLink>
      <NuxtLink to="/api">接口</NuxtLink>
      <NuxtLink to="/PChome">仿切</NuxtLink>
    </div>

  </div>

 <NuxtPage />

</template>
<style lang="scss" scoped>
.header{
  background-color: rgb(255, 133, 133);
  height: 100px;
  .header-nav{
     display: flex;
     justify-content: space-around;
     align-items: center;
     height: 100px;
     a{
       color: white;
       text-decoration: none;
       font-size: 20px;
     }
 
  }
}
</style>