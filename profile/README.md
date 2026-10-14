# ra2-agent · 红色警戒 NPC 研究

让不同策略在相同规则下对战，记录可以追溯的 Elo。社区贡献 Agent；维护者负责测试和正式战绩。

| 仓库 | 用途 |
|---|---|
| [.github](https://github.com/ra2-agent/.github) | 组织入口、治理和社区规范 |
| [rust-ra2](https://github.com/ra2-agent/rust-ra2) | 社区引擎分支、Agent 接入、评测与性能优化 |
| [agent-spec](https://github.com/ra2-agent/agent-spec) | Agent 清单、版本与评测协议 |
| [agent-template](https://github.com/ra2-agent/agent-template) | 可复制的 Rust NPC 开发模板 |
| [agents](https://github.com/ra2-agent/agents) | 社区 PR 提交的 Agent 源码和不可变版本 |
| [leaderboard](https://github.com/ra2-agent/leaderboard) | 维护者提交战绩、确定性重算 Elo |
| [research](https://github.com/ra2-agent/research) | 研究路线、实验记录和资料索引 |

## 现在可以做什么

从模板开发策略 → 向 agents 提交 PR → 维护者审查收录 → 维护者本地测试 → 在 leaderboard 录入比赛 → 重算榜单。

首期使用 [ra2-agent/rust-ra2](https://github.com/ra2-agent/rust-ra2) 的 Rust NPC 接口，开发分支为 ra2-agent。该引擎 Fork 自 [rust-alert/ra2.exe](https://github.com/rust-alert/ra2.exe)，现已公开 Agent 接口、无窗口 Arena、回放和性能优化代码；模板可直接克隆接入。正式赛季仍等待维护者确认名单、规则指纹与测试结果。

首期协议为全图信息、合成场景；其 Elo 只描述对应重写引擎的表现。原版 RA2、YR、其他模组和未来视野/LLM 接口分别制定协议与赛季，不混算。当前没有正式比赛，也没有虚构排名。

参与前阅读 [贡献规则](https://github.com/ra2-agent/agents/blob/main/CONTRIBUTING.md)、[评测协议](https://github.com/ra2-agent/agent-spec/blob/main/docs/evaluation.md) 和 [维护者手册](https://github.com/ra2-agent/leaderboard/blob/main/docs/maintainer-guide.md)。

## 加QQ群

欢迎加群一起pk（959308531）
