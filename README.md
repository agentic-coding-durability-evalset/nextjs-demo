# Next.js Demo

一个基于 [Next.js](https://nextjs.org/) 16 的 React 全栈应用示例项目。展示了如何使用 Next.js App Router、TypeScript 和 Tailwind CSS 构建现代化的 Web 应用。

## 技术栈

- **Next.js**: 16.0.0
- **React**: 19.2.0
- **TypeScript**: 5.x
- **Tailwind CSS**: 4.x
- **ESLint**: 9.x

## 项目结构

```
nextjs-demo/
├── app/
│   ├── layout.tsx        # 根布局组件
│   ├── page.tsx          # 首页
│   ├── globals.css       # 全局样式
│   └── favicon.ico       # 网站图标
├── public/               # 静态资源
│   ├── next.svg
│   ├── vercel.svg
│   └── ...
├── next.config.ts        # Next.js 配置
├── tsconfig.json         # TypeScript 配置
├── postcss.config.mjs    # PostCSS 配置
├── eslint.config.mjs     # ESLint 配置
└── README.md
```

## 功能特性

- App Router 架构
- 服务端渲染 (SSR)
- 静态站点生成 (SSG)
- 自动代码分割
- 图片优化
- 暗色模式支持
- TypeScript 支持
- Tailwind CSS 样式

## 快速开始

### 前置要求

- Node.js 18 或更高版本
- npm, yarn, 或 pnpm

### 安装和运行

```bash
# 克隆项目
git clone <repository-url>
cd nextjs-demo

# 安装依赖
npm install
# 或
yarn install
# 或
pnpm install

# 运行开发服务器
npm run dev
# 或
yarn dev
# 或
pnpm dev
```

应用将在 `http://localhost:3000` 启动。

### 构建和部署

```bash
# 构建生产版本
npm run build

# 启动生产服务器
npm start

# 运行 Lint
npm run lint
```

## 项目特点

### App Router

项目使用 Next.js 13+ 的 App Router，提供：
- 基于文件系统的路由
- 布局和模板
- 加载状态
- 错误处理
- 路由组和并行路由

### 页面结构

- **`app/layout.tsx`**: 根布局，包含所有页面的共享 UI
- **`app/page.tsx`**: 首页组件
- **`app/globals.css`**: 全局样式文件

### 样式系统

使用 Tailwind CSS 4.x 进行样式设计：
- 实用优先的 CSS 框架
- 暗色模式支持
- 响应式设计
- JIT 编译

## 开发

### 热重载

Next.js 提供快速刷新功能，修改代码会自动更新浏览器。

### TypeScript

项目完全使用 TypeScript，提供类型安全：
- 严格的类型检查
- 自动完成和 IntelliSense
- 编译时错误检测

### 代码质量

- **ESLint**: 代码 linting
- **TypeScript**: 类型检查
- **Prettier**: 代码格式化（如配置）

## 部署

### Vercel（推荐）

Next.js 由 Vercel 创建，可以一键部署：

```bash
# 安装 Vercel CLI
npm i -g vercel

# 部署
vercel
```

### 其他平台

Next.js 可以部署到任何支持 Node.js 的平台：
- Docker
- AWS
- Google Cloud
- Azure
- 自托管服务器

## 参考资源

- [Next.js 文档](https://nextjs.org/docs)
- [Next.js 学习中心](https://nextjs.org/learn)
- [Next.js GitHub](https://github.com/vercel/next.js)
- [Vercel 部署](https://vercel.com/new)
