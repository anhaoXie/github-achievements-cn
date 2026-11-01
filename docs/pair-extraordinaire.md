# 🤝 Pair Extraordinaire

## 触发条件

**在已被合并的 PR 中包含共同作者（co-authored）提交**。

| 等级 | 门槛 |
| --- | --- |
| 基础 | 1 个 |
| Bronze（x2） | 10 个 |
| Silver（x3） | 24 个 |
| Gold（x4） | 48 个 |

## 怎么拿

Co-authored-by 是 Git 提交信息里的一个标准尾注（trailer），格式：

```text
feat: 一起完成的功能

Co-authored-by: 小明 <xiaoming@example.com>
```

完整步骤：

1. 找到一个真实合作的场景（和同学 / 队友一起写代码、结对提交）。
2. 在提交信息末尾加 `Co-authored-by`，邮箱写**对方 GitHub 账号已验证的邮箱**（或 `对方用户名@users.noreply.github.com`）。
3. 发 PR，把 PR 合入默认分支。
4. 这个 PR 就算 1 个。

多个共同作者可以写多行：

```text
Co-authored-by: A <a@example.com>
Co-authored-by: B <b@example.com>
```

## 关键细节

- **对方必须有 GitHub 账号**，且邮箱能对应到账号，否则只算普通提交。
- **必须合入默认分支**：草稿 PR、未合并 PR 不算。
- **作者和共同作者两边都会被计入**（各自账号的成就）。
- 一个 PR 里有多个 co-authored 提交，仍按 PR 计 1 个（按 PR 累计更稳妥）。
- 邮件里的 `-by` 必须写对：`Co-authored-by:`（Git 不区分大小写，但建议标准写法）。

## 现实建议

这个徽章天然需要「另一个人」：队友、同学、开源搭档。最自然的用法就是真实结对编程——提交里如实署名，不要拿小号刷。
