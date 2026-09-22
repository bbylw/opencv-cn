# OpenCV 中文文档网站

基于 [OpenCV 5.0 官方文档](https://docs.opencv.org/5.0/) 整理的中文静态站点，在线访问：<https://opencv.ndjp.net>

## OpenCV：开源计算机视觉库

### 资源

* 主页：<https://opencv.org>
  * 课程：<https://opencv.org/courses>
* 文档：<https://docs.opencv.org/5.x/>
* 问答论坛：<https://forum.opencv.org>
  * 旧论坛（只读）：<http://answers.opencv.org>
* 问题追踪：<https://github.com/opencv/opencv/issues>
* 额外的 OpenCV 功能：<https://github.com/opencv/opencv_contrib>
* 捐赠给 OpenCV：<https://opencv.org/support/>

### 贡献方式

在开始提交 Pull Request 之前，请先阅读[贡献指南](https://github.com/opencv/opencv/wiki/How_to_contribute)。

#### 指南要点：

* 一个 Pull Request 对应一个问题；
* 选择正确的目标分支；
* 包含测试与文档；
* 提交前清理「手滑」式的无效提交；
* 遵循[代码风格指南](https://github.com/opencv/opencv/wiki/Coding_Style_Guide)。

### 更多资源

* [提交你的 OpenCV 项目](https://form.jotform.com/233105358823151)，加入 opencv.org 上的 Community Friday 栏目
* [订阅 OpenCV YouTube 频道](https://youtube.com/@opencvofficial)，观看 OpenCV Live 一小时直播节目
* [在 LinkedIn 关注 OpenCV](https://linkedin.com/company/opencv/)，获取每日计算机视觉与 AI 前沿动态
* [申请成为 OpenCV 志愿者](https://form.jotform.com/232745316792159)，协助组织活动与线上推广并扩大影响力
* [在 Mastodon 关注 OpenCV](https://mastodon.social/@opencv)（Fediverse 联邦宇宙）
* [在 X 关注 OpenCV](https://x.com/opencvofficial)
* [OpenCV.ai](https://opencv.ai)：OpenCV 团队提供的计算机视觉与 AI 开发服务。

## 网站开发

本站内容涵盖：简介、安装配置、核心模块、像素数据类型、教程导航、DNN 深度学习、多语言示例、社区资源、贡献指南与常见问题。

### 技术栈

- [Astro 7.3.3](https://astro.build)
- TypeScript 6.0.3（strict）
- [Tailwind CSS 4.3.3](https://tailwindcss.com)
- [Bun](https://bun.sh) 包管理与运行

### 本地运行

```bash
bun install
bun run dev        # 开发服务器
bun run build      # 生产构建（输出 dist/）
bun run preview    # 预览构建结果
bunx astro check   # 类型检查
```

推送至 `main` 分支后，GitHub Actions 会自动构建并部署到 GitHub Pages（自定义域：opencv.ndjp.net）。
