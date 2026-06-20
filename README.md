# 军伟观察短视频口播文案创作 Skill

基于 Hermes Agent 的 short-video-script skill，支持双角色口播结构（军伟开场 + 小零口播全文）。

## 核心能力

- 🎬 双角色脚本结构 SOP（军伟开场~15秒 + 小零口播全文）
- 📊 关键数据表 + 宣发标签规范
- 🛡️ 品牌安全措辞规范
- 🔴🟡🟢 三级审核自查清单
- 📋 参考案例（EP17 v1.4 / EP18 v1.5 双角色定稿版）

## 适用场景

- 短视频口播文案创作（知识科普/财经分析类）
- AI 辅助内容生产流水线
- 军伟观察系列内容标准化输出

## 文件结构

```
SKILL.md                          # 主技能文件（416行）
references/
├── brand-safety-guidelines.md    # 品牌安全规范
├── cross-doc-sync-lessons.md     # 跨文档同步经验
├── doubao-review-examples.md     # 豆包审核示例
├── dual-role-transition.md       # 双角色结构转换指南
├── ep17-double-review-lessons.md # EP17 双审核经验
├── ep17-v14-oral-patterns.md     # EP17 v14 口播范式
├── ep18-cross-doc-sync-failure.md # EP18 跨文档同步故障
├── ep18-final-lessons.md         # EP18 终稿经验
├── ep18-v14-revision-patterns.md  # EP18 v14 修订范式
└── structured-review-template.md # 结构化审核模板
```

## 使用方式

本 Skill 设计为 Hermes Agent 的 SKILL.md 格式，可直接导入 `~/.hermes/skills/creative/` 目录使用。

## License

MIT © 2026 socneo
