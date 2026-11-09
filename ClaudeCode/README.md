# Claude Code 技能分类包

收录 34 个技能入口，按功能分类整理，保留脚本、模板和参考资料。这是分类分发目录，尚未安装或启用到 Claude Code。

## 安装与发现

Claude Code 支持项目级 `.claude/skills/<skill-name>/SKILL.md` 和个人级 `~/.claude/skills/<skill-name>/SKILL.md`。当前分类目录不是这些默认目录；不要把整个 ClaudeCode 分类目录当作一个技能安装。

按照 `安装索引.json` 选择技能，将其入口目录链接到目标项目 `.claude/skills/<skill-name>`，并完整保留本目录中的资源包。为遵守 D/E 盘约定，建议在 E 盘项目使用项目级目录，通过目录链接复用本分类包；无需把技能复制到 C 盘。

例如，在 PowerShell 中将代码维护技能加入你的 E 盘项目（将“你的项目”换成真实项目名；示例不会自动执行）：

```powershell
New-Item -ItemType Directory -Path 'E:\你的项目\.claude\skills' -Force
New-Item -ItemType Junction -Path 'E:\你的项目\.claude\skills\gh-address-comments' -Target 'E:\skills_sorted\ClaudeCode\代码维护\gh-address-comments'
```

若目标技能名已经存在，先比较，不要覆盖。安装后在 Claude Code 中通过 `/skill-name` 调用，并核对描述是否正确；`grill-me` 是仅手动调用的 grilling 别名。

## 配套资源与限制

数学建模的六个独立子工具均有英文入口和完整 bundle。必须先按入口读取 bundle 内原始 SKILL.md，并以该原始目录解析脚本、模板和相对路径。主技能 cumcm-step-review 内的中文子技能是配套资源，不是需要额外注册的重复入口。

write-like-me 保留完整版本包布局，应从索引指定的内部 skills 目录注册入口，并保留外层资源；使用用户提供样本，或经授权配置 Claude Code 可访问的资料源。没有迁移当前平台的 Gmail、Drive 等连接。

imagegen 使用包内 CLI/API 路线，需要本地 OPENAI_API_KEY 和对应 API 使用权限；Claude 订阅不提供该 API 权限。代码、视频、论文和文档工具仍需对应运行环境、API 或登录态。运行环境和软件按需安装至 D 盘独立目录，工程和素材放 E 盘。

skill-creator、skill-installer、openai-docs、imagegen、grill-me 已加入 Claude Code 宿主说明，其余技能保留流程与资源。原文对 Cursor/Codex 的产品分支和示例并不等于当前宿主；执行时使用 Claude Code 当前可用的终端、文件、搜索或已配置 MCP 工具，不调用不存在的专用接口。

39 个未适配的专用插件与模板入口见 `未收录说明.json`。此分类依据文件格式和工具依赖，不代表 34 个技能均已在 Claude Code 运行通过。未安装软件、配置 MCP、复制账号凭据或修改 Claude Code 现有配置。

官方依据：https://code.claude.com/docs/en/skills

## 技能入口

