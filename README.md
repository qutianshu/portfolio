# QS · 曲天舒 AI 产品经理作品集

深圳大学人工智能专业（2028 届）· 两段 AI 产品实习 · 主攻 AI 产品经理。

单文件静态站，零构建零依赖，部署于 GitHub Pages。

## 快速开始

```bash
git clone https://github.com/<你的用户名>/<你的用户名>.github.io.git
# 直接双击 index.html 即可本地预览
```

## 站点结构

- `index.html` — 单文件站点（内联 CSS / JS），六大区块：首屏 Hero / 项目案例 / 能力地图 / 经历与证据 / 紧凑简历 / 联系
- `assets/hero-bg.png` — 首屏背景（深圳大学天际线黄昏照）
- `assets/proof/` — 项目运行证据截图（Dify 工作流运行页、邮件交付留痕）

## 部署

见 `部署说明.txt`（GitHub Pages 网页手动方式）。

## 技术要点

- 暗色终端极客风设计系统：底色 `#0B1411` / 荧光绿 `#D6F957`，等宽字体
- 交互：案例卡片折叠、六段式 Tab、11 节点 Pipeline 可点击图、滚动入场动画
- `@media print` 打印白底反转；`prefers-reduced-motion` 适配
