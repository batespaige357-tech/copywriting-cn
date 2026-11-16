# Copywriting CN

**保留你的表达，把中文页面文案写清楚。**

基于 [coreyhaines31/marketingskills 的 copywriting](https://github.com/coreyhaines31/marketingskills/tree/main/skills/copywriting) 的小幅中文适配。独立维护、非官方。

## 保留上游核心

先读产品背景，再区分空白起草、恢复原稿声音、局部修改；逐单元打磨，用可感知、可证实、具有区分度的三问核对文案。保留原正文和三个完整参考文件，不另造一套方法。

## 小幅中文补充

- 保留用户的中文口语和专业表达，避免改成统一公文腔。
- 英文长句规则按含义迁移，不生硬变成中文固定字数。
- 中文 CTA 说清实际下一步，费用、周期和条件保持事实。
- 缺少数据或背书时指出具体所需材料，不编造转化率或客户评价。

## 安装与调用

```bash
npx skills add batespaige357-tech/copywriting-cn --skill copywriting-cn
```

对助手说“用 copywriting-cn 修改这段中文页面文案，保留我的语气”；Codex 可使用 `$copywriting-cn`。也可将 `skills/copywriting-cn` 整个文件夹放到助手的技能目录，保留 references 子目录。

技能本身不需要脚本或额外 API Key。引用到的其他 marketing skills 为相关可选能力，本仓库不打包整个上游技能集合。没有示例网页、效果截图或发布功能。

## 来源与验证

MIT，保留 Corey Haines 版权、完整许可和上游正文中的来源致谢。参考提交、修改范围见 [CHANGES.md](CHANGES.md)。

已检查原正文和三个参考完整保留、UTF-8、相对链接与技能格式。尚未完成真实模型文案盲测或转化实验；参考资料的历史指标不能作为本项目成绩。未执行前端编译。
