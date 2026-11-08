# Cursor 技能分类包

收录 34 个技能入口。此目录是分类分发资料，尚未安装到应用，未修改任何现有 Agent 配置。

## 安装方式

请根据安装索引逐个选择入口：将 SKILL.md 所在目录注册/链接到目标 Agent 的技能目录。不要仅复制 SKILL.md；保留完整资源和目录关系。分类层不是自动发现目录。

Cursor 可使用项目 .cursor/skills 或 .agents/skills；Antigravity 可显式配置发现路径；DeepSeek Harness 可配置自定义技能根目录或在 .dsh/skills 下注册单层入口。以所安装版本文档为准。目录名 DeeSeek Harness 按用户指定保留。

插件型条目必须完整保留其版本包（含 assets/docs 等），并由宿主提供对应插件服务；它们不是只复制文件即可运行的独立技能。数学建模子工具有单独入口及完整 bundle，原中文说明保留。名称采用英文标识的入口便于跨平台发现。

软件和依赖未安装；需要时装到 D 盘各自独立目录，工程和素材放 E 盘项目目录。图像 API、论文搜索、社交平台等仍需相应账号/密钥/网络。未包含账号凭据。

所有跨 Agent 兼容性均为文件与依赖检查结果，不是逐技能运行验收。grill-me 是手动调用的别名。

| 类别 | 技能 | 入口 | 状态 |
|---|---|---|---|
| 互联网调研 | agent-reach | [互联网调研/agent-reach/SKILL.md](互联网调研/agent-reach/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 代码维护 | cli-creator | [代码维护/cli-creator/SKILL.md](代码维护/cli-creator/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 代码维护 | gh-address-comments | [代码维护/gh-address-comments/SKILL.md](代码维护/gh-address-comments/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 代码维护 | gh-fix-ci | [代码维护/gh-fix-ci/SKILL.md](代码维护/gh-fix-ci/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 代码维护 | review-agent | [代码维护/review-agent/SKILL.md](代码维护/review-agent/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 代码维护 | security-best-practices | [代码维护/security-best-practices/SKILL.md](代码维护/security-best-practices/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 写作辅助 | write-like-me | [写作辅助/write-like-me-0.1.1/skills/write-like-me/SKILL.md](写作辅助/write-like-me-0.1.1/skills/write-like-me/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 图像生成 | imagegen | [图像生成/imagegen/SKILL.md](图像生成/imagegen/SKILL.md) | 已增加宿主适配说明；仍需配置依赖，未运行验收 |
| 图表绘制 | drawio-skill | [图表绘制/drawio-skill/SKILL.md](图表绘制/drawio-skill/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 学术检索 | dual-paper-search | [学术检索/dual-paper-search/SKILL.md](学术检索/dual-paper-search/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 技能管理 | find-skills | [技能管理/find-skills/SKILL.md](技能管理/find-skills/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 技能管理 | openai-docs | [技能管理/openai-docs/SKILL.md](技能管理/openai-docs/SKILL.md) | 已增加宿主适配说明；仍需配置依赖，未运行验收 |
| 技能管理 | skill-creator | [技能管理/skill-creator/SKILL.md](技能管理/skill-creator/SKILL.md) | 已增加宿主适配说明；仍需配置依赖，未运行验收 |
| 技能管理 | skill-installer | [技能管理/skill-installer/SKILL.md](技能管理/skill-installer/SKILL.md) | 已增加宿主适配说明；仍需配置依赖，未运行验收 |
| 数学建模 | cumcm-step-review | [数学建模/cumcm-step-review/SKILL.md](数学建模/cumcm-step-review/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 数据分析 | jupyter-notebook | [数据分析/jupyter-notebook/SKILL.md](数据分析/jupyter-notebook/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 数据分析 | xlsx-tools | [数据分析/xlsx-tools/SKILL.md](数据分析/xlsx-tools/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 文档办公 | docx-tools | [文档办公/docx-tools/SKILL.md](文档办公/docx-tools/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 文档办公 | latex-tools | [文档办公/latex-tools/SKILL.md](文档办公/latex-tools/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 文档办公 | pdf-cumcm | [文档办公/pdf-cumcm/SKILL.md](文档办公/pdf-cumcm/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 网站与界面设计 | impeccable | [网站与界面设计/impeccable/SKILL.md](网站与界面设计/impeccable/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 网站与界面设计 | personal-intro-site | [网站与界面设计/personal-intro-site/SKILL.md](网站与界面设计/personal-intro-site/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 视频制作 | hyperframes | [视频制作/hyperframes/SKILL.md](视频制作/hyperframes/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 视频制作 | hyperframes-animation | [视频制作/hyperframes-animation/SKILL.md](视频制作/hyperframes-animation/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 视频制作 | hyperframes-audio | [视频制作/hyperframes-audio/SKILL.md](视频制作/hyperframes-audio/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 视频制作 | hyperframes-cli | [视频制作/hyperframes-cli/SKILL.md](视频制作/hyperframes-cli/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 视频制作 | hyperframes-core | [视频制作/hyperframes-core/SKILL.md](视频制作/hyperframes-core/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 视频制作 | hyperframes-creative | [视频制作/hyperframes-creative/SKILL.md](视频制作/hyperframes-creative/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 视频制作 | hyperframes-keyframes | [视频制作/hyperframes-keyframes/SKILL.md](视频制作/hyperframes-keyframes/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 视频制作 | hyperframes-registry | [视频制作/hyperframes-registry/SKILL.md](视频制作/hyperframes-registry/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 视频制作 | media-use | [视频制作/media-use/SKILL.md](视频制作/media-use/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 视频制作 | remotion-best-practices | [视频制作/remotion-best-practices/SKILL.md](视频制作/remotion-best-practices/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 需求讨论 | grill-me | [需求讨论/grill-me/SKILL.md](需求讨论/grill-me/SKILL.md) | 已增加宿主适配说明；仍需配置依赖，未运行验收 |
| 需求讨论 | grilling | [需求讨论/grilling/SKILL.md](需求讨论/grilling/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
