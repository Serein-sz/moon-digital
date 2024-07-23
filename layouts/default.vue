<script setup lang="ts">
const links = [
  {
    label: '大屏应用'
  },
  {
    label: '三维场景'
  },
  {
    label: '数据管理'
  },
  {
    label: '资产库'
  },
]
</script>
<template>
  <div class="min-h-screen w-screen bg-white dark:bg-black dark:text-white">
    <div class="h-[50px] flex justify-center border-b border-gray-200 dark:border-gray-800">
      <div>
        <UHorizontalNavigation :links class=""></UHorizontalNavigation>
      </div>
    </div>
    <slot />
    <div>Footer</div>
  </div>
</template>
<style scoped></style>
