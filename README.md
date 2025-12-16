# Christmas Tree - 手势控制圣诞树

使用 Three.js 和 MediaPipe 构建的交互式 3D 圣诞树，支持手势控制。

## 技术栈

- **Three.js** - 3D 图形渲染
- **MediaPipe** - 手势识别
- **Vite** - 构建工具
- **Vite Plugin WASM** - WebAssembly 支持

## 安装

```bash
npm install
```

## 开发

```bash
npm run dev
```

开发服务器将在 `http://localhost:3000` 启动

## 构建

```bash
npm run build
```

构建产物将输出到 `dist/` 目录

## 预览构建结果

```bash
npm run preview
```

## 功能

- 🎄 3D 圣诞树渲染
- ✋ 手势识别控制
- 📸 照片上传功能
- 📱 移动端支持
- 🎨 视觉效果（粒子、光晕等）

## 手势控制

- **握拳** - 聚合成树
- **张开手** - 星云散开
- **向右划动** - 惯性拨动
- **捏合手指** - 抓取照片

## 浏览器支持

- Chrome/Edge (推荐)
- Safari (iOS 需要 HTTPS)
- Firefox

## 注意事项

- 移动端需要 HTTPS 环境（localhost 除外）
- 首次使用需要授权摄像头权限
- iOS 设备上可能需要更长的初始化时间




