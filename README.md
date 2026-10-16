# website-blog-writer-enzh-skill

**Website Blog Writer EN/ZH / 网站中英博客写作**

An evidence-controlled blog writing skill used with an AI agent. It turns a brief and accessible approved background into editable English and native Simplified Chinese candidates, a review package and an optional content handoff for a website team.

搭配 AI agent 使用，将写作简报和可访问、获准使用的资料整理成英文主稿、自然简体中文适配稿、审阅包，以及按需提供的网站内容交接。它是一套写作与审阅指南，不是独立运行的研究、作图或发布程序。

## Features / 六项特点

| Feature / 特点 | What it does / 实际能力 |
|---|---|
| Native bilingual adaptation / 双语本地化 | English controls facts and reasoning; Chinese uses native syntax, terminology and rhythm. Compare numbers, examples, attribution and claim strength rather than translating sentence by sentence. / 英文控制事实与论点，中文按母语习惯重写，并核对数字、例子、归因及主张强度。[Workflow steps 3–4 / 对应步骤](skills/website-blog-writer-enzh/SKILL.md#workflow-and-evidence) · [Language rules / 语言规则](skills/website-blog-writer-enzh/references/editorial-workflow.md#native-simplified-chinese) |
| Evidence-controlled claims / 证据分级 | Distinguish user-confirmed facts, permitted observations, claims needing external support and claims to exclude. Missing evidence is flagged, qualified or requested. / 区分已确认事实、允许使用的观察、需要外部证据及不得声称的内容；不编造案例、引用、指标或结果。[Evidence plan / 证据流程](skills/website-blog-writer-enzh/SKILL.md#workflow-and-evidence) · [Claim rules / 主张规则](skills/website-blog-writer-enzh/references/editorial-workflow.md#brief-and-accessible-background) |
| Context reuse and recent-content checks / 背景复用与近期内容去重 | Reuse relevant accessible approved background and check recent content for repetition when it is available. / 复用可访问且获准使用的背景；有近期文章资料时检查重复。资料不可访问时说明限制，不假装完成全站或全网去重。[Writing contract / 写作约定](skills/website-blog-writer-enzh/SKILL.md#establish-the-writing-contract) · [Workflow step 1 / 对应步骤](skills/website-blog-writer-enzh/SKILL.md#workflow-and-evidence) |
| Whole-piece naturalness review / 整篇去模板审阅 | Check mechanical parallelism, forced contrasts, marketing filler, uniform rhythm and Chinese translation patterns while preserving professional meaning. / 检查机械排比、强行反转、营销空话、单一节奏和中文翻译腔；不机械禁词，也不用假故事或故意犯错来“去 AI”。[English review / 英文审阅](skills/website-blog-writer-enzh/references/editorial-workflow.md#english-editorial) · [Chinese review / 中文审阅](skills/website-blog-writer-enzh/references/editorial-workflow.md#native-simplified-chinese) |
| Staged quality gates / 分阶段质量审阅 | Review brief fit, evidence, language and bilingual consistency; apply bounded targeted repairs and identify the exact candidates. / 分别审阅简报、证据、语言及双语一致性；局部修复有上限，记录候选版本，文件交接时记录哈希。审阅通过不等于用户批准或已发布。[Workflow steps 2–5 / 对应步骤](skills/website-blog-writer-enzh/SKILL.md#workflow-and-evidence) · [Repair and integrity rules / 修复与完整性](skills/website-blog-writer-enzh/references/editorial-workflow.md#integrity-and-bounded-repairs) |
| SEO content handoff / SEO 内容交接 | Supply titles, semantic descriptions, article structure and link intent; suggest concise semantic slugs when requested. / 提供标题、语义摘要、正文结构和链接意图，按需建议 slug。路由及语言映射依实际站点规范，未知就留待确认；不等于关键词验证、schema 实现或排名证明。[Output contract / 交付约定](skills/website-blog-writer-enzh/SKILL.md#deliverable-and-stop-point) · [Handoff rules / 交接规则](skills/website-blog-writer-enzh/references/content-handoff.md) |

## Use cases / 适用场景

- **Professional blogs:** explainers, methods and practical guidance for a defined audience. / **专业博客：**面向明确读者的知识解释、方法说明和实用指南。
- **Brand viewpoints:** articulate a supplied position, separating opinion from factual support. / **品牌观点：**表达已给定的立场，区分观点和事实依据，不捏造品牌经历或效果。
- **Cases and experiments:** write from real, permitted records, stating methods, observations and limits without inventing outcomes. / **案例与实验：**基于真实且允许披露的记录写作，说明方法、观察与限制，不虚构客户或实验成果。
- **Bilingual adaptation and revision:** adapt an English factual master into natural Simplified Chinese, or review/edit only the requested language. / **双语适配与修订：**以英文控制事实，进行中文原生改写；也可只审阅或修改指定语言，不必重跑全流程。

## Use / 使用

Use [skills/website-blog-writer-enzh/SKILL.md](skills/website-blog-writer-enzh/SKILL.md). Copy that skill folder into your AI agent's supported skill directory or provide the entrypoint explicitly. The current agent drafts and reviews the prose under these instructions; no external writer is required.

将技能文件夹放入 agent 支持的技能目录，或明确提供入口文件。由当前 agent 按流程写作和审阅，不依赖外部 Writer。已有可访问背景应先复用并简要说明。

## Inputs and outputs / 输入与交付

| Input / 输入 | Output / 交付 |
|---|---|
| Topic, reader, purpose, positioning, language/locale, voice, length and exclusions. / 主题、读者、目的、定位、语言/地区、语气、长度与排除项。 | Editable EN/ZH candidates or the requested subset; Markdown/text by default. / 可编辑中英候选稿或指定部分，默认 Markdown/文本。 |
| Approved facts, source materials and disclosure limits; recent articles when repetition checking is wanted. / 获准使用的事实、来源、披露边界；需要去重时提供近期文章。 | Background-reuse note, key sources, claim/evidence summary, bilingual factual review and material gaps. / 背景复用说明、关键来源、主张与证据摘要、双语事实检查及重要缺口。 |
| Existing drafts and output location; site conventions only when a website handoff is requested. / 已有稿件及交付位置；需要网站交接时提供实际站点规范。 | Candidate identity and concise review/repair notes, plus an optional content handoff. Status: READY FOR REVIEW or DRAFT — BLOCKED with the precise issue. / 候选版本、简短审阅/修复记录及按需内容交接；明确可审阅或草稿阻塞状态。 |

For file-based handoffs, record candidate paths and SHA-256 when file tools are available; do not claim hashes or saved files that were not actually produced. The [output contract](skills/website-blog-writer-enzh/SKILL.md#deliverable-and-stop-point) separates the article body from review notes and unresolved decisions.

文件交接按实际能力记录路径与 SHA-256，不虚构已保存文件或已计算哈希。文章正文与审阅说明分开；候选锁定只是版本完整性记录，不代表用户批准。

## Agent and tool dependencies / Agent 与工具依赖

The core writing workflow needs an AI agent and adequate accessible evidence, not a specific model, paid research provider, website framework or publication adapter. External research, if needed, depends on actual permitted browsing/search tools and source access; reading or writing files and computing hashes depend on host file capabilities. The skill does not grant account access, paid-call authority or access to unavailable history.

核心流程需要 AI agent 和足够、可访问的证据，不绑定模型、付费研究服务、网站框架或发布 adapter。需要补充外部研究时，依赖宿主实际可用且获准的联网工具与来源访问能力；文件读写和哈希依赖对应宿主能力。没有工具或关键证据时，应说明限制、复用充分的已给资料或补问，不能假称已联网、读过历史或完成验证。工具权限和费用遵守当前任务授权。

## Example / 示例

> Draft an English article and native Simplified Chinese adaptation explaining a fictional community workshop's repair-guide checklist. Use only the attached brief, no claimed customer outcomes. Return editable Markdown, a factual comparison and a website content handoff. Do not change a website.

> 根据所附虚构简报，写一篇工作坊指南结构说明的英文博客和自然简体中文稿。不虚构用户成效，交付可编辑 Markdown、事实对照及内容交接，不修改网站。

See [worked example](examples/fictional-guide.md) and [validation cases](VALIDATION.md).

## Limitations / 能力边界

- **Research and repetition:** no bundled autonomous web-crawling or keyword/rank-data feed, and no guarantee of full-site or web-wide deduplication. Checks cover only actual accessible materials. / **研究与去重：**不自带自动爬取或关键词/排名数据源，也不保证全站、全网去重；只检查实际可访问材料。
- **SEO:** semantic content inputs and retrieval-friendly structure are not keyword validation, ranking gains, indexation or AI-citation evidence. Chinese metadata remains editorial/semantic unless dedicated research actually exists. / **SEO：**标题摘要和便于检索的结构不等于关键词验证、排名提升、收录或 AI 引用证明；中文元信息未经专项研究时仍属编辑/语义建议。
- **Images:** no dedicated image-generation/editing workflow or automatic image attachments are implemented in this skill. / **配图：**当前没有实际图片生成、图片编辑或自动图片附件交付流程。
- **Website and publication:** no website mutation, CMS login, Git operations, deployment, scheduling or automatic publication. Site-specific preview/implementation and separate publication-adapter workflows are outside this package. / **网站与发布：**不改网站、不登录 CMS、不操作 Git、不部署、不排期或自动发布；原站点专属实现/预览及独立发布 adapter 不在通用包内。
- **Technical verification:** website, build, structured-data and draft-safety checks remain NOT CHECKED unless actual implementation was inspected in a separately authorized task. Editorial files alone cannot prove them. / **技术验证：**未经另行授权并实际检查实现，网站、构建、结构化数据和草稿安全均标为未检查，不能仅凭文稿声称通过。
- **Privacy and truth:** access is not disclosure permission. Do not expose private source material or invent personal/client experiences, metrics, citations or results. / **隐私与事实：**可访问不等于可公开；不泄露私密原料，不编造个人/客户经历、指标、引用或结果。示例全部虚构。

Adaptation snapshot: `review-draft-1` (2026-10-16), based on private blog production source `0.2.1`. This README clarification documents existing behavior; it adds no tool or publishing capability. Source pilot results do not transfer to this copy. See [provenance](PROVENANCE.md) and [rights](RIGHTS.md). No new open-source license has been selected.

## Portfolio and rights / 作品展示与权利

Published as a demonstration of a reusable writing workflow and a reference for the use cases described above. It does not certify generated output, platform compliance, traffic or business results. The owner authorized this sanitized public snapshot. No new root open-source license is assigned; see [rights](RIGHTS.md) and [provenance](PROVENANCE.md). Identified upstream licenses retain their own permissions, including commercial use where granted.

此公开版展示作者的通用写作工作流，可按上述场景了解和评估。它不是生成质量、平台合规或业务效果的认证。新增与适配部分未指定根开源许可证；实际采用的第三方部分保留原许可，不用“非商用”覆盖其既有权利。

Canonical repository: [website-blog-writer-enzh-skill](https://github.com/HuiyangElsaXie/website-blog-writer-enzh-skill). Related workflows: [general social](https://github.com/HuiyangElsaXie/social-media-post-writer-skill), [EN/ZH blog](https://github.com/HuiyangElsaXie/website-blog-writer-enzh-skill), [RedNote](https://github.com/HuiyangElsaXie/rednote-writer-skill).
