<h1>项目说明</h1>
一、项目简介

CraveDelivery 是一个基于 React + TypeScript + Vite 构建的前端项目，主要用于外卖/配送类应用的界面展示与交互。项目采用组件化与页面化结构，包含地址管理、订单流程、支付方式、地图模式等功能页面，适合二次开发与功能扩展。

二、技术栈

前端框架：React 19

开发语言：TypeScript

构建工具：Vite 6

图标库：lucide-react

<img width="444" height="625" alt="image" src="https://github.com/user-attachments/assets/0600941f-feab-4f10-9211-7264df72502e" />

四、环境要求

在运行项目前，请确保本地已安装以下环境：

Node.js ≥ 18（推荐使用 LTS 版本）

npm ≥ 9

可通过以下命令检查：

node -v
npm -v

五、项目依赖说明
运行时依赖（dependencies）
依赖名	说明
react	React 核心库
react-dom	React DOM 渲染
lucide-react	React 图标组件库
开发依赖（devDependencies）
依赖名	说明
vite	前端构建工具
@vitejs/plugin-react	Vite 的 React 插件
typescript	TypeScript 支持
@types/node	Node.js 类型定义
六、安装与运行
1. 安装依赖
在项目根目录下执行：

npm install

2. 启动开发环境
npm run dev


启动成功后，终端会显示本地访问地址，例如：

http://localhost:5173


在浏览器中打开即可预览项目。

3. 构建生产环境代码
npm run build


构建完成后，会在 dist/ 目录生成生产环境文件。

4. 本地预览生产环境
npm run preview


用于模拟生产环境效果。

七、环境变量说明

项目支持通过 .env.local 文件配置本地环境变量，例如：

VITE_API_BASE_URL=http://localhost:3000


以 VITE_ 开头的变量才会被 Vite 注入到前端代码中。

八、开发说明

页面级功能统一放在 pages/ 目录

可复用组件建议放在 components/

全局类型统一维护在 types.ts

全局常量放在 constants.ts

路由与页面切换逻辑可在 App.tsx 中扩展

九、适用场景

外卖 / 同城配送前端项目

React + Vite + TS 学习示例

