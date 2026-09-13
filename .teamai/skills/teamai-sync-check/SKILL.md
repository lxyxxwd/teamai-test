---
name: teamai-sync-check
display_name: TeamAI 同步检查
display_name_en: TeamAI Sync Check
description: 验证当前 AI 工具是否已成功加载 TeamAI 分发的测试技能；当用户要求检查 TeamAI Skill 同步或调用 teamai-sync-check 时使用。
description_zh: 验证当前 AI 工具是否已成功加载 TeamAI 分发的测试技能。
description_en: Confirms that the current AI tool successfully loaded the test skill distributed by TeamAI.
version: 1.0.1
author: TeamAI Sync Test
user-invocable: true
---

# TeamAI Sync Check

Respond with exactly this sentence:

`TeamAI Skill 同步成功：当前工具已加载 teamai-sync-check。`

Do not run commands, modify files, or perform network requests for this check.