| 类别 | 技能 | 入口 |
|---|---|---|
| 互联网调研 | agent-reach | [互联网调研/agent-reach/SKILL.md](互联网调研/agent-reach/SKILL.md) |
| 代码维护 | cli-creator | [代码维护/cli-creator/SKILL.md](代码维护/cli-creator/SKILL.md) |
| 代码维护 | gh-address-comments | [代码维护/gh-address-comments/SKILL.md](代码维护/gh-address-comments/SKILL.md) |
| 代码维护 | gh-fix-ci | [代码维护/gh-fix-ci/SKILL.md](代码维护/gh-fix-ci/SKILL.md) |
| 代码维护 | review-agent | [代码维护/review-agent/SKILL.md](代码维护/review-agent/SKILL.md) |
| 代码维护 | security-best-practices | [代码维护/security-best-practices/SKILL.md](代码维护/security-best-practices/SKILL.md) |
| 写作辅助 | write-like-me | [写作辅助/write-like-me-0.1.1/skills/write-like-me/SKILL.md](写作辅助/write-like-me-0.1.1/skills/write-like-me/SKILL.md) |
| 图像生成 | imagegen | [图像生成/imagegen/SKILL.md](图像生成/imagegen/SKILL.md) |
| 图表绘制 | drawio-skill | [图表绘制/drawio-skill/SKILL.md](图表绘制/drawio-skill/SKILL.md) |
| 学术检索 | dual-paper-search | [学术检索/dual-paper-search/SKILL.md](学术检索/dual-paper-search/SKILL.md) |
| 技能管理 | find-skills | [技能管理/find-skills/SKILL.md](技能管理/find-skills/SKILL.md) |
| 技能管理 | openai-docs | [技能管理/openai-docs/SKILL.md](技能管理/openai-docs/SKILL.md) |
| 技能管理 | skill-creator | [技能管理/skill-creator/SKILL.md](技能管理/skill-creator/SKILL.md) |
| 技能管理 | skill-installer | [技能管理/skill-installer/SKILL.md](技能管理/skill-installer/SKILL.md) |
| 数学建模 | cumcm-step-review | [数学建模/cumcm-step-review/SKILL.md](数学建模/cumcm-step-review/SKILL.md) |
| 数据分析 | jupyter-notebook | [数据分析/jupyter-notebook/SKILL.md](数据分析/jupyter-notebook/SKILL.md) |
| 数据分析 | xlsx-tools | [数据分析/xlsx-tools/SKILL.md](数据分析/xlsx-tools/SKILL.md) |
| 文档办公 | docx-tools | [文档办公/docx-tools/SKILL.md](文档办公/docx-tools/SKILL.md) |
| 文档办公 | latex-tools | [文档办公/latex-tools/SKILL.md](文档办公/latex-tools/SKILL.md) |
| 文档办公 | pdf-cumcm | [文档办公/pdf-cumcm/SKILL.md](文档办公/pdf-cumcm/SKILL.md) |
| 网站与界面设计 | impeccable | [网站与界面设计/impeccable/SKILL.md](网站与界面设计/impeccable/SKILL.md) |
| 网站与界面设计 | personal-intro-site | [网站与界面设计/personal-intro-site/SKILL.md](网站与界面设计/personal-intro-site/SKILL.md) |
| 视频制作 | hyperframes | [视频制作/hyperframes/SKILL.md](视频制作/hyperframes/SKILL.md) |
| 视频制作 | hyperframes-animation | [视频制作/hyperframes-animation/SKILL.md](视频制作/hyperframes-animation/SKILL.md) |
| 视频制作 | hyperframes-audio | [视频制作/hyperframes-audio/SKILL.md](视频制作/hyperframes-audio/SKILL.md) |
| 视频制作 | hyperframes-cli | [视频制作/hyperframes-cli/SKILL.md](视频制作/hyperframes-cli/SKILL.md) |
| 视频制作 | hyperframes-core | [视频制作/hyperframes-core/SKILL.md](视频制作/hyperframes-core/SKILL.md) |
| 视频制作 | hyperframes-creative | [视频制作/hyperframes-creative/SKILL.md](视频制作/hyperframes-creative/SKILL.md) |
| 视频制作 | hyperframes-keyframes | [视频制作/hyperframes-keyframes/SKILL.md](视频制作/hyperframes-keyframes/SKILL.md) |
| 视频制作 | hyperframes-registry | [视频制作/hyperframes-registry/SKILL.md](视频制作/hyperframes-registry/SKILL.md) |
| 视频制作 | media-use | [视频制作/media-use/SKILL.md](视频制作/media-use/SKILL.md) |
| 视频制作 | remotion-best-practices | [视频制作/remotion-best-practices/SKILL.md](视频制作/remotion-best-practices/SKILL.md) |
| 需求讨论 | grill-me | [需求讨论/grill-me/SKILL.md](需求讨论/grill-me/SKILL.md) |
| 需求讨论 | grilling | [需求讨论/grilling/SKILL.md](需求讨论/grilling/SKILL.md) |
