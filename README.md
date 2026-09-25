# migrate-conversation-prompt

为已迁移到 DSH 工作区的领域/项目生成现成提示词：读取项目 conversations/*.md 以继续/迁移对话，并生成测试迁移项目完整性的提示词。适用于「生成开场提示词、继续迁移对话、校验迁移项目是否完整」类请求。

## 这是什么

DSH（DeepSeek Harness）skill —— 一个可由 AI agent 按需自动加载的能力单元。克隆到 skill 目录后，DSH 会依据上方描述自动发现并触发它，无需构建。

## 安装

最简单：用 [dsh-config](https://github.com/hpsks416/dsh-config) 的一键脚本 `install.ps1` 批量安装全部 skill。单个安装：

    # GitHub
    git clone https://github.com/hpsks416/migrate-conversation-prompt.git "$env:USERPROFILE\.dsh\skills\migrate-conversation-prompt"
    # 或 Gitee（国内直连更快）
    git clone https://gitee.com/hpsks416/migrate-conversation-prompt.git "$env:USERPROFILE\.dsh\skills\migrate-conversation-prompt"

克隆后 DSH 会自动重新发现，无需重启。更新用：

    git -C "$env:USERPROFILE\.dsh\skills\migrate-conversation-prompt" pull

## 目录结构

    migrate-conversation-prompt/
    ├── SKILL.md    技能入口与工作流
    ├── evals.yaml

## 依赖

无运行时依赖，纯指令型 skill（由 agent 直接执行 Markdown 工作流）。

## License

MIT License. See [LICENSE](LICENSE).
