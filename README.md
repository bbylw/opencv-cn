# OpenCV 中文文档网站

基于 [README](../README.md) 内容与 [OpenCV 5.0 官方文档](https://docs.opencv.org/5.0/) 整理的中文静态站点。

## 技术栈

- [Astro 7.3.3](https://astro.build)
- TypeScript **6.0.3**（strict）
- [Tailwind CSS 4.3.3](https://tailwindcss.com)
- [Bun](https://bun.sh) 包管理与运行

## 开发

```bash
bun install
bun run dev        # 开发服务器
bun run build      # 生产构建（输出 dist/）
bun run preview    # 预览构建结果
bunx astro check   # 类型检查
```

## 页面结构

| 路径 | 内容 |
| --- | --- |
| `/` | 首页：5.0 亮点、应用领域、语言接口、4.x→5.0 对比 |
| `/intro` | 简介：版本要点、模块结构、9 大核心 API 概念 |
| `/install` | 安装：pip / CMake / g++ / 源码 / 平台速查与排查 |
| `/modules` | 5.0 主模块（分组）+ 生态与版本时间线 |
| `/datatypes` | 像素数据类型完整参考（含 5.0 新增类型） |
| `/tutorials` | 教程导航：学习路径、Python 目录、C++ 主题 |
| `/dnn` | DNN 模块：引擎、后端、模型格式、预处理 API |
| `/examples` | 多语言示例：基础 / imgproc / 特征 / 视频 / DNN / JS |
| `/resources` | README 资源汇总与社区渠道 |
| `/contribute` | 贡献指南要点 |
| `/faq` | 常见问题（可按分类筛选） |
