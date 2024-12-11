# 桥梁检测报告系统

## 安装说明

### 安装依赖

```bash
pnpm install
```

### 运行开发环境

```bash
npm run dev
```

### 打包项目前端文件

```bash
npm run build # 运行前检查
npm run build-only # 运行前不检查
```

### 打包 electron 应用

```bash
npm electron:win # 打包windows应用
npm build-electron:win # 打包前端项目 并生成windows应用

npm electron:mac # 打包mac应用
npm build-electron:mac # 打包前端项目 并生成mac应用
```
