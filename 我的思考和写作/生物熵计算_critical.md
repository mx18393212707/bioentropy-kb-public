---
type: 思考写作
title: 生物熵计算_critical
source_file: 生物熵计算_critical.docx
source_size: "53709"
created: 2026-09-19
modified: 2026-09-19
domain: 我的思考·讲座·视频
topics:
  - 思考流
tags:
  - 生物熵
  - 复杂度度量
  - 多组学
  - 动力学建模
  - 扰动预测
share: True
---


# 生物熵计算_critical

生物熵量化方法、计算及应用的争议与进展

——在既有综述初稿基础上的第二版修订稿（强化批判性分析）

说明：本文重点补强“为何不同研究可能得到方向相反的量化结果、这些结果应如何解释”的分析

摘  要

生物熵相关研究已经形成由时间序列复杂度方法、网络/信号/单细胞熵方法、关键转变检测方法以及药学和中药质量评价中的熵思想外延共同构成的方法体系。然而，随着文献数量增加，一个越来越不能回避的问题是：同一类生物学问题在不同研究中可能得到方向相反的熵结果，例如某些研究报告疾病状态下熵升高，另一些则报告熵降低；某些研究把高熵解释为系统失稳，另一些则把高熵解释为更高可塑性或更强适应性。若不对这些相反结果的来源进行方法学和生物学层面的双重分析，综述很容易退化为结果堆砌。本文在既有文献基础上，围绕“方法如何计算—结果为何相反—何种解释是可接受的”这一主线，对生物熵量化方法进行重新梳理。综述指出：时间序列熵与网络/信号熵虽然都使用 entropy 语言，但测量对象、概率结构和解释层级不同，因此其结果方向不能直接类比；即便在同一方法族内部，参数设定、预处理、采样尺度、先验网络、归一化策略、病程阶段和研究终点差异，也足以导致结论相反。因此，评价生物熵研究的关键并非简单追问“熵升还是降”，而是明确“哪一种熵、在哪个层级、对哪个对象、在何种比较框架下、以何种生物学终点进行解释”。本文认为，未来更高质量的研究应把可重复性、稳健性和跨模态验证置于与方法创新同等重要的位置。

关键词：生物熵；近似熵；样本熵；多尺度熵；信号熵；网络熵；单细胞熵；关键转变；可重复性；方法学争议

1 引言

关于生物熵的综述往往面临一种结构性困难：方法越来越多，应用越来越广，但结果之间的可比性和解释的统一性并没有同步提升。如果综述只是顺次介绍 ApEn、SampEn、MSE、network entropy、signalling entropy、single-cell entropy、SPNE 和熵权法等方法，很容易给读者造成一种错觉——仿佛这些方法共同测量着一个方向明确、层级统一的“生物熵”。

事实上，现有文献已经反复显示，结果并非如此简单。同样是疾病研究，某些研究得到“复杂度下降”，某些研究得到“网络熵升高”；同样是高熵，在生理信号中可能意味着调控结构更不稳定，在细胞状态空间中却可能意味着更高可塑性和更强干性。因此，正式综述的任务不应停留在‘有哪些方法’，而应进一步回答‘这些方法究竟计算什么、为什么会出现相反结果、哪些解释可以成立、哪些解释属于过度延伸’。

2 生物熵量化方法的基本分层

围绕量化方法本身，当前文献大致可以分为四个层面。第一层是分布与推断层，包括香农熵、相对熵和最大熵。它们主要面向概率分布、不确定性和模型约束问题。第二层是时间序列复杂度层，包括 ApEn、SampEn、PE、MSE 和 entropy of entropy，主要面向连续生理信号的规则性与复杂度。第三层是网络与状态空间层，包括 network entropy、signalling entropy、single-cell entropy、scGRN-Entropy 及其衍生方法，主要面向高维组学和系统状态可塑性。第四层是方法外延层，即熵权法及其与层次分析法、指纹图谱、网络药理学等结合的综合评价方法，其主要作用是赋权和决策，而不是直接刻画生命系统状态。

把这四类方法放在同一综述中并非没有意义，但前提是必须承认它们测量对象不同：时间序列熵方法测量的是模式延续性与多尺度动态结构；网络与信号熵测量的是状态空间、可塑性和扰动结构；熵权法则只是借用熵思想进行多指标离散度加权。若不先完成这一步分层，后文关于‘熵升高/降低’的比较将失去基础。

3 时间序列熵方法：成熟、实用，但最易被过度简化

3.1 ApEn、SampEn、PE 与 MSE 的计算对象并不相同

