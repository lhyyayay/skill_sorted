# Codex 技能分类包

收录 73 个技能入口。此目录是分类分发资料，尚未安装到应用，未修改任何现有 Agent 配置。

## 安装方式

请根据安装索引逐个选择入口：将 SKILL.md 所在目录注册/链接到目标 Agent 的技能目录。不要仅复制 SKILL.md；保留完整资源和目录关系。分类层不是自动发现目录。

Cursor 可使用项目 .cursor/skills 或 .agents/skills；Antigravity 可显式配置发现路径；DeepSeek Harness 可配置自定义技能根目录或在 .dsh/skills 下注册单层入口。以所安装版本文档为准。目录名 DeeSeek Harness 按用户指定保留。

插件型条目必须完整保留其版本包（含 assets/docs 等），并由宿主提供对应插件服务；它们不是只复制文件即可运行的独立技能。数学建模子工具有单独入口及完整 bundle，原中文说明保留。名称采用英文标识的入口便于跨平台发现。

软件和依赖未安装；需要时装到 D 盘各自独立目录，工程和素材放 E 盘项目目录。图像 API、论文搜索、社交平台等仍需相应账号/密钥/网络。未包含账号凭据。

所有跨 Agent 兼容性均为文件与依赖检查结果，不是逐技能运行验收。grill-me 是手动调用的别名。

