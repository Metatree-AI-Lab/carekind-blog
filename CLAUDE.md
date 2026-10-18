# CLAUDE.md — careKind Blog

Owner: Lightman · Status: Repository initialised · Last reviewed: 18/10/2026

## 这里是什么
careKind Blog 独立仓库；作为 Company OS 的 `07-marketing-ops/blog/` submodule 使用，也可以单独 clone。

## 必读上下文
- Company OS：`https://github.com/Metatree-AI-Lab/carekind`
- 在 Company OS 中工作时先读根 `AGENTS.md` 和 `07-marketing-ops/CLAUDE.md`。
- 单独 clone 时先读取 Company OS 对应规则；缺少上下文时不可擅自发布。
- 规则：`rules/00-company-rules.md`、`rules/01-operations-rules.md`、`rules/05-changelog-rules.md`。
- 开发前读取代码规则及设计系统；营销内容以主 PRD §6 和 §9 为边界。

## 特有规则
- 只建立了仓库基础，技术栈和网站尚未实现；没有可运行的 build、lint、test 或部署命令。
- 未获得明确授权，不提交、推送或触发 CI/CD；部署必须另行授权。
- 不放入真实住户信息、客户资料、密钥或未获授权素材。
- 对外文章用澳式英语；发布前跑 Company OS 的 marketing-content-publish workflow。
- AI 草稿须人工审核，不编造临床事实、诊断、治疗建议、效果数字或客户案例。
- 若后续新增产品界面，应复用 Company OS 设计系统并交付可查看的完整成果 Demo。
- 本次初始化不创建 workflow、自动发布、付费服务或用户业务写入。

## 关键文件
- `README.md`：用途、仓库关系与当前状态。
- `AGENTS.md`：指向本文件的软链接。
- `CHANGELOG.md`：本仓库变更摘要；Company OS 另记 AI 修改记录。