近似熵（ApEn）和样本熵（SampEn）的核心是模式相似性延续概率。它们本质上衡量的是序列的规则性，而不是一般意义上的‘混乱度’。因此，把它们简单翻译成“熵越高越无序”并不准确，更准确的说法应是“模式延续性越弱，规则性越低”[1-3]。

排列熵（PE）则基于序数模式频率，测量的是序模式分布的不确定性[4]；多尺度熵（MSE）通过粗粒化和多尺度分析，刻画的是复杂度在不同时间尺度上的分布结构[5,6]。这意味着，即便同一组原始信号，ApEn/SampEn、PE 与 MSE 所强调的统计特征也并不完全一致。

3.2 为什么不同研究会得到相反结果

首先，参数设定差异即可导致结果方向不同。ApEn 和 SampEn 对嵌入维数 m、容差 r、数据长度和噪声水平高度敏感。一个研究若采用较短时间窗和更宽松容差，可能会把短期波动解释为‘更复杂’；另一个研究若使用更长时间窗和更严格参数，则可能得到相反结论[3,7]。

其次，数据预处理会显著改变复杂度指标。去趋势、带通滤波、去伪迹、重采样、缺失值插补和归一化都会改变序列的局部结构。在脑电、心率和步态研究中，这种影响尤其明显，因为这些信号本身包含多个时间尺度和噪声来源。

再次，比较对象不同也会改变方向。例如在某些疾病场景中，短期不规则性增加可能使单尺度熵升高，但多尺度结构同时被破坏，从而使 MSE 在较大尺度上下降。如果研究者只报告单尺度结果或只选择部分尺度，便可能与另一项多尺度研究得出相反结论。

3.3 结果相反并不一定意味着谁对谁错

对时间序列熵方法而言，‘相反结果’并不总是研究错误，也可能反映所测量的统计特征不同。一个常见误区是把“复杂度”“规则性”“随机性”和“熵”当作完全等同的词使用。事实上，完全随机的序列在某些单尺度熵指标上可以表现为高熵，但并不意味着它具有高的生理复杂性；而健康系统之所以常被描述为“复杂”，并不是因为它最随机，而是因为它在多个时间尺度上保留了丰富且协调的动态组织[5,6,7]。

因此，当两个研究得到相反结果时，首先应检查的并不是“哪项研究更接近常识”，而是：两项研究用的是不是同一种熵、同一组参数、同一时间尺度、同一信号预处理流程，以及同一疾病阶段。

【作者观点】如果只让我挑一个最需要警惕的问题，我会选“把所有时间序列熵结果都翻译成复杂度升降”。在很多论文里，复杂度、随机性、规则性和熵值方向被混成一团，这是导致解释失真的核心来源之一。

4 网络、信号与单细胞熵方法：解释力强，但层级跳跃风险更高

4.1 signalling entropy 计算的是状态空间，而不是一般意义上的‘无序’

2014 年 signalling entropy 框架的价值，在于它把转录组表达与蛋白互作网络结合，进而把“熵”解释为细胞可达状态空间和信号潜能[8]。在这个框架下，高熵常常不对应“坏”或“混乱”，而更接近更高的可塑性、更强的干性或更广的状态可达性。这也是为什么在肿瘤和干细胞研究中，高信号熵常被视为异质性和状态灵活性的表征[9-12]。因此，若把 signalling entropy 的高低直接套用为“熵增/熵减”或“秩序破坏/秩序恢复”，便会误读其方法本义。

4.2 为什么网络熵研究中也会出现方向相反的结果

第一，先验网络差异是最直接的来源。不同研究使用的蛋白互作网络、网络规模、边权构造方式和节点过滤标准不同，所得熵值并不天然一致。这也是 2025 年 robust signalling entropy estimation 特别强调的问题：不同网络来源和校正策略本身就会显著改变结果[13]。

第二，归一化与表达映射方式会改变网络转移概率结构。某些研究使用原始表达，某些研究使用归一化后表达，某些研究还会引入局部网络校正、背景噪声修正或样本扰动项。这些差异会使‘同一算法名称’下的实际计算对象发生变化。

第三，生物学终点不同。某些研究比较癌与正常，另一些研究比较高分化与低分化、耐药与敏感、进展前与进展后。在这些不同终点下，高熵既可能表示更高异质性，也可能表示更接近临界状态；若不说明终点，仅比较‘熵高还是低’，容易造成表面矛盾。

4.3 单细胞与关键转变方法为何更难解释

