<script setup>
import IconVue from "@/assets/vue.svg";
import IconBYRTeam from "@/assets/byrteam-logo.svg?url";
</script>

<template>
  <div class="space-y-12 mt-12">
    <div class="vanilla-container">
      <h3 class="title">tailwind样式文件内引入编写示例<br />使用图片引入svg</h3>
      <img :src="IconBYRTeam" class="logo" alt="Byr logo" />
    </div>
    <div class="flex flex-col items-center">
      <h3 class="font-bold">tailwind行内编写示例<br />直接import导入svg</h3>
      <icon-vue
        class="h-12 w-12 cursor-pointer hover:scale-125 transition-transform"
      />
    </div>
    <div class="tailwind-style-container">
      <h3 class="font-bold">
        tailwind样式文件内引入编写示例<br />使用图片引入svg
      </h3>
      <img src="/vite.svg" class="tailwind-style-logo" alt="Vite logo" />
    </div>
  </div>
</template>

<style scoped>
/* 以下两个样式是类名css文件引入tailwind样式 */
.tailwind-style-container {
  @apply flex flex-col items-center;
}
.tailwind-style-logo {
  @apply h-12 w-12 cursor-pointer hover:scale-125 transition-transform;
}

/* 以下是原生样式写法 */
.vanilla-container {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.vanilla-container .title {
  font-weight: bold;
}
.vanilla-container .logo {
  height: 48px;
  cursor: pointer;
  transition: transform 0.3s;
}
.vanilla-container .logo:hover {
  transform: scale(1.25);
}
</style>
