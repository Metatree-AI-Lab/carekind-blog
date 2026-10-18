# 澳洲养老行业每日新闻博客

Owner: Lightman · Status: Scheduled; drafts only · Last reviewed: 18/10/2026

## 任务
每天早上 08:00，按 Australia/Brisbane（AEST，UTC+10），联网核实澳洲养老行业新闻，选择一个新角度，撰写一篇完整原创澳式英语文章，保存为本地 Markdown 草稿。

## 输出
- 文件：`articles/YYYY-MM-DD-english-slug.md`，按 Brisbane 当天日期。
- 读者：澳洲养老机构运营者、护理主管及护士。
- 通常约 700–1,000 words，按信息量调整。
- 文件头：Owner、Status: Draft — awaiting human review、Last reviewed，并记录标题、新闻时间窗口、生成日期与时区。
- 关键事实就近附原始链接；文末保留来源标题、发布者、发布日期和查阅日期。
- 完成后用中文报告文章标题、绝对路径、新闻日期与来源，以及待人工审核状态。

## 新闻核实与内容质量
优先最近 24–48 小时的澳洲本地新闻，不足时查最近 7 天，并如实标明日期。优先政府、监管机构和行业机构原始公告，结合可靠澳洲新闻或行业媒体。必须打开阅读来源，区分事件发生与报道日期、实施与提案，不以搜索摘要代替核实。

主题覆盖 residential aged care、home care、workforce、机构运营、服务质量及行业政策。先检查已有文章避免重复；每日只写一篇，说明事实、依据、实际关联及读者可核查的事项，不凑字数、不大段复制、不编造数字或采访。无足够新且可核实的新闻时报告原因，不冒充新消息。

## 审核与边界
遵循 Company OS 规则，保存前按 marketing-copy-check 和 tga-boundary-check 自审。草稿须人工审核后另行决定是否发布。涉及法律或监管时附：Operational reference only; not legal advice.

不生成诊断、治疗或用药建议，不声称保证合规、效果或未验证的产品能力。不放入真实住户或客户资料。不覆盖已有文章及人工修改；当日稿件存在时报告现有路径，避免重复生成。

## 自动化
Codex 自动化 ID：`carekind`，名称：careKind 澳洲养老新闻日报与博客。任务在本聊天中定时运行并写入此仓库工作目录；保存本地文件不等于 GitHub 仓库已更新。

不自动 commit、push、发布、触发 CI/CD 或使用付费服务。运行依赖 Codex 本地自动化执行环境和网络可用；首次定时运行及实际文章生成尚待验证。
