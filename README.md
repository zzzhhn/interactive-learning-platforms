# Interactive Learning Platforms

Interactive, zero-dependency learning platforms built for university courses at CUHK-Shenzhen. Each single-file HTML application transforms lecture content into quizzes, visual knowledge maps, case studies, and exam simulators.

> **Live demo**: [zzzhhn.github.io/interactive-learning-platforms](https://zzzhhn.github.io/interactive-learning-platforms/)

## Platforms

| Course | Subject | Lines | Key Features | Live Demo |
|--------|---------|-------|-------------|-----------|
| **FIN4210** | Corporate Finance | 22,663 | Knowledge graph, mock exams, case studies, TVM/NPV/IRR calculators, tiered quizzes | [Open](https://zzzhhn.github.io/interactive-learning-platforms/FIN4210/) |
| **FIN3080** | Investment Analysis & Portfolio Management | 16,272 | Story-driven learning, radar chart comparisons, company screener, decision tree models | [Open](https://zzzhhn.github.io/interactive-learning-platforms/FIN3080/) |
| **MAT2002** | Ordinary Differential Equations | 14,262 | Slope field simulator, real-time function graphing, step-by-step ODE solver, bilingual (EN/ZH) | [Open](https://zzzhhn.github.io/interactive-learning-platforms/MAT2002/) |
| **ACT4253** | Business Ethics | 1,879 | Difficulty-tagged quizzes, star bookmarks, ethical framework reference | [Open](https://zzzhhn.github.io/interactive-learning-platforms/ACT4253/) |

**Total: 55,000+ lines across 4 platforms.**

## Feature Highlights

- **Interactive Quizzes** — Multiple-choice, fill-in-the-blank, and tiered difficulty assessments with instant feedback
- **Knowledge Graphs** — Visual concept maps showing topic dependencies and learning paths
- **Real-time Visualizations** — Slope field simulators, candlestick-style financial charts, radar comparisons
- **Case Studies** — Scenario-based problem solving (capital budgeting, portfolio construction)
- **Financial Calculators** — Time Value of Money, NPV, IRR, WACC computation tools
- **Mock Exams** — Full-length practice tests with auto-grading and wrong-answer review
- **Bilingual Support** — English/Chinese toggle where applicable
- **Dark/Light Theme** — System-aware theme switching

## Tech Stack

| Technology | Purpose |
|-----------|---------|
| Vanilla JavaScript | Core logic, DOM manipulation, quiz engines |
| [MathJax 3](https://www.mathjax.org/) | LaTeX formula rendering |
| [Chart.js](https://www.chartjs.org/) | Financial dashboards and bar/line charts |
| [Plotly](https://plotly.com/javascript/) | Interactive 2D/3D plots, slope fields |
| [Math.js](https://mathjs.org/) | Symbolic math computation and function parsing |
| HTML/CSS | Single-file architecture, CSS custom properties for theming |

## Design Philosophy

1. **Single-file architecture** — Each platform is one self-contained HTML file. No build step, no bundler, no server. Open the file in any browser and it works.
2. **Zero external dependencies at runtime** — All libraries are loaded via CDN with fallback. Works offline after first load.
3. **Learning-first** — Every interactive element serves a pedagogical purpose: reinforcing concepts through active recall, spaced repetition, and visual encoding.

## Last Updated

| Platform | HTML Template Last Updated |
|----------|---------------------------|
| FIN4210 | April 2026 |
| FIN3080 | March 2026 |
| MAT2002 | February 2026 |
| ACT4253 | January 2026 |

> These dates reflect the last snapshot committed to this repository. The source platforms may continue to be updated locally.

## Author

**Bobby Zhong** — [bobbyzhong.com](https://bobbyzhong.com) · CUHK-Shenzhen, Quantitative Finance