单细胞熵、SPNE、SNE、edge-based relative entropy、network information gain 等方法的共同特点是，它们不满足于静态差异，而试图识别细胞命运变化、系统临界转变和前疾病阶段[11,14-19]。这类方法的解释难度更高，因为它们往往引入参考样本、扰动网络、局部子网、相邻时间点比较或伪时间轨迹。结果方向不仅受生物学状态影响，还受参照框架影响。

举例而言，某一单样本熵上升可能意味着该样本相对参考群体造成更大网络扰动；但若参考群体换成另一类样本，方向可能改变。因此，这类方法的关键不是‘熵值高低本身’，而是‘相对于谁、在什么网络和什么时间框架下比较’。

【作者观点】我认为网络/单细胞熵方法最容易发生的错误，不是算法本身不够先进，而是研究者在解释阶段把“状态空间的变化”误写成“系统本体熵的变化”。这一步跨越如果没有充分限定，会让论文看起来更宏大，但也更脆弱。

5 为什么同一生物问题会得到相反量化结果：一个辩证框架

从现有文献来看，不同研究量化结果相反，主要可归为四类原因。第一类是生物学真实差异，即不同疾病阶段、不同终点、不同组织类型和不同尺度下，系统状态变化的方向本就不同。例如，在肿瘤研究中，高信号熵可能指向更强的细胞可塑性；而在心率变异研究中，复杂度下降则可能指向调控弹性的减弱。二者并不矛盾，因为所处层级和对象不同。

第二类是统计特征差异。不同熵方法测量的不是同一种属性：有的测规则性，有的测分布不确定性，有的测网络状态空间，有的测扰动敏感性。因此，‘方向相反’有时只是因为方法关注的统计特征不同。

第三类是技术性差异，包括参数设定、信号预处理、网络来源、归一化、样本质量、批次效应和参考组选择。这一类差异在时间序列熵和网络熵研究中都非常常见，也是导致不可比结果的主要原因之一。

第四类是解释性过度。部分研究在结果讨论中把熵值变化直接翻译为“系统有序性”或“系统健康程度”的变化，而忽略了该指标本来只是在特定框架下测量某一统计特征。这类过度解释会把方法内部的有限结论扩展为系统层面的宏大判断，从而使不同研究看起来彼此冲突。

5.1 应如何对相反结果作出更稳妥解释

较稳妥的做法不是问‘到底是熵升高还是降低’，而是依次回答五个问题：第一，这项研究测的是哪一种熵；第二，它作用于哪一种数据对象；第三，比较框架是什么；第四，研究终点是什么；第五，作者是否把统计量过度解释为系统本体属性。

只有当这五个问题被说明之后，所谓“相反结果”才有可能被区分为：真实的生物学差异、不同尺度和统计特征的结果、技术性不可比，或者解释性越界。

6 疾病与药学应用：哪些结论更稳固，哪些仍需谨慎

6.1 较稳固的板块：生理信号复杂度与肿瘤状态表征

从文献成熟度看，较稳固的应用板块主要有两类。其一是时间序列熵在心血管、糖尿病、慢性呼吸系统疾病和神经退行性疾病中的应用，因为这一路线拥有相对清晰的方法谱系和较多综述型总结[20-26]。其二是 signalling entropy 与 network entropy 在肿瘤和单细胞系统生物学中的应用，因为这些研究已经围绕异质性、干性、分化潜能和药物反应形成较连续的问题链[8-19,27]。

6.2 仍需谨慎的板块：关键转变检测与方法外延

关键转变检测方法具有很强前景，但其临床转化证据仍有限。当前多数研究仍依赖特定数据集、参考群体和网络构造方式，前瞻性验证和机制实验支撑尚不足[14-19]。

药学与系统中医/中药学中的熵权法、复杂系统熵聚类和网络药理学应用，则体现了熵思想的广泛延伸，但理论地位和证据性质并不一致。例如，熵权法在中药质量评价中非常实用，却不能被当作生命系统熵测量；复杂系统熵聚类在规律挖掘中有价值，但其结果解释仍需更多验证。

【作者观点】我不认为“结果相反”本身就是坏事。真正的问题不在于相反，而在于研究者是否有能力说明‘为什么会相反’。如果一篇论文能清楚交代层级、参数、参考框架和终点，即便结果与另一篇相反，也未必缺乏价值。

7 结论与建议

综上，生物熵量化方法的真正难点，不在于是否还能继续提出新的 entropy 指标，而在于现有指标如何被更稳健地计算、更克制地解释和更严格地比较。时间序列熵方法、网络/信号熵方法和单样本/单细胞关键转变方法，分别针对不同层级的生物数据提供了有价值的分析框架，但其结果方向并不具有普遍可交换性。

