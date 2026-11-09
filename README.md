# lark-tech-storytelling

飞书文档（Docx / Wiki）默认写作与交互式 SVG 动画规范 Skill（覆盖原生 `lark-doc` / `lark-cli` 内置文风与创建工作流）。

## 核心特性

- **说人话叙事结构**：从「正常全景交互图」到「零上下文 4 段式破题」，删繁就简，让读者在 3～5 分钟内看懂复杂技术问题与 Bug 根因。
- **视觉与排版克制**：短句独立分段、二级嵌套列表代替 `<br/>` 堆砌、克制使用黑体（`<b>`）与浅黄高亮（全文 ≤ 3～5 处）。
- **经典 IDE 亮色交互式 SVG 动画（`<html5-block>`）**：GitHub Light 风格配色、图内极简少字 + 顶部动态说明栏、支持「🚨 故障现场 / ✅ 修复后」切换与分步回放，严格防溢出（Zero Overflow）。
- **极简 `lark-cli` 调用链路**：直接通过 `lark-cli docs +fetch/+create/+update` 读写，省去繁琐的形式化契约路由。

## 使用方式

详见 [`SKILL.md`](SKILL.md)。
