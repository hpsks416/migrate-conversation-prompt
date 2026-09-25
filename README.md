> ⚠️ **本仓库已废弃**：内容已并入 [agent-deploy](https://github.com/hpsks416/agent-deploy) 的 skills/migrate-conversation-prompt/ 子目录，请以 agent-deploy 为准。本仓库保留仅供历史归档。

# migrate-conversation-prompt

为已迁移到 DSH 工作区的领域/项目，生成可直接粘贴到「新建会话」的提示词，两类各一条：

## 环境依赖

- 操作系统：Windows
- 运行时：无（纯指令型 skill，由 agent 直接执行）
- 第三方软件：无（仅依赖系统自带的 PowerShell / 标准库）

## 目录结构

    migrate-conversation-prompt/
    ├── SKILL.md    技能入口与工作流
    ├── evals.yaml

## 安装

    # GitHub
    git clone https://github.com/hpsks416/migrate-conversation-prompt.git "$env:USERPROFILE\.dsh\skills\migrate-conversation-prompt"
    # 或 Gitee（国内直连）
    git clone https://gitee.com/hpsks416/migrate-conversation-prompt.git "$env:USERPROFILE\.dsh\skills\migrate-conversation-prompt"

克隆后 DSH 自动重新发现，无需构建。

## License

MIT License. See [LICENSE](LICENSE).