因此，正式的批判性综述不应再满足于总结“哪些方法被用了”，而应进一步区分：哪些结果反映真实生物学差异，哪些来自统计特征差异，哪些受技术选择主导，哪些则源于解释越界。

未来更高质量的研究，应把参数报告、参考框架说明、网络来源说明、跨研究可比性分析和外部验证放在与方法创新同等重要的位置。

参考文献

[1] Pincus SM. Approximate entropy as a measure of system complexity. PNAS, 1991.

[2] Pincus SM. Physiological time-series analysis: what does regularity quantify? AJP-Heart, 1994.

[3] Richman JS, Moorman JR. Physiological time-series analysis using approximate entropy and sample entropy. AJP-Heart, 2000.

[4] Bandt C, Pompe B. Permutation entropy: a natural complexity measure for time series. PRL, 2002.

[5] Costa M, Goldberger AL, Peng CK. Multiscale entropy analysis of complex physiologic time series. PRL, 2002.

[6] Costa M, Goldberger AL, Peng CK. Multiscale entropy analysis of biological signals. PRE, 2005.

[7] Delgado-Bonal A, Marshak A. Approximate Entropy and Sample Entropy: A Comprehensive Tutorial. Entropy, 2019.

[8] Teschendorff AE. Signalling Entropy. Methods, 2014.

[9] West J, et al. Differential network entropy reveals cancer system hallmarks. Scientific Reports, 2013.

[10] Banerji CRS, et al. Cellular network entropy as the energy potential in Waddington’s differentiation landscape. Scientific Reports, 2013.

[11] Teschendorff AE, et al. Single-cell entropy for accurate estimation of differentiation potency from a cell’s transcriptome. Nat Commun, 2017.

[12] Ahn S, et al. Pan-cancer network disorders revealed by overall and local signaling entropy. J Mol Cell Biol, 2021.

[13] Robust signalling entropy estimation for biological process analysis. Brief Bioinform, 2025.

[14] SPNE: sample-perturbed network entropy for revealing critical states of complex biological systems. Brief Bioinform, 2023.

[15] Disease prediction by network information gain on a single sample basis. Fundamental Research, 2023.

[16] Edge-based relative entropy as a sensitive indicator of critical transitions in biological systems. J Transl Med, 2024.

[17] Detecting tipping points of complex diseases by network information entropy. Brief Bioinform, 2024.

[18] scGRN-Entropy: Inferring cell differentiation trajectories using cell entropy. PLoS Comput Biol, 2024.

[19] Detection of pre-transition phases during biological development using single-sample network entropy (SNE). npj Syst Biol Appl, 2025.

[20] Complexity Change in Cardiovascular Disease. IJBS, 2017.

[21] Decreased complexity of glucose dynamics in diabetes. AJP-Regulatory, 2014.

[22] Physiological signal entropy in patients with chronic respiratory disease: a systematic review. Eur Respir Rev, 2024.

[23] EEG entropy insights in the context of physiological aging and Alzheimer’s and Parkinson’s diseases. GeroScience, 2024.

[24] Development of a Neurodegenerative Disease Gait Classification Model Using Multiscale Sample Entropy and Machine Learning. Entropy, 2020.

[25] Entropy Analysis of COVID-19 Cardiovascular Signals. Entropy, 2021.

[26] Multiscale entropy with electrocardiograph, electromyography, electroencephalography and photoplethysmography for healthy systems, aging and disease. Biomedical Signal Processing and Control, 2024.

[27] Perturbation-Driven Entropy as a Source of Cancer Cell Heterogeneity. Trends Cancer, 2020.

[28] 生物熵在药物研究中的应用. 中国药学杂志, 2025.

[29] 熵权法在中药制剂研究中的应用概况. 中成药, 2024.

[30] 基于层次分析-熵权法的中药质量标志物量化辨识方法研究——以芍药甘草汤为例. 药学学报, 2021.

[31] 基于层次分析-熵权法和指纹图谱的杠板归质量标志物研究. 中国中药杂志, 2022.

[32] Traditional Chinese Medicine studies for Alzheimer’s disease via network pharmacology based on entropy and random walk. PLoS One, 2023.

[33] Entropy measures for quantifying complexity in digital pathology and spatial omics. iScience, 2025.

---

## 转档说明（AI 自动生成）
- 来源：`生物熵计算_critical.docx`（段落 88 个），由 convert_office_docs.py 于 2026-09-19 自动转档。
- 原件已移出库外归档：`E:\生物熵知识库工具\_备份\原文件归档-2026-09-19\我的思考和写作\生物熵计算_critical.docx`
- 图片/扫描页未导出内容，需要看图请打开归档原件；本文件不代写任何原文没有的内容。