| 类别 | 技能 | 入口 | 状态 |
|---|---|---|---|
| 云端办公 | google-docs | [云端办公/google-drive-0.1.22/skills/google-docs/SKILL.md](云端办公/google-drive-0.1.22/skills/google-docs/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 云端办公 | google-drive | [云端办公/google-drive-0.1.22/skills/google-drive/SKILL.md](云端办公/google-drive-0.1.22/skills/google-drive/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 云端办公 | google-drive-comments | [云端办公/google-drive-0.1.22/skills/google-drive-comments/SKILL.md](云端办公/google-drive-0.1.22/skills/google-drive-comments/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 云端办公 | google-sheets | [云端办公/google-drive-0.1.22/skills/google-sheets/SKILL.md](云端办公/google-drive-0.1.22/skills/google-sheets/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 云端办公 | google-slides | [云端办公/google-drive-0.1.22/skills/google-slides/SKILL.md](云端办公/google-drive-0.1.22/skills/google-slides/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 互联网调研 | agent-reach | [互联网调研/agent-reach/SKILL.md](互联网调研/agent-reach/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 交互可视化 | visualize | [交互可视化/visualize-1.0.89/skills/visualize/SKILL.md](交互可视化/visualize-1.0.89/skills/visualize/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 代码维护 | cli-creator | [代码维护/cli-creator/SKILL.md](代码维护/cli-creator/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 代码维护 | gh-address-comments | [代码维护/gh-address-comments/SKILL.md](代码维护/gh-address-comments/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 代码维护 | gh-fix-ci | [代码维护/gh-fix-ci/SKILL.md](代码维护/gh-fix-ci/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 代码维护 | review-agent | [代码维护/review-agent/SKILL.md](代码维护/review-agent/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 代码维护 | security-best-practices | [代码维护/security-best-practices/SKILL.md](代码维护/security-best-practices/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 写作辅助 | write-like-me | [写作辅助/write-like-me-0.1.1/skills/write-like-me/SKILL.md](写作辅助/write-like-me-0.1.1/skills/write-like-me/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 可复用模板 | artifact-template-analytics-dashboard | [可复用模板/openai-templates-0.1.1/skills/artifact-template-analytics-dashboard/SKILL.md](可复用模板/openai-templates-0.1.1/skills/artifact-template-analytics-dashboard/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 可复用模板 | artifact-template-business-review | [可复用模板/openai-templates-0.1.1/skills/artifact-template-business-review/SKILL.md](可复用模板/openai-templates-0.1.1/skills/artifact-template-business-review/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 可复用模板 | artifact-template-design-report | [可复用模板/openai-templates-0.1.1/skills/artifact-template-design-report/SKILL.md](可复用模板/openai-templates-0.1.1/skills/artifact-template-design-report/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 可复用模板 | artifact-template-experiment-analysis | [可复用模板/openai-templates-0.1.1/skills/artifact-template-experiment-analysis/SKILL.md](可复用模板/openai-templates-0.1.1/skills/artifact-template-experiment-analysis/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 可复用模板 | artifact-template-financial-budget | [可复用模板/openai-templates-0.1.1/skills/artifact-template-financial-budget/SKILL.md](可复用模板/openai-templates-0.1.1/skills/artifact-template-financial-budget/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 可复用模板 | artifact-template-investment-committee-memo | [可复用模板/openai-templates-0.1.1/skills/artifact-template-investment-committee-memo/SKILL.md](可复用模板/openai-templates-0.1.1/skills/artifact-template-investment-committee-memo/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 可复用模板 | artifact-template-legal-memorandum | [可复用模板/openai-templates-0.1.1/skills/artifact-template-legal-memorandum/SKILL.md](可复用模板/openai-templates-0.1.1/skills/artifact-template-legal-memorandum/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 可复用模板 | artifact-template-market-trends-report | [可复用模板/openai-templates-0.1.1/skills/artifact-template-market-trends-report/SKILL.md](可复用模板/openai-templates-0.1.1/skills/artifact-template-market-trends-report/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 可复用模板 | artifact-template-minimal-letterhead | [可复用模板/openai-templates-0.1.1/skills/artifact-template-minimal-letterhead/SKILL.md](可复用模板/openai-templates-0.1.1/skills/artifact-template-minimal-letterhead/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 可复用模板 | artifact-template-operating-calendar | [可复用模板/openai-templates-0.1.1/skills/artifact-template-operating-calendar/SKILL.md](可复用模板/openai-templates-0.1.1/skills/artifact-template-operating-calendar/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 可复用模板 | artifact-template-operating-review | [可复用模板/openai-templates-0.1.1/skills/artifact-template-operating-review/SKILL.md](可复用模板/openai-templates-0.1.1/skills/artifact-template-operating-review/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 可复用模板 | artifact-template-project-kickoff | [可复用模板/openai-templates-0.1.1/skills/artifact-template-project-kickoff/SKILL.md](可复用模板/openai-templates-0.1.1/skills/artifact-template-project-kickoff/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 可复用模板 | artifact-template-project-tracker | [可复用模板/openai-templates-0.1.1/skills/artifact-template-project-tracker/SKILL.md](可复用模板/openai-templates-0.1.1/skills/artifact-template-project-tracker/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 可复用模板 | artifact-template-sales-pipeline | [可复用模板/openai-templates-0.1.1/skills/artifact-template-sales-pipeline/SKILL.md](可复用模板/openai-templates-0.1.1/skills/artifact-template-sales-pipeline/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 可复用模板 | artifact-template-simple-dark-mode | [可复用模板/openai-templates-0.1.1/skills/artifact-template-simple-dark-mode/SKILL.md](可复用模板/openai-templates-0.1.1/skills/artifact-template-simple-dark-mode/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 可复用模板 | artifact-template-simple-light-mode | [可复用模板/openai-templates-0.1.1/skills/artifact-template-simple-light-mode/SKILL.md](可复用模板/openai-templates-0.1.1/skills/artifact-template-simple-light-mode/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 可复用模板 | artifact-template-strategy-memorandum | [可复用模板/openai-templates-0.1.1/skills/artifact-template-strategy-memorandum/SKILL.md](可复用模板/openai-templates-0.1.1/skills/artifact-template-strategy-memorandum/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 可复用模板 | artifact-template-system-design | [可复用模板/openai-templates-0.1.1/skills/artifact-template-system-design/SKILL.md](可复用模板/openai-templates-0.1.1/skills/artifact-template-system-design/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 可复用模板 | artifact-template-team-alignment | [可复用模板/openai-templates-0.1.1/skills/artifact-template-team-alignment/SKILL.md](可复用模板/openai-templates-0.1.1/skills/artifact-template-team-alignment/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 可复用模板 | artifact-template-three-statement-forecast | [可复用模板/openai-templates-0.1.1/skills/artifact-template-three-statement-forecast/SKILL.md](可复用模板/openai-templates-0.1.1/skills/artifact-template-three-statement-forecast/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 图像生成 | imagegen | [图像生成/imagegen/SKILL.md](图像生成/imagegen/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 图表绘制 | drawio-skill | [图表绘制/drawio-skill/SKILL.md](图表绘制/drawio-skill/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 学术检索 | dual-paper-search | [学术检索/dual-paper-search/SKILL.md](学术检索/dual-paper-search/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 平台管理 | plugin-management | [平台管理/plugin-management-0.1.0/skills/plugin-management/SKILL.md](平台管理/plugin-management-0.1.0/skills/plugin-management/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 技能管理 | find-skills | [技能管理/find-skills/SKILL.md](技能管理/find-skills/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 技能管理 | openai-docs | [技能管理/openai-docs/SKILL.md](技能管理/openai-docs/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 技能管理 | skill-creator | [技能管理/skill-creator/SKILL.md](技能管理/skill-creator/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 技能管理 | skill-installer | [技能管理/skill-installer/SKILL.md](技能管理/skill-installer/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 技能管理 | template-creator | [技能管理/template-creator-26.1105.12137/skills/template-creator/SKILL.md](技能管理/template-creator-26.1105.12137/skills/template-creator/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 数学建模 | cumcm-step-review | [数学建模/cumcm-step-review/SKILL.md](数学建模/cumcm-step-review/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 数据分析 | excel-live-control | [数据分析/spreadsheets-26.1105.12137/skills/excel-live-control/SKILL.md](数据分析/spreadsheets-26.1105.12137/skills/excel-live-control/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 数据分析 | jupyter-notebook | [数据分析/jupyter-notebook/SKILL.md](数据分析/jupyter-notebook/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 数据分析 | spreadsheets | [数据分析/spreadsheets-26.1105.12137/skills/spreadsheets/SKILL.md](数据分析/spreadsheets-26.1105.12137/skills/spreadsheets/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 数据分析 | xlsx-tools | [数据分析/xlsx-tools/SKILL.md](数据分析/xlsx-tools/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 文档办公 | documents | [文档办公/documents-26.1105.12137/skills/documents/SKILL.md](文档办公/documents-26.1105.12137/skills/documents/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 文档办公 | docx-tools | [文档办公/docx-tools/SKILL.md](文档办公/docx-tools/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 文档办公 | latex-tools | [文档办公/latex-tools/SKILL.md](文档办公/latex-tools/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 文档办公 | pdf-cumcm | [文档办公/pdf-cumcm/SKILL.md](文档办公/pdf-cumcm/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 文档办公 | pdf-openai | [文档办公/pdf-26.1105.12137/skills/pdf/SKILL.md](文档办公/pdf-26.1105.12137/skills/pdf/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 桌面宠物 | create-pet | [桌面宠物/work-pets-0.1.6/skills/create-pet/SKILL.md](桌面宠物/work-pets-0.1.6/skills/create-pet/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 桌面宠物 | pets | [桌面宠物/work-pets-0.1.6/skills/pets/SKILL.md](桌面宠物/work-pets-0.1.6/skills/pets/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 桌面宠物 | update-pet | [桌面宠物/work-pets-0.1.6/skills/update-pet/SKILL.md](桌面宠物/work-pets-0.1.6/skills/update-pet/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 演示文稿 | presentations | [演示文稿/presentations-26.1105.12137/skills/presentations/SKILL.md](演示文稿/presentations-26.1105.12137/skills/presentations/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 电脑操作 | computer-use | [电脑操作/computer-use-26.1103.32239/skills/computer-use/SKILL.md](电脑操作/computer-use-26.1103.32239/skills/computer-use/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 网站与界面设计 | impeccable | [网站与界面设计/impeccable/SKILL.md](网站与界面设计/impeccable/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 网站与界面设计 | personal-intro-site | [网站与界面设计/personal-intro-site/SKILL.md](网站与界面设计/personal-intro-site/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 网站与界面设计 | sites | [网站与界面设计/sites-1.1.4/skills/sites/SKILL.md](网站与界面设计/sites-1.1.4/skills/sites/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
| 网站与界面设计 | sites-remix | [网站与界面设计/sites-1.1.4/skills/sites-remix/SKILL.md](网站与界面设计/sites-1.1.4/skills/sites-remix/SKILL.md) | 原始插件资源包；需由 Codex 提供对应插件工具/运行时，复制不等于已连接 |
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
| 需求讨论 | grill-me | [需求讨论/grill-me/SKILL.md](需求讨论/grill-me/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
| 需求讨论 | grilling | [需求讨论/grilling/SKILL.md](需求讨论/grilling/SKILL.md) | 需配置工具或运行环境；未在目标 Agent 运行验收 |
