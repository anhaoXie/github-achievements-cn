# 徽章等级对照表

部分徽章有 **x2 / x3 / x4** 三个等级，分别对应 Bronze / Silver / Gold。等级不影响功能，只是图标外观和角标不同。

## 等级标签

| 等级 | 角标 | 颜色 |
| --- | --- | --- |
| 基础（Base） | 无 | 原色 |
| Bronze | x2 | 铜色 `#F9BFA7` |
| Silver | x3 | 银色 `#E1E4E4` |
| Gold | x4 | 金色 `#FAE57E` |

## 全部等级门槛

### Pull Shark（合并的 PR 数）

| 等级 | 门槛 |
| --- | --- |
| 基础 | 2 |
| Bronze（x2） | 16 |
| Silver（x3） | 128 |
| Gold（x4） | 1024 |

### Pair Extraordinaire（含共同作者的已合并 PR 数）

| 等级 | 门槛 |
| --- | --- |
| 基础 | 1 |
| Bronze（x2） | 10 |
| Silver（x3） | 24 |
| Gold（x4） | 48 |

### Galaxy Brain（被采纳的答案数）

| 等级 | 门槛 |
| --- | --- |
| 基础 | 2 |
| Bronze（x2） | 8 |
| Silver（x3） | 16 |
| Gold（x4） | 32 |

### Starstruck（仓库 star 数）

| 等级 | 门槛 |
| --- | --- |
| 基础 | 16 |
| Bronze（x2） | 128 |
| Silver（x3） | 512 |
| Gold（x4） | 4096 |

### 无等级的徽章

Quickdraw、YOLO、Public Sponsor 都是一次性成就，没有等级。

## 识别方法

1. 打开 `https://github.com/<用户名>?tab=achievements`。
2. 徽章图片角落有等级角标（x2 / x3 / x4）。
3. 点开或悬停徽章，弹窗里的 `History` 会显示当前等级名与解锁进度（例如 `100% unlocked`）。

## 注意

- 门槛是**累计值**，不是增量：到了 16 个合并 PR 就是 x2，不会从 0 重新计算。
- 等级只升不降（删除仓库等情况除外，以 GitHub 实际行为为准）。
- 刷等级没有意义，Gold 档门槛（1024 个合并 PR / 4096 star）是长期真实贡献的副产品。
