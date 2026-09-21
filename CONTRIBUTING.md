# 贡献指南 · Contribution Guide

> 适用版本：2026-09-21 v2（public 仓库 + 开放贡献）

## 🔄 先看这里：如何获取最新更新

**clone 只需一次，之后用 `pull` 同步即可，不必重新 clone。**

维护者更新知识库后，在你本地仓库目录里执行：

```bash
cd "你的路径/bioentropy-kb-public"
git pull
```

Obsidian 会自动加载变化（新增/修改的笔记立即出现，工作台内容同步刷新）。

### 更省事的办法：让 Obsidian 自动拉取（推荐）

装社区插件 **Obsidian Git**（Settings → 第三方插件 → 浏览 → 搜索 "Git"）：

| 设置项 | 建议值 | 效果 |
|---|---|---|
| Pull updates on startup | 开启 | 每次打开 Obsidian 自动同步一次 |
| Auto pull interval (minutes) | 60（或按需） | 每小时后台自动同步 |
| Disable push | 只读用户可开启 | 避免误推送 |

设置好之后，你完全不用碰命令行——打开 Obsidian 就是最新版。也可以随时用命令面板执行 `Obsidian Git: Pull` 手动拉取。

### 冲突怎么办？

- **只读浏览（没改过文件）**：`git pull` 永远顺畅，不会冲突。
- **本地改过东西**：pull 可能提示冲突。最干净的解法是先把改动收起来：
  ```bash
  git stash        # 暂存本地改动
  git pull         # 同步最新版
  git stash pop    # 恢复你的改动（如冲突会提示你手动选）
  ```
- **想长期贡献**：别直接在主分支改，按下面「方式 2」走 fork + PR，就不会和同步打架。
- **彻底重置**（放弃本地一切改动，只要最新版）：
  ```bash
  git fetch origin
  git reset --hard origin/main
  ```

---

## 三种参与方式（按技术门槛排序）

### 方式 1：反馈建议（零门槛，无需账号也行）

最简单：直接访问 https://github.com/mx18393212707/bioentropy-kb-public/issues → **New issue** → 选类型：
- 📝 **纠错**：发现笔记里有错别字/数据/引用错误 → 维护者会修
- 💡 **建议**：希望增加某领域/某文献/某主题 → 维护者会跟进
- ❓ **提问**：想了解某文献/某概念 → 维护者会回复

> 提交 issue 不需要 GitHub 账号（GitHub 支持匿名 issue，但功能受限）。

### 方式 2：fork + 提 PR（需 GitHub 账号，会用 Obsidian）

适合技术型同事，想实际改文档：

```bash
# 1. 在 GitHub 网页点 Fork 按钮（复制到你的账号下）

# 2. clone 你的 fork
git clone https://github.com/<你的账号>/bioentropy-kb-public.git
cd bioentropy-kb-public

# 3. 装 Obsidian + Dataview + Apex Dashboard 三个软件/插件
#    然后 Open folder as vault → 选这个目录

# 4. 编辑你想改的文档
#    ⚠️ 不要在 GitHub 网页里编辑，会丢失 frontmatter 元数据

# 5. 提交推送
git add -A
git commit -m "类型: 简短描述"
git push origin main

# 6. 在你的 fork 页面点 "Contribute" → "Open pull request"
# 7. 等维护者 review + merge
```

### 方式 3：私有贡献（直接发资料给维护者）

如果你有想要补充的文献/笔记但不方便自己提 PR：

- 直接微信/邮件发给维护者
- 维护者会按格式入库并加署你的贡献记录

## 编辑须知（方式 2 必读）

### 保留元数据

每篇 `.md` 必须保留 YAML frontmatter 完整（dashboard 工作台依赖 domain/topics/tags 字段自动分类）：

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

### 内容禁区

- ❌ **不要写个人研究笔记、导师汇报、未发表猜想**——这些应留在维护者本地
- ❌ **不要分享带 DOI 但未发表/付费墙的全文**（仅放题录与笔记）
- ❌ **不要添加 .docx/.pdf 原始文件**（仓库体积会爆炸）；如需分享请用 .md 转写
- ❌ **不要直接编辑 dashboard.md**——它是自动生成的（保护 frontmatter 不被覆盖）
- ❌ **不要动 `.obsidian/` 目录**——是 Obsidian 本地配置，对他人无用

### PR 检查清单

- [ ] frontend 完整（domain/topics/tags 都填）
- [ ] 没有删除/重命名其他文档的链接（除非必要并在 PR 描述说明）
- [ ] commit message 写明意图
- [ ] 在 PR 描述里写：改了哪些文档、为什么改、有没有连带影响

## 文档组织原则

- 每篇笔记对应一个主题/一篇文献/一次读书
- 内部链接用 `[[笔记名]]` 双向链接
- 段落首行不缩进；用 `##` `###` 标题分级
- 中文标点统一全角
- 引用文献：作者+期刊+年份，DOI 链接放在脚注或文末

## 维护者

- 主维护者：项目组负责人
- 反馈通道：GitHub Issues
- 紧急联系：直接微信私聊维护者

---

_本仓库从本地完整 vault 按隐私规则筛选同步而来，私密文档（导师汇报、个人批注、毕设档案内部文件等）永远不会进入本仓库。如发现误分享，请立即 issue 通知维护者删除。_