# 常见问题（FAQ）

## 徽章多久会出现？

官方没有承诺实时。经验值：**几分钟到 24 小时**。如果刚完成操作没看到，先等，再换无痕窗口或直接打开 `https://github.com/<用户名>?tab=achievements` 查看。

## 为什么我合并了 PR 却没有 Pull Shark？

逐条排查：

1. **PR 合入的是默认分支吗？** 合进非默认分支不算。
2. **仓库是公开的吗？** 私有仓库的活动不一定会被统计，用公开仓库验证。
3. **PR 是你开的吗？** Pull Shark 统计你作为作者的 PR。
4. **是不是在 fork 里操作？** fork 内的 issue/PR 不触发，要合入上游。
5. **提交邮箱验证了吗？** `git config user.email` 的邮箱必须已在 GitHub 账号里验证并关联。
6. **数量够吗？** 基础档要 2 个已合并 PR。

## 为什么 YOLO 没出现？

- PR 上有没有任何 review 记录？哪怕一条 comment review 也会让它失效。
- 是不是自己的 PR？合并别人的 PR 不算。
- 是不是已经拿过？一次性成就不会重复出现。

## 为什么 Quickdraw 没出现？

- 关闭时间距创建时间是否已超过 5 分钟？
- 是在 fork 或私有仓库里操作的吗？
- 是否已经拿过（一次性）？

## 徽章可以隐藏吗？

可以：

- 整体：设置 → Profile → `Show Achievements on my profile` 取消勾选。
- 单个：个人主页 → Achievements → 点进某个徽章 → 隐藏。

## 私有贡献能触发成就吗？

社区说法不一致，官方文档没有明确承诺。**可靠路径是公开仓库**：公开的合并、公开的 issue、公开的讨论一定会被统计。

## 刷徽章会怎样？

GitHub 的[可接受使用政策](https://docs.github.com/en/site-policy/acceptable-use-policies/github-acceptable-use-policies)禁止协同造假和虚假活动。已有先例：

- 为刷 Galaxy Brain 在官方社区刷「快速问答」→ 该仓库的成就统计被关闭，参与者被警告。
- 买 star / 互 star 群 → star 被清理，成就被移除。

徽章是玩具，账号才是资产。

## 在哪里能看到完整的官方清单？

GitHub 官方文档里的成就清单页已经下线。目前最全的社区清单是 [Schweinepriester/github-profile-achievements](https://github.com/Schweinepriester/github-profile-achievements)，本仓库的中文整理也基于它 + 实际验证。

## 实测记录（2026-11-01）

| 徽章 | 操作 | 结果 |
| --- | --- | --- |
| Quickdraw | 公开仓库开 issue，12 秒后关闭 | 刷新个人主页立即出现 |
| YOLO | 自己的 PR，无任何 review，直接合并 | 合并后几秒出现 |
| Pull Shark | 合并自己的第 7 个 PR | 计数累加，等级不变（基础档） |

结论：成就统计**不一定**要等 24 小时，常见动作常常几分钟内生效；「24 小时」是官方给的兜底时间，等不到再怀疑操作本身。
