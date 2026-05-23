---
  简述（Repository description，一行）：

  ▎ 基于 React Native / Expo 的智慧校园移动应用，集成课程管理、成绩查询、校园资讯与个人中心等功能。

  ---
  README ：

  # 智育云

  基于 React Native + Expo 构建的智慧校园应用，支持 iOS / Android / Web 多端运行。

  ## 功能模块

  - **首页** — 轮播 Banner、快捷服务入口、校园公告与动态
  - **学习** — 课程列表、课表查询、成绩查看、图书馆
  - **校园** — 校园资讯与校园卡
  - **我的** — 个人中心与设置

  ## 快速开始

  ```bash
  npm install
  npx expo start

  技术栈

  - React Native 0.85 + Expo SDK 56
  - Expo Router（文件式路由）
  - React Native Paper（UI 组件库）
  - TypeScript

  ---
1. 添加截图/演示图
  最能让访客快速了解项目，放 2-3 张手机截图或 GIF。

  2. 添加项目结构树
  ├── app/              # 页面路由
  │   ├── index.tsx     # 首页
  │   ├── learn/        # 学习模块
  │   ├── campus/       # 校园模块
  │   └── profile/      # 个人中心
  ├── components/       # 通用组件
  ├── data/             # Mock 数据
  ├── hooks/            # 自定义 Hooks
  └── utils/            # 工具函数 & 主题

  3. 补充环境要求
  Node.js >= 18
  npm >= 9
