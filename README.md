# Bioentropy & Complex System Lab

生物熵课题组的共享知识库镜像，由本地完整知识库按隐私规则筛选同步而来。

**本仓库由 Git 托管 + Obsidian 本地阅读模式构建。**

## 快速上手（6 步）

1. **安装 Obsidian**：[obsidian.md/download](https://obsidian.md/download)（Windows / macOS / Linux 全平台，免费）
2. **安装必装插件**：
   - [Dataview](https://github.com/blacksmithgu/obsidian-dataview) — 工作台列查询
   - [Apex Dashboard](https://github.com/chetachi/obsidian-apex-dashboard) — 七列工作台
3. **Clone 本仓库到本地**：
   ```bash
   git clone https://github.com/mx18393212707/bioentropy-kb-public.git
   ```
4. **Obsidian 打开 `bioentropy-kb-public` 文件夹**（"Open another vault" → "Open folder as vault"）
5. **⭐ 打开工作台（最关键的一步）**：

   按 `Ctrl + P`（macOS: `Cmd + P`）打开命令面板 → 输入 `Apex Dashboard: Open Dashboard` → 回车

   此时会新开一个 tab，里面就是七列工作台。

   > **为什么必须手动这一步？** Apex Dashboard 是注册了一个独立视图（不是接管 markdown 文件的渲染）。即使仓库里已有 `dashboard.md`，你也要主动触发命令才能看到工作台视图。

6. **（可选）设为启动项**：Obsidian Settings → Core Plugins → 启用 **Workspaces** → 命名（例："生物熵知识库"） → 把当前布局保存为 workspace。下次打开 vault 自动恢复。

> **看不到工作台怎么办？**
> - 确认 Dataview 和 Apex Dashboard 都已**启用**（Settings → Community plugins，列表里不是灰色）
> - 重新执行步骤 5（命令面板 → `Apex Dashboard: Open Dashboard`）
> - 如果命令找不到：在 Community plugins 搜 Apex Dashboard → Re-enable → 重启 Obsidian

## 贡献与编辑

请先阅读 [`CONTRIBUTING.md`](./CONTRIBUTING.md) 了解协作流程。