# GitHub 高星项目 & 每周热门榜单

自动更新的 GitHub 项目导航站，由 WorkBuddy 自动化任务维护。

## 站点

| 页面 | 内容 | 更新频率 |
|------|------|----------|
| [`/` (index.html)](https://021902341.github.io/github-top-stars/) | 全量高星总览：1 万星以上 **5442 个项目**，18 类功能分类 + 中文简介，支持搜索/筛选/排序 | 按需 |
| [`/weekly.html`](https://021902341.github.io/github-top-stars/weekly.html) | 每周热门：近 7 天新星 + 活跃高星项目榜单（🆕/🔥 标签），分类 + 中文简介 | 每周日自动 |

## 功能

- 每个项目含：功能分类标签、中文一句话简介（能做什么）、原始描述、语言、星标/Fork、创建年份、GitHub 链接
- 全量站：黑白双主题、语言/年份统计面板、星标区间筛选（10万+/5万+/1万+）
- 周榜：🆕 本周新星 / 🔥 活跃热门 标记、统计周期标注

## 维护

- 文件直接替换 `index.html` / `weekly.html` 后 push 到 `main`，GitHub Actions 自动部署
- 数据来源：GitHub Search API · 分类/简介由规则自动生成，仅供参考
