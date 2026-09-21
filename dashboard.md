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
    height: 201
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
  - name: 生物熵课题启发书单
    color: "#6366f1"
    type: sticky
---

## 🧭 课题主线（项目组）

### wb-上游 · 负熵靶点识别
id: wb-proj-upstream
type: generic
任务：疾病熵增规律刻画 → 负熵靶点发现与验证

### wb-中游 · 负熵药效评估
id: wb-proj-midstream
type: generic
任务：以熵变为核心的药效评价体系（12 类熵度量、Δσ、安全窗）

### wb-下游 · 生物智能耦合
id: wb-proj-downstream
type: generic
任务：AI × 湿实验闭环（虚拟细胞 / 多组学 / UDE 灰盒建模）

## 🌀 熵与涌现 · 理论根基

## 🦢 头雁分子与蒋组研究

## 🧬 衰老与细胞稳态

## 🧪 PMN·AA 课题与建模方法

## 📁 毕设档案·T2DM-ATM

## 🖋 我的思考·讲座·视频

## 数据库

## 生物熵课题启发书单

### 《生命是什么》 薛定谔 ｜ 科学经典
id: card-mub32422
type: generic
以物理学家视角回答“生命如何对抗热力学衰退”：负熵概念、遗传物质的非周期性晶体猜想、量子跃迁与突变。篇幅极短（约 10 万字讲稿），思想浓度极高。对研究者的价值：负熵框架的原始出处，写 Introduction 引言链（Anderson→Laughlin→“负熵为靶”）时必须回到的源头文本；但它是思想纲领而非可操作的理论，不宜从中寻找数学工具。

### 《生命是什么》 王立铭 ｜ 大众科普（仅通识价值）
id: card-mub33khi
type: generic
从物质、能量、信息、时间等角度概述生命的核心特征（自我复制、能量代谢、感知决策），行文流畅但停留在概念比喻层面，无定量内容。对研究者的价值：科学传播而非学术资源——适合刚入组、无复杂系统背景学习者的入门读物，或用于向非专业听众解释课题时的表述参考；对建模和文献工作没有直接贡献。

### 《复杂生命的起源》 Nick Lane ｜ 高质量科普（有框架价值）
id: card-mub361xa
type: generic
论证线粒体内共生是复杂生命的唯一可行路径：质子动力与能量经济学、线粒体与真核基因组的共演化、ROS 信号与衰老的线粒体理论。叙述性写作但背后有完整的原始文献体系（Lane 本人是 UCL 进化生物化学家）。对研究者的价值：全书几乎所有论点都能溯源到正式论文，适合当线索书用——沿它的引用链找到线粒体能量学（如质子泄漏、复合物 I 解偶联）的一手研究，直接服务 SIRT3–线粒体–负熵主线；注意它的部分论断（如真核起源单一事件）在学界有争议，引用时需回查。

### 《复杂》（第一推动丛书）Melanie Mitchell ｜ 高质量科普（有框架价值）
id: card-mub373wm
type: generic
复杂系统科学的结构化导览：熵与信息、计算与图灵机、遗传算法、元胞自动机、网络科学、规模律，各章配经典模型（如 Game of Life、Boids）。作者本人是该领域顶尖研究者（ santa fe 学派）。对研究者的价值：作为概念地图与检索入口极好——帮助定位“我这课题用到的方法属于哪一支、关键词是什么”；但不含数学细节，具体模型（如吸引子动力学、QSSA）仍需回教材与论文。

### 《复杂：诞生于秩序与混沌边缘的科学》 Waldrop ｜ 大众科普（科学史价值）
id: card-mub38n0r
type: generic
圣塔菲研究所创建史：Cowan、Anderson、Holland、Kauffman、Arthur 等人的群像叙事，记录“复杂适应系统”范式的诞生过程。对研究者的价值：方法论信息几乎为零，但科学史与叙事价值高——理解这个领域为什么在“秩序与混沌边缘”提出问题、各学派（物理 vs 经济 vs 生物）如何碰撞，对写课题的立论背景和 Introduction 的历史脉络有用。属于“读故事，不读技术”的一本。

### 《规模》 Geoffrey West ｜ 高质量科普（有框架价值）
id: card-mub39cg8
type: generic
异速生长标度律的系统阐述：克莱伯定律（代谢率∝M^¾）、城市与公司的规模律、生命史理论（生长率、死亡率随体重的标度）、有限时间奇点假说。数据驱动，West 是统计物理学家，本书是他数十年研究的通俗总结。对研究者的价值：异速标度与熵产生率的尺度关系（σ 随体量如何变化）是你“分尺度耦合/τ_slow·τ_fast”论证的最近类比；书中多数标度律有对应原始论文（Science、Nature 系列），可作为标度思维训练+文献线索双重用途。

### 《衰老生物学》（原书第 2 版）R. B. McDonald ｜ 专业教材
id: card-mub3d3sm
type: generic
衰老领域标准教科书：从进化论解释（一次性体细胞理论）到分子机制（端粒、氧化应激、mtDNA 突变、营养感知通路 mTOR/AMPK/IGF-1）、系统性衰老（免疫衰老、炎性老化）及干预手段（CR、senolytics）。对研究者的价值：硬核读物——是生物学侧的事实底盘，PMN 四态、炎性老化、NLRP3 等概念的标准定义与文献出处都在这里；适合当案头工具书随查随用，而非通读。
