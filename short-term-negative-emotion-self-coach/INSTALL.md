# 安装方式

这里给你 3 种最实用的安装方式。

## 方式 1：直接复制到 Claude Code / Codex 本地 skills 目录

适合你自己或熟悉本地文件的人。

### Claude Code / 通用 `.agents`

把整个目录复制到：

```bash
~/.agents/skills/short-term-negative-emotion-self-coach-0.1.0
```

例如：

```bash
cp -R short-term-negative-emotion-self-coach/packages/default ~/.agents/skills/short-term-negative-emotion-self-coach-0.1.0
```

如果要装永澄版：

```bash
cp -R short-term-negative-emotion-self-coach/packages/yongcheng-style ~/.agents/skills/short-term-negative-emotion-self-coach-yongcheng-style-0.1.0
```

### Codex `.codex`

也可以复制到：

```bash
~/.codex/skills/short-term-negative-emotion-self-coach
```

## 方式 2：导入 `.skill` 打包文件

如果目标环境支持导入 `.skill` 文件，直接用 `dist` 下的打包产物。

默认版：

```text
short-term-negative-emotion-self-coach-default.skill
```

永澄版：

```text
short-term-negative-emotion-self-coach-yongcheng-style.skill
```

## 方式 3：从 GitHub 拉取

适合要发给别人长期复用。

只要把这个 repo 发给对方，然后让对方复制 `packages/default` 或 `packages/yongcheng-style` 到自己的 skills 目录即可。

如果后续放到公开 GitHub repo，最稳的说法是：

```bash
git clone <repo-url>
cp -R <repo>/packages/default ~/.agents/skills/short-term-negative-emotion-self-coach-0.1.0
```

## 安装后怎么试

建议先用这些输入试一轮：

```text
别人已经开始赚到钱了，我连网站都没上线，我感觉自己特别差。
```

```text
我搞了这么久都没做出来，我觉得自己可能根本就不是这块料。
```

## 一个提醒

有些运行环境不会热刷新 skills。

如果你复制完目录后没有立刻生效：

- 新开一个会话
- 或重启当前 Agent / Claude Code 会话
