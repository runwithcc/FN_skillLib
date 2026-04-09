# FN_skillLib

易仁永澄的技能储备库。

这里放的不是零散提示词，而是可以直接交给 Agent 使用、继续迭代、继续分发的技能包与方法资产。

## 这个仓库里有什么

目前仓库会逐步沉淀三类东西：

- 可直接安装的 Agent Skill
- 与 Skill 配套的测试用例、安装说明与打包产物
- 一些还没有完全 skill 化、但已经具备方法论价值的认知资产

## 推荐入口

### 短期负面情绪自我教练 Skill

这是一个帮助副业 / 创业新手在短期负面情绪中：

- 先被接住
- 再被澄清
- 最后回到行动

的 Agent 技能包。

入口目录：

- `short-term-negative-emotion-self-coach/`

包含内容：

- `packages/default`
- `packages/yongcheng-style`
- `TEST-CASES.md`
- `INSTALL.md`
- `dist/*.skill`

## 直接下载

默认版 `.skill`：

- [下载 default](https://raw.githubusercontent.com/runwithcc/FN_skillLib/master/short-term-negative-emotion-self-coach/dist/short-term-negative-emotion-self-coach-default.skill)

永澄风格版 `.skill`：

- [下载 yongcheng-style](https://raw.githubusercontent.com/runwithcc/FN_skillLib/master/short-term-negative-emotion-self-coach/dist/short-term-negative-emotion-self-coach-yongcheng-style.skill)

## 使用方式

如果你只是想快速试用，优先看：

- `short-term-negative-emotion-self-coach/INSTALL.md`
- `short-term-negative-emotion-self-coach/TEST-CASES.md`

如果你想直接安装 skill，去看：

- `short-term-negative-emotion-self-coach/packages/default`
- `short-term-negative-emotion-self-coach/packages/yongcheng-style`

## 这个仓库的定位

它不是一个“炫功能”的仓库。

我更希望它逐步变成：

- 一套可复用的 Agent 能力库
- 一套能真正帮助普通人推进现实问题的技能资产
- 一个从认知、方法到技能包逐步成形的公开技能仓
