# GitHub 成就徽章中文指南

GitHub 个人主页侧栏的 **Achievements（成就）** 是一组小徽章，记录你在 GitHub 上的关键动作：合并 PR、5 分钟内关掉 issue、在 Discussions 里回答被采纳、仓库拿到 star、赞助开源项目……

本仓库把 **截至 2026 年 11 月** 还能拿到的徽章、触发条件、等级门槛和真实获取路径整理成中文，并记录徽章不显示时该查什么（24 小时延迟、fork 不算、邮箱未验证……）。

> 徽章是 GitHub 的趣味系统，不是技能证明。请用真实贡献获取，不要刷量。
> GitHub 的[可接受使用政策](https://docs.github.com/en/site-policy/acceptable-use-policies/github-acceptable-use-policies)禁止协同造假、虚假活动，刷出来的成就可能被移除。

## 一览：现在能拿到的 7 个徽章

| 徽章 | 触发条件 | 等级门槛（x2 / x3 / x4） |
| --- | --- | --- |
| 🦈 **Pull Shark** | 你的 Pull Request 被合并 | 2 / 16 / 128 / 1024 个 |
| ⚡ **Quickdraw** | 打开 issue 或 PR 后 5 分钟内关闭 | 一次性 |
| 😅 **YOLO** | 未经 code review 合并自己的 PR | 一次性 |
| 🤝 **Pair Extraordinaire** | 已合并的 PR 里有共同作者（co-authored）提交 | 1 / 10 / 24 / 48 个 |
| 🧠 **Galaxy Brain** | 在 Discussions 中的回答被采纳为答案 | 2 / 8 / 16 / 32 个 |
| ⭐ **Starstruck** | 自己创建的仓库获得 star | 16 / 128 / 512 / 4096 个 |
| ❤️ **Public Sponsor** | 通过 GitHub Sponsors 赞助开源 | 一次性 |

详细玩法见 [`docs/`](docs/)：

- [Pull Shark](docs/pull-shark.md) · [YOLO](docs/yolo.md) · [Quickdraw](docs/quickdraw.md)
- [Pair Extraordinaire](docs/pair-extraordinaire.md) · [Galaxy Brain](docs/galaxy-brain.md)
- [Starstruck](docs/starstruck.md) · [Public Sponsor](docs/public-sponsor.md)

## 已经不发放 / 还没上线

| 徽章 | 状态 |
| --- | --- |
| Arctic Code Vault Contributor | 已停发（2020 年北极代码库计划快照） |
| Mars 2020 Contributor | 已停发（当年 NASA 直升机项目的指定仓库） |
| Heart On Your Sleeve | 测试中，未正式上线（用 ❤️ 回应内容） |
| Open Sourcerer | 测试中，未正式上线（在多个公开仓库有 PR 合入） |
| Finishing Touch | 新徽章，「改进 GitHub UI 质量的已合并 PR」，外部贡献者是否可拿官方未说明 |
| Proxima Pioneer / Staffshipper / Staffuser | GitHub 内部徽章，普通用户拿不到 |

详见 [docs/retired-and-disabled.md](docs/retired-and-disabled.md)。

## 徽章不出现？先查这 6 条

1. **24 小时延迟**：成就统计不是实时的，最多可能要等一天，换无痕窗口刷新再看。
2. **必须合入默认分支**：合进 `main` / `master` 才算数。
3. **fork 里的操作不算**：在 fork 里开 issue / PR 不触发；要合进上游仓库。
4. **邮箱必须已验证并关联到账号**：提交里的作者邮箱如果没在 GitHub 账号里验证，这次提交就不被识别。
5. **私有仓库不稳妥**：可靠路径是用公开仓库；公开活动一定会被统计。
6. **旧徽章不会重发**：Quickdraw、YOLO 是一次性成就，拿过就不会再出现。

更多排查见 [docs/faq.md](docs/faq.md)。

## 在哪里看

- 个人主页 → 侧栏 **Achievements** 区域；或直接打开 `https://github.com/<你的用户名>?tab=achievements`
- 鼠标悬停在徽章上会显示详情弹窗（解锁时间、历史记录）
- 设置里可以整体关闭显示（`Show Achievements on my profile`），也可以单独隐藏某个徽章

## 关于等级

部分徽章有 Bronze（x2）/ Silver（x3）/ Gold（x4）等级，等级标签显示在徽章图片角落。等级门槛见上表与各徽章详情页。

## 参考

- [GitHub 2022 年成就系统公告](https://github.blog/2022-06-09-introducing-achievements-recognizing-the-many-stages-of-a-developers-coding-journey/)
- 社区维护的完整清单：[Schweinepriester/github-profile-achievements](https://github.com/Schweinepriester/github-profile-achievements)
- [创建多作者提交（co-authored commit）](https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/creating-a-commit-with-multiple-authors)
- [GitHub Sponsors](https://github.com/sponsors)

## 许可

[MIT](LICENSE)
