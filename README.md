# careKind Blog

Owner: Lightman · Status: Repository initialised; unpublished · Last reviewed: 18/10/2026

## 用途
careKind Blog 的独立私有仓库，用于后续维护博客内容、素材及网站实现。当前只建立仓库基础，没有文章、网站、Demo 或发布流程。

## 仓库关系
- 独立仓库：`Metatree-AI-Lab/carekind-blog`
- Company OS：`Metatree-AI-Lab/carekind`
- Submodule 路径：`07-marketing-ops/blog/`
- 完整规则和营销流程以 Company OS 为准；单独 clone 时也须查阅其 `AGENTS.md`、`rules/00-company-rules.md`、`rules/01-operations-rules.md`。

## 工作方式
在本仓库独立管理版本；经授权提交并推送后，在 Company OS 更新 submodule 指针。两边提交、推送和部署分别授权。

对外内容使用澳式英语。发布前按 Company OS 的 `11-workflows/marketing-content-publish.md` 完成审核；不得包含真实住户数据、未经证实的效果数字或超出实际能力的声明。

## 当前状态
未选择网站技术栈，未接入域名、托管、付费服务或 CI/CD。本次仅建立仓库，不代表博客产品已交付。

## 每日新闻写作

每天 Brisbane 时间早上 08:00，自动查找澳洲养老行业新闻并写成澳式英语 Markdown 草稿，保存到 `articles/`。规范见 [DAILY-BLOG.md](DAILY-BLOG.md)。仅本地保存，待人工审核，不自动推送或发布。
