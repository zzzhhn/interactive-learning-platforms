# 交互式学习平台

为香港中文大学（深圳）课程构建的零依赖交互式学习平台。每个单文件 HTML 应用将课程内容转化为测验、可视化知识图谱、案例分析和模拟考试。

> **在线体验**: [zzzhhn.github.io/interactive-learning-platforms](https://zzzhhn.github.io/interactive-learning-platforms/)

## 平台概览

| 课程代码 | 课程名称 | 代码行数 | 核心功能 | 在线演示 |
|---------|---------|---------|---------|---------|
| **FIN4210** | 公司金融 | 22,663 | 知识图谱、模拟考试、案例分析、TVM/NPV/IRR 计算器、分层测验 | [打开](https://zzzhhn.github.io/interactive-learning-platforms/FIN4210/) |
| **FIN3080** | 投资分析与投资组合管理 | 16,272 | 故事模式学习、雷达图对比、公司筛选器、决策树模型 | [打开](https://zzzhhn.github.io/interactive-learning-platforms/FIN3080/) |
| **MAT2002** | 常微分方程 | 14,262 | 斜率场模拟器、实时函数绘图、分步 ODE 求解器、中英双语 | [打开](https://zzzhhn.github.io/interactive-learning-platforms/MAT2002/) |
| **ACT4253** | 商业伦理 | 1,879 | 难度分级测验、收藏标记、伦理框架参考 | [打开](https://zzzhhn.github.io/interactive-learning-platforms/ACT4253/) |

**总计：55,000+ 行，覆盖 4 门课程。**

## 技术栈

| 技术 | 用途 |
|-----|------|
| 原生 JavaScript | 核心逻辑、DOM 操作、测验引擎 |
| MathJax 3 | LaTeX 公式渲染 |
| Chart.js | 金融仪表盘和图表 |
| Plotly | 交互式 2D/3D 图、斜率场 |
| Math.js | 符号数学计算和函数解析 |

## 设计理念

1. **单文件架构** — 每个平台都是一个自包含的 HTML 文件。无需构建工具，无需服务器，浏览器直接打开即可使用。
2. **零运行时依赖** — 所有库通过 CDN 加载并带有回退机制。首次加载后可离线使用。
3. **学习优先** — 每个交互元素都服务于教学目标：通过主动回忆、间隔重复和视觉编码强化概念理解。

## 最后更新

| 平台 | HTML 模板最后更新时间 |
|------|-------------------|
| FIN4210 | 2026 年 4 月 |
| FIN3080 | 2026 年 3 月 |
| MAT2002 | 2026 年 2 月 |
| ACT4253 | 2026 年 1 月 |

> 以上日期为提交至本仓库的最后快照时间，源平台可能在本地持续更新。

## 作者

**钟昊楠** — [bobbyzhong.com](https://bobbyzhong.com) · 香港中文大学（深圳）量化金融专业
