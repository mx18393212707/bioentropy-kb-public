---
dashboard: true
banner:
  quote: "Life feeds on negative entropy."
  author: "Erwin Schrödinger《生命是什么》"
  image: "https://images.pexels.com/photos/2307638/pexels-photo-2307638.jpeg"
columns:
  - name: 🧭 课题主线（项目组）
    color: "#ef4444"
    type: memo
  - name: 🌀 熵与涌现 · 理论根基
    color: "#6366f1"
    type: dataview
    height: 461
    half: true
    dataview:
      query: "LIST\nWHERE domain = \"熵与涌现·理论根基\"\nFLATTEN topics AS 主题\nGROUP BY 主题\nSORT 主题 ASC"
  - name: 🦢 头雁分子与蒋组研究
    color: "#6366f1"
    type: dataview
    height: 461
    half: true
    dataview:
      query: "LIST\nWHERE domain = \"头雁分子与蒋组研究\" AND !contains(topics, \"题录库·按需查\")\nFLATTEN topics AS 主题\nGROUP BY 主题\nSORT 主题 ASC"
  - name: 🧬 衰老与细胞稳态
    color: "#6366f1"
    type: dataview
    height: 453
    half: true
    dataview:
      query: "LIST\nWHERE domain = \"衰老与细胞稳态\"\nFLATTEN topics AS 主题\nGROUP BY 主题\nSORT 主题 ASC"
  - name: 🧪 PMN·AA 课题与建模方法
    color: "#6366f1"
    type: dataview
    height: 454
    half: true
    dataview:
      query: "LIST\nWHERE domain = \"PMN·AA课题与建模方法\"\nFLATTEN topics AS 主题\nGROUP BY 主题\nSORT 主题 ASC"
  - name: 📁 毕设档案·T2DM-ATM
    color: "#6366f1"
    type: dataview
    height: 391
    half: true
    dataview:
      query: "LIST\nWHERE domain = \"毕设档案·T2DM-ATM\"\nFLATTEN topics AS 主题\nGROUP BY 主题\nSORT 主题 ASC"
  - name: 🖋 我的思考·讲座·视频
    color: "#6366f1"
    type: dataview
    height: 391
    half: true
    dataview:
      query: "LIST\nWHERE domain = \"我的思考·讲座·视频\"\nFLATTEN topics AS 主题\nGROUP BY 主题\nSORT 主题 ASC"
  - name: 数据库
    color: "#6366f1"
    type: library
    library:
      viewMode: kanban
      sortBy: "modified"
      sortDesc: true
      excludeFolders:
        - "00-知识库导航"
        - "08-每日整理"
        - "09-文献追踪"
        - "_hl_crops"
        - "_ocr_tmp"
        - "导师汇报"
        - "12-知识库智能体/_备份"
        - "12-知识库智能体"
        - "99-图片附件"
        - "日常阅读与记录/读书笔记/《复杂：诞生于秩序与混沌边缘的科学》/_拆分前快照"
        - "毕设ATM建模相关/我的课题建模及湿实验"
      kanbanGroupBy: "tags"
  - name: 微信读书
    color: "#6366f1"
    type: web
    web:
      url: "https://weread.qq.com/"
---

## 🧭 课题主线（项目组）

### wb-今日焦点
id: wb-memo-focus
type: generic
（智能体每日整理时更新）
当前课题阶段：PMN · AA 代谢网络 + 头雁分子评估体系整合

### wb-上游 · 负熵靶点识别
id: wb-proj-upstream
type: generic
任务：疾病熵增规律刻画 → 负熵靶点发现与验证
- 关键词：负熵为靶、头雁分子（HGM）、多靶点最优干预
- 组内方向：SIRT3 头雁分子激活 → 线粒体复合物 I 解离 → 负熵机制（[[DOI-Engineering-2026-SIRT3头雁分子激活触发负熵机制|Engineering 2026 论文笔记]]）
- 详情见 [[前沿进展-蒋建东课题组与负熵领域]]

### wb-中游 · 负熵药效评估
id: wb-proj-midstream
type: generic
任务：以熵变为核心的药效评价体系（12 类熵度量、Δσ、安全窗）
- 关键词：熵产生率 σ、放大比 A_i、疾病态=吸引子偏移
- 立场：不用最小熵产生定理作优化目标（仅近平衡近似）
- 相关：[[蒋建东院士对生物熵项目的想法]]

### wb-下游 · 生物智能耦合
id: wb-proj-downstream
type: generic
任务：AI × 湿实验闭环（虚拟细胞 / 多组学 / UDE 灰盒建模）
- 本组课题（PMN-AA 网络 + 头雁评估）属此层
- 方法底座：[[00-毕设工作交接汇报-2026-09-18]]（T2DM-ATM 前期工作交接）
- 湿实验参照：PMN 静息/激活/衰老/NETosis 四态

### wb-项目组会议节奏
id: wb-proj-meetings
type: generic
- 年中会议：[[2026.7.26-细胞稳态与衰老北京研究中心年中工作会议-打勾讲者整理与课题启发]]
- 最新纪要：2026.8.29（存于 E:\AIDD\我的工作及文献\生物熵\会议纪要\）
- AI 负熵运算模型任务书节点：2027-09 中期考核

### wb-批注池水位
id: wb-annot-pool
type: generic
- 复杂书批注池：40/40 cleared（2026-09-17）
- 朱景德 PDF 批注池：3/3 cleared（2026-09-17）
- 水位文件：[[00-PDF批注池水位（自动生成）]]
- 新批注由每日整理自动化进池、分批处理

### wb-画布
id: wb-canvases
type: generic
- [[T2DM机制.canvas|🧫 T2DM 机制画布（毕设档案）]]
- [[2026.8.29-纲要逻辑图-刘光慧衰老研究文献梳理.canvas|🧬 刘光慧衰老研究梳理画布（衰老域）]]

## 🌀 熵与涌现 · 理论根基

## 🦢 头雁分子与蒋组研究

## 🧬 衰老与细胞稳态

## 🧪 PMN·AA 课题与建模方法

## 📁 毕设档案·T2DM-ATM

## 🖋 我的思考·讲座·视频

## 数据库

## 微信读书
