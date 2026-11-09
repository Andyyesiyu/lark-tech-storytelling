# lark-tech-storytelling

飞书文档（Docx / Wiki）默认写作与交互式 SVG 动画规范 Skill（覆盖原生 `lark-doc` / `lark-cli` 内置文风与创建工作流）。适用于架构拆解、机制原理解析、技术方案演进对比、以及问题/Bug 深度复盘。

## 目录结构

- [`SKILL.md`](SKILL.md)：核心文风、章节叙事结构、排版克制规则与 `<html5-block>` 交互动画规范。
- [`assets/interactive-svg-template.html`](assets/interactive-svg-template.html)：通用 GitHub Light 风格交互式 SVG 动画模板（支持单模式全景分步流转与双模式对比切换）。

## 核心特性

- **从全景到说人话破题**：先用纯主干交互图建立全局直觉，再用零上下文友好的 3～4 个短段落讲透核心机制或关键矛盾。
- **视觉与排版克制**：短句独立分段、二级嵌套列表代替 `<br/>` 堆砌、克制使用黑体（`<b>`）与浅黄高亮（全文 ≤ 3～5 处）。
- **通用 IDE 亮色交互式 SVG 动画（`<html5-block>`）**：内置 `MODES` + `steps` 数据驱动模板，自适应「单模式全景演进」与「双模式方案/状态对比」，严格防溢出（Zero Overflow）。
- **极简 `lark-cli` 调用链路**：直接通过 `lark-cli docs +fetch/+create/+update` 读写，省去繁琐的形式化契约路由。
