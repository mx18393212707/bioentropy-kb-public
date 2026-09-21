# 贡献指南 · Contribution Guide

## 协作三原则

1. **公共仓库只读**：不要直接 push 到 `main` 分支。所有改动必须通过 Pull Request。
2. **编辑在本地**：不要在 GitHub 网页里直接编辑文档（会丢失 frontmatter 元数据）。Clone 到本地用 Obsidian 编辑。
3. **PR 必经维护者审核**：所有合并需 1 位 reviewer 通过。

## 工作流（标准 7 步）

```bash
# 1. fork 仓库（GitHub 网页操作，点 Fork 按钮）
# 2. clone 你 fork 的仓库
git clone https://github.com/<your-fork>/bioentropy-kb-public.git

# 3. 进入项目目录，开新分支
cd bioentropy-kb-public
git checkout -b fix/xxx 或 feat/xxx 或 docs/xxx

# 4. 用 Obsidian 打开这个目录编辑
#    - Obsidian → Open another vault → Open folder as vault → 选这个目录

# 5. 编辑后提交（保持 frontmatter 完整，特别是 domain/topic/tags）
git add -A
git commit -m "类型: 简短描述"
git push origin <你的分支名>

# 6. 在 GitHub 上点 "Compare & pull request"
# 7. 等维护者 review + merge
```

## 文档组织

每篇 .md 必须有 YAML frontmatter：

```yaml
---
domain: 熵与涌现·理论根基       # 6 选 1：熵与涌现 / 衰老与细胞稳态 / 蒋组 / PMN·AA / 毕设档案 / 思考
topics:                          # 1-3 个主题标签
  - 生物熵
  - 涌现
  - 复杂系统
tags: [生物熵, 负熵, 头雁分子]   # 1-5 个关键词
share: true                       # 标记为可分享
---
```

工作台 dashboard.md 已按 domain 分 6 列自动分类。新增笔记后会被自动收录。

## 内容禁区

- **不要写个人研究笔记、导师汇报、未发表猜想** —— 这些应该留在维护者本地
- **不要分享带 DOI 但未发表/付费墙的全文**（仅放题录与笔记）
- **不要添加 .docx/.pdf 原始文件**（仓库体积会爆炸）；如需分享请用 .md 转写

## 提 PR 的检查清单

- [ ] frontmatter 完整（domain/topics/tags 都填）
- [ ] 没有删除/重命名其他文档的链接（除非必要并在 PR 描述说明）
- [ ] commit message 写明意图
- [ ] 在 PR 描述里写：改了哪些文档、为什么改、有没有连带影响

## 维护者

- 主维护者：项目组负责人
- 紧急联系：GitHub Issues 或私聊维护者

---

_本仓库从本地完整 vault 按隐私规则筛选同步而来，私密文档（导师汇报、个人批注、毕设档案内部文件）永远不会进入本仓库。如发现误分享，请立即 issue 通知维护者删除。_