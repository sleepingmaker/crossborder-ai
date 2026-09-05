# CrossBorder AI

AI-powered cross-border e-commerce research platform for product analysis, competitor research, user pain-point discovery, and listing optimization.

基于 AI 的跨境电商研究平台，支持产品分析、竞品调研、用户痛点挖掘与 Listing 优化。

## 项目目标

CrossBorder AI 面向跨境电商新人、运营人员和产品研究人员，尝试把原本分散的市场调研步骤整合为一个 AI 辅助工作流：输入商品/市场信息，输出结构化的市场研究结果。

## MVP v0.1

第一版只验证“AI 能否把已有数据整理成有用的市场研究报告”，暂不优先解决复杂爬虫和反爬问题。

输入：
- 商品关键词
- 目标市场
- Listing 文本或 CSV/JSON 评论数据
- 可选的 Reddit/社区讨论数据

输出：
- 市场概览
- 竞品分析
- 价格区间
- 高频关键词
- 用户痛点
- 差评问题
- 用户画像
- 产品机会点
- Listing 优化建议
- 风险提示

## 当前阶段

`Phase 0 — 学习参考项目 + 明确 MVP`

当前不追求快速堆代码，优先完成：
1. 跑通参考项目；
2. 理解核心数据流；
3. 明确 MVP 输入和输出；
4. 再开始实现最小闭环。

## 学习原则

AI 可以辅助写代码，但项目负责人必须能解释：
- 这个功能解决什么问题；
- 数据从哪里来、到哪里去；
- 为什么这样设计；
- 如果需求改变，应该改哪里。

## 文档

- `docs/PRD.md`：产品需求与 MVP 边界
- `AGENTS.md`：Cursor / Codex 协作规则

## License

MIT
