# 2023 年 BYR Team 首页 Vue 版本

BYR Team 首页：https://team.byrio.work/

BYR Team 首页源码：https://github.com/BYRIO/byrteam

## 如何运行？

首先你需要安装 `nodejs` 推荐版本 [node 20](https://nodejs.org/zh-cn)

然后

```bash
git clone https://git.byr.moe/ChocoLZS/byrteam-vue.git
```

```bash
npm install
```

```bash
npm run dev
```

推荐使用 `vscode` 进行代码编写

## 任务

使用本仓库尽可能的复刻首页样式，**可参考源码**，相关素材在源码仓库中

源码是使用 React + Tailwind 编写

你需要使用 vue 来复刻这个首页

## 要求

尽可能还原桌面端的样式，希望能在浏览器窗口拖拽的过程中样式没有明显的跳跃感。

本仓库已经提供了 tailwindcss 的基本用法，但不强制要求使用 tailwindcss。

**不要求还原动画效果**，如果有需要可以参考使用 [@vueuse/motion](https://motion.vueuse.org/)

**不需要还原字体**，用系统默认字体即可

## 章节提示/说明

### `顶部栏`

可以不需要添加链接

### `首屏`

可以不需要添加链接

注意字体大小与样式

### `关于BYR-Team`

无

### `我们的产品`

这一章节，不需要还原动画，被选中的图标需要有一定的变化，比如添加背景颜色，变大等。可以使用数组来模拟选择。

[@click](https://cn.vuejs.org/guide/essentials/event-handling) 事件绑定数组下标

### `部门介绍`

同 `我们的产品` 的思路，不需要实现动画

### `学长学姐说`

关键词：轮播图

如果难度过大可忽略不做，只需要实现一个学长学姐说的卡片

### `招新公告与招新流程`

无

## 相关资料

### Vue

[vue 框架](https://cn.vuejs.org/guide/introduction.html)

有中文

这个是用于编写基本的模块/组件，本次任务主要是要基于这个框架编写

### Tailwindcss

[tailwindcss 样式](https://tailwindcss.com/docs/installation)

英文

这个是 css 样式的一种选择，因为可以省掉想类名的脑细胞，所以推荐一下

### 其它

除此之外你需要学会基本的 git 操作，如 git clone，git add ., git commit, git push

需要一点基本的 js 编程知识
