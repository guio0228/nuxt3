<script setup lang='ts'>
 useSeoMeta({
  title: 'hello',
  description: 'hello world',
  keywords: 'hello,world',
 })
 const { data } = await useFetch('/api/channel');
</script>

<template>
  <div>
    <h2>首頁</h2>
    <pre>{{ data }}</pre>
  </div>
</template>



<style lang="scss" scoped>

</style>