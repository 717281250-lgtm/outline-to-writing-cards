# outline-to-writing-cards V0.1

把一份过重、难以启动的长篇大纲，重构为 3 张可独立完成的短篇写作卡。

## 文件

- `SKILL.md`：Skill 主文件
- `examples/ai-middle-layer-test-input.md`：用“AI 中间层大洗牌”选题准备的测试输入
- `tests/evaluation-checklist.md`：测试后评分与复盘清单

## 明早怎么测

1. 将 `SKILL.md` 放入你使用的 Skill 目录，或把全文作为系统/项目指令加载。
2. 新建一次干净对话，避免旧上下文替 Skill 偷偷补全信息。
3. 粘贴 `examples/ai-middle-layer-test-input.md` 的内容。
4. 让模型严格使用 `outline-to-writing-cards` Skill 处理。
5. 不要马上修改输出，先用 `tests/evaluation-checklist.md` 打分。
6. 重点记录：哪张卡让你最想立刻写，以及你实际写 30 分钟后卡在哪里。

## 建议测试指令

> 使用 outline-to-writing-cards Skill 处理下面的长篇计划。严格执行删减，不要代写正文，不要因为材料很多就全部保留。输出后告诉我最应该先写哪张卡，以及现在 30 分钟内只做什么。

## V0.1 暂不解决

- 自动联网搜集和核实新闻数据；
- 深挖章节的完整研究工作；
- 三篇完成后的全文润色；
- 自动代写整篇长文。

这些功能应在本 Skill 验证有效后，再拆成后续 Skill。
