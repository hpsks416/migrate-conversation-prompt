# migrate-conversation-prompt

为已迁移到 DSH 工作区的领域/项目，生成可直接粘贴到「新建会话」的提示词，两类各一条：

## 适用对象

- DeepSeek Harness（DSH）用户：一个可由 AI agent 按需自动加载的 skill，克隆即用、无需构建。
- 把对话迁移到 DSH 工作区、生成续聊提示词的人

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
