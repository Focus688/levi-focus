# levi-focus

Levi Focus 的个人研究站与 Focus688 开源矩阵总站：AI × 硬件的深度研究，每篇结论前置、数据可验证。

**站点**：https://focus688.github.io/levi-focus/

## 这里有什么

| 板块 | 内容 |
|---|---|
| Agent 安全与供应链审计 | Skill 供应链入门、vercel-labs/skills 39.3k★ 审计（v3 实弹复测）、Cindy 7.4k★ 十技能红队审计 |
| 无代码论文复现 | Naive Prompt Optimization（弱复现 ✓）、OverclaimBench（强复现 ✓），代码与 45 文件语料在 [paper-repro](https://github.com/Focus688/paper-repro) |
| AI 时空观 · B2A · GEO | 20 年推演、Meta Muse 与 B2A、SEO→GEO 打法、接口经济（含视频） |

## 仓库结构

```
index.html            站点首页（含开源矩阵与访客分流指南）
assets/site.css       全站公共样式（统一暗色主题）
*.html                11 篇文章（保留原 URL，零断链）
llms.txt              机器可读索引（供 AI 引用）
sitemap.xml           站点地图
robots.txt            爬虫规则（含 AI crawler 显式放行 + Sitemap）
video/                文章配套视频（不参与样式）
```

修改内容时的约定：
- 新增文章 → 在 `index.html` 对应分组加卡片 + `llms.txt` 加条目 + `sitemap.xml` 加 URL。
- 引用任何数字 → 回到对应文章或开源仓库的证据文件核对，不凭记忆。
- 页面共用 `assets/site.css`；页面内 `<style>` 只保留布局，颜色与排版以公共样式为准。

## Focus688 Open Source Matrix

| 项目 | 定位 | 解决什么问题 |
|---|---|---|
| [**agent-security-skills**](https://github.com/Focus688/agent-security-skills) | Agent 安全之「盾」 | 生产 Agent 运维安全技能库：安全安装、静默故障巡检、MCP 权限与 SKILL.md 供应链审计 |
| [**agent-enhancement-playbook**](https://github.com/Focus688/agent-enhancement-playbook) | Agent 增强之「矛」 | 证据分级的生产 Agent 增强手册：C1-C8 有效组合、K1-K9 反模式、12 维实机账本与可执行模板 |
| [**china-policy-radar**](https://github.com/Focus688/china-policy-radar) | 垂直情报活水层 | 结构化、带一手官方链接、机器可读的中国政策索引、跨版本 Diff 与回测记分牌 |
| [**paper-repro**](https://github.com/Focus688/paper-repro) | 无代码论文复现 | 低预算独立复现/证伪无官方代码热门论文：源码 + 复现报告 + 全量日志可追溯 |
| [**levi-focus**](https://focus688.github.io/levi-focus/) | 研究与矩阵总站 | 实弹供应链审计报告、复现拆解文章与 GEO 入口（[GitHub](https://github.com/Focus688/levi-focus)） **← 当前仓库** |

## License

- 文章与站点内容：**CC BY 4.0**（转载须署名并链接原文）
- 代码与样式：**MIT**

详见 [LICENSE](LICENSE)。
